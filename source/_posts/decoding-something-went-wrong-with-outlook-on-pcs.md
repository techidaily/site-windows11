---
title: Decoding Something Went Wrong with Outlook on PCs
date: 2024-07-11T22:07:41.651Z
updated: 2024-07-12T22:07:41.651Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Decoding Something Went Wrong with Outlook on PCs
excerpt: This Article Describes Decoding Something Went Wrong with Outlook on PCs
keywords: Outlook Error Fixing Guide,Email Client Troubleshooting,PC Outlook Malfunction Solutions,Resolve Outlook Crash Issues,Improve Outlook Performance Windows,Identify Outlook Glitches on PCs,Optimize Outlook Sync on Computer
thumbnail: https://thmb.techidaily.com/ad7d05b0030775951042fde08b0fbde9a0ebb4cf05f0435bf5618af5d7b42ae3.jpg
---

## Decoding Something Went Wrong with Outlook on PCs

 Microsoft Outlook's somewhat vague "Something went wrong" error message may appear when you are trying to set up your account or using the app in general. Without a clear indication of what’s going wrong, fixing such Outlook errors can be tricky.

 To help out, we have listed all the possible ways to fix the “Something went wrong” error in Outlook for Windows.

## 1\. Edit Registry Files

 Autodiscover is a nifty feature that allows Outlook to automatically configure email account settings without requiring manual input from the user. If this service receives any unexpected results from the third-party web server, Outlook might display the "Something went wrong" error message. To resolve this, you will need to make a few changes to the registry files on your PC.

 As you may be aware, making incorrect changes to the registry files can render your system inoperable. Hence, it is advisable to [back up all of your registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Press **Win + R** to open the Run dialog box.
2. Type **regedit** in the box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Paste the following path in the address bar at the top and press **Enter** to quickly navigate to the **AutoDiscover** key.  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Office\XX.0\Outlook\AutoDiscover`  
 Replace **XX.0** in the above path with your version of Office (**16.0** \= Office 365, Office 2019, and Office 2016, **15.0** \= Office 2013).
5. Right-click on the **AutoDiscover** key and select **New > DWORD (32-bit) Value**.  
![Create DWORD in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-dword-in-registry.jpg)

1. Rename the DWORD to **ExcludeHttpsRootDomain**.
2. Double-click the newly created DWORD and set its value to **1**.
3. Right-click on the **AutoDiscover** key again and select **New > DWORD (32-bit) Value**. Name the DWORD **ExcludeHttpsAutoDiscoverDomain**.
4. Double-click the **ExcludeHttpsAutoDiscoverDomain** DWORD and set its value to **1**.
5. Create two more DWORD values named **ExcludeSrvRecord** and **ExcludeLastKnownGoodUrl** and set their values to **1**.  
![AutoDiscover in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/autodiscover-in-registry-editor.jpg)

 Restart your PC after this and check if you still get the “Something went wrong” error in Microsoft Outlook.

## 2\. Open Outlook in Safe Mode

 At times, third-party add-ins in Outlook can disrupt app processes and trigger such errors. To verify if this is the case, you can [try starting Outlook in safe mode](https://www.makeuseof.com/outlook-safe-mode/).

 If Outlook works as expected, it means one of your add-ins is causing the issue. To find the culprit, you'll need to disable all the add-ins and re-enable them one at a time. Here are the steps for the same.

1. In the Outlook app, click on **File > Options**.
2. In the **Outlook Options** window, select the **Add-ins** tab from the left sidebar.
3. Click the **Go** button next to **COM Add-ins**.
4. Clear all the checkboxes to disable your add-ins and then click **OK**.  
![Disable Outlook Add-Ins-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-outlook-add-ins-1.jpg)

 Restart the Outlook app and enable your add-ins one by one until the error occurs again. Once you find the troublesome add-in, consider removing it to avoid such issues.

## 3\. Clear the Outlook Cache

 Outdated or corrupted cache data can cause Outlook to misbehave and display unusual errors. If this is the cause of your problems, clearing the Outlook app cache should get things going again. To do so, use these steps:

1. Press **Win + R** to open the Run command (see [how to open the Windows Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more information).
2. Type **%localappdata%\\Microsoft\\Outlook** in the text box and press **Enter**.
3. In the **RoamCache** folder that opens, press **Ctrl + A** to select all the files, and click the **trash** icon at the top to delete them.  
![Delete Outlook Cache Data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-outlook-cache-data.jpg)

## 4\. Repair Your Outlook Profile

 Another reason why you may get the “Something went wrong” error in Outlook is if there is an issue with your Outlook profile. You can try repairing your Outlook profile to see if that restores normalcy. Here are the steps for the same.

1. Open the Outlook app and click the **File** menu at the top.
2. In the Info tab, click on **Account Settings** and select **Account Settings**.
3. Select your profile under the **Email** tab and click **Repair**.  
![Repair Outlook Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-outlook-account.jpg)

 Allow Outlook to repair your profile and then restart the app.

## 5\. Remove and Re-Add Your Account

 If repairing your Outlook profile does not help, your next best option is to remove your email account from the Outlook app and add it back. Here's how to do it.

1. Open the Outlook app.
2. Navigate to **File > Info > Account Settings > Account Settings**.
3. Under the **Email** tab, select your account and click **Remove**.
4. Select **Yes** to continue.  
![Remove Outlook Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/remove-outlook-account.jpg)

 Once removed, click the **New** option under the **Email** tab and set up your account again.

## 6\. Remove Outlook Password From Credential Manager

 Are you getting the "Something went wrong" error while adding an account in Outlook? That might be caused by outdated data in the [Credential Manager](https://www.makeuseof.com/windows-credential-manager-guide/). You can try removing any Outlook entries from the Credential Manager to fix the issue.

1. Click the **magnifying icon** on the taskbar.
2. Type **credential manager** in the box and select the first result that appears.
3. Select **Windows Credentials**.
4. Select the entry related to your account and click **Remove**.  
![Remove Outlook Credentials From Windows PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/remove-outlook-credentials-from-windows-pc.jpg)

## 7\. Run the Office Repair Tool

 Running Microsoft’s Office repair tool is an effective way to resolve issues with Office apps like Outlook. So, if the above tips don't help, you can run the Office repair tool as a last resort.

1. Press **Win + S** to open the search menu.
2. Type **Control Panel** in the box and press **Enter**.
3. Click the drop-down menu in the top right corner to select **Large icons**.
4. Click on **Programs and Features**.
5. Select **Microsoft Office suite** on the list and click the **Change** button at the top.
6. Select the **Quick Repair** option.
7. Click the **Repair** button.  
![Repair Microsoft Office](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/repair-microsoft-office.jpg)

 If the problem persists even after this, repeat the above steps to perform an **Online Repair**. This process may take a little longer, but it’s most likely to resolve the issue.

## Fixing Outlook's “Something Went Wrong” Error on Windows

 Encountering such errors in the Outlook app can affect your productivity and leave you frustrated. We hope that the solutions listed above have helped in resolving the “Something went wrong” error in Microsoft Outlook.

 That said, if all of the above tips prove ineffective, we recommend you contact the official Microsoft support team for further assistance.

 To help out, we have listed all the possible ways to fix the “Something went wrong” error in Outlook for Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-http.techidaily.com/updated-avoiding-misdated-memories-with-exact-times-for-2024/"><u>[Updated] Avoiding Misdated Memories with Exact Times for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-at-win-11-games-easy-steps-for-enhancing-fun-and-performance/"><u>Winning at Win 11 Games: Easy Steps for Enhancing Fun and Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-rectifying-memory-issues-on-pcs/"><u>Guide to Rectifying Memory Issues on PCs</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-disruptive-beats-curated-list-of-music-mutators/"><u>[Updated] In 2024, Disruptive Beats  Curated List of Music Mutators</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-steps-to-correct-windows-11-0x800f0922-error/"><u>Effective Steps to Correct Windows 11 0X800F0922 Error</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-the-terminal-workflow-setting-it-as-main/"><u>Transforming the Terminal Workflow: Setting It As Main</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-master-list-of-best-mp4-players/"><u>[New] Master List of Best MP4 Players</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-and-solving-hard-drive-failures/"><u>Deciphering and Solving Hard Drive Failures</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-instagram-video-editor-how-to-edit-instagram-videos/"><u>[Updated] In 2024, Instagram Video Editor  How to Edit Instagram Videos</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-from-celluloid-to-screen-adapting-your-vids-for-ig/"><u>[New] In 2024, From Celluloid to Screen  Adapting Your Vids for IG</u></a></li>
<li><a href="https://extra-skills.techidaily.com/quick-play-music-10-best-apps-phones-for-2024/"><u>Quick Play Music  10 Best Apps, Phones for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/downloading-woes-how-to-fix-windows-11-transfer-issues-2/"><u>Downloading Woes: How to Fix Windows 11 Transfer Issues (2)</u></a></li>
<li><a href="https://windows11.techidaily.com/alleviating-overuse-of-wmi-in-windows-installer/"><u>Alleviating Overuse of WMI in Windows Installer</u></a></li>
<li><a href="https://review-topics.techidaily.com/motorola-data-recovery-recover-lost-data-from-motorola-moto-g73-5g-by-fonelab-android-recover-data/"><u>Motorola Data Recovery – recover lost data from Motorola Moto G73 5G</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-elevate-your-storytelling-wevideos-online-video-editing-solution/"><u>Updated 2024 Approved Elevate Your Storytelling WeVideos Online Video Editing Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-install-non-verified-windows-applications/"><u>Steps to Install Non-Verified Windows Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-updating-windows-cards-a-comprehensive-guide/"><u>Swiftly Updating Windows Cards: A Comprehensive Guide</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-seek-out-the-bell-echo-simulation-soundtrack/"><u>New Seek Out the Bell Echo Simulation Soundtrack</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-chrome-crashes-or-wont-open-on-honor-100-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Chrome Crashes or Wont Open on Honor 100 | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-vivo-t2x-5g-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>In 2024, Vivo T2x 5G ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-at-world-of-warcraft-defy-error-132/"><u>Winning at World of Warcraft: Defy Error #132</u></a></li>
<li><a href="https://windows11.techidaily.com/taskers-curiosity-non-edge-process-puzzles/"><u>Tasker's Curiosity: Non-Edge Process Puzzles</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-how-to-custom-your-youtube-channel-url-super-easy-for-2024/"><u>[Updated] How to Custom Your YouTube Channel URL – Super Easy for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unwinding-windows-11s-0x8004def5-onedrive-snags/"><u>Unwinding Windows 11'S 0X8004DEF5 Onedrive Snags</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-lessons-from-the-leading-ogg-file-converters-for-2024/"><u>Updated Lessons From the Leading OGG File Converters for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/create-a-convenient-windows-environment-portable-software-icons/"><u>Create a Convenient Windows Environment: Portable Software Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tune-your-system-control-delete-confirmations/"><u>Fine-Tune Your System: Control Delete Confirmations</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-a-new-era-for-content-creators-non-tiktok-alternatives-unveiled/"><u>[New] In 2024, A New Era for Content Creators  Non-TikTok Alternatives Unveiled</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/social-gaming-galore-the-ultimate-metaverse-list-for-2024/"><u>Social Gaming Galore  The Ultimate Metaverse List for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-above-the-mainstage-significant-youtube-meetings/"><u>[New] 2024 Approved  Above the Mainstage  Significant YouTube Meetings</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-camera-app-crash-microsofts-windows-error-0xa00f425d/"><u>Eliminating Camera App Crash: Microsoft's Windows Error 0xA00F425D</u></a></li>
<li><a href="https://extra-hints.techidaily.com/step-by-step-method-for-capturing-internet-radio-frequencies/"><u>Step-by-Step Method for Capturing Internet Radio Frequencies</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/unlocking-ez-grabber-a-quick-guide-to-downloading-setting-up/"><u>Unlocking EZ Grabber - A Quick Guide to Downloading, Setting Up</u></a></li>
<li><a href="https://windows11.techidaily.com/time-is-money-restoring-windows-server-time-quickly/"><u>Time Is Money: Restoring Windows Server Time Quickly</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-androidprocessmedia-has-stopped-on-vivo-g2-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android.Process.Media Has Stopped on Vivo G2 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/diagnosing-absent-monitor-display-issue/"><u>Diagnosing Absent Monitor Display Issue</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-contacts-files-from-g24-power-by-fonelab-android-recover-contacts/"><u>How To  Restore Missing Contacts Files from G24 Power.</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-a-guide-infinix-gt-10-pro-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>In 2024, A Guide Infinix GT 10 Pro Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-productivity-select-6-crucial-android-apps-for-windows-11/"><u>Boosting Productivity: Select 6 Crucial Android Apps for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-to-stop-fluctuating-printer-choices-on-pc/"><u>Tactics to Stop Fluctuating Printer Choices on PC</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-oppo-a78-5g-drfone-by-drfone-android/"><u>How To Use Allshare Cast To Turn On Screen Mirroring On Oppo A78 5G | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-whatsapp-messages-on-htc-u23-without-them-knowing-drfone-by-drfone-virtual-android/"><u>How to Track WhatsApp Messages on HTC U23 Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-creativity-windows-outlook-calendar-personalization-guide/"><u>Unleash Creativity: Windows Outlook Calendar Personalization Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-fixing-non-working-display-driver-on-windows-11/"><u>Guide to Fixing Non-Working Display Driver on Windows 11</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-hide-location-on-apple-iphone-15-plus-and-android-without-others-knowing-drfone-by-drfone-virtual-ios/"><u>In 2024, Hide location on Apple iPhone 15 Plus and Android without others knowing | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/best-approaches-to-regulate-device-connections-in-windows/"><u>Best Approaches to Regulate Device Connections in Windows</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/boost-your-tiktok-video-speed-easy-methods-explored/"><u>Boost Your TikTok Video Speed  Easy Methods Explored</u></a></li>
<li><a href="https://windows11.techidaily.com/what-does-s-mode-mean-in-the-world-of-windows-11-updates/"><u>What Does 'S Mode' Mean in the World of Windows 11 Updates?</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-microsoft-store-crash-error-0x800704cf/"><u>Tackling Microsoft Store Crash: Error 0X800704CF</u></a></li>
<li><a href="https://extra-resources.techidaily.com/market-precision-strategic-package-interpretations/"><u>Market Precision  Strategic Package Interpretations</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-inactive-windows-headsets-communication-line/"><u>Fixing Inactive Windows Headset's Communication Line</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-the-sound-engineers-roadmap-techniques-and-tools-for-reducing-ambient-noises-during-recording-sessions/"><u>New 2024 Approved The Sound Engineers Roadmap Techniques and Tools for Reducing Ambient Noises During Recording Sessions</u></a></li>
<li><a href="https://windows11.techidaily.com/top-techniques-to-quell-input-delay-on-windows-11/"><u>Top Techniques to Quell Input Delay on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/camouflage-computing-integrating-archives-into-digital-image-win/"><u>Camouflage Computing: Integrating Archives Into Digital Image WIN</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-how-to-record-a-podcast-on-iphone-or-ipad-best-for-interviews-and-trave/"><u>[New] How To Record a Podcast on iPhone or iPad (Best for Interviews & Trave</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/elevating-your-listening-palette-with-youtube-music/"><u>Elevating Your Listening Palette with YouTube Music</u></a></li>
<li><a href="https://windows11.techidaily.com/7-essential-steps-to-resolve-chrome-profile-errors/"><u>7 Essential Steps to Resolve Chrome Profile Errors</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-google-frp-lock-on-infinix-note-30-vip-racing-edition-by-drfone-android-unlock-remove-google-frp/"><u>Remove Google FRP lock on Infinix Note 30 VIP Racing Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/file-location-artistry-in-windows-11-exploring-best-practices-6-advanced-methods/"><u>File Location Artistry in Windows 11: Exploring Best Practices (6 Advanced Methods)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-igtv-deactivation-methods/"><u>[New] 2024 Approved  IGTV Deactivation Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-dive-into-and-remove-windows-usage-logs/"><u>How to Dive Into and Remove Windows Usage Logs</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-overhaul-pretend-its-windows-98-edition/"><u>Windows Overhaul: Pretend It's Windows 98 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-microphone-setup-with-the-latest-windows-11-features/"><u>Streamlining Microphone Setup with the Latest Windows 11 Features</u></a></li>
</ul></div>
