---
title: What Purpose Does a Directory Like Windows ~BT Serve?
date: 2024-08-15T16:09:58.886Z
updated: 2024-08-16T16:09:58.886Z
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

<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->

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
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-crafting-mp3s-from-instagram-the-easy-methodology/"><u>[New] 2024 Approved  Crafting Mp3s From Instagram  The Easy Methodology</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-best-practices-for-non-audio-filming/"><u>[New] Best Practices for Non-Audio Filming</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-crafting-compelling-videos-the-instagram-editors-playbook/"><u>[New] Crafting Compelling Videos  The Instagram Editor's Playbook</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-beyond-the-numbers-narrative-the-impact-of-fake-likes/"><u>[New] In 2024, Beyond the Numbers Narrative  The Impact of Fake Likes</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-track-lost-friends-on-instagram/"><u>[New] Track Lost Friends on Instagram</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-screen-recorder-pro-a-beginners-handbook-for-mac/"><u>[Updated] In 2024, Screen Recorder Pro  A Beginner's Handbook for Mac</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-synchronize-speech-and-slide-show-the-voiceover-advantage-for-2024/"><u>[Updated] Synchronize Speech and Slide Show  The Voiceover Advantage for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-overcoming-video-blank-screen-the-ultimate-chromesafari-guide/"><u>2024 Approved  Overcoming Video Blank Screen  The Ultimate Chrome/Safari Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-script-failures-windows-script-troubleshooting-guide/"><u>Bypass Script Failures: Windows Script Troubleshooting Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-11-restrictions-a-beginners-guide/"><u>Bypassing Windows 11 Restrictions: A Beginner's Guide</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/eliminating-dead-pixels-from-desktop-screens/"><u>Eliminating Dead Pixels From Desktop Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-opaque-windows-11-themes-via-registry-manipulation/"><u>Enabling Opaque Windows 11 Themes via Registry Manipulation</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-level-insights-into-windows-non-adjacent-partition-integration/"><u>Expert-Level Insights Into Windows Non-Adjacent Partition Integration</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-change-credit-card-on-your-iphone-13-pro-apple-id-and-apple-pay-by-drfone-ios/"><u>How to Change Credit Card on Your iPhone 13 Pro Apple ID and Apple Pay</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-elevate-your-old-computer-into-a-windows-11-powerhouse/"><u>How to Elevate Your Old Computer Into a Windows 11 Powerhouse</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-a-motorola-g54-5g-phone-that-is-locked-by-drfone-android/"><u>How to Reset a Motorola G54 5G Phone that is Locked?</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-a-motorola-moto-g84-5g-phone-that-is-locked-by-drfone-android/"><u>How to Reset a Motorola Moto G84 5G Phone that is Locked?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-after-switching-from-vivo-y02t-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data After Switching From Vivo Y02T to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-cards-of-vivo-g2-without-puk-codes-by-drfone-android/"><u>How To Unlock SIM Cards Of Vivo G2 Without PUK Codes</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-8-best-apps-for-screen-mirroring-samsung-galaxy-s24-ultra-pc-drfone-by-drfone-android/"><u>In 2024, 8 Best Apps for Screen Mirroring Samsung Galaxy S24 Ultra PC | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-6-best-sim-unlock-services-that-actually-work-on-your-poco-x6-device-by-drfone-android/"><u>In 2024, The 6 Best SIM Unlock Services That Actually Work On Your Poco X6 Device</u></a></li>
<li><a href="https://windows11.techidaily.com/inside-outlook-and-file-explorers-new-backup-integration-in-windows-11/"><u>Inside Outlook and File Explorer's New Backup Integration in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/iphoneandroid-as-windows-microphones-guide/"><u>IPhone/Android as Windows Microphones Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/localize-onedrive-a-step-by-step-windows-approach/"><u>Localize OneDrive: A Step-by-Step Windows Approach</u></a></li>
<li><a href="https://tech-revival.techidaily.com/mastering-deduction-with-advanced-ai-discover-4-engaging-cyber-sleuthing-challenges/"><u>Mastering Deduction with Advanced AI: Discover 4 Engaging Cyber Sleuthing Challenges</u></a></li>
<li><a href="https://windows11.techidaily.com/overriding-default-no-notify-camera-behavior-in-ws11/"><u>Overriding Default No-Notify Camera Behavior in WS11</u></a></li>
<li><a href="https://windows11.techidaily.com/peek-inside-windows-determining-your-computers-manufacturer/"><u>Peek Inside Windows: Determining Your Computer's Manufacturer</u></a></li>
<li><a href="https://win-solutions.techidaily.com/persona-amoled-solutions-handling-crash-prone-scenarios-for-seamless-gaming/"><u>Persona Amoled Solutions: Handling Crash-Prone Scenarios for Seamless Gaming</u></a></li>
<li><a href="https://windows11.techidaily.com/precise-strategies-resetting-razers-system-integration/"><u>Precise Strategies: Resetting Razer's System Integration</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-rpc-errors-on-windows-os/"><u>Quick Fixes for RPC Errors on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-imaginary-device-issue-in-win-11-os/"><u>Resolving Imaginary Device Issue in Win 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-win1011-network-failure-code-0x800704b3/"><u>Resolving Win10/11 Network Failure: Code 0X800704B3</u></a></li>
<li><a href="https://windows11.techidaily.com/revitalizing-your-stalled-windows-11-mobile-network-connection/"><u>Revitalizing Your Stalled Windows 11 Mobile Network Connection</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionize-your-pc-clear-tpm-from-windows-11/"><u>Revolutionize Your PC: Clear TPM From Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-shadowrunners-speed-up-your-bf2-experience/"><u>Seamless Shadowrunners: Speed up Your BF2 Experience</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/skyrocketing-video-performance-in-instagram-stories-mobile/"><u>Skyrocketing Video Performance in Instagram Stories (Mobile)</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-deleting-search-box-art-in-win/"><u>Strategies for Deleting Search Box Art in Win</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-your-security-settings-on-windows-11/"><u>Tailoring Your Security Settings on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-curtail-excessive-wmi-worker-use/"><u>Tips to Curtail Excessive WMI Worker Use</u></a></li>
<li><a href="https://windows11.techidaily.com/win11s-file-explorer-glitches-learn-how-to-stop-them/"><u>Win11's File Explorer Glitches? Learn How To Stop Them</u></a></li>
</ul></div>
