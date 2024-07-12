---
title: Launching Windows File Explorer Directly via OneDrive
date: 2024-07-11T21:13:06.278Z
updated: 2024-07-12T21:13:06.278Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Launching Windows File Explorer Directly via OneDrive
excerpt: This Article Describes Launching Windows File Explorer Directly via OneDrive
keywords: Launcher Files Explorer,OneDrive File Access,Direct Explorer Use,OneDrive Direct Share,Windows Explorer Link,Office App Integration,Streaming Folder Views,Launcher Exe File,Directional OneDrive,Direct Explorer,OneDrive Sharing,Windows Explorer,Office Apps Cloud,Stream Folder View
thumbnail: https://thmb.techidaily.com/a6dbe934550b4e8e63b5bdb5b2859a1cbef0d47ae79e9b219910350b66fadbff.jpg
---

## Launching Windows File Explorer Directly via OneDrive

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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-clips.techidaily.com/in-2024-unmute-your-social-platforms-audio-a-quick-fix-guide/"><u>In 2024, Unmute Your Social Platform's Audio  A Quick Fix Guide</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/2024-approved-10plus-free-online-mp3-to-text-converters/"><u>2024 Approved 10+ FREE Online MP3 to Text Converters</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-the-experts-guide-to-streamer-software-mastery-top-10/"><u>[New] The Expert's Guide to Streamer Software Mastery (Top 10)</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-capturing-the-spectrum-a-broad-overview-of-recorders/"><u>[New] In 2024, Capturing the Spectrum  A Broad Overview of Recorders</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-edge-guards-camera-and-mic-use/"><u>Activating Edge Guards: Camera & Mic Use</u></a></li>
<li><a href="https://windows11.techidaily.com/bridge-ios-and-windows-using-apple-calendar-effortlessly/"><u>Bridge iOS and Windows: Using Apple Calendar Effortlessly</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-enhancing-video-visibility-to-attract-vimeos-top-choices/"><u>[Updated] In 2024, Enhancing Video Visibility to Attract Vimeo's Top Choices</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-animated-wonders-a-curated-top-15-in-stop-motion/"><u>2024 Approved  Animated Wonders  A Curated Top 15 in Stop Motion</u></a></li>
<li><a href="https://windows11.techidaily.com/briskly-engage-bings-ai-assistant-in-windows-11-search-field/"><u>Briskly Engage Bing's AI Assistant in Windows 11 Search Field</u></a></li>
<li><a href="https://windows11.techidaily.com/8-strategies-for-enhancing-windows-11-wi-fi-connectivity/"><u>8 Strategies for Enhancing Windows 11 Wi-Fi Connectivity</u></a></li>
<li><a href="https://windows11.techidaily.com/character-inspector-easy-steps-for-windows-11/"><u>Character Inspector: Easy Steps for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-peak-speed-for-your-windows-ssd-using-fresh-methods/"><u>Achieve Peak Speed for Your Windows' SSD Using Fresh Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-control-over-users-and-groups-in-windows-1110-homes/"><u>Boosting Control Over Users & Groups in Windows 11/10 Homes</u></a></li>
<li><a href="https://windows11.techidaily.com/captivating-holiday-vistas-through-designed-panes/"><u>Captivating Holiday Vistas Through Designed Panes</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-one-side-output-in-windows-10-headphones/"><u>Addressing One Side Output in Windows 10 Headphones</u></a></li>
<li><a href="https://windows11.techidaily.com/asus-challenges-rog-ally-with-innovative-designs/"><u>ASUS Challenges ROG Ally with Innovative Designs</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-twitters-top-picks-best-amazon-prime-content-2023-for-2024/"><u>[Updated] Twitter's Top Picks  Best Amazon Prime Content 2023 for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/4-ways-to-fix-the-mail-apps-cant-get-mail-error-on-windows-11/"><u>4 Ways to Fix the Mail App's Can’t Get Mail Error on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/a-deep-dive-into-winning-windows-captures-with-printscreen-or-snip-tool/"><u>A Deep Dive Into Winning Windows Captures with Printscreen or Snip Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/6-ways-to-fix-minecrafts-exit-code-1-on-windows/"><u>6 Ways to Fix Minecraft's Exit Code: 1 on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/5-ways-to-fix-the-hypervisorerror-blue-screen-on-windows-11-and-11/"><u>5 Ways to Fix the HYPERVISOR_ERROR Blue Screen on Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-blackwhite-displays-in-windows-store-app/"><u>Addressing Black/White Displays in Windows Store App</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-in-2024-top-mac-video-editing-software-options-beyond-pinnacle-studio/"><u>New In 2024, Top Mac Video Editing Software Options Beyond Pinnacle Studio</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-performance-pitfalls-high-cpu-usage-with-rm/"><u>Avoiding Performance Pitfalls: High CPU Usage with RM</u></a></li>
<li><a href="https://windows11.techidaily.com/7-annoying-windows-11-design-inconsistencies/"><u>7 Annoying Windows 11 Design Inconsistencies</u></a></li>
<li><a href="https://techidaily.com/how-to-erase-apple-iphone-13-mini-data-permanently-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>How To Erase Apple iPhone 13 mini Data Permanently | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/troubleshooting-a-non-operational-obs-video-capture/"><u>Troubleshooting a Non-Operational OBS Video Capture</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-productivity-with-permanent-windows-terminal-admin-entry/"><u>Boost Productivity with Permanent Windows Terminal Admin Entry</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-monitors-sequence-on-laptops/"><u>Altering Monitors' Sequence on Laptops</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-11-key-inactivity-issues/"><u>Addressing Windows 11 Key Inactivity Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/capturing-games-using-intels-graphics-hub-on-windows/"><u>Capturing Games Using Intel's Graphics Hub on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-onedrive-failure-in-folder-addition-on-desktop-os/"><u>Bypassing OneDrive Failure in Folder Addition on Desktop OS</u></a></li>
<li><a href="https://video-capture.techidaily.com/the-essential-guide-for-cost-free-google-meet-management-for-2024/"><u>The Essential Guide for Cost-Free Google Meet Management for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/advancing-windows-technology-for-real-world-use/"><u>Advancing Windows Technology for Real-World Use</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-edge-browsing-performance-on-win10win11/"><u>Accelerating Edge Browsing Performance on Win10/Win11</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-mastering-viral-content-top-50plus-creative-quotes-for-tiktok/"><u>[Updated] 2024 Approved  Mastering Viral Content  Top 50+ Creative Quotes for TikTok</u></a></li>
<li><a href="https://windows11.techidaily.com/6-routines-to-reclaim-your-desktops-daytime-look/"><u>6 Routines To Reclaim Your Desktop's Daytime Look</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-engaging-enthusiasts-30plus-revolutionary-bio-strategies-for-maximum-popularity-on-filmoras-tiktok-platform/"><u>2024 Approved  Engaging Enthusiasts  30+ Revolutionary Bio Strategies for Maximum Popularity on Filmora's TikTok Platform</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/hassle-free-techniques-record-your-dell-screen-easily-for-2024/"><u>Hassle-Free Techniques  Record Your Dell Screen Easily for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/android-meets-windows-easy-synching-protocol/"><u>Android Meets Windows: Easy Synching Protocol</u></a></li>
</ul></div>
