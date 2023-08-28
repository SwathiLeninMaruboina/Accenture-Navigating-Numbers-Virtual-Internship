## Accenture Navigating Numbers Virtual Internship
#### Bring data to life with analytics & visualization

### Internship Introduction:
This is a virtual internship program case study with the company, Accenture North America. This program is hosted through the site called "Forage". This internship helps you to learn data basics such as data cleaning, modelling, visualization and storytelling.

### Internship Company:
![](https://miro.medium.com/v2/resize:fit:828/format:webp/1*JiN07MFVNNlJoA-_KkI7wA.png)

Accenture is a leading global professional services company that helps the world's leading businesses, governments and other organizations build their digital core, optimize their operations, accelerate revenue growth and enhance citizen services - creating tangible value at speed and scale.

### Project File:
All files related to this internship can be accessible [here](https://github.com/SwathiLeninMaruboina/Accenture-Navigating-Numbers-Virtual-Internship)

### Certificate:
![Certificate of Completion](https://github.com/SwathiLeninMaruboina/Accenture-Navigating-Numbers-Virtual-Internship/blob/main/certificate.png)

### Scenario:
The client company is Social Buzz. Social Buzz was founded by two former engineers from a large social media conglomerate, one from London and the other from San Francisco. Social Buzz emphasizes content by keeping all users anonymous, only tracking user reactions on every piece of content. There are over 100 ways that users can react to content, spanning beyond the traditional reactions of likes, dislikes, and comments.
They have scaled quicker than anticipated and need the help of an advisory firm to oversee their scaling process effectively. Due to their rapid growth and digital nature of their core product, the amount of data that they create, collect and must analyze is huge. Every day over 100,000 pieces of content, ranging from text, images, videos and GIFs are posted. All of this data is highly unstructured and requires extremely sophisticated and expensive technology to manage and maintain.
To start our engagement with Social Buzz, Accenture is running a 3 month initial project in order to prove to them that we are the best firm to work with. They are expecting the following:
- An audit of their big data practice
- Recommendations for a successful IPO
- An analysis of their content categories that highlights the top 5 categories with the largest aggregate popularity

### Dataset Summary:
The client provided 3 datasets:
- Content
- Reactions
- ReactionTypes
- 
Here is the summary of the contents and columns from the datasets:
#### Content
-  **ID:** Unique ID of the content that was uploaded (automatically generated)
-  **User ID:** Unique ID of a user that exists in the User table
-  **Type:** A string detailing the type of content that was uploaded
-  **Category:** A string detailing the category that this content is relevant to
-  **URL:** Link to the location where this content is stored
  
#### Reaction
-  **Content ID:** Unique ID of a piece of content that was uploaded
-  **User ID:** Unique ID of a user that exists in the User table who reacted to this piece of content
-  **Type:** A string detailing the type of reaction this user gave
-  **Datetime:** The date and time of this reaction
 
#### ReactionTypes
-  **Type:** A string detailing the type of reaction this user gave
-  **Sentiment:** A string detailing whether this type of reaction is considered as positive, negative or neutral
-  **Score:** This is a number calculated by Social Buzz that quantifies how "popular" each reaction is. A reaction type with a higher score should be considered as a more popular reaction

#### Client 'Social Buzz' provided the Data Model:
![image](https://github.com/SwathiLeninMaruboina/Accenture-Navigating-Numbers-Virtual-Internship/assets/111370672/6628d543-eebd-4264-8549-48992fc00946)

### Task 1: Project Understanding:
A data analyst sits between the business and the data.

- One of Accenture's Managing Directors, Mae Mulligan, is the client lead for Social Buzz.
- She has reviewed the brief provided by Social Buzz and has assembled a diverse team of Accenture experts to deliver the project.
- Mae has scheduled a project kick off call with the internal Accenture project team for tomorrow morning.
- About Client: [Social Buzz](https://cdn.theforage.com/vinternships/companyassets/T6kdcdKSTfg2aotxT/MsAqi7SNLKw3C6LAr/1664296994014/Data_Analytics%20Client%20Brief.pdf)
  
#### Task for Accenture:

- Client's Problem that Accenture is tasked to address: The client has reached a massive scale within recent years and does not have the resources internally to handle it.
- Three requirements that Accenture is tasked to fulfil: Audit of big data practice, recommendations for IPO, analysis of popular content

  
### Accenture Project Team:
![image](https://github.com/SwathiLeninMaruboina/Accenture-Navigating-Numbers-Virtual-Internship/assets/111370672/f88a4e81-f874-4a08-ac90-6e0b464d3bf6)

#### Key roles and responsibilities of a Data Analyst
A data analyst sits between the business and the data.

What do we mean by that?

- The Business refers to the client and your internal team members who won't be involved in detailed data analysis.
- They rely on your analysis to make strategic business decisions.
- Importantly, not everyone will have a strong understanding of data. Your job is to communicate your data findings simply and clearly for everyone to understand.
- The Data refers to the relevant data sources that you will clean, process, and use to generate interesting insights for the business.

As a Data Analyst at Accenture, you'll get to work across a range of different clients and projects. This keeps things interesting, as there are always new problems to solve and new topics to learn about.

However, our clients often want accurate results in a tight timeframe. The pace of work is fast and you'll need to get up to speed on new projects as quickly as possible.

Now you know a bit more about the role, let's get back to the project with Social Buzz.
#### Task for Data Analyst :
Analysis of sample data sets with visualizations to understand the popularity of different content categories.

In short, the client wanted to see "An analysis of their content categories showing the top 5 categories with the largest popularity".

### Task 2: Data Cleaning and Modeling
- Often you won't need all these datasets to find what you're looking for.
- So, the first step is to use this data model to identify which datasets will be required to answer your business question - which is to to figure out the top 5 categories with the largest popularity.
- After Analysis we got data sets needed to complete analysis:
1. Reaction Score(score is used to quantified the popularity)
2. Content ID
3. Reaction Types
4. Content type
5. Category
#### Data Cleaning:
- removing rows that have values which are missing,
- changing the data type of some values within a column, and
- removing columns which are not relevant to this task.
- Think about how each column might be relevant to the business question you're investigating. If you can't think of why a column may be useful, it may not be worth including it.

After data cleaning as a result we have 3 cleaned data sets i.e., Reaction Types, Reactions and Content.

#### Data Modelling:
In final dataset we have combined Reaction Types, Reactions and Content into a single spreadsheet.
After modelling data as a result we have a spreadsheet with cleaned dataset and top 5 categories.

### Task 3: Data Visualization and Storytelling
- From a total of 16 different content categories, the top 5 contents include animals, science, healthy eating, technology, and food.
 ![](https://miro.medium.com/v2/resize:fit:828/0*AfREiV0ipyh2WOlP)
- In terms of percentage share of popularity amongst the top 5 content categories, animals has a popularity percentage share of 21.5%, followed by science with a popularity percentage share of 20.4%, healthy eating and food are in 3rd and 5th place respectively, with each having a popularity percentage share of 19.5% and 19.3% respectively.
 ![](https://miro.medium.com/v2/resize:fit:828/0*Opp13lTVJ0XPJpXN) 
- Looking at the total number of posts by category we can see that the top 5 content categories are in sequential order with respect to the previous two visuals. animals tops the chart with a total of 1,897 posts, followed by science which has a total of 1,796 posts. In last place is public speaking with a total post of 1,217.
![](https://miro.medium.com/v2/resize:fit:828/0*twC-TK6vqp3vX9Sd)  
- Looking at the total number of posts by content type, photos have the highest posts with a total of 6,589 posts, followed by videos with a total of 6,245 posts, in third place is GIFs with a total of 6,079 posts, and lastly audio with a total of 5,660 posts.
![](https://miro.medium.com/v2/resize:fit:828/0*Esdj2PqqEgpqD_uM)  
- Looking at the total number of posts by sentiment type, we have 13807 positive posts, 7695 negative posts and 3071 neutral posts.
![](https://miro.medium.com/v2/resize:fit:828/0*wieOCgXsWGlxHQ_G)  
- May is the month having the highest number of posts with a total of 2,138 posts, this shows that people post a lot during this period. Other high. Though there is a huge drop in total posts in the month of February with a total of 1,914 posts. From this chart we can see that posts by month undulating (rises and falls).
![](https://miro.medium.com/v2/resize:fit:828/0*Q1yizjpS8JZeGr_j)  
- Looking at the total number of posts by reaction type, heart have the highest posts with a total of 1622 posts, followed by scared with a total of 1,572 posts, in third place is peeking with a total of 1,559 posts.
![](https://miro.medium.com/v2/resize:fit:828/0*C4wBVIw67tz-3tKa)

#### Final Dashboard:
![](https://miro.medium.com/v2/resize:fit:828/format:webp/1*Mnj6vDI98h8pqnnoB0U2-Q.png)

### Task 4: Present to the Client
Present your powerpoint presentation to the client and deliver the insights of your analysis [click here to see the presentation.](https://drive.google.com/file/d/1VMY-uX9w76sINur_7f5A6S-HTRnnyj3E/view?usp=drive_link)

#### Insight:
In the top 5 categories food is the common theme with 'Healthy Eating' ranking the highest. This is the indication to the audience within the user base. We suggest you could use this insight to create a campaign and work with healthy eating brands to boost user engagement.
