THE DEWEY DECIMAL PROJECT_ PART 3_POE

TABLE OF CONTENTS:
A. PROJECT TITLE
B. GITHUB LINK
C. PURPOSE OF THE PROJECT
D. DATE OF SUBMISSION
E. AUTHORS
F. USER INSTRUCTIONS
G. HOW TO COMPILE THIS PROJECT
H. HOW TO RUN THIS APPLICATION AFTER COMPILING

A. PROJECT TITLE: NewDewey

B. GITHUB LINK: https://github.com/st10114295/PROGRAMMING7312.git

C. PURPOSE OF THE PROJECT: 
In the first part of the final project, I needed to do online research to find call numbers and their descriptions to the nearest integer (i.e., no 
need to get into the digits after the decimal point).
In a Word document, create a multi-level list showing the call numbers, for example:
• 700 Arts & Recreation
o 750 Paining
 751 Techniques, procedures, apparatus, equipment, materials, forms
 752 Color

In the second part of the final project, we needed to create a quiz where the user drills deeper and deeper into the hierarchy until they find the correct answer.
The following requirements must be added to the application created in Part 2:
1. Create a file containing the data that was gathered in the research part of this task in a format that can be read by your application.
2. Enable the Finding call numbers task.
3. When the user chooses Finding call numbers, the application must load the Dewey Decimal classification data into memory from the file created in Step 1.
4. The quiz must work as follows:
a. For each question, randomly select a third level entry from the data, for example, 752 Color. Display only the description, not the call number.
b. Display four top level options to the user to choose between, one of which must be the correct one and the other three randomly selected incorrect answers. For example: 000 General 400 Language 700 Arts & Recreation (Correct answer) 800 Literature
c. For the options, display both the call number and description. Display the options in numerical order by call number.
d. If the user selects the correct option, show them four options from the next level, until the most detailed level is reached.
e. If the user selects the wrong option anywhere along the way, indicate this and then ask the next question.
5. Implement a gamification feature to motivate users to keep using the application. You may use the same one as before or choose to implement a different one.
Technical requirements:
1. Make use of a tree to store the data in memory.

D. DATE: 21 November 2023

E. AUTHORS: Nicole Willemse

F. USER INSTRUCTIONS:
1.	The user will be met with a splash screen, which will load until the welcome page appears.
2.	The user should then click on “Identify An Area”, followed by “Explore Area”.
3.  When the user chooses the Identifying areas task, they should be presented with a user interface where they will match two columns: call number (top level only) and description.
4.	The user should then click on the “submit” button to check their sorting. Or, click in the “back” button to go back to the main page.
5.	The user can keep track of their score at the bottom of the screen, on the right side of the application.
6. To play a different game, the user should then click on “Identify An Area”, followed by “Explore Area”.
3.  When the user chooses the Identifying areas task, they should be presented with a user interface where they will match two columns: call number (top level only) and description.
4.	The user should then click on the “submit” button to check their sorting. Or, click in the “back” button to go back to the main page.
5.	The user can keep track of their score at the bottom of the screen, on the right side of the application.


G. HOW TO COMPILE THIS PROJECT: 
1. Open Visual Studio.
2. On the start window, select Create a new project.
3. On the Create a new project window, select the Windows Forms App (.NETFramework) template for C#.
4. In the Configure your new project window, type or enter NewDewey in the Project name box. Then, select Create.
5. Now we create the first form called the splash screen.
6. Next, we will create our second form called startup.
7. Then we will create our third form called ReplacingBooks.
8. Lastly, we will create our third form called FindNumber.

H. HOW TO RUN THIS APPLICATION AFTER COMPILING:
Select the Start button to run the application.