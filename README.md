- 👋 Hi, I’m @Rajafanofpspk
- 👀 I’m interested in ...

Farmer’s Buddy

	Revision History:	



 Version No	

Date	
         Prepared By/
Modified By	
   
                     Significant Changes


      


         BuildVersion1	

          


           11/12/2023	



Anusha, Radha	


1.	When the user is trying to login with valid credentials it is showing error message "Invalid Login, please login with valid credentials"
2.	Crop list is not displaying for spring.
3.	Water and soil conditions are not displaying for any of the crops.







0.1	





13/12/2023	




     Manjunadh, Rohan	



1.	 The login error message which has showed
While the user is trying to login is resolved.
2.	Now The Crop list is displaying for spring.
3.	Now The Water and Soil conditions are 
Displaying for any Crops.


1.1	Project Overview:

•	The Farmer’s Buddy application is designed to assist users, particularly farmers, in selecting suitable crops based on the season and soil type. It provides information on crops that thrive in specific seasons and corresponding soil conditions.
1.2	Scope:

•	The scope of the project is to provide accessibility to all the farmers who have valid user Id and password. Analyzing the soil, water conditions and fertilizers to be  used is the main scope for this project. 

1.3	Out of Scope: 
•	Automation Testing

1.4      Intended Audience:
•	Farmers:
Farmers looking for guidance on selecting crops based on seasons and soil conditions.
•	Agricultural Experts:
Agricultural experts and advisors who can use the application to provide recommendations to farmers.

1.5      High level use cases:
•	User Login
•	Season Selection
•	Crop Details

1.6      Use Cases Detailed: 
 1.     User Login:
o	Description: Registered users can log in to the application using their credentials.
o	Intended Audience: User, System
•	Season Selection:
o	Description: Users can select the current season for crop recommendations.
o	Intended Audience: User, System
•	Crop Details:
o	Description: Users can view detailed information about a specific crop, including soil and water conditions.
o	Intended Audience: User, System

1.7      User Interface Modules:
•	Login Module:
o	Takes user input for username and password.
o	Validates the user credentials against the database.
•	Main Menu Module:
o	After successful login, displays the main menu options.
o	Options might include selecting a season, viewing crop recommendations, or logging out.
•	Season Selection Module:
o	Prompts the user to select the current season.
o	Validates the season input.
•	Crop Recommendations Module:
o	Displays a list of recommended crops based on the selected season.
o	Allows the user to select a specific crop for more details.
•	Crop Details Module:
o	Displays detailed information about a selected crop, including soil and water conditions.

1.8	  Technical Architecture:
1.	Presentation Layer:
o	Console Interface
2.	Application Logic Layer:
o	Main Application Class
o	User Authentication Module
o	Crop Selection Module
o	Database Connectivity Module
3.	Data Layer:
o	MySQL Database
o	User Table
o	Crop Table

1.9   Technical Detailed Description:
•	MySQL Database:
Contains one main table: users.
Users Table:
o	Stores user information including username and password.




1.10    Sequence Diagram:
                                  

                                                              
                                                           
                                                  

                 
                  


















1.11 Standards:
•	Class Name Starts With Capital Letter.
•	Used Meaningful Variable And Method Names.
•	Adopted a Java Testing Frame Work Test NG For The Automation Testing.
•	Used Document Code By Including Comments For Each Section.
1.12 Non-Functional Requirements:
•	Performance:
The system should respond to user input within 2 seconds.
•	Reliability:
The application should handle errors gracefully and provide meaningful error messages to users.
In case of a system failure, the application should recover without data loss.
•	Security:
User authentication and authorization should be implemented securely.
Passwords should be stored securely using SQL
•	Usability:
The console interface should guide users through the process clearly.
Help messages and instructions should be available for users to understand the available commands.







 

<!---
Rajafanofpspk/Rajafanofpspk is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
