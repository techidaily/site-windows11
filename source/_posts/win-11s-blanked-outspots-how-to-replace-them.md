---
title: "Win 11'S Blanked Outspots: How to Replace Them"
date: 2024-12-24T18:59:07.474Z
updated: 2024-12-25T19:25:22.369Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Win 11'S Blanked Outspots: How to Replace Them"
excerpt: "This Article Describes Win 11'S Blanked Outspots: How to Replace Them"
keywords: Win 11 Spot Replacement,Windows 11 Upgrade Guide,Fix Blackout Areas in Win 11,Replacing Blanked Outspots in Win 11,Troubleshoot Windows 11 Display,Windows 11 Display Fix,Spotlight Issues
thumbnail: https://thmb.techidaily.com/72ad6224a96d1332d870ccac31eeed89a25da9895e91d61d746d246092f66e50.png
---

## Win 11'S Blanked Outspots: How to Replace Them

 Desktop icons on Windows 11 give you quick access to your favorite apps, files, folders, and more. But what if these desktop icons vanish without a trace? How do you get the icons back?

 If you're facing this baffling problem, this guide will help you restore the missing desktop icons in Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zmXpl6irBYk?si=BXjGpQr6PXFcqhCI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the above steps, your icons should appear on the desktop.

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0nGlyEL5K6Y?si=3KZhTTBvKcPmyS68" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/T-ssCD10v2M?si=WVWGNayUiCAkMZzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the issue persists even after updating the driver, your graphics driver may be corrupt. In that case, you'll need to reinstall the graphics driver on your PC. Refer to our guide on[how to fix corrupt drivers on Windows](https://www.makeuseof.com/how-to-fix-corrupt-drivers-on-windows-10/) for more instructions on how to fix this.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3hS27nZVi9Y?si=_Zqj_l4a4XkPqT2S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Check the Group Policy Settings

 The Group Policy Editor lets you make various system-wide changes on your Windows computer. If desktop icons are disabled from the Group Policy Editor, you won’t be able to add or remove desktop icons no matter what you do. To fix this, you must disable this “Hide and disable all items on the desktop” from the Group Policy Editor.

 Note that you can only access the Group Policy Editor on Windows 11 Professional, Enterprise, and Education editions. If you’re running Windows 11 Home, check our guide on[how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Click the magnifying icon on the taskbar to open the search menu.
2. Type**gpedit.msc** in the box and press**Enter** . This will open the Local Group Policy Editor.
3. Use the left pane to navigate to **User Configuration > Administrative Templates > Desktop** .
4. Double-click the**Hide and disable all items on the desktop** policy on your right.
5. Select**Not configured** or**Disabled** .
6. Click**Apply** followed by**OK** .  
![Enable Desktop Icons on Windows 11 via Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Enable-Deskop-Icons-on-Windows-11-via-Group-Policy-Editor-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yr0yS_Ywrjs?si=QxzYiX1KmUaExmlo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 Wait for Windows to reboot and revert to the specified restore point. Following that, your desktop icons should appear.

## 8\. Manually Restore the Desktop Shortcut Icons

 If your desktop icons are still missing at this point, you can try restoring them manually.

 To add an icon to the desktop in Windows 11, open the**Start menu** and click on**All apps** . Scroll down to the app you want to add to the desktop. Finally, drag the app shortcut to your desktop.

![Create Desktop Shortcut From Start Menu in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Create-Desktop-Shortcut-From-Start-Menu-in-Windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/f3PFn06LijE?si=zHrmlTOzrKxXe-k4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Alternatively, you can create a shortcut on your desktop by using the Create Shortcut wizard. To do so, right-click anywhere on the desktop and select**New > Shortcut** . Then, click the**Browse** button to locate the file, folder, or app you want to add to your desktop. Then, click**Next** followed by**Finish** .

 We covered this topic in more detail in our guide to[how to add icons to the desktop on Windows](https://www.makeuseof.com/how-to-add-icon-to-desktop-windows/) .

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
<li><a href="https://on-screen-recording.techidaily.com/new-definitive-top-ten-nintendo-switch-combat-apps-max-156/"><u>[New] Definitive Top Ten Nintendo Switch Combat Apps (Max 156)</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-perfecting-proximity-views-an-essential-for-roblox-enthusiasts/"><u>[Updated] Perfecting Proximity Views An Essential for Roblox Enthusiasts</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-precision-planning-of-collaborative-slack-plus-filmora-meetings/"><u>[Updated] Precision Planning of Collaborative Slack + Filmora Meetings</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-prime-old-school-techniques-elevating-edits-for-2024/"><u>[Updated] Prime Old-School Techniques Elevating Edits for 2024</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/2024-approved-avoid-posting-mistakes-on-twitter-by-knowing-the-aspect-ratio/"><u>2024 Approved Avoid Posting Mistakes on Twitter by Knowing the Aspect Ratio</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-fixes-for-windows-remote-desktop-problems/"><u>Essential Fixes for Windows Remote Desktop Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-pathways-for-opening-hardware-spaces-on-w10w11/"><u>Essential Pathways for Opening Hardware Spaces on W10/W11</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-expected-video-gb-for-continuous-24-hour-viewing/"><u>In 2024, Expected Video GB for Continuous 24-Hour Viewing</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-how-to-create-endless-video-on-iphone/"><u>In 2024, How-To Create Endless Video on iPhone</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-prevent-data-loss-in-unresponsive-usb-cases-windows/"><u>Methods to Prevent Data Loss in Unresponsive USB Cases (Windows)</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/navigating-the-bargains-what-to-expect-from-amazon-prime-day-2024/"><u>Navigating the Bargains: What to Expect From Amazon Prime Day 2024?</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-your-pcs-clock-view-ideal-screensaver-creation-apps-in-windows-platform/"><u>Personalize Your PC's Clock View: Ideal Screensaver Creation Apps in Windows Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-your-windows-start-windows-media-player-now/"><u>Unleash Your Windows: Start Windows Media Player Now</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-torrent-speed-resetting-stalled-status-on-windows/"><u>Unlocking Torrent Speed: Resetting Stalled Status on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-non-essential-windows-applications-for-elimination/"><u>Unveiling Non-Essential Windows Applications for Elimination</u></a></li>
</ul></div>

