---
title: Reversing File Locks on Windows OS
date: 2024-09-09T11:58:19.848Z
updated: 2024-09-10T11:58:19.848Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reversing File Locks on Windows OS
excerpt: This Article Describes Reversing File Locks on Windows OS
keywords: Reverse File Access Windows,Unlocking Files Windows PC,Overcoming File Locks Windows,Removing File Restrictions Windows,Clearing Locked Files Windows OS,Bypassing File Protection Windows,Disabling File Lock Windows
thumbnail: https://thmb.techidaily.com/356d504c4e521db72b45b5ec62fa587016c69e83da4a3303db46e26dc1ec6ec7.jpg
---

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2136548/16384" target="_top" id="2136548">
  <img src="//a.impactradius-go.com/display-ad/16384-2136548" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136548/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Reversing File Locks on Windows OS

 When a file is marked as read-only on Windows, you can only view it and not change it in any way. This essentially protects important files from unauthorized changes.

 On Windows, you can set or remove the read-only attribute for a file by modifying its properties. Alternatively, you can also run a command in Command Prompt or Windows PowerShell to do the same. In this article, we take a look at all of them.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118320/7443" target="_top" id="2118320">
  <img src="//a.impactradius-go.com/display-ad/7443-2118320" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118320/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. How to Change the Read-Only Attribute for Files by Modifying Properties

 The easiest way to set or remove the read-only attribute for a file on Windows is by modifying its properties. Here’s how you can go about it.

1. [Open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to the file for which you want to change the read-only attribute.
2. Right-click on your file and select**Properties** .
3. Under the**General** tab, check or uncheck the**Read-only** box.
4. Click**Apply** followed by**OK** .  
![Change Read-Only Attribute by Modifying Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-by-Modifying-Properties.jpg)

 Note that Windows may prevent you from changing the read-only attribute of a file if you don’t have the necessary permissions to modify the folder in which the file is located. In that case, you must take ownership of the folder first. If you need help, check our guide on[how to take ownership of folders on Windows](<http://How> to Take Ownership of Folders in Windows 10 & 11) .

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137974/21526" target="_top" id="2137974">
  <img src="//a.impactradius-go.com/display-ad/21526-2137974" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137974/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. How to Change the Read-Only Attribute for Files Using the Command Prompt

 Command Prompt is one of two command-line tools available on Windows. You can use it to run batch files, troubleshoot errors, and perform various other tasks. It also lets you change a file's read-only attribute with a single command. Here are the steps you need to follow.

1. Right-click on the file for which you want to modify the read-only attribute and select**Copy as path** .
2. Press**Win + X** to open the Power User menu.
3. Select**Terminal (Admin)** from the list.
4. Select**Yes** when the User Account Control (UAC) prompt appears.
5. In the console, type the following command and press**Enter** to set your file as read-only.  
`attrib +r "FilePath"`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

![Change Read-Only Attribute With Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-Command-Prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123735/7443" target="_top" id="2123735">
  <img src="//a.impactradius-go.com/display-ad/7443-2123735" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123735/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Once you run the above command, the file will be set as read-only. Likewise, if you want to remove the read-only attribute for a file, use this command:

`attrib -r "FilePath"`

 Once you remove the read-only attribute for a file, you should be able to edit or modify it.

 Like using Command Prompt? Check our guide to learn[how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115946/19272" target="_top" id="2115946">
  <img src="//a.impactradius-go.com/display-ad/19272-2115946" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115946/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. How to Change the Read-Only Attribute for Files Using Windows PowerShell

 You can also run a command in[Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) to change the read-only attribute for a file.

To change the read-only attribute using PowerShell:

1. Right-click on the file for which you want to change the read-only attribute and select**Copy as path** .
2. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
3. Type**Windows PowerShell** and select**Run as Administrator** .
4. Select**Yes** when the User Account Control (UAC) prompt shows up.
5. Paste the following command and press**Enter** to set your file as read-only.  
`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $True`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

![Change Read-Only Attribute With PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-PowerShell.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135411/19272" target="_top" id="2135411">
  <img src="//a.impactradius-go.com/display-ad/19272-2135411" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135411/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Alternatively, if you want to remove the read-only attribute for a file, use this command:

`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $False`

## Modifying the Read-Only Attribute for Files on Windows

 It’s worth noting that most system files on Windows will have the read-only attribute by default. So, make sure you don't modify them by mistake. For your other files, you can pick any of the above methods listed above to set or unset their read-only attribute.

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
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-gamers-guides-essential-tips-for-recording-riveting-races/"><u>[New] 2024 Approved  Gamers' Guides  Essential Tips for Recording Riveting Races</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-is-it-allowable-to-distribute-videos-via-social-networks/"><u>[New] 2024 Approved  Is It Allowable to Distribute Videos via Social Networks?</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-making-the-most-of-siri-voice-interactions-for-tiktok-content/"><u>[New] 2024 Approved  Making the Most of Siri Voice Interactions for TikTok Content</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-become-a-zoom-screenshare-pro-in-minutes/"><u>[New] In 2024, Become a Zoom Screenshare Pro in Minutes</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-brighten-up-techniques-for-improving-video-lighting-on-youtube/"><u>[New] In 2024, Brighten Up  Techniques for Improving Video Lighting on YouTube</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-from-live-stream-to-high-fidelity-choosing-budget-friendly-wav-tools/"><u>[New] In 2024, From Live Stream to High Fidelity  Choosing Budget-Friendly WAV Tools</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-mastering-telegram-web-a-beginners-walkthrough-for-2024/"><u>[New] Mastering Telegram Web  A Beginner's Walkthrough for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-cost-effective-obs-setup-tips/"><u>[Updated] 2024 Approved  Cost-Effective OBS Setup Tips</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-discover-and-make-the-fb-most-watched-song-videos/"><u>[Updated] Discover & Make the #FB Most-Watched Song Videos</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-elevate-engagement-todays-must-use-instagram-hashtags-for-2024/"><u>[Updated] Elevate Engagement  Today's Must-Use Instagram Hashtags for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-from-novice-to-expert-a-compreenhensive-fcp-guide/"><u>[Updated] In 2024, From Novice to Expert  A Compreenhensive FCP Guide</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-innovative-approaches-to-healthcare-marketing-on-facebook/"><u>2024 Approved  Innovative Approaches to Healthcare Marketing on Facebook</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-techniques-to-transfer-data-from-oppo-f23-5g-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Techniques to Transfer Data from Oppo F23 5G to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://facebook.techidaily.com/analyzing-how-and-why-telegram-skyroited-after-facebook-crash/"><u>Analyzing How and Why Telegram Skyroited After Facebook Crash</u></a></li>
<li><a href="https://tech-haven.techidaily.com/exploring-the-capabilities-can-chatgpt-operate-a-smart-house/"><u>Exploring the Capabilities: Can ChatGPT Operate a Smart House?</u></a></li>
<li><a href="https://windows11.techidaily.com/extend-windows-storage-while-keeping-files/"><u>Extend Windows Storage While Keeping Files</u></a></li>
<li><a href="https://windows11.techidaily.com/festive-features-for-a-windows-11-christmas-spread/"><u>Festive Features for a Windows 11 Christmas Spread</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-no-sound-device-error-in-windows-os/"><u>Fix No Sound Device Error in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-icue-how-to-resolve-no-device-found-error/"><u>Fixing ICUE: How to Resolve 'No Device Found' Error</u></a></li>
<li><a href="https://driver-error.techidaily.com/gtx-950-malfunctioning-with-code-43-heres-the-complete-solution-for-windows-10-users/"><u>GTX 950 Malfunctioning with Code 43? Here's the Complete Solution for Windows 10 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-cut-spotlight-wallpaper-icon-on-windows-11s-desk/"><u>Guide to Cut Spotlight Wallpaper Icon on Windows 11'S Desk</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-requested-resource-is-in-use-error-in-windows-11-and-11/"><u>How to Fix “The Requested Resource Is in Use” Error in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-jumpstart-your-qbittorrent-in-sluggish-state-windows/"><u>How to Jumpstart Your qBittorrent in Sluggish State (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rescue-your-windows-11-from-hypervisor-bsos-blues/"><u>How to Rescue Your Windows 11 From Hypervisor BSOS Blues</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-windows-shortcuts-from-acting-on-their-own/"><u>How to Stop Windows Shortcuts From Acting on Their Own</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-3-ways-to-track-apple-iphone-xs-without-them-knowing-drfone-by-drfone-virtual-ios/"><u>In 2024, 3 Ways to Track Apple iPhone XS without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-samsung-galaxy-m54-5g-frp-in-3-different-ways-by-drfone-android/"><u>In 2024, How To Bypass Samsung Galaxy M54 5G FRP In 3 Different Ways</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-video-editing-for-virality-a-comprehensive-guide-to-instagram-success/"><u>In 2024, Video Editing for Virality  A Comprehensive Guide to Instagram Success</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-is-a-sim-network-unlock-pin-get-your-htc-u23-pro-phone-network-ready-by-drfone-android/"><u>In 2024, What Is a SIM Network Unlock PIN? Get Your HTC U23 Pro Phone Network-Ready</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-learn-how-everything-works-on-poco-m6-pro-5g-drfone-by-drfone-virtual-android/"><u>Life360 Learn How Everything Works On Poco M6 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/logitech-unify-mismatch-in-win1110-fixed-guide/"><u>Logitech Unify Mismatch in Win11/10 - Fixed Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/masterful-strategies-for-resolving-zerox-typing-flaw-in-windows-11/"><u>Masterful Strategies for Resolving Zerox Typing Flaw in Windows 11</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/mastering-instagram-broadcasting-with-obs-a-step-by-step-guide/"><u>Mastering Instagram Broadcasting with OBS  A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-restoring-hibernation-mode/"><u>Mastering the Art of Restoring Hibernation Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-virtual-memory-in-windows-11-systems/"><u>Maximizing Virtual Memory in Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-system-restore-in-windows-a-comprehensible-tutorial/"><u>Navigating System Restore in Windows: A Comprehensible Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-highlighting-obstacles-in-windows-pdf-files/"><u>Overcome Highlighting Obstacles in Windows' PDF Files</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-blue-screen-errors-how-to-fix-0x8007045d-in-windows-11/"><u>Overcoming Blue Screen Errors: How to Fix 0X8007045d in Windows 11</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/perfecting-pronunciation-and-typography-of-spanish-accents/"><u>Perfecting Pronunciation and Typography of Spanish Accents</u></a></li>
<li><a href="https://windows11.techidaily.com/preserve-digital-progress-consistent-backups-on-windows/"><u>Preserve Digital Progress: Consistent Backups on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/prime-virtual-machines-designed-for-windows-11-devices/"><u>Prime Virtual Machines Designed for Windows 11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/pro-editing-techniques-with-powertoys-utilities/"><u>Pro Editing Techniques with PowerToys Utilities</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tips-overcoming-windows-winerror-messages/"><u>Quick Tips: Overcoming Windows WinError Messages</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-hyper-v-error-code-0x8009030e-on-windows-os/"><u>Resolving Hyper-V Error Code: 0X8009030E on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/restore-bluetooth-connection-fixing-mice-on-windows-xpvista/"><u>Restore Bluetooth Connection: Fixing Mice on Windows XP/Vista</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-ccleaner-performance-in-win11/"><u>Reviving CCleaner Performance in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/rog-ally-vs-asus-who-wins-the-steam-deck-war/"><u>ROG Ally Vs. ASUS: Who Wins the Steam Deck War?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/seeking-honesty-in-chatgpts-responses/"><u>Seeking Honesty in ChatGPT's Responses</u></a></li>
<li><a href="https://windows11.techidaily.com/separate-and-align-win-11-taskbar-items/"><u>Separate and Align Win 11 Taskbar Items</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-deactivation-of-windows-11-notifications/"><u>Speedy Deactivation of Windows 11 Notifications</u></a></li>
<li><a href="https://windows11.techidaily.com/tailor-fit-window-color-schemes-with-winterral/"><u>Tailor-Fit Window Color Schemes with WinTerral</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-overcome-code-0x0000004e-glitch/"><u>Techniques to Overcome Code 0X0000004E Glitch</u></a></li>
<li><a href="https://windows11.techidaily.com/the-new-age-laptops-at-ifa-2023-exposed/"><u>The New Age Laptops at IFA 2023 Exposed</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-taskbar-functionality-6-essential-upgrades-for-windows-11/"><u>Transforming Taskbar Functionality: 6 Essential Upgrades for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-steps-for-non-responsive-windows-11-spotify/"><u>Troubleshooting Steps for Non-Responsive Windows 11 Spotify</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-disabled-lsa-security-signal/"><u>Troubleshooting Windows' Disabled LSA Security Signal</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-hidden-features-in-windows-snipping-tool-for-flawless-screen-shots/"><u>Unlock Hidden Features in Windows Snipping Tool for Flawless Screen Shots.</u></a></li>
<li><a href="https://windows11.techidaily.com/unpacking-windows-maintenance-tools/"><u>Unpacking Window's Maintenance Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-and-fixing-directdraw-errors-in-win1011-systems/"><u>Unraveling and Fixing DirectDraw Errors in WIN10/11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-installation-conundrums-a-windows-guide/"><u>Unraveling Installation Conundrums: A Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-a-beginners-guide-to-screensavers/"><u>Win11: A Beginner's Guide to Screensavers</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-22h2-gets-another-year-of-optional-updates-what-this-means-for-you/"><u>Windows 11 22H2 Gets Another Year of Optional Updates: What This Means for You</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-uninstalling-made-easy-crafting-custom-shortcuts/"><u>Windows Uninstalling Made Easy: Crafting Custom Shortcuts</u></a></li>
</ul></div>
