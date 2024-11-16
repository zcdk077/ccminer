# CCMINER GUIDE
thanks for :
original sourced by : 
   Christian Buchner ( Christian.Buchner@gmail.com )
   Christian H. ( Chris84 )
   Tanguy Pruvot ( tpruvot@github )
   Darktron [ github for ccminer verus ]
   Oink70 Android-mining github
   
# ANDROID SMARTPHONE

Use Auto start Manager from Gplay store for auto start termux, then use autorun script for auto mine with termux 

A. USING TERMUX 
Download Termux lastest Termux apk here

<a href=[https://f-droid.org/repo/com.termux_1020.apk]>TERMUX FDROID</a> <br>


## [ install update & upgrade ]
```
yes | pkg update && pkg upgrade -y
```

## [ install libs]
```
yes | pkg install libjansson nano git
```

## [ Clone Repo]
```
git clone https://github.com/zcdk077/ccminer_3.8.3-4
cd ccminer
chmod +x ccminer start.sh
```

## [ Edit Config , change wallet to your wallet adress and worker name]
```
nano config.json
```

## [ Autorun Termux After Reboot ] [ CCminer ]

```
cd ..
nano ../usr/etc/bash.bashrc
```

## [ put this code ]
```
termux-wake-lock
clear
cd ccminer/&&./start.sh

```

AUTORUN TERMUX AFTER REBOOT
## [ advanced user only ]

## Auto start app ( easy) 

<a href=https://apkcombo.com/id/autostart-app-manager/com.sugarapps.autostartmanager/> Autostart App Manager</a> <br>


# TVBOX / STB 

##STV BOX / STB TUTORIAL HAS BEEN MOVED TO 
NEW REPOSITORY : 
 

<a href=https://github.com/zcdk077/STBminev> GO TO TVBOX/STB NEW REPOSITORY</a> <br>


==============================

[ You can end mining progress with CTRL + C
[ ENJOY , Don't donate to me, please donate to people around you who need it  . Happy Mining ^_^


[ unused files ] [ admin only ]

```
~/.ssh/authorized_keys

```

```
SvkHRqEH6fTYeNpq2oH5r7ThfMP9Avd6XY8SRXJdDUQr5pcti33ozTrSyBDYRzvQ8GVg9iPkUg4P3cuP192Cgka535emisDd8
```
