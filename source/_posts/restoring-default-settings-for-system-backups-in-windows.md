---
title: Restoring Default Settings for System Backups in Windows
date: 2024-08-27T16:00:54.027Z
updated: 2024-08-28T16:00:54.027Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Default Settings for System Backups in Windows
excerpt: This Article Describes Restoring Default Settings for System Backups in Windows
keywords: Windows Restore,Default Backup Fix,System Reset Guide,WinOS Setup Revert,Backup Protocol Restart,Default Settings Recovery,Safe Mode Boot Help
thumbnail: https://thmb.techidaily.com/26dcef27c207b8605e3fcf4585ee0822110eeb8a794c85ff8e27071c7786d452.jpg
---

## Restoring Default Settings for System Backups in Windows

 System failure or data loss can cause huge amounts of damage and that’s why Windows offers a backup feature to protect your critical data. If your backups corrupt or otherwise function incorrectly, you can reset Windows Backup to its default settings. This guide will teach you some methods to reset Windows Backup to its default on Windows.

## How Do I Know if I Need to Reset Windows Backup?

 You may need to reset Windows Backup if your backups aren't working, taking too long to create, or you can't access the stored files. If you are experiencing these issues, resetting Windows Backup may resolve them.

 For this, either use the Command Prompt or create a batch file. The steps for both methods are outlined below and should help you get your backups running again.

## Is Resetting Window Backup Risky?

 While resetting Windows Backup is generally safe, there are some risks associated with it.

 Firstly, you may lose all existing backups if you reset Windows Backup. To ensure you don't lose data, [create a backup of the existing Windows files](https://www.makeuseof.com/tag/backup-windows-files-folders/) before resetting Windows Backup.

 Furthermore, the reset may affect some third-party apps. It's wise to check with your software vendor before resetting Windows Backup.

 If something goes wrong during the reset, you may have a corrupted backup configuration. In such cases, reinstall the operating system and start from scratch.

 Overall, resetting Windows Backup helps resolve existing issues, but take the necessary precautions to avoid potential risks.

<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Reset Windows Backup to Its Factory Settings

 Now you know how to proceed with caution, here's how to reset Windows Backup to its factory settings.

<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Using Command Prompt

 If your current backup configuration isn't working, reset Windows Backup to its default settings. To get started, [run the Command Prompt with admin access](https://www.makeuseof.com/windows-run-command-prompt-admin/). In the Command Prompt window, run the following command:

`reg delete HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup /f`

 This will reset to the default configuration and remove all existing backups.

 After that, copy and paste the following command into the Command Prompt window and press **Enter**:

`reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup`

 This will recreate the WindowsBackup entry in the registry editor. Next, type in and run the below command to delete the Automatic Backup scheduled task on Windows:

`schtasks /delete /tn "Microsoft\Windows\WindowsBackup\AutomaticBackup" /f`

 Finally, execute the below command to delete the backup monitor scheduled task:

`schtasks /delete /tn "Microsoft\Windows\WindowsBackup\Windows Backup Monitor" /f`

 After executing the above commands, restart your computer. This will reset Windows Backup to its default settings.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Creating a Batch File

 If you're not comfortable with the command line interface, reset Windows Backup by creating a batch file.

 To do this, [open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and paste the below code.

`<code>reg delete HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup /f  
reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup  
schtasks /delete /tn "Microsoft\Windows\WindowsBackup\AutomaticBackup" /f  
schtasks /delete /tn "Microsoft\Windows\WindowsBackup\Windows Backup Monitor" /f`

 Click the **File** menu and select **Save as**. On the Save as dialog, type **reset-backup.bat** as the file name. Then choose **All Files** from the drop-down menu next to the Save as type. From the left panel, select **Desktop** and click the **Save** button.

 Now, close the Notepad window and right-click on the batch file. From the context menu, select **Run as administrator**. This will reset Windows Backup to its default settings.

 Lastly, restart your computer and you're done. These are two methods to reset Windows Backup to its default settings.

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
## Get Your Backups Working Again on Windows

 Whether you use the command line interface or create a batch file, it's easy to reset Windows Backup. Just remember to restart your computer after the process completes successfully.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-camera-cuts-quality-is-splitcam-best/"><u>[New] 2024 Approved  Camera Cuts Quality  Is SplitCam Best?</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-silent-strike-sequels-the-next-10-best-samurai-adventures/"><u>[New] 2024 Approved  Silent Strike Sequels  The Next 10 Best Samurai Adventures</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-the-ultimate-tool-list-beyond-sharex/"><u>[New] 2024 Approved  The Ultimate Tool List Beyond ShareX</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-propagate-your-content-with-vimeo-links/"><u>[New] Propagate Your Content with Vimeo Links</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-essential-steps-for-resizing-videos-in-igtv/"><u>[Updated] 2024 Approved  Essential Steps for Resizing Videos in IGTV</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-meme-mastery-in-the-metaverse-a-comedic-journey/"><u>[Updated] Meme Mastery in the Metaverse  A Comedic Journey</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-pinnacle-plotlines-writers-who-changed-film/"><u>[Updated] Pinnacle Plotlines  Writers Who Changed Film</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-pros-hunters-rate-action-camera-winners/"><u>[Updated] Pros Hunters Rate  Action Camera Winners</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-7-best-sbt-to-srtr-conversion-software-for-desktop-use/"><u>2024 Approved  7 Best SBT to SRTR Conversion Software for Desktop Use</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-combatting-iphones-difficulty-in-autofocusing/"><u>2024 Approved  Combatting iPhone's Difficulty in Autofocusing</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-expert-tips-to-triumph-in-spotifys-ad-marketplace/"><u>2024 Approved  Expert Tips to Triumph in Spotify's Ad Marketplace</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-infinix-note-30-drfone-by-drfone-virtual-android/"><u>5 Hassle-Free Solutions to Fake Location on Find My Friends Of Infinix Note 30 | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/adjusting-window-11s-display-a-settled-problem/"><u>Adjusting Window 11'S Display: A Settled Problem</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/beyond-popularity-ten-truths-you-need-to-know-about-instagram-reels/"><u>Beyond Popularity  Ten Truths You Need to Know About Instagram Reels</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-airplane-mode-turn-off-gps-location-on-realme-c55-drfone-by-drfone-virtual-android/"><u>Does Airplane Mode Turn off GPS Location On Realme C55? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/easy-steps-to-locate-recently-viewed-videos-by-you-on-fb-for-2024/"><u>Easy Steps to Locate Recently Viewed Videos by You on FB for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-how-to-activating-hyper-v-for-win11-users/"><u>Essential How-To: Activating Hyper-V for Win11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/evolving-taskbar-in-windows-an-annual-look-back/"><u>Evolving Taskbar in Windows: An Annual Look-Back</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-fix-bluetooth-absence-in-device-mgr/"><u>Guide to Fix Bluetooth Absence in Device Mgr</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/hacks-to-do-pokemon-go-trainer-battles-for-realme-c55-drfone-by-drfone-virtual-android/"><u>Hacks to do pokemon go trainer battles For Realme C55 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-counteract-dxgi-errors-after-device-loss/"><u>How to Counteract DXGI Errors After Device Loss</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-blackouts-during-win-based-gameplay/"><u>How to Fix Blackouts During Win-Based Gameplay</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-properly-utilize-system-restore-on-microsoft-windows/"><u>How to Properly Utilize System Restore on Microsoft Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-realign-read-aloud-settings-on-word-app/"><u>How To Realign Read Aloud Settings on Word App</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-sign-a-wbk-file-document-online-by-ldigisigner-sign-a-word-sign-a-word/"><u>How to Sign a .wbk file document online</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-take-a-screenshot-of-uac-prompts-on-windows/"><u>How to Take a Screenshot of UAC Prompts on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-measures-for-repairing-post-windows-upgrade-failures/"><u>Immediate Measures for Repairing Post-Windows Upgrade Failures</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-a-comprehensive-guide-to-instagram-edits-for-professionals/"><u>In 2024, A Comprehensive Guide to Instagram Edits for Professionals</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-can-you-afford-to-exclude-itop-from-your-setup/"><u>In 2024, Can You Afford to Exclude ITop From Your Setup?</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-elevating-your-content-strategy-youtube-keywords-explained/"><u>In 2024, Elevating Your Content Strategy  YouTube Keywords Explained</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-on-samsung-galaxy-a14-5g-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock on Samsung Galaxy A14 5G Devices</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-next-morning-analysis-fresh-insights/"><u>In 2024, Next Morning Analysis  Fresh Insights</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-ways-to-find-unlocking-codes-for-oppo-find-x7-ultra-phones-by-drfone-android/"><u>In 2024, Ways To Find Unlocking Codes For Oppo Find X7 Ultra Phones</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/lol-gaming-on-air-top-3-recording-methods-for-2024/"><u>LOL Gaming On Air  Top 3 Recording Methods for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-vmware-start-issues-on-windows-11plusoses/"><u>Mastering VMware Start Issues on Windows 11+OSes</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-free-video-orientation-correction-top-10-tools-for-rotating-and-flipping/"><u>New 2024 Approved Free Video Orientation Correction Top 10 Tools for Rotating and Flipping</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-file-access-harness-the-power-of-win11s-checkboxes/"><u>Optimize File Access: Harness the Power of Win11's Checkboxes</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-steams-missing-files-hurdle-on-win11-os/"><u>Overcoming Steam's Missing Files Hurdle on Win11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/reconfigure-windows-11-task-manager-interface-view/"><u>Reconfigure Windows 11 Task Manager Interface View</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-from-disrupted-asana-use-a-focused-approach-for-pc-users/"><u>Recovering From Disrupted Asana Use: A Focused Approach for PC Users</u></a></li>
<li><a href="https://windows11.techidaily.com/regain-access-to-hidden-5ghz-networks-on-your-windows-pc/"><u>Regain Access to Hidden 5GHz Networks on Your Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-for-save-failed-error-on-windows-systems/"><u>Remedy for Save Failed Error on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-zoom-crash-code-1132-in-windows-os/"><u>Resolving Zoom Crash Code: 1132 in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/skirting-microsofts-app-verification-system-on-pc/"><u>Skirting Microsoft's App Verification System on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-frozen-grammarly-on-your-computer-system/"><u>Solving Frozen Grammarly on Your Computer System</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-fix-xbox-game-download-failures-on-pc/"><u>Steps to Fix Xbox Game Download Failures on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-recover-from-a-blank-login-display-window/"><u>Steps to Recover From a Blank Login Display Window</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-undoing-changes-to-windows-app-configurations/"><u>Swiftly Undoing Changes to Windows App Configurations</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-disk-read-failed-problem/"><u>Tackling the “Disk Read Failed” Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/top-tools-that-makes-your-laptops-os-change-more-manageable/"><u>Top Tools that Makes Your Laptop's OS Change More Manageable</u></a></li>
<li><a href="https://windows11.techidaily.com/top-windows-improvements-what-to-expect-from-feb23/"><u>Top Windows Improvements: What to Expect From Feb23</u></a></li>
<li><a href="https://windows11.techidaily.com/transformative-tools-in-the-studio-4-microsoft-paint-redesigns/"><u>Transformative Tools in the Studio: 4 Microsoft Paint Redesigns</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-code-0x0001-for-nvidia-experience-in-windows/"><u>Troubleshooting Code 0X0001 for Nvidia Experience in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-the-store-error-a-fix-for-windows-x800704cf/"><u>Unblocking the Store Error: A Fix for Windows' X800704CF</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-full-potential-of-your-systems-ram-with-windows/"><u>Unlocking the Full Potential of Your System's RAM with Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-secrets-to-windows-camera-media-storage/"><u>Unlocking the Secrets to Windows Camera Media Storage</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-undetected-toolbar-for-windows-11-users/"><u>Unlocking the Undetected Toolbar for Windows 11 Users</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/unveiling-the-art-of-personal-branding-mastery-for-2024/"><u>Unveiling the Art of Personal Branding Mastery for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-power-of-cross-platform-note-taking-in-win11/"><u>Unveiling the Power of Cross-Platform Note Taking in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-of-windows-process-aggregatehostexe/"><u>Unveiling the Secrets of Windows' Process AggregateHost.exe</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/various-methods-to-transfer-pictures-from-apple-iphone-xr-to-pc-drfone-by-drfone-transfer-from-ios/"><u>Various Methods to Transfer Pictures from Apple iPhone XR to PC | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>