---
title: Reinstating Default Organization of Windows Files
date: 2024-11-11T17:11:39.518Z
updated: 2024-11-15T16:49:13.290Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reinstating Default Organization of Windows Files
excerpt: This Article Describes Reinstating Default Organization of Windows Files
keywords: Windows File Ordering,File System Restore,Windows Organized Folders,Reinstallation Filenames,OS File Default Setting,Windows Original Layout,Filesystem Reversion Windows
thumbnail: https://thmb.techidaily.com/5ed909f597267ef924f41dbe3db988e7da363a5d5c3d20cd43f4003c2eedf878.jpg
---

## Reinstating Default Organization of Windows Files

 Folder View Settings in Windows help you control how the contents of a particular folder are displayed and organized. If you’ve changed these settings, but now want to reset them to the default view, it’s easy. Read this guide to learn how to reset Folder View settings on your Windows 11 PC.

## How to Reset Folder View Settings to Default on Windows

 There are three ways to reset your Folder View Settings to the default view. The first method is to run a batch file, the second using File Explorer, whereas the third and final method involves tweaking the registry editor. This post explains each method in detail. Let's dive into it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036467/19272" target="_top" id="2036467">
  <img src="//a.impactradius-go.com/display-ad/19272-2036467" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036467/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 1\. Run a Batch File to Reset Folder View Settings to Default

 Resetting the Folder View Settings with this method requires creating and running a batch file. This will reset the settings for all folders across your computer. Here's how to do it:

1. Right-click on your desktop and select**New > Text Document** .
2. Name it**ResetFolderViewSettings** and press Enter to save it.
3. Open the newly created text file in Notepad or any other text editor of your choice.
4. Now copy and paste the following code into the file:  
`@echo off  

:: Resets folder view settings, window size and position of all folders  
Reg Delete "HKCU\SOFTWARE\Classes\Local Settings\Software\Microsoft\Windows\Shell\BagMRU" /F  
Reg Delete "HKCU\SOFTWARE\Classes\Local Settings\Software\Microsoft\Windows\Shell\Bags" /F  

:: To reset "Apply to Folders" views to default for all folder types  
REG Delete "HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Streams\Defaults" /F  

:: To reset size of details, navigation, preview panes to default for all folders  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Modules\GlobalSettings\Sizer" /F  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Modules\NavPane" /F  

:: To reset size of Save as amd Open dialogs to default for all folders  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\CIDOpen" /F  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\CIDSave" /F  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\ComDlg32" /F  

:: To kill and restart explorer process  
taskkill /f /im explorer.exe  
start explorer.exe`
5. After adding the code, click**File** in the top menu, then select**Save As** .
6. Now select**All Files** in the Save as type menu, and add**.bat** to the end of the file’s name.  
![Run a Batch File to Reset Folder View Settings to Default](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-a-batch-file-to-reset-folder-view-settings-to-default.jpg)
7. From the left pane, select**Desktop** as the location.
8. Then click**Save** and close the text editor window.
9. Finally, double-click the batch file you created, and it will reset your Folder View Settings to the default view.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997717/19272" target="_top" id="1997717">
  <img src="//a.impactradius-go.com/display-ad/19272-1997717" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997717/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Reset Folder View Settings to Default via File Explorer

 If you only need to reset the View Settings of all folders of the same type, this method is for you. Here's what you have to do:

1. Click on Start and search for**File Explorer Options** . To learn more about it, see our guide on[how to open the Folder Options on Windows](https://www.makeuseof.com/windows-10-open-folder-options/) .
2. Now, select the**View** tab in the top bar and tap on**Reset Folders** .  
![Reset Folder View Settings to Default Via File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-via-file-explorer.jpg)
3. Click**Yes** when prompted to confirm your action.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100541/7443" target="_top" id="2100541">
  <img src="//a.impactradius-go.com/display-ad/7443-2100541" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Finally, hit**OK** and the window will close.

 This will reset your Folder View Settings to Windows' default settings.

### 3\. Reset Folder View Settings to Default Using Registry Editor

 The last method to reset Folder View settings involves using the Windows Registry Editor. You should only use this method if you are an experienced user and know how it works, since messing with its keys could cause serious problems. To avoid data loss, you must[create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before continuing.

 To reset folder view settings using the registry editor, do the following:

1. Press**Win + R** on your keyboard to[open the Run command](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**regedit** in the text box and press Enter. This will[open the Registry Editor window](https://www.makeuseof.com/windows-11-open-registry-editor/) .
3. Navigate to the following location:  
HKEY_CURRENT_USER\Software\Classes\Local Settings\Software\Microsoft\Windows\Shell
4. In the left sidebar, right-click on the**BagMRU** folder and select**Delete.**  
![Reset Folder View Settings to Default Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-using-registry-editor.jpg)
5. Click**Yes** when asked to confirm your action.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959764/19272" target="_top" id="1959764">
  <img src="//a.impactradius-go.com/display-ad/19272-1959764" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959764/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Similarly, delete the**Bags** folder and close the Registry window.

## Reset Folder View Settings to Default

 Folder View on Windows allows users to customize their view of files and folders. This includes settings such as the file size information, restoring the previous folder when logging in, and automatically entering words when searching.

 However, if you have changed the View settings, this guide will help you reset Folder Options to its default.

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
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-mastering-gamified-views-selecting-the-best-webcams-for-players/"><u>[Updated] In 2024, Mastering Gamified Views Selecting the Best Webcams for Players</u></a></li>
<li><a href="https://extra-tips.techidaily.com/beats-for-chats-adding-sound-to-whatsapp-for-2024/"><u>Beats for Chats Adding Sound to WhatsApp for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/forgot-locked-iphone-13-pro-password-learn-the-best-methods-to-unlock-by-drfone-ios/"><u>Forgot Locked iPhone 13 Pro Password? Learn the Best Methods To Unlock</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reduce-overhead-from-real-time-scanners/"><u>How to Reduce Overhead From Real-Time Scanners</u></a></li>
<li><a href="https://windows11.techidaily.com/how-windows-blue-screen-data-assists-diagnosis/"><u>How Windows Blue Screen Data Assists Diagnosis</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-can-life360-track-you-when-your-apple-iphone-13-pro-is-off-drfone-by-drfone-virtual-ios/"><u>In 2024, Can Life360 Track You When Your Apple iPhone 13 Pro is off? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-delete-icloud-account-remove-your-apple-id-permanently-on-iphone-xs-by-drfone-ios/"><u>In 2024, How To Delete iCloud Account Remove Your Apple ID Permanently On iPhone XS</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-step-by-step-guide-to-perfect-close-up-cinematic-shots/"><u>In 2024, Step-by-Step Guide to Perfect Close-Up Cinematic Shots</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/insider-tips-for-spotting-real-chatbot-ios-products/"><u>Insider Tips for Spotting Real ChatBot iOS Products</u></a></li>
<li><a href="https://win-answers.techidaily.com/mastering-the-controllers-overcoming-mouse-malfunctions-in-resident-evil-village/"><u>Mastering the Controllers: Overcoming Mouse Malfunctions in Resident Evil Village</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-smartly-minimizing-applications-using-ctrlplustab/"><u>Navigate Smartly: Minimizing Applications Using Ctrl+Tab</u></a></li>
<li><a href="https://win-ratings.techidaily.com/resolved-efficiently-access-your-shortcuts-by-linking-to-the-preferred-folder-in-this-collaborative-repository/"><u>Resolved: Efficiently Access Your Shortcuts by Linking to the Preferred Folder in This Collaborative Repository</u></a></li>
<li><a href="https://windows11.techidaily.com/restore-smooth-operation-to-windows-timer-tasks/"><u>Restore Smooth Operation to Windows Timer Tasks</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-stopping-bsod-events-with-vmware-on-win11/"><u>Solutions for Stopping BSOD Events with VMware on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/your-guide-to-developing-an-automatic-voice-to-text-application-for-windows/"><u>Your Guide to Developing an Automatic Voice-to-Text Application for Windows</u></a></li>
</ul></div>

