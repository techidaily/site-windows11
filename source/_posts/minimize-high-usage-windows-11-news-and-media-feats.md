---
title: Minimize High Usage Windows 11 News & Media Feats
date: 2024-07-11T22:00:29.065Z
updated: 2024-07-12T22:00:29.065Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Minimize High Usage Windows 11 News & Media Feats
excerpt: This Article Describes Minimize High Usage Windows 11 News & Media Feats
keywords: Minimize High Usage,Optimize Win11 Performance,Reduce Resource-Heavy Tasks,Efficient Win11 Usage,Enhance Win11 Media Features,Boost Win11 Productivity,Improve Win11 High Use
thumbnail: https://thmb.techidaily.com/829637766daad5158a0e2799ab45977f98c34111cdb4f87264835a3e2bfe371a.jpg
---

## Minimize High Usage Windows 11 News & Media Feats

 News and Interests is a Windows 11 and 10 widget on your taskbar to show weather, sports, and news events at a glance. While it seems like a harmlessly unwanted feature, it can sometimes cause high memory usage on your computer.

 This News and Interests issue occurs due to a potential memory leak and can make your computer run slow. So, if you want to make your computer run fast again, follow these steps to fix the News and Interests high memory usage problem.

## 1\. Install Windows Update Hotfix

![windows 11 update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-update.jpg)

 Reportedly, the problem occurs due to a Windows bug. To fix the problem, Microsoft released cumulative update KB5010415 for Windows 11 and 10\. So, check if you have any pending updates for your computer and install them to see if that helps resolve the error.

To install a Windows 11 update:

1. Press**Win + I** to open**Settings** .
2. Open the**Windows Update** tab in the left pane. Check if a new update is available. If not, click on**Check for updates** .
3. Windows will scan the Microsoft servers for newer updates. If available, click on**Download & install** . Once installed, restart your computer and check for any improvements.

 You can also learn how to [manage Windows 10 updates](https://www.makeuseof.com/tag/manage-windows-update-windows-10/) to ensure your computer is constantly updated. However, if you can find this specific update on your computer, go to [Microsoft Update Catalog](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) and search for the update. If available, download the update and run the installer to install it manually.

## 2\. Turn Off News and Interests

 If you don't really use the News and Interests feature, you're better off turning it off. That way, you can save on hardware resources and help your computer run faster.

### Turn Off News and Interests on Windows 10

 If you don't use News and Interests, you can turn off the feature from the Taskbar on Windows 10\. To turn off News and Interests on Windows 10:

1. Right-click on the**Taskbar** to open the context menu.  
![turn off news and interests](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-news-and-interestsjpg.jpg)
2. Next, go to**News and Interests** and select**Turn Off** .

 That's it. With the**News and Interests** feature disabled, your memory usage should return to its normal range.

### Disable News and Interests on Windows 11

![disable widgets Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/disable-widgets-windows-11.jpg)

 Unfortunately, News and Interests is a core feature of Windows 11 widgets. If the lack of Widgets isn't a concern, you can [disable the Windows 11 Widget app](https://www.makeuseof.com/windows-11-disable-widgets/) to get rid of the resource-hog news feed on your computer. However, if you find the widgets useful, you must endure the News and Interests feature.

 The easiest way to disable Widgets is from the Taskbar settings. If that does not work or if your Windows 11 isn't activated, you can use Registry Editor to disable the Widgets icon from the taskbar.

 If the issue persists even after disabling News and Interest, try to [perform a Windows 11 repair reinstall](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/) . During a repair reinstall, Windows will reinstall the operating system without removing your personal files and apps.

## 3\. Disable News and Interests Using the Group Policy Editor

 On Windows 11, you can configure News and Interests on the taskbar policy to disable the feature and prevent high memory usage. Group Policy Editor (GPEdit) is a Windows component and is not only available on the OS's Pro, Enterprise, and Education editions.

 If you are on Windows 11 Home, follow these steps to [enable gpedit on Windows Home](https://www.catalog.update.microsoft.com/) and then proceed with the steps below:

1. Press**Win + R** to open**Run** .
2. Type**gpedit.msc** and click**OK** to open**Group Policy Editor** .
3. In Group Policy Editor, navigate to the following location:  
`Computer Configuration > Administrative Templates > Windows Components > News and Interests`
4. In the right pane, right-click on**Enable News and Interests** **on the taskbar** policy and select**Edit** .  
![turn off news and interest disabled 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-news-and-interest-disabled-1.jpg)
5. Select**Disabled** and click**Apply** and**OK** to save the changes.  
![turn off news and interest disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-news-and-interest-disabled.jpg)
6. Close Group Policy Editor and restart your computer.

 After restarting your computer, the News and Interests feature should no longer appear. Launch the task manager and check for improvements in your PC's CPU and memory usage.

## 4\. Disable News and Interests Using the Registry Editor on Windows 10

 You can disable the feed feature using the Windows Registry if you don't have Group Policy Editor. For this, you'll need to create an EnableFeeds value and set it to 0 to disable it.

 Incorrect modifications to the Windows Registry can cause your system to malfunction. We recommend [creating a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before making any changes to the registry entries.

To disable the news feed feature using Windows Registry:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open**Registry Editor** .  
![registry editor new key Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/registry-editor-new-key-windows.jpg)
3. In Registry Editor, navigate to the following location. You can copy and paste the registry path for quicker navigation:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows`
4. Right-click on the**Windows** key in the left pane.
5. Select**New > Key** . Rename the key as**Windows Feeds** .  
![registry editor new key Windows new DWORd value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/registry-editor-new-key-windows-new-dword-value.jpg)

1. Next, right-click the**Windows Feeds** key and select**New > DWORD (32-bit) Value** .
2. Rename the new value as**EnableFeeds** .
3. Double-click on the**EnableFeeds** value to edit it.  
![registry editor new key Windows new DWORd value 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/registry-editor-new-key-windows-new-dword-value-0.jpg)
4. Type**0** in the**Value data** field and click**OK** to save the changes.
5. Close the Registry Editor and restart your computer to apply the changes.

## 5\. Add and Disable EnableFeeds Using PowerShell

![powershell add registry key value Windows feeds Enable feeds](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/powershell-add-registry-key-value-windows-feeds-enable-feeds.jpg)

 You can also add and modify the EnableFeeds value in the Windows Registry using PowerShell. To do this:

1. Press the**Win** key and type**powershell** .
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell terminal, copy and paste the following entry and press Enter:  
`REG ADD "HKLM\SOFTWARE\Policies\Microsoft\Windows\Windows Feeds" /v "EnableFeeds" /t REG_DWORD /d 0 /f`
4. The above command will create a new**Windows Feeds** subkey and contain the value**EnableFeeds** set to disabled.
5. If there are no errors, type**exit** and press**Enter** to close PowerShell. Restart your Computer and check for any improvements.

## Fix the News and Interests Feature's High Memory Usage on Windows

 Memory leakage is a common cause for the News and Interests high memory usage issue. While a hotfix is available, you'll need to disable the News and Interests widget item to resolve the problem if the issue persists.


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
<li><a href="https://windows11.techidaily.com/windows-users-beware-is-yourphoneexe-safe-to-use/"><u>Windows Users Beware: Is YourPhone.exe Safe to Use?</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-nubia-red-magic-8s-pro-phone-without-password-by-drfone-android/"><u>How To Unlock Nubia Red Magic 8S Pro Phone Without Password?</u></a></li>
<li><a href="https://windows11.techidaily.com/software-selection-showdown-on-windows-choc-vs-wm/"><u>Software Selection Showdown on Windows: Choc vs WM</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-login-audit-success-or-no-go-indicators/"><u>Windows Login Audit: Success or No-Go Indicators</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-support-functionality-in-windows-11-help/"><u>Restoring Support Functionality in Windows 11 Help</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-unleashing-potential-gopro-karmas-journey/"><u>[New] Unleashing Potential  GoPro Karma's Journey</u></a></li>
<li><a href="https://windows11.techidaily.com/address-common-printer-glitches-in-windows-11/"><u>Address Common Printer Glitches in Windows 11</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-from-beginner-to-pro-final-cut-pro-tutorials-for-2024/"><u>New From Beginner to Pro Final Cut Pro Tutorials for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-unleash-your-creativity-gopro-video-editing-on-mac-made-easy/"><u>New Unleash Your Creativity GoPro Video Editing on Mac Made Easy</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/night-photography-perfection-with-iphones/"><u>Night Photography Perfection with iPhones</u></a></li>
<li><a href="https://windows11.techidaily.com/5-key-fixes-to-stop-rpc-failures-in-windows/"><u>5 Key Fixes to Stop RPC Failures in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-your-windows-11-program-choices/"><u>Streamlining Your Windows 11 Program Choices</u></a></li>
<li><a href="https://windows11.techidaily.com/the-8-different-ways-to-restart-your-windows-computer/"><u>The 8 Different Ways to Restart Your Windows Computer</u></a></li>
<li><a href="https://howto.techidaily.com/top-10-fixes-for-phone-keep-disconnecting-from-wi-fi-on-vivo-y100t-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 10 Fixes for Phone Keep Disconnecting from Wi-Fi On Vivo Y100t | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/slowing-down-the-high-life-excess-in-windowed-worlds/"><u>Slowing Down the High Life Excess in Windowed Worlds</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-endless-entertainment-escapade-top-tier-free-films-on-youtube/"><u>[Updated] Endless Entertainment Escapade  Top-Tier Free Films on YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-sleep-mode-anomalies-why-it-frustrates-users/"><u>Windows' Sleep Mode Anomalies: Why It Frustrates Users</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-spinning-stories-rotate-videos-to-captivate-your-instagram-community/"><u>In 2024, Spinning Stories  Rotate Videos to Captivate Your Instagram Community</u></a></li>
<li><a href="https://windows11.techidaily.com/6-methods-for-reviving-windows-command-line-interface/"><u>6 Methods for Reviving Windows' Command Line Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/speed-up-taskbar-interaction-enabledisable-ai-on-win-11/"><u>Speed Up Taskbar Interaction: Enable/Disable AI on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-secrets-to-stable-apex-play-on-windows-11/"><u>Unlocking the Secrets to Stable Apex Play on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-tasks-in-windows-11-with-a-customized-run-command-setup/"><u>Streamline Tasks in Windows 11 with a Customized Run Command Setup</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/mastering-memory-allocation-elevating-minecraft-experience/"><u>Mastering Memory Allocation  Elevating Minecraft Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-dual-defense-opt-for-single-antivirus-in-windows-systems/"><u>Avoid Dual Defense: Opt for Single Antivirus in Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-unlock-your-computers-windows-license/"><u>Techniques to Unlock Your Computer's Windows License</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-power-of-hashtags-in-growing-your-instagram-reel-presence/"><u>The Power of Hashtags in Growing Your Instagram Reel Presence</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-mastering-response-etiquette-discord-messaging-guide-for-2024/"><u>[New] Mastering Response Etiquette  Discord Messaging Guide for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/present-day-drones-paving-way-for-futuristic-advancements-for-2024/"><u>Present-Day Drones Paving Way for Futuristic Advancements for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/secrecy-in-posts-how-to-oc-for-2024/"><u>Secrecy in Posts  How to Oc for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-crafting-your-signature-tone-a-comprehensive-zoom-recording-workshop/"><u>[Updated] Crafting Your Signature Tone  A Comprehensive ZOOM Recording Workshop</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-windows-sluggish-discord-overlay-performance/"><u>Reviving Windows' Sluggish Discord Overlay Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-fixing-0x8009030e-on-virt-environments/"><u>Step-by-Step Guide: Fixing 0X8009030E on Virt Environments</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-blank-display-in-windows-remoting-services/"><u>Addressing Blank Display in Windows Remoting Services</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/best-10-web-based-hd-screen-capture-tools/"><u>Best 10 Web-Based HD Screen Capture Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-silent-sounds-on-windows-devices/"><u>Troubleshooting Silent Sounds on Windows Devices</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-vivo-v30-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Vivo V30 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-lav-filters-a-comprehensive-guide-to-effective-use-in-windows/"><u>Mastery Over LAV Filters: A Comprehensive Guide to Effective Use in Windows</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-recording-lenovo-fast-and-fuss-free-tips/"><u>[New] 2024 Approved  Recording Lenovo  Fast and Fuss-Free Tips</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/how-to-concatenate-videos-using-ffmpeg-for-2024/"><u>How to Concatenate Videos Using FFmpeg for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharge-performance-conquering-windows-lag-issues/"><u>Supercharge Performance: Conquering Windows Lag Issues</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-cyber-profile-pixelation-crafting-a-playful-look/"><u>[Updated] In 2024, Cyber-Profile Pixelation  Crafting a Playful Look</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-in-2024-mastering-tiktok-aspect-ratios-a-step-by-step-guide/"><u>Updated In 2024, Mastering TikTok Aspect Ratios A Step-by-Step Guide</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-identify-some-outdated-your-drivers-on-windows-11107-by-drivereasy-guide/"><u>Use Device Manager to identify some outdated your drivers on Windows 11/10/7</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-right-click-customization-compatibility-tool-inclusion/"><u>Windows Right-Click Customization: Compatibility Tool Inclusion</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-slow-windows-apps-ensure-robust-web-linkage/"><u>Revive Slow Windows Apps: Ensure Robust Web Linkage</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-integration-how-to-get-and-run-msibundle-and-appxappxbundles/"><u>Seamless Integration: How to Get & Run MsiBundle & Appx/Appxbundles</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-tips-for-a-seamless-phone-screen-record/"><u>[Updated] In 2024, Tips for a Seamless Phone Screen Record</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-in-depth-look-at-12-techniques-for-storing-web-based-songs/"><u>[New] In-Depth Look at 12 Techniques for Storing Web-Based Songs</u></a></li>
<li><a href="https://windows11.techidaily.com/additional-updates-available-in-windows-11s-latest-release/"><u>Additional Updates Available in Windows 11'S Latest Release</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-full-potential-of-the-windows-11-taskbar/"><u>Unlock the Full Potential of the Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/reset-windows-strategies-8-techniques-unveiled/"><u>Reset Windows Strategies: 8 Techniques Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-offline-status-of-valve-games-via-steam-desktop-client/"><u>Addressing Offline Status of Valve Games via Steam Desktop Client</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-top-6-clearcut-android-recorder-options-no-ads-for-2024/"><u>[Updated] Top 6 Clearcut Android Recorder Options (No Ads) for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-to-troubleshoot-loaded-lol-screens/"><u>Tactics to Troubleshoot Loaded LOL Screens</u></a></li>
</ul></div>
