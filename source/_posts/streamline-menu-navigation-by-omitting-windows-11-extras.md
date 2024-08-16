---
title: Streamline Menu Navigation by Omitting Windows 11 Extras
date: 2024-08-15T16:17:32.000Z
updated: 2024-08-16T16:17:32.000Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Streamline Menu Navigation by Omitting Windows 11 Extras
excerpt: This Article Describes Streamline Menu Navigation by Omitting Windows 11 Extras
keywords: Simplify Menu Streamlining,Reduce W11 Add-Ons,Optimize UI Layouts,Clean Menu Navigation,Minimize Windows Extras,Enhance Menu Clarity,Eliminate Unnecessary Features
thumbnail: https://thmb.techidaily.com/2f486f4dd87aa179d36ac9cfba84a9e655bb2170ba42ee253c3df8a8c92937c0.jpg
---

## Streamline Menu Navigation by Omitting Windows 11 Extras

 Windows 11 comes with a fresh new look and has mainly got a positive response for its new interface. However, there are a couple of features that are not being welcomed by the users. For instance, the addition of the "show more options" entry to the right-click context menu.

 Although it was introduced to simplify things, many users still prefer the old context menu from Windows 10\. Fortunately, you can remove Show more options from the context menu on Windows 11 by following the below methods.

## 1\. How to Remove "Show More Options" From the Context Menu With Folder Options

 The[Windows Folder Options](https://www.makeuseof.com/windows-folder-options-guide/) in File Explorer is the go-to place to view and manage File Explorer settings. You can use it to[enable compact view in File Explorer on Windows 11](https://www.makeuseof.com/how-to-enable-compact-view-windows-11-file-explorer/) , manage file thumbnails, remove the "show more options" entry, and much more.

 Here's how to use the folder option to remove the "show more options" entry from the context menu:

1. Press the**Win + E** hotkey to open the**File Explorer.**
2. Click the three horizontal dots at the top bar and choose**Options.**
3. In the**Folder Options,** switch to the**View** tab.
4. Check the**Launch folder** **windows in a separate process** box.  
![Launch folder windows in a separate process box in the Folder option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/launch-folder-windows-in-a-separate-process-box.jpg)
5. Click**Apply** \>**OK** to save the changes.

Next, restart your computer for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Remove Show More Options From the Context Menu Using the Command Prompt

 If you're a power user, you can use Command Prompt to remove the "show more options" entry from the context menu. Here's how:

1. Open the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Command Prompt** and choose**Run as administrator** from the right pane.
3. Click**Yes** to the UAC that crops up.
4. In the elevated Command Prompt window, type the following command and press**Enter** :  
`reg add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve`

![Command to Remove Context menu in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/command-to-remove-context-menu.jpg)

 After executing the command, you'll see the "The operation completed successfully" message to confirm that it went through.

 Now, you will have to restart Windows Explorer to see the changes. To do that, open the**Task Manager** (see how to[launch the Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) ), right-click on**Windows Explorer,** and choose**Restart.**

 Check if you can see the changes. If not, then you will have to restart your computer for the changes to take effect.

 In the future, if you want to add the "show more options" entry to the context menu, then open Command Prompt with admin rights and run the following command:

`reg delete "HKEY_CURRENT_USER\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}" /f​`

## 3\. Remove Show More Options From the Context Menu Using the Registry Editor

 Another quick way to remove the "show more options" entry is through the Registry Editor. Here's what you need to do:

 Before making any changes to the registry, ensure you've[created a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) or[back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . This will ensure your system settings and files are secure, and you can quickly access them if something goes wrong.

1. Open the Start Menu, type**Registry Editor** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID`
3. Right-click on the empty space on the right pane, click**New,** and then select**DWORD** **(32-bit) Value** from the context menu.
4. Name the value as**"UndockingDisabled"** and press**Enter** .  
![UndockingDisabled entry in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/undockingdisabled-entry.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Double-click on the UndockingDisabled key, type**1** in the**Value data,** and click**OK** to save the changes.  
![Editing UndockingDisabled in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/editing-undockingdisabled.jpg)

<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Remove the "Show More Options" Entry From the Context Menu Using Winaero Tweaker

 There are plenty of third-party tools using which you can customize the look of your Windows 11 computer. For this guide, we will use Winaero Tweaker.

 Here's how to download Winaero Tweaker and use it to remove the "show more options" entry from the context menu:

1. Download the[Winaero Tweaker zip file](https://winaero.com/downloads/winaerotweaker.zip) on your computer.
2. Unzip the file, open the executable, and then follow the on-screen instructions to install it on your computer.
3. Launch Winaero Tweaker and choose the**Classic Full Context Menus** option from the left sidebar.  
![Classic Full Context Menus option of Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/classic-full-context-menus-option.jpg)
<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Check the**Enable classic full context menus** box.  
![Enable classic full context menus option in Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-classic-full-context-menus.jpg)
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Click the**Restart Explorer** button that appears.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
## Enjoy an Old School Context Menu on Windows 11

 The desktop context menu lets you quickly access areas like the personalization menu, display settings, and much more. In Windows 11, you get the new "Show more options" entry in the context menu. But if you prefer the old design, you can quickly disable the "Show more options" entry from the context using either of the above methods.


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
<li><a href="https://youtube-lab.techidaily.com/024-approved-sourav-joshis-path-to-wealth-via-youtube/"><u>[New] 2024 Approved  Sourav Joshi's Path to Wealth via YouTube</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-what-is-a-parody-and-how-to-make-a-parody-video/"><u>[New] In 2024, What Is a Parody and How to Make a Parody Video</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-audio-amplification-adding-tracks-to-premiere-projects-with-ease/"><u>[Updated] Audio Amplification  Adding Tracks to Premiere Projects with Ease</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-starting-simple-how-to-create-your-own-twitter/"><u>[Updated] Starting Simple  How to Create Your Own Twitter</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-chromatic-symphony-the-filmmakers-toolkit/"><u>2024 Approved  Chromatic Symphony  The Filmmaker's Toolkit</u></a></li>
<li><a href="https://windows11.techidaily.com/activate-virtualization-your-step-by-step-guide-for-win-11-homes/"><u>Activate Virtualization: Your Step by Step Guide for Win 11 Homes</u></a></li>
<li><a href="https://windows11.techidaily.com/beginners-manual-discovering-windows-aids-and-assists/"><u>Beginner's Manual: Discovering Windows Aids and Assists</u></a></li>
<li><a href="https://tech-revival.techidaily.com/beyond-automation-8-essential-facts-about-ai-chatbot-shortcomings-in-content-writing/"><u>Beyond Automation: 8 Essential Facts About AI Chatbot Shortcomings in Content Writing</u></a></li>
<li><a href="https://windows11.techidaily.com/brushstrokes-begin-accessing-microsoft-paint-in-windows-11/"><u>Brushstrokes Begin: Accessing Microsoft Paint in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-blank-login-issues-on-win1011-pcs/"><u>Clearing Up Blank Login Issues on WIN10/11 PCs</u></a></li>
<li><a href="https://network-issues.techidaily.com/eliminating-dark-mode-black-screen-post-update/"><u>Eliminating Dark Mode BLACK SCREEN Post Update</u></a></li>
<li><a href="https://windows11.techidaily.com/ensure-smooth-os-operation-autoupdate-and-change-amd-drivers/"><u>Ensure Smooth OS Operation: Autoupdate & Change AMD Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-strategies-for-overcoming-windows-error-code-0x80040610/"><u>Essential Strategies for Overcoming Windows Error Code 0X80040610</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-strategies-for-effortless-integration-of-directories-win-11/"><u>Expert Strategies for Effortless Integration of Directories, Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fast-factor-essential-steps-for-assessing-lan-router-speed/"><u>Fast Factor: Essential Steps for Assessing LAN Router Speed</u></a></li>
<li><a href="https://driver-download.techidaily.com/1722964875801-get-your-new-nvidia-quadro-rtx-8000-drivers-now-compatible-with-windows-1087/"><u>Get Your New Nvidia Quadro RTX 8000 Drivers Now: Compatible with Windows 10/8/7</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-display-apple-iphone-11-pro-max-screen-on-pc-easily-drfone-by-drfone-ios/"><u>How to Display Apple iPhone 11 Pro Max Screen on PC Easily? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-muted-audio-recordings-in-obs-studio-on-windows-11-pcs/"><u>How to Fix Muted Audio Recordings in OBS Studio on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-pin-gmail-to-the-taskbar-on-a-windows-pc/"><u>How to Pin Gmail to the Taskbar on a Windows PC</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-crafting-content-that-captivates-a-guide-to-facebook-reels/"><u>In 2024, Crafting Content that Captivates  A Guide to Facebook Reels</u></a></li>
<li><a href="https://youtube-help.techidaily.com/making-every-minute-count-youtube-length-reduction-techniques-for-2024/"><u>Making Every Minute Count  YouTube Length Reduction Techniques for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-terminal-personalize-colors-and-style/"><u>Mastering Terminal: Personalize Colors & Style</u></a></li>
<li><a href="https://windows11.techidaily.com/maximize-your-taskbar-attaching-items-in-windows-11/"><u>Maximize Your Taskbar: Attaching Items in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-default-usb-suspension-on-windows-11/"><u>Overcoming Default USB Suspension on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-system-shutdown-alerts-due-to-roblox-glitches/"><u>Overcoming System Shutdown Alerts Due to Roblox Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-the-process-setting-up-msoffice-in-windows-11/"><u>Perfecting the Process: Setting Up MSOffice in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-failed-jvm-launch-windows-guide/"><u>Remedying Failed JVM Launch: Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-non-existent-device-alerts-on-windows-1011/"><u>Resolving Non-Existent Device Alerts on Windows 10/11</u></a></li>
<li><a href="https://fix-guide.techidaily.com/solved-warning-camera-failed-on-vivo-y200e-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Solved Warning Camera Failed on Vivo Y200e 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/supporting-the-unsupported-life-after-windows-781/"><u>Supporting the Unsupported: Life After Windows 7/8.1</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-vivo-y02t-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Vivo Y02T? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-how-to-stop-game-proposals/"><u>Win11: How To Stop Game Proposals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/window-management-adding-this-pc-to-windows-desktop/"><u>Window Management: Adding 'This PC' To Windows Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-upcoming-moment-anticipated-new-features/"><u>Windows 11'S Upcoming Moment: Anticipated New Features</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-the-battle-against-windows-software-problems-7-ways/"><u>Winning the Battle Against Windows Software Problems (7 Ways)</u></a></li>
<li><a href="https://windows11.techidaily.com/winrars-corrected-compression-overcoming-sum-errors/"><u>WinRAR's Corrected Compression: Overcoming Sum Errors</u></a></li>
</ul></div>
