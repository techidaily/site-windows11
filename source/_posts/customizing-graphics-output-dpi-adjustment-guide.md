---
title: "Customizing Graphics Output: DPI Adjustment Guide"
date: 2025-01-12T09:04:51.102Z
updated: 2025-01-15T17:47:33.063Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Customizing Graphics Output: DPI Adjustment Guide"
excerpt: "This Article Describes Customizing Graphics Output: DPI Adjustment Guide"
keywords: Graphic DPI Tutorial,DPI Customization Steps,Increase Image Quality,High Precision Graphics,Adjusting Screen DPI,Optimize Visual Output,Fine-Tune Graphics Display
thumbnail: https://thmb.techidaily.com/545eb30532b146292d910492a3de0882f942d02de7b5ef10d79d0e3f377f7561.jpg
---

## Customizing Graphics Output: DPI Adjustment Guide

 If you're looking to customize your computer experience, or just make things easier on the eyes, then changing the display DPI scaling on Windows is a great way to do that. In this helpful article, we'll provide you with an easy step-by-step guide for both registry tweaks and Windows settings so that customizing your computer can be done quickly and easily.

 Whether it's due to vision problems or if you simply want more control over how things look onscreen, these solutions are sure to help.

## What Is DPI Scaling on Windows?

 DPI stands for "dots per inch" and it refers to the number of individual dots that can be packed into an inch of space on your screen. The higher the number, the sharper and clearer the display. But here's the thing, sometimes you might want your text and images to be bigger, while at other times, you might want them smaller. That's where DPI scaling comes in; it's your very own personal adjustment tool.

## How to Change Display DPI Scaling via Windows Settings

 The Settings app is the simplest and easiest way to change display scaling in Windows 11\. Here's how to do it.

1. Press**Win + I** on your keyboard to open the Settings menu.
2. From the left pane of the window, click the**System** tab.
3. Click**Display** on the right side.
4. Scroll down to the**Scale and layout** section.
5. Next to the**Scale** option, click the dropdown menu and change the scaling.  
![Change DPI Scale in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/change-dpi-scale-in-settings.jpg)
6. Select the one that best fits your needs.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vEYkX2NJgZw?si=IaHqlqJcYipwUOht" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After you've made your changes, close the window and restart your computer, so the changes take effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change Display DPI Scaling Using the Registry Editor

 If the Settings app isn't working, or you don't have access to it, you can change the scaling through the Registry Editor. But keep in mind that it can be a bit tricky, and you should [back up your registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making any changes.

 To change Display DPI Scaling using Registry Editor, follow these steps:

1. Press**Win + R** on your keyboard to [open the Run command](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**regedit** in the dialog box and hit Enter.
3. If UAC prompts on your screen, click**Yes** to continue.
4. Once you're in the Registry Editor window, navigate to the following path:  
HKEY_CURRENT_USER\Control Panel\Desktop
5. In the right pane, right-click on**LogPixels** and select**Modify** from the context menu.  
 If you don't see the LogPixels DWORD key, you need to manually create it. For this, right-click on the empty space in the right pane and select**New > DWORD (32-bit) Value** . Upon creating the DWORD key, give it the name**LogPixels** and save it. Now click twice on the key you just created, and a pop-up will appear.

1. Choose one of the following Value data fields and set the base to**Decimal** .  
![Change Display DPI Scaling in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-display-dpi-scaling-in-windows.jpg)  
| Value data | DPI scale                  |  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qv4Qm7kpeMs?si=9fv5SOS5a2DvixTK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

| ---------- | -------------------------- |  
| 96         | Smaller 100% (Recommended) |  
| 120        | Medium 125%                |  
| 144        | Larger 150%                |  
| 192        | Extra Large 200%           |  
| 240        | Custom 250%                |  
| 288        | Custom 300%                |  
| 384        | Custom 400%                |  
| 480        | Custom 500%                |
2. When you're done making these changes, click**OK** to save them.
3. Next, double-click**Win8DpiScaling** in the right pane. If you don't see the Win8DpiScaling DWORD key there, you must create it manually in the same way as you created LogPixels.  
![Change Display DPI Scaling Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-display-dpi-scaling-using-registry.jpg)
4. In the pop-up menu, set the Value data to**0** if you set Logpixels to 96, or**1** if you used any other value.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Select**Hexadecimal** as the base and click**OK** .

 After performing the above steps, restart your computer to take effect the changes. If you ever need to restore the default settings, just open Registry Editor and go to the same location. Then double-click on Win8DpiScaling and change the Value data to 0.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RCYs8keh-Vs?si=uDC28-9yh-k6HLj4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Scale the Display DPI on Windows

 If you're in search of ways to give your screen a sharper and crisper look, change the DPI scaling! You can customize different elements displayed on your device like text size, icons, and more so that it's easier for you to read and navigate.

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
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-snap-the-truth-your-manual-to-authenticity-on-instagram/"><u>[New] In 2024, Snap the Truth Your Manual to Authenticity on Instagram</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-decoding-youtube-income-how-much-does-each-1000-viewer-earn/"><u>[Updated] In 2024, Decoding YouTube Income How Much Does Each 1,000 Viewer Earn?</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-the-ultimate-rankings-of-youtubes-mp3-downloader-apps/"><u>[Updated] The Ultimate Rankings of YouTube's MP3 Downloader Apps</u></a></li>
<li><a href="https://howto.techidaily.com/8-workable-fixes-to-the-sim-not-provisioned-mm2-error-on-tecno-spark-20c-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Workable Fixes to the SIM not provisioned MM#2 Error on Tecno Spark 20C | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-finding-installed-programs-locations/"><u>Essential Tips: Finding Installed Programs' Locations</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-videos-from-your-v30-lite-5g-by-fonelab-android-recover-video/"><u>How to recover old videos from your V30 Lite 5G</u></a></li>
<li><a href="https://fox-blue.techidaily.com/in-2024-pioneering-websites-for-modern-letterforms/"><u>In 2024, Pioneering Websites for Modern Letterforms</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-space-in-windows-without-data-loss/"><u>Maximizing Space in Windows Without Data Loss</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-restoring-itunes-functionality-in-windows/"><u>Quick Fix: Restoring iTunes Functionality in Windows</u></a></li>
<li><a href="https://win-advanced.techidaily.com/superior-substitutes-for-windows-file-recovery-tools-your-ultimate-guide-to-data-rescue-solutions/"><u>Superior Substitutes for Windows File Recovery Tools: Your Ultimate Guide to Data Rescue Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-pinpointing-5-disturbing-design-traits/"><u>Windows 11: Pinpointing 5 Disturbing Design Traits</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-whisperer-learning-to-activate-the-hidden-character-tracker/"><u>Windows Whisperer: Learning to Activate the Hidden Character Tracker</u></a></li>
</ul></div>

