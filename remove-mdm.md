# [Please see the README file before viewing the information in this file.](README.md)

## Below are the necessary steps that allow a user to bypass any MDM restrictions on an iPad.

### 1. Before doing anything, you must download the required apps on a Windows 10 computer:
  - Download iBackupBot app on a Windows 10 computer
  - Download Apple iTunes app on the Win 10 PC (allows the computer to access iPad files)
  - Connect iPad to the computer using a lightning to USB cable.
  - Press “Yes” on iPad when it asks if you want to trust the computer
  - Go to Display & Brightness in settings, set screen timeout to never 
  - Remove iPad password if needed
### 2. Then, backup all files on the iPad just in case anything goes wrong.
  - Make two backups
  - One backup will be modified
  - The other backup will be a normal backup just in case
  - Rename the backups accordingly
### 3. This is the main part where we modify the configuration profiles on the mobile device. 
  - Open the modified backup in iBackupBot desktop application
  - Search up “config” in main directory
  - Click on “ConfigurationProfiles" file folder
  - Remove the profiles that contain any restriction commands:
    - Warning - ONLY delete the files that restrict the device from downloading or connecting to any apps or VPNs, and nothing else.
    - A profile that restricts VPNs will have a list of VPN networks and their addresses (e.g.: "hotspotshield.com"). Delete this file.
    - A profile that restricts any apps from being downloaded from the App Store will contain any code that prevents downloads (these files are easily distinguishable from others)
    - On my iPad, I needed to remove the files that started with these characters (this may be different for every organization, but I am documenting it here:
      - vpn profile: 8eab4842..
      - restrictions 1: 973342024b65ca..
      - restrictions 2: b8cec5a9..
### 4. Now, we will load the modified backup file (without restrictions) onto the school iPad 
  - Select entire directory of modified backup
  - Press load backup button at top of screen
  - Wait for the backup to load onto the iPad
  - iPad will restart and load - this will take some time
### 5. Download apps onto iPad
  - Connect to an internet connected WiFi network on the iPad
  - Create a burner email account with any service (usually gmail is preferred)
  - Go to appleid.apple.com
  - Create Apple ID using the gmail account
  - Log into Apple ID on the iPad’s app store
  - Now you can download any apps onto the school iPad.
### 6. Verify full system functionality
  - Run all apps and make sure they work.


#  
Copyright © 2023 Guhoo Technology LLC. All rights reserved
