---
title: What Purpose Does a Directory Like Windows ~BT Serve?
date: 2024-07-11T21:23:08.703Z
updated: 2024-07-12T21:23:08.703Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes What Purpose Does a Directory Like Windows ~BT Serve?
excerpt: This Article Describes What Purpose Does a Directory Like Windows ~BT Serve?
keywords: BT Windows Directory Purpose,Windows BT Guide,BT Directory Function,Understanding BT Directory,BT System Role in Windows,Directory Significance for BT,Purpose of BT Integration
thumbnail: https://thmb.techidaily.com/46562a4985b29bb04ac045f40f195ad5a81e8c6a78d3deb58b3600f2a5e9d7c1.jpg
---

## What Purpose Does a Directory Like Windows ~BT Serve?

 Deleting the hidden "$Windows.\~BT" folder and recovering gigabytes of space on your hard drive is tempting. But what is this cryptically named folder for, and how critical is it to your Windows installation?

## What Is the “$Windows.\~BT” Folder, and Should You Delete It?

 Windows creates the "$Windows.\~BT" folder when you upgrade the operating system to a newer build. This folder contains all the essential files for the upgrade process, like temporary installation files and logs from the previous Windows installation.

 Windows automatically removes the "$Windows.\~BT" folder after 10 days. As manually deleting this folder will [remove old Windows installation files](https://www.makeuseof.com/tag/delete-old-windows-update-files/), you won't be able to roll back to the previous Windows build using the **Go back** option in the Recovery menu within that time (for example, to [downgrade from Windows 11 to Windows 10](https://www.makeuseof.com/windows-11-downgrade-to-windows-10/)). Hence, you should only get rid of this folder if you are satisfied with the current Windows build on your PC. You can also safely delete the massive folder if Windows fails to do it automatically after the grace period.

 But you shouldn't just delete this hidden folder like any other folder on the desktop. Instead, you should turn to the Disk Cleanup tool or the Command Prompt.

## How to Find and Delete the "$Windows.\~BT" Folder

 As "$Windows.\~BT" is a hidden folder, you need to [configure Windows to show hidden files and folders](https://www.makeuseof.com/windows-11-show-hidden-files-folders/) to find it in File Explorer. Once you do, the **C:\\$Windows.\~BT** directory will become visible.

 You can’t delete the "$Windows.\~BT" folder directly, though. To do so, you need to run the Disk Cleanup tool. Here's how:

1. Press **Win + R** to open the Run dialog box.
2. Type **cleanmgr** in the box and press **Enter**.
3. Use the dropdown menu to select the system drive (usually **C:**) and click **OK**.
4. Click the **Clean up system files** button.
5. Under **Files to delete**, use the checkboxes to select these options: **Previous Windows Installations**, **Windows Update Cleanup**, **Windows upgrade log files**, **Temporary Windows installation files**, and **Temporary files**.
6. Click **OK**.
7. Choose **Delete Files** to confirm.  
![Delete the $Windows.~BT Folder Using the Disk Cleanup Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/delete-the-windows-bt-folder-using-the-disk-cleanup-tool.jpg)

 If the "$Windows.\~BT" folder shows up even after you run the Disk Cleanup tool, you'll need to execute a few commands in Command Prompt. For that, [open Command Prompt with administrative rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) and then run the following commands one by one.

`takeown /F C:\$Windows.~BT\* /R /A
icacls C:\$Windows.~BT\*.* /T /grant administrators:F
rmdir /S /Q C:\$Windows.~BT\`

 Once you run the above commands, the "$Windows.\~BT" folder will be deleted for good.

 Now that you understand the purpose of the "$Windows.\~BT" folder, you can decide how to handle it. Beyond the "$Windows.\~BT" folder, you may also come across folders like "Windows.old," "$WinREAgent," "$SysReset," and others which can also be deleted safely using the Disk Cleanup tool.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://location-fake.techidaily.com/5-best-route-generator-apps-you-should-try-on-nokia-c110-drfone-by-drfone-virtual-android/"><u>5 Best Route Generator Apps You Should Try On Nokia C110 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-set-up-troubleshooter-shortcuts-in-windows-11-and-11/"><u>How to Set Up Troubleshooter Shortcuts in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-memory-management-in-new-os/"><u>Mastering Memory Management in New OS</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-office-suites-strict-safe-mode-on-windows-operations/"><u>Troubleshooting Office Suite's Strict Safe Mode on Windows Operations</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-revolutionize-your-social-media-experience-with-top-fire-browser-extensions-for-facebook-2023/"><u>[New] In 2024, Revolutionize Your Social Media Experience with Top Fire-Browser Extensions for Facebook, 2023</u></a></li>
<li><a href="https://windows11.techidaily.com/optimal-system-settings-reducing-resource-drain-while-playing/"><u>Optimal System Settings: Reducing Resource Drain While Playing</u></a></li>
<li><a href="https://windows11.techidaily.com/restore-and-revitalize-13-ways-to-rejuvenate-windows-systems/"><u>Restore & Revitalize: 13 Ways to Rejuvenate Windows Systems</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-beginners-luck-15-free-video-editing-programs-to-get-you-started-for-2024/"><u>New Beginners Luck 15 Free Video Editing Programs to Get You Started for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unfreezing-and-reviving-windows-11s-stuck-media-player/"><u>Unfreezing and Reviving Windows 11'S Stuck Media Player</u></a></li>
<li><a href="https://windows11.techidaily.com/make-your-windows-life-easier-with-proper-installation-steps/"><u>Make Your Windows Life Easier with Proper Installation Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-efface-license-end-soon-warning-from-your-pc/"><u>How To Efface License End Soon Warning From Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-this-file-is-alone-error-on-pcs/"><u>Overcoming This File Is Alone Error on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/reset-chronology-fix-windows-time-errors/"><u>Reset Chronology: Fix Windows Time Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-snipping-tool-activation-from-pressing-prtscn-in-11/"><u>How to Stop Snipping Tool Activation From Pressing PrtScn in 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-elusive-guide-to-unseen-menu-adjustments-windows-style/"><u>The Elusive Guide to Unseen Menu Adjustments, Windows Style</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-local-security-authority-protection-is-off-security-warning-on-windows/"><u>How to Fix the “Local Security Authority Protection Is Off” Security Warning on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-multi-user-printer-errors-windows-11-guide/"><u>Handling Multi-User Printer Errors: Windows 11 Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-extend-the-pin-length-in-windows-11-and-11/"><u>How to Extend the PIN Length in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-microsoft-m365-glitch-with-code-30015-26/"><u>Remedy Microsoft M365 Glitch with Code 30015-26</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-your-subnet-in-the-latest-os-win11/"><u>Optimizing Your Subnet in the Latest OS: Win11</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-the-art-of-connection-4-ways-to-tie-in-your-fb-story/"><u>In 2024, The Art of Connection  4 Ways to Tie in Your Fb Story</u></a></li>
<li><a href="https://windows11.techidaily.com/securely-clearing-email-details-post-login/"><u>Securely Clearing Email Details Post-Login</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-efficient-use-of-obs-with-zoom-video-platform/"><u>[New] Efficient Use of OBS with Zoom Video Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-application-failure-the-notorious-error-the-application-couldnt-start-xc000003e-on-win11-and-11/"><u>Navigating Application Failure: The Notorious Error The Application Couldn’t Start Xc000003e on Win11 & 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-can-you-transfer-files-from-realme-12plus-5g-to-iphone-151413-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How Can You Transfer Files From Realme 12+ 5G To iPhone 15/14/13? | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-realme-v30t-drfone-by-drfone-virtual-android/"><u>Here are Some Pro Tips for Pokemon Go PvP Battles On Realme V30T | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/investigating-and-fixing-create-failed-on-windows-error-30005/"><u>Investigating and Fixing Create Failed on Windows Error 30005</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-mastering-the-new-era-of-editing-with-powerdirector-24-edition/"><u>[Updated] Mastering the New Era of Editing with PowerDirector '24 Edition</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-the-art-of-keeping-tiktok-content-safe-on-devices/"><u>In 2024, The Art of Keeping TikTok Content Safe on Devices</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-avoiding-pitfalls-tiktok-video-copyright-verification-guide/"><u>[New] 2024 Approved  Avoiding Pitfalls  TikTok Video Copyright Verification Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/howtodarkennotepadwindesktop/"><u>HowToDarkenNotepadWinDesktop</u></a></li>
<li><a href="https://windows11.techidaily.com/visualize-resource-consumption-windows-tray-update-guide/"><u>Visualize Resource Consumption: Windows Tray Update Guide</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-best-10-webcam-recorders-no-cost/"><u>[Updated] In 2024, Best 10 Webcam Recorders, No Cost</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-device-control-for-sleep-state-wakefulness/"><u>Unlocking Device Control for Sleep State Wakefulness</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-effortless-control-enhancing-gameplay-on-steam-using-switch-pro/"><u>In 2024, Effortless Control  Enhancing Gameplay on Steam Using Switch Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-for-resolving-missing-drivers-alert-on-windows-setup/"><u>Guidelines for Resolving Missing Drivers Alert on Windows Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/restore-full-size-to-your-windows-11-icons/"><u>Restore Full Size to Your Windows 11 Icons</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-pictures-from-nubia-red-magic-8s-proplus-by-fonelab-android-recover-pictures/"><u>Easy steps to recover deleted pictures from Nubia Red Magic 8S Pro+.</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-non-existence-of-powershell-in-windows/"><u>Tackling the Non-Existence of PowerShell in Windows</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-the-ultimate-guide-to-team-chat-apps-slack-vs-discord-showdown/"><u>[New] The Ultimate Guide to Team Chat Apps  Slack Vs. Discord Showdown</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-your-console-dreams-choose-windows-for-games/"><u>Unlocking Your Console Dreams: Choose Windows for Games</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-quick-and-easy-iphone-burst-techniques/"><u>2024 Approved  Quick and Easy iPhone Burst Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-window-gloss-your-guide-to-a-clearer-taskbar-in-win11/"><u>Mastering Window Gloss: Your Guide to a Clearer Taskbar in Win11</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-streaming-software-showdown-choosing-between-obs-and-streamlabs/"><u>In 2024, Streaming Software Showdown  Choosing Between OBS and Streamlabs</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-correct-hardware-detection-errors-in-win/"><u>How To Correct Hardware Detection Errors in Win</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-unveiling-the-finest-free-online-recorders-top-picks/"><u>[New] 2024 Approved  Unveiling the Finest Free Online Recorders – Top Picks</u></a></li>
<li><a href="https://windows11.techidaily.com/proven-strategies-for-comprehensible-comic-consumption-on-win11/"><u>Proven Strategies for Comprehensible Comic Consumption on Win11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-everything-you-need-to-know-about-lock-screen-settings-on-your-vivo-y100i-power-5g-by-drfone-android/"><u>In 2024, Everything You Need to Know about Lock Screen Settings on your Vivo Y100i Power 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windowsstore-app-folder-hidden-entry-points/"><u>Unveiling WindowsStore App Folder Hidden Entry Points</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-total-guide-ultimate-video-show-experience-in-24/"><u>[Updated] Total Guide  Ultimate Video Show Experience in '24</u></a></li>
</ul></div>
