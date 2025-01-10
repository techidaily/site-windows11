---
title: Clearing Custom Privileges in Win11 by Default
date: 2025-01-04T16:47:54.892Z
updated: 2025-01-10T22:18:16.343Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Clearing Custom Privileges in Win11 by Default
excerpt: This Article Describes Clearing Custom Privileges in Win11 by Default
keywords: Win11 Privilege Management,Clearance Windows 11,Disable Default Permissions,Win11 User Settings,Privilege Reset Win11,Access Control in Win11,Secure Win11 Configurations
thumbnail: https://thmb.techidaily.com/09fee241173a4d75afd314bc2889ac10d1158fd98dc41bc3885e34ece3467540.jpg
---

## Clearing Custom Privileges in Win11 by Default

 Having issues with apps or programs not running properly on your Windows computer? Resetting Windows Update permissions could be the solution you need. Similarly, if you're troubleshooting user profile problems, you can restore user permissions.

 This article covers three different methods to reset all user permissions – using the Icacls command, the Secedit command, and the Subinacl tool.

Let's now explore them in detail.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vfq0vw0Spz8?si=2EAk6hW-Gb-o33_L" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Run the Icacls Command

 The Icacls command allows you to view, modify, and reset file system permissions on files and folders. To reset Windows Update permissions using this command, you will first have to [take ownership of the folders on Windows](https://www.makeuseof.com/windows-10-11-own-folder/) . Then [open an elevated Command Prompt on Windows](https://www.makeuseof.com/windows-run-command-prompt-admin/) and type in the following command:

`icacls * /t /q /c /reset`

 Now press Enter on your keyboard to execute the command. This will reset all user permissions to default for every folder, subfolder, and file within the current working directory.

In the above command, here are the parameters explained:

* \* – This is a wildcard character that includes all folders within the current directory.
* /t – It targets all the subfolders and files within the current folder.
* /q – Run command without displaying success messages.
* /c – Continues the operation even if errors occur.
* /reset – This parameter resets the permission options to their default values.

## 2\. Run the Secedit command

 Windows provides the Secedit command to configure and analyze system security. To reset all user permissions using this command, run the command prompt with admin access, then type in the following command:

![Run the Secedit command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-the-secedit-command.jpg)

`secedit /configure /cfg %windir%\inf\defltbase.inf /db defltbase.sdb /verbose`

 Now press Enter to execute the command. Wait for the process to finish and restart your computer. This will reset the user permissions to the default system settings.

## 3\. Run the Subinacl Tool

 If you're not comfortable using the command prompt, you may use the Subinacl tool. This is a command-line utility from Microsoft that can be used to reset user permissions. Here's how to do it:

1. [Download the Subinacl tool from Microsoft's webpage](https://web.archive.org/web/20190830103837/http://www.microsoft.com/en-us/download/confirmation.aspx?id=23510) . When you open the page, the download starts automatically. If not, wait 30 seconds and click the link.
2. Once downloaded, double-click on the installer package. This will open the installation wizard.  
![Open the installation wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-the-installation-wizard.jpg)
3. Click on**Next** and then accept the license agreement terms.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PNw3Lb26wFA?si=5NR1XRVSp41EQYMy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Install the Subinacl tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-the-subinacl-tool.jpg)
4. Next, copy and paste the following path into the Destination folder:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X4q6gyaEojM?si=ImdFm6Zsr0azykqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`C:\Windows\System32`  
 Note: If you have installed Windows on a different drive, use that path instead.
5. Now click on**Install now** and wait for the Subinacl tool to be installed. This may take several minutes, so be patient.

1. When the installation is complete,[open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and type in the following commands:  
`subinacl /subkeyreg HKEY_LOCAL_MACHINE /grant=administrators=f  
subinacl /subkeyreg HKEY_CURRENT_USER /grant=administrators=f  
subinacl /subkeyreg HKEY_CLASSES_ROOT /grant=administrators=f  
subinacl /subdirectories %SystemDrive% /grant=administrators=f  
subinacl /subkeyreg HKEY_LOCAL_MACHINE /grant=system=f  
subinacl /subkeyreg HKEY_CURRENT_USER /grant=system=f  
subinacl /subkeyreg HKEY_CLASSES_ROOT /grant=system=f  
subinacl /subdirectories %SystemDrive% /grant=system=f`
2. On the Save As window, set the File name to**Reset.cmd** and then select**All Files** from the drop-down menu next to it.  
![Reset Windows Update permissions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-update-permissions.jpg)
3. Next, select**Desktop** from the left pane and click on**Save** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6xGqSETroqA?si=4C1GPgXi-AksR_oO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Now double-click on it to reset the user permissions to default.
5. This may take a while to complete the procedure, so wait for it to finish.

 Once done, close any running program, and then restart your computer. Your Windows Update permissions will be reset to their default settings. These are three different methods you can use to reset the user permission settings on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gyGoQi7hsZk?si=8OcKcPUj2wSBmVZ1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Restore User Permissions to Default on Windows

 User permissions play a crucial role in computer security. If you're experiencing user permission issues, you must reset them to their default settings. This guide helps you reset all user permissions on Windows using three different methods. You can use the ICACLS command, Secedit command, or Subinacl tool, depending on your preference.

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
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-hd-video-recording-for-windows-10-users/"><u>[New] In 2024, HD Video Recording for Windows 10 Users</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-innovative-image-editing-on-ios-best-tools-to-erase-objects-from-photos/"><u>[New] Innovative Image Editing on iOS Best Tools to Erase Objects From Photos</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-sound-fidelity-preservation-computer-sounds-and-dialogue/"><u>[New] Sound Fidelity Preservation Computer Sounds & Dialogue</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-capture-and-record-videos-from-your-webcam-for-2024/"><u>[Updated] Capture and Record Videos From Your Webcam for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-strategic-animation-techniques-to-boost-your-facebook-ad-roi/"><u>[Updated] In 2024, Strategic Animation Techniques to Boost Your Facebook Ad ROI</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-the-verified-journey-on-social-media-accelerate-followers-with-these-six-tips/"><u>[Updated] In 2024, The Verified Journey on Social Media Accelerate Followers with These Six Tips</u></a></li>
<li><a href="https://discover-deluxe.techidaily.com/easy-to-follow-instructions-retrieving-lost-or-erased-folders-on-windowsmac-computers/"><u>Easy-to-Follow Instructions: Retrieving Lost or Erased Folders on Windows/Mac Computers</u></a></li>
<li><a href="https://tech-haven.techidaily.com/explore-confidential-ai-talks-connect-with-chatgpt-and-more-using-duckduckgos-encrypted-chat-service/"><u>Explore Confidential AI Talks: Connect with ChatGPT and More Using DuckDuckGo's Encrypted Chat Service</u></a></li>
<li><a href="https://windows11.techidaily.com/from-mobile-to-desktop-utilizing-smartphone-mic/"><u>From Mobile to Desktop: Utilizing Smartphone Mic</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-maintain-a-single-wallpaper-in-win11/"><u>How to Maintain a Single Wallpaper in Win11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-change-lock-screen-wallpaper-on-infinix-note-30i-by-drfone-android/"><u>In 2024, How to Change Lock Screen Wallpaper on Infinix Note 30i</u></a></li>
<li><a href="https://windows11.techidaily.com/instant-fix-resetting-windows-11-search-preferences/"><u>Instant Fix: Resetting Windows 11 Search Preferences</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-in-pc-device-activation-during-sleep/"><u>Navigating In-PC Device Activation During Sleep</u></a></li>
<li><a href="https://windows11.techidaily.com/reshaping-record-chronology-in-win8-with-7-tools/"><u>Reshaping Record Chronology in Win8 with 7 Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/saying-goodbye-to-apps-on-windows-11-a-compact-guide-98-chars/"><u>Saying Goodbye to Apps on Windows 11 - A Compact Guide (98 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-social-connectivity-winning-at-fbm-glitches/"><u>Seamless Social Connectivity: Winning at FBM Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/signs-of-trouble-is-factory-reset-right-for-your-pc/"><u>Signs of Trouble: Is Factory Reset Right for Your PC</u></a></li>
</ul></div>

