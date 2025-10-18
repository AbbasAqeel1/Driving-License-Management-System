To run this program There are a few steps you need to follow to run the program without any errors or bugs

here are the steps:

1. Open DVLD Project folder, then you will see Three folders one for the (Database files) and the second one for (Program files) and the third one (Project Icons) is for the icons used in the program.
2. Open Your (SQL Server Management Studio ) and restore the DVLD Database (DVLD.bak) file in (Database files) Folder

    Here is the restore script:-
( USE MASTER

 	GO

 	RESTORE DATABASE DVLD
FROM DISK = 'Your DVLD.bak file path'

     	WITH FILE = 1;).



NOTE:- Database name should be DVLD, In order to be compatible with the program, so that no error occurs when the program is run.



2\. Once you have done with Database, go to (Program Files) folder and then you will see Three folders inside it, First (DVLD) folder it is The Presentation Layer This is the layer that Users will see and deal with it.

3\. The second one(DVLD\_Buisness) is Business Layer where the logic of the program is in it, This is responsible for the logic in the program.

4\. And the third one (DVLD\_DataAccess) is Data Access Layer This layer is responsible for brings the data from the database using (Ado.net) and send it to business layer and send data to the database.



5.Open (DVLD) folder then go to (DVLD.sln) double click on it to run the program.





To enter the system use the following user Info:

    username: Msaqer77

    Password : 1234



The program should run correctly without any problems.



