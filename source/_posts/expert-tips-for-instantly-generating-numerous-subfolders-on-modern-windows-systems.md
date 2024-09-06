---
title: Expert Tips for Instantly Generating Numerous Subfolders on Modern Windows Systems
date: 2024-09-05T02:08:08.244Z
updated: 2024-09-06T02:08:08.244Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Expert Tips for Instantly Generating Numerous Subfolders on Modern Windows Systems
excerpt: This Article Describes Expert Tips for Instantly Generating Numerous Subfolders on Modern Windows Systems
keywords: Numerous Folders Guide,Quick Folder Creation,Subfolder Techniques,Windows Folder Management,Instant Folder Generation,Modern Windows Organization,Efficient Directory Structuring
thumbnail: https://thmb.techidaily.com/8c3061c39eb85dd875af824e1d1149fd13be54628fb79ee748ce5191efb525e2.jpg
---

## Expert Tips for Instantly Generating Numerous Subfolders on Modern Windows Systems

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094415/7443" target="_top" id="2094415">
  <img src="//a.impactradius-go.com/display-ad/7443-2094415" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094415/7443" style="position:absolute;visibility:hidden;" border="0" />
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
4. Once the Folder Frenzy dialog launches, type the names of the folders you want to create and click on the **Create Folder** button. These folders will be created in the Folder Frenzy file.  
<!-- affiliate ads begin -->
<span id="1993647">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993647.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993647">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993647.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993647%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993647/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Create folder in Folder Frenzy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/folder-frenzy-create-folder.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137413/7443" target="_top" id="2137413">
  <img src="//a.impactradius-go.com/display-ad/7443-2137413" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137413/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 From here, you can even take a step further and learn [how to launch multiple programs with one shortcut on Windows](https://www.makeuseof.com/tag/launch-multiple-programs-single-shortcut-using-batch-file/) to increase your productivity at work or school. In case you no longer need the tool after creating bulk folders, you can uninstall it. This won't automatically delete the folders you have created using the tool, unless the uninstallation process explicitly offers to do so and you confirm that action.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918684/19272" target="_top" id="1918684">
  <img src="//a.impactradius-go.com/display-ad/19272-1918684" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918684/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Create Multiple Folders in a Few Clicks on Windows

 Creating several folders manually is a mundane task, and you can spend the same energy doing something more productive. The steps we have outlined above should help you automate this task, saving time for things that actually bring in some value.

 The latest Windows versions allow you to automate quite a few of your tasks, for instance letting you create multiple folders and sub-folders at once. This is quite helpful in situations where you need to sort out the data (for each semester, for instance) and do not want to spend hours doing it.

 There is more than one method of creating multiple files and folders in Windows, and we have outlined the best ways of doing so for you below. Read through the methods and proceed with the one you want.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://snapchat-videos.techidaily.com/new-fiery-friendship-keeping-your-snapstreak-hot-and-steady-for-2024/"><u>[New] Fiery Friendship  Keeping Your Snapstreak Hot and Steady for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-maximizing-zoom-visual-precision-effective-strategies/"><u>[New] Maximizing Zoom Visual Precision  Effective Strategies</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-precision-and-panache-advanced-tiktok-editing-skills/"><u>[New] Precision and Panache  Advanced TikTok Editing Skills</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-effortless-screen-recording-on-modern-pcs/"><u>[Updated] 2024 Approved  Effortless Screen Recording on Modern PCs</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-sharp-focus-tech-best-4k-camera-phones-of-the-genre/"><u>[Updated] 2024 Approved  Sharp Focus Tech  Best 4K Camera Phones of the Genre</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-transform-your-igtv-visuals-with-updated-covers/"><u>[Updated] In 2024, Transform Your IGTV Visuals with Updated Covers</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-integrate-youtube-content-into-google-slides-effectively-for-2024/"><u>[Updated] Integrate YouTube Content Into Google Slides Effectively for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-experts-list-of-tools-for-accelerating-your-facebook-vids/"><u>[Updated] The Expert's List of Tools for Accelerating Your Facebook Vids</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-cultivating-connections-friendly-games-growth-with-friends-on-farms/"><u>2024 Approved  Cultivating Connections  Friendly Games Growth with Friends on Farms</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/3-ways-to-unlock-apple-iphone-14-plus-without-passcode-or-face-id-drfone-by-drfone-ios/"><u>3 Ways to Unlock Apple iPhone 14 Plus without Passcode or Face ID | Dr.fone</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ld-beyond-men-top-10-inspirational-youtube-stars-for-2024/"><u>A World Beyond Men  Top 10 Inspirational YouTube Stars for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/balancing-main-and-supplemental-filmmaking-elements/"><u>Balancing Main & Supplemental Filmmaking Elements</u></a></li>
<li><a href="https://games-able.techidaily.com/channel-success-with-top-6-multi-genre-games/"><u>Channel Success with Top 6 Multi-Genre Games</u></a></li>
<li><a href="https://common-error.techidaily.com/essential-fixes-for-non-functional-windows-audio/"><u>Essential Fixes for Non-Functional Windows Audio</u></a></li>
<li><a href="https://program-issues.techidaily.com/fix-guide-for-when-your-guilds-in-midgard-game-collapse/"><u>Fix Guide for When Your Guilds in Midgard Game Collapse</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-overcoming-lol-launch-lag/"><u>Guide to Overcoming LOL Launch Lag</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-postpone-windows-10-shutdown-during-active-processes/"><u>Guide to Postpone Windows 10 Shutdown During Active Processes</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-sign-off-strangers-on-windows-11/"><u>Guide to Sign Off Strangers on Windows 11</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-delete-icloud-account-on-iphone-6s-without-password-by-drfone-ios/"><u>How to Delete iCloud Account On iPhone 6s without Password?</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-force-delete-or-uninstall-a-printer-in-windows-10-and-11/"><u>How to Force Delete or Uninstall a Printer in Windows 10 & 11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-action-seekers-dilemma-gopro-vs-yi-camera-showdown-revised/"><u>In 2024, Action Seekers' Dilemma  GoPro Vs. Yi Camera Showdown, Revised</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-fake-android-location-without-rooting-for-your-lava-yuva-2-drfone-by-drfone-virtual/"><u>In 2024, Fake Android Location without Rooting For Your Lava Yuva 2 | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-forgot-pattern-lock-heres-how-you-can-unlock-poco-pattern-lock-screen-by-drfone-android/"><u>In 2024, Forgot Pattern Lock? Heres How You Can Unlock Poco Pattern Lock Screen</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-m4a-editor-software-free-download-top-5-options/"><u>In 2024, M4A Editor Software Free Download Top 5 Options</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-total-gb-for-24-hour-movie-size/"><u>In 2024, Total GB for 24-Hour Movie Size</u></a></li>
<li><a href="https://buynow-info.techidaily.com/in-depth-analysis-of-the-affordable-hisense-40h5590f-smart-television/"><u>In-Depth Analysis of the Affordable Hisense 40H5590F Smart Television</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-vboxs-security-settings-secure-boot-and-tpm-management/"><u>Mastering VBox's Security Settings: Secure Boot & TPM Management</u></a></li>
<li><a href="https://windows11.techidaily.com/modify-default-task-manager-viewport-in-win11/"><u>Modify Default Task Manager Viewport in Win11</u></a></li>
<li><a href="https://win-able.techidaily.com/no-more-crashes-in-samurai-warriors-5-on-pc-optimizing-performance-and-fixes/"><u>No More Crashes in Samurai Warriors 5 on PC - Optimizing Performance and Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-keyboard-interface-with-personalized-fn-keys-in-windows-11/"><u>Optimizing Keyboard Interface with Personalized FN Keys in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-update-issue-windows-11-error-code-0x800f0922/"><u>Overcome Update Issue: Windows 11 Error Code 0X800F0922</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-usb-device-errors-on-windows-pcs/"><u>Overcoming USB Device Errors on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/personalized-overheat-avoidance-bios-tutorial-for-win-users/"><u>Personalized Overheat Avoidance: BIOS Tutorial for Win Users</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-common-winx-update-error-0x80246007/"><u>Quick Fixes for Common WinX Update Error: 0X80246007</u></a></li>
<li><a href="https://windows11.techidaily.com/regaining-composure-post-high-living-days-for-windows-users/"><u>Regaining Composure Post-High Living Days, for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/security-refresh-windows-firewalls-five-commandments/"><u>Security Refresh: Windows Firewall's Five Commandments</u></a></li>
<li><a href="https://windows11.techidaily.com/smooth-operations-at-low-cost-leverage-w11-pro-key/"><u>Smooth Operations at Low Cost: Leverage W11 Pro Key</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-securing-computer-against-unauthorized-usb-clip-attacks/"><u>Steps for Securing Computer Against Unauthorized USB Clip Attacks</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-spontaneous-scrolls-a-winworlders-guide/"><u>Stop Spontaneous Scrolls: A Winworlder's Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/strategic-shopping-for-cost-efficient-windows-11-keys/"><u>Strategic Shopping for Cost-Efficient Windows 11 Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-decrease-high-cpu-consumption-by-dropbox-on-windows/"><u>Strategies to Decrease High CPU Consumption by Dropbox on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-overcome-iphone-photographic-transfer-issues-on-w11-systems/"><u>Strategies to Overcome iPhone Photographic Transfer Issues on W11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-overcome-zero-x-error-in-the-microsoft-email-on-windows-11/"><u>Strategies to Overcome Zero X Error in the Microsoft Email on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-pc-toggle-folders-visibility-windows-11/"><u>Streamline Your PC: Toggle Folders Visibility (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/strengthen-your-safe-space-top-5-corrections-in-windows-features/"><u>Strengthen Your Safe Space: Top 5 Corrections in Windows Features</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-windows-update-failures-error-x712/"><u>Tackling Windows Update Failures: Error X712</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-picture-previews-in-windows-11-ui/"><u>Tailoring Picture Previews in Windows 11 UI</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-win1011-audio-error-xc00d36b4/"><u>Troubleshooting Win10/11 Audio Error XC00D36B4</u></a></li>
<li><a href="https://windows11.techidaily.com/unique-apps-for-a-stylish-windows-clock-display/"><u>Unique Apps for a Stylish Windows Clock Display</u></a></li>
<li><a href="https://windows11.techidaily.com/unjamming-windows-tackling-access-issues-head-on/"><u>Unjamming Windows: Tackling Access Issues Head-On</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11s-vanishing-icons-restoration-strategies/"><u>Win 11'S Vanishing Icons - Restoration Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-1110-hacks-swift-recovery-of-synapse-functions/"><u>Windows 11/10 Hacks: Swift Recovery of Synapse Functions</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-with-both-wi-fi-and-ethernet-connections-on-your-computer/"><u>Winning with Both Wi-Fi & Ethernet Connections on Your Computer</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>