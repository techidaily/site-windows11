---
title: Can You Get Rid of the Windows ~BT Directories?
date: 2024-07-11T21:33:40.401Z
updated: 2024-07-12T21:33:40.401Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Can You Get Rid of the Windows ~BT Directories?
excerpt: This Article Describes Can You Get Rid of the Windows ~BT Directories?
keywords: Eliminate Windows BT Folders,Remove BT Directory Files,Delete BT System Files,Cleanup BT Temp Directories,Erase Windows BT Data,Clear BT File Cache,Uninstall BT Templates
thumbnail: https://thmb.techidaily.com/cbf529e05dd3135fe67a52edb00f230c5ea15121620c8f38c53b6edc4bb0734a.jpg
---

## Can You Get Rid of the Windows ~BT Directories?

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
<li><a href="https://windows11.techidaily.com/ensure-seamless-fullscreen-launch-on-windows-pcs/"><u>Ensure Seamless Fullscreen Launch on Windows PCs</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-step-by-step-guide-building-high-quality-windows-11-videos/"><u>[New] Step-by-Step Guide  Building High-Quality Windows 11 Videos</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-premier-5-time-lapse-camera-apps/"><u>[Updated] In 2024, Premier 5 Time-Lapse Camera Apps</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-art-of-refining-published-videos-on-youtube/"><u>2024 Approved  The Art of Refining Published Videos on YouTube</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-strategies-to-perfect-the-last-push-on-your-vimeo-videos/"><u>[Updated] 2024 Approved  Strategies to Perfect the Last Push on Your Vimeo Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-heavy-resource-use-by-news-apps-in-windows-os/"><u>Reducing Heavy Resource Use by News Apps in Windows OS</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-how-to-remove-static-noise-from-audio-in-seconds/"><u>New In 2024, How to Remove Static Noise From Audio in Seconds</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-the-apple-iphone-14-sim-lock-4-easy-methods-by-drfone-ios/"><u>In 2024, How To Unlock The Apple iPhone 14 SIM Lock 4 Easy Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-system-limitations-intel-hd-graphics-compatibility-fixes/"><u>Rectifying System Limitations: Intel HD Graphics Compatibility Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-unlock-and-reset-restricted-program-status/"><u>How to Unlock and Reset Restricted Program Status</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-link-your-windows-product-key-to-a-microsoft-account/"><u>How to Link Your Windows Product Key to a Microsoft Account</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-your-windows-onedrive-hurdles-now/"><u>Fix Your Windows OneDrive Hurdles Now</u></a></li>
<li><a href="https://windows11.techidaily.com/key-steps-unveiled-navigating-disks-in-w10-and-w11-systems/"><u>Key Steps Unveiled: Navigating Disks in W10 & W11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-failed-application-launches-windows-11s-error-0xc000003e-explained/"><u>Correcting Failed Application Launches: Windows 11'S Error 0XC000003E Explained</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-videopad-video-editor-2023-a-detailed-review-and-recommendation/"><u>Updated In 2024, Videopad Video Editor 2023 A Detailed Review and Recommendation</u></a></li>
<li><a href="https://windows11.techidaily.com/rectify-stalling-windows-guard-mechanism-in-win-11/"><u>Rectify Stalling Windows Guard Mechanism in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-windows-11-when-it-cant-connect-to-5ghz-wi-fi/"><u>How to Fix Windows 11 When It Can’t Connect to 5GHz Wi-Fi</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-connected-platforms-sharing-videos-between-twitter-and-tumblr/"><u>In 2024, Connected Platforms  Sharing Videos Between Twitter & Tumblr</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-securing-snapshots-across-android-and-mac-platforms/"><u>[New] In 2024, Securing Snapshots Across Android and Mac Platforms</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-pgsharp-legal-when-you-are-playing-pokemon-on-samsung-galaxy-xcover-6-pro-tactical-edition-drfone-by-drfone-virtual-android/"><u>In 2024, Is pgsharp legal when you are playing pokemon On Samsung Galaxy XCover 6 Pro Tactical Edition? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-common-issues-for-intel-unison-on-windows-11/"><u>Fixing Common Issues for Intel Unison on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/redirecting-to-file-explorer-from-onedrive-menu/"><u>Redirecting to File Explorer From OneDrive Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-1110-how-to-stop-double-click-folders-from-closing/"><u>Fixing Windows 11/10: How to Stop Double-Click Folders From Closing</u></a></li>
<li><a href="https://windows11.techidaily.com/mindfulness-meets-the-mind-cognitive-and-emotional-responses-to-meditation/"><u>Mindfulness Meets the Mind: Cognitive & Emotional Responses to Meditation</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-track-imei-number-of-vivo-v29e-through-google-earth-by-drfone-android/"><u>How To Track IMEI Number Of Vivo V29e Through Google Earth?</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-2024-approved-how-to-post-twitter-video-on-instagram/"><u>[New] 2024 Approved  How to Post Twitter Video on Instagram</u></a></li>
<li><a href="https://windows11.techidaily.com/power-up-your-vms-in-windows-using-these-top-6-enhancers/"><u>Power Up Your VMs in Windows Using These Top 6 Enhancers</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlocking-made-easy-the-best-10-apps-for-unlocking-your-oppo-reno-11f-5g-device-by-drfone-android/"><u>Unlocking Made Easy The Best 10 Apps for Unlocking Your Oppo Reno 11F 5G Device</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/snatching-twitter-laughter-3-pc-techniques/"><u>Snatching Twitter Laughter  3 PC Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/recover-lost-pin-following-system-breakdown-on-windows-11/"><u>Recover Lost PIN Following System Breakdown on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-grammarly-settings-in-windows/"><u>Resetting Grammarly Settings in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/instructional-guide-for-end-task-enabling-on-windows-11/"><u>Instructional Guide for End Task Enabling on Windows 11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-activation-lock-on-the-iphone-12-pro-max-without-previous-owner-by-drfone-ios/"><u>In 2024, How to Remove Activation Lock On the iPhone 12 Pro Max Without Previous Owner?</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/top-trending-ig-filters-ranked/"><u>Top Trending IG Filters Ranked</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-the-absence-of-drive-letters-in-windows-environments/"><u>Dissecting the Absence of Drive Letters in Windows Environments</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/bringing-people-together-in-real-time-using-whatsapp-desktop-for-laptops/"><u>Bringing People Together in Real Time Using WhatsApp Desktop for Laptops</u></a></li>
<li><a href="https://windows11.techidaily.com/easily-identify-last-opened-files-in-windows-explorer/"><u>Easily Identify Last Opened Files in Windows Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/ignite-vm-speed-and-stability-top-6-methods-to-enhance-in-windows/"><u>Ignite VM Speed and Stability: Top 6 Methods to Enhance in Windows</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-can-you-cast-your-apple-iphone-12-to-windows-pc-with-ease-drfone-by-drfone-ios/"><u>How Can You Cast Your Apple iPhone 12 to Windows PC With Ease? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-lava-yuva-2-drfone-by-drfone-virtual-android/"><u>In 2024, Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Lava Yuva 2 | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-motorola-edge-40-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Motorola Edge 40 to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-cutting-through-the-noise-strategies-for-standout-instagram-success-for-2024/"><u>[Updated] Cutting Through the Noise  Strategies for Standout Instagram Success for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windows-11-search-with-custom-settings/"><u>Optimizing Windows 11 Search with Custom Settings</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-navigating-high-definition-video-production-in-the-facebook-era/"><u>[Updated] 2024 Approved  Navigating High Definition Video Production in the Facebook Era</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-11-nvidia-cp-not-opening-problem/"><u>Fixing Windows 11: Nvidia CP Not Opening Problem</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/snapchats-visual-language-mastering-the-art-of-gifting-with-gifs/"><u>Snapchat's Visual Language  Mastering the Art of Gifting with Gifs</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-nvidia-experience-connectivity-issues-on-pcs/"><u>Remedying Nvidia Experience Connectivity Issues on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tracker-tools-the-ultimate-6-list-for-windows-users/"><u>Essential Tracker Tools: The Ultimate 6 List For Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-interactions-between-devices-and-pc-slumber/"><u>Navigating Interactions Between Devices and PC Slumber</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/unlocking-the-secrets-of-high-conversion-rates-in-youtube-banner-designs-for-2024/"><u>Unlocking the Secrets of High Conversion Rates in YouTube Banner Designs for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-surface-software-enhancement-techniques-for-maximum-performance/"><u>Mastering Surface Software Enhancement Techniques for Maximum Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-not-found-errors-on-pc-windows/"><u>Overcoming 'Not Found' Errors on PC Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/integrated-thermal-management-windows-edition/"><u>Integrated Thermal Management: Windows Edition</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-the-ultimate-guide-to-auditory-clarity-prime-apps-for-removing-unwanted-sounds/"><u>New In 2024, The Ultimate Guide to Auditory Clarity Prime Apps for Removing Unwanted Sounds</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/focus-on-clarity-the-best-zooming-video-editors-list-for-2024/"><u>Focus on Clarity - The Best Zooming Video Editors List for 2024</u></a></li>
<li><a href="https://location-fake.techidaily.com/3utools-virtual-location-not-working-on-xiaomi-redmi-note-12-pro-4g-fix-now-drfone-by-drfone-virtual-android/"><u>3uTools Virtual Location Not Working On Xiaomi Redmi Note 12 Pro 4G? Fix Now | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-handle-exception-breaking-point-issues-on-pc/"><u>How to Handle Exception Breaking Point Issues on PC</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-the-ultimate-list-10-linux-video-editing-software-like-premiere-for-2024/"><u>Updated The Ultimate List 10 Linux Video Editing Software Like Premiere for 2024</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-ways-to-stop-parent-tracking-your-apple-iphone-11-drfone-by-drfone-virtual-ios/"><u>In 2024, Ways to stop parent tracking your Apple iPhone 11 | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-inside-outlook-on-vr-good-and-bad-aspects/"><u>[Updated] Inside Outlook on VR  Good & Bad Aspects</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-overcoming-printer-error-0xfffffff/"><u>Expert Advice: Overcoming Printer Error 0xFFFFFFF</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/o-make-a-youtube-reaction-video-3-ways/"><u>How to Make a YouTube Reaction Video? [3 Ways]</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-the-art-of-music-infused-snapchatting-for-2024/"><u>[New] The Art of Music-Infused Snapchatting for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-screencapturepro-review-expert-insights-and-comparisons/"><u>[New] ScreenCapturePro Review  Expert Insights and Comparisons</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-resource-scheduling-for-android-on-windows-wsl/"><u>Efficient Resource Scheduling for Android on Windows WSL</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-geforce-experience-setting-retrieval-failure-on-windows-1111/"><u>Resolving 'GeForce Experience' Setting Retrieval Failure on Windows 11/11</u></a></li>
<li><a href="https://windows11.techidaily.com/prioritize-your-data-spotting-the-biggest-disk-space-eaters/"><u>Prioritize Your Data: Spotting the Biggest Disk Space Eaters</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-win11-pointer-adjustments-for-access/"><u>Mastering Win11 Pointer Adjustments for Access</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-champions-of-cutting-edge-vr-creation/"><u>2024 Approved  Champions of Cutting-Edge VR Creation</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-differences-how-exe-files-function-compared-to-msi/"><u>Dissecting Differences: How Exe Files Function Compared to Msi</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-troubleshooting-excel-display-issue-in-notepad/"><u>Remedy: Troubleshooting Excel Display Issue in Notepad</u></a></li>
</ul></div>
