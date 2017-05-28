PyBGPKiller is an open source Python implementation of BGPKiller.

BGPKiller ("Your Avira Ad Killer"), or Background Process Killer.
From the website (http://bgpkiller.weebly.com/) description:

BGPKiller is an ad killer (or blocker) for your Avira Antivir antivirus. 
The application is designed to stop popup windows (i.e. ads) coming from Avira.  It monitors the unwanted Avira processes responsible for ads, and silently kills Avira popups and ads before they show up. 



2017/05/28 - Release v1.0

First release of PyBGPKiller. This is a proof of concept of BPGKiller's implementation.
Blocking "ipmgui.exe" (In Product Messaging GUI) in Windows Firewall will work just as well.

Recommended running mode is to have a batch file on startup (%APPDATA%\Microsoft\Windows\Start Menu\Programs\Startup).
Just copy & paste:
start "PyBGPKiller" /low pythonw.exe pybgpkiller.py
exit