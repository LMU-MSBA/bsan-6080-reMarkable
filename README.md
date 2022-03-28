# bsan-6080-reMarkable
![alt text](tablet.jpg)

# Business Understanding
## Business Objective: 
### Background: 
reMarkable is a Norwegian-based tablet company that was founded in early 2014. It produces a specialized electronic-ink tablet whose main focus is to replicate the experiences users have with paper such as writing, drawing, and reading. reMarkable position intersects three markets; smart tablets, physical book substitutes, and drawing tablets, therefore allowing the company to compete with a diverse array of companies from well-known brands such as Apple’s iPad and Amazon’s Kindle to smaller companies such as SuperNote and Boox. 

## Business Objectives: 
### Product Design: 
The first business objective is to identify specific and actionable customer needs and pain points to inform and aid the engineering department in designing our next product. reMarkable is currently selling the second iteration of its tablet. There is sufficient consumer feedback from the company's official feedback channels as well as on third-party websites such as Amazon and Twitter, which is packed with crucial user-generated content (UGC) waiting to be extracted and implemented. 

### Marketing:
The second objective is to formulate our marketing processes, which consist of Segmentation, Targeting, and Positioning. 
First we need to determine how our current and potential customers are segmented which will help us identify specific attributes within the segments. This process is crucial for us to understand our customers and effectively target the audience interested in our products. Our team will use the information from our customer segmentation to determine how customers perceive our brand and products, and strategically reposition ourselves to fit the type of brand we want to be. 

### Business Success Criteria
In the short term, our success criteria is to increase product sales by 20% and achieve higher customer satisfaction. In the long run, we hope to help design a better reMarkable3 where the success will be measured by the product’s sales and customer feedback. 


## Assess Situation: 
### Inventory of resources
### Personnel:
We have a diverse team of six well-rounded individuals who possess strong business understanding. Each person brings unique value to the project. 
* Alena: Has experience using CRISP-DM and is the project owner responsible for the overall project planning.
* Rana: Has deep marketing understanding, fluent in Norwegian language, and has connections with individuals in Norway (possibly with the CEO of reMarkable).
* Krissy: Has strong marketing understanding and an understanding of US local markets.
* Oliver: Is a data mining expert and has strong presentation skills.
* Daniel: Has extensive work experience in business.
* Arshak: Is a data mining expert.
We also are privileged to have four LMU professors actively helping us in the process.
 
### Data:
We have developed programming codes and have obtained the keys for data collection with API’s such as Amazon API, Twitter API, Yelp API and Web scraping.
We strive to obtain insight sales and revenue data from reMarkable, if possible.
 
### Computing resources:
We have 6 laptops (2 Macs, 4 Windows), 1 PC, access to LMU Computer Labs and VDI. In addition, we can utilize cloud sources such as Google Colab, Deepnote, AWS, etc.
 
### Software:
We will be using Colab and Deepnote for Python. We expect to use libraries such as Axesso API, Request API, Pandas, Tweepy API, etc. Most are either free or will be included in the budget.
For visualization purposes we might be using Tableau with the student account.
 
### Requirements, assumptions, and constraints
Schedule of completion:
The schedule of completion is based on the sprints scheduled by the professor and is fully documented in the planning section completed by Alena.
We use Trello to manage time and tasks.
 
### Comprehensibility:
We assume our audience has a basic understanding of technical aspects of our project such as Machine Learning, API’s, Jupyter Notebooks, etc. With this assumption, we will present our findings and results to stakeholders in a language that would be understood by an average college educated person. 
We will use simple graphs and explanations in our presentation together with Q&A’s and references for complex terms.
 
### Quality of results:
We assume that UGC for reMarkable contains useful customer insights and that these insights can be extracted using our data extraction methods. This assumption is based on articles in scientific literature and our experiences with similar projects.
As an example of such article please refer to Identifying Customer Needs from User-Generated Content
Artem Timoshenko, John R. Hauser
 
### Security:
We believe that security is not a major issue since most of the collected data is publicly available on Social Media and Amazon.
If we are lucky enough to get insight data through Rana’s Norwegian connections, we will sign NDA and follow all necessary safety protocols including but not limited to Password encryption, Separate accounts for the project (non-personal), Limiting the circle of consultants (all sign NDA). 

### Legal issues:
In addition to the aforementioned statements, we believe that on the rights of an Educational Project we can execute our project plan fully with no legal confrontations with the company.
Make sure that you are allowed to use the data
We are allowed to use the data as long as we have the appropriate keys for API’s. For example, when using Twitter Academic API, we need to properly describe our project to Twitter.
 
### Risks and contingencies
API’s might stop working (recently happened with Facebook API). In the event that our API’s stopped working, we will change our data source accordingly. For example, instead of using Twitter we can use Reddit, Instead of Amazon reviews, Blog Posts.
Some of our teammates might get too busy with their jobs and not be able to meet their personal deadlines for sprints. In this situation, we will rearrange tasks accordingly and delegate the workload to third parties. We will keep each other accountable and be transparent with our stakeholders in the process of our project. 
If we are not able to extract customer needs from UGC we will then find other ways to generate insight from the company either using different data sources or conducting a different type of analysis. 
The company might get acquired and lose its independence and might not need our project anymore. We will make sure that this is accounted for in the contract (theoretically) so that the team is paid off. In this event, we will be pitching our project to the company who acquired reMarkable.
And many more scenarios. In any situation we would reassess the situation and move forward with the best understanding of the problem at the time.
 
## Terminology
### Business Understanding

Customer Segmentation: Identifying groups of customers based on their characteristics.

Targeting: Choosing customers segments to target (act upon). Designing marketing strategies for each chosen customer segment.

Positioning: Relates to where we position our product in the mind of the customer. This part is crucial especially for our drawing tablet/book product since there are many similar products on the market that have slightly different combinations of attributes and benefits.

Product Attribute: A physical characteristic of a product. For example: black and white E-ink display.

Customer Benefit: A benefit that a customer gets that is related to a Product Attribute. For example: thanks to the E-ink display, customers enjoy less strain on their eyes and can read and draw even outside on a sunny day.
 
### Data Mining
API: application programming interface is used to connect programs with other programs. In our case it will be used to connect Python or Jupyter Notebook to Twitter and Amazon to get the data programmatically as opposed to manual scraping.
 
Word Embedding: A process of converting words into numbers in a way that reflects the meaning of the words. This allows the computer to perform analytical operations on these words (reviews), particularly to extract customer needs.
 
## Costs and benefits
Construct a cost-benefit analysis for the project, which compares the costs of the project with the potential benefits to the business. The comparison should be as specific as possible. For example, use monetary measures in a commercial situation:
Total Costs: $32,526
Pay for personnel:
6 people * $50/h * 10h/week * 8 weeks = $24,000
Cost of software:
Tableau License if not provided by LMU: $70 per month * 6 people * 2 months = $840
Axesso API for Amazon Reviews: $90 per month * 2 months = $180. (might increase to $700 if we need more data, there are different plans)
30% overhead for the budget, in case of urgent costs not accounted for here.
 
## Expected benefits:
It is difficult to directly estimate the benefits for the company if the project is successful.
Some of the possible benefits include:
20% increase in sales.
10% increase in market share.
Average 0.8 points increase in customer satisfaction (based on reviews)
Better product. At least 2 product improvements based on customer needs.
Better positioning. At least 2 new developments of distinctive assets for the product and the company.
Ability to reuse our methodology for future research and improvements.


## Determine Data Mining Goals:

### Data Mining Goals
Our main data mining goal is to obtain insightful data which will help us achieve our aforementioned business objectives. 
To achieve this, we must implement ETL (extract, transform, and load) on all of the different sources of information. We will most likely not be using clean data since we will obtain most data from the original source, UGC. This makes it even more crucial to properly inspect the raw data and implement ETL in order to have usable data. 
In addition to applying ETL on each data source independently, we must ensure that we have uniformity across the different sources. One of our business goals is to identify customer needs and since this is not to be done in silo based on the different sources, but rather as an aggregate study, we must be able to utilize all of our data sets together. Having clean and uniform data will allow us to use the data set to carry out our investigation. Another business goal is to inform the marketing STP (Segmentation, Targeting, & Positioning). This process will require the analysis of the aggregate data therefore all data must be joined together to form one large data set where we will use it for our analysis. 

### Data Mining Success Criteria
In order to measure the success of our data mining we must set certain criterias. 
The most basic is “is this dataset usable?”. This can be determined by making sure our dataset will load into the chosen software (Google Colab, Deepnote…). If it is not formatted so that it is usable in the desired platform, then the data has no value to this project. 
Another criteria in determining the success of our data mining, is whether we can extract at least 2 new customer needs and/or pain points from the analyzed UGC. If we are unable to extract this information from the dataset, we will need to gather additional data from the same sources or different platforms. 
Another criteria is making sure that we are able to properly create an STP model from our dataset. We should be able to segment our audience so that the marketing team can target new customers. Should we not have sufficient information to segment our audience, we would need to obtain additional data. 

## Produce Project Plan:

In order to complete our desired goals for this project, we decided to utilize Agile methodologies to assist with project management. Specifically, we will be using Trello to assign tasks to ensure we hit our various sprint goals as well as to keep all project related material in one place. Furthermore, we will use WhatsApp for any necessary quick and instant messaging. Lastly, the team has agreed to have a weekly meeting every Tuesday at 5:00 P.M. until the completion of our project, so that we can communicate where everyone is with their assigned tasks and keep the team on the same page at various points throughout the project. Down below is more information on the specifics of each Sprint and how we plan to reach these various milestones.

* Sprint 0: Project Proposal (Expected Completion Date: 03/15/2022)
	
	Deliverables: 
Project proposal
Job post

This Sprint has been completed and a GitHub Repository for the project has been created.

* Sprint 1: Business Understanding (Expected Completion Date: 03/29/2022)
	
	Deliverables: 
Documented CRISP-DM Business Understanding Tasks and Outputs
Create and Update Trello Board

In order to complete this sprint all team members must first create Trello accounts, so that all members have access to a central Trello board for this project. Additionally, a meeting will be necessary to breakdown and discuss specific tasks that need to be done to complete Business Understanding CRISP-DM documentation.

* Sprint 2: Data Understanding (Expected Completion Date: 04/12/2022)
	
	Deliverables: 
Documented CRISP-DM Data Understanding Tasks and Outputs
Data Collection Jupyter Notebook (data_collection.ipynb)
Exploratory Data Analysis Jupyter Notebook (eda.ipynb)
Update Trello Board

As we plan to analyze User Generated Content from Twitter, we plan to use Jupyter Notebooks and a simple Twitter API calls to extract the data (tweets) that will be necessary for the project. Additionally, a meeting will be necessary to breakdown and discuss the specific tasks that need to be done to complete Data Understanding CRISP-DM documentation.


* Sprint 3: Data Preparation, Modeling, Evaluation (Expected Completion Date: 04/26/2022)
	
	Deliverables:
Documented CRISP-DM Data Preparation, Modeling, and Evaluation Tasks and Outputs
Data Preparation Jupyter Notebook (data_preparation.ipynb)
Machine Learning Models Jupyter Notebook (models.ipynb)
Machine Learning Models Saved as Pickle Files
Update Trello Board
AWS Database Connection Details (aws_db_project_name.txt)

For Sprint 3, we will continue to utilize Jupyter Notebooks for both prepping our data for the model and to run the BERT model that we plan to use to analyze the Tweets. Additionally, we plan to run K-Means Clustering analysis that will also be done with Python to run a thorough marketing analysis on the data that will allow us to segment, target, and position ReMarkable. According to the model assessment, we will revise parameter settings and tune them for different iterations. We will continue to model until we believe we have found the best model and clustering. All iterations (revisions and assessments) will be documented in Trello.

This workload may seem unachievable for one Sprint, but with the BERT model already available to us, this will likely be possible to complete in a timely manner. Lastly, a meeting will be necessary to breakdown and discuss the specific tasks that need to be done to complete Data Preparation, Modeling, and Evaluation CRISP-DM documentation.

* Sprint 4: Deployment (Expected Completion Date: 05/06/2022)
	
	Deliverables:
Documented CRISP-DM Deployment Tasks and Outputs
Dashboards
Machine Learning API URL Endpoint
Slides (presentation.pdf)
Update Trello Board
Peer Evaluation
Q&A 

For the final sprint, we will use the Matplotlib package in Python to create visualizations as well as Tableau to create dashboards of our findings. We will also create a presentation deck on Google Slides and prepare for our final presentation. Lastly, a meeting will be necessary to breakdown and discuss the specific tasks that need to be done to complete the Deployment CRISP-DM documentation.




