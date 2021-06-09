![image001 (1)](https://user-images.githubusercontent.com/85593608/121298475-ef105380-c8c1-11eb-829d-c19b65795801.png)
# Data Certification and Quality Improvement

Since the success of the Portfolio Central Data Quality project (link), a new intitative at Barings was started called "Trust your Data", which involved standardizing other datasets and scaling out the Microsoft PowerBI dashboard. 


### About
The purpose of this project was to set up data standardization and monitoring by a process known as data set certification. This is the highest level of data governance that can be applied to a data set. Certification ensures that we know as much as we can know about the data.  It builds upon the artifacts necessary to authorize a data set to greatly expand our knowledge about the data.  Like authorization, it captures where the data lives and what it means, but also answers questions such as:

•	What does the data look like?  (data profiling)

•	How did the data get there? (data lineage)

•	Is the data fit for purpose? (data quality measurement and scorecards)



#### Setup 
now given taking a model and scaling out had to build a workflow model. technical documention. and shell scripts. (add pictures. driver loop) lkp table.alter relations on powerbi loop in terms. etc.

scaling out---shell scripts needed to optimize workflow as new systems added-documentation technical
![image](https://user-images.githubusercontent.com/85593608/121294851-12d09b00-c8bc-11eb-8acf-791306d07253.png)


#### 1. What does the data look like? 
    Having the correct terminolgy is the first key to having an accurate, and more importantly useful, dataset

Barings adopted the data profiling tool Collibra, which will let users know where they should go to consume data and exactly what that data means.
This includes:
definitions
domains
data owners
reposible data steward etc
 
 ![image](https://user-images.githubusercontent.com/85593608/121295233-af933880-c8bc-11eb-929b-9bca7a71ed57.png)
 
In a company that holds over 25,000 assets and stores data on companies, clients, properties, etc. across eight different software- requires that everyone is on the same page about what a term means, especially what it means in a relational contex.

 This is often a process of discovery to identify competing sources of the truth, analysis of the data to determine overlap, and decision-making with Data Owners to identify a single source of truth if there are multiple potential sources. 

 



2. •	How did the data get there? (data lineage)
establish Workflows
        ○ Audit Trail
Location Alignment identifcation
correlation how well matches.
Data Matching
![image](https://user-images.githubusercontent.com/85593608/121295111-82468a80-c8bc-11eb-9c35-e6e49b5d4c09.png)

![image](https://user-images.githubusercontent.com/85593608/121295172-968a8780-c8bc-11eb-9f8a-ad7aa49863c9.png)
  
•
•	Data lineage traces data back to original sources through source to target mappings.  This capability automatically parses the code used to move and store data to inform users where their data came from.  This information is especially useful when investigating root causes for data quality problems.


which database, application, or file contains the right informatio



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





