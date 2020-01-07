# Scheduler
Adds your course schedule to your Google Calendar to get reminders

# Requirements

1)Python 3

2)Google api package for python:
Install using -

"pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib"

https://developers.google.com/docs/api/quickstart/python

OR 

Use the "requirements.txt" file

3)Your schedule for Spring 2020:
1) Go to my.wisc.edu -> Course Schedule ->Click on the Print button on the top right
2) Copy the text below the schedule - starting from "Monday" till the end of the page
3) Save the text in a file called "schedule.txt" in the same folder as the python script

4)Download the files "cal_setup.py", "credentials.json", and "Schedule.py". Place in the
same folder as the "schedule.txt" file

# Run the script

1) Run the script "Schedule.py"
2) You may have to log into your google account to allow it access your google calendar in the pop up window
3) Your classes should now be visible in your Google Calendar 


