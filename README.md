# Off-Campus Student Housing
Authors: Iris Ren and Rianna James
Course: CS506
Semester: Fall 2025

# Core Question: 

Can we identify distinct groups of landlords or neighborhoods based on their building property violation patterns?

This will be helpful for students who need to determine which landlords, neighborhoods, and adresses get the most violations for when they need to pick housing. 

# Background/Context:

In the City of Boston, there are over 96,000 undergraduate and over 65,000 graduate students in colleges and universities since 2023. In a Student Housing trends report in 2023, 51% of undergraduate students lived off campus, with the majority (~64.4% of off-campus students) not living at home. On campus students are more likely to receive direct security services from campus and Boston police in addition to guaranteeing living conditions and housing security, as opposed to off campus students who may not receive the same level of services and may deal with issues with landlords or difficult neighborhoods. The City of Boston is interested in having a more cohesive understanding of Student off-campus housing living and financial experiences, conditions, and safety to better employ resources to support certain areas and to publicize the conditions for better accountability.

As students, creating a useful tool that could synthesize the conditions and reports on available off-campus housing in addition to where many fellow students tend to live would be extremely helpful for searching for reliable, affordable, and safe housing during the school year, summer, and even post-graduation.


# Clear goal(s) (e.g. successfully predict the number of students attending lecture based on the weather report).

Synthesize data from housing violation and condition datasets and higher education off-campus reports to better understand where students live, what percentage of renters are students in each district, and the housing conditions students experience. Successfully visualize the growth of off-campus housing student living patterns and living conditions based on historical data on property and building conditions and violations.


# What data needs to be collected, and how you will collect it (e.g. scraping xyz website or polling students).

The data that will be collected is the building and property violations, student housing data, property assessment data, and Boston neighborhood boundaries. We will collect this data from the following sources: the Boston government sites and a student housing Google sheet provided by Spark.  


# How you plan on modeling the data (e.g. clustering, fitting a linear model, decision trees, XGBoost, some sort of deep learning method, etc.).

For Modeling, we decided to use K-means to visualize the clusters of student populations off campus and housing violations throughout the years.

# How do you plan on visualizing the data? (e.g. interactive t-SNE plot, scatter plot of feature x vs. feature y). 
	
Geographic maps of the districts with filters for housing violation categories, including a compiled filter/layer that emphasizes areas or buildings that have the most housing violations/issues perhaps with size or color scales for points. Having a consistent geographic map and key for filters would also help with creating timelines over the past few years or overall growth since the base year of 2013.
If time permits, an interactive map that could include adding and removing these filters and zooming into the regions and areas to see specific addresses. Furthermore, synthesizing multiple time snapshots of data could be useful, to see how over time if certain neighborhoods increase in student populations more than others and how that does or does not correspond with housing violations or issues in that area.

Bar graphs could also be used for counts of housing violations within certain neighborhoods as it relates to percentages of tenants who are students. 

Further studies could include pairing qualitative data online or in semi-structured interviews/surveys to understand the tradeoffs, benefits, and barriers that different students who are living off-campus deal with most. Understanding why students are choosing off-campus housing over on-campus housing could be extremely helpful for higher education institutions within Boston when considering how they structure their Housing systems and could be helpful for new students with similar backgrounds or priorities who are considering their housing for the school year.


# What is your test plan? (e.g. withhold 20% of data for testing, train on data collected in October and test on data collected in November, etc.). 

Our plan will be the following: 

Split the data set to have 60% used for training the model and 40% to test the model 

Weekly Meetings will be on Sunday, at 2 PM or sometime in the afternoon as appropriate with Iris Ren and Rianna James.

Timeline of when each component of the project will be worked on/ completed: 

Data Analysis, Literature Review:  By September 30th
* Gathering useful Datasets and storing them in the Github once finalized, reading at least 2-4 articles on Student Off-Campus Housing/Housing in general
* Creating the shared Github repository
* Start to become familiar with Python tools needed for data cleaning and compilation (Numpy)
* Make adjustments to goal of project as needed based on dataset availability/completeness and feedback from Course Staff

Data preprocessing, cleaning, and feature Extraction:  By October 13th
* Clean out null values 
* Remove irrelevant columns 
* Maintain a complete log within shared Github repository of progress

Data visualization:   By October 20th
* Create preliminary bar graph counts for student renter counts and housing violations
* Create preliminary geographic maps with student counts and housing violation filters and counts visualized
* Maintain a complete log within shared Github repository of progress
* 5-min youtube presentation
* Create a detailed Report including the Midterm Report details

Model training, deployment, and evaluation metrics( ???):  By October 27,  November + December 12 
* Create preliminary model and fitting it to the data 
* Evaluate model performance 

Important Deadlines: 
* Midterm report: October 27th
* Final presentation: December 12th 

