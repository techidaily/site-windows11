---
title: Tips for Accessing Photos via Windows 11'S Explorer
date: 2024-11-14T16:59:58.010Z
updated: 2024-11-15T16:52:53.162Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tips for Accessing Photos via Windows 11'S Explorer
excerpt: This Article Describes Tips for Accessing Photos via Windows 11'S Explorer
keywords: Windows 11 Photo Access,Windows 11 Explorer Views,Photo Explorer Windows 11,Win11 Image Browsing,Windows 11 Photo Tools,Quick Photos in Windows 11,Windows 11 Photo Explorer
thumbnail: https://thmb.techidaily.com/d9d28999ab80c3fe303824be9f1e02b9cc335e9a7ef77a5fdd8ceeee3dcb3523.jpg
---

## Tips for Accessing Photos via Windows 11'S Explorer

 Windows 11’s File Explorer has a tabs feature now. You can open a new location on the disk in a new tab rather than opening a new File Explorer window. Switching between multiple file locations is seamless, all thanks to this feature. But Microsoft isn’t planning to stop here. It wants to completely overhaul the File Explorer.

 File Explorer Gallery is one such new feature that Microsoft is testing in the Canary channel. Having a Gallery section will remove the need to browse separate folders to find or preview an image. Want to enable the feature on your system? Let’s begin.

## What Is the Gallery Feature in Windows File Explorer?

 File Explorer’s Gallery feature works exactly like it sounds. It categorically lists all the images on your system in a separate section, so you can find and view all the images in one tab. Android File Explorers have had this feature for quite a long, but Windows seems to care about it now.

 This new feature is available in the Windows Insider build version 25300 and above. But Microsoft made a big change to the Insider program by adding a Canary channel. So, any new Canary build will also have this experimental feature. Microsoft adds the new File Explorer based on Windows App SDK, which you can verify by hovering over the “pizza” icon in the File Explorer address bar.

 The Gallery section displays images from the Pictures and OneDrive folders and lists them by date. It has nice, rounded corners around each image in the Gallery section, which makes it feel like a part of the overall Windows 11 design. It appears right below the Home option in the left pane.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151859/7443" target="_top" id="2151859">
  <img src="//a.impactradius-go.com/display-ad/7443-2151859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151859/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Enable Gallery in File Explorer in Windows 11

 Repeat the following steps to enable the new Gallery section in File Explorer:

### 1\. Update to the Appropriate Windows Insider Build

 The Gallery section is hidden in Insider builds 25300 and above. If you are a Windows Insider program participant, open and check for the latest Insider builds on your system. Make sure to be in the Dev or Canary channel because this experimental feature is exclusive to these channels only. Or, you can use[UUP Dump to download Windows Insider builds without participating in Microsoft’s Insider program](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) .

### 2\. Download ViVeTool

 You will also need ViVeTool to enable these experimental features on your system. You can[download ViVetool from GitHub](https://github.com/thebookisclosed/ViVe/releases) , but make sure that you pick the most recent release. Extract the tool to the C drive and then proceed to the next section.

### 2\. Enabling Gallery in Windows File Explorer

 Retrace the following steps to enable the Gallery section on Windows 11:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** and press**Ctrl + Shift + Enter** keys at once to open a new Command Prompt window with administrator privileges.
2. Now, navigate to the main directory in C drive. Type**cd C:\\ command** and press the enter key.
3. Next, type the**cd Vivetool** command to enter the folder where Vivetool is present in the C drive. It is the main reason why we suggested you extract Vivetool in a convenient location.
4. Type the**Vivetool** command and press enter key to check if the tool is accessible and working. You will see the version of the tool along with the parameters it supports.  
![Enable Gallery in File Explorer in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-gallery-in-file-explorer-in-windows-11.jpg)
5. Now, type the following command and press the enter key:  

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/798165/11305" target="_top" id="798165">
  <img src="//a.impactradius-go.com/display-ad/11305-798165" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i110150.net/i/5597632/798165/11305" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

vivetool /enable /id:41040327
6. If the command executes correctly, you will see a “Successfully set feature configuration(s)” message. But don’t close the Command Prompt window. Type the following commands to enable all the Gallery features one by one and execute them.  
vivetool /enable /id:40729001 vivetool /enable /id:40731912 vivetool /enable /id:41969252 vivetool /enable /id:42922424 vivetool /enable /id:42295138
7. After running all the commands without any error, type**exit** and press the enter key to close the command prompt window.  
![Enable Gallery in File Explorer in Windows 11 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-gallery-in-file-explorer-in-windows-11-2.jpg)
8. Restart your computer for the changes made by Vivetool to take effect.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148638/16836" target="_top" id="2148638">
  <img src="//a.impactradius-go.com/display-ad/16836-2148638" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148638/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Once your computer boots up, press**Win + E** to open File Explorer. You will see a new**Gallery** option in the left pane below the**Home** option.

## How to View the Gallery in File Explorer

 You can access the Gallery section by launching File Explorer and clicking on the Gallery option in the left navigation pane. You will see all the images from the Pictures folder and OneDrive folder arranged by modification time (new to old). There is also a handy slider to scroll through the vast image tiles without using the mouse scroll wheel.

![Gallery in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/gallery-in-windows-file-explorer.jpg)

<!-- affiliate ads begin -->
<span id="1975658">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975658.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975658">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975658.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975658%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975658/22993" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130529/26400" target="_top" id="2130529">
  <img src="//a.impactradius-go.com/display-ad/26400-2130529" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130529/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-eye-catching-tiktok-personalities-30-pfp-strategies/"><u>[Updated] 2024 Approved Eye-Catching TikTok Personalities 30 PFP Strategies</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-quick-tips-for-seamless-embedding-of-youtube-playlists-on-a-website/"><u>[Updated] 2024 Approved Quick Tips for Seamless Embedding of YouTube Playlists on a Website</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-chrome-crashes-or-wont-open-on-vivo-s18-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Chrome Crashes or Wont Open on Vivo S18 | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/capturing-moments-right-ideal-perspectives-on-iphone-for-2024/"><u>Capturing Moments Right Ideal Perspectives on iPhone for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-activation-problem-eliminate-error-0x803f700f/"><u>Fixing Windows Activation Problem: Eliminate Error 0X803F700f</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-discord-fatal-javascript-error-in-windows-11-and-11/"><u>How to Fix the Discord Fatal Javascript Error in Windows 11 & 11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-icloud-on-iphone-15-plus-smoothly-by-drfone-ios/"><u>In 2024, How To Remove iCloud On iPhone 15 Plus Smoothly</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-samsung-galaxy-a15-5g-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Samsung Galaxy A15 5G to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-master-levels-enhancing-steam-gameplay-videos/"><u>In 2024, Master Levels Enhancing Steam Gameplay Videos</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-the-modern-filmmakers-guide-for-computer-mac-and-mobile/"><u>In 2024, The Modern Filmmaker's Guide for Computer, Mac & Mobile</u></a></li>
<li><a href="https://program-issues.techidaily.com/pathfinder-overcoming-frequent-system-crashes-with-wrath-of-the-righteous-solution-steps/"><u>Pathfinder: Overcoming Frequent System Crashes with Wrath of the Righteous Solution Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/precision-and-convenience-meet-with-our-winning-window-timers-list/"><u>Precision & Convenience Meet With Our Winning Window Timers List</u></a></li>
<li><a href="https://sound-issues.techidaily.com/quick-guide-to-restoring-full-sound-capacity-on-windows-10-devices/"><u>Quick Guide to Restoring Full Sound Capacity on Windows 10 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/re-establishing-classic-navigation-in-win-11/"><u>Re-Establishing Classic Navigation in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-repair-disk-errors-in-windows-os/"><u>Steps to Repair Disk Errors in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-your-wi-fi-networks-usage-metrics-with-windows-11/"><u>Tailoring Your Wi-Fi Network's Usage Metrics with Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-absence-of-files-on-windows-11/"><u>Troubleshooting Absence of Files on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-your-pcs-true-power-with-enhanced-vram-settings-in-windows-10-and-11/"><u>Unleash Your PC's True Power with Enhanced VRAM Settings in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-memory-write-hitches-in-windows/"><u>Unraveling 'Memory Write' Hitches in Windows</u></a></li>
</ul></div>

