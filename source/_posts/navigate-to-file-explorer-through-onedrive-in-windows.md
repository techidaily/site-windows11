---
title: Navigate to File Explorer Through OneDrive in Windows
date: 2024-09-10T19:48:38.667Z
updated: 2024-09-15T22:34:06.222Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigate to File Explorer Through OneDrive in Windows
excerpt: This Article Describes Navigate to File Explorer Through OneDrive in Windows
keywords: Navigate to DFexplorer,OneDrive Explore Files,File Explorer Access,Windows OneDrive View,Direct Explorer Opening,Quick OneDrive Explorer,OneDrive Navigate Explorer
thumbnail: https://thmb.techidaily.com/9ad9147e4fbb8c24ccda197a0486be5c1d9c044a46c11534bd2a1352ab33e591.png
---

## Navigate to File Explorer Through OneDrive in Windows

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135365/19272" target="_top" id="2135365">
  <img src="//a.impactradius-go.com/display-ad/19272-2135365" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135365/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://instagram-video-recordings.techidaily.com/new-from-front-to-back-and-back-again-the-insta-rotation-ritual-for-success-for-2024/"><u>[New] From Front to Back, and Back Again The Insta Rotation Ritual for Success for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-essential-guide-to-twitter-videos-and-aspect-ratios-for-2024/"><u>[Updated] Essential Guide to Twitter Videos and Aspect Ratios for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/boosting-video-impact-integrating-free-luts-into-your-obs-workflow-for-2024/"><u>Boosting Video Impact Integrating Free LUTs Into Your OBS Workflow for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/establishing-an-unchangeable-trash-for-files-on-windows-devices/"><u>Establishing an Unchangeable Trash for Files on Windows Devices</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-your-insignia-usb-and-ethernet-cable-converters-newest-software-here/"><u>Get Your Insignia USB and Ethernet Cable Converter's Newest Software Here!</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-apple-iphone-11-pro-max-drfone-by-drfone-virtual-ios/"><u>How to get the dragon scale and evolution-enabled pokemon On Apple iPhone 11 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/is-youtubes-monetization-payment-frequent/"><u>Is YouTube's Monetization Payment Frequent?</u></a></li>
<li><a href="https://windows11.techidaily.com/polishing-windows-11-backgrounds-for-eye-pleasure/"><u>Polishing Windows 11 Backgrounds for Eye Pleasure</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-a-stalled-mobile-hotspot-in-windows-11/"><u>Quick Fixes for A Stalled Mobile Hotspot in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-high-scores-fixing-fps-drops-in-valorant/"><u>Securing High Scores: Fixing FPS Drops in Valorant</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-utilizing-microsofts-phone-link-app/"><u>Understanding and Utilizing Microsoft's Phone Link App</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unleash-next-level-gaming-with-asus-rog-strix-g16-at-an-incredible-amazon-offer-of-just-1164/"><u>Unleash Next-Level Gaming with ASUS Rog Strix G16 at an Incredible Amazon Offer of Just $1,164</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-strategies-for-ms-teams-error-80080300/"><u>Win11 Strategies for MS Teams Error 80080300</u></a></li>
</ul></div>

