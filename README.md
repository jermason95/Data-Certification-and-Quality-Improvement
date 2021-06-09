# Data Certification and Quality Improvement

Since the success of the Portfolio Central Data Quality project (link), a new intitative at Barings was started called "Trust your Data", which involved standardizing other datasets and scaling out the Microsoft PowerBI dashboard. 


### About
The purpose of this project is to set up data standardization and monitoring by a process known as data set certification. This is the highest level of data governance that can be applied to a data set. It builds upon the artifacts necessary to authorize a data set to greatly expand our knowledge about the data.  It not only captures where the data lives and what it means, but also answers questions such as:

•	What does the data look like?  (data profiling)

•	How did the data get there? (data lineage)

•	Is the data fit for purpose? (data quality measurement and scorecards)



#### Setup 
Given I was tasked to scale out the data quality model from one software to ultimately all datasets at Barings, first it was crucial to setup the standard operating procedure/workflow. This included providing technical documention of the coding procedure (i.e. shell scripts of the drivers and loops) and updating the lkp tables and relationships in powerbi for optimal scalability. 

Here is an outline of the designed workflow
![image](https://user-images.githubusercontent.com/85593608/121294851-12d09b00-c8bc-11eb-8acf-791306d07253.png)


#### 1. What does the data look like? 
    Having the correct terminolgy is the first key to having an accurate, and more importantly useful data

In a company that holds over 25,000 assets and stores data on companies, clients, properties, indexes, and countries, ensuring everyone is on the same page about what a term means is crucial. Especially what it means in a relational contex.To solve this problem, I worked with the Data Steward team to learn the data profiling tool Collibra, to upload important information on the data we are checking for data quality. This will ensure users know where they should go to consume data and exactly what that data means.
This includes: definitions, domains, data owners, responsible data stewards, etc.
 
 ![image](https://user-images.githubusercontent.com/85593608/121295233-af933880-c8bc-11eb-929b-9bca7a71ed57.png)
 


 



2. •	How did the data get there? (data lineage)
	For any big enterprise, finding where you data is can be a daunting task

In order to ensure a dataset is used properly knowing how to easily access your data is crucial. Not only from a business decision making standpoint, but to ensure that an audit trail can be followed to comply with government regulation. Many times datasets overlap, so is crucial to have a sorce of truth in discrepancies. Without a source of truth admins are at a much high risk to report inaccurate data, which negatively impacts business decisions 

Through our data matching we were able to identity which database, application, file, table, and even column name all of the fields. 





Location Alignment Identifcation:

![image](https://user-images.githubusercontent.com/85593608/121295111-82468a80-c8bc-11eb-9c35-e6e49b5d4c09.png)

Data Match Correlation:

![image](https://user-images.githubusercontent.com/85593608/121295172-968a8780-c8bc-11eb-9f8a-ad7aa49863c9.png)
  



4. •	Is the data fit for purpose? 
	Data profiling, which can also be done through Collibra, examines each column within a data set and compiles facts about it – data type, distribution of data values, maximums, minimums, and means.  Profiling tells users what the data looks like without judging whether it is good or bad.  

However, to judge if it's good or bad, an expansion of the PowerBi Dashboard. Details on the dashboard can be seen here.

ESG (Environmental, Social, Governance) Scores
SFR () 
can now be seen in the dashboard.
Screenshots.
![image001 (1)](https://user-images.githubusercontent.com/85593608/121298489-f7688e80-c8c1-11eb-9051-ae9bdfbaa52a.png)





Correlation metrics can be quickly derieved multiple terms drilled by investment teams,
groups of terms.



5. analyzing controls

•	Regulatory, Contractual, and other Obligations: Do we have adequate controls over our data with respect to our regulators, vendor contracts, and corporate ethos?  Some examples:
•	
•	Appropriate access: Are the data values only accessible by users that have a right to see them?
•	Data retention: How long can we keep the data?
•	Distribution: Are we allowed to distribute the data we receive and if so, are there limitations?  
•	Ethical sourcing: Is the data we are using collected in an ethical manner?
•	Appropriate usage: Are we using the data for the intended purpose?  If not, does this new use case create any contractual or ethical concerns?





