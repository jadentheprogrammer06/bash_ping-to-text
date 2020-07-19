# bash_ping-to-text "PING TO TEXT version 1.0" & "TRACEROUTE TO TEXT version 1.0"
***Includes ping-to-text and traceroute-to-text scripts.***

*Made by jadentheprogrammer06 on github*
 
*About & Installation steps below.*
---------------------------------------------------
ABOUT THIS TOOL
---------------------------------------------------
This is a hand-coded script I wrote to do the basic task of
pinging a DNS/IP address and then saving the results to
a log file which is named by date and time.

This is a useful tool for establishing your reliable network baseline; As you do more and more network connectivity tests it is important to log each test.

Included with the "ping-to-text" script in this folder is a "traceroute-to-text" script.

This is my first "real" bash script. (I spent quite a lengthy time cleaning up this code, writing the readme, and making the script
feel nice to use, among other things. It was good practice with bash, version control and writing clean code in my projects. I also understand programs should be intuitive and confusion-free, so I cleaned up the script text and README files.)

*I would appreciate any constructive criticism if anyone happens to view this in the future.*

---------------------------------------------------
----------------------------------------------------
	RECENT UPDATES TO THE SCRIPT(s)
----------------------------------------------------
*July 19: Can now pass in an argument from the command line (shell).*
----------------------------------------------------
PATH INSTALLATION STEPS:  Make script(s) executable + Install to PATH (as terminal commands)
----------------------------------------------------
*chmod +x makes the scripts executable, if they aren't already when cloning/downloading from this repository.*
*files located in ./bash_ping-to-text/bin/*

	chmod +x ping-to-text; chmod +x traceroute-to-text

*/opt/local/ can be the PATH script-installation-directory of your choice. I am using it here as an example since its where it is recommended to install custom scripts.*


**If you dont have /opt/local/ directory:**

	mkdir /opt/local/


**Move this script's folder to the PATH directory above, or one of your choice:**

	mv bash_ping-to-text/ /opt/local/


**Add the following line to your ~/.bashrc file:**

	export PATH=$PATH:/opt/local/bash_ping-to-text/bin

**Alternatively, if you choose a different PATH directory (such as /usr/local/bin), the line will look similar to this:**

	export PATH=$PATH:/usr/local/bin/bash_ping-to-text/bin

# Now that the script is in your PATH it should be available as a command.
	Reboot the terminal. (reboot or exit -f)

**Calling the scripts from PATH as commands:**

	ping-to-text

	traceroute-to-text

note: If this doesn't work try searching the internet for answers.
