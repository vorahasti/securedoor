# Securedoor
Arduino Based Door Access Control provides security for home, office, shops, banks etc through a security password which is providential for the user alone. Users have the freedom to set a predefined code fortheir locking systems. The system will allow access to the person who knows the password and will not allow access to unauthorized person.

The project presented here is based on arduino and is more simple and reliable than simple micro controller based digital code lock. Here is a LCD display which is used to interface with the project to output lock status. In this project we have an additional advantage that the user can change the password. 
The user will be prompted to set a password at installation. This password inputted at installation will continue to serve the lock until it is change. The program will check for current password and allows the user to change Password only if the current password is input correctly.
Applications: 
It can be used in places where we need more security.
It can also be used in door, lockers, offices, main gate of house, ATM etc.

IMPLEMENTATION:

In this project, a 5V supply is used which is connected to the LCD display and Arduino.
When the circuit is energized, you will be asked to enter 5 digits as password at the initial boot/reset of the device. 
The first 5 digits you will enter at installation will be saved as your SET PASSWORD.
The device will go LOCKED after setting PASSWORD. We have to input correct password to Unlocking. 
If a user wants to open the security system, first he/she will be asked to enter the password, After entering the password, the Arduino will check whether the password match the password which is stored in the internal RAM is correct or not.
A LED is connected to pin no. 13 will remain on for 3 sec, and then it will go to off state.
If the pressed password is correct then Arduino will display access granted. It will be turn on the relay or other mechanism.
If the password is not correct it will display wrong password. When wrong password is entered more than 3 times, the system will be locked. 
To unlock it we then have to reset the system by pressing reset button and after resetting it the program will be re-excited. 
The main part of the circuit is Arduino UNO. The power supply section is very important.
It should provide constant voltage to the devices for successful working of the project.
The project is being tested in protous and is working properly. It is also tested in bread board and is properly working. 
It has lots of application like we can use this project in door for home and office security, lockers, ATM, and anywhere where security is needed. 
Here we can easily change the password and it has features like if wrong password is entered more than three times it would be locked until and unless reset button is pressed. 
In this project we have used very less component so it is cost effective and it is less complicated than a simple micro controller based code lock system.

