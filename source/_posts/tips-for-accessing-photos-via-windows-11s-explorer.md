---
title: Tips for Accessing Photos via Windows 11'S Explorer
date: 2024-08-22T21:42:22.389Z
updated: 2024-08-23T21:42:22.389Z
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

## How to Enable Gallery in File Explorer in Windows 11

 Repeat the following steps to enable the new Gallery section in File Explorer:

### 1\. Update to the Appropriate Windows Insider Build

 The Gallery section is hidden in Insider builds 25300 and above. If you are a Windows Insider program participant, open and check for the latest Insider builds on your system. Make sure to be in the Dev or Canary channel because this experimental feature is exclusive to these channels only. Or, you can use[UUP Dump to download Windows Insider builds without participating in Microsoft’s Insider program](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) .

### 2\. Download ViVeTool

 You will also need ViVeTool to enable these experimental features on your system. You can[download ViVetool from GitHub](https://github.com/thebookisclosed/ViVe/releases) , but make sure that you pick the most recent release. Extract the tool to the C drive and then proceed to the next section.

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The gallery app allows you to adjust the view of the image tiles to accommodate more or less in a single window. You can use the View option in the menu bar of File Explorer to change the image tile size. If you click on any image, it will open in a separate app window (Photos app or any other app that you use).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4693127&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.videosoftdev.com/images/video_editor/screenshots/1.jpg" border="0">
VSDC Pro Video Editor is a light professional non-linear video editing suite for creating a movie of any complexity. It supports the most popular video/audio formats and codecs, including 4K, HD and GoPro videos. Preconfigured profiles make the creation of videos for various multimedia and mobile devices absolutely hassle-free.

Key features:

•	Import from any devices and cams, including GoPro and drones. All formats supported. Сurrently the only free video editor that allows users to export in a new H265/HEVC codec, something essential for those working with 4K and HD.
•	Everything for hassle-free basic editing: cut, crop and merge files, add titles and favorite music
•	Visual effects, advanced color correction and trendy Instagram-like filters   
•	All multimedia processing done from one app: video editing capabilities reinforced by  a video converter, a screen capture, a video capture, a disc burner and a YouTube uploader
•	Non-linear editing: edit several files with simultaneously 
•	Easy export to social networks: special profiles for YouTube, Facebook, Vimeo, Twitter and Instagram
•	High quality export – no conversion quality loss, double export speed even of HD files due to hardware acceleration
•	Stabilization tool will turn shaky or jittery footage into a more stable video automatically. 
•	Essential toolset for professional video editing: blending modes, Mask tool, advanced multiple-color Chroma Key  
</a>
<!-- affiliate ads end -->
## How to Add or Remove Locations From Gallery in Windows File Explorer

 By default, the Gallery selection displays all the images located in the Pictures folder and OneDrive. But you can add or remove a folder from the Gallery section as well.

1. To add a folder to the Gallery, go to the menu bar and click on the**Locations** option. A new pop-up window will open and list all the folders that the Gallery section is pulling images from. Click on the**Add** button.  
![Adding a Folder to Gallery in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/adding-a-folder-to-gallery-in-windows-file-explorer.jpg)
2. Now select any folder or sub-folder with images and click on the**Include Folder** button.
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
3. The selected folder will appear in the list of available folders. Click on the**OK** button.
4. File Explorer gallery will now display the images present inside the newly added folder as well.

To remove a folder from Gallery, repeat the following steps:

1. Open the Gallery section and click on the**Locations** option in the menu bar.
2. You will see the list of all the folders currently included in the Gallery.
3. Click on the folder you want to remove to select it. Then click on the**Remove** button.  
![Removing a Folder from Gallery in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/removing-a-folder-from-gallery-in-windows-file-explorer.jpg)
4. Lastly, click on the**OK** button to finalize the changes. The Gallery section won’t display any images from the excluded folder from now onwards.
<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Problems With the Gallery Section in Windows File Explorer

 The current preview of the Gallery feature is far from perfect. Firstly, the section works well in finding and categorically listing all the images from the included folders. But the images, despite being big, appear hazy. What’s the point of including a section if the images aren’t visible clearly?

 There is also the issue of images opening in a separate tab rather than in the same File Explorer window. If you plan to open the image in another window, you can do it from the image folder as well. So, future builds should include an option to preview the image in the File Explorer window. Otherwise, you are opening two apps to achieve the same thing. The Gallery section cannot list any videos as well and just ignores all the video files.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
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
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-transform-your-ppts-into-stunning-video-content/"><u>[New] 2024 Approved  Transform Your PPTs Into Stunning Video Content</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-reclaim-inaccessible-watch-icon/"><u>[New] In 2024, Reclaim Inaccessible Watch Icon</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-unveiling-top-5-easy-to-use-cost-effective-zoom-transcription-tools/"><u>[New] Unveiling Top 5 Easy-to-Use, Cost-Effective Zoom Transcription Tools</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-recording-your-live-feed-without-spending-a-dime/"><u>[Updated] Recording Your Live Feed without Spending a Dime</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-premium-cloud-based-recorder-tech/"><u>2024 Approved  Premium Cloud-Based Recorder Tech</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-pure-portrayals-on-platforms-your-guide-to-authentic-snapshots/"><u>2024 Approved  Pure Portrayals on Platforms  Your Guide to Authentic Snapshots</u></a></li>
<li><a href="https://howto.techidaily.com/9-quick-fixes-to-unfortunately-touchwiz-has-stopped-of-vivo-s17e-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Quick Fixes to Unfortunately TouchWiz has stopped Of Vivo S17e | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/empowering-video-content-with-advanced-aiseesoft-tech/"><u>Empowering Video Content with Advanced Aiseesoft Tech</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-fatigued-performance-in-win10plusedge-browser/"><u>Fixing Fatigued Performance in Win10+Edge Browser</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-windows-10-update-error-code-0xc1900208-a-step-by-step-guide/"><u>Fixing Windows 10 Update Error Code 0xC1900208: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/gaming-past-present-atlasos-enablement/"><u>Gaming Past, Present: AtlasOS Enablement</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-screens-revealed-the-most-effective-6-techniques-to-recover-off-screen-apps-in-win/"><u>Hidden Screens Revealed: The Most Effective 6 Techniques to Recover Off-Screen Apps in Win</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-ignore-microsofts-app-verification-warnings/"><u>How to Ignore Microsoft's App Verification Warnings</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-a-unresponsive-windows-start-button/"><u>How to Reactivate a Unresponsive Window's Start Button</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-resolve-offline-printer-problems-in-os/"><u>How To Resolve Offline Printer Problems in OS</u></a></li>
<li><a href="https://some-techniques.techidaily.com/how-to-use-free-countdown-timer-for-2024/"><u>How to Use Free Countdown Timer for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-crafting-squares-for-viral-videos-in-a-social-media-world/"><u>In 2024, Crafting Squares for Viral Videos in a Social Media World</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/in-2024-vloggers-money-saving-camera-recommendations/"><u>In 2024, Vloggers' Money-Saving Camera Recommendations</u></a></li>
<li><a href="https://windows11.techidaily.com/isolating-and-resolving-unilateral-sound-issue-on-win-os/"><u>Isolating and Resolving Unilateral Sound Issue on WIN OS</u></a></li>
<li><a href="https://driver-error.techidaily.com/keybacklight-dark-issue-asus/"><u>Keybacklight Dark Issue - ASUS</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-calculators-dark-scheme/"><u>Mastering Windows Calculator's Dark Scheme</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-reinstate-working-utorrent-installer-in-various-windows-versions/"><u>Methods to Reinstate Working uTorrent Installer in Various Windows Versions</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-setbacks-due-to-recent-windows-installation/"><u>Overcoming Setbacks Due to Recent Windows Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-battlenet-being-inaccessible-in-windows-1011/"><u>Quick Fixes for Battle.net Being Inaccessible in Windows 10/11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/revealing-top-streamers-expert-tips-on-choosing-right/"><u>Revealing Top Streamers  Expert Tips on Choosing Right</u></a></li>
<li><a href="https://tech-revival.techidaily.com/securing-ai-conversations-chatgpt-and-vpn-strategies/"><u>Securing AI Conversations: ChatGPT & VPN Strategies?</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-fixing-windows-updates-error-xcode-0x80246007/"><u>Solutions for Fixing Windows Updates Error – XCode 0X80246007</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-file-transfer-problems-on-windows-1011/"><u>Solutions to File Transfer Problems on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-failed-page-loading-on-ms-store/"><u>Steps to Resolve Failed Page Loading on MS Store</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-tackle-stranded-error-on-xbox-app-windows-devices/"><u>Steps to Tackle 'Stranded' Error on Xbox App Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-resolve-windows-1110s-nvidia-access-problem/"><u>Strategies to Resolve Windows 11/10'S NVidia Access Problem</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-future-of-drone-control-with-syma-x8c-for-2024/"><u>The Future of Drone Control with Syma X8C for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-quintessential-social-media-quartet-facebook-twitter-instagram-and-youtube/"><u>The Quintessential Social Media Quartet: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-collection-of-task-management-tools-for-windows-11-users/"><u>The Ultimate Collection of Task Management Tools for Windows 11 Users</u></a></li>
<li><a href="https://extra-information.techidaily.com/top-tips-for-flawless-green-screen-cinematography/"><u>Top Tips for Flawless Green-Screen Cinematography</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-file-download-issues-on-windows-11-6/"><u>Troubleshooting File Download Issues on Windows 11 (6)</u></a></li>
<li><a href="https://windows11.techidaily.com/unchained-gpt-on-your-machine-using-freedomgpt/"><u>Unchained GPT on Your Machine: Using FreedomGPT</u></a></li>
<li><a href="https://windows11.techidaily.com/what-are-windows-bsod-memory-dumps-and-how-can-they-help-you/"><u>What Are Windows BSoD Memory Dumps, and How Can They Help You?</u></a></li>
</ul></div>