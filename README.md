SPT - Coop - Launcher and Client Documentation

If you do not follow this step by step you will likely run into issues. Make
sure to take your time and read each step carefully.

Make sure any application you start is started as administrator to
avoid any issues!

Prerequisite - Install dependencies
  1. .Net Framework 4.7.2 or higher is installed
    a. https://dotnet.microsoft.com/en-us/download/dotnet-framework
    b. Follow the installer instructions and should be good to go.
  2. .net core 6 desktop runtime or higher
    a. https://dotnet.microsoft.com/en-us/download/dotnet
    b. Follow the installer instructions and should be good to go.

Step 1 - Creating Folders
  1. Make new folder in C:\Program Files\ called SITcoopClient
  2. Make new folder in C:\Program Files\SITcoopClient\ called SITgame
  3. Make new folder in C:\Program Files\SITcoopClient\ called SITlauncher
     
Step 2 - Downloading Required Files
  1. Download the latest version of the launcher from the link provided.
    a. https://github.com/paulov-t/SIT.Launcher/releases
    b. In this example we will use this version - SIT-Launcher.Release-84.zip
  2. Download the latest version of the SPT-AKI Patcher/Downgrader from the link provided.
    a. https://hub.sp-tarkov.com/files/file/204-aki-patcher/#versions
    b. The version you will pick will depend on your official tarkov version. This can be
    found in the BSG Launcher in the bottom right corner.
      i. Say your official Tarkov client version is 13.5.0.25837. You will need the
      corresponding Patcher/Downgrader Version 13.5.0.25837 to 13.1.3.25206.
      ii. The portion of the Patcher/Downgrader in my example 13.1.3.25206
      refers to the version of Tarkov the latest SPT-AKI supports, so this will
      likely change over time.
     
Step 3 - Create Game Files and Downgrade Files For Compatibility
  1. Move to your official tarkov folder usually located at C:\Program Files\Battlestate
  Games\EFT
  2. Copy all the files in the EFT folder
    a. Make sure to copy the files and not move them into a different folder
  3. Move back to C:\Program Files\SITcoopClient\SITgame and CRTL + V to paste the files
  into the folder
  4. Move to your Downloads folder and move your AKI Patcher/Downgrade to C:\Program
  Files\SITcoopClient\SITgame
  5. Move to C:\Program Files\SITcoopClient\SITgame then unzip Patcher_13.5.0.25837_to_13.1.3.25206.zip
     and open the folder Patcher_13.5.0.25837_to_13.1.3.25206
    a. Remember this is just an example and your downgrader will likely have a
    different name.
    b. There may be two folders keep opening the folders until you see the files
    Aki_Patches and patcher
  6. First CRTL + A then use CRTL + C to highlight all the files and copy them
  8. Go back to the folder C:\Program Files\SITcoopClient\SITgame and CRTL + V to paste
  the files into the folder
    a. You can now delete the folder Patcher_13.5.0.25800_to_13.1.3.25206 and zip
    file Patcher_13.5.0.25800_to_13.1.3.25206.zip to save space
  9. Now start the patcher application and it will downgrade your current game version to the
  latest supported version of SPT-AKI

Step 4 - Creating Launcher and Starting it for the first time
1. Move to your Downloads folder and move the SIT-Launcher.Release-84.zip from your
downloads folder to C:\Program Files\SITcoopClient\SITlauncher
2. Go to folder C:\Program Files\SITcoopClient\SITlauncher and unzip
SIT-Launcher.Release-84.zip and open the folder SIT-Launcher.Release-84
3. First CRTL + A then use CRTL + C to highlight all the files and copy them
4. Go back to the folder C:\Program Files\SITcoopClient\SITlauncher and CRTL + V to
paste the files into the folder
a. You can now delete the folder SIT-Launcher.Release-84 and zip file
SIT-Launcher.Release-84.zip to save space
5. Go back to the folder C:\Program Files\SITcoopClient\SITlauncher
6. Start the SIT.launcher application and it will ask "No OFFLINE install found. Would you
like to install it now?"
a. Select “No”
7. Select "Settings" in the SIT Launcher and click "Change Offline Install Path"
8. Navigate to your folder C:\Program Files\SITcoopClient\SITgame and select the
"EscapeFromTarkov" application as your install path
9. Click on Play in the SIT Launcher and enter the IP address the SIT Server is located
a. e.g. http://10.0.0.5:6969
10. Create a Username and Password
a. *DO NOT USE ANY CREDENTIAL COMBINATION YOU USE FOR REAL
ACCOUNTS*
i. The username and password are not encrypted and someone listening to
your HTTP traffic can steal your credentials.
1
1. S
ele
c
t
L
a
u
n
c
h in
t
h
e
SIT
L
a
u
n
c
h
e
r
a
n
d if
t
h
e
S
e
rv
e
r is
s
e
t
u
p
p
r
o
p
e
rly
y
o
u
s
h
o
uld
c
o
n
n
e
c
t
wit
h
n
o is
s
u
e
s!
