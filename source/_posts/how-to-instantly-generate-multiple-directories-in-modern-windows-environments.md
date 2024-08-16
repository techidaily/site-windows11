---
title: How to Instantly Generate Multiple Directories in Modern Windows Environments
date: 2024-08-15T15:44:26.911Z
updated: 2024-08-16T15:44:26.911Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Instantly Generate Multiple Directories in Modern Windows Environments
excerpt: This Article Describes How to Instantly Generate Multiple Directories in Modern Windows Environments
keywords: WinDirGenInstantly,MultiWinDirCreation,QuickWindowsDirectories,InstantWinDirMaking,ModernWindowsMultiDirs,DirectoriesInWinOS,WindowsDirsGenFast
thumbnail: https://thmb.techidaily.com/de3aeccba8a1988fe712bc85cebc3af3bc3a21faab0414036ff801745dc15189.png
---

## How to Instantly Generate Multiple Directories in Modern Windows Environments

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
5. Give your file a name followed by **.bat**. For instance, we named our file as makeuseof.bat.  
![Notepad file name](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/notepad-file-name.jpg)
<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Expand the dropdown for Save as type and choose **All files**.
7. Click **OK** and close the Notepad.
8. Now, navigate to the location of the folder and open the bat file. Opening it should create the folders and their subfolders for you.

 Now that you have created multiple files and folders, [organizing these files on Windows](https://www.makeuseof.com/tag/automatically-organize-files-windows/) is also worth considering if you do not want to spend a lot of time looking for information in them. Additionally, Windows also allows you to [rename multiple folders at once](https://www.makeuseof.com/cool-folder-tips-windows/), which can be helpful when organizing them.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Once the Folder Frenzy dialog launches, type the names of the folders you want to create and click on the **Create Folder** button. These folders will be created in the Folder Frenzy file.  
![Create folder in Folder Frenzy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/folder-frenzy-create-folder.jpg)

 From here, you can even take a step further and learn [how to launch multiple programs with one shortcut on Windows](https://www.makeuseof.com/tag/launch-multiple-programs-single-shortcut-using-batch-file/) to increase your productivity at work or school. In case you no longer need the tool after creating bulk folders, you can uninstall it. This won't automatically delete the folders you have created using the tool, unless the uninstallation process explicitly offers to do so and you confirm that action.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-beginners-obs-techniques-for-youtube-live-streaming/"><u>[New] 2024 Approved  Beginner's OBS Techniques for YouTube Live Streaming</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-easy-peasy-the-route-to-past-facebook-stories/"><u>[Updated] In 2024, Easy Peasy  The Route to Past Facebook Stories</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-all-about-it-understanding-googles-podcast-service/"><u>2024 Approved  All About It  Understanding Google's Podcast Service</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-eliminating-frame-drops-in-obs-broadcasts/"><u>2024 Approved  Eliminating Frame Drops in OBS Broadcasts</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-the-finest-12-tycoons-your-pathway-to-gaming-enthusiasm/"><u>2024 Approved  The Finest 12 Tycoons  Your Pathway to Gaming Enthusiasm</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-unveiling-the-secrets-of-effective-screencasts/"><u>2024 Approved  Unveiling the Secrets of Effective Screencasts</u></a></li>
<li><a href="https://activate-lock.techidaily.com/3-easy-methods-to-unlock-icloud-locked-iphone-xsipadipod-by-drfone-ios/"><u>3 Easy Methods to Unlock iCloud Locked iPhone XS/iPad/iPod</u></a></li>
<li><a href="https://unlock-android.techidaily.com/7-ways-to-unlock-a-locked-infinix-smart-8-plus-phone-by-drfone-android/"><u>7 Ways to Unlock a Locked Infinix Smart 8 Plus Phone</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/8-ways-ai-chatbots-are-impacting-content-creation/"><u>8 Ways AI Chatbots Are Impacting Content Creation</u></a></li>
<li><a href="https://tech-hub.techidaily.com/ai-contenders-in-code-quest-the-battle-between-chatgpt-and-gemini-unveiled/"><u>AI Contenders in Code Quest: The Battle Between ChatGPT and Gemini Unveiled</u></a></li>
<li><a href="https://network-issues.techidaily.com/bloodied-barbarian-balance-adjustment/"><u>Bloodied Barbarian Balance Adjustment</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-or-see-text-messages-what-can-you-do-with-life360-on-vivo-y77t-drfone-by-drfone-virtual-android/"><u>Can Life360 Track Or See Text Messages? What Can You Do with Life360 On Vivo Y77t? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/five-fun-flicks-in-windows-cmd-world/"><u>Five Fun Flicks in Windows' CMD World</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-print-server-not-responding-issue/"><u>Fixing Print Server Not Responding Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/getting-the-0x0-0x0-error-code-in-windows-11-heres-how-to-fix-it/"><u>Getting the 0X0 0X0 Error Code in Windows 11? Here's How to Fix It</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-acoustiquest-investigating-soundscape/"><u>In 2024, AcoustiQuest  Investigating Soundscape</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-getting-the-pokemon-go-gps-signal-not-found-11-error-in-poco-c50-drfone-by-drfone-virtual/"><u>In 2024, Getting the Pokemon Go GPS Signal Not Found 11 Error in Poco C50 | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-iphone-14-pro-without-passcode-or-face-id-drfone-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 14 Pro without Passcode or Face ID | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-restarting-non-starting-windows-drivers/"><u>Mastering the Art of Restarting Non-Starting Windows Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/meet-asuss-latest-rivals-to-rog-ally-in-gaming/"><u>Meet ASUS’s Latest Rivals to ROG Ally in Gaming</u></a></li>
<li><a href="https://windows11.techidaily.com/mend-your-meeting-screen-display/"><u>Mend Your Meeting Screen Display</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-for-reviving-your-windows-11-password/"><u>Methods for Reviving Your Windows 11 Password</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-common-pin-hurdles-in-modern-windows-os-win10win11/"><u>Navigating Common PIN Hurdles in Modern Windows OS (Win10/Win11)</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-essential-elements-warning-in-windows-11/"><u>Navigating Through Essential Elements Warning in Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-your-contacts-after-realme-11x-5g-has-been-deleted-by-fonelab-android-recover-contacts/"><u>Recover your contacts after Realme 11X 5G has been deleted.</u></a></li>
<li><a href="https://windows11.techidaily.com/regaining-run-windows-past-execution/"><u>Regaining Run Window's Past Execution</u></a></li>
<li><a href="https://extra-hints.techidaily.com/remove-youtube-sneak-peeks-for-uninterrupted-views/"><u>Remove YouTube Sneak Peeks for Uninterrupted Views</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-chrome-setup-in-windows-11-systems/"><u>Seamless Chrome Setup in Windows 11 Systems</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/simplified-guide-uploading-urls-to-instagram-media-for-2024/"><u>Simplified Guide  Uploading URLs to Instagram Media for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-access-to-repair-solutions-customizing-hotkeys-for-win-1011/"><u>Speedy Access to Repair Solutions: Customizing Hotkeys for Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-successful-v22h2-updater-execution-on-win11/"><u>Strategies for Successful V22H2 Updater Execution on WIN11</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-driving-experience-with-free-upgrades-for-windows-users/"><u>Streamline Driving Experience with Free Upgrades for Windows Users</u></a></li>
<li><a href="https://howto.techidaily.com/top-10-fixes-for-phone-keep-disconnecting-from-wi-fi-on-oneplus-nord-ce-3-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 10 Fixes for Phone Keep Disconnecting from Wi-Fi On OnePlus Nord CE 3 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-error-code-9999-in-win-based-audacity/"><u>Unraveling the Mystery of Error Code 9999 in Win-Based Audacity</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-windows-11s-elevation-failures/"><u>Unraveling the Mystery of Windows 11’S Elevation Failures</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-end-task-control-capabilities-in-windows-11-ui-environment/"><u>Unveiling End Task Control Capabilities in Windows 11 UI Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/utilizing-rgb-lighting-on-win11-pcs/"><u>Utilizing RGB Lighting on Win11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-establishing-kids-online-boundaries/"><u>Windows 11: Establishing Kids' Online Boundaries</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-watchlist-7-tasks-to-inspect-for-hidden-viruses/"><u>Windows Watchlist: 7 Tasks to Inspect for Hidden Viruses</u></a></li>
</ul></div>
