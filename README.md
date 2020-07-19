# "PING TO TEXT version 1.2.2" & "TRACEROUTE TO TEXT version 1.2.2" for Linux-based OS.
***Includes ping-to-text and traceroute-to-text scripts.***

*Made by jadentheprogrammer06 on github*
 
---------------------------------------------------
ABOUT THIS TOOL
---------------------------------------------------
These scripts can either ping or traceroute an
DNS/IP address and then save the results to
a log file which is named by date and time.

I have included installation steps, primarily for Ubuntu-based Linux and WSL2 if installed on Windows 10.

This is a useful tool for establishing your reliable network baseline; As you do more and more network connectivity tests it is important to log each test.

Included with the "ping-to-text" script in this folder is a "traceroute-to-text" script.

*I would appreciate any constructive criticism if anyone happens to view this in the future.*

---------------------------------------------------
----------------------------------------------------
RECENT UPDATES TO THE SCRIPT(s)
----------------------------------------------------
*JULY 19 2020: Version 1.2.2:* 

	*Can now pass in multiple arguments from the command line (shell).*
	*Refined code and patched some bugs.*

*July 19 2020: Version 1.2:*

	*Can now pass in an argument from the command line (shell).*
	*Also planning to allow batch-pinging of multiple addresses (passing in multiple arguments to the script)*

----------------------------------------------------
PATH INSTALLATION STEPS:  Make script(s) executable + Install to PATH
----------------------------------------------------
*chmod +x makes the scripts executable, if they aren't already when cloning/downloading from this repository.*
*files located in ./bash_ping-to-text/bin/*
*NOTE: it is important to do this step so that files can be created.*

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

note: This installation guide was designed for ubuntu-based OS(s). The steps for other Linux based operating systems shouldn't be too different. To run on windows install WSL2.
