# COSC1410-Introduction-to-Computer-Science-Assignment-2-solved

Download Here: [COSC1410 Introduction to Computer Science • Assignment 2 solved](https://jarviscodinghub.com/assignment/introduction-to-computer-science-•-assignment-2-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

You will develop and implement a program that simulates a basic login process (for example, similar to one we use for logging in our email accounts). The primary objective of this assignment is for students to demonstrate use of the looping mechanisms.
2 Program The username must meet the following requirements:  6 digits long  Contains only numbers  No spaces  A constant value, which is 123456. It must be initialized at the declaration. This corresponds to the record that we store in our system. Please notice that you must declare a variable to read the input from the user. Then, you will compared the stored username to the user input.  The username can NOT be changed.
The password must meet the following requirements:  4 digits long  Contains only numbers  No spaces  The temporary (i.e., initial) password must be 1234, and the variable must be initialized at the variable declaration. This corresponds to the record that we store in our system. Please notice that you must declare a variable to read the input from the user. Then, you will compare the stored password to the user input.  The password must be changed at the first user login.
The program begins by having the user enter the username (i.e., 123456) first and then the temporary password (i.e., 1234). Please notice that you need to re-enter the username and the temporary password if you re- execute the program.
The following 2 outputs were produced by running the program on one single occasion.
Introduction to Computer Science • Assignment 2
© 2016 Hakan Haberdar hakan@haberdar.org
Our program requires the user to change his/her password after first logging in with the temporary password. To be able to change the temporary password, the user must first enter the correct username and the temporary password combination. Our system limits the number of times a user can enter an incorrect login credentials. If the user enters incorrect combination of the username and the temporary password 3 times, the program terminates.
THE FOLLOWING 1 OUTPUT IS PRODUCED BY RUNNING THE PROGRAM ON ONE SINGLE OCCASION.
If the user enter the correct username and temporary password combination at the first, the second, or the third attempt, the user will be prompted to change the password.
Introduction to Computer Science • Assignment 2
© 2016 Hakan Haberdar hakan@haberdar.org
THE FOLLOWING 5 OUTPUTS ARE PRODUCED BY RUNNING THE PROGRAM ON ONE SINGLE OCCASION.
The new password must be a 4-digit number and different from the temporary password. If the user tries to enter the temporary password as the new password, the system warns the user and ask for a new password. Similarly, the user must enter 4-digit password, the system warns the user and ask for a new password.
This repeats until the user enters a valid new password. After a NEW VALID password is entered, the program will prompt the user to login using the updated credentials.
Introduction to Computer Science • Assignment 2
© 2016 Hakan Haberdar hakan@haberdar.org
Similar to above, the user has 3 chances to enter the correct user name and password combination.
Introduction to Computer Science • Assignment 2
© 2016 Hakan Haberdar hakan@haberdar.org
If the user enter valid new password and username, the program displays the success message.
Please notice that you may design a better user interface for the assignment.
Hints:  You can use any number of loops in the program.  You can use bool variables (i.e., bool isFirstLoginSuccess )
Introduction to Computer Science • Assignment 2
© 2016 Hakan Haberdar hakan@haberdar.org
3 Grading A correct solution: worth 100 points
Deductions:
ERROR DEDUCTED POINTSP rogram cannot be compiled 40 Program terminates unexpectedly during runtime 40 User interface does not have required information 5 No prompt for entering invalid data 10 Code is not commented 10 Proper indentation is not used 20 Proper variable types are not used 5 3-attemp policy for the first login not implemented properly 10 Password cannot be changed 20 3-attemp policy for 2nd login (after the change) not implemented properly 10 No looping mechanism is used 35 Missing access granted message 5 Login with invalid credentials allowed 20 Password 4-digit rule not implemented properly 10 New password not different from the temporary password 10

1. Feel free to discuss ideas and implementations with your classmates, however DO NOT share code.
2. If you have a question about the assignment, do not wait until the last minute to ask.
3. Normal deductions for late submissions will be in effect. Please see Assignment Guidelines.
4. ANY kind of plagiarism or cheating, will result in a grade of 0.
