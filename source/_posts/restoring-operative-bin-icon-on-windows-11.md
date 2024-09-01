---
title: Restoring Operative Bin Icon on Windows 11
date: 2024-08-31T22:09:21.232Z
updated: 2024-09-01T22:09:21.232Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Operative Bin Icon on Windows 11
excerpt: This Article Describes Restoring Operative Bin Icon on Windows 11
keywords: Win11 Restore Icons,Bin Icon Fix Windows,Windows 11 Icon Repair,Operation Icons Reinstate,Renew Windows Icon Image,Windows Operative Symbol,Bin Icon Restoration W11
thumbnail: https://thmb.techidaily.com/5584d777e110cbdbb48713bd82133ccfd2417ed4baa291781cd47c73ffc42e1f.jpeg
---

## Restoring Operative Bin Icon on Windows 11

 The Recycle Bin has been a staple on Windows for a long time, but not everyone wants it on the desktop. You can disable it via the Desktop Icon Settings, but there is a bug where if you try to re-enable it, the "Recycle Bin" option is grayed out and cannot be toggled.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

## 1\. How to Bring Back the Recycle Bin Using the Group Policy Editor

 The Group Policy Editor lets you show or hide the Recycle Bin icon from the desktop. Check if you have modified and accidentally disabled the Recycle Bin group policy recently. If so you can set the Remove Recycle Bin icon from the desktop policy to "Not Configured" which will restore it.

 You may not find the Local Group Policy Editor in Windows Home Edition. However, you can run a batch script to [enable Group Policy Editor on the Windows Home edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) or skip to the Registry Editor-based fix in the next step.

 To restore the Recycle Bin icon using the Group Policy Editor:

1. Press **Win + R** to open **Run**.
2. Type **gpedit.msc** and click **OK** to open the **Group Policy Editor**.  
![gpedit msc windows 11 run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/gpedit-msc-windows-11-run.jpg)
3. Next, navigate to the following location:  
`User Configuration > Administrative Templates > Desktop`
4. In the right pane, locate and double-click on the **Remove Recycle Bin icon from the desktop** option to open its properties.  
![edit remove recycle bin icon from settings gpedit policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-remove-recycle-bin-icon-from-settings-gpedit-policy.jpg)
5. In the **Properties** dialog, select **Not Configured**.  
![edit remove recycle bin icon from settings gpedit policy not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-remove-recycle-bin-icon-from-settings-gpedit-policy-not-configured.jpg)
6. Click **Apply** and **OK** to save the changes.

 Close the Group Policy Editor and check your desktop to see if you can access the Recycle Bin. If not, make sure the Recycle Bin is set to show in Desktop Icon Settings.

 To enable Recycle Bin in Desktop Icon Settings:

1. Press **Win + I** to open **Settings**.
2. Next, open the **Personalization** tab in the left panel.
3. Click on **Themes**.  
![desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/desktop-icon-settings-windows-11.jpg)
4. Click on **Desktop icon settings** under the **Related settings** section.
5. In the **Desktop Icon Settings** dialog, select **Recycle Bin**.  
![enable recycle bin desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/enable-recycle-bin-desktop-icon-settings-windows-11.jpg)
6. Click **Apply** and **OK** to save the changes.

 If you can’t access Group Policy Editor or if the issue persists, you can use the Registry Editor to fix this problem.

## 2\. Modify the Recycle Bin Registry Settings

 Another way to resolve and restore the grayed-out Recycle Bin icon in the Desktop settings is via the Windows Registry. You can modify the registry entry value responsible for the settings and configurations of Recycle Bin working to restore the functionality.

 Making modifications to the Windows registry involves tweaking settings that may harm your device if performed incorrectly. We recommend you [create a Windows restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [take a Windows registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before attempting to modify the Windows registry.

 To modify the Recycle Bin registry value:

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK**. Click **Yes** if prompted by **User Account Control**.
3. In the Registry Editor, navigate to the following location. You can copy and paste the path in the editor for quicker navigation:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\NonEnum`
4. In the right pane, locate the **{645FF040-5081-101B-9F08-00AA002F954E}** DWORD (32-bit) value.  
![registry editor nonnum new dword value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value.jpg)
5. If it does not exist, you’ll need to create a new value. To do this, right-click on the **NonEnum** subkey folder in the left pane and select **New > DWORD (32-bit) Value**.
6. Rename the value as **{645FF040-5081-101B-9F08-00AA002F954E}**.
7. Next, double-click on the new DWORD value to open its properties.  
![registry editor nonnum new dword value edit 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value-edit-0.jpg)
8. Type **0** in the Value data field and click **OK** to save the changes.
9. Close Registry Editor and restart your computer. Sometimes, you’ll need to restart your computer for the new registry modifications to work.

 If the issue persists, try to [create a new user account with administrative rights](https://www.makeuseof.com/windows-11-create-local-user-account/), [perform a system restore](https://www.makeuseof.com/use-system-restore-windows/), or [repair corrupted Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get Access to the Recycle Bin Desktop Icon Setting Again

 An incorrectly modified group policy can gray out the Recycle Bin icon in the Desktop Icon Settings dialog. Fortunately, it's an easy fix, and you should now have your Recycle Bin back to how you like it.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-videos.techidaily.com/new-10-strategies-to-make-money-on-youtube-shorts-easily/"><u>[New] 10 Strategies to Make Money on YouTube Shorts Easily</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-capture-every-word-4-tips-for-fb-video-transcripts/"><u>[New] In 2024, Capture Every Word  4 Tips for FB Video Transcripts</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-master-screen-recording-on-windows-macos-and-android-devices/"><u>[New] In 2024, Master Screen Recording on Windows, macOS, and Android Devices</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-top-15-whatsapp-tricks-that-will-change-everything-for-2024/"><u>[New] Top 15 WhatsApp Tricks That Will Change Everything for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-2024s-premium-video-equipment-unpacked/"><u>[Updated] 2024'S Premium Video Equipment Unpacked</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-capturing-footage-from-above-drone-filming-tips-for-2024/"><u>[Updated] Capturing Footage From Above  Drone Filming Tips for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-essential-mac-tools-for-screen-capture-discovering-the-top-5-for-2024/"><u>[Updated] Essential Mac Tools for Screen Capture, Discovering the Top 5 for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-free-high-quality-edits-explore-these-9-cloud-apps/"><u>[Updated] Free, High-Quality Edits  Explore These 9 Cloud Apps</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-5-key-steps-to-transforming-videos-into-cash-on-vimeo/"><u>[Updated] In 2024, 5 Key Steps to Transforming Videos Into Cash on Vimeo</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-top-4-screen-recording-features-for-windows-8/"><u>[Updated] In 2024, Top 4 Screen Recording Features for Windows 8</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-personalize-and-protect-youtube-channel-url-made-simple/"><u>2024 Approved  Personalize & Protect  YouTube Channel URL Made Simple</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-pioneering-quests-and-thrills-top-10-game-wonders-top-10/"><u>2024 Approved  Pioneering Quests & Thrills – Top 10 Game Wonders (Top 10)</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-saving-time-avoiding-edgenuity-lessons-without-guilt/"><u>2024 Approved  Saving Time  Avoiding Edgenuity Lessons Without Guilt</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-the-ultimate-guide-to-professional-livestreamers-vmix-or-wirecast/"><u>2024 Approved  The Ultimate Guide to Professional Livestreamers  VMix or Wirecast?</u></a></li>
<li><a href="https://win11.techidaily.com/4-key-approaches-to-activate-a-dormant-windows-guard/"><u>4 Key Approaches to Activate a Dormant Windows Guard</u></a></li>
<li><a href="https://games-able.techidaily.com/disabling-steam-boots-silently/"><u>Disabling Steam Boots Silently</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-customizing-windows-11-default-apps/"><u>Essential Guide to Customizing Windows 11 Default Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-for-rectifying-display-driver-crashes/"><u>Essential Tips for Rectifying Display Driver Crashes</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-absent-mfc71udll-steps-for-windows-users/"><u>Fixing Absent Mfc71u.dll: Steps for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-video-playback-issues-with-error-0xc10100bf/"><u>Fixing Video Playback Issues with Error 0XC10100BF</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-the-latest-surface-pro-ebx4-drivers-installed-in-windows-step-by-step/"><u>Get the Latest Surface Pro Ebx4 Drivers Installed in Windows: Step-by-Step</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-disable-hyper-v-in-windows-11/"><u>Guide to Disable Hyper-V in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-windows-components-administration-tool/"><u>Guide to Windows Components Administration Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-windows-activation-error-0x803f700f/"><u>How to Fix the Windows Activation Error 0X803F700F</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-keep-search-invisible-in-win-11-taskbar/"><u>How to Keep Search Invisible in Win 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-repair-auto-detection-failure-in-windows-proxies/"><u>How to Repair Auto-Detection Failure in Windows Proxies</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-swiftly-overcome-directdraw-errors-in-win1011-environments/"><u>How to Swiftly Overcome DirectDraw Errors in Win10/11 Environments</u></a></li>
<li><a href="https://windows11.techidaily.com/improve-efficiency-with-top-5-clock-screensaver-apps/"><u>Improve Efficiency with Top 5 Clock Screensaver Apps</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-learn-how-everything-works-on-lava-blaze-2-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Learn How Everything Works On Lava Blaze 2 | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-step-by-step-guide-to-record-online-video-calls/"><u>In 2024, Step-by-Step Guide to Record Online Video Calls</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-ultimate-selection-best-idevice-custom-alerts/"><u>In 2024, Ultimate Selection  Best iDevice Custom Alerts</u></a></li>
<li><a href="https://extra-hints.techidaily.com/learning-the-ropes-of-lunapics-user-interface/"><u>Learning the Ropes of LunaPic's User Interface</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721475610947-lost-an-iphone-app-follow-this-simple-troubleshooting-technique-to-recover-it/"><u>Lost an iPhone App? Follow This Simple Troubleshooting Technique to Recover It!</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-auto-shutdown-for-idle-windows-1011-machines/"><u>Mastering Auto-Shutdown for Idle Windows 10/11 Machines</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-winscombsvr-crashes-in-windows/"><u>Navigating Through WinScombSvr Crashes in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/optimal-pc-protection-activating-tpm-and-secure-boot-in-win-11/"><u>Optimal PC Protection: Activating TPM & Secure Boot in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-security-updating-user-passwords-on-win-11/"><u>Optimizing Security: Updating User Passwords on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-update-error-0x800736cc-fix-guide/"><u>Overcoming Windows Update Error: 0X800736CC Fix Guide</u></a></li>
<li><a href="https://video-capture.techidaily.com/perfecting-live-steam-playback-a-step-by-step-approach-for-2024/"><u>Perfecting Live Steam Playback  A Step-by-Step Approach for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/post-maintenance-world-what-comes-next-after-windows-781/"><u>Post-Maintenance World: What Comes Next After Windows 7/8.1?</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-normal-operations-for-deleted-characters/"><u>Restoring Normal Operations for Deleted Characters</u></a></li>
<li><a href="https://extra-information.techidaily.com/scripting-stimulating-screen-grabbers/"><u>Scripting Stimulating Screen-Grabbers</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-steps-to-alter-your-cursors-look/"><u>Simplified Steps to Alter Your Cursor's Look</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-activate-windows-11-family-safeguards/"><u>Steps to Activate Windows 11 Family Safeguards</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-inability-to-run-os-disk-organizer/"><u>Tackling Inability to Run OS Disk Organizer</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-to-conceal-windows-11s-task-control-icon/"><u>Tactics to Conceal Windows 11'S Task Control Icon</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-to-overcome-disappearing-ubisoft-game-launcher/"><u>Tactics to Overcome Disappearing Ubisoft Game Launcher</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/the-ultimate-guide-to-prime-notetaking-with-ai-innovations/"><u>The Ultimate Guide to Prime Notetaking with AI Innovations</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-repairing-disp-settings-missing-error/"><u>Tips for Repairing Disp Settings Missing Error</u></a></li>
<li><a href="https://windows11.techidaily.com/triggers-for-authentication-control-screen-windows-11/"><u>Triggers for Authentication Control Screen (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-windows-not-recognizing-an-interface/"><u>Troubleshoot Windows Not Recognizing an Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-disk-space-through-powershell-metrics-analysis/"><u>Understanding Disk Space Through PowerShell Metrics Analysis</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-upgraded-widget-choice-interface-in-win11/"><u>Unlocking Upgraded Widget Choice Interface in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11-with-non-admin-steps/"><u>Unlocking Windows 11 With Non-Admin Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-microsoft-shop-glitch-0x80131500/"><u>Unraveling Microsoft Shop Glitch #0X80131500</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-of-fax-cover-page-editing-in-win11/"><u>Unveiling the Secrets of Fax Cover Page Editing in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/your-guide-to-next-gen-computing-at-ifa-2023/"><u>Your Guide to Next-Gen Computing at IFA 2023</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>