# Remediate-Secure-Token

Script is designed to challeng the end user fo details of the FileVault user. 
If more than one filevault users are present, you will have to type the username
manually, if there is only one secure token user then this user will be 
used by default.

Trouble Shooting
look at the logs created locally in /var/log/d8FVRemediation.log
Ensure you are running the script as root!, Jamf Self Service does this by default.
The logo used here is a base 64 encoded image, you can do the same with your logo using

test=$( base64 myIcon.png )
to see the text clear your screen and type
echo $test

Copy this and paste it into line 34 of the script between the quotes
theLogo="iVBO...dssds"
