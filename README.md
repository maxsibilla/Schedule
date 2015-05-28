# Schedule
Takes text from MyPage and converts it into an .ics file that can be read by a calendar application

REQUIREMENTS: 
You will need to have at least Java 1.7 jdk installed on your machine and the files schedule.txt and Kronos.jar in the same directory (folder). 

USE:
First copy and paste the text of the schedule from my page into schedule.txt, no additional edits should be made. The copied portion should look something like this:
After you have saved your changes to scheudle.txt simply double click Kronos.jar and it should create a new file called Schedule.ics in the same directory. Open that to import your schedule into your calendar.

FEEDBACK:
If you encounter any issues with running the executable jar file first delete the existing Schedule.ics file first then send me an email with your version of schedule.txt.

File: kronos.java
    Description: Converts a .txt file named "schedule.txt" into an .ics file that can be imported into a calendar application

    Modification Protocol:
	Be sure to include schedule.txt in the same directory as the runnable jar file. The creation of scheudle.txt simply requires one to copy and paste the text schedule from MyPage. No additional edits are needed in said file.
	
	Versioning:
    -0.1 (4/15/2015): Created file
		
    -0.2 (4/28/2015): Added hours scheduled that shift and total hours scheduled that week to comment section of the .ics file
    
    -0.3 (5/23/2015): Added conditional statements that check if  that day was requested off, ie "RTO".
    	Also changed how the program anticipates months, MyPage displays only the first 3 letters of each month not the full name
