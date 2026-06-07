
ERP(Enterprise Resource Planning)

The Purpose of any ERP Software is to manage the entire organization so that we can maximize the profit of the Organization. 

For eg.
- We have a Organization, there We will have lots of employees, resources, products, Accounts, Sales, etc.
- As A owner how will I suppose to manage Everyone so that I can utilize all of my resources so that I can increase my Profit?
- An ERP Software always claims that I am going to manage your entire Department and as a owner or Admin you will have the license and access of everything so that by sitting at your home you can check the growth and maintenance of your organization. 
- Way before 1972, lots of companies were growing and they were facing the issue for management. 
- 5 employees of IBM left their jobs and founded a new company called SAP(System Application and Product in Real-time Data processing)
- parent company: SAP 

**Features Of SAP Software**
- It is an integration of all the functions into one common software.
	- Every organization has lots of Departments, SAP has divided all these Departments and SAP software calls them as a **Module**.
	- SAP also made this Software Multi-Lingual, which supports 40+ languages so that It can be used and implemented across the globe.
	- SAP is not a Open Software and Its Unbreachable. Without UserID and password one cannot access SAP software. 


**Architecture of SAP Software**
When SAP launched the 1st version of SAP Software in 1972, at that time the version was called R1. 
- All Components including the database was combined into a single system.
- R1 was not good for security as anybody can easily access the data and destroy it.
- Software is basically divided into 2 parts.

Version 2: R2
- In this R2 version, the Presentation and Application Layer was together as a Single layer and Database Layer was the secondary layer for storing the data. 
- This was definitely an Improvement, but the presentation and Application layer together will cause a load on the First Layer. 
	- Because of this reason the performance was not that Good for the SAP System.
	- So, SAP Decoupled the 1st layer and separated the application and presentaion layer. 
	- This had led to its 3rd version R/3.

**SAP VERSION R/3**
3 major Layers:
						Presentation Layer 
						Application Layer [[Application Layer]]
						Database Layer
Presentation Layer
- Only (mainly) focuses on two things: From where the user will give the input and take the output.

Application layer
- Application layer is only for the logic part. The logic will be executed based on the input given by the user.
- We as ABAPer write code and logic in this Layer and build application the top of this layer.

Database Layer
- This is the layer where we will write out the logic.
- When SAP launched its 3rd Generation, they named it ECC system(Enterprise Central Component), where SAP was using Database from different vendors like Oracle, Mysql, Mssql, etc.
- As a company If I am buying this SAP software, I was using the database from these Different Vendors because SAP did not provide any of their own databases.
- 