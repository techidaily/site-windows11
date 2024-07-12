---
title: Circumventing Windows Security Controlled by Domain Admins
date: 2024-07-11T21:50:37.633Z
updated: 2024-07-12T21:50:37.633Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Circumventing Windows Security Controlled by Domain Admins
excerpt: This Article Describes Circumventing Windows Security Controlled by Domain Admins
keywords: Bypassing Admin Windows Access,Defying PC Admin Restrictions,Evading Admin-Controlled Windows,Eluding Authorized Windows Security,Circumventing Domain Admin Safeguards,Skirting Admin Windows Policy,Overriding Admin Windows Permissions
thumbnail: https://thmb.techidaily.com/19529825bc864f6a7105eee056c51264b322fc80a0ff9dab5d25b004c909ef6a.jpg
---

## Circumventing Windows Security Controlled by Domain Admins

 Some users have reported they can’t set Windows Security options because of an error that says, “This setting is managed by your administrator.” Those users see that error message just above options within the**Virus & threat protection** and**App & browser tabs** of that app. Consequently, they can’t turn on important Windows Security settings there that are grayed out and disabled.

 That issue has little to do with admin rights. Many users who encounter the issue are already utilizing Windows administrator accounts. This is how you can fix the “setting is managed by your administrator” error in Windows 11.

## 1\. Check for and Install Available Windows 11 Updates

 Although not the most likely potential solution, some users have said installing available Windows 11 updates helped them resolve this error. Patchers for Windows 11 usually address Windows bugs reported by users.

 If you're not sure how to do this, visit [how to install Windows 11 updates](https://www.makeuseof.com/windows-11-install-updates/) for a step-by-step guide.

## 2\. Reset the Windows Security and Settings Apps

 Users who’ve fixed the “setting is managed by your administrator” error have confirmed resetting the Windows Security and Settings apps can work. Resetting those apps will clear their data. You can reset Windows Security via Settings, as outlined in our [how to reset apps on Windows](https://www.makeuseof.com/windows-reset-app/) guide.

![The Reset button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reset-option.jpg)

 To reset Settings, you must open the Start menu and right-click the app’s shortcut. Select**App settings** to bring up some troubleshooting options for it. Then select the**Reset** troubleshooting option for the app.

## 3\. Uninstall Third-Party Antivirus Software

 Some third-party antivirus utilities can disable Windows Security features they effectively replace. If you’ve installed an overlapping third-party antivirus product, uninstalling it may resolve Windows Security’s administrator error. Uninstall antivirus software with a method within our guide on [how to remove Windows programs](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) to see if that resolves the issue.

![The uninstaller tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-uninstaller-tool.jpg)

 Should this solution work, the issue will likely reoccur if you reinstall the same third-party antivirus virus software. Then you would have to choose between using the third-party antivirus utility or Windows Security.

## 4\. Edit the Registry

 Many users have been able to fix the Windows Security administrator error by applying this confirmed registry solution. This registry tweak involves modifying a DWORD value, but you don’t need to delete any key. To apply this potential resolution, edit the registry like this:

1. Run the Windows Registry Editor app, which you can open with any method included in our [how to open Regedit](https://www.makeuseof.com/windows-11-open-registry-editor/) [g](https://www.makeuseof.com/windows-11-open-registry-editor/) uide.
2. Click inside the address box at the top of Registry Editor and erase the text in it.
3. Input this key path in the registry address bar and press**Return** :  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\DeviceGuard\Scenarios\HypervisorEnforcedCodeIntegrity`
4. Then double-click the**Enabled** DWORD within the**HypervisorEnforcedCodeIntegrity** key.  
![The HypervisorEnforced registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-hypervisor-key.jpg)
5. Clear the**Data value** box, and then input**0** there.
6. Select**OK** to set the**Enabled** DWORD’s value.  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/edit-dword-window.jpg)
7. Exit Registry Editor and click the**Power** \>**Restart** Start menu options.

## 5\. Set Group Policy’s Real-time Protection Settings to "Not Configured"

 A possibility for Windows 11 Pro and Enterprise users to consider is that Group Policy Editor could be blocking changes to Windows Security settings. If you can open Group Policy Editor on your PC, check real-time protection policy settings aren’t enabled there. This is how you can set real-time protection settings to not configured in Group Policy Editor:

1. Find Group Policy Editor by clicking the search magnifying glass icon and inputting**gpedit.msc** .
2. Select**gpedit.msc** to open the Group Policy Editor window.
3. Then select**Computer Configuration** to extend that category.
4. Double-click**Administrative Template** to access several setting categories.
5. Next, double-click**Windows Components** \>**Microsoft Defender Antivirus** \>**Real-time Protection** in the navigation sidebar.  
![The Real-time Protection policy settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-real-time-protection-policy-settings.jpg)
6. Double-click any policy setting that’s with an enabled state.
7. Then select the**Not configured radio** button.  
![The Not Configured radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/not-configured-option.jpg)
8. Click**Apply** \>**OK** in the window to set the change.
9. Repeat the previous three steps for all real-time protection policies set to enabled.

## 6\. Reinstall Windows Security

 You can’t reinstall Windows Security by uninstalling that app via Settings and downloading it from Microsoft Store. However, you can run a more general PowerShell command that reinstalls all apps pre-installed with Windows 11\. Try reinstalling Windows Security with that command as follows:

1. Open PowerShell with administrative rights. Our guide on [how to open PowerShell](https://www.makeuseof.com/windows-11-powershell-administrator/) includes various methods for opening that app.
2. Then input the following PowerShell command for reinstalling apps:  
`Get-AppXPackage -AllUsers | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall app PowerShell command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reinstall-app-command.jpg)
3. Press**Enter** and wait for the command to finish.
4. Restart your laptop or desktop from the Start menu.

## 7\. Reinstall Windows 11 With the Media Creation Tool

 Reinstalling Windows 11 by downloading an ISO with Media Creation Tool is a drastic potential solution. However, users have confirmed updating Windows 11 in such a way works for fixing this error. Furthermore, you can select to preserve apps and files when reinstalling. This is how to reinstall Windows 11:

1. Download the latest Windows 11 ISO with the Media Creation Tool. Our guide on [how to download a Windows 11 ISO](https://www.makeuseof.com/windows-11-download-iso/) includes step-by-step instructions for how to do so.
2. Then double-click your downloaded Windows 11 ISO file.
3. Click**setup.exe** to open the Windows 11 installer.  
![The Windows 11 Setup window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-setup-window.jpg)
4. Select**Next** to initiate a system check.
5. Press the**Accept** button for the license terms.
6. The**Keep personal files and apps** option will probably be set by default at the ready-to-install stage. However, you click**Change what to keep** to make sure the**Keep personal files and apps** option is selected.  
![The Keep personal files and apps radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/keep-personal-files-option.jpg)
7. Then select**Next** to proceed to the last step.
8. Click**Install** to reinstall Windows 11.

## Change Windows Security’s Settings Again

 Those are the most widely cited ways to fix the “setting is managed by your administrator” error in Windows 11\. So, applying those potential resolutions will probably resolve the “setting is managed by your administrator” issue on your PC. Then you’ll be able to set all the options within Windows Security as required.

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
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-universal-synchronization-zoom-on-phones-tablets-pcs-all/"><u>[Updated] In 2024, Universal Synchronization  Zoom on Phones, Tablets, PCs All</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-restore-your-desktop-icon-positions-on-windows/"><u>How to Restore Your Desktop Icon Positions on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-user-interface-fastest-uninstall-actions-with-context/"><u>Elevate User Interface: Fastest Uninstall Actions with Context</u></a></li>
<li><a href="https://windows11.techidaily.com/interpretation-of-the-red-x-icon-in-file-management/"><u>Interpretation of the Red “X” Icon in File Management</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-rejuvenate-a-dysfunctional-search-bar-in-windows-11/"><u>Guide to Rejuvenate a Dysfunctional Search Bar in Windows 11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-kazam-screen-recorder-features-guide-review/"><u>[New] Kazam Screen Recorder Features| Guide| Review</u></a></li>
<li><a href="https://windows11.techidaily.com/ideal-mobile-software-for-windows-pc-owners-on-android/"><u>Ideal Mobile Software for Windows PC Owners on Android</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-behind-pretense-apps-slowdown-your-modern-windows/"><u>Hidden Behind Pretense: Apps Slowdown Your Modern Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-folders-to-the-context-menu-in-windows-11/"><u>How to Add Folders to the Context Menu in Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-motorola-moto-g-5g-2023-to-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Motorola Moto G 5G (2023) To Phone | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/earnings-escalation-leveraging-your-youtube-channel-on-mobile-devices/"><u>Earnings Escalation  Leveraging Your YouTube Channel on Mobile Devices</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-masterclass-in-crafting-empowerment-videos-for-viewers/"><u>[Updated] Masterclass in Crafting Empowerment Videos for Viewers</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-solving-win-1011-ad-ds-printer-problems-efficiently/"><u>Guide to Solving Win 10/11 AD DS Printer Problems Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-the-power-of-background-blur-a-windows-11-photo-guide/"><u>Discover the Power of Background Blur: A Windows 11 Photo Guide</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/broadcast-easily-3-steps-to-post-mp3-on-youtube-for-2024/"><u>Broadcast Easily  3 Steps to Post MP3 on YouTube for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-file-selection-adding-directories-to-context-menu/"><u>Enhancing File Selection: Adding Directories to Context Menu</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-the-rise-and-fall-a-comparative-study-on-tiktok-and-snaps-popularity/"><u>2024 Approved  The Rise and Fall  A Comparative Study on TikTok and Snap’s Popularity</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-microsofts-enhancements-in-februarys-win11-patch/"><u>Exploring Microsoft's Enhancements in February's Win11 Patch</u></a></li>
<li><a href="https://windows11.techidaily.com/future-screens-innovating-beyond-windows-11/"><u>Future Screens: Innovating Beyond Windows 11</u></a></li>
<li><a href="https://animation-videos.techidaily.com/in-2024-8-free-gif-animators-to-make-your-own-gif/"><u>In 2024, 8 Free GIF Animators to Make Your Own GIF</u></a></li>
<li><a href="https://windows11.techidaily.com/installing-icloud-is-easy-troubleshoot-issues-on-windows/"><u>Installing iCloud Is Easy: Troubleshoot Issues on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-data-handling-navigate-4-steps-to-open-disk-management-in-windows-11/"><u>Effortless Data Handling: Navigate 4 Steps to Open Disk Management in Windows 11</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/mastering-lip-sync-explore-top-apps-for-dynamic-videos/"><u>Mastering Lip Sync Explore Top Apps for Dynamic Videos</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-save-money-and-time-creating-engaging-youtube-intros-without-paying/"><u>[New] 2024 Approved  Save Money & Time  Creating Engaging YouTube Intros Without Paying</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-unlocking-the-potential-of-mobile-video-conferencing/"><u>[Updated] In 2024, Unlocking the Potential of Mobile Video Conferencing</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-discover-review-and-compare-with-az-screenshotter/"><u>[New] Discover, Review & Compare with AZ Screenshotter</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-the-gamers-playbook-mastering-recordings-on-the-latest-w11/"><u>[New] 2024 Approved  The Gamers' Playbook  Mastering Recordings on the Latest W11</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-to-vanquish-your-pcs-win11-blue-screen/"><u>Expert Tips to Vanquish Your PC's Win11 Blue Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/highlighting-key-windows-processes-for-virus-alerts/"><u>Highlighting Key Windows Processes for Virus Alerts</u></a></li>
<li><a href="https://windows11.techidaily.com/initiate-your-narrative-with-a-click-on-windows-11/"><u>Initiate Your Narrative with a Click on Windows 11</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-exit-android-factory-mode-on-oneplus-ace-2-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Exit Android Factory Mode On OnePlus Ace 2 Pro? | Dr.fone</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-fake-gps-without-root-on-samsung-galaxy-m14-5g-drfone-by-drfone-virtual-android/"><u>3 Ways to Fake GPS Without Root On Samsung Galaxy M14 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/is-windows-11-running-slow-or-lagging-on-your-computer-7-ways-to-fix-it/"><u>Is Windows 11 Running Slow or Lagging on Your Computer? 7 Ways to Fix It</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-overcome-media-error-input-not-recognized-by-vlc/"><u>How to Overcome Media Error: Input Not Recognized by VLC</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-streamlining-presentations-webcam-recording-tips/"><u>[New] 2024 Approved  Streamlining Presentations  Webcam Recording Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-desktop-aesthetics-best-pc-time-saver-apps-listed/"><u>Boost Desktop Aesthetics – Best PC Time Saver Apps Listed</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-on-oneplus-ace-2-pro-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos on OnePlus Ace 2 Pro</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-inside-out-unveiling-the-true-intentions-behind-emojis-for-2024/"><u>[Updated] Inside Out  Unveiling the True Intentions Behind Emojis for 2024</u></a></li>
</ul></div>
