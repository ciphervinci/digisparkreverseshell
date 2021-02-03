# Digispark Reverse Shell

This arduino script is used to download payload from your system and execute it in other system in local network by using Digispark Attiny85 chip.

# Usage

-First create a payload in your system. Can be any executable (I am using .exe). Use MSFvenom.  
-Then create simple http server by python in 8080 port. (python3 -m http.server 8080)  
-Replace the ip and the name of the payload in the script according to your local ip and payload name.  
<img src="https://i.ibb.co/brB2Dmp/Changing-Line.png" alt="Change here">  
-Upload Script to your attiny85 chip.  
-Open a listener in your system.(Like MSFconsole)  
-Plug Digispark chip in the victim's computer and let it execute the scripts.  
-And there you get the reverse shell of victim's system.  

**NOTE :** This script only works if windows defender - Real time protection is DISABLED. However, you can add scripts for disabling it before the actual script.

# Digispark Attiny85
<img src="https://media-exp1.licdn.com/dms/image/C5122AQFMYT3z8azQ6w/feedshare-shrink_8192/0/1564979684009?e=1615420800&v=beta&t=mDQJA7dLvFUuyo8ovnOuVGpr1sfBKnb3GK4nWOiQ4Gc" alt="Digispark Attiny85" width="320" height="569">

# DISCLAIMER :

Any actions and or activities related to the material contained within this repo is solely your responsibility.The misuse of the information in this repo can result in criminal charges brought against the persons in question. I will not be held responsible in the event any criminal charges be brought against any individuals misusing the information in this repo to break the law.
