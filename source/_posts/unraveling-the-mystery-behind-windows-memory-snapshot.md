---
title: Unraveling the Mystery Behind Windows' Memory Snapshot
date: 2024-08-08T06:15:03.097Z
updated: 2024-08-09T06:15:03.097Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unraveling the Mystery Behind Windows' Memory Snapshot
excerpt: This Article Describes Unraveling the Mystery Behind Windows' Memory Snapshot
keywords: Windows MemSnapshot Insight,Memory Snapshots Explained,Exploring Windows RAM Views,Deciphering Windows MemSnaps,Windows RAM Capture Clarity,Understanding MemSnaps in Win,Unveiling Windows Memory Snaps
thumbnail: https://thmb.techidaily.com/96d4e4e3696a3d428399dbec4c54090942565cd5b197d0762ff7457e8ce649a0.jpg
---

## Unraveling the Mystery Behind Windows' Memory Snapshot

 When your Windows computer is running out of storage space, you may find yourself looking for ways to free up some of it, even if they're a bit unconventional. One of these unconventional methods you may come across is deleting the Pagefile.sys file. But before you consider deleting it, you should know what Pagefile.sys is and if you should delete it in the first place.

Here's what you need to know.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
## What Is Pagefile.sys?

 Pagefile.sys is a system file in Windows set aside for your computer’s[Random Access Memory (RAM)](https://www.makeuseof.com/tag/quick-dirty-guide-ram-need-know/) , also known as physical memory. When your computer's RAM begins to run out of memory, it uses the pagefile to offload data it doesn't need, such as files and apps.

 So how does your computer’s RAM decide when to offload data? Let’s use an app as an example of how this works.

 Usually, when you minimize an app, Windows will leave it running in the background. However, it will keep its data in the RAM so it can quickly access them when needed.

 Then, when you boot up a RAM-intensive app, Windows needs to make room for it within the RAM. As such, Windows will instruct your PC’s RAM to dump the minimized app’s program files into Pagefile.sys, so it can free up memory without losing data.

 By default, Windows will store Pagefile.sys in the root folder of your local drive (C:).

 When you need to use the minimized app again, Windows will read its data from the Pagefile.sys file. And you'll be none the wiser that it's compensating for its physical memory shortcomings with the help of your local drive.

 Reading an app’s program files from Pagefile.sys is slower than reading them from RAM. The process is even slower when you're using a hard disk drive (HDD)[instead of a solid-state drive (SDD)](https://www.makeuseof.com/choose-ssd-or-hdd-storage/) . However, It’s faster than closing the app and then relaunching it.

## How to Check the Size of Pagefile.sys

 To prevent tampering with Pagefile.sys, Windows will hide it by default. If you want to see it, here’s what you should do.

1. Press**Win + E** to open File Explorer.
2. Click on**This PC** in the navigation pane on the left and double-click your**local drive (C:)** on the right to open it.
3. Now you need to open Folder Options. On Windows 11, click the**three vertical dots** in the top menu and select**Options** . On Windows 10, click**View** in the top menu and then on**Options** .  
![selecting options in the top menu of file explorer in windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/file-explorer-options.jpg)
4. Select the**View** tab in Folder Options and uncheck**Hide protected operating system files (Recommended)** .  
![The unhide protected os files option in folder options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/folder-options-unhide-protected-os-files.jpg)
5. In the warning that pops up, click**Yes** .
6. A bit further up, you see**Hidden files and folders** . Inside it, check the**Show hidden files, folders, and drives** radio button.
7. Click**OK** to close Folder Options and apply the changes.
8. Scroll down in your local drive, and you’ll be able to see Pagefile.sys.  
![the pagefile.sys file in the root folder of the local drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/pagefile-sys-file.jpg)

 As you can see, the Pagefile.sys file is quite large, which makes many people think deleting it is a good idea when they're running out of storage space.

## Should You Delete Pagefile.sys?

 One scenario where it would be reasonable to delete Pagefile.sys to save disk space is if you have a lot of RAM. That way, it can store all the data it needs to keep apps running without needing to offload them. For the average Windows user, the minimum RAM size for this would be 16GB.

 If you delete Pagefile.sys and your computer runs out of physical memory, your system will start to become sluggish. If the sluggishness gets too bad, Windows itself might even crash.

 Also, you might notice some apps becoming slower or crashing as well. That’s because they have nowhere to put the data they need to operate properly since your computer’s RAM is full and there is no Pagefile.sys to pick up the slack.

 So unless your physical memory needs aren’t greater than your installed RAM’s capacity, we recommend leaving Pagefile.sys alone.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Delete Pagefile.sys

 Since Windows is constantly using Pagefile.sys, it will not allow you to delete it in File Explorer directly. In fact, if you selected the file and hit the**Delete** key, you will see the following message: "The action can't be completed because the file is open in another program."

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
![deleting-pagefile-error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/deleting-pagefile-error.jpg)

 However, there’s another method you can use to delete the file and save some disk space. To do that, follow the steps below.

1. Press**Win + S** to open Windows Search.
2. Type**sysdm.cpl** in the search box and hit the**Enter** key to open the System Properties window.  
![searching for sysdm.cpl in windows search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/windows-search-sysdm-cpl.jpg)
3. Select the**Advanced** tab, and in the**Performance** section, click the**Settings** button.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![the system properties dialog box in windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/system-properties-advanced.jpg)
4. In the Performance Options window, select the**Advanced** tab and click**Change** .  
![the Perfomance Options window on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/performance-options-advanced.jpg)
5. In the Virtual Memory window, uncheck the**Automatically manage paging file size for all drives** checkbox at the top.
6. Click on the radio button for**No paging file** , and click the**Set** button on the right.  
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![the Virtual Memory window on Windows with the No paging radio button ticked](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-no-paging-windows.jpg)
7. You’ll get a warning from Windows. Click**Yes** to bypass it.
8. Click on**OK** to close the Virtual Memory window and apply the changes.
9. Restart your Windows computer for the changes to take effect.

 When Windows boots back up, the OS will have no use for Pagefile.sys, and it will delete it from your local drive. It will also delete the Swapfile.sys along with it. If you don't know what that file is and its importance, please read our guide on[what Swapfile.sys is and if you can delete it](https://www.makeuseof.com/windows-swapfile-sys-guide/) .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
## How to Restore Pagefile.sys

 If you deleted Pagefile.sys and discovered that you're experiencing problems because of it, you can easily restore it. However, if the problems are so severe that Windows is constantly freezing or can't even boot up properly, you should try entering Safe Mode first. To do that, please check out guides on[ways to boot into Safe Mode on Windows 11](https://www.makeuseof.com/windows-11-boot-safe-mode/) and[what is Safe Mode on Windows 10](https://www.makeuseof.com/windows-11-boot-safe-mode/) .

Now, to bring back Pagefile.sys, follow the steps below:

1. Press**Win + R** to open Windows Run.
2. In the text box, enter**sysdm.cpl** and then hit the**Enter** key to launch the System Properties window.  
<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
![opening the System Properties window using Windows Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/open-system-properties-windows-run.jpg)
3. Select the**Advanced** tab, and in the**Performance** section, click the**Settings** button.
4. In the Performance Options window, select the**Advanced** tab and click**Change** .
5. In the Virtual Memory window, make sure the**Automatically manage paging file size for all drives** checkbox at the top is checked.
6. Click on**OK** to close the Virtual Memory window and apply the changes.
7. Restart your Windows computer for the changes to take effect.

 Once your computer boots up, and you go to the folder where Pagefile.sys is located, you will see that the file has returned, along with Swapfile.sys.

## How to Resize Pagefile.sys

 If deleting Pagefile.sys isn’t an option for you, consider resizing it instead. Here’s how to do that:

1. Press**Win + E** to open File Explorer.
2. In the Navigation Pane, right-click**This PC** and select**Properties** . On Windows 11, you will have to select**Show more options** first before you can see the**Properties** option.
3. Click on the**Advanced system settings** link to open the System Properties window. On Windows 11, you will find the link on the right panel, while, on Windows 10, it will be on the left side menu.  
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
![the About page of the System window in the Settings app on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/system-about-windows-11.jpg)
4. Select the**Advanced** tab, and in the**Performance** section, click the**Settings** button.
5. In the Performance Options window, select the**Advanced** tab and click**Change** .
6. In the Virtual Memory window, uncheck the**Automatically manage paging file size for all drives** checkbox at the top.
7. Click on the radio button for**Custom size** . Immediately, you’ll see that the two text boxes below it (**Initial size** and**Maximum size**) are no longer grayed out.
8. Enter the appropriate page file sizes in megabytes (MB) in both text boxes and then click**Set** .  
![the virtual memory dialog box on windows with the custom page file size set to 4096](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/virtual-memory-custom-size.jpg)
9. Click**OK** to close the Virtual Memory window and apply the changes.
10. Restart your Windows computer for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
## Pagefile.sys, Demystified

 Pagefile.sys is an extremely important file when it comes to keeping your Windows computer running smoothly. It helps give your PC's RAM more breathing room when physical memory can no longer hold more data. You can delete it, but only do so when you know your computer's RAM has enough capacity to stand on its own. If not, you’re better off just resizing Pagefile.sys so it doesn’t take up too much space.

 If you’re unsure of what to do with Pagefile.sys, just leave it to Windows to handle the file and look for other ways to free up space on your storage drive.

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
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-earn-big-on-snapchat-the-ultimate-guide-to-money-making-tips/"><u>[New] In 2024, Earn Big on Snapchat  The Ultimate Guide to Money-Making Tips</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-methods-to-clear-up-obs-fullscreen-troubles/"><u>[New] Methods to Clear Up OBS Fullscreen Troubles</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-elite-internet-recorder-choices-7-to-try-for-2024/"><u>[Updated] Elite Internet Recorder Choices - 7 to Try for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-universal-strategies-for-screen-capturing-on-diverse-devices/"><u>[Updated] In 2024, Universal Strategies for Screen Capturing on Diverse Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/11-common-windows-11-problems-with-easy-solutions/"><u>11 Common Windows 11 Problems With Easy Solutions</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-comprehensively-capturing-your-messenger-conversations/"><u>2024 Approved  Comprehensively Capturing Your Messenger Conversations</u></a></li>
<li><a href="https://windows11.techidaily.com/8-ways-to-fix-the-windows-pin-not-working-in-windows-10-and-11/"><u>8 Ways to Fix the Windows PIN Not Working in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/a-complete-look-at-windows-11s-audio-recorder-keys/"><u>A Complete Look at Windows 11'S Audio Recorder Keys</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/a-comprehensive-guide-to-apple-iphone-xr-blacklist-removal-tips-and-tools-by-drfone-ios/"><u>A Comprehensive Guide to Apple iPhone XR Blacklist Removal Tips and Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-how-to-deal-with-non-terminatable-errors/"><u>Bypassing Windows: How to Deal with Non-Terminatable Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/cease-uncontrolled-system-shutdowns-on-windows-11/"><u>Cease Uncontrolled System Shutdowns on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/ceasing-autonomous-openings-in-microsoft-shop-app/"><u>Ceasing Autonomous Openings in Microsoft Shop App</u></a></li>
<li><a href="https://windows11.techidaily.com/changing-terminals-default-backdrop/"><u>Changing Terminal's Default Backdrop</u></a></li>
<li><a href="https://windows11.techidaily.com/decluttering-windows-11-icon-pile-up/"><u>Decluttering Windows 11 Icon Pile-Up</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-hardware-utilization-in-windows-11/"><u>Decoding Hardware Utilization in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-the-essence-of-windows-11s-registry-structure/"><u>Dissecting the Essence of Windows 11'S Registry Structure</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-tips-for-reactivating-file-explorer-ui/"><u>Easy Tips for Reactivating File Explorer UI</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-windows-volume-preserve-data/"><u>Enhance Windows Volume, Preserve Data</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-flaky-windows-apps-a-step-by-step-guide/"><u>Fixing Flaky Windows Apps: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-white-or-gray-microsoft-store-display/"><u>Fixing White or Gray Microsoft Store Display</u></a></li>
<li><a href="https://android-unlock.techidaily.com/forgot-pattern-lock-heres-how-you-can-unlock-oppo-find-n3-pattern-lock-screen-by-drfone-android/"><u>Forgot Pattern Lock? Heres How You Can Unlock Oppo Find N3 Pattern Lock Screen</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-facebook-dating-for-your-samsung-galaxy-m14-5g-drfone-by-drfone-virtual-android/"><u>How to Change Location On Facebook Dating for your Samsung Galaxy M14 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-customize-sound-levels-with-dedicated-win11-keys/"><u>How to Customize Sound Levels with Dedicated Win11 Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-develop-windows-custom-text-to-voice-software-using-whisper-and-ahk/"><u>How to Develop Window's Custom Text-To-Voice Software Using Whisper & AHK</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-nonfunctional-wsreset-service-in-windows/"><u>How to Reactivate Nonfunctional WSReset Service in Windows</u></a></li>
<li><a href="https://techidaily.com/how-to-update-or-downgrade-apple-iphone-x-without-losing-anything-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade Apple iPhone X Without Losing Anything? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/improving-memory-footprint-in-ms-teams/"><u>Improving Memory Footprint in MS Teams</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-4-effective-methods-fake-gps-location-on-apple-iphone-14-plusipad-drfone-by-drfone-virtual-ios/"><u>In 2024, 4 Effective Methods Fake GPS Location on Apple iPhone 14 Plus/iPad | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-capturing-the-webs-essence-top-browsers-for-screen-recorders/"><u>In 2024, Capturing the Web’s Essence  Top Browsers for Screen Recorders</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-xs-max-without-passcode-or-face-id-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone XS Max without Passcode or Face ID</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-oppo-a78-phone-frp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Oppo A78 Phone FRP Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/integrating-nas-into-mobile-device-setups/"><u>Integrating NAS Into Mobile Device Setups</u></a></li>
<li><a href="https://windows11.techidaily.com/1719382274392-is-your-hardware-upgraded-for-win11-find-out/"><u>Is Your Hardware Upgraded For Win11? Find Out</u></a></li>
<li><a href="https://windows11.techidaily.com/method-for-handling-device-access-issues-with-audacity-win/"><u>Method for Handling Device Access Issues with Audacity (Win)</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-restrictions-to-write-files-in-windows-11-os/"><u>Overcoming Restrictions to Write Files in Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaim-default-speaker-levels-post-windows-update/"><u>Reclaim Default Speaker Levels Post-Windows Update</u></a></li>
<li><a href="https://windows11.techidaily.com/safeguard-files-with-windows-controlled-access-feature/"><u>Safeguard Files with Window's Controlled Access Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-setting-up-a-trio-of-widget-boards-in-windows-11/"><u>Step by Step: Setting Up a Trio of Widget Boards in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-rectify-faulty-cpu-usage-in-windows-management-console/"><u>Steps to Rectify Faulty CPU Usage in Windows Management Console</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-rectify-preview-failures-in-outlook-for-pcs/"><u>Steps to Rectify Preview Failures in Outlook for PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-gaming-experience-installing-windows-on-steam-deck/"><u>Streamline Your Gaming Experience: Installing Windows on Steam Deck</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-flush-for-your-win11-dns-cache/"><u>The Ultimate Flush for Your Win11 DNS Cache</u></a></li>
<li><a href="https://windows11.techidaily.com/tricks-to-extend-the-wait-window-in-windows-10-before-restarting/"><u>Tricks to Extend the Wait Window in Windows 10 Before Restarting</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-disabled-programs-in-windows/"><u>Unblocking Disabled Programs in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/uncovering-the-oddities-in-windows-11-visual-language/"><u>Uncovering the Oddities in Windows 11 Visual Language</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unraveling-filmora-editing-inquiries-for-2024/"><u>Unraveling Filmora Editing Inquiries for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-hidden-potential-essential-tips-on-windows-narrator-commands/"><u>Unveiling the Hidden Potential: Essential Tips on Windows Narrator Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/wireless-mouse-woes-on-windows-heres-what-to-do/"><u>Wireless Mouse Woes on Windows? Here's What to Do</u></a></li>
</ul></div>