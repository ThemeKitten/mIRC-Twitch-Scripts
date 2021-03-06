# mIRC-Twitch-Scripts
The main focus of the scripts on this GitHub are for use with a Twitch [mIRC](http://www.mirc.com/) bot that works in conjunction with [AnkhBot](http://marcinswierzowski.com/Code/AnkhBotR2/) and AnkhBot's point system.  [AnkhBot](http://marcinswierzowski.com/Code/AnkhBotR2/) is a free and versatile Twitch bot, yet like most things, there is always room for improvement.  These scripts are designed to compliment and enchance a Twitch channel that is currently running AnkhBot, however, many of the scripts can also be easily modified to use without AnkhBot.  See the [wiki](https://github.com/Blasman/mIRC-Twitch-Scripts/wiki) for more information regarding each script.  

Be aware that [mIRC](http://www.mirc.com/) is a shareware program with a 30-day trial period, after which you will be required to purchase a license for the program. The standard cost is $20 US, however, there is a permanent [50% off coupon which drops the price to $10 found here](http://www.mirc.com/register.php?coupon=MIRC-SWV0-MNKL).  

# Credits  

AnkhHeart: For [AnkhBot](http://marcinswierzowski.com/Code/AnkhBotR2/), the bot that my scripts are designed to work with.  
SReject: For the [JSON Parser](http://hawkee.com/snippet/10194/) and [mTwitch scripts](https://github.com/SReject/mTwitch).  
Ramirez: For the [mIRC SQLite](http://hawkee.com/profile/12444/) script.  

# Installation

### If You Do Not Have a mIRC Twitch Bot, Set One Up

1. Download and install mIRC. UNCHECK EVERYTHING except "Scripts" and "Help Files" on the "Choose Components" section of the install, as you don't need most of it. http://www.mirc.com/get.html  

2. Get **YOUR BOT'S** Twitch account (**NOT** the Twitch name that you stream with) up and running with mIRC, and set up your main Twitch account's channel as an auto-join channel as well. See http://help.twitch.tv/customer/portal/articles/1302780-twitch-irc#MIRC You may ignore the section titled "Join/Parts - mIRC," as one of the required scripts below will perform the same function automatically.  Keep in mind that for Step 5 of the tutorial, you will need to be logged into Twitch using your BOT'S Twitch account when retreiving the oath token to use as your password.  

3. [Optional] I have created a YouTube video for setting up mIRC and making it as unobtrusive as possible.  It is created with the purpose of lurking in channels in mind, however, you may find some of the information useful.  https://www.youtube.com/watch?v=k7ULgVCZ3Ns

## Once You Do Have a mIRC Twitch Bot
### Download Required Scripts
To use any of the games scripts in this GitHub, you will need to download the following scripts to your MAIN (root) mIRC directory.  If you did not change the default install directory of mIRC, you can find the directory by typing %APPDATA%/mIRC into your Windows Folder Titlebar.
* [JSONForMirc.mrc](https://raw.githubusercontent.com/SReject/mTwitch/master/resources/JSONForMirc.mrc): right click this link and "save link as..." to your mIRC directory.
* [mTwitch.Core.mrc](https://raw.githubusercontent.com/SReject/mTwitch/master/mTwitch.Core.mrc): right click this link and "save link as..." to your mIRC directory.
* [mTwitch.DisplayName.mrc](https://raw.githubusercontent.com/SReject/mTwitch/master/mTwitch.DisplayName.mrc): right click this link and "save link as..." to your mIRC directory.
* [mIRC SQLite](http://hawkee.com/scripts/11648275/): Extract the .zip file from this webpage to your mIRC directory.
* [ankhbot.mrc](http://raw.githubusercontent.com/Blasman/mIRC-Twitch-Scripts/master/ankhbot.mrc) : right click this link and "save link as..." to your mIRC directory.

### Install Required Scripts
In mIRC, type in the following commands anywhere.  Accept and run any initialization command prompts.  When loading the last script (ankhbot.mrc), you will have to enter some information into input boxes that will pop up:  

`/load -rs JSONForMirc.mrc`  
`/load -rs mTwitch.Core.mrc`  
`/load -rs mTwitch.DisplayName.mrc`  
`/load -rs msqlite.mrc`  
`/load -rs ankhbot.mrc`  

You will have to reconnect to the Twitch server after installing these scripts.  

### Download and Install Desired Scripts
For information on each script, see the [wiki](https://github.com/Blasman/mIRC-Twitch-Scripts/wiki).  You can also right click the links on the wiki and select "save link as..." and then use `/load -rs scriptname.mrc` just like the previous install instructions.  Do Not "save link as..." using the links on the main page, as they are links to the GitHub html pages.  

You may install as many of the games scripts as desired, as to prevent spam, most of the games are designed so that if one of them is currently being played by a user in the channel, then another game cannot be started by a user until that current game is completed.  

### Contact Info / Help  

By visiting my Twitch channel at http://www.twitch.tv/blasman13/profile , you may Twitch message me regarding any help that you may require with anything on this GitHub, and/or make a donation for my hard work by clicking on the donation link. Before messaging me for help, please make sure that you are using the most recent updates of the scripts on this GitHub, as I am constantly updating the scripts here, and many scripts require newly added segments of other scripts. For general mIRC help, consider joining the [mirchelp](http://www.twitch.tv/mirchelp) chat on Twitch.  

#### Channels Currently Running These Scripts  

A few of the channels currently using some of the scripts on this GitHub:  
[Blasman13](http://twitch.tv/Blasman13/profile/) | [xxxDESPERADOxxx](http://twitch.tv/xxxDESPERADOxxx/profile/) | [AeroGarfield29](http://twitch.tv/AeroGarfield29/profile/) | [wgrates](http://twitch.tv/wgrates/profile/) | [A_Colder_Vision](http://twitch.tv/A_Colder_Vision/profile/) | [Tygastripe](http://twitch.tv/Tygastripe/profile/) | [XinarTheNeko](http://twitch.tv/XinarTheNeko/profile/) | [BruisedAngel](http://twitch.tv/BruisedAngel/profile/) | [TheYasmein](http://twitch.tv/TheYasmein/profile/) | [CreepurQT](http://twitch.tv/CreepurQT/profile/) | [Queen_bad](http://twitch.tv/Queen_bad/profile/)  

