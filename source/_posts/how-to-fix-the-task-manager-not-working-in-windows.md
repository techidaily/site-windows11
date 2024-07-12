---
title: How to Fix the Task Manager Not Working in Windows
date: 2024-07-11T21:11:57.694Z
updated: 2024-07-12T21:11:57.694Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the Task Manager Not Working in Windows
excerpt: This Article Describes How to Fix the Task Manager Not Working in Windows
keywords: TaskMgrTroubleFix,WinTaskErrorSolve,WindowsManagerIssue,UnresponsiveTaskWin,TaskBarNonResponsive,FixWindowsTaskbar,ResolveTaskManageFail
thumbnail: https://thmb.techidaily.com/1a71493edba37cb030611c5a8b9738f6d63a9069f2561431aa2bb888dda851d0.jpg
---

## How to Fix the Task Manager Not Working in Windows

 Task Manager is one of the most important Windows 11/10 system utilities. So, it’s a big issue when Task Manager is not working. Some users have reported Task Manager not opening (working) for them when they try to access it.

 Task Manager might throw up an error message or simply not respond when it’s not working. Task Manager opens with a blank window and crashes soon after for some users. Users can’t utilize Task Manager when it’s not working. This is how you can fix Task Manager not working on a Windows 11/10 PC.

## 1\. Run System File and Image Repair Commands

 Many users have confirmed running system file and image repair commands can fix the Task Manager not working. So, that’s one of the first things you should try for fixing Task Manager when it’s not opening.

 To apply this potential solution, you’ll need to input separate Command Prompt commands for running the DISM (Deployment Image Servicing and Management) and SFC (System File Checker) tools. The SFC tool repairs system files and DISM services the Windows image.

 Follow the instructions in our article about [repairing corrupted Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) to run the SFC and DISM command-line tools.

![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/sfc-scannow-command2.jpg)

## 2\. Disable the Remove Task Manager Policy

 Group Policy Editor includes an option for disabling Task Manager. If you see an error message that states Task Manager is disabled, that option is likely enabled. Even if you don’t see an error message, you should still check the **Remove Task Manager** policy if you can access Group Policy Editor on your PC. This is how you can disable the **Remove Task Manager** policy:

1. [Open Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) on your Windows PC. If you're on Windows Home, you'll need to learn [how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) first.
2. Double-click **User Configuration** \> **Administrative Templates** \> **System** \> **Ctrl + Alt + Del Options** in Group Policy Editor’s sidebar.  
![The Ctrl+Alt+Del Options policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/remove-task-manager-policy.jpg)
3. Next, double-click **Remove Task Manager** to view a window for configuring that policy.
4. Select **Disabled** or **Not Configured** if you find this policy enabled.  
![The Remove Task Manager window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/remove-task-manager-window.jpg)
5. Click **Apply** to set the new option for enabling Task Manager.
6. Then close the Remove Task Manager window by clicking **OK**.

 If this policy is not enabled, try turning it on and off. Click **Enabled** and **Apply** to activate the policy. Then select **Disabled**/**Not configured** to disable it.

## 3\. Initiate an Antivirus Scan

 Malware can sometimes be the reason for the Task Manager not working. Task Manager is targeted by malware because it’s an important system utility. So, [run an antivirus scan](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) with Windows Security or third-party security software to check for and purge malware from your PC. Select the most thorough antivirus scanning option in whatever option you utilize.

![The antivirus scan options in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/scan-now-option.jpg)

## 4\. Edit the Policies Key

 Note that running an antivirus scan might only eliminate the cause of this issue. Then you would still need to re-enable Task Manager to get it working after purging malware that disabled it. A virus will have likely disabled Task Manager in the registry. You can re-enable the Task Manager by editing the Policies registry key like this:

1. To access Registry Editor, press the **Windows key + S** key combination, enter a **regedit** keyword, and click the matching result shown in the search tool.
2. Next, go to the **Policies** key by inputting this path inside the registry address bar:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies`
3. Skip to step seven if you can see a **System** subkey. If you can’t, right-click **Policies** and select **New** \> **Key**.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-key-options.jpg)
4. Enter **System** in the new key’s text box.
5. Right-click **System** and select **New** \> **DWORD**.

1. Input **DisableTaskMgr** inside the DWORD’s text box.
2. Double-click the **DisableTaskMgr** DWORD within the **System** key.  
![The DisableTaskMgr DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disabletskmgr-dword.jpg)
3. The value for the **DisableTaskMrg** DWORD should be **0**. If it’s set any differently, erase the number in the **Value** box and input **0**.
4. Click **OK** to set the **DisableTaskMgr** value.  
![The Edit DWORD (32-bit) Value window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-edit-dword-window.jpg)
5. Now close the Registry Editor. To ensure the changes take effect, [restart your Windows PC](https://www.makeuseof.com/windows-restart-methods/) after editing the registry.

## 5\. Run the PowerShell Command for Re-Registering Apps

 Some users say they managed to fix Task Manager by running a PowerShell command for reinstalling and registering built-in Windows 11/10 apps. If that worked for them, maybe this resolution will fix Task Manager not working on your PC. This is how you can run that PowerShell command:

1. Activate the **Type here to search** box by utilizing the **Windows key + S** keyboard shortcut.
2. Enter **PowerShell** inside the file search box.
3. Click **Run as administrator** for the matching PowerShell app search result.
4. Input this command:  
`Get-AppXPackage | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The PowerShell command that can fix Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-reinstall-apps-command.jpg)
5. Press **Enter** to execute the command and wait for it to finish before exiting PowerShell.

## 6\. Change Your User Account

 Windows user account issues can also cause Task Manager to stop working. For example, your user account might be corrupted in some way. In this case, you can try to repair the corrupted user account or set up an entirely new one. Task Manager might work fine in a new user account.

 First, set up a new user account and sign into it to see if Task Manager works there. If it does, transfer all the user files from your old Windows account to the new one. Our guide to [fixing Windows issues by creating new accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) includes instructions for applying this troubleshooting method.

![The Add account button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/add-account-button.jpg)

## 7\. Restore Windows to an Earlier Time

 The System Restore tool can address some of the potential causes for Task Manager not working if you have it enabled. Much depends on whether you can select a restoration point that will roll Windows back to a date when Task Manager worked okay. If you can, rolling Windows back to an earlier time is worth a try when other potential solutions are ineffective.

 Our article about [how to utilize System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) tells you how to apply this potential fix. Choose a restoration point that will restore Windows to a time when you could utilize Task Manager without issues. You’ll need to reinstall desktop software and apps installed after a chosen restore point.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/system-restore-window.jpg)

## 8\. Reset Your Window PC

 This final resolution for the Task Manager not working is the most nuclear of the lot. Resetting Windows 11/10 will restore the platform to factory default settings by reinstalling it, which will obliterate malware and repair system file issues. It’s recommended as a last resort since resetting Windows will wipe out all the software you’ve installed.

 You can apply this potential resolution with the Reset this PC tool, as covered in this article about [resetting Windows 10 or 11](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/#:~:text=To%20access%20this%20Windows%20reinstall,this%20PC%20to%20get%20started.). There’s no need to back up user files since you can select a **Keep my files** option within the Reset this PC window. Make sure the **Reinstall preinstalled apps** option is selected to retain the software bundled with your PC.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/reset-this-pc-tool.jpg)

## Use Task Manager Within Windows Again

 Task Manager is not something most users can do without. Fortunately, the potential resolutions in this guide will likely resolve many of the Task Manager issues that prevent users from opening and utilizing that utility. At least one will probably kick-start Task Manager on your PC, enabling you to use that tool as required again.

 Task Manager might throw up an error message or simply not respond when it’s not working. Task Manager opens with a blank window and crashes soon after for some users. Users can’t utilize Task Manager when it’s not working. This is how you can fix Task Manager not working on a Windows 11/10 PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/dismantling-tpm-in-win11-using-the-power-of-rufus/"><u>Dismantling TPM in Win11 Using the Power of Rufus</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-top-insights-on-maximizing-business-engagement-on-insta/"><u>2024 Approved  Top Insights on Maximizing Business Engagement on Insta</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-facebooks-brief-broadcasts-unpacked/"><u>[New] In 2024, Facebook's Brief Broadcasts Unpacked</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-controlled-temperature-policy-on-windows-pcs/"><u>Setting up Controlled Temperature Policy on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/the-simple-trick-to-finding-your-installed-application-home/"><u>The Simple Trick to Finding Your Installed Application Home</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-elevating-your-media-adding-compelling-audio-elements-to-videos/"><u>2024 Approved Elevating Your Media Adding Compelling Audio Elements to Videos</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-the-art-of-image-enhancement-pivotal-pixlr-insights/"><u>2024 Approved  The Art of Image Enhancement  Pivotal Pixlr Insights</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/snapchat-savvy-elevating-your-photographic-style-with-app-edits/"><u>Snapchat Savvy  Elevating Your Photographic Style with App Edits</u></a></li>
<li><a href="https://extra-support.techidaily.com/mastering-sound-communication-on-whatsapp-for-2024/"><u>Mastering Sound Communication on WhatsApp for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/ultimate-guide-top-screen-capture-tools-roundup-for-2024/"><u>Ultimate Guide  Top Screen Capture Tools Roundup for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/tactical-aid-for-windows-issues-in-googles-nearby-share-app/"><u>Tactical Aid for Windows Issues in Google's Nearby Share App</u></a></li>
<li><a href="https://youtube-help.techidaily.com/how-to-flip-your-video-collection-in-a-flash-for-2024/"><u>How to Flip Your Video Collection in a Flash for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-prevent-and-fix-windows-error-code-0xc00000f/"><u>Strategies to Prevent & Fix Windows Error Code 0Xc00000f</u></a></li>
<li><a href="https://vp-tips.techidaily.com/accelerating-or-decelerating-mastering-snapchats-timeline-controls-for-2024/"><u>Accelerating or Decelerating  Mastering Snapchat's Timeline Controls for 2024</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/google-translate-video-a-complete-guide-to-translate-video-with-google-for-2024/"><u>Google Translate Video A Complete Guide To Translate Video With Google for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-versatility-top-10-innovative-ways-to-use-powertoys-tools/"><u>Discover Versatility: Top 10 Innovative Ways to Use PowerToys Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-alternate-pdf-reader-on-windows/"><u>Configuring Alternate PDF Reader on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-abrupt-game-closure-in-roblox-fix-tips-for-pc-users/"><u>Avoiding Abrupt Game Closure in Roblox: Fix Tips for PC Users</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-motorola-moto-g-5g-2023-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Motorola Moto G 5G (2023) Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-choosing-the-right-medium-audio-vs-video-based-platforms/"><u>[New] Choosing the Right Medium  Audio vs Video-Based Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-the-setup-of-new-non-operational-store-programs/"><u>Streamlining the Setup of New, Non-Operational Store Programs</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-shortcut-for-character-viewing/"><u>Windows 11 Shortcut for Character Viewing</u></a></li>
<li><a href="https://windows11.techidaily.com/7-festive-tweaks-to-personalize-your-windows-11/"><u>7 Festive Tweaks to Personalize Your Windows 11</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-how-to-fix-obs-camera-not-working/"><u>2024 Approved  How to Fix OBS Camera Not Working</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-unlocking-the-potential-of-recording-google-voice-calls-for-2024/"><u>[Updated] Unlocking the Potential of Recording Google Voice Calls for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-catch-or-beat-sleeping-snorlax-on-pokemon-go-for-infinix-note-30-vip-drfone-by-drfone-virtual-android/"><u>In 2024, Catch or Beat Sleeping Snorlax on Pokemon Go For Infinix Note 30 VIP | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11-for-optimal-clipchamp-functionality/"><u>Unlocking Windows 11 for Optimal ClipChamp Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-fix-absent-app-in-windows-filesystem/"><u>Strategies to Fix Absent App in Windows Filesystem</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-tab-issue-solutions-for-non-responsive-keys/"><u>Windows Tab Issue: Solutions for Non-Responsive Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-old-user-credentials-issue-on-win-11-os/"><u>Clearing Up 'Old User Credentials' Issue on Win 11 OS</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-watch-local-videos-on-chromecast-a-comprehensive-guide-for-windows-mac-android-and-ios-users/"><u>Updated In 2024, Watch Local Videos on Chromecast A Comprehensive Guide for Windows, Mac, Android, and iOS Users</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-restoring-icon-clarity-on-your-pcs-desktop/"><u>Tips for Restoring Icon Clarity on Your PC's Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/decreasing-the-impact-of-high-cpu-tiworkerexe-applications/"><u>Decreasing the Impact of High-CPU TiWorker.exe Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/syncing-sound-levels-across-windows-and-bt-audio-gear/"><u>Syncing Sound Levels Across Windows and BT Audio Gear</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/best-vertical-video-apps-for-ios-and-android-for-2024/"><u>Best Vertical Video Apps for iOS and Android for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-pc-to-apple-iphone-14-drfone-by-drfone-ios/"><u>How to Mirror PC to Apple iPhone 14? | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-simplify-macbook-screen-capture-for-beginners/"><u>[Updated] 2024 Approved  Simplify MacBook Screen Capture for Beginners</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-powertoys-worldwide-mouse-capabilities/"><u>Unlock PowerToy's Worldwide Mouse Capabilities</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-nubia-red-magic-9-pro-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Nubia Red Magic 9 Pro If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-editing-gopro-videos-on-pc-quik-alternatives-and-more/"><u>New 2024 Approved Editing GoPro Videos on PC Quik, Alternatives, and More</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-photographers-choice-top-10-watermarks-software/"><u>[New] Photographer's Choice  Top 10 Watermarks Software</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/navigating-advanced-features-in-obs-studio-android-for-2024/"><u>Navigating Advanced Features in OBS Studio (Android) for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-policy-settings-with-proven-gpo-update-methods/"><u>Streamlining Policy Settings with Proven GPO Update Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/detailed-guide-extracting-device-ids-on-windows-pcs/"><u>Detailed Guide: Extracting Device IDs on Windows PCs</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-fake-gps-without-root-on-tecno-spark-20-proplus-drfone-by-drfone-virtual-android/"><u>3 Ways to Fake GPS Without Root On Tecno Spark 20 Pro+ | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-wired-internet-beyond-100mbps-in-windows/"><u>Accelerating Wired Internet Beyond 100Mbps in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-breakdown-using-toolbar-in-mspcm-on-windows-11/"><u>Comprehensive Breakdown: Using Toolbar in MSPCM on Windows 11</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-mastering-tiktok-with-its-top-7-emojis-a-beginners-handbook/"><u>[New] In 2024, Mastering TikTok with Its Top 7 Emojis  A Beginner's Handbook</u></a></li>
<li><a href="https://windows11.techidaily.com/breathing-life-into-winget-a-windows-11-solution/"><u>Breathing Life Into Winget: A Windows 11 Solution</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-2-ways-to-transfer-text-messages-from-vivo-y36-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 2 Ways to Transfer Text Messages from Vivo Y36 to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-audio-error-devices-being-used-by-non-targeted-apps/"><u>Clearing Up Audio Error: Devices Being Used by Non-Targeted Apps</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/about-vivo-y78plus-frp-bypass-by-drfone-android/"><u>About Vivo Y78+ FRP Bypass</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-correcting-malwarebytes-call-failure-in-win11win10/"><u>Steps for Correcting Malwarebytes Call Failure in Win11/Win10</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-nearby-share-for-file-transfers/"><u>Understanding Nearby Share for File Transfers</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-strength-of-details-why-hdr-triumphs-over-sdr/"><u>The Strength of Details  Why HDR Triumphs Over SDR</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-your-workflow-with-windows-11s-widget-toolbar/"><u>Boost Your Workflow with Windows 11'S Widget Toolbar</u></a></li>
<li><a href="https://windows11.techidaily.com/your-missing-flight-tech-copilot-in-new-os/"><u>Your Missing Flight Tech (Copilot) in New OS?</u></a></li>
<li><a href="https://windows11.techidaily.com/stealth-mode-disabling-windows-wi-fi-broadcast/"><u>Stealth Mode: Disabling Windows Wi-Fi Broadcast</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-tiktok-bgs-exploring-affordable-eye-catching-visuals/"><u>In 2024, TikTok BGs  Exploring Affordable, Eye-Catching Visuals</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-free-vs-paid-gaming-entrances-top-12-insights-for-youtube-gamers/"><u>[New] 2024 Approved  Free vs Paid Gaming Entrances  Top 12 Insights for YouTube Gamers</u></a></li>
<li><a href="https://howto.techidaily.com/app-wont-open-on-your-oneplus-nord-3-5g-here-are-all-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>App Wont Open on Your OnePlus Nord 3 5G? Here Are All Fixes | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-tackle-icons-not-aligned/"><u>Win 11: Tackle Icons Not Aligned</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-10-password-cracking-tools-for-xiaomi-13t-pro-by-drfone-android/"><u>Top 10 Password Cracking Tools For Xiaomi 13T Pro</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-teach-you-to-transfer-files-from-samsung-galaxy-f54-5g-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways To Teach You To Transfer Files from Samsung Galaxy F54 5G to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/unmasking-windows-hidden-chronicle-view-clean-up/"><u>Unmasking Windows' Hidden Chronicle - View, Clean Up!</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-wows-abrupt-server-quit-error-132-in-win11/"><u>Solutions for WoW's Abrupt Server Quit (Error 132) in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-common-issues-with-windows-shared-printers/"><u>Solving Common Issues with Windows Shared Printers</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-mastering-maccam-easy-webcam-recordings/"><u>In 2024, Mastering MacCam  Easy Webcam Recordings</u></a></li>
</ul></div>
