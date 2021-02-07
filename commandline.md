# Command Line Notes for A+





## Advanced Windows Command Line
- shutdown
- tasklist/taskkill - list/kill any task on machine
- gpupdate/gpresult - Group Policy - query domain controller to check for group policy update and result shows changes

## Advanced Linux
- shutdown
- **CopmTIA uses apt-get install specifically**
- ps  - shows processes
- ps aux - shows all the processes on the system.
- ps aux | grep "libre"- runs ps aus and the pipes the output to grep, which searches for the string "libre"
kill - kills a process

## Chaning Permissions on Linux
- ls -l shows files and permissions for file (permissions in format User, Group, Other)
- Chmod 664 *filename* - Permissions are set using 7 for RWX, 6 for RW, 4 for R,
- Chown *username* *filename*

##Changing password
- sudo passwd - change password for current account


#Scripting
- creating a batch script
	-use a text editor write a cmd commands and then save a .bat file to run.
- home path %HomePath\
- set - opens enviroment variables

##Powershell
cmdlet - mini program for pwoershell
