---
title: 11 Ways to Open the Credential Manager on Windows 11
date: 2024-07-11T21:12:39.422Z
updated: 2024-07-12T21:12:39.422Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 11 Ways to Open the Credential Manager on Windows 11
excerpt: This Article Describes 11 Ways to Open the Credential Manager on Windows 11
keywords: Windows Credentials Access,Win11 CredManager Unlock,11 Methods CredManager,CredManager Opener Guide,Master Key Manager Tools,Windows Password Management,Secure Login Credential Help
thumbnail: https://thmb.techidaily.com/b40abdafc85906cdf8c505af7da6e2b6de5b2e3882be4cc44ae2eb5b5e3f9c4a.jpg
---

## 11 Ways to Open the Credential Manager on Windows 11

 Credential Manager in Windows 11 stores all the username and password combinations that you use for websites you visit in Edge browsers, apps, or networks. Microsoft introduced Credential Manager with Windows 10 and since then it stores and manages all credentials in one place. You can even back up and remove credential entries that are obsolete.

 The most obvious method to access the Credential Manager is using the Control Panel. But do you know that there are other methods to access this password management too? We will list out all the possible ways to open it quickly. Let’s begin.

## 1\. Using Start Menu

 The Start menu is the most-visited section by Windows users. To access Credential Manager using the Start menu, repeat the following steps:

1. Press the**Win** key to open the Start menu.
2. Type**Credentials Manager** and click on the**Open** option.
3. The Credential Manager utility will launch on your system.

## 2\. Using Windows Search

 Alternatively, you can use the new and improved Windows Search tool to find and open Credential Manager on your system. Here’s how to do it:

1. Press**Win + S** to open the Windows Search utility.  
![Open Credentials Manager Using Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/open-credentials-manager-using-windows-search.jpg)
2. Type Credential Manager and click on the first relevant search result to open the tool.

## 3\. Using the Run Command Box

 You can launch Credentials Manager without using your mouse and clicking on options or the context menu using the Run command box. Repeat the following steps:

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**control /name Microsoft.CredentialManager** in the text input box and press the**Enter** key.  
![Open Credentials Manager Using the Run Command Box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/open-credentials-manager-using-the-run-command-box.jpg)
3. Credential Manager will open in a separate control panel window.

## 4\. Using the File Explorer

 Credential Manager’s DLL file is located inside the SysWoW64 folder. You can access it using File Explorer and then run it using Control Panel. Ensure that you have administrator privileges to access the SysWOW64 folder before trying this method. Here’s how:

1. Press**Win + E** to [launch the File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) .
2. Go to the address bar, paste the following path, and press the**Enter** key:**C:\\Windows\\SysWOW64**
3. Once you are inside the SysWOW64 folder, locate the**keymgr.dll file** and right-click on it.
4. Select**Show more options** from the context menu and then click on the**Open with** option.
5. Scroll down and click on the**Choose an app on your PC** option.
6. Navigate to the C drive and click on the Windows folder. Then, open the SysWOW64 folder.
7. Find the**Control.exe** program and select it. Click on the**Open** button.  
![Open Credentials Manager Using the File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/open-credentials-manager-using-the-file-explorer.jpg)
8. Window Control Panel will be added to the list of supported programs.**Double-click** on it to open keymgr.dll file in Control Panel.

## 5\. Using the CMD

 You can use the Command Prompt to open Credential Manager directly. No need to navigate through Control Panel to locate the utility. Repeat the following steps:

1. Press**Win + R** to open the Run dialog box.
2. Type**cmd** and press**Ctrl + Shift + Enter** to launch Command Prompt with administrator privileges.
3. In the Command Prompt window, type the following command and press the**Enter** key:**control.exe keymgr.dll**  
![Open Credentials Manager Using the CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/open-credentials-manager-using-the-cmd.jpg)
4. Credentials Manager will launch on your system. Close the Command Prompt window.

## 6\. Using Control Panel

 Control Panel is the central hub for many system utilities and also contains Credential Manager. If you prefer the GUI method to open any Windows utility, you can use Control Panel. Repeat the following steps:

1. Press**Win + R** to launch the Run command box. Type**control** and press the**Enter** key.
2. In the Control Panel window, click on the**User Accounts** option.  
![Open Credentials Manager Using Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/open-credentials-manager-using-control-panel.jpg)
3. Lastly, click on the**Credential Manager** option to launch the tool.

## 7\. Using a Desktop Shortcut

 A desktop shortcut can save much time in Credential Manager on the system. Since it is not an executable program but a DLL file, merely making a desktop shortcut won’t work. Instead, we will create a shortcut of the Credential Manager DLL file and configure it to open with Control Panel.

 Repeat the following steps to create a shortcut for Credential Manager:

1. Press**Win + D** to switch to Desktop.
2. Right-click on the Desktop and select the**New > Shortcut** option from the context menu.
3. In the Create Shortcut window, paste the following text in the Location box:**control.exe /name Microsoft.CredentialManager**  
![Open Credentials Manager Using a Desktop Shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/open-credentials-manager-using-a-desktop-shortcut.jpg)
4. Click on the**Next** button. Name the shortcut**Credential Manager** and click on the**Finish** button.
5. Now, double-click on the shortcut to open Credential Manager.

## 8\. Using the Settings App

 Microsoft hasn’t moved all Control Panel options to the Settings app. But it is possible to search and access Credential Manager inside the Settings app. Here’s how to do it:

1. **Right-click** on the Start button to open the Power User menu. Select the**Settings** option from the menu.
2. Navigate to the top-left corner and click on the**Find a setting** option.  
![Open Credentials Manager Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/open-credentials-manager-using-the-settings-app.jpg)
3. Type**Credential Manager** and click on the first relevant search result for the utility.

## 9\. Using a PowerShell Command

 Like the Command Prompt, you can use PowerShell to open Credential Manager with a simple one-line command. Here’s how to do it:

1. Press**Win + S** to [open Windows Search](https://www.makeuseof.com/windows-search-use-guide/) .
2. Type**PowerShell** and click on the**Run as administrator** option in the right pane.
3. Type the following command in the PowerShell window and press the**Enter** key:**start-process control.exe keymgr.dll**  
![Open Credentials Manager Using a PowerShell Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/open-credentials-manager-using-a-powershell-command.jpg)
4. Credential Manager will open. Type the**exit** command in the PowerShell window and press the**Enter** key to close it.

## 10\. Using a Batch File

 A batch file is a more convenient method to open Credential Manager whenever you need it. You can place it on the desktop and run it with administrator privileges just like a shortcut. Repeat the following steps to create a batch file:

1. Press**Win + D** to switch to the Desktop. Right-click on the desktop and select the**New > Text Document** option.
2. Open the empty text document and paste the following code snippet:  
`@echo off powershell.exe control.exe keymgr.dll`
3. Press**Ctrl + Shift + S** to open the**Save as** window. Name the file “**CredMgr.bat** ” and click on the**Save** button.  
![Open Credentials Manager Using a Batch File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/open-credentials-manager-using-a-batch-file.jpg)
4. Close the Notepad file. Navigate to the location where you saved the CredMgr.bat file.
5. Right-click on it and select the**Run as administrator** option.
6. The PowerShell window will launch and close automatically. Credential Manager will launch on your system.

## 11\. Using the Task Manager

 You can open Credentials Manager by running a new task in Task Manager. Here’s how to do it:

1. Press**Win + R** to open the Run command box. Type**taskmgr** in the text input area and press the**Enter** key to open Task Manager.
2. In the Task Manager window, click on the**Run new task** button.  
![Open Credentials Manager Using the Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/open-credentials-manager-using-the-task-manager.jpg)
3. Type**control.exe keymgr.dll** in the Create new task window and click on the**OK** button.
4. Credential Manager will open in a new window. Exit the Task Manager window.

## Check Your Credentials on Windows Quickly With These Tips

 Windows Credential Manager is an excellent utility that automatically saves usernames and login pairs without installing a separate application. Even if you don’t use the feature for saving passwords of your favorite websites, you can still save login information of all the Windows apps which you use.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>



<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://audio-editing.techidaily.com/updated-from-novice-to-pro-harnessing-the-potential-of-adobes-audio-editor-adobe-audition/"><u>Updated From Novice to Pro Harnessing the Potential of Adobes Audio Editor (Adobe Audition)</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-unplayable-file-challenge/"><u>Addressing Windows' Unplayable File Challenge</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-mastering-single-platform-livestreaming-unveiling-onestream-techniques/"><u>2024 Approved  Mastering Single-Platform Livestreaming  Unveiling OneStream Techniques</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-accelerated-mp4-to-facebook-video-conversion-for-2024/"><u>[New] Accelerated MP4-to-Facebook Video Conversion for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/curing-unable-to-retrieve-settings-issue-with-geforce-experience-on-windows-11/"><u>Curing Unable to Retrieve Settings Issue with GeForce Experience on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/7-crucial-blunders-every-windows-11-novice-must-avoid/"><u>7 Crucial Blunders Every Windows 11 Novice Must Avoid</u></a></li>
<li><a href="https://windows11.techidaily.com/convenience-at-a-click-discover-how-to-enable-gestures-on-edge-windows-11/"><u>Convenience at a Click: Discover How to Enable Gestures on Edge (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/winphone-users-decide-between-unison-and-phone-link-apps/"><u>WinPhone Users: Decide Between Unison and Phone Link Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/win11s-0x8007045d-an-effective-resolution-blueprint/"><u>Win11's 0X8007045D: An Effective Resolution Blueprint</u></a></li>
<li><a href="https://extra-information.techidaily.com/experts-choice-peak-business-space/"><u>Expert's Choice  Peak Business Space</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-prime-windows-10-photo-display/"><u>[New] In 2024, Prime Windows 10 Photo Display</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-apple-iphone-12-mini-drfone-by-drfone-virtual-ios/"><u>In 2024, 9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Apple iPhone 12 mini | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-non-operational-windows-defrag-tool/"><u>Troubleshooting Non-Operational Windows Defrag Tool</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-icloud-by-checkra1n-even-on-apple-iphone-14-pro-if-youve-tried-everything-by-drfone-ios/"><u>How To Bypass iCloud By Checkra1n Even On Apple iPhone 14 Pro If Youve Tried Everything</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-break-even-on-youtube-monetizing-with-a-minimum-of-500-viewers/"><u>[New] 2024 Approved  Break Even on Youtube  Monetizing with a Minimum of 500 Viewers</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-windows-11-homespace-options/"><u>Accessing Windows 11 Homespace Options</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-pathways-to-successful-office-activation/"><u>Clearing Pathways to Successful Office Activation</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-11s-hidden-error-code-0xc1900101/"><u>Unveiling Windows 11'S Hidden Error Code #0xC1900101</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-ranked-top-5-ps3-virtual-players-for-pc/"><u>[Updated] Ranked  Top 5 PS3 Virtual Players for PC</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-twitsnap-secure-effortless-methods-for-downloading-tweets-videos/"><u>[New] 2024 Approved  TwitSnap Secure  Effortless Methods for Downloading Tweets' Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-nvidia-driver-recommendations-entertainment-sector/"><u>Tailored Nvidia Driver Recommendations: Entertainment Sector</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-the-ultimate-guide-to-audio-integration-on-reels/"><u>[New] 2024 Approved  The Ultimate Guide to Audio Integration on Reels</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-the-windows-lsa-disablement-warning/"><u>Bypassing the Windows LSA Disablement Warning</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-offline-setting-up-on-disconnected-pcs/"><u>Win11 Offline: Setting Up on Disconnected PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/triumph-over-microsoft-teams-stumbling-block-80080300-on-w11/"><u>Triumph over Microsoft Teams' Stumbling Block #80080300 on W11</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-command-prompt-gambits-for-a-laugh/"><u>Top 5 Command Prompt Gambits for a Laugh</u></a></li>
<li><a href="https://audio-editing.techidaily.com/where-to-submit-your-show-complete-list-of-podcast-directories-for-2024/"><u>Where to Submit Your Show Complete List of Podcast Directories for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/1719349405273-say-no-to-incompatibility-quick-solutions-for-vistawindows-7-users/"><u>Say No to Incompatibility: Quick Solutions for Vista/Windows 7 Users.</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-comprehensive-guide-to-fb-video-success/"><u>[New] In 2024, Comprehensive Guide to FB Video Success</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-mystery-of-mouse-controls-on-windows-11/"><u>Unlock the Mystery of Mouse Controls on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-solutions-for-correction-of-network-security-discrepancy-in-windows-11/"><u>Top 5 Solutions for Correction of Network Security Discrepancy in Windows 11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-ultimate-guide-to-extracting-youtube-subtitles-srt/"><u>2024 Approved  The Ultimate Guide to Extracting YouTube Subtitles (SRT)</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-mastering-picture-warping-techniques-with-various-apps/"><u>[New] Mastering Picture Warping Techniques with Various Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/changing-network-address-translation-types-simplified-for-wins-oses/"><u>Changing Network Address Translation Types Simplified for Wins OSes</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-easily-alter-tiktok-audio-the-no-frills-guide-to-vocal-changes/"><u>In 2024, Easily Alter TikTok Audio  The No-Frills Guide to Vocal Changes</u></a></li>
<li><a href="https://windows11.techidaily.com/triumph-over-troubled-windows-credentials/"><u>Triumph over Troubled Windows Credentials</u></a></li>
</ul></div>
