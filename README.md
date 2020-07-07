# bash_ping-to-text
┏━┓╻┏┓╻┏━╸   ╺┳╸┏━┓   ╺┳╸┏━╸╻ ╻╺┳╸
┣━┛┃┃┗┫┃╺┓    ┃ ┃ ┃    ┃ ┣╸ ┏╋┛ ┃ 
╹  ╹╹ ╹┗━┛    ╹ ┗━┛    ╹ ┗━╸╹ ╹ ╹ 
	version 1.0

	featuring:

╺┳╸┏━┓┏━┓┏━╸┏━╸┏━┓┏━┓╻ ╻╺┳╸┏━╸   ╺┳╸┏━┓   ╺┳╸┏━╸╻ ╻╺┳╸
 ┃ ┣┳┛┣━┫┃  ┣╸ ┣┳┛┃ ┃┃ ┃ ┃ ┣╸     ┃ ┃ ┃    ┃ ┣╸ ┏╋┛ ┃
 ╹ ╹┗╸╹ ╹┗━╸┗━╸╹┗╸┗━┛┗━┛ ╹ ┗━╸    ╹ ┗━┛    ╹ ┗━╸╹ ╹ ╹
	version 1.0

made by jadentheprogrammer06 on github

*about & installation steps below.
---------------------------------------------------
ABOUT THIS TOOL
---------------------------------------------------
This is a hand-coded script I wrote to do the basic task of
pinging a DNS/IP address and then saving the results to
a log file which is named by date and time.

This is useful for establishing your network baseline as you do more and more network connectivity tests.
^ I recommend that you use this tool frequently when you believe it is needed for this very reason.

I also recommend writing down notes and examining how and why your network connection is working.

Included with the "ping-to-text" script in this folder is a "traceroute-to-text" script.
If you are going to make a program like this, why not include traceroute as well?

This is/was my first bash script. (I spent quite a lengthy time cleaning up this code, writing the readme, and making the script
feel nice to use. For a simple tool like this that I see being used often it was worth it.)

I would appreciate any constructive criticism if anyone happens to view this in the future.

---------------------------------------------------

----------------------------------------------------
PATH INSTALLATION STEPS (Make script(s) executable + Install to PATH (as terminal commands) )
----------------------------------------------------
# chmod +x makes the scripts executable.
0)files located in ./bash_ping-to-text/bin/
 
1)chmod +x ping-to-text; chmod +x traceroute-to-text

# /opt/local/ can be the PATH script-installation-directory of your choice. I am using it here as an example.


# if you dont have /opt/local/ directory:
2.1)mkdir /opt/local/


# move this script's folder to the PATH directory.
2.2)mv bash_ping-to-text/ /opt/local/


# add this script to your PATH
3) Add the following line to your ~/.bashrc file:
export PATH=$PATH:/opt/local/bash_ping-to-text/bin


# Now that the script is in your PATH it should be available as a command.
4) Reboot the terminal. (reboot or exit -f)

# if this doesn't work try searching the internet for answers.

# I would appreciate any constructive criticism if anyone happens to view this in the future.
