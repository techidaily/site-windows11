---
title: "Morning Magic: Startup Seamlessly, Unlock Notepad Quickly"
date: 2024-08-31T22:16:03.011Z
updated: 2024-09-01T22:16:03.011Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Morning Magic: Startup Seamlessly, Unlock Notepad Quickly"
excerpt: "This Article Describes Morning Magic: Startup Seamlessly, Unlock Notepad Quickly"
keywords: Morning Routine Tips,Seamless Startups,Fast Access Notebook,Productivity Beginnings,Early Success Secrets,Quick Workspace Setup,Efficient Starting Mornings
thumbnail: https://thmb.techidaily.com/95c7607cc85834758f594e36f86b8274633568f32ba37267dd79e6e802f121e2.png
---

## Morning Magic: Startup Seamlessly, Unlock Notepad Quickly

 Are you tired of opening Sticky Notes every time you turn on your computer? What if it could open automatically each time Windows starts?

 Well, there's good news for you: Sticky Notes can launch at startup in Windows. This article illustrates how to set up and use Sticky Notes at startup.

## 1\. Keep Sticky Notes Open at Shutdown

 When you're done working with Sticky Notes, make sure not to close the window. Instead, leave it open as you shut down your computer. This will ensure that when you turn on your computer, Sticky Notes opens automatically.

 Although the solution is simple, it may not work, or you may find it difficult to remember to keep it open when you turn off your PC. In that case, there are other alternatives; add Sticky Notes to the startup folder or use Task Scheduler.

## 2\. Add Sticky Notes to the Startup Folder

 If you don't want to keep Sticky Notes open at shutdown, you can add it to the startup folder. The Startup folder is a special directory in File Explorer. It stores applications that launch automatically when Windows starts.

 To add Sticky Notes to the Startup folder, follow these steps.

1. Press **Win + R** and type **shell:startup** in the Run dialog.
2. Click **OK** or press Enter. This opens a folder containing all the applications that launch at startup.
3. Press **Windows** to open the Start menu, then click **All apps**. Now scroll down and find **Sticky Notes** in the list.
4. Drag and drop **Sticky Notes** into the Startup folder.

 After performing these steps, close File Explorer and restart your computer. Sticky Notes should now open at startup.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Use the Task Scheduler

 Task Scheduler is another way to open Sticky Notes at startup. This Windows feature schedules and automates tasks at specific times or conditions.

 To add Sticky Notes using this tool, follow these steps:

1. [Open Task Scheduler](https://www.makeuseof.com/windows-11-open-task-scheduler/).
2. Click **Create Basic Task** from the **Actions** panel on the right. This opens a wizard that guides you through the setup.  
![Create Basic Task in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-basic-task-in-task-scheduler.jpg)
3. In the first step, give your task a name and click **Next**.  
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Startup Sticky Notes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-sticky-notes.jpg)
4. Now select **When I log on** as the trigger and click **Next** at the bottom.  
![Create Basic Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-basic-task-wizard.jpg)
5. Choose **Start a program** in the Action window and click **Next**.  
![Start a program in Action tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-action-tab.jpg)
6. In the **Program/script** field, type the path below:  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
C:\Windows\System32\cmd.exe
7. In the Add arguments (optional) field, copy and paste the following command:  
/c start shell:appsfolder\Microsoft.MicrosoftStickyNotes_8wekyb3d8bbwe!App  
![Start a Program in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-task-scheduler.jpg)
8. Click **Next** and review all the settings.
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
9. Now click **Finish** to save your work.  
![Finish Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/finish-task-wizard.jpg)

 The Task Scheduler will now run Sticky Notes each time you log in. This way, Sticky Notes launches automatically at startup.

## 4\. Tweak the Registry Editor

 If you're comfortable editing the Windows registry, you can tweak it to open Sticky Notes at startup. This method requires knowledge of how the Registry Editor works and caution when editing it. If done incorrectly, it can cause serious system errors. It's best to [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing anything.

 To open Sticky Notes at startup using the Registry Editor, follow these steps:

1. [Open Windows Search](https://www.makeuseof.com/windows-search-use-guide/).
2. Type **regedit** in the search bar and click on the Registry Editor option.
3. If the UAC dialog appears, click **Yes** to grant access.
4. In the Registry Editor window, navigate to the following path:  
Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\PenWorkspace\Notes
5. Double-click the **LaunchOnNextUserSession** key on the right.  
![Tweak Registry Editor to Open Sticky Notes at Startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tweak-registry-editor-to-open-sticky-notes-at-startup.jpg)
6. Change the Value data from 0 to **1** in the Edit DWORD (32-bit) Value window and click **OK**.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
 If you can't find the **LaunchOnNextUserSession** key, right-click on the **Notes** folder and select **New > DWORD (32-bit) Value**. Name the newly created key “LaunchOnNextUserSession” and assign it the Value data of **1**.
7. Close the Registry Editor and restart your computer to save the changes. Sticky Notes should now open at startup.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## Windows Now Starts With Sticky Notes Open

 This article outlines several ways to open Sticky Notes at startup in Windows. If you want an easier solution, leave Sticky Notes open when you shut down your computer; it will launch automatically when Windows starts. If not, add Sticky Notes to the startup folder. If you want more control over when Sticky Notes launches, use Task Scheduler or tweak the Registry Editor.

 Well, there's good news for you: Sticky Notes can launch at startup in Windows. This article illustrates how to set up and use Sticky Notes at startup.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-fixes-for-iphoneandroidchrome-why-are-facebook-videos-blurry/"><u>[New] 2024 Approved  Fixes for iPhone/Android/Chrome | Why Are Facebook Videos Blurry?</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-enthralling-readers-with-these-stellar-5-book-promo-videos-for-2024/"><u>[New] Enthralling Readers with These Stellar 5 Book Promo Videos for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-digital-artisans-gathering-haven/"><u>[Updated] 2024 Approved  Digital Artisans Gathering Haven</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-enhance-creativity-on-tiktok-three-essential-steps-to-change-video-backdrops/"><u>[Updated] 2024 Approved  Enhance Creativity on TikTok  Three Essential Steps to Change Video Backdrops</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-best-free-android-capture-app-zero-ads/"><u>[Updated] Best Free Android Capture App, Zero Ads</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-mastering-close-up-cinematography-through-zooming-for-2024/"><u>[Updated] Mastering Close-Up Cinematography Through Zooming for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/efficient-image-capturing-made-simple-the-best-pc-snipers-listed/"><u>Efficient Image Capturing Made Simple  The Best PC Snipers Listed</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/fixing-errors-with-missing-dll-files-in-windows-solutions-for-msvcr71dll/"><u>Fixing Errors with Missing DLL Files in Windows: Solutions for Msvcr71.dll</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/full-guide-to-unlock-iphone-6s-with-itunes-drfone-by-drfone-ios/"><u>Full Guide to Unlock iPhone 6s with iTunes | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-change-credit-card-on-your-apple-iphone-11-pro-apple-id-and-apple-pay-by-drfone-ios/"><u>How to Change Credit Card on Your Apple iPhone 11 Pro Apple ID and Apple Pay</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-change-your-apple-id-on-iphone-x-with-or-without-password-by-drfone-ios/"><u>How To Change Your Apple ID on iPhone X With or Without Password</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-effortlessly-engage-with-windows-11-service-tools/"><u>How to Effortlessly Engage with Windows 11 Service Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-prolong-windows-10-restart-time-while-tasks-run/"><u>How to Prolong Windows 10 Restart Time While Tasks Run</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-remove-screen-lock-pin-on-lava-blaze-2-5g-like-a-pro-5-easy-ways-by-drfone-android/"><u>How To Remove Screen Lock PIN On Lava Blaze 2 5G Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-speed-up-the-yuzu-emulator-on-windows/"><u>How to Speed Up the Yuzu Emulator on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/is-enhancement-or-extra-cost-justified-for-win-11s-add-ons/"><u>Is Enhancement or Extra Cost Justified for Win 11'S Add-Ons?</u></a></li>
<li><a href="https://windows11.techidaily.com/making-the-right-windows-11-call-home-vs-premium-features/"><u>Making the Right Windows 11 Call: Home Vs. Premium Features</u></a></li>
<li><a href="https://windows11.techidaily.com/master-email-attachment-handling-in-microsoft-words-read-pane-mode/"><u>Master Email Attachment Handling in Microsoft Word's Read Pane Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-successful-files-transfer-in-windows/"><u>Mastering the Art of Successful Files Transfer in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-fixes-reconciling-obs-server-disconnections-on-windows/"><u>Mastering the Fixes: Reconciling OBS Server Disconnections on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-keeping-windows-time-unchanged/"><u>Mastery over Keeping Windows Time Unchanged</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-prevent-windows-pc-from-booting-into-bios/"><u>Methods to Prevent Windows PC From Booting Into BIOS</u></a></li>
<li><a href="https://windows11.techidaily.com/move-your-onedrive-step-by-step-for-windows-11/"><u>Move Your OneDrive: Step-by-Step for Windows 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/navigating-number-changes-on-tiktok-with-precision/"><u>Navigating Number Changes on TikTok with Precision</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-intel-hd-error-in-meeting-minimum-requirements/"><u>Navigating Through Intel HD Error in Meeting Minimum Requirements</u></a></li>
<li><a href="https://fake-location.techidaily.com/prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-honor-x50-gt-drfone-by-drfone-virtual-android/"><u>Prank Your Friends! Easy Ways to Fake and Share Google Maps Location On Honor X50 GT | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/pursuitofhigherqualitycams/"><u>PursuitOfHigherQualityCams</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-failures-of-file-segmentation-service/"><u>Resolving Failures of File Segmentation Service</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-checksum-accuracy-in-winrar-archives-with-6-tips/"><u>Restoring Checksum Accuracy in WinRAR Archives with 6 Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-taskbar-button-image-rendering/"><u>Restoring Taskbar Button Image Rendering</u></a></li>
<li><a href="https://windows11.techidaily.com/reversing-operation-failure-0x709-on-pc/"><u>Reversing Operation Failure 0X709 on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-and-protect-win-11-edge-instalment-of-microsofts-aguard-feature/"><u>Secure and Protect Win 11 Edge: Instalment of Microsoft's Aguard Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/securely-resetting-dns-on-the-latest-windows-version/"><u>Securely Resetting DNS on the Latest Windows Version</u></a></li>
<li><a href="https://windows11.techidaily.com/skyrocket-success-in-windows-11-with-these-top-5-apps/"><u>Skyrocket Success in Windows 11 With These Top 5 Apps</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/steps-to-restore-your-data-following-an-iphone-factory-reset/"><u>Steps to Restore Your Data Following an iPhone Factory Reset 🔄</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-tackling-windows-disk-errors/"><u>The Ultimate Guide to Tackling Windows Disk Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/title-perfecting-space-between-windows-widgets/"><u>Title: Perfecting Space Between Windows Widgets</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-non-responsive-windows-enter-key/"><u>Troubleshooting Non-Responsive Windows Enter Key</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-steps-for-the-black-screen-issue-in-rainbow-six-siege-pc-guide/"><u>Troubleshooting Steps for the Black Screen Issue in Rainbow Six Siege - PC Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/turning-classic-computers-into-modern-windows-11-hubs-with-tools/"><u>Turning Classic Computers Into Modern Windows 11 Hubs with Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-new-network-possibilities-with-win11s-settings/"><u>Unlock New Network Possibilities with Win11's Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-diagnostic-info-a-quick-guide/"><u>Unlocking Windows' Diagnostic Info: A Quick Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-gif-size-limits-a-guide-to-fixed-errors-in-discord-win11/"><u>Unraveling GIF Size Limits: A Guide to Fixed Errors in Discord (Win11)</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-the-industry-standard-adobe-premiere-pro-for-mac-video-editors/"><u>Updated In 2024, The Industry Standard Adobe Premiere Pro for Mac Video Editors</u></a></li>
<li><a href="https://windows11.techidaily.com/uptime-expertise-for-win11-devices-discover-the-top-5-methods/"><u>Uptime Expertise for Win11 Devices - Discover the Top 5 Methods</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/vocal-variation-at-your-fingertips-free-software-to-transform-your-voice/"><u>Vocal Variation at Your Fingertips  Free Software to Transform Your Voice</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-setting-up-microsoft-pc-manager/"><u>Win 11: Setting Up Microsoft PC Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-stop-intelligent-assistant/"><u>Windows 11: Stop Intelligent Assistant</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-tricks-bringing-off-screen-apps-back-to-life-with-6-tips/"><u>Windows Tricks: Bringing Off-Screen Apps Back to Life with 6 Tips</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>