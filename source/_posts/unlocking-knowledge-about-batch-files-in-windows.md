---
title: Unlocking Knowledge About Batch Files in Windows
date: 2024-12-08T18:27:28.903Z
updated: 2024-12-10T17:16:23.913Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlocking Knowledge About Batch Files in Windows
excerpt: This Article Describes Unlocking Knowledge About Batch Files in Windows
keywords: Windows Batch File Guide,Mastering Batch Scripts,Batch Command Basics,Windows Execute Batch,Understanding Batch Files,Learn Batch Syntax,Advanced Batch Commands
thumbnail: https://thmb.techidaily.com/f2cea06ab8ae79e3da9341215d5a2b3791081a5d0d2f702dc7f4ecb1fa023ae2.jpg
---

## Unlocking Knowledge About Batch Files in Windows

 Deleting the hidden "$Windows.\~BT" folder and recovering gigabytes of space on your hard drive is tempting. But what is this cryptically named folder for, and how critical is it to your Windows installation?

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4qA2pGQ5qmw?si=1mAA9WTi2Z5F7n6s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Is the “$Windows.\~BT” Folder, and Should You Delete It?

 Windows creates the "$Windows.\~BT" folder when you upgrade the operating system to a newer build. This folder contains all the essential files for the upgrade process, like temporary installation files and logs from the previous Windows installation.

 Windows automatically removes the "$Windows.\~BT" folder after 10 days. As manually deleting this folder will [remove old Windows installation files](https://www.makeuseof.com/tag/delete-old-windows-update-files/), you won't be able to roll back to the previous Windows build using the **Go back** option in the Recovery menu within that time (for example, to [downgrade from Windows 11 to Windows 10](https://www.makeuseof.com/windows-11-downgrade-to-windows-10/)). Hence, you should only get rid of this folder if you are satisfied with the current Windows build on your PC. You can also safely delete the massive folder if Windows fails to do it automatically after the grace period.

 But you shouldn't just delete this hidden folder like any other folder on the desktop. Instead, you should turn to the Disk Cleanup tool or the Command Prompt.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8dH3yHH9IX8?si=geiW5KbIljSFT9pz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Find and Delete the "$Windows.\~BT" Folder

 As "$Windows.\~BT" is a hidden folder, you need to [configure Windows to show hidden files and folders](https://www.makeuseof.com/windows-11-show-hidden-files-folders/) to find it in File Explorer. Once you do, the **C:\\$Windows.\~BT** directory will become visible.

 You can’t delete the "$Windows.\~BT" folder directly, though. To do so, you need to run the Disk Cleanup tool. Here's how:

1. Press **Win + R** to open the Run dialog box.
2. Type **cleanmgr** in the box and press **Enter**.
3. Use the dropdown menu to select the system drive (usually **C:**) and click **OK**.
4. Click the **Clean up system files** button.
5. Under **Files to delete**, use the checkboxes to select these options: **Previous Windows Installations**, **Windows Update Cleanup**, **Windows upgrade log files**, **Temporary Windows installation files**, and **Temporary files**.
6. Click **OK**.
7. Choose **Delete Files** to confirm.  
![Delete the $Windows.~BT Folder Using the Disk Cleanup Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/delete-the-windows-bt-folder-using-the-disk-cleanup-tool.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XoC2TGp1PLY?si=iH9xs76NhWn4pP-E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the "$Windows.\~BT" folder shows up even after you run the Disk Cleanup tool, you'll need to execute a few commands in Command Prompt. For that, [open Command Prompt with administrative rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) and then run the following commands one by one.

`takeown /F C:\$Windows.~BT\* /R /A
icacls C:\$Windows.~BT\*.* /T /grant administrators:F
rmdir /S /Q C:\$Windows.~BT\`

 Once you run the above commands, the "$Windows.\~BT" folder will be deleted for good.

 Now that you understand the purpose of the "$Windows.\~BT" folder, you can decide how to handle it. Beyond the "$Windows.\~BT" folder, you may also come across folders like "Windows.old," "$WinREAgent," "$SysReset," and others which can also be deleted safely using the Disk Cleanup tool.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-delve-into-discussions-of-dedicated-viewers/"><u>[New] In 2024, Delve Into Discussions of Dedicated Viewers</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-battle-of-the-capture-tools-obs-studio-against-bandicam-for-2024/"><u>[Updated] Battle of the Capture Tools OBS Studio Against Bandicam for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-freedom-from-popups-discover-the-top-7-android-adblock-apps-for-2024/"><u>[Updated] Freedom From Popups? Discover the Top 7 Android AdBlock Apps for 2024</u></a></li>
<li><a href="https://win-able.techidaily.com/how-to-stop-your-disco-elysium-adventure-from-crashing-on-pc-a-comprehensive-guide/"><u>How to Stop Your Disco Elysium Adventure From Crashing on PC: A Comprehensive Guide</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-essential-online-marketing-strategies-for-newcomers/"><u>In 2024, Essential Online Marketing Strategies for Newcomers</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-apple-iphone-se-2022-drfone-by-drfone-virtual-ios/"><u>In 2024, How PGSharp Save You from Ban While Spoofing Pokemon Go On Apple iPhone SE (2022)? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-use-pokemon-emerald-master-ball-cheat-on-motorola-edge-40-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Pokémon Emerald Master Ball Cheat On Motorola Edge 40 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/lowest-on-bf-day-save-612-lifetime-windows-10/"><u>Lowest on BF Day: Save $6.12, Lifetime Windows 10</u></a></li>
<li><a href="https://win-exceptional.techidaily.com/mastering-motherboard-maintenance-troubleshooting-tips-from-yl-software-experts/"><u>Mastering Motherboard Maintenance: Troubleshooting Tips From YL Software Experts</u></a></li>
<li><a href="https://tech-revival.techidaily.com/online-gratuit-png-to-jpeg-conversion-premium-service-by-movavi/"><u>Online Gratuit PNG-to-JPEG Conversion - Premium Service by Movavi</u></a></li>
<li><a href="https://windows11.techidaily.com/the-winning-edge-a-compilation-of-top-8-editors-for-windows/"><u>The Winning Edge: A Compilation of Top 8 Editors for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-potential-with-updated-amd-drivers-in-windows-11/"><u>Unleashing Potential with Updated AMD Drivers in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unveil-if-your-pc-is-prepared-for-the-upcoming-os/"><u>Unveil If Your PC Is Prepared for the Upcoming OS</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-1110-homes-enabling-efficient-user-handling/"><u>Windows 11/10 Homes: Enabling Efficient User Handling</u></a></li>
</ul></div>

