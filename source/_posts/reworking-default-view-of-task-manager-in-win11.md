---
title: Reworking Default View of Task Manager in Win11
date: 2024-08-15T15:44:53.041Z
updated: 2024-08-16T15:44:53.041Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reworking Default View of Task Manager in Win11
excerpt: This Article Describes Reworking Default View of Task Manager in Win11
keywords: Win11 Task Manager Update,Enhanced Task View Win11,Modern Task Manager Win11,UI Revamp Task Manager Win11,Default View Improvement Win11,Win11 Task Interface Redesign,New TaskManager Win11 Experience
thumbnail: https://thmb.techidaily.com/15a61f0827860e342a65d573fdf8ef935cbe188b573d2796a1411e612ad84808.jpg
---

## Reworking Default View of Task Manager in Win11

 The Task Manager provides a quick overview of your system's current status and shows essential information. Its Start page displays useful details such as currently running background processes, applications, CPU, and memory utilization. If you'd like to customize its appearance, change the Start page. In this article, we’ll look at how to change the Task Manager Start page in Windows 11\.

## 1\. Use Task Manager Settings

 If you want to quickly change the Task Manager Start page, you can use its Settings tab. This option requires no modification to the registry editor or additional scripts to run.

 To change the Task Manager Start page using Task Manager settings, do the following.

1. Press **Win + R** to open the Run dialog box.
2. Type **taskmgr** and press **Enter** to launch Task Manager.
3. Once in Task Manager, click on **Settings** (the gear icon).
4. You'll see a **Default Start Page** drop-down menu at the top. This is where you can select the page to display when Task Manager opens.  
![Use Settings to Change Task Manager Start Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/use-settings-to-change-task-manager-start-page.jpg)

 The options available are the following:

1. Processes
2. Performance
3. App history
4. Startup apps
5. Users
6. Details
7. Services ​​​​

 Once you make a selection, Task Manager will remember the setting and open the page you chose from now on.

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Tweak the Registry Editor

 The Registry Editor is another way to change the default Start page for Task Manager. The procedure is slightly more complex than using Task Manager Settings, but it offers more customization options. Be careful when modifying entries in the Registry Editor, as incorrect changes can cause errors or system instability. To avoid losing data, [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 To change the Task Manager Start page using the Registry Editor, follow these steps.

1. [Open the Registry Editor window](https://www.makeuseof.com/windows-11-open-registry-editor/).
2. If the UAC prompt pops up, click **Yes** to grant administrative rights.
3. In the left pane, navigate to the following key.  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\TaskManager`
4. Double-click **StartUpTab** in the right pane. If there is no such entry, then right-click on the Task Manager key.
5. From the context menu, select **New > DWORD (32-bit) Value**.
6. Now name the value **StartUpTab** and double-click on it.  
![Modify Registry to Change Task Manager Start Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modify-registry-to-change-task-manager-start-page.jpg)
<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Set its **Value data** to one of the following numbers to change the default start page:  
`0 = Processes  

1 = Performance  

2 = App history  

3 = Startup apps  

4 = Users  

5 = Details  

6 = Services`
8. Click **OK** to save the changes and close the Registry Editor window.

 Next time you open Task Manager, it will display a page according to your preferences.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Use a REG File

 If the registry editor isn't your thing, you can use a REG file to modify the Task Manager start page. The process does not require registry tweaking and is straightforward.

 To create a .reg file, [open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and type the following:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\TaskManager]  
  
"StartUpTab"=dword:00000000`

 Here, the last digit reflects the type of Start page.

 For example, if you want to set **Processes** as your default start page, use **0** (**00000000**). Similarly, if you want the **Details** page to display as default, set it to **5** (**00000005**).

 The other options are:

`00000001 - Performance  
  
00000002 - App history  
  
00000003 - Startup apps  
  
00000004 - Users  
  
00000006 - Services`

 Now, click **File** and select **Save as**. In the Save as dialog box, click the Save as type drop-down menu and select **All files**. Name the file with the **.reg** extension. For example, **TaskManagerStartPage.reg**.

![Use a REG File to Change Task Manager Start Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/use-a-reg-file-to-change-task-manager-start-page.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->

 Next, select **Desktop** from the left pane and click **Save**. Once saved, double-click on this newly created REG file. This adds the required details to the Registry Editor and changes the Task Manager start page.

 If you ever want to revert the changes, delete the REG file and restart your computer.

<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Changing the Task Manager Start Page on Windows

 It’s easy to customize Task Manager and change its Start page according to your preference. You can use Task Manager Settings, the Registry Editor, or a REG file to set the desired page. Once you have set the Start page, Task Manager will remember it and open that page when you launch it.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-information.techidaily.com/new-beginning-with-windows-10-sound-recording/"><u>[New] Beginning with Windows 10 Sound Recording</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-mastering-the-social-media-lands-point-10-secrets-for-fb-optimization/"><u>[Updated] In 2024, Mastering the Social Media Lands Point 10 Secrets for FB Optimization</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-symbolizing-success-affordable-and-flexible-logo-crafting-from-templates/"><u>2024 Approved  Symbolizing Success  Affordable & Flexible Logo Crafting From Templates</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-the-great-growers-guide-the-best-farmer-games/"><u>2024 Approved  The Great Growers' Guide  The Best Farmer Games</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-no-audio-devices-in-windows/"><u>Addressing 'No Audio Devices' In Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/blocking-windows-update-prompts/"><u>Blocking Windows Update Prompts</u></a></li>
<li><a href="https://windows11.techidaily.com/cherishing-the-slumber-of-your-computer/"><u>Cherishing the Slumber of Your Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-errors-during-amd-195-installation/"><u>Eliminating Windows Errors During AMD 195 Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-windows-for-wordpad-operability/"><u>Exploring Windows for WordPad Operability</u></a></li>
<li><a href="https://change-location.techidaily.com/guide-how-to-unbrick-a-bricked-oppo-find-x7-ultra-phone-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Guide How To Unbrick a Bricked Oppo Find X7 Ultra Phone | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-xiaomi-redmi-note-12-pro-4g-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Xiaomi Redmi Note 12 Pro 4G Phones with/without a PC</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-windows-11-theme-treasures-revealed/"><u>Hidden Windows 11 Theme Treasures Revealed</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-icloud-activation-lock-on-ipod-and-apple-iphone-7-the-right-way-by-drfone-ios/"><u>How To Bypass iCloud Activation Lock On iPod and Apple iPhone 7 The Right Way</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-error-1015-while-restoring-iphone-12-mini-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to fix error 1015 while restoring iPhone 12 mini | Stellar</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-boost-your-brand-visibility-mastering-instagram-hashtags/"><u>In 2024, Boost Your Brand Visibility – Mastering Instagram Hashtags</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-3-sites-to-find-free-htc-unlock-codes-to-unlock-your-htc-phone-by-drfone-android/"><u>In 2024, Top 3 Sites to Find Free HTC Unlock Codes to Unlock Your HTC Phone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-error-handling-fixing-missing-updates-error-code-0x80070003/"><u>Mastering Windows Error Handling: Fixing Missing Updates (Error Code: 0X80070003)</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-internet-options-tweaks-for-windows-11/"><u>Mastery of Internet Options Tweaks for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-common-windo-errors-quickly/"><u>Navigating Through Common Windo Errors, Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/preserving-calculator-precedence-on-windows-systems/"><u>Preserving Calculator Precedence on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-guide-to-restore-windows-11-troubleshooters/"><u>Quick FIX Guide to Restore Windows 11 Troubleshooters</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/recommended-best-applications-for-mirroring-your-itel-a70-screen-drfone-by-drfone-android/"><u>Recommended Best Applications for Mirroring Your Itel A70 Screen | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-smooth-operation-fix-frozen-epic-games-launcher/"><u>Securing Smooth Operation: Fix Frozen Epic Games Launcher</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-rearranged-characters-in-windows-os/"><u>Solutions for Rearranged Characters in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-ipad-image-import-issues-in-windows-1111-pro/"><u>Solving iPad Image Import Issues in Windows 11/11 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-to-switching-notepad-to-dark-theme-in-windows-11/"><u>Step-by-Step Guide to Switching Notepad to Dark Theme in Windows 11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/strategies-for-selective-success-in-the-youtube-realm-for-2024/"><u>Strategies for Selective Success in the YouTube Realm for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-github-desktop-on-windows-11-os/"><u>The Ultimate Guide to GitHub Desktop on Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-device-synergy-with-google-nearby-sharing/"><u>Unlocking Device Synergy with Google Nearby Sharing</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-windows-blue-screen-error-0x8007007e/"><u>Unraveling the Mystery of Windows Blue Screen Error: 0X8007007E</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-wisdom-efficiently-eliminate-partitioned-areas-on-your-pc/"><u>Windows Wisdom: Efficiently Eliminate Partitioned Areas on Your PC</u></a></li>
</ul></div>
