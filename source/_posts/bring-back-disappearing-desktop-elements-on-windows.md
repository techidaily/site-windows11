---
title: Bring Back Disappearing Desktop Elements on Windows
date: 2025-01-18T18:01:48.523Z
updated: 2025-01-22T18:30:44.715Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bring Back Disappearing Desktop Elements on Windows
excerpt: This Article Describes Bring Back Disappearing Desktop Elements on Windows
keywords: Restore Windows Panels,Add Back Desktops,Enhance Windows UI,Reintroduce Taskbar Features,Fix Window Interface,Revive PC Display Elements,Improve System Widgets
thumbnail: https://thmb.techidaily.com/ed24203618acc19422dc1e656e53cdd94b542178679b34754816329310d98db4.jpg
---

## Bring Back Disappearing Desktop Elements on Windows

 Desktop icons on Windows 11 give you quick access to your favorite apps, files, folders, and more. But what if these desktop icons vanish without a trace? How do you get the icons back?

 If you're facing this baffling problem, this guide will help you restore the missing desktop icons in Windows 11.

## 1\. Enable Show Desktop Icons

 On Windows 11, you can show or hide desktop icons with a couple of clicks. So, if you’ve accidentally hidden your desktop icons, getting them back is fairly easy.

 Right-click anywhere on an empty spot on your desktop and select**View > Show desktop icons** . Once you do that, all your hidden desktop icons should reappear.

![Show Desktop Icons on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Show-Desktop-Icons-on-Windows-11.jpg)

## 2\. Check Desktop Icon Settings

 If you're only missing a few desktop icons, such as This PC, Recycle Bin, Control Panel, and others, you may have disabled them in the "Desktop Icon Settings" window. In that case, you can use the following steps to re-enable those desktop icons.

1. Open the**Start menu** and click the**gear icon** to launch the Settings app.
2. Select**Personalization** from the left sidebar.
3. Select**Themes** .
4. Under**Related settings** , click on**Desktop icon settings** .
5. Under the**Desktop icons** section, use the checkboxes to enable the icons you want on your desktop.
6. Click**Apply** followed by**OK** to save the changes.  
![Desktop Icon Settings Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Desktop-Icon-Settings-Window.jpg)

 Once you complete the above steps, your icons should appear on the desktop.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hHPljBHrvkA?si=HwdfDM9rlbABSIrx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Restart Windows Explorer

 The Windows Explorer process handles the Graphical User Interface (GUI) for a number of utilities, including the desktop. If this service encounters any issues, your desktop and taskbar icons may disappear. If this is the case, you can restart the Windows Explorer process to fix the problem.

1. Right-click on the Start icon or press**Win + X** to open the Power User menu.
2. Select**Task Manager** from the list.
3. In the**Processes** tab, locate**Windows Explorer** . Right-click on it and select**Restart** .  
![Restart Windows Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Restart-Windows-Explorer.jpg)

 Your taskbar will disappear for a brief moment and then reappear. Following this, your desktop icons should be visible.

## 4\. Rebuild Icon Cache

 Another reason why desktop icons on Windows may appear broken or go missing is if the existing icon cache data is corrupt. In that case, you can try clearing the corrupted icon cache data. This will force Windows to rebuild the icon cache from scratch and resolve your problem.

To rebuild icon cache on Windows 11:

1. Press**Win + S** to open the search menu.
2. Type**command prompt** in the box and select**Run as administrator** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Paste the following command in the console and press**Enter** to navigate to the directory where Windows stores the icon cache.  
`cd /d %userprofile%\AppData\Local\Microsoft\Windows\Explorer`
5. Run the following command to terminate the Explorer process:  
`taskkill /f /im explorer.exe`
6. Paste this command and press**Enter** to delete icon cache files:  
`del iconcache*`  
![Rebuild Icon Cache Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Rebuild-Icon-Cache-Windows.jpg)
7. Finally, type in the following text and hit**Enter** to restart Explorer:  
`Explorer.exe`

 Once you complete the above steps, restart your PC and see if the desktop icons appear.

## 5\. Update Your PC’s Graphics Driver

 An outdated graphics driver on Windows can also lead to such anomalies. You can try updating the faulty driver using Device Manager to see if that helps. Here's how to do it.

1. Press**Win + S** to open the search menu.
2. Type**device manager** in the search box and select the first result that appears.
3. Expand**Display adapters** .
4. Right-click on your graphics driver and select**Update driver** .
5. Select**Search automatically for drivers** to let Windows find and install the best drivers.  
![Update Graphics Driver on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Update-Graphics-Driver-on-Windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RvR5PNhspKE?si=uJcMYK9v-_Xq7fAg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the issue persists even after updating the driver, your graphics driver may be corrupt. In that case, you'll need to reinstall the graphics driver on your PC. Refer to our guide on [how to fix corrupt drivers on Windows](https://www.makeuseof.com/how-to-fix-corrupt-drivers-on-windows-10/) for more instructions on how to fix this.

## 6\. Check the Group Policy Settings

 The Group Policy Editor lets you make various system-wide changes on your Windows computer. If desktop icons are disabled from the Group Policy Editor, you won’t be able to add or remove desktop icons no matter what you do. To fix this, you must disable this “Hide and disable all items on the desktop” from the Group Policy Editor.

 Note that you can only access the Group Policy Editor on Windows 11 Professional, Enterprise, and Education editions. If you’re running Windows 11 Home, check our guide on [how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Click the magnifying icon on the taskbar to open the search menu.
2. Type**gpedit.msc** in the box and press**Enter** . This will open the Local Group Policy Editor.
3. Use the left pane to navigate to **User Configuration > Administrative Templates > Desktop** .
4. Double-click the**Hide and disable all items on the desktop** policy on your right.
5. Select**Not configured** or**Disabled** .
6. Click**Apply** followed by**OK** .  
![Enable Desktop Icons on Windows 11 via Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Enable-Deskop-Icons-on-Windows-11-via-Group-Policy-Editor-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gSKkJrJ57EA?si=WDOmInPE9EgQa_tB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eu4vwlZcMvM?si=4vEczfVU4BUUFP-t" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 7\. Perform a System Restore

 There's a chance that a recent system change is to blame for the missing desktop icons in Windows 11\. If you can't figure out what it is, you can use System Restore to restore Windows to a previous state.

Follow these steps to perform a system restore on Windows:

1. Press**Win + R** to open the Run dialog box.
2. Type**sysdm.cpl** in the box and press**Enter** .
3. Under the**System Protection** tab, click on**System Restore** .
4. Click**Next** .
5. Select a restore point before the issue first appeared and hit**Next** .
6. Click on**Finish** .  
![System Restore Dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/System-Restore-Dialog.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/w7c5EHp-GDw?si=UTw7lZR0wTmRjp8W" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Wait for Windows to reboot and revert to the specified restore point. Following that, your desktop icons should appear.

## 8\. Manually Restore the Desktop Shortcut Icons

 If your desktop icons are still missing at this point, you can try restoring them manually.

 To add an icon to the desktop in Windows 11, open the**Start menu** and click on**All apps** . Scroll down to the app you want to add to the desktop. Finally, drag the app shortcut to your desktop.

![Create Desktop Shortcut From Start Menu in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Create-Desktop-Shortcut-From-Start-Menu-in-Windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/On0Jw2oMZf0?si=Pm-FJoEt8XWmtMbr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Alternatively, you can create a shortcut on your desktop by using the Create Shortcut wizard. To do so, right-click anywhere on the desktop and select**New > Shortcut** . Then, click the**Browse** button to locate the file, folder, or app you want to add to your desktop. Then, click**Next** followed by**Finish** .

 We covered this topic in more detail in our guide to [how to add icons to the desktop on Windows](https://www.makeuseof.com/how-to-add-icon-to-desktop-windows/) .

## Restore the Missing Desktop Icons on Windows 11

 Hopefully, the above-mentioned solutions have helped you restore the missing desktop icons on Windows 11 and things are back to normal. However, if none of the above solutions work, you may have to reset your Windows 11 PC as a last resort.

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
<li><a href="https://article-files.techidaily.com/new-a-deeper-dive-into-the-game-five-easy-zooming-methods/"><u>[New] A Deeper Dive Into the Game Five Easy Zooming Methods</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-essential-free-apps-for-youtube-to-wav-transformation/"><u>[Updated] 2024 Approved Essential Free Apps for YouTube to WAV Transformation</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-mastering-digital-media-xmlttml-conversion-guide-for-srt/"><u>[Updated] In 2024, Mastering Digital Media XML/TTML Conversion Guide for SRT</u></a></li>
<li><a href="https://windows11.techidaily.com/dynamic-tray-display-live-system-usage-statistics-on-desktop/"><u>Dynamic Tray Display: Live System Usage Statistics on Desktop</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/earn-extra-bucks-maximizing-youtubes-mobile-revenue-opportunities-for-2024/"><u>Earn Extra Bucks Maximizing YouTube's Mobile Revenue Opportunities for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-win-based-open-ai-discussions/"><u>Effortless WIN-Based Open AI Discussions</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-vm-game-six-key-tips-for-windows-optimization/"><u>Elevate Your VM Game: Six Key Tips for Windows Optimization</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-the-windows-error-code-0x8007251d-for-activation/"><u>Eliminating the Windows Error Code 0X8007251D for Activation</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-live-performance-on-task-monitor-win-11/"><u>Enhance Live Performance on Task Monitor Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-the-real-time-update-speed-of-task-manager/"><u>Enhance the Real-Time Update Speed of Task Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-user-experience-add-portable-software-to-windows/"><u>Enhance User Experience: Add Portable Software to Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-power-indicators-set-up-fully-charged-notifications-on-windows-11/"><u>Enhancing Power Indicators: Set up Fully Charged Notifications on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-productivity-grouped-software-installs-on-windows-11-using-winstall/"><u>Enhancing Productivity: Grouped Software Installs on Windows 11 Using Winstall</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/free-mindset-tunes-no-copyrights-for-2024/"><u>Free Mindset Tunes - No Copyrights for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/how-to-get-your-brother-printer-back-up-and-running-on-windows/"><u>How to Get Your Brother Printer Back Up & Running on Windows</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-google-pixel-7a-phone-with-broken-screen-by-drfone-android/"><u>In 2024, How to Unlock Google Pixel 7a Phone with Broken Screen</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-securing-an-annotate-free-video-experience-tips-for-new-avi-users/"><u>In 2024, Securing an Annotate-Free Video Experience Tips for New AVI Users</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unleash-the-power-of-your-lost-iphone-x/"><u>In 2024, Unleash the Power of Your Lost iPhone X</u></a></li>
<li><a href="https://video-capture.techidaily.com/x-tape-maker-desktop-compatible-for-2024/"><u>X-Tape Maker Desktop Compatible for 2024</u></a></li>
</ul></div>

