---
title: "Solving SnipKey Issues: Resetting Windows Keys"
date: 2024-07-11T21:52:17.998Z
updated: 2024-07-12T21:52:17.998Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Solving SnipKey Issues: Resetting Windows Keys"
excerpt: "This Article Describes Solving SnipKey Issues: Resetting Windows Keys"
keywords: Fix SnipKey Key Errors,Reset Window Lockkeys,Reconfigure Windows Keys,SnipKey Functionality Restore,Unlock Windows Snipping Tool,Troubleshoot Snipping Edge,Erase Windows Screen Capture Issue
thumbnail: https://thmb.techidaily.com/10c291d26c69b79184acc714bd905fecf227774d1628ff4b17b2024d943bf02d.jpg
---

## Solving SnipKey Issues: Resetting Windows Keys

 Whether you need to capture an error message or share something specific with someone, screenshots can be a lifesaver. The Win + Shift + S shortcut makes it easy to take screenshots with the Snipping Tool, but what if that shortcut stops responding?

 Is your screenshot-taking career over? Definitely not. There are still some fixes you can try to solve this issue. Read on to learn what to do when your Win + Shift + S shortcut isn't working.

## 1\. Restart the Computer

 It might sound simple, but restarting your computer often solves minor problems. This can help clear out any glitches that may prevent the shortcut from working correctly.

 To restart your computer, close any running programs. Now, open the Start menu and choose **Restart** in the list of options.

## 2\. Check Your Keyboard

 Check the keyboard for any dirt or debris that may obstruct the keys. Clean off dust, crumbs, and other particles with compressed air. Ensure that all the keys are working correctly and that none are stuck or pressed down. If the keys have been damaged or worn down, consider replacing your keyboard.

## 3\. Enable the Clipboard History

 If keyboard dirt and debris are not the issues, you may need to enable the clipboard history feature. This will help you restore any screenshots taken with Win + Shift + S that have been lost.

![Enable the Clipboard History](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/enable-the-clipboard-history.jpg)

 To enable it, open Settings and navigate to **System** \> **Clipboard**. There, you'll find the toggle for **Clipboard history** – turn it on.

 You can also use the Windows search bar to type in **Clipboard settings** and open it directly. If you prefer shortcuts, hit **Win + R** or type **ms-settings:clipboard** into Run.

## 4\. Turn on Snipping Tool Notification Toggle

 When you press Win + Shift + S on your keyboard, a notification should appear in the bottom-right corner of the screen. This notification toggle helps you quickly access screenshots taken with the shortcut.

 If you don't see a notification, that means the toggle is off, and you may need to enable it manually. Here's how to do it:

1. Right-click on Start and select **Settings**.
2. In the Settings window, navigate to **System** \> **Notifications**.
3. Under **Notifications from apps and other senders**, scroll down to the bottom and turn on the Snipping Tool notification toggle.  
![Turn on Snipping Tool Notification Toggle](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/turn-on-snipping-tool-notification-toggle.jpg)

 Once you have enabled this option, press **Win + Shift + S** to take a screenshot. If the shortcut works, you will see a notification that the screenshot is saved to the clipboard.

## 5\. Reset the Snipping Tool

 Another solution is to reset the Snipping Tool. It restores the default settings and can help if something goes wrong.

 To reset it, right-click on the **Start** menu and select **Installed apps**. Find **Snipping Tool** in the list, click three dots, and select **Advanced options**.

 You can also use **Win + R** or type **ms-settings:appsfeatures** in the Run dialog box to open Installed apps. From there, you can find the Advanced options for the Snipping Tool.

![Reset Snipping Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-snipping-tool.jpg)

 On the next page, scroll down to the **Reset** section. Select **Reset** and then click on **Reset** again in the confirmation popup. After resetting the Snipping Tool, check if the Win + Shift + S shortcut works.

## 6\. Reinstall the Snipping Tool

 If resetting doesn't solve the problem, try reinstalling the Snipping Tool. It will resolve any issues you may have with your current installation.

 To reinstall the Snipping Tool, open the System Settings. Select **Apps** \> **Installed apps**, then find and select **Snipping Tool** from the list of installed programs.

![Reset the Snipping Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-the-snipping-tool.jpg)

 Click the three dots and select **Uninstall**. Now follow the on-screen instructions to complete the process. Once done, download and install a new version of the Snipping Tool from the Microsoft Store app.

## 7\. Turn on Windows Hotkeys

 If your Windows hotkeys are disabled for some reason, the shortcut keys will not work. In such cases, you will need to enable the Windows hotkeys through the group policy editor. Here's how to do it:

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **gpedit.msc** in the dialog box and hit Enter. This will open the Group Policy Editor window.  
![Turn on Windows Hotkeys Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/turn-on-windows-hotkeys-using-group-policy.jpg)
3. Navigate to the path:  
`User Configuration > Administrative Templates > Windows Components > File Explorer`
4. In the right pane, double-click on the **Turn off Windows Key hotkeys** option.
5. Select Enabled in the settings window and click **Apply** \> **OK**.

 After making these changes, try taking a screenshot with Win + Shift + S shortcut. It should work now.

 One thing to remember is that this method will only work with Windows Pro and Enterprise editions. If you have the Home edition, you can't access the Group Policy Editor. In such a case, you'll need to [enable the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). But if that sounds complicated, skip this method and use the Registry Editor instead.

 To enable Windows Hotkeys through the Registry Editor, follow these steps:

* Click on Start, type **regedit**, and hit **Enter**.
* If the UAC window pops up, click Yes to open the registry editor.  
`Navigate to HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer`
* If you don't see the Explorer folder, right-click on **Policies** and select **New > Key**. Name the newly created key **Explorer**.
* Now right-click on **Explorer** and select **New** \> **DWORD 32-bit**.
* Name the DWORD **NoWinKeys**.
* Double-click on **NoWinKeys** and set the value data to **0**.  
![Turn on Windows Hotkeys Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/turn-on-windows-hotkeys-using-registry.jpg)
* Select Base as **Hexadecimal** and click **OK** to save the changes.

 After that, exit the registry editor and restart your computer. Once the system reboots, check if the issue has been resolved.

## 8\. Perform Some Generic Fixes

 There are a few general fixes that might help you get the Win + Shift + S keyboard shortcut working. Here's what you need to do:

1. Check the keyboard driver status and update it if needed.
2. Try [running the SFC utility](https://www.makeuseof.com/windows-built-in-repair-tools/) to fix corrupted system files.
3. Make sure you are [running the latest version of Windows](https://www.makeuseof.com/update-windows-manually/).
4. [Run a full scan with your antivirus program](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) and see if it solves the issue.
5. If the issue still persists, there's a chance that third-party applications are interfering with the Snipping Tool shortcut. In such a case, [try performing a clean boot](https://www.makeuseof.com/clean-boot-windows-11/). This will temporarily disable all the third-party applications and allow you to check if they were causing the issue.

## Taking Screenshots Is Easy With Shortcut Keys

 Keyboard shortcuts provide quick and easy access to different functions on your PC. It allows you to easily switch between applications and perform tasks. There are times, though, when the Win + Shift + S hotkey does not work properly. Hopefully, one of the above methods fixed this issue for you.

 Is your screenshot-taking career over? Definitely not. There are still some fixes you can try to solve this issue. Read on to learn what to do when your Win + Shift + S shortcut isn't working.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/solve-non-responsive-function-keys-in-windows-11/"><u>Solve: Non-Responsive Function Keys in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enjoy-desktop-wallpapers-in-their-best-quality-on-windows-11/"><u>How to Enjoy Desktop Wallpapers in Their Best Quality on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/identifying-programs-by-their-launch-shorthand-labels/"><u>Identifying Programs by Their Launch Shorthand Labels</u></a></li>
<li><a href="https://windows11.techidaily.com/the-offline-warriors-guide-to-microsoft-onedrive/"><u>The Offline Warrior's Guide to Microsoft OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-integration-mastery-overcoming-add-on-installation-roadblocks/"><u>Windows Integration Mastery: Overcoming Add-On Installation Roadblocks</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-obstacle-of-error-code-0x0000004e/"><u>Overcoming the Obstacle of Error Code 0X0000004E</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-prevent-microsoft-teams-freeze-in-ws11ws10/"><u>Strategies to Prevent Microsoft Teams Freeze in WS11/WS10</u></a></li>
<li><a href="https://windows11.techidaily.com/uncomplicated-superiority-persistent-high-privilege-terminal/"><u>Uncomplicated Superiority: Persistent High-Privilege Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/perfect-pixels-for-every-window-11-display/"><u>Perfect Pixels for Every Window 11 Display</u></a></li>
<li><a href="https://windows11.techidaily.com/six-secrets-to-spinning-pictures-in-w11-os/"><u>Six Secrets to Spinning Pictures in W11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-through-a-windows-systems-exception-breaking-point-issue/"><u>Guiding Through a Windows System's Exception Breaking Point Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-generic-sound-not-recognized-issue-in-windows-system/"><u>Overcoming Generic Sound Not Recognized Issue in Windows System</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-windows-onedrive-error-for-immediate-folder-addition/"><u>Unraveling Windows OneDrive Error for Immediate Folder Addition</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-to-erase-steam-dns-information-on-pc/"><u>Guidelines to Erase Steam DNS Information on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-redo-on-windows-with-a-hotkey/"><u>How to Redo on Windows With a Hotkey</u></a></li>
<li><a href="https://windows11.techidaily.com/purging-protection-logs-on-windows-1011-with-ease/"><u>Purging Protection Logs on Windows 10/11 with Ease</u></a></li>
<li><a href="https://android-location.techidaily.com/getting-the-pokemon-go-gps-signal-not-found-11-error-in-xiaomi-redmi-note-13-proplus-5g-drfone-by-drfone-virtual/"><u>Getting the Pokemon Go GPS Signal Not Found 11 Error in Xiaomi Redmi Note 13 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-windows-searches-using-everythingapp/"><u>Streamline Windows Searches Using EverythingApp</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-whatsapp-messages-on-vivo-s17-pro-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track WhatsApp Messages on Vivo S17 Pro Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/how-to-make-money-from-youtube-shorts-requirements-and-earning-potential/"><u>How to Make Money From YouTube Shorts  Requirements and Earning Potential</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-flixfortress-over-a-hundred-channels-of-fortitude/"><u>[Updated] In 2024, FlixFortress  Over a Hundred Channels of Fortitude</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-absence-win-error-due-to-missing-mfc71udll/"><u>Troubleshooting Absence: Win Error Due to Missing Mfc71u.dll</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-discord-flag-artists-masterpieces-and-your-profile-coverage-ideas/"><u>[New] Discord Flag Artists  Masterpieces and Your Profile Coverage Ideas</u></a></li>
<li><a href="https://driver-install.techidaily.com/optimizing-wacom-support-on-classic-and-modern-windows-versions/"><u>Optimizing Wacom Support on Classic & Modern Windows Versions</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11s-multi-task-abilities-efficiently/"><u>Navigating Windows 11'S Multi-Task Abilities Efficiently</u></a></li>
<li><a href="https://some-techniques.techidaily.com/home-cinematic-excellence-with-5-quick-tips-for-2024/"><u>Home Cinematic Excellence with 5 Quick Tips for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-financial-engine-behind-windows-11/"><u>The Financial Engine Behind Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/re-establish-steam-offline-status-via-win-tricks/"><u>Re-Establish Steam Offline Status via Win Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-installer-package-fails-on-windows-11/"><u>Troubleshooting Installer Package Fails on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-ideas-into-art-the-best-drawing-apps-ranked-in-win10/"><u>Transforming Ideas Into Art: The Best Drawing Apps Ranked in Win10</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-cost-effective-windows-11-keys/"><u>Unveiling Cost-Effective Windows 11 Keys</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/unearthing-user-generated-footage-on-facebook/"><u>Unearthing User-Generated Footage on Facebook</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-lost-wi-fi-links-top-strategies-to-regain-internet-connection-on-windows-10/"><u>Reviving Lost Wi-Fi Links: Top Strategies to Regain Internet Connection on Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-ensure-optimal-functionality-of-add-ons-in-windows-os/"><u>Strategies to Ensure Optimal Functionality of Add-Ons in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-disabled-remove-option-for-pin-access-control/"><u>Reviving Disabled 'Remove' Option for PIN Access Control</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-makeover-the-art-of-digital-expression/"><u>Windows 11 Makeover: The Art of Digital Expression</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-creativity-in-calendar-design-a-windows-outlook-method/"><u>Unleashing Creativity in Calendar Design - A Windows Outlook Method</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-hidden-desktop-icons-on-the-latest-windows/"><u>Revive Hidden Desktop Icons on the Latest Windows</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-vintage-video-production-techniques-for-timelessness/"><u>[Updated] Vintage Video Production  Techniques for Timelessness</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-the-complete-guide-to-soundtracking-vimeo-content/"><u>In 2024, The Complete Guide to Soundtracking Vimeo Content</u></a></li>
<li><a href="https://windows11.techidaily.com/never-disable-wins-11-notifications-why/"><u>Never Disable Wins 11 Notifications: Why?</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-how-luts-revolutionize-your-photo-editing-experience/"><u>2024 Approved  How LUTs Revolutionize Your Photo Editing Experience</u></a></li>
<li><a href="https://data-recovery.techidaily.com/complete-data-revival-solution-reinstate-lost-information-across-formats/"><u>Complete Data Revival Solution - Reinstate Lost Information Across Formats</u></a></li>
</ul></div>
