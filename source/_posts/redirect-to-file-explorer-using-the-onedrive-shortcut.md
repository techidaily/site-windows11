---
title: Redirect to File Explorer Using the OneDrive Shortcut
date: 2024-06-25T12:35:16.355Z
updated: 2024-06-26T12:35:16.355Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Redirect to File Explorer Using the OneDrive Shortcut
excerpt: This Article Describes Redirect to File Explorer Using the OneDrive Shortcut
keywords: Redirect File Explorer,OneDrive Explorer,Office Explorer Shortcut,Quick OneDrive Access,Drive File Linking,Direct File Explorer,Share Folder Link
thumbnail: https://thmb.techidaily.com/850c193e7db5e5c0dafad83a501e0d012a7f8ab4be61e59f0459fea3e866d702.png
---

## Redirect to File Explorer Using the OneDrive Shortcut

 When you launch Windows File Explorer, it automatically takes you to the "Quick Access" view. This page displays shortcuts to recently accessed folders and files and lists your favorite folders. It might be convenient for some users but not for others who prefer easy access to their cloud storage.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.

## 1\. Use the Folder Options

 If you want to make OneDrive the starting point of your File Explorer, you can do so using folder options. Here's how to do it:

1. Open the Start menu and type **File Explorer** in the search box. When the File Explorer icon appears, click it to launch the app. You can also use **Win + E** to open the program quickly.
2. In the File Explorer window, look for **See more** (three dots) at the top. Clicking on it opens the Folder Options dialog box.  
![Open Folder Options in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-folder-options-in-file-explorer.jpg)
3. On the General tab, click the **Open File Explorer to** drop-down menu and select "Username Personal". Here, "Username" refers to your Windows account name.  
![Open File Explorer to OneDrive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-file-explorer-to-onedrive.jpg)
4. Click **Apply** \> **OK** to close the dialog box.

 From now on, opening File Explorer will automatically launch OneDrive rather than Quick Access.

## 2\. Using the Registry Editor

 You can also use the Registry Editor to set OneDrive as your default File Explorer view. But be warned: if you make an incorrect change to the system registry, you could damage your computer. We recommend [backing up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 Once backed up, follow these steps to make OneDrive the default view:

1. [Open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** in the text box and hit **Enter**.
3. If you're prompted for permission, select **Yes** to continue. The Registry Editor window will open.
4. In the Registry Editor window, navigate to this path:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. In the right pane, locate and double-click the **LaunchTo** entry. If the entry isn't present, you'll need to create it. For that, right-click on the **Advanced** folder and select **New > DWORD (32-bit) Value**. Name the value "LaunchTo" and press Enter. Doing so will create a new DWORD in the registry.  
![Set File Explorer to Open OneDrive Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/set-file-explorer-to-open-onedrive-using-registry.jpg)
6. Double-click on this newly created value and set its value to **4**.
7. Click **OK** and close the registry window.

 After that, restart your computer for the changes to take effect. Once your PC restarts, launch File Explorer. With this method, you will launch File Explorer directly to your cloud storage without navigating through Quick Access.

## 3\. Using a Reg File

 The third and final method to set OneDrive as the default view involves using a reg file. It contains the necessary instructions that modify the registry on your behalf. So, if you're not comfortable using the registry editor, this is the right way to go.

 To create the reg file, follow these steps:

1. Right-click on your desktop and select **New > Text Document**.
2. Name the file **OneDrive.reg** and hit **Enter**.
3. Now open the file in a text editor such as Notepad.
4. Copy and paste the following code into the text document:  
`<code>Windows Registry Editor Version 5.00  

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced]  
"LaunchTo"=dword:00000004`
5. After pasting the given code, click **File** \> **Save as**.
6. In the Save as dialog box, select **All files** from the Save as type drop-down menu and hit Enter. Make sure the file is saved as a **.reg** file and not as a .txt file.  
![Open File Explorer to OneDrive Using REG File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-file-explorer-to-onedrive-using-reg-file.jpg)
7. Double-click the REG file you just created. If you're prompted for permission to change your computer, click **Yes**.
8. Finally, restart your computer for the changes to take effect.

 After your system restarts, launch File Explorer. You'll see OneDrive as the main view instead of Quick Access.

## Set File Explorer to Open OneDrive Instead of Quick Access

 There you have it; three different methods to make OneDrive your default File Explorer view. If you like, you can also change other folder views, such as Downloads or This PC, using the same techniques we discussed above. I hope this guide helped you get things done quickly and easily.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/accelerate-vm-performance-on-windows-6-precise-tips-and-tricks/"><u>Accelerate VM Performance on Windows: 6 Precise Tips & Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/nullify-specification-shortfalls-alerts-in-win11/"><u>Nullify Specification Shortfalls Alerts in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-recurring-disk-full-issues-in-windows/"><u>How to Stop Recurring Disk Full Issues in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-command-prompt-gambits-for-a-laugh/"><u>Top 5 Command Prompt Gambits for a Laugh</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-convergence-the-best-6-compatible-android-apps-on-windows-11/"><u>Master the Convergence: The Best 6 Compatible Android Apps on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-steps-to-launch-wordpad-on-windows/"><u>Seamless Steps to Launch WordPad on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-path-to-spooler-restart/"><u>Direct Path to Spooler Restart</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-pause-auto-updates-no-more-prompts/"><u>Windows Pause Auto-Updates: No More Prompts!</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-database-connections-resolving-malwarebytes-service-issues/"><u>Recovering Database Connections: Resolving Malwarebytes Service Issues</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-unfollowers-alert-on-your-instagram-map/"><u>In 2024, Unfollowers Alert on Your Instagram Map</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-reset-honor-play-7t-without-volume-buttons-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Reset Honor Play 7T Without Volume Buttons | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-sonic-pixels-turning-sound-into-visual-storytelling/"><u>[New] Sonic Pixels  Turning Sound Into Visual Storytelling</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-unlock-your-fb-potential-with-these-video-engagement-techniques/"><u>[Updated] In 2024, Unlock Your FB Potential with These Video Engagement Techniques</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-simplifying-connection-combining-linkedin-profile-with-your-tiktok-bio/"><u>In 2024, Simplifying Connection  Combining LinkedIn Profile with Your TikTok Bio</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-iphone-15-plus-official-method-to-unlock-your-iphone-15-plus-by-drfone-ios/"><u>How To Unlock iPhone 15 Plus Official Method to Unlock Your iPhone 15 Plus</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-ace-your-tiktok-videos-pick-the-right-editor/"><u>[New] In 2024, Ace Your TikTok Videos  Pick the Right Editor</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-restoring-sound-linkage-in-obs-broadcasts/"><u>2024 Approved  Restoring Sound Linkage in OBS Broadcasts</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/craft-the-ultimate-outro-with-pro-maker-advice-for-2024/"><u>Craft the Ultimate Outro with Pro Maker Advice for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-simplify-video-capturing-5-user-friendly-methods-for-macs-webcam/"><u>[New] 2024 Approved  Simplify Video Capturing  5 User-Friendly Methods for Mac's Webcam</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>