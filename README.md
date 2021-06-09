# Data Certification and Quality Improvement

Since the success of the Portfolio Central Data Quality project (README.md), a new intitative at Barings was started called "Trust your Data", which involved standardizing other datasets and scaling out the Microsoft PowerBI dashboard. 


### About
The purpose of this project is to set up data standardization and monitoring by a process known as data set certification. This is the highest level of data governance that can be applied to a data set. It builds upon the artifacts necessary to authorize a data set to greatly expand our knowledge about the data.  It not only captures where the data lives and what it means, but also answers questions such as:

•	What does the data look like?  (data profiling)

•	How did the data get there? (data lineage)

•	Is the data fit for purpose? (data quality measurement and scorecards)



### Setup 
Given I was tasked to scale out the data quality model from one software, Portfolio Central, to ultimately all datasets at Barings, first it was crucial to setup the standard operating procedure/workflow. This included providing technical documention of the coding procedure (i.e. shell scripts of the drivers and loops) and updating the lkp tables and relationships in powerbi for optimal scalability. 

Here is an outline of the designed workflow:

![image](https://user-images.githubusercontent.com/85593608/121294851-12d09b00-c8bc-11eb-8acf-791306d07253.png)


#### 1. What does the data look like? 
    Having the correct terminolgy is the first key to having an accurate, and more importantly useful dataset

In a company that holds over 25,000 assets and stores data on companies, clients, properties, indexes, and countries, ensuring everyone is on the same page about what a term means is crucial. Especially what it means in a relational contex. To solve this problem, I worked with the Data Steward team to learn the data profiling tool Collibra and uploaded important information on the additional datasets. This will ensure users know where they should go to consume data and exactly what that data means.
This includes: definitions, domains, data owners, responsible data stewards, etc.
 
 ![image](https://user-images.githubusercontent.com/85593608/121295233-af933880-c8bc-11eb-929b-9bca7a71ed57.png)
 


 



#### 2. How did the data get there? (data lineage)
	For any big enterprise, finding where you data is can be a daunting task

In order to ensure a dataset is used properly, knowing how to easily access your data is crucial. Not only from a business decision making standpoint, but to ensure that an audit trail can be followed to comply with government regulation. Many times datasets overlap, so is crucial to have a source of truth if (when) discrepancies occur. Without a source of truth admins are at a much high risk to report inaccurate data, which negatively impacts business decisions.

Through our data matching we were able to identity which database, application, file, table, and even column name all the fields are located in for the addtional datasets.





Location Alignment Identifcation:

![image](https://user-images.githubusercontent.com/85593608/121295111-82468a80-c8bc-11eb-9c35-e6e49b5d4c09.png)

Data Match Correlation:

![image](https://user-images.githubusercontent.com/85593608/121295172-968a8780-c8bc-11eb-9f8a-ad7aa49863c9.png)
  



#### 4. Is the data fit for purpose? 

Data profiling, which can also be done through Collibra, examines each column within a data set and compiles facts about it – data type, distribution of data values, maximums, minimums, and means. Profiling tells users what the data looks like without judging whether it is good or bad.  

However, to judge if it's good or bad, an expansion of the PowerBi Dashboard was created. Details on the functionaliy of the dashboard can be seen here (link)

The two additional datasets at this point are:

ESG (Environmental, Social, Governance) Scores

![image](https://user-images.githubusercontent.com/85593608/121302165-46fd8900-c8c7-11eb-9f69-8e60ff3336b9.png)

EU Regulatory reporting such as RSFDR (Sustainable Finance Disclosure Regulation)
![image](https://user-images.githubusercontent.com/85593608/121302315-83c98000-c8c7-11eb-907e-711775666911.png)


Here is an example how you can quickly derive correlation metrics by drilling down on a portfolio name.
![image001 (1)](https://user-images.githubusercontent.com/85593608/121298489-f7688e80-c8c1-11eb-9051-ae9bdfbaa52a.png)





### What I Learned

**Data Analysis Tools** → Collibra, T-SQL

**Data Visualization Tools** → Microsoft PowerBI DAX, Dynamic Functions

**Soft Skills and Critical Thinking** → Technical Documentation, Data Regulation, Best Practices




