NOTE: Logging is automatically turned on. When you start msfconsole you should see that you are logging to a file. This file is unique
since we are using the same format (i.e. /root/blueStarCmdLogging_[epoch time]).


If this was not turned on automatically for us, then you could do the following: 

To initiate logging in metasploit, do the following:

	0	spool /root/nameOfYourOwnageFile.txt
	1	[ This is where the actual ownage goes!!! ] 
	2	spool off

Note, it may not be useful to turn it off if you just want to capture everything during your session.

To ensure that you always have a log of what you are doing, you can add the spool command to the msfconsole.rc file (note, just line 0 above).
