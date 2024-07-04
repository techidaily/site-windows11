---
title: Accessing Stealthed Elements in Windows 11 UI
date: 2024-07-03T11:11:53.039Z
updated: 2024-07-04T11:11:53.039Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Accessing Stealthed Elements in Windows 11 UI
excerpt: This Article Describes Accessing Stealthed Elements in Windows 11 UI
keywords: Windows UI Stealth Access,Stealth Elements Window,Win11 UI Stealthy Extractions,Elusive Elements UWP,Hidden UI Windows Find,Stealthed UI Element Locate,Silent Elements In Windows UI
thumbnail: https://thmb.techidaily.com/0177669a9f7e47198243a9fecb2a2f8d7897c9576df374da55c9c20dfb4332d6.jpg
---

## Accessing Stealthed Elements in Windows 11 UI

 The system tray, which is part of the Taskbar and shows the apps you use frequently, among other things, can become overcrowded.

 If that happens, you can remove a couple of app icons, as well as the hidden icons menu, to make it less cluttered. And if you can’t find the app icons you need or the hidden icons menu is missing, you can add those too.

## How to Show or Hide System Tray Icons on Windows 11

 To show more icons in the system tray, you need to access the Taskbar's settings by pressing **Win + I**, selecting **Personalization** on the left side menu, and then clicking **Taskbar** in the right panel.

![Go to Taskbar Settings in the Personalization Tab of Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/6-go-to-taskbar-settings-in-the-personalization-tab-of-windows-settings-app.jpg)

 In Taskbar settings, scroll down and expand the **Other system tray icons** section. Find the icon you want to show (its toggle will be set to **Off** if it isn’t in the system tray) and click on the toggle on its right to set it to the **On** position.

![you can turn system tray icons on and off in the Taskbar settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-tray-icons-windows-11.jpg)

 If you want to remove the system tray icon, simply set the toggle to **Off**.

 Another way to remove icons from the system tray is to place them in the hidden icons menu. This is the menu that appears when you click the **up caret** icon in the system tray. When the menu is opened, the icon becomes a **down caret**.

![the hidden icons menu on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hidden-icons-menu-windows-11.jpg)

 To remove an icon from the system tray and place it into the hidden icons menu, click and drag it into the **up caret**. And when you expand the hidden icons menu, you will see that the icon is inside.

 When you remove system tray icons from the settings, they will not appear in the hidden icons menu but will be removed completely.

 To add the icon back in the system tray, click and drag it from the hidden icons menu and then place it in the system tray.

## How to Show or Hide the Hidden Icon Menu

 As mentioned earlier, the hidden icon menu is what appears when you click the **up caret** in the system tray. You can also hide and show this menu as you please.

### Using the Settings App

 If you can't see the hidden icon menu, you can show it from the Taskbar settings as well. To get there, right-click an empty part of the Taskbar and select **Taskbar settings**.

![opening Taskbar settings by right clicking an empty part of the Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/opening-taskbar-settings.jpg)

 Scroll down until you reach the **Other system tray icons** section and expand it. To reveal the hidden icon menu, set the toggle next to the **Hidden menu icon** option to **On**. To hide it, set the toggle to **Off**.

### Using the Registry Editor

 If you’re not familiar with the Registry Editor, we recommend that you read our guide on [what the Windows Registry is](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) before continuing. It’s crucial that you know what you’re working with before moving forward. Also, be sure to [make a backup of the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) while you're at it.

 With that out of the way, you can open the Registry Editor by pressing **Win + R**, entering **regedit** in the text box, and then clicking on **OK**. In the UAC prompt, click **Yes** to launch the tool.

 For more methods to launch the Registry Editor, please check out our guide on [ways to open the Registry Editor on Windows 11](https://www.makeuseof.com/windows-11-open-registry-editor/).

 Afterward, copy and paste the following path into the address bar of the Registry Editor and hit the **Enter** key:

HKEY_CURRENT_USER\Software\Classes\Local Settings\Software\Microsoft\Windows\CurrentVersion\TrayNotify

 Next, double-click the **SystemTrayChevronVisibility** value in the right panel.

![the SystemTrayChevronVisibility value in the Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/systemtraychevronvisibility-value-regedit-windows.jpg)

 To show the hidden icon menu, set the **Value data** text box to **1** and click **OK**.

![setting the SystemTrayChevronVisibility value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/systemtraychevronvisibility-value-data.jpg)

 And to hide the hidden icon menu set the **Value data** text box to **0** and click **OK**.

## Control the Icons that Appear in the System Tray on Windows 11

 Whether you want to add icons or remove them from the system tray, the process is simple. Just go to the Taskbar settings and turn them on or off as needed. You can also hide or show the hidden icon menu in the process.

 And if you want to show or hide the clock and date in the system tray, you can do that too.

 If that happens, you can remove a couple of app icons, as well as the hidden icons menu, to make it less cluttered. And if you can’t find the app icons you need or the hidden icons menu is missing, you can add those too.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/quick-fix-bypassing-the-components-not-found-issue-on-w10w11/"><u>Quick Fix: Bypassing the Components Not Found Issue on W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-system-crashes-sifting-through-win-files/"><u>Deciphering System Crashes: Sifting Through Win Files</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-ftdibussys-understanding-its-role-in-windows-memory-controls/"><u>Decoding ftdibus.sys: Understanding Its Role in Windows Memory Controls</u></a></li>
<li><a href="https://windows11.techidaily.com/lock-it-down-steps-to-activate-windows-controlled-access/"><u>Lock It Down: Steps to Activate Window’s Controlled Access</u></a></li>
<li><a href="https://windows11.techidaily.com/mitigating-code-xc0000142-on-windows-xp-10/"><u>Mitigating Code XC0000142 on Windows XP, 10</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-failed-logon-wait-duration-settings-in-windows/"><u>Altering Failed Logon Wait Duration Settings in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/9-steps-to-resolve-windows-hello-fingerprint-lockout/"><u>9 Steps to Resolve Windows Hello Fingerprint Lockout</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-repeated-sign-in-requests-for-team-collaboration-software/"><u>Overcoming Repeated Sign-In Requests for Team Collaboration Software</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-the-art-of-crafting-content-for-snapchat-professionals/"><u>In 2024, The Art of Crafting Content for Snapchat Professionals</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/boosting-your-drone-experience-with-these-11-items/"><u>Boosting Your Drone Experience with These 11 Items</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-perfecting-your-youtube-video-blueprint/"><u>[Updated] Perfecting Your YouTube Video Blueprint</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-screen-record-wizard-for-win11-enthusiasts/"><u>[Updated] In 2024, Screen Record Wizard for Win11 Enthusiasts</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-stay-concentrated-how-to-tame-the-chatter-of-google-video-calls/"><u>[New] In 2024, Stay Concentrated  How to Tame the Chatter of Google Video Calls</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-video-magic-how-to-capture-stunning-freeze-frames-in-minutes/"><u>New Video Magic How to Capture Stunning Freeze Frames in Minutes</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-geo-blocking-and-how-to-bypass-it-on-honor-x9b-drfone-by-drfone-virtual-android/"><u>What is Geo-Blocking and How to Bypass it On Honor X9b? | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-unlocking-visual-potential-the-9-best-mobile-accessories-for-vloggers/"><u>In 2024, Unlocking Visual Potential  The 9 Best Mobile Accessories for Vloggers</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-rhythm-and-resolution-edit-and-merge-songs-into-windows-11-vids/"><u>2024 Approved  Rhythm & Resolution  Edit and Merge Songs Into Windows 11 Vids</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>