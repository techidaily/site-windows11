---
title: Batch Folder Generation in Windows 11 for Efficiency Boost
date: 2024-07-11T22:11:16.401Z
updated: 2024-07-12T22:11:16.401Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Batch Folder Generation in Windows 11 for Efficiency Boost
excerpt: This Article Describes Batch Folder Generation in Windows 11 for Efficiency Boost
keywords: Win11 Batch Creation,Efficient Folder Gen,Efficiency Increase,Windows Optimization,Speed Up Folders,Batch Generator Pro,Productivity Tools Win11
thumbnail: https://thmb.techidaily.com/d8f2922d20e310fe909f77a8d8b81c6fbacf60f301e5bf6586c75f1b0b08c5ac.jpeg
---

## Batch Folder Generation in Windows 11 for Efficiency Boost

 The latest Windows versions allow you to automate quite a few of your tasks, for instance letting you create multiple folders and sub-folders at once. This is quite helpful in situations where you need to sort out the data (for each semester, for instance) and do not want to spend hours doing it.

 There is more than one method of creating multiple files and folders in Windows, and we have outlined the best ways of doing so for you below. Read through the methods and proceed with the one you want.

## 1\. Use the Command Prompt to Create Multiple Folders at Once

 In this first method, we will be using a command-line utility called Command Prompt in Windows. Unless you are very tech-savvy, you may not have noticed it anywhere in Windows, but it has been around for quite a long time.

 Typically, administrators use it to make advanced-level changes throughout the system. You can enter text-based commands to automate a bunch of tasks.

 Below, we have listed detailed steps for using Command Prompt to create multiple folders at once. Make sure you are signed in to Windows as an administrator before you proceed:

1. Type **Command Prompt** in Windows search and click on **Run as administrator**.
2. Alternatively, you can also open Run by pressing **Win** \+ **R** and type **cmd** in the text field. Press **Ctrl** \+ **Shift** \+ **Enter** to open Command Prompt as an administrator.  
![Run dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/accessing-cmd-through-run-box.jpg)
3. Click **Yes** in the User Account Control prompt.
4. Type the following command in the Command Prompt window and hit **Enter** to execute it. Make sure to replace the \[location\] with the location where you want to create multiple folders.  
`cd /d [location]`
5. For instance, if we want to create folders in the C:\\users\\hp\\documents folder, we will execute the command like cd /d C:\\users\\hp\\documents.  
![Location command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win11-cd-d-location-1.jpg)
6. Then, type **md** following the names of the folders in one command and execute it. For instance, if we want to create folders for the first 4 months of the year. We will execute the command as:  
`md january february march april`  
![Command with file names](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win11-md-files.jpg)
7. Once done, close the Command Prompt window and visit the location of folders in File Explorer to see if the folders have been created.

 If for some reason using the Command Prompt does not work for you, you can use Windows Powershell (Admin) to perform the same steps. The Powershell works almost the same as Command Prompt, but it is much more powerful than cmd.

 To use Powershell, follow these steps:

1. Right-click on the **Windows icon** on your taskbar and choose **Powershell (Admin)**.  
![Windows Terminal (Admin)](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/windows-terminal.jpg)
2. Select Yes in the UAC prompt.  
![UAC prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win11-terminal-uac.jpg)
3. Now, execute the command mentioned below and change the \[Location\] with your targeted location for creating the folders.  
`cd [Location]`
4. We want to create the sub-folders in the document folders, so we will be executing the following command:  
`cd C:\users\hp\documents`  
![Execute location command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win11-terminal-cd-d-location.jpg)
5. Once done, execute the following command. Replace the \[foldername\] with the names you want to give the folders.  
`md "[foldername]", "[foldername]", "[foldername]", "[foldername]"`
6. For instance, if we want to create folders for the first 4 months of the year. We will execute the command as:  
`md "january", "february", "march", "april"`  
![File names command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win11-terminal-md-files.jpg)

 Finally, close the Powershell window and check if the folders have been created.

## 2\. Use the Notepad to Create Multiple Folders at Once

 Though it may come as a surprise, the Windows Notepad can perform more advanced technical operations than just writing to-do lists.

 The methods above are suitable if you only want to create multiple folders without any subfolders. If you wish to create subfolders as well, then an easy way to do it is by creating a batch script via Notepad.

 Here is how you can do that:

1. Type **Notepad** in Windows search and click **Open**.
2. In the Notepad window, click type **@ECHO OFF** and click **Enter**.
3. Then type **md** followed by the folder and subfolder names enclosed in double quotes. For instance, if we want to create a MUO January folder with a Windows subfolder and a MUO February folder with an Android subfolder, we will type it down in Notepad as:  
`@ECHO OFF  
md "MUOJan"\"Windows" "MUOFeb"\"Android"`  
![Notepad command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win11-notepad-command.jpg)
4. After you have typed down the names of all the folders and subfolders that you want to create, navigate to **File** in the top-left corner and choose **Save as**.  
![Save as option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/notepad-save-as.jpg)
5. Give your file a name followed by **.bat**. For instance, we named our file as makeuseof.bat.  
![Notepad file name](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/notepad-file-name.jpg)
6. Expand the dropdown for Save as type and choose **All files**.
7. Click **OK** and close the Notepad.
8. Now, navigate to the location of the folder and open the bat file. Opening it should create the folders and their subfolders for you.

 Now that you have created multiple files and folders, [organizing these files on Windows](https://www.makeuseof.com/tag/automatically-organize-files-windows/) is also worth considering if you do not want to spend a lot of time looking for information in them. Additionally, Windows also allows you to [rename multiple folders at once](https://www.makeuseof.com/cool-folder-tips-windows/), which can be helpful when organizing them.

## 3\. Use a Third-Party Application

 Last but not least, if you think using Command Prompt and Notepad is too time-consuming, you can try using a third-party application.

 There are quite a few apps that can help you achieve this, including the following:

* [Soboloft](https://www.sobolsoft.com/file-management.htm)
* [Text 2 Folders](https://www.softpedia.com/get/System/File-Management/Text-2-Folders.shtml)
* [Folder Frenzy](https://www.softpedia.com/get/System/File-Management/Folder-Frenzy.shtml)
* [FreeCommander XE](https://freecommander.com/en/summary/)
* [XMD](https://www.softpedia.com/get/System/File-Management/XMD.shtml)

 For illustration purposes, we will be using Folder Frenzy. The steps of creating multiple folders in other applications might vary, but the basics will remain the same.

1. Download Folder Frenzy.
2. Extract the downloaded file and then launch it.
3. Click **Yes** in the confirmation prompt.  
![Clicking Yes in the UAC prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/folder-frenzy-agreement.jpg)
4. Once the Folder Frenzy dialog launches, type the names of the folders you want to create and click on the **Create Folder** button. These folders will be created in the Folder Frenzy file.  
![Create folder in Folder Frenzy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/folder-frenzy-create-folder.jpg)

 From here, you can even take a step further and learn [how to launch multiple programs with one shortcut on Windows](https://www.makeuseof.com/tag/launch-multiple-programs-single-shortcut-using-batch-file/) to increase your productivity at work or school. In case you no longer need the tool after creating bulk folders, you can uninstall it. This won't automatically delete the folders you have created using the tool, unless the uninstallation process explicitly offers to do so and you confirm that action.

## Create Multiple Folders in a Few Clicks on Windows

 Creating several folders manually is a mundane task, and you can spend the same energy doing something more productive. The steps we have outlined above should help you automate this task, saving time for things that actually bring in some value.

 The latest Windows versions allow you to automate quite a few of your tasks, for instance letting you create multiple folders and sub-folders at once. This is quite helpful in situations where you need to sort out the data (for each semester, for instance) and do not want to spend hours doing it.

 There is more than one method of creating multiple files and folders in Windows, and we have outlined the best ways of doing so for you below. Read through the methods and proceed with the one you want.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-content-creator.techidaily.com/in-2024-system-requirements-for-running-premiere-pro-how-to-set-up-computer/"><u>In 2024, System Requirements for Running Premiere Pro How to Set Up Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/safekeep-your-files-setting-up-folder-restrictions-in-windows-11/"><u>Safekeep Your Files: Setting Up Folder Restrictions in Windows 11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-elevate-your-videos-auditory-experience-on-youtube/"><u>[New] Elevate Your Video's Auditory Experience on YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-could-not-initialize-vm-error-on-pc/"><u>Overcome 'Could Not Initialize VM' Error on PC</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-speed-up-or-slow-down-top-10-free-video-editing-apps-for-mobile/"><u>2024 Approved Speed Up or Slow Down Top 10 Free Video Editing Apps for Mobile</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-resolve-code-0x0001-glitch-in-w10w11-setup/"><u>Methods to Resolve Code 0X0001 Glitch in W10/W11 Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/take-control-of-your-workflow-learn-these-essential-cmd-commands/"><u>Take Control of Your Workflow: Learn These Essential CMD Commands</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-dos-and-donts-of-youtube-promo-video-making/"><u>In 2024, The Do's and Don’ts of YouTube Promo Video Making</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-auto-lock-settings-in-windows/"><u>Navigate Auto-Lock Settings in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/premium-collection-winning-windows-dsswitch-emulators-list/"><u>Premium Collection: Winning Windows DS/Switch Emulators List</u></a></li>
<li><a href="https://windows11.techidaily.com/sparkle-up-windows-11-for-the-festive-season/"><u>Sparkle Up Windows 11 for the Festive Season</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-tweet-town-ranking-the-trending-threads/"><u>2024 Approved  Tweet Town  Ranking the Trending Threads</u></a></li>
<li><a href="https://windows11.techidaily.com/moment-by-moment-synchronize-windows-clock/"><u>Moment by Moment: Synchronize Windows Clock</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-error-0x80042306-on-windows-to-reset-successfully/"><u>Tackling Error 0X80042306 on Windows to Reset Successfully</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/filmora-13-free-download-professional-video-editing-software/"><u>Filmora 13 Free Download Professional Video Editing Software</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-photoshop-and-beyond-top-monitors-reviewed-editors-picks/"><u>2024 Approved  Photoshop & Beyond  Top Monitors Reviewed [Editors' Picks]</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-windows-1111-shop-glitch-x800704cf/"><u>Preventing Windows 11/11 Shop Glitch X800704CF</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-failed-zip-operations-on-win-11-system/"><u>Recovering Failed ZIP Operations on Win 11 System</u></a></li>
<li><a href="https://windows11.techidaily.com/removing-the-rust-of-access-denied-in-windows/"><u>Removing the Rust of 'Access Denied' In Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-to-mending-directdraw-glitches-in-11-series-oses/"><u>Quick Guide to Mending DirectDraw Glitches in 11-Series OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-non-attached-usb-device-dilemma-in-virtualbox-environment/"><u>Tackling Non-Attached USB Device Dilemma in VirtualBox Environment</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/the-fiscal-footprint-of-a-gigantism-icon/"><u>The Fiscal Footprint of a Gigantism Icon</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-explore-top-ringtones-for-pixel-devices/"><u>2024 Approved  Explore Top Ringtones for Pixel Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagining-taskbar-functionality-essential-upgrades-to-improve-microsofts-user-interface/"><u>Reimagining Taskbar Functionality: Essential Upgrades to Improve Microsoft's User Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-obstacles-inaccessible-network-router-interface/"><u>Overcoming Obstacles: Inaccessible Network Router Interface</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-activation-lock-from-apple-iphone-12-pro-max-or-ipad-by-drfone-ios/"><u>How to Bypass Activation Lock from Apple iPhone 12 Pro Max or iPad?</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-corruption-unlock-write-permissions-in-win10win11/"><u>Overcoming Corruption: Unlock Write Permissions in Win10/Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-chromeedge-from-hiding-taskbar-on-large-screens/"><u>Preventing Chrome/Edge From Hiding Taskbar on Large Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-spotify-connection-errors-in-win11/"><u>Tackling Spotify Connection Errors in Win11</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-8-safe-and-effective-methods-to-unlock-your-iphone-6-plus-without-a-passcode-by-drfone-ios/"><u>In 2024, 8 Safe and Effective Methods to Unlock Your iPhone 6 Plus Without a Passcode</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-roadblocks-activating-non-functional-scripts-in-windows/"><u>Overcoming Roadblocks: Activating Non-Functional Scripts in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-browser-security-incorporating-trusted-websites-in-windows-11/"><u>Personalize Browser Security: Incorporating Trusted Websites in Windows 11</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-launching-into-the-spotlight-instagram-lives-for-2024/"><u>[Updated] Launching Into the Spotlight  Instagram Lives for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharge-efficiency-select-windows-software-for-success/"><u>Supercharge Efficiency: Select Windows Software for Success</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-and-streamlined-drive-access-via-new-os-win11/"><u>Secure & Streamlined Drive Access via New OS (Win11)</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-absence-of-display-on-remote-workspace-win/"><u>Overcoming Absence of Display on Remote Workspace Win</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-fix-pokemon-go-route-not-working-on-asus-rog-phone-7-drfone-by-drfone-virtual-android/"><u>How to Fix Pokemon Go Route Not Working On Asus ROG Phone 7? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-easily-unlock-your-oppo-k11-5g-device-sim-by-drfone-android/"><u>In 2024, Easily Unlock Your Oppo K11 5G Device SIM</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-re-establish-winning-online-wol-experience/"><u>Steps to Re-Establish Winning Online WoL Experience</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-a-realme-narzo-n53-easily-by-drfone-android/"><u>In 2024, How To Unlock a Realme Narzo N53 Easily?</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-a-stuck-discord-interface-element-on-your-system/"><u>Mending a Stuck Discord Interface Element on Your System</u></a></li>
</ul></div>
