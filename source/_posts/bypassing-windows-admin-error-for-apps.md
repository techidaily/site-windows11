---
title: Bypassing Windows Admin Error for Apps
date: 2024-07-11T21:15:51.343Z
updated: 2024-07-12T21:15:51.343Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bypassing Windows Admin Error for Apps
excerpt: This Article Describes Bypassing Windows Admin Error for Apps
keywords: Bypass Error Windows,Win Error Handling,Admin Access Bypass,Applications Override,Error Bypass Techniques,Windows App Override,Avoiding Admin Errors
thumbnail: https://thmb.techidaily.com/6dfe7c6db7f80e87ac6b399dc687e52e1d331efd7fce0bd5f581a2c33f337372.jpg
---

## Bypassing Windows Admin Error for Apps

 User Account Control on Windows prevents unauthorized changes to your computer. This, however, can cause issues with genuine apps and block them from running.

 This app has been blocked by your system administrator error is triggered if your account doesn't have admin rights. Other reasons include issues with User Account Control and Microsoft Defender SmartScreen blocking the app.

 To fix the problem, perform a quick restart of your computer. If the issue persists after the restart, follow these steps to fix the This app has been blocked by your system administrator error on Windows.

## 1\. Unblock the App Executable

![unblocking a file in Properties on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unblock-file-properties-windows.jpg)

 Windows can automatically block apps downloaded from the internet from running your computer. This is a safety measure intended to protect your system against apps from unknown publishers.

 If you trust the publisher, you can manually unblock the file and run it without the error.

To unblock an app on Windows:

1. Locate and right-click on the app's executable and select**Properties** .
2. In the**Properties** dialog, open the**General** tab.
3. In the**Secure** section, check the**Unblock** option.
4. Click**Apply** and**OK** to save the changes.
5. Launch the app again to see if the error is resolved.

## 2\. Run the App Using the Command Prompt

 You can run and launch apps using Command Prompt on Windows. All you need is a file path followed by the file name. Command Prompt offers a faster way to open apps on Windows; however, you can also use it if you can't open an app from File Explorer.

To open Windows apps using Command Prompt:

1. Right-click on the app shortcut and select**Open File Location** .
2. Next, right-click on the**app.exe** file and select**Properties** .  
![Windows file properties file path location](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-file-properties-file-path-location.jpg)
3. In the Properties dialog, open the**Genera** l tab.
4. Copy the file path shown as**Location** .
5. On Windows 11, right-click on the .exe file and select**Copy as File Path** .  
![run program using command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-program-using-command-prompt.jpg)
6. Next, press the**Win** key and type**cmd** .
7. Right-click on**Command Prompt** , and select**Run as administrator.**
8. Next, press**Ctrl + V** to paste the copied file path in Command Prompt. Make sure to add the .exe file name at the end of the file path.
9. Press**Enter** to launch the app.

## 3\. Run the Apps as an Administrator

![run minecraft as administrator windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-minecraft-as-administrator-windows-11.jpg)

 Some Windows apps may need administrator privileges to work correctly. To fix the error, run the app as an administrator. If it works, you can configure the app properties to always run as administrator.

To run an app as an administrator:

1. Right-click on the app icon and select**Run as administrator** .
2. Click**Yes** if prompted by User Account Control.

 Check if the app launches ad administrator without the error. If yes, you can [set the app to always run as administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) to fix the issue. That said, do this only if you trust the publisher for security reasons.

## 4\. Repair or Reset the Microsoft Store Apps

 If the error is triggered when opening a Microsoft Store app, try to perform a repair. You can repair Microsoft Store apps from the Settings panel. This should fix temporary glitches with the app and resolve the error.

To repair a Microsoft Store app:

![repair photos app windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/repair-photos-app-windows-11.png)

1. Press**Win + I** to open**Settings** .
2. Open the**Apps** tab and click on**Installed Apps** .
3. Search and locate the app you want to repair.
4. Click the**three-dots menu** next to the app name and select**Advanced Options** .
5. Scroll down and click on the**Repair** button. Wait as Windows repairs the app; you will see a green check mark indicating the repair is complete.

 Once done, launch the app and check if the error is resolved. If you see the error again, try to reset the app.

Reset the Microsoft Store app:

![reset-microsoft-teams-windows-11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-microsoft-teams-windows-11.jpg)

 Resetting an app will delete its data, including sign-in details and preferences.

1. Press**Win + I** to open**Settings** .
2. Open the**Apps** tab and click on**Installed Apps** .
3. Click the**three-dots menu** near the app name and select**Advanced options** .
4. Scroll down and click the**Reset** button. Click**Reset** again to confirm the action. Similar to Repair, you'll see a checkmark when the reset process is complete.

## 5\. Disable Microsoft Defender SmartScreen

 Microsoft Defender's SmartScreen scans programs and files during the launch for potential threats and can block them from running. You can disable the SmartScreen feature temporarily to determine if your app is blocked by it.

 You can [disable Microsoft SmartScreen Filter on Windows](https://www.makeuseof.com/windows-smartscreen-filter-enable-disable/) using the Windows Security app. Once disabled, relaunch the app and check if the error is resolved.

## 6\. Turn Off Your Antivirus Program

 False positives from Antivirus programs are not uncommon. Whether you are using Microsoft Windows Defender or another antivirus program, turn off the security program temporarily to determine if your antivirus blocking the app.

 You can [temporarily disable Microsoft Defender](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) using the Windows Security app. To turn off third-party antivirus, right-click the app icon in the system tray and select the appropriate options.

 If the error is resolved, add the app to your security program's allowed list. You can also [allowlist files and apps on Windows Defender](https://www.makeuseof.com/how-to-whitelist-files-windows-defender/) if you use it as the primary security application.

## 7\. Modify the Windows Registry to Remove Admin Block

 User Account Control settings are another common trigger for the This app has been blocked by your system administrator error. You can modify the User Account Control settings in Registry Editor to remove the admin block and resolve the error.

 Making incorrect modifications to the Windows Registry can cause your system to malfunction. Make sure to [create a Windows registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) , and a [system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed with the steps below.

To remove the admin block using Registry Editor:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open Registry Editor. Click**Yes** , if prompted by User Account Control.
3. In Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies`
4. Select the**System** subkey under**Policies** .
5. In the right pane, locate**EnableLUA** .  
![enable lua modify registry editor windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-lua-modify-registry-editor-windows.jpg)
6. Right-click on the**EnableLUA** value and select**Modify** .
7. Type**0** in the**Value data** field and click**OK** to save the changes.  
![enable lua modify registry editor value 0 windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-lua-modify-registry-editor-value-0-windows.jpg)
8. Close Registry Editor and restart your computer to apply the changes. After the restart, launch the app to see if the error is resolved.
9. If you are using a school or work computer, your organization may put some restrictions on its use. If you can't find the UAC settings, contact your IT administrator to resolve the issue.

## Unblock the Apps Blocked by Your System Administrator

 Security settings on your Windows computer can often block suspicious apps and trigger the This app has been blocked by your system administrator message. To resolve the issue, check and unblock the app in file properties. Also, turn off the SmartScreen filter and your antivirus solution.

 Reconfiguring your UAC settings in Registry Editor is another way to resolve the problem. If all else fails, the restrictions may have been put in place by guardians or the school or work administration.


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
<li><a href="https://windows11.techidaily.com/how-to-fix-the-local-security-authority-protection-is-off-security-warning-on-windows/"><u>How to Fix the “Local Security Authority Protection Is Off” Security Warning on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-extend-the-pin-length-in-windows-11-and-11/"><u>How to Extend the PIN Length in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reset-chronology-fix-windows-time-errors/"><u>Reset Chronology: Fix Windows Time Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/the-elusive-guide-to-unseen-menu-adjustments-windows-style/"><u>The Elusive Guide to Unseen Menu Adjustments, Windows Style</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-synthesize-shots-the-photo-montage-methodology/"><u>In 2024, Synthesize Shots  The Photo Montage Methodology</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-free-easy-to-use-online-editors-for-quick-postings/"><u>[New] 2024 Approved  Free, Easy-to-Use Online Editors for Quick Postings</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-set-up-troubleshooter-shortcuts-in-windows-11-and-11/"><u>How to Set Up Troubleshooter Shortcuts in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/granting-correct-permissions-to-solve-windows-installer-error/"><u>Granting Correct Permissions to Solve Windows Installer Error</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-foremost-dialogue-maker-hub/"><u>[Updated] 2024 Approved  Foremost Dialogue Maker Hub</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/efficient-resurrection-for-lost-images/"><u>Efficient Resurrection for Lost Images</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windowsstore-app-folder-hidden-entry-points/"><u>Unveiling WindowsStore App Folder Hidden Entry Points</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-superior-editors-for-stellar-webcam-videos/"><u>In 2024, Superior Editors for Stellar Webcam Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-your-console-dreams-choose-windows-for-games/"><u>Unlocking Your Console Dreams: Choose Windows for Games</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-crafting-compelling-videos-the-instagram-editors-playbook-for-2024/"><u>[New] Crafting Compelling Videos  The Instagram Editor's Playbook for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-memory-management-in-new-os/"><u>Mastering Memory Management in New OS</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-the-essential-blueprint-crafting-memes-that-perform-on-social-networks/"><u>[New] The Essential Blueprint  Crafting Memes That Perform on Social Networks</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-framing-brilliance-nikon-d500s-high-definition-journey/"><u>[New] Framing Brilliance  Nikon D500's High-Definition Journey</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-application-failure-the-notorious-error-the-application-couldnt-start-xc000003e-on-win11-and-11/"><u>Navigating Application Failure: The Notorious Error The Application Couldn’t Start Xc000003e on Win11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-office-suites-strict-safe-mode-on-windows-operations/"><u>Troubleshooting Office Suite's Strict Safe Mode on Windows Operations</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-infinix-smart-7-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>How to Unlock Infinix Smart 7 Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://windows11.techidaily.com/what-purpose-does-a-directory-like-windows-bt-serve/"><u>What Purpose Does a Directory Like Windows ~BT Serve?</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-photo-wizardry-made-easy-mastering-slideshow-creation-and-spot-repair/"><u>Windows 11'S Photo Wizardry Made Easy: Mastering Slideshow Creation & Spot Repair</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-device-control-for-sleep-state-wakefulness/"><u>Unlocking Device Control for Sleep State Wakefulness</u></a></li>
<li><a href="https://windows11.techidaily.com/howtodarkennotepadwindesktop/"><u>HowToDarkenNotepadWinDesktop</u></a></li>
<li><a href="https://windows11.techidaily.com/investigating-and-fixing-create-failed-on-windows-error-30005/"><u>Investigating and Fixing Create Failed on Windows Error 30005</u></a></li>
<li><a href="https://windows11.techidaily.com/unfreezing-and-reviving-windows-11s-stuck-media-player/"><u>Unfreezing and Reviving Windows 11'S Stuck Media Player</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/instavideo-magic-crafting-a-plan-to-capture-your-audiences-attention-for-2024/"><u>InstaVideo Magic  Crafting a Plan to Capture Your Audience's Attention for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-window-gloss-your-guide-to-a-clearer-taskbar-in-win11/"><u>Mastering Window Gloss: Your Guide to a Clearer Taskbar in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/restore-and-revitalize-13-ways-to-rejuvenate-windows-systems/"><u>Restore & Revitalize: 13 Ways to Rejuvenate Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-your-subnet-in-the-latest-os-win11/"><u>Optimizing Your Subnet in the Latest OS: Win11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/prime-shopping-destinations-customizable-presents-with-flair/"><u>Prime Shopping Destinations  Customizable Presents with Flair</u></a></li>
<li><a href="https://windows11.techidaily.com/restore-full-size-to-your-windows-11-icons/"><u>Restore Full Size to Your Windows 11 Icons</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-top-10-iphone-video-capture-apps/"><u>[New] Top 10 iPhone Video Capture Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/visualize-resource-consumption-windows-tray-update-guide/"><u>Visualize Resource Consumption: Windows Tray Update Guide</u></a></li>
<li><a href="https://win11.techidaily.com/dont-overlook-the-side-effects-of-bargain-windows-keys/"><u>Don't Overlook: The Side Effects of Bargain Windows Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-non-existence-of-powershell-in-windows/"><u>Tackling the Non-Existence of PowerShell in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-efface-license-end-soon-warning-from-your-pc/"><u>How To Efface License End Soon Warning From Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-correct-hardware-detection-errors-in-win/"><u>How To Correct Hardware Detection Errors in Win</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-complete-guide-to-producing-high-quality-gopro-time-lapse/"><u>[New] The Complete Guide to Producing High-Quality GoPro Time-Lapse</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-realme-gt-neo-5-se-drfone-by-drfone-virtual-android/"><u>In 2024, How to get the dragon scale and evolution-enabled pokemon On Realme GT Neo 5 SE? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-microsoft-m365-glitch-with-code-30015-26/"><u>Remedy Microsoft M365 Glitch with Code 30015-26</u></a></li>
<li><a href="https://windows11.techidaily.com/securely-clearing-email-details-post-login/"><u>Securely Clearing Email Details Post-Login</u></a></li>
<li><a href="https://windows11.techidaily.com/proven-strategies-for-comprehensible-comic-consumption-on-win11/"><u>Proven Strategies for Comprehensible Comic Consumption on Win11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-top-picks-for-the-modern-buyer-advanced-360cams/"><u>[New] Top Picks for the Modern Buyer  Advanced 360Cams</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-this-file-is-alone-error-on-pcs/"><u>Overcoming This File Is Alone Error on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-snipping-tool-activation-from-pressing-prtscn-in-11/"><u>How to Stop Snipping Tool Activation From Pressing PrtScn in 11</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-multi-user-printer-errors-windows-11-guide/"><u>Handling Multi-User Printer Errors: Windows 11 Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-disabling-windows-surrounders/"><u>Guide to Disabling Windows Surrounders</u></a></li>
<li><a href="https://windows11.techidaily.com/optimal-system-settings-reducing-resource-drain-while-playing/"><u>Optimal System Settings: Reducing Resource Drain While Playing</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-top-10-luts-for-adobe-lightroom/"><u>In 2024, Top 10 LUTs for Adobe LightRoom</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-se-2022-to-other-iphone-14-pro-max-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone SE (2022) to other iPhone 14 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/make-your-windows-life-easier-with-proper-installation-steps/"><u>Make Your Windows Life Easier with Proper Installation Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/1719261046850-experience-gptclone-at-home-for-free-on-windows/"><u>Experience GPTClone at Home for FREE on Windows</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-image-innovation-for-windows-and-mac-photo-to-cartoon-software/"><u>2024 Approved  Image Innovation for Windows & Mac  Photo-to-Cartoon Software</u></a></li>
<li><a href="https://windows11.techidaily.com/1719293285605-windows-11-woes-re-opening-chrome-made-simple/"><u>Windows 11 Woes: Re-Opening Chrome Made Simple.</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-hasten-haste-in-videos-with-top-apps-android/"><u>2024 Approved  Hasten Haste in Videos with Top Apps, Android</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-2024-approved-blur-your-video-for-free-no-software-required/"><u>Updated 2024 Approved Blur Your Video for Free No Software Required</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-fix-auto-lock-greyed-out-on-iphone-15-pro-max-by-drfone-ios/"><u>In 2024, How To Fix Auto Lock Greyed Out on iPhone 15 Pro Max</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-innovative-practices-for-distinguished-music-video-production/"><u>New In 2024, Innovative Practices for Distinguished Music Video Production</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-for-resolving-missing-drivers-alert-on-windows-setup/"><u>Guidelines for Resolving Missing Drivers Alert on Windows Setup</u></a></li>
</ul></div>
