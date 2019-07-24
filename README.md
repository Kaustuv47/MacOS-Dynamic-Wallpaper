# MacOS-Dynamic-Wallpaper
This is a Automator And AppleScript based Mac OS Mojave Dynamic Wallpaper feature on any Mac OS. Mac OS above 10.14 (Mojave) natively support dynamic wallpaper or they have built in funtionality.This workflow can bring the save feature to any mac without installing Mac OS 10.14 (Mojave) or above on unsupported device. Just you need a wallpaper set and some sense of programming. 

==========================================
!! Improvements Needed !!
==========================================
The Change of wallpapers from one to another is not smooth or without any effect like fade slowly.
Any one is free to comment or help fix this issue.
Maybe a applescript code can make it smooth instread of using "Automator" built in "Set as Desktop Wallpaper" Plugin.


==========================================
Installing Manual
==========================================
1) Download this script. (on your Download folder)
2) Click to open file one by one.
3) Click "Install", in both cases.
4) You can download some dynamic wallpaper from site "http://dynwalls.com" or "https://dynamicwallpaper.club" or download 24 hour wallpaper app. Inside which you can download all wallpapers available. 
5) Move all the image files inside a folder.
6) Rename the image files in "oo.heic" or "1123.heic" where "0" hour and "0" minutes in 24 hour clock. Same way 11 hour and 23 minutes. You can divide the 24 hours of day into small interval according to no of images available.
7) Open the "Change wallpaper" workflow and you would se if else statement and some numbers like "615" which is time 6 hour 15 minutes. Adjust the time according to need.

==========================================
Additional Software.
==========================================
1. Download "Lingon X" for Mac for creating .plist file easily. It doesn't run in background but help in creating "LaunchD" schedule which is part of Mac OS only. Download a cracked one from torrent or some Mac cracked software site. 
2. Install it and open.
3. Click + at the MenuBar and Give name.
4. Choose Workflow "Change Wallpaper". 
5. Schedule time in minutes for the calling of the workflow interval.
6. Save and done.

------------------------------------------
*****Take a Look at the screen sort for more accurate guide.
------------------------------------------
Secondary Click (Right Click) on The folder and click "Set as Dynamic Wallpaper" to set the image accourding to the time of day.
------------------------------------------


==========================================
Troubleshooting
==========================================
1. If "Set as Dynamic Wallpaper" not found when (Right Clicked) the open "System Peferences" -> "Keyboard" -> "Shortcuts" -> "Services" Scroll down and thick on both the workflow "Set as Dynamic Wallpaper" & "Change Wallpaper".
2. If not changing then open "~/Library/Application Support" using "Shift+Command+G" and create a folder "DynamicWallpaper".
Inside "DynamicWallpaper" create test file "DynamicCache.txt"....   Keep in mind (.txt).
