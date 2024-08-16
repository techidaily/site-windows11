---
title: "Maximizing Windows: Unlocking DiskUsage Insights for Storage Management"
date: 2024-08-15T16:13:28.875Z
updated: 2024-08-16T16:13:28.875Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Maximizing Windows: Unlocking DiskUsage Insights for Storage Management"
excerpt: "This Article Describes Maximizing Windows: Unlocking DiskUsage Insights for Storage Management"
keywords: Disk Usage Analysis,Storage Optimization,Data Management Tips,Increase PC Performance,Reduce System Clutter,Windows Storage Insights,Maximize Hard Drive Space
thumbnail: https://thmb.techidaily.com/d3a69700e0cb55adae67e72e210fb2f2a9d54f1a94f5e0b261b4ccf5f3207b46.jpg
---

## Maximizing Windows: Unlocking DiskUsage Insights for Storage Management

 The DiskUsage.exe tool can be used to analyze the contents of any drive or folder on Windows 11\. DiskUsage is accessed from the command line and includes many options for filtering and refining the file data that can be output. In certain situations, this can make it far more useful than GUI tools like Storage Sense.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

## View Disk Usage of Any Drive or Folder

 The simplest way to use the DiskUsage command line tool is to get an overview of how space is currently used in almost a drive or folder. We have used the tool on Windows 11, but it is also available on Windows 10\.

1. Run the Command Prompt as an admin. If you need help, check out [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. In Command Prompt type **DiskUsage** followed by the path to the drive or folder you want to analyze.
3. For example, to view the disk usage of the Pictures folder, type: **DiskUsage C:\\Users\\UserName\\Pictures**, and press **Enter**.  
![The disk usage command in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-cmd.jpg)
4. To see the SizeOnDisk number in a human-readable format, e.g. KB, MB, or GB, add **/h** to the end of the command.
5. In our example, this looks like **DiskUsage C:\\Users\\UserName\\Pictures /h**.  
![Disk usage date displayed in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-data.jpg)

 You can use DiskUsage to analyze any folder in the same way. You can even check internal and external drives, including the C: drive. Bear in mind that analyzing a drive such as C: will spew out a huge list of files and folders in DiskUsage.

 If using DiskUsage.exe seems too complicated, you can easily view how disk space is being used with [Storage Sense](https://www.makeuseof.com/windows-11-storage-sense-guide/).

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
## List All Files Larger Than a Specified Size

 You can refine the data displayed in DiskUsage based on file size. So if, for example, you only want to include files over 500MB, you can set it to ignore smaller files.

1. To only include files above a specific size, you need to add the minFileSize option to the command.
2. As an example: **DiskUsage /minFileSize=6553600 C:\\Users\\UseName\\Downloads /h**.
3. This will only look for files in Downloads larger than 50MB and then display the disk space those files occupy in that location.
4. The file size number must be entered in bytes, so you might have to convert MB to Byte using an online conversion tool.

 For a more detailed view of large files, including file name as well as size, you can use the **/u** command modifier. This allows you to list a defined number of the largest files in the drive or folder.

1. To do this type: **DiskUsage C:\\Users\\UserName\\Downloads /h /u=15**.
2. The 15 largest files in the Downloads folder will now be listed in Command Prompt.  
![file data listed in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-list.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
3. You can replace the number with any other you want to use. For example, to see the top 5 files taking up space, use **/u=5**.
4. Make sure to include the **/h** option so that the output is in a format that's easy to read.

 After identifying what is taking up the most space, you can use any one of these [methods to delete large files](https://www.makeuseof.com/windows-11-delete-select-files/).

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
## Additional DiskUsage Command Options

 The DiskUsage tool contains several other useful options that you can use to filter the output. You can filter by filename, display reserved space, or the largest directories within the folder.

 For example, to filter by filename add **/n=installer** to the end of the command to display only files that contain the word installer.

 You can see a complete list of the options by typing **DiskUsage /?** and pressing **Enter**.

![A list of DiskUsage options in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-options.jpg)
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Analyze Drive Space With DiskUsage

 Many of the available command line tools are extremely useful for maintaining and managing your Windows PC. And as this guide shows, DiskUsage.exe is a powerful alternative to graphical UI tools such as Storage Sense if you want to really dig down into how your drive space is being used.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-youtube-video-dimension-standards/"><u>[New] 2024 Approved  YouTube Video Dimension Standards</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-beyond-photography-an-exhaustive-review-of-the-toolwiz-app-2023/"><u>[New] Beyond Photography  An Exhaustive Review of the Toolwiz App, 2023</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-the-ultimate-guide-to-high-definition-hd-youtube-and-fb-videos/"><u>[New] The Ultimate Guide to High Definition (HD) YouTube & FB Videos</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-navigate-the-nuances-of-zooms-broadcast-technology-for-youtube-pros/"><u>2024 Approved  Navigate the Nuances of Zoom's Broadcast Technology for YouTube Pros</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-maximize-your-library-a-comprehensive-list-of-online-mp3-tag-editor-powerhouses/"><u>2024 Approved Maximize Your Library A Comprehensive List of Online MP3 Tag Editor Powerhouses</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerated-cross-language-compreinasion-via-windows-keyboard-tricks/"><u>Accelerated Cross-Language Compreinasion via Windows Keyboard Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-xc0000142-issue-in-windows-11-10/"><u>Correcting XC0000142 Issue in Windows 11, 10</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-windows-gadgets-2024s-must-haves-list/"><u>Cutting-Edge Windows Gadgets - 2024'S Must-Haves List</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-misentered-characters-in-windows-os/"><u>Dealing with Misentered Characters in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-your-global-ip-on-win-os-via-cli/"><u>Demystifying Your Global IP on WIN OS via CLI</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-pubg-save-problems-on-windows-systems/"><u>Eliminating PUBG Save Problems on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-pc-sounds-with-windows-11s-mixer-feature/"><u>Enhance PC Sounds with Windows 11'S Mixer Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-reliability-of-your-windows-interface/"><u>Enhancing Reliability of Your Windows Interface</u></a></li>
<li><a href="https://fake-location.techidaily.com/full-guide-to-fix-itoolab-anygo-not-working-on-xiaomi-14-pro-drfone-by-drfone-virtual-android/"><u>Full Guide to Fix iToolab AnyGO Not Working On Xiaomi 14 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-how-to-deactivate-amdnvidia-vr-boosting/"><u>Guide: How to Deactivate AMD/Nvidia VR Boosting</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-gigglegallery-log-in-and-make-magic-videos/"><u>In 2024, GiggleGallery  Log In and Make Magic Videos</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-mastering-the-lens-focus-techniques-for-storify-success/"><u>In 2024, Mastering the Lens  Focus Techniques for Storify Success</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-vivo-y200e-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Unova Stone Pokémon Go Evolution List and How Catch Them For Vivo Y200e 5G | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/instant-restoration-for-missing-snaps/"><u>Instant Restoration for Missing Snaps</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-files-6-methods-to-retrieve-windows-11-paths/"><u>Mastering Files: 6 Methods to Retrieve Windows 11 Paths</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-device-id-extraction-techniques-for-windows-users/"><u>Mastery of Device ID Extraction Techniques for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-freeze-flaws-in-adobes-pc-artist-suite/"><u>Mending Freeze Flaws in Adobe's PC Artist Suite</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/microsoft-surface-laptop-4-analysis-top-performance-and-design-unveiled/"><u>Microsoft Surface Laptop 4 Analysis - Top Performance and Design Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/microsofts-surface-studio-2-a-step-towards-perfection/"><u>Microsoft's Surface Studio 2 - A Step Towards Perfection?</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11s-s-mode-is-it-worth-considering/"><u>Navigating Windows 11'S 'S Mode': Is It Worth Considering?</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-pen-pad-glitches/"><u>Overcoming Windows Pen-Pad Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/prtscn-and-snipping-tool-link-in-windows-11-prevent-connection/"><u>PrtScn & Snipping Tool Link in Windows 11: Prevent Connection</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-screen-resolution-problems-in-windows-os/"><u>Rectifying Screen Resolution Problems in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-could-not-create-vm-problems-in-microsoft-os/"><u>Remedying 'Could Not Create VM' Problems in Microsoft OS</u></a></li>
<li><a href="https://windows11.techidaily.com/resuscitate-stalled-excel-performance-in-windows-environment/"><u>Resuscitate Stalled Excel Performance in Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-to-extending-windows-1011-contextual-commands/"><u>Step-by-Step Guide to Extending Windows 10/11 Contextual Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-windows-update-fixes-for-error-0x800736cc/"><u>Streamlining Windows Update Fixes for Error 0X800736CC</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/tackling-mpeg-streamer-issues-on-latest-win11/"><u>Tackling MPEG Streamer Issues on Latest Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/taskers-edge-enigma-hidden-processes/"><u>Tasker's Edge Enigma: Hidden Processes?</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/the-art-of-language-acquisition-through-scientifically-backed-melodies/"><u>The Art of Language Acquisition Through Scientifically Backed Melodies</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-print-guide-to-making-your-powerpoint-shine-on-a-windows-system/"><u>The Ultimate Print Guide to Making Your PowerPoint Shine on a Windows System</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-battlenet-accessibility-on-1011-systems/"><u>Unlocking Battle.net Accessibility on 10/11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11s-printer-interface-max-48-chars/"><u>Unlocking Windows 11'S Printer Interface (Max 48 Chars)</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-does-enter-puk-code-mean-and-why-did-the-sim-get-puk-blocked-on-asus-rog-phone-8-pro-device-by-drfone-android/"><u>What Does Enter PUK Code Mean And Why Did The Sim Get PUK Blocked On Asus ROG Phone 8 Pro Device</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-and-discord-fixing-the-deadly-js-error-quickly/"><u>Win 11 and Discord: Fixing The Deadly JS Error Quickly</u></a></li>
</ul></div>
