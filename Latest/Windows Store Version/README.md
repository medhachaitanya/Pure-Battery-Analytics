# Install from the [Microsoft Store](https://www.microsoft.com/store/productId/9N3HDTNCF6Z8) - The easiest way 

# How to install manually ? - The easy way 
(another way to install at the end of the page)
* Download the zip file from [Windows Store Version](https://github.com/medhachaitanya/PureBatteryAddOnSetup/blob/master/Latest/Windows%20Store%20Version/PureBatteryAddOnPackage_1.0.17.0_StoreVersion.zip) folder.
* Extract the zip
  * Right-click on install.ps1 and choose -> run with powershell. You can choose option A or option R as required.
* After installing, open the app and you should see the add-on running in your taskbar.
* Right click and configure settings based on your preferences.
* You're all set!

# What's new?
-You can now bold the percentage digits shown in the system-tray. 

-Performance improvements and bug fixes.

-Launch Pure battery right from the tray icon.

-Add as many as battery percentage values to get notified accordingly. 

I understand everyone has their own requirements. Not one size fits all.
Based on the feedback that I have received,
  * Few wanted to get notified at 30,90.
  * Few wanted to get notified at 10,15,25,30,90.
  * Few at every percentage from 10 to 20.  
  
So, I thought separating the values with commas is a simple way to satisfy different requirements. Please let me know if you have any other ideas or suggestions.

# Screenshots

![System-Tray](https://github.com/medhachaitanya/PureBatteryAddOnSetup/blob/master/Screenshots/Screenshot%202023-05-11%20231018.png)
![App Settings](https://github.com/medhachaitanya/PureBatteryAddOnSetup/blob/master/Screenshots/Screenshot%202023-06-01%20170515.png)
![Icon Settings](https://github.com/medhachaitanya/PureBatteryAddOnSetup/blob/master/Screenshots/Screenshot%202023-06-01%20170547.png)

# Examples 
  * 20 - Notifies only when battery is 20%
  * 30,90 - Notifies when battery is 30% or 90%.
  * 10,50,80,90 - Notifies whenever battery is 10% or 50% or 80% or 90%.
  * 15,16,17,18,19,20 - If you want to be notified at every percentage from 15-20.
  * 15,15 - Any duplicates are ignored internally. So, DO NOT assume that 15,15 will raise the notifications twice.
  * There's no restriction on the number of values given. But practically, you can give only 93 values as battery ranges from 7-100 and duplicates are ignored. Windows by default hiberates if the battery is less than 7%.
  
# Requirements
This application requires:

 * The latest [.NET Framework 4.8.](https://dotnet.microsoft.com/download/dotnet-framework/net48)
 * Windows 10 with Anniversary Update (10.0 build 14393) or later


This project/software is made free so that more people can use it. 
To help me continue working on making this app better, please consider donating any amount(tiny/small/big) that you wish to. 

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=karri.15%40wright.edu&currency_code=USD&source=url)


# Is there any another way to install ?

## Step 1 - With an example certificate. You will see PureBatteryAddOnPackage_1.0.13.0_x86_x64_arm_arm64.cer
![Step 1](https://github.com/medhachaitanya/YGIC-Photo-Maker/blob/master/AppReleases/Images/Step%201.PNG)
## Step 2
![Step 2](https://github.com/medhachaitanya/YGIC-Photo-Maker/blob/master/AppReleases/Images/Step%202.PNG)
## Step 3
![Step 3](https://github.com/medhachaitanya/YGIC-Photo-Maker/blob/master/AppReleases/Images/Step%203.PNG)
## Step 4
![Step 4](https://github.com/medhachaitanya/YGIC-Photo-Maker/blob/master/AppReleases/Images/Step%205.PNG)
## Step 5
![Step 5](https://github.com/medhachaitanya/YGIC-Photo-Maker/blob/master/AppReleases/Images/Step%206.PNG)
## Step 6
![Step 6](https://github.com/medhachaitanya/YGIC-Photo-Maker/blob/master/AppReleases/Images/Step%207.PNG)
## Step 7
![Step 7](https://github.com/medhachaitanya/YGIC-Photo-Maker/blob/master/AppReleases/Images/Step%208.PNG)
## Step 8
Install setup.msixbundle
