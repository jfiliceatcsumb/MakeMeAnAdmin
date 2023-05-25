Make Me an Admin!

This script, when run, will allow a standard user to upgrade themselves to an admin for 60 minutes and then will grab a snapshot of the logs for the past 30 minutes as well so you can track what they did. 

The script will create a launch daemon to take care of demoting the user so that no matter how many times they log out or shut down, after 30 minutes of uptime, a script will be run to remove their admin privileges. 

It is recommended to push this script as a policy to self service to run only once per day.

The script allows you to set the count down minutes by providing 
Parameter 4 in Jamf Pro. The Default value = 60 minutes.
