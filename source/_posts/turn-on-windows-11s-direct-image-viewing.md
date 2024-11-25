---
title: Turn On Windows 11'S Direct Image Viewing
date: 2024-11-21T01:26:43.806Z
updated: 2024-11-24T17:56:08.882Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Turn On Windows 11'S Direct Image Viewing
excerpt: This Article Describes Turn On Windows 11'S Direct Image Viewing
keywords: Windows 11 Image Viewing,Direct Windows 11 Display,Enable Image Window 11,Windows 11 Image Direct,Direct Screen Windows 11,Turn On Windows Image,Image View in Windows 11
thumbnail: https://thmb.techidaily.com/bfe8f97d519484170998bced830c25ea7c96c9f9fefb2b304db02c765d66484d.jpg
---

## Turn On Windows 11'S Direct Image Viewing

 Windows 11’s File Explorer has a tabs feature now. You can open a new location on the disk in a new tab rather than opening a new File Explorer window. Switching between multiple file locations is seamless, all thanks to this feature. But Microsoft isn’t planning to stop here. It wants to completely overhaul the File Explorer.

 File Explorer Gallery is one such new feature that Microsoft is testing in the Canary channel. Having a Gallery section will remove the need to browse separate folders to find or preview an image. Want to enable the feature on your system? Let’s begin.

## What Is the Gallery Feature in Windows File Explorer?

 File Explorer’s Gallery feature works exactly like it sounds. It categorically lists all the images on your system in a separate section, so you can find and view all the images in one tab. Android File Explorers have had this feature for quite a long, but Windows seems to care about it now.

 This new feature is available in the Windows Insider build version 25300 and above. But Microsoft made a big change to the Insider program by adding a Canary channel. So, any new Canary build will also have this experimental feature. Microsoft adds the new File Explorer based on Windows App SDK, which you can verify by hovering over the “pizza” icon in the File Explorer address bar.

 The Gallery section displays images from the Pictures and OneDrive folders and lists them by date. It has nice, rounded corners around each image in the Gallery section, which makes it feel like a part of the overall Windows 11 design. It appears right below the Home option in the left pane.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MHafwnWSEQk?si=rejNVNpJZH2SqNLy&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Enable Gallery in File Explorer in Windows 11

 Repeat the following steps to enable the new Gallery section in File Explorer:

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gkdZ3A1mock?si=2zeR5GtTU2VujM_w&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 1\. Update to the Appropriate Windows Insider Build

 The Gallery section is hidden in Insider builds 25300 and above. If you are a Windows Insider program participant, open and check for the latest Insider builds on your system. Make sure to be in the Dev or Canary channel because this experimental feature is exclusive to these channels only. Or, you can use[UUP Dump to download Windows Insider builds without participating in Microsoft’s Insider program](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) .

### 2\. Download ViVeTool

 You will also need ViVeTool to enable these experimental features on your system. You can[download ViVetool from GitHub](https://github.com/thebookisclosed/ViVe/releases) , but make sure that you pick the most recent release. Extract the tool to the C drive and then proceed to the next section.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jjGL9wFdlbo?si=Vb1JgZqRXNc03UGG&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Enabling Gallery in Windows File Explorer

 Retrace the following steps to enable the Gallery section on Windows 11:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** and press**Ctrl + Shift + Enter** keys at once to open a new Command Prompt window with administrator privileges.
2. Now, navigate to the main directory in C drive. Type**cd C:\\ command** and press the enter key.
3. Next, type the**cd Vivetool** command to enter the folder where Vivetool is present in the C drive. It is the main reason why we suggested you extract Vivetool in a convenient location.
4. Type the**Vivetool** command and press enter key to check if the tool is accessible and working. You will see the version of the tool along with the parameters it supports.  
![Enable Gallery in File Explorer in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-gallery-in-file-explorer-in-windows-11.jpg)
5. Now, type the following command and press the enter key:  
vivetool /enable /id:41040327
6. If the command executes correctly, you will see a “Successfully set feature configuration(s)” message. But don’t close the Command Prompt window. Type the following commands to enable all the Gallery features one by one and execute them.  
vivetool /enable /id:40729001 vivetool /enable /id:40731912 vivetool /enable /id:41969252 vivetool /enable /id:42922424 vivetool /enable /id:42295138
7. After running all the commands without any error, type**exit** and press the enter key to close the command prompt window.  
![Enable Gallery in File Explorer in Windows 11 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-gallery-in-file-explorer-in-windows-11-2.jpg)
8. Restart your computer for the changes made by Vivetool to take effect.
9. Once your computer boots up, press**Win + E** to open File Explorer. You will see a new**Gallery** option in the left pane below the**Home** option.

## How to View the Gallery in File Explorer

 You can access the Gallery section by launching File Explorer and clicking on the Gallery option in the left navigation pane. You will see all the images from the Pictures folder and OneDrive folder arranged by modification time (new to old). There is also a handy slider to scroll through the vast image tiles without using the mouse scroll wheel.

![Gallery in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/gallery-in-windows-file-explorer.jpg)

 The gallery app allows you to adjust the view of the image tiles to accommodate more or less in a single window. You can use the View option in the menu bar of File Explorer to change the image tile size. If you click on any image, it will open in a separate app window (Photos app or any other app that you use).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U6lCtLUeROA?si=se6OFuis9JpcTGJf&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Add or Remove Locations From Gallery in Windows File Explorer

 By default, the Gallery selection displays all the images located in the Pictures folder and OneDrive. But you can add or remove a folder from the Gallery section as well.

1. To add a folder to the Gallery, go to the menu bar and click on the**Locations** option. A new pop-up window will open and list all the folders that the Gallery section is pulling images from. Click on the**Add** button.  
![Adding a Folder to Gallery in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/adding-a-folder-to-gallery-in-windows-file-explorer.jpg)
2. Now select any folder or sub-folder with images and click on the**Include Folder** button.
3. The selected folder will appear in the list of available folders. Click on the**OK** button.
4. File Explorer gallery will now display the images present inside the newly added folder as well.

To remove a folder from Gallery, repeat the following steps:

1. Open the Gallery section and click on the**Locations** option in the menu bar.
2. You will see the list of all the folders currently included in the Gallery.
3. Click on the folder you want to remove to select it. Then click on the**Remove** button.  
![Removing a Folder from Gallery in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/removing-a-folder-from-gallery-in-windows-file-explorer.jpg)
4. Lastly, click on the**OK** button to finalize the changes. The Gallery section won’t display any images from the excluded folder from now onwards.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_7AYCS7zBU0?si=7R9oIpE4hyEbtk3x&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Problems With the Gallery Section in Windows File Explorer

 The current preview of the Gallery feature is far from perfect. Firstly, the section works well in finding and categorically listing all the images from the included folders. But the images, despite being big, appear hazy. What’s the point of including a section if the images aren’t visible clearly?

 There is also the issue of images opening in a separate tab rather than in the same File Explorer window. If you plan to open the image in another window, you can do it from the image folder as well. So, future builds should include an option to preview the image in the File Explorer window. Otherwise, you are opening two apps to achieve the same thing. The Gallery section cannot list any videos as well and just ignores all the video files.

## Find All Your Images in One Place on Windows With Galleries

 Adding a Gallery section to File Explorer is a fantastic decision by Microsoft. But the current version is full of kinks we hope that Microsoft irons out before the final preview. If done right, this would make the File Explorer app a powerhouse and reduce dependency on other apps.

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
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-navigating-the-world-of-sound-symbols-on-instagram-platform/"><u>[Updated] 2024 Approved Navigating the World of Sound Symbols on Instagram Platform</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-fluidity-in-filming-a-deep-dive-into-inshots-transition-features/"><u>[Updated] Fluidity in Filming A Deep Dive Into Inshot's Transition Features</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-t5-thievery-a-comprehensive-action-footage-analysis/"><u>[Updated] T5 Thievery - A Comprehensive Action Footage Analysis</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-mirrorless-4k-cameras-top-10-list-unveiled/"><u>2024 Approved Mirrorless 4K Cameras Top 10 List Unveiled</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-slow-it-down-a-comprehen/"><u>2024 Approved Slow It Down A Comprehen</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-the-depths-of-android-and-windows-file-sharing/"><u>Exploring the Depths of Android & Windows File Sharing</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/failed-to-play-mov-movies-on-redmi-note-13-proplus-5g-by-aiseesoft-video-converter-play-mov-on-android/"><u>Failed to play MOV movies on Redmi Note 13 Pro+ 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-app-complaint-net-core-install-required-on-windows/"><u>Fixing App Complaint: .NET Core Install Required on Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/how-can-i-catch-the-regional-pokemon-without-traveling-on-vivo-y200e-5g-drfone-by-drfone-virtual-android/"><u>How Can I Catch the Regional Pokémon without Traveling On Vivo Y200e 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/inside-insights-windows-saver-mechanics-explained/"><u>Inside Insights: Windows Saver Mechanics Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/powershell-expertise-uncovering-network-details-in-windows/"><u>PowerShell Expertise: Uncovering Network Details in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/progressive-pathways-mastering-the-art-of-replacing-aged-windows-drivers/"><u>Progressive Pathways: Mastering the Art of Replacing Aged Windows Drivers</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/srt-conversion-essentials-ttml-xml-ssa-and-beyond-for-2024/"><u>SRT Conversion Essentials TTML, XML, SSA, and Beyond for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/unlocking-the-power-of-smart-lock-a-beginners-guide-for-honor-magic-5-pro-users-by-drfone-android/"><u>Unlocking the Power of Smart Lock A Beginners Guide for Honor Magic 5 Pro Users</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/unveiling-the-leading-cheap-smartphone-network-options-for-savvy-consumers-in-twentyeitnf/"><u>Unveiling the Leading Cheap Smartphone Network Options for Savvy Consumers in ˈtwentyeitnɪf</u></a></li>
<li><a href="https://windows11.techidaily.com/visual-upgrade-protocols-a-comprehensive-guide-to-theme-alteration-in-win11/"><u>Visual Upgrade Protocols: A Comprehensive Guide to Theme Alteration in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-installation-insight-pinpointing-software-homesteads/"><u>Windows Installation Insight: Pinpointing Software Homesteads</u></a></li>
<li><a href="https://windows11.techidaily.com/winerror-woes-be-gone-fixing-oculus-app-for-winxc/"><u>WinError Woes Be Gone: Fixing Oculus App for WinXC</u></a></li>
<li><a href="https://windows11.techidaily.com/wsl-and-the-surge-in-linux-popularity/"><u>WSL and the Surge in Linux Popularity</u></a></li>
</ul></div>

