# How to install the beta version ?

* Download the zip file from [latest-beta](https://github.com/medhachaitanya/PureBatteryAddOnSetup/blob/master/Latest/beta/latest-beta.zip) folder, extract it and right-click on install.ps1 and choose -> run with powershell.
You can choose option A or option R as required. 

* I am working to get this software to the MS store so that you can download it from there directly. Just some more time. Thank you.

* Extract the zip
  * Right-click on install.ps1 and choose -> run with powershell. You can choose option A or option R as required.
  * Ignore if there are any windows smartscreen warnings as shown in [Step 2](https://github.com/medhachaitanya/PureBatteryAddOnSetup/blob/master/Step%202_%20Very%20Imp%20-%20Read%20and%20Understand.png).
* If you want to know why Windows is showing the smartscreen warning you can read -> [Read the reason](https://github.com/medhachaitanya/PureBatteryAddOnSetup/blob/master/Step%202_%20Very%20Imp%20-%20Read%20and%20Understand.png)
* After installing, you should see the add-on running in your taskbar.
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

![System-Tray](https://github.com/medhachaitanya/PureBatteryAddOnSetup/blob/master/Screenshots/SystemTray.PNG)

![You can now choose to notify at multiple battery percentages](https://github.com/medhachaitanya/PureBatteryAddOnSetup/blob/master/Screenshots/LatestScreenshot.png)

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
