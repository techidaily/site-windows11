---
title: How to Quickly Fix Keyboard Issues in Window's Snipper
date: 2024-07-11T22:00:19.866Z
updated: 2024-07-12T22:00:19.866Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Quickly Fix Keyboard Issues in Window's Snipper
excerpt: This Article Describes How to Quickly Fix Keyboard Issues in Window's Snipper
keywords: Keyboard Repair Windows,Fix Keyboard Sniper,Solve WinSnapper Keying,Quick Keyfix Windows,Window's Key Troubleshoot,SnipKeyfix Guide Windo,Fast Fix Keyboard Win
thumbnail: https://thmb.techidaily.com/33bb4081d4eeefa2b002761f140e6d8a1ab23c4b8fc2690daa04e9c88bdd81bd.jpg
---

## How to Quickly Fix Keyboard Issues in Window's Snipper

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
<li><a href="https://windows11.techidaily.com/winning-back-chrome-color-loss/"><u>Winning Back Chrome Color Loss</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-non-existent-mmc-snaps/"><u>Unraveling the Mystery of Non-Existent MMC Snaps</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-chrome-freeze-windows-edition/"><u>Overcoming Chrome Freeze: Windows Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-solve-drop-problems-in-win11/"><u>Swiftly Solve Drop Problems in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-malfunctioning-windows-easy-fixes-at-hand/"><u>Mastery Over Malfunctioning Windows: Easy Fixes at Hand!</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-secrets-for-mastering-volume-control-in-windows-11/"><u>Unlock Secrets for Mastering Volume Control in Windows 11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/day-jobs-and-digital-passion-striking-a-balance-for-2024/"><u>Day Jobs & Digital Passion  Striking a Balance for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-google-frp-on-galaxy-a05s-by-drfone-android-unlock-remove-google-frp/"><u>How To Bypass Google FRP on Galaxy A05s</u></a></li>
<li><a href="https://windows11.techidaily.com/automate-peaceful-rest-for-your-windows-11-desktop/"><u>Automate Peaceful Rest for Your Windows 11 Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-turn-on-or-off-windows-installation-service/"><u>Tips to Turn On or Off Windows Installation Service</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-versatile-10-applications-beyond-official-game-bar/"><u>[Updated] Versatile 10 Applications Beyond Official Game Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-powershell-for-user-account-control/"><u>Leveraging PowerShell for User Account Control</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-comparative-analysis-is-pickup-the-best-editor-for-your-android-device/"><u>[Updated] Comparative Analysis  Is PickUp The Best Editor for Your Android Device?</u></a></li>
<li><a href="https://activate-lock.techidaily.com/easy-tutorial-for-activating-icloud-on-iphone-14-pro-max-safe-and-legal-by-drfone-ios/"><u>Easy Tutorial for Activating iCloud on iPhone 14 Pro Max Safe and Legal</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-unreachable-error-with-spotify-in-windows-1011/"><u>Tackling the Unreachable Error with Spotify in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-error-code-31-a-troubleshooting-manual/"><u>Navigating Through Windows Error Code 31: A Troubleshooting Manual</u></a></li>
<li><a href="https://windows11.techidaily.com/insight-into-application-usage-on-windows-pc/"><u>Insight Into Application Usage on Windows PC</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-optimizing-igtv-videos-editing-strategies/"><u>[Updated] In 2024, Optimizing IGTV Videos  Editing Strategies</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/1713951834744-want-to-learn-how-to-crop-or-trim-video-in-powerpoint-we-have-got-you-covered-we-have-given-a-step-by-step-guide-that-will-allow-you-to-trim-and-crop-videos/"><u>Want to Learn How to Crop or Trim Video in PowerPoint? We Have Got You Covered; We Have Given a Step-by-Step Guide that Will Allow You to Trim and Crop Videos Using This Presentation Program for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/ideal-ringtones-picks-high-quality-destinations/"><u>Ideal Ringtones Picks  High-Quality Destinations</u></a></li>
<li><a href="https://windows11.techidaily.com/maintaining-taskbars-presence-in-maxed-browser-views/"><u>Maintaining Taskbar's Presence in Maxed Browser Views</u></a></li>
<li><a href="https://windows11.techidaily.com/remote-server-files-via-nas-sharing/"><u>Remote Server Files via NAS Sharing</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-installation-issues-fixing-zero-error-on-win11/"><u>Avoid Installation Issues: Fixing Zero Error on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-overcome-windows-memory-errors/"><u>Steps to Overcome Windows Memory Errors</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-best-selling-ubuno-video-recorders-for-linux-users-for-2024/"><u>[New] Best-Selling UbuNo Video Recorders for Linux Users for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/redefining-user-experience-the-changing-landsinas-of-w10-and-w11/"><u>Redefining User Experience: The Changing Landsinas of W10 & W11</u></a></li>
<li><a href="https://windows11.techidaily.com/ai-driven-evolution-in-windows-software-design/"><u>AI-Driven Evolution in Windows Software Design</u></a></li>
<li><a href="https://windows11.techidaily.com/turbocharging-windows-solid-state-drives-utilizing-fresh-tools/"><u>Turbocharging Windows' Solid State Drives - Utilizing Fresh Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-faulty-tab-key-on-your-pc/"><u>Recovering Faulty Tab Key on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-locked-status-tips-for-windows-users-153-chars/"><u>Preventing Locked Status: Tips for Windows Users (153 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/simple-steps-to-enable-windows-11s-search-feature-in-task-manager/"><u>Simple Steps to Enable Windows 11'S Search Feature in Task Manager</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-the-ultimate-screen-recording-hack-for-instagram-stories/"><u>[Updated] In 2024, The Ultimate Screen Recording Hack for Instagram Stories</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-eliminate-windows-unknown-value-warning/"><u>Strategies to Eliminate Windows Unknown Value Warning</u></a></li>
<li><a href="https://windows11.techidaily.com/approaches-to-fix-failed-launch-of-lunar-client-in-windows/"><u>Approaches to Fix Failed Launch of Lunar Client in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-personalization-transforming-ordinary-into-extraordinary/"><u>Windows 11 Personalization: Transforming Ordinary Into Extraordinary</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-efficiently-stream-your-facebook-feed-on-pcmaclaptop/"><u>2024 Approved  Efficiently Stream Your Facebook Feed on PC/Mac/Laptop</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-a-non-responsive-resource-monitor-steps-for-windows-11-users/"><u>Navigating a Non-Responsive Resource Monitor: Steps for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-invalid-temp-directories-in-windows-11/"><u>Resolving Invalid Temp Directories in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-dxgierrordevicehung-in-win1011/"><u>Overcoming DXGI_ERROR_DEVICE_HUNG in Win10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-for-genuine-adobe-error-message/"><u>Quick Fix for Genuine Adobe Error Message</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-editors-elite-gadgets-best-machines-for-screen-magic/"><u>[Updated] In 2024, Editor’s Elite Gadgets  Best Machines for Screen Magic</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstating-unblocked-access-for-microsoft-store-app-in-win11/"><u>Reinstating Unblocked Access for Microsoft Store App in Win11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/ultimate-10-volume-upgrade-tools-for-pc-ios-and-android-for-2024/"><u>Ultimate 10 Volume Upgrade Tools for PC, iOS & Android for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-file-management-through-explores-sidebar/"><u>Streamlining File Management Through Explore's Sidebar</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-deactivated-sliders-for-volume-control/"><u>Troubleshooting Deactivated Sliders for Volume Control</u></a></li>
<li><a href="https://facebook.techidaily.com/navigating-the-sea-of-data-utilizing-facebooks-transparent-tools/"><u>Navigating the Sea of Data: Utilizing Facebook's Transparent Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-achieve-stable-gameplay-and-fps-boost-in-roblox/"><u>Strategies to Achieve Stable Gameplay & FPS Boost in Roblox</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-mastering-the-art-of-larger-video-posts-in-instagram-for-2024/"><u>[New] Mastering the Art of Larger Video Posts in Instagram for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/improving-startup-order-in-windows-11/"><u>Improving Startup Order in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-your-sign-in-overcoming-access-restrictions-in-win/"><u>Secure Your Sign-In: Overcoming Access Restrictions in Win</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-efficiently-techniques-bypassing-ls-command/"><u>Navigating Windows Efficiently: Techniques Bypassing LS Command</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/2024-approved-off-limits-guide-unfollowers-pathway-out-of-tiktok/"><u>2024 Approved  Off-Limits Guide  Unfollower's Pathway Out of TikTok</u></a></li>
</ul></div>
