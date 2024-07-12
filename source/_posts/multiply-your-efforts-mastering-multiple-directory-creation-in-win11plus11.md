---
title: "Multiply Your Efforts: Mastering Multiple Directory Creation in Win11+11"
date: 2024-07-11T21:41:34.131Z
updated: 2024-07-12T21:41:34.131Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Multiply Your Efforts: Mastering Multiple Directory Creation in Win11+11"
excerpt: "This Article Describes Multiply Your Efforts: Mastering Multiple Directory Creation in Win11+11"
keywords: Win11 DirCreation Skills,Multiply DirCreation Effort,Master Win11+11 Directory,Learn Multiple Directories,Enhance Win11 DirSkill,Boost Win11+DirEfforts,Optimize 11+11 Directory Creation
thumbnail: https://thmb.techidaily.com/2a86960040387567ee8a74265a39e135c9493f594810dac12c910c9d9ffd0bfb.jpg
---

## Multiply Your Efforts: Mastering Multiple Directory Creation in Win11+11

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
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-an-introductory-overview-using-ez-grabber-software/"><u>[New] 2024 Approved  An Introductory Overview  Using EZ Grabber Software</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-dual-device-names-on-your-windows-network/"><u>Preventing Dual Device Names on Your Windows Network</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-11s-insufficient-uninstall-rights/"><u>Fixing Windows 11'S Insufficient Uninstall Rights</u></a></li>
<li><a href="https://howto.techidaily.com/stuck-at-android-system-recovery-of-samsung-galaxy-a24-fix-it-easily-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Stuck at Android System Recovery Of Samsung Galaxy A24 ? Fix It Easily | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-the-already-in-use-local-device-name-mistake-on-pcs/"><u>Remedy the 'Already in Use' Local Device Name Mistake on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/harness-window-11-a-productivity-playbook/"><u>Harness Window 11: A Productivity Playbook</u></a></li>
<li><a href="https://windows11.techidaily.com/security-enhancement-manual-add-a-self-designed-lock-pattern/"><u>Security Enhancement Manual: Add a Self-Designed Lock Pattern</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-perfect-pairing-transferring-camera-roll-content-effortlessly-to-snapchat-for-2024/"><u>[New] Perfect Pairing  Transferring Camera Roll Content Effortlessly to Snapchat for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reinvigorate-windows-search-top-11-remedies-explored/"><u>Reinvigorate Windows Search: Top 11 Remedies Explored</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-command-control-on-windows-with-sudo/"><u>Maximizing Command Control on Windows with Sudo</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reinvigorate-the-essential-wsreset-process/"><u>How to Reinvigorate the Essential WSReset Process</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-premier-recommendations-best-iphone-tones-designers/"><u>In 2024, Premier Recommendations  Best iPhone Tones Designers</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-absence-of-windows-1011-search-outcomes/"><u>Solving Absence of Windows 10/11 Search Outcomes</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11s-network-failure-0x800704b3/"><u>Navigating Windows 11'S Network Failure 0X800704B3</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-the-absence-of-dxgidll-in-new-os-windows-11/"><u>Mending the Absence of Dxgi.dll in New OS, Windows 11</u></a></li>
<li><a href="https://ai-video.techidaily.com/new-an-exhaustive-list-of-lip-sync-apps-for-vibrant-video-creation/"><u>new An Exhaustive List of Lip Sync Apps for Vibrant Video Creation</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-speedy-strategies-capturing-your-screen-in-a-flash-dell/"><u>[Updated] Speedy Strategies  Capturing Your Screen in a Flash (Dell)</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-extract-and-play-fb-soundtracks-for-2024/"><u>[Updated] Extract and Play FB Soundtracks for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/get-to-safety-six-steps-to-entering-safe-mode-in-windows-11/"><u>Get to Safety: Six Steps to Entering Safe Mode in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-icon-positioning-in-windows/"><u>Mastering Icon Positioning in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/extend-the-time-windows-11-spends-in-shutdown-with-ongoing-jobs/"><u>Extend the Time Windows 11 Spends in Shutdown with Ongoing Jobs</u></a></li>
<li><a href="https://windows11.techidaily.com/power-preservation-pitfalls-the-reality-of-modern-standby/"><u>Power Preservation Pitfalls: The Reality of Modern Standby</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-words-silent-mode-fix-for-pc-users/"><u>Microsoft Word's Silent Mode Fix for PC Users</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11-multi-display-setup/"><u>Navigating Windows 11 Multi-Display Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/reinitializing-distro-and-catroot2-in-w11-a-step-by-step-guide/"><u>Reinitializing Distro & Catroot2 in W11: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-software-removal-context-menu-optimization-for-win-1011/"><u>Simplifying Software Removal: Context Menu Optimization for Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tricks-to-pinpoint-your-graphic-card-on-windows-11/"><u>Quick Tricks to Pinpoint Your Graphic Card on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/improve-file-selection-techniques-activating-windows-11-boxes/"><u>Improve File Selection Techniques: Activating Windows 11 Boxes</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-remove-the-show-more-options-entry-from-the-context-menu-on-windows-11/"><u>How to Remove the Show More Options Entry From the Context Menu on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-missed-files-in-steam-and-windows-11/"><u>Overcoming Missed Files in Steam & Windows 11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/sim-unlock-oneplus-ace-2-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>Sim Unlock OnePlus Ace 2 Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-breathe-new-life-into-your-mac-a-guide-to-freeing-up-space-and-improving-fcpx-performance-for-2024/"><u>New Breathe New Life Into Your Mac A Guide to Freeing Up Space and Improving FCPX Performance for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-a-symphony-for-the-ears-ranking-the-top-8-filmmaking-sonic-experiences/"><u>New 2024 Approved A Symphony for the Ears Ranking the Top 8 Filmmaking Sonic Experiences</u></a></li>
<li><a href="https://windows11.techidaily.com/reinitializing-your-steam-gaming-milestones/"><u>Reinitializing Your Steam Gaming Milestones</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-nuances-of-widget-alerts-in-windows/"><u>Navigating the Nuances of Widget Alerts in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-access-to-greyed-out-pin-unlock-option/"><u>Restoring Access to Greyed-Out Pin Unlock Option</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-xc0f1103f-flaw-with-nvidias-windows-software/"><u>Overcoming XC0F1103F Flaw with Nvidia's Windows Software</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-uniform-iptv-system-utilization/"><u>[New] Uniform IPTV System Utilization</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-correct-the-internal-error-on-windows-1111-pro/"><u>Methods to Correct the Internal Error on Windows 11/11 Pro</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/crafting-visually-striking-fb-ad-videos/"><u>Crafting Visually Striking FB Ad Videos</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-hacks-averted-restore-your-facebook-account-safely-for-2024/"><u>[New] Hacks Averted! Restore Your Facebook Account Safely for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-powerful-usage-in-modern-host-computers/"><u>Reducing Powerful Usage in Modern Host Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-action-to-freeze-damaged-windows-pins/"><u>Immediate Action to Freeze-Damaged Windows PINs</u></a></li>
</ul></div>
