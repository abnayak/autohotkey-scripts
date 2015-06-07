Autostart the scripts during windows boot:
------------------------------------------

There is a folder in the Start Menu called Startup.  If you put a shortcut to your script in that folder, 
the script will launch automatically every time you start your PC. 

To create a shortcut:

1. Find the script file, select it, and press Control-c.
2. Press Windows Key + r to start run window.
3. Type shell:Startup and press ok, it will open the startup folder
4. Paste the script by Control-p

When properly started, you can see Autohokey icons for each scripts in your taskbar.

Description of scripts:
-----------------------
1. closeApplication.ahk : 

Maps Control-q to Alt-F4. So, we can close applications by pressing Control+q in UNIX/Mac way.