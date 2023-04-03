# -IT5016_Creating-a-Repository-ID20220456-
Assessment 3 Software development Help desk Ticketing Code
Project Description:This project is a prototype of a Help Desk Ticketing System that allows internal customers to submit tickets for IT support. The system is designed to track tickets, generate new passwords for password change requests, and keep track of statistics. It is written in Python and uses object-oriented programming concepts.
Technologies Used: Python
Challenges Faced:  One of the biggest challenges in creating this project was generating new passwords for password change requests. We had to figure out a way to extract information from the ticket and combine it in a specific way to generate the password. Another challenge was keeping track of ticket statistics, such as the number of open, closed, and resolved tickets. We had to design a system that could update these statistics automatically.
Features to Implement in the Future:
 In the future, we would like to add more functionality to the system, such as the ability to assign tickets to specific IT team members and the ability to generate reports on ticket trends over time.
 
 Table of Contents:
1.	How to Install and Run the Project
2.	How to Use the Project
3.	Tests

1.	How to Install and Run the Project:
•	Clone the repository to your local machine.
•	Open a command prompt or terminal window and navigate to the project directory.
•	Run the command "python main.py" to start the program.
2.	How to Use the Project:
•	To submit a ticket, enter the following information:
•	Staff ID
•	Ticket creator name
•	Contact email

Description of the issue
If the ticket’s description of the issue contains the words “Password Change”, a new password will be generated following a specific rule.
There is an option to respond to a ticket by providing feedback response.
Ticket statistics can be displayed to the console.
The IT department can resolve or reopen tickets as needed.
Ticket information can be displayed, including ticket number, creator name, staff ID, email address, description, response from the IT department, and ticket status.
3.	Tests: 
To run the tests, navigate to the project directory in a command prompt or terminal window and run the command "python test_ticket.py". This will run a series of tests on the Ticket class to ensure that it is functioning correctly. 
The tests include: 
o	Test that a ticket can be created with the correct information.
o	Test that a password can be generated for a password change request.
o	Test that the statistics can be updated correctly.
o	Test that a ticket can be resolved or reopened.
o	Test that ticket information can be displayed correctly.


