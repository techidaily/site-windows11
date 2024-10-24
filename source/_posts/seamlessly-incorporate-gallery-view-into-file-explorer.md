---
title: Seamlessly Incorporate Gallery View Into File Explorer
date: 2024-10-19T19:03:41.333Z
updated: 2024-10-24T19:16:56.119Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Seamlessly Incorporate Gallery View Into File Explorer
excerpt: This Article Describes Seamlessly Incorporate Gallery View Into File Explorer
keywords: Gallery View Integration,Enhance File Explorer,Seamless Interface Add-On,Extend Explorer Graphics,Streamline File Viewer,Visual Gallery Tooling,Effortless Explorer Display
thumbnail: https://thmb.techidaily.com/2f486f4dd87aa179d36ac9cfba84a9e655bb2170ba42ee253c3df8a8c92937c0.jpg
---

## Seamlessly Incorporate Gallery View Into File Explorer

 Windows 11’s File Explorer has a tabs feature now. You can open a new location on the disk in a new tab rather than opening a new File Explorer window. Switching between multiple file locations is seamless, all thanks to this feature. But Microsoft isn’t planning to stop here. It wants to completely overhaul the File Explorer.

 File Explorer Gallery is one such new feature that Microsoft is testing in the Canary channel. Having a Gallery section will remove the need to browse separate folders to find or preview an image. Want to enable the feature on your system? Let’s begin.

## What Is the Gallery Feature in Windows File Explorer?

 File Explorer’s Gallery feature works exactly like it sounds. It categorically lists all the images on your system in a separate section, so you can find and view all the images in one tab. Android File Explorers have had this feature for quite a long, but Windows seems to care about it now.

 This new feature is available in the Windows Insider build version 25300 and above. But Microsoft made a big change to the Insider program by adding a Canary channel. So, any new Canary build will also have this experimental feature. Microsoft adds the new File Explorer based on Windows App SDK, which you can verify by hovering over the “pizza” icon in the File Explorer address bar.

 The Gallery section displays images from the Pictures and OneDrive folders and lists them by date. It has nice, rounded corners around each image in the Gallery section, which makes it feel like a part of the overall Windows 11 design. It appears right below the Home option in the left pane.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100529/7443" target="_top" id="2100529">
  <img src="//a.impactradius-go.com/display-ad/7443-2100529" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Enable Gallery in File Explorer in Windows 11

 Repeat the following steps to enable the new Gallery section in File Explorer:

### 1\. Update to the Appropriate Windows Insider Build

 The Gallery section is hidden in Insider builds 25300 and above. If you are a Windows Insider program participant, open and check for the latest Insider builds on your system. Make sure to be in the Dev or Canary channel because this experimental feature is exclusive to these channels only. Or, you can use[UUP Dump to download Windows Insider builds without participating in Microsoft’s Insider program](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) .

### 2\. Download ViVeTool

 You will also need ViVeTool to enable these experimental features on your system. You can[download ViVetool from GitHub](https://github.com/thebookisclosed/ViVe/releases) , but make sure that you pick the most recent release. Extract the tool to the C drive and then proceed to the next section.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006928/19272" target="_top" id="2006928">
  <img src="//a.impactradius-go.com/display-ad/19272-2006928" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006928/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134242/18498" target="_top" id="2134242">
  <img src="//a.impactradius-go.com/display-ad/18498-2134242" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134242/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to View the Gallery in File Explorer

 You can access the Gallery section by launching File Explorer and clicking on the Gallery option in the left navigation pane. You will see all the images from the Pictures folder and OneDrive folder arranged by modification time (new to old). There is also a handy slider to scroll through the vast image tiles without using the mouse scroll wheel.

![Gallery in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/gallery-in-windows-file-explorer.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461">
  <img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The gallery app allows you to adjust the view of the image tiles to accommodate more or less in a single window. You can use the View option in the menu bar of File Explorer to change the image tile size. If you click on any image, it will open in a separate app window (Photos app or any other app that you use).

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

## Problems With the Gallery Section in Windows File Explorer

 The current preview of the Gallery feature is far from perfect. Firstly, the section works well in finding and categorically listing all the images from the included folders. But the images, despite being big, appear hazy. What’s the point of including a section if the images aren’t visible clearly?

 There is also the issue of images opening in a separate tab rather than in the same File Explorer window. If you plan to open the image in another window, you can do it from the image folder as well. So, future builds should include an option to preview the image in the File Explorer window. Otherwise, you are opening two apps to achieve the same thing. The Gallery section cannot list any videos as well and just ignores all the video files.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137380/7443" target="_top" id="2137380">
  <img src="//a.impactradius-go.com/display-ad/7443-2137380" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137380/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-bridging-gaps-transforming-trend-data-into-video-concepts/"><u>[New] 2024 Approved Bridging Gaps Transforming Trend Data Into Video Concepts</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-branding-breakthrough-constructing-logos-for-podcasts/"><u>[New] Branding Breakthrough Constructing Logos for Podcasts</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-mastering-money-making-top-13-strategies-for-novice-reddit-users/"><u>2024 Approved Mastering Money-Making Top 13 Strategies for Novice Reddit Users</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-realme-c67-4g-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Realme C67 4G</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/charting-your-path-to-success-in-youtubes-earnings-system-for-2024/"><u>Charting Your Path to Success in YouTube's Earnings System for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-windows-pe-file-system/"><u>Decoding Windows' PE File System</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tuning-fn-keys-windows-10-and-11-techniques/"><u>Fine-Tuning FN Keys: Windows 10 and 11 Techniques</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-corrupt-mp4-and-mov-files-of-11-proplus-using-video-repair-utility-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair corrupt MP4 and MOV files of 11 Pro+ using Video Repair Utility on Windows?</u></a></li>
<li><a href="https://windows11.techidaily.com/howtodarkennotepadwindesktop/"><u>HowToDarkenNotepadWinDesktop</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-did-your-apple-iphone-15-pro-passcode-change-itself-unlock-it-now-drfone-by-drfone-ios/"><u>In 2024, Did Your Apple iPhone 15 Pro Passcode Change Itself? Unlock It Now | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-call-issue-fixed-runtime-errors-in-malwarebytes-for-win10win11/"><u>Overcoming the Call Issue: Fixed Runtime Errors in Malwarebytes for Win10/Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-gl-driver-error-3-on-windows-11-a-step-by-step-guide/"><u>Resolving GL Driver Error 3 on Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/restore-full-size-to-your-windows-11-icons/"><u>Restore Full Size to Your Windows 11 Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-your-system-without-relying-on-bitlocker/"><u>Securing Your System without Relying on Bitlocker</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-correct-sound-hiccup-in-audacity-on-windows-11/"><u>Strategies to Correct Sound Hiccup in Audacity on Windows 11</u></a></li>
<li><a href="https://driver-install.techidaily.com/unlocking-w11plus-windows-8plus-with-asus-bluetooth-drivers/"><u>Unlocking W11+ Windows 8+ with ASUS Bluetooth Drivers</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-create-unforgettable-lip-sync-videos-with-these-5-top-rated-apps/"><u>Updated In 2024, Create Unforgettable Lip Sync Videos with These 5 Top-Rated Apps</u></a></li>
</ul></div>

