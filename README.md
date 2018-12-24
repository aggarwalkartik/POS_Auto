# POS_Auto
POS_Auto_Ver0.1
-This script opens a BI document, logs in with client name & password
-After logging in, the script connects to the database. The time period for the data required is entered and the query is run
-The script goes into sleep for 20 minutes so that the query can be completed. After 20 minutes, the script copys all data
-Having copied the data from BI tool, this script opens a new notepad, data fromm BI is copied as text and saved in the designated folder
-This script then sends an email with the data prepared as attachment to the respective person

Challenges
-Throughout the script, keystrokes have been used. A buffer time had to be given for these keystrokes to perform the action.This is because
 computer induced keystrokes are much faster than human induced keystrokes. Thus, we need to give a wait time for the system to 
 capture them
-Initially data was to be prepared in Excel, however, not having a licensed product opens up "Microsoft Product Activation Wizard" on which 
 KeyStrokes could not be used. Further, it was causing the script to run in an infinite loop

Time Utilized
-For development of the script, two man days were utilized

Further development
-The location of files are hardcoded and would need to be dynamic for wider scope of use
