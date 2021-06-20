# Phonebook-Assignment
ProgressSoft .NET Phonebook assignment

Dear ProgressSoft team,

thank you for reaching out to me, it was a pleasure solving the task.
Below are some information about the project for a successfull build and run:

-Included is a Web.config file which contains the Connection String and the Database path, both are in the <appSettings> section, in which you might need to change accordingly to your machine setup.

-I have implemented a "Download as QR png" option to the cards, but because of the huge size of the base64 photo field it doesn't fit in the generated QR code and thus I left it out (it will show my default photo instead).

-You might need to give full control permissions to "IIS_USRS" in order for the IIS excuter to make changes to the included database,
If you get an error message with "Insufficient privileges" please try one of the following: 
	1-try running Visual Studio as an administrator.
	2-try giving "IIS_USRS" full permission to the database.accdb file.
	3-try running the application pool with a user account identity instead of ApplicationPoolIdentity.

-The search bar on top of the cards in the Home screen can be used to filter the results according to (Name, DOB, Phone, Gender or Email).

-Included is a folder named "Samples" which contains sample business cards to use in the "import from a template" button.

-I have coded and compiled the project using MS Visual Studio 2017 using .NET Framework 4.8 .


Thank you for your time and consideration.

Best,
M. Al-Daqqa.
