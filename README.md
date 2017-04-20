# COP4640-Project-3

Goal: To familiarize students with basic Linux Bash admin commands.
We have created a set of virtual machines running Linux, you will be supplied with an IP address of the machine assigned to you in class.
1. Login as student with password .
2. Change the password (use the command passwd).
3. Determine the version of Linux running.
4. Determine how long the machine has been running.
5. Get a report of file system disk usage.
6. Show the configuration of the network interfaces.
7. Use sudo and adduser to create a new user account using your N number as the user name and giving it a password that you define.
8. Give the new account sudo privileges (investigate groups and usermod commands)
9. Create another user using your last name as the user id.
10. Create a group cop4640 and add the user to it (investigate addgroup and usermod, use cat /etc/group to see all groups).
11. Put a command in the .bashrc file of your N number user to be:
“n00123456:command> “
(replace n00123456 with your user name. Do not hardcode your user name. Investigate the environment variable PS1, use pico or vi to edit the file.)
12. Schedule a command to run as your N number user at a given time every day (investigate crontab http://www.adminschoice.com/crontab-quick-reference)
13. Use the apt list to list all the packages available. The use the apt install command to install package yum then verify that it is installed.
1. Write a lab report that explains how you did each step and then that shows that you have done all of these items by running the appropriate commands and capturing the session. For example, do an ls of the /home directory to show the home directories. Do not include screen snapshots, actually capture the text and paste it into your document formatted as Courier New font, single spaced.
You should submit the lab report as a MS word or PDF file. University of North Florida 1