![air-script logo](https://raw.githubusercontent.com/B3ND1X/air-script-img/main/IMG_0992.jpg)

## WHAT IS AIR SCRIPT?

Air Script is an automated and automatic way to pwn wifi. 


Automated: Step by step user friendly interface, to improve work flow. Type less, attack more!


Automatic: You can tell Air-Script to hack all wifi networks around you with an Air Script attack. (Attack all option)
Air Script will automatically pwn every network in range in a matter of seconds to minutes without any user input. When Air-Script is done. It will automatically turn off monitor mode, and send you an email notification. (Notifications are optional) Then Air Script will ask you what wordlist to use, and will to try and bruteforce the password for you. (When asked for wordlist, click enter or crl + c to skip.

*If on Raspberry Pi, it's recommended to skip bruteforce and transfer handshakes from Pi to PC to decrypt the password.*

*Create or upload your own wordlist to Air Script. More wordlists means a higher chance of getting the password!* 

*Also note you will have to convert .cap files to .hccap yourself if you want to use hashcat* (This will be an automated option in the future)

Use this if you don't know how to convert: https://hashcat.net/cap2hccapx/ (Convert handshake for hashcat, this is optional)


To make things easier, do this all over SSH and Air Script will turn off monitor mode when it finishes scanning, deauth, flood, etc. 
It automatically turns off monitor mode after every step to ensure you can stay connected via SSH. 


Air Script is a great tool for lazy people, script kiddies, and anyone who wants to pwn on the go. (Especially without being noticed. 
Easily hide a Pi in your pocket, connect via ssh with mobile hotspot or ad hoc and pwn the world!)

*PLEASE NOTE: If youre on Raspberry Pi over SSH, VNC or Ad Hoc most tools will not work due to being disconnected when being put into monitor mode. ONLY Air Script Attacks work when connected over SSH or Ad Hoc. Air Script Wifi attacks were specifically built for a headless set up*

## EMAIL NOTIFICATIONS
Don't want to sit around and pay attention to what's happening? Yeah, me either... Thats why Air Script will ask you if you want an email notification when its done pwning networks. No set up, no fuss, just type in a working email address and air script will do the rest. Your email is never recorded or sent to any server. Don't belive me? Check the code! Air Script is 100% open sourced and safe to use.


## DONT WANT TO USE ONLY AIR SCRIPT?

Thats okay, me either! Thats why Air Script comes with extra tools! See changelog for a list of added tools.
Air Script comes loaded with a variety of extra tools to improve workflow for hackers, pentesters and security researchers.
Either install all or choose which tools to install to save space. 

*This script comes as is, there is no warranty.*
*By using this script you agree to not hack, pwn or attack anything you do not own or have permission to hack, pwn or attack.*
*Hacking, pwning or attacking things you do not have permission to is illegal and pinishable by law. I am not responsible for your actions, or  any damages caused by misuse of Air Script or any of it's tools.*

![alt text](https://raw.githubusercontent.com/B3ND1X/air-script-img/main/air-scriptv1.0.2.png)
![alt text](https://raw.githubusercontent.com/B3ND1X/air-script-img/main/IMG_0991.JPG)	
![alt text](https://github.com/B3ND1X/air-script-mobile/blob/main/img/IMG1.JPG)


## VIDEO:
* https://drive.google.com/file/d/1JHz_qeq7M-sfPU6Nh0MtVoqs0EQeNFEt/view?usp=sharing (KALI PC)
* https://drive.google.com/file/d/1F6777GA08joON5ZYYVb8gWt6bt6WNW-d/view?usp=sharing (KALI RASPBERRY PI SSH)

## Mobile & Raspberry Pi
							               
PLEASE NOTE: 
* NO JAILBREAK is required to SSH to your Pi from iOS! Just download "Terminus" app from AppStore	
* NO ROOT is required when SSH to Pi from Android donwload a terminal of your choice from Google Play
* For Raspberry Pi users, it's recomended to select only the tools you need to save on space. 
		
## HOW TO INSTALL:

Open Terminal

run commands: 

* cd
* git clone https://github.com/B3ND1X/air-script
* cd air-script 
* chmod +x install.sh
* sudo ./install.sh


## HOW TO RUN:

* cd air-script
* sudo ./air-script.sh



## HOW TO UNINSTALL THIS GARBAGE SCRIPT?!!

It's a shame to see you go. No hard feelings!

* Please go to "Help" (Option 8)
* Select "Uninstall" (Option 4)
<br>
</br>

### CHANGELOG

v 1.0.5
* Email notifications for when Air Script is done attacking
* Other small bug fixes and improvments

v 1.0.4
* Small bug fixes and typos
* Added Fluxion
* Added Wifite & Wifite2
* Added Fern
* Added Airogeddon
* Added Morpheus
* Added Hakku
* Added Trity
* Added Cupp
* Added Dracnmap
* Added KickThemOut
* Added Ghost-Phisher
* Added Xerxes
* Added Katana
* Added Websploit
* Added BeeLogger
* Added Ezsploit
* Added TheFatRat
* Added Angry IP Scanner
* Added Sn1per
* Updated installer(Option to install all or select what to install to save space)
* Updated Uninstaller 


v 1.0.3
* Added Wifiphisher to wifi tools
* Added Zatacker to extra tools
* Added Routerploit to extra tools
* Updated installer and uninstaller
* Small bug fixes and typos


v 1.0.2
* Extra tools option
* Added Zirikatu to tools
* Added uninstall script to remove air-script and or air-script tools
* Cleaned things up


v. 1.0.1


* Anonsurf added to tools
* MAC Changer added tools
* Fluxion added to tools


v 1.0
* Initial Release
