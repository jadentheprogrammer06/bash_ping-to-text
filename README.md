# bash_ping-to-text
#PING TO TEXT version 1.0
*includes:*
#TRACEROUTE TO TEXT version 1.0

*Made by jadentheprogrammer06 on github*
 
*About & Installation steps below.*
---------------------------------------------------
##ABOUT THIS TOOL
---------------------------------------------------
This is a hand-coded script I wrote to do the basic task of
pinging a DNS/IP address and then saving the results to
a log file which is named by date and time.

This is a useful tool for establishing your reliable network baseline; As you do more and more network connectivity tests it is important to log each test.

Included with the "ping-to-text" script in this folder is a "traceroute-to-text" script.

This is/was my first "real" bash script. (I spent quite a lengthy time cleaning up this code, writing the readme, and making the script
feel nice to use. For a simple tool like this that I see being used often it was worth it.)

*I would appreciate any constructive criticism if anyone happens to view this in the future.*

---------------------------------------------------

----------------------------------------------------
##PATH INSTALLATION STEPS (Make script(s) executable + Install to PATH (as terminal commands) )
----------------------------------------------------
*chmod +x makes the scripts executable.*
*files located in ./bash_ping-to-text/bin/*

	$ chmod +x ping-to-text; chmod +x traceroute-to-text

*/opt/local/ can be the PATH script-installation-directory of your choice. I am using it here as an example.*


*If you dont have /opt/local/ directory:*
	$ mkdir/opt/local/


Move this script's folder to the PATH directory:
	$ mv bash_ping-to-text/ /opt/local/


Add the following line to your ~/.bashrc file:
	$ export PATH=$PATH:/opt/local/bash_ping-to-text/bin


# Now that the script is in your PATH it should be available as a command.
	$ Reboot the terminal. (reboot or exit -f)

note: If this doesn't work try searching the internet for answers.
