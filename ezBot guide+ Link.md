# M.K

ezBot guide
EZBOT FOR BOTTING ACCOUNTS
Frist, you will need ezbot and Elobuddy, you can download it from HERE: https://github.com/fkingnoobgg/lolbot/releases/download/1.0.1.7/lolbot.v1.0.1.7.zip
ezBot is not made by me it is made by Tryller and updated by Hesa and fkingnoobgg
After you downloaded it extract it to a folder (its ok on your desktop)
===Config Part===
Enter settings.ini in config folder, now frist change your lol path folder
[GENERAL]
LauncherPath=Y:\games\League Of Legends\    Set this to where your league of legends folder is (where you installed LoL)
MaxBots=2                                                                   You can change this but it depends on your computer
MaxLevel=31                                                               Set this to 31 so you can bot accounts even if they are lvl 30 cause you cant reach lvl 31 in this game(IP Farm)
RandomSpell=false                                                    Set this to true IF you want the bot to take random spells each time (better set it to false so its more human-like, no one at lvl 30 will take cleanse and ghost)
Spell1=Ignite                                                                Set this to ignite/flash/heal or any spell that you want (THIS AND SPELL2 MUST NOT BE THE SAME)
Spell2=Heal                                                                  Set this to ignite/flash/heal or any spell that you want (THIS AND SPELL1 MUST NOT BE THE SAME)
PrintGameStats=false
GarenaLoLFolder=C:\GarenaLoL\GameData\Apps\LoL\     SET YOUR GARENA FOLDER (IF YOU DONT KNOW WHAT IS GARENA YOU CAN LEAVE THIS ALONE)
Language=en
 
[ACCOUNT]
MinDelay=1600   This is the delay between accounts, you can tweak a bit those numbers if you want but its not that important
MaxDelay=9485
BuyExpBoost=false This is if you want your account to buy xp boost (mostly you dont want it to spend your rp so you may want to set this to false)
 
[CHAMPIONS]
PickRandomlyFromThisList=true Here is the list that your bot will pick your champs from, be sure to have scripts for the champs that you put here
FirstChampionPick=Ashe
SecondChampionPick=Ashe
ThirdChampionPick=MasterYi
FourthChampionPick=MasterYi
FifthChampionPick=MasterYi
 
[LOLSCREEN]                                   
ReplaceLoLConfig=true          This will replace the LoL config file to have the resolution here (default its like this and its very small but you can still see if there is any problem)
SreenHeight=480    
SreenWidth=800
LOWPriority=true                      This will play even if your account has leave buster (better keep it true)
LOWGraphics=true                  This will set your lol graphics on low so your bots will have more FPS (better keep it true)
 
[FRIENDS]
QueueWithFriends=true                Here you can select to que your bots together, you need to change the leader name to your frist botting account and FristFriend and SecondFriend and the rest to your rest accounts
LeaderName=Leader Name
FirstFriend=Account1
SecondFriend=Account2
ThirdFriend=
FourthFriend=
 
IMPORTANT THE LEADER WILL BE LEADE IN YOUR ACCOUNTS.TXT TOO
 
[SHUTDOWN]       This will shut down your ezbot or pc (if you want your pc to be close too set AloseCloseComputer=true) after X amount of games, this didnt worked for me so i left it to 0
AfterXGames=0
AlsoCloseComputer=false
 
Accounts.txt
Account1|PASSWORD1l|SERVER|MAP|Member
Account2|PASSWORD2|SERVER|MAP|Member
Account3|PASSWORD3|SERVER|MAP|Leader
 
Now set your accounts, you can use how many accounts you want but you will need to change max accounts to Y accounts you have
Type your LOGIN NAME and PASSWORD FOR THAT ACCOUNT.
YOUR ACCOUNTS SERVER
1.NA
2.EUW
3.EUNE
4.KR
5.BR
6.TR
7.PBE (pbe works too)
8.RU
9.OCE
10.LAS
11.JP
Garena servers work too
SG, MY, TW, TH, PH, VN
 
EXAMPLE MODES
Example modes are:
INTRO_BOT - Intro Bot....
BEGINNER_BOT
MEDIUM_BOT
BOT_3x3
NORMAL_5x5
NORMAL_3x3
ARAM
Example config should look like this
Username1|Password1|EUNE|ARAM|Member
Username|Password|EUNE|ARAM|Leader
 
