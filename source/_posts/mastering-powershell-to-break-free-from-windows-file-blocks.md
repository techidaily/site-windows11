---
title: Mastering PowerShell to Break Free From Windows File Blocks
date: 2024-07-11T21:32:57.990Z
updated: 2024-07-12T21:32:57.990Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering PowerShell to Break Free From Windows File Blocks
excerpt: This Article Describes Mastering PowerShell to Break Free From Windows File Blocks
keywords: PowerShell Mastery,File Access Control,Bypass Windows Limits,Advanced Scripting Skills,Enhanced File Management,Automated Task Execution,Secure Administration Techniques
thumbnail: https://thmb.techidaily.com/d3f8a164ff7cec81bd719ff1860ad4b428bdab1ff70424914ce34922d708e742.jpg
---

## Mastering PowerShell to Break Free From Windows File Blocks

 So you’ve downloaded files onto a directory on your PC, but Windows doesn’t trust them? This is understandable because some files from the internet can harm your computer, but what if you know for sure that the files are safe? Luckily there’s an easy PowerShell command you can use to unblock all of them.

## How Do I Unblock Multiple Files Using PowerShell on Windows?

 You can easily unblock a file by right-clicking on it and going to**Properties** — If you're on Windows 11, you'll need to click**Show more options** first before you can see the**Properties** option in the context menu. And once you're there, select the**General** tab and tick**Unblock** at the bottom in the**Security** section.

![unblocking a file in Properties on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unblock-file-properties-windows.jpg)

 But what if you have more than one file you need to unblock? Doing this one by one can get tedious. Alternatively, you can execute a single PowerShell command to unblock multiple files in a directory. Here is the command structure you need to use:

`dir [path] | unblock-file -confirm`

 Just replace**path** in the square brackets with the file path of the directory that has the blocked files. You can grab the file path of the directory by right-clicking on it and selecting**Copy as path** .

![copying file path on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-as-path-windows-11.jpg)

 With the file path handy, follow the instructions below to use the unblock command in PowerShell:

1. Press**Win + S** to open Windows Search.
2. Type**powershell** in the search box and when the program appears in the search results, right-click on it and select**Run as administrator** . For more ways to open it, please read our guide on [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
3. Enter the unblock command in PowerShell and hit the**Enter** key to run it. This is what it looks like on our computer:  
![entering the unblock file command in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-command.jpg)
4. You will be asked to confirm each file you want to unblock, so type either**Y** for**Yes** or**N** for**No** and hit the**Enter** key. This confirmation step is due to the**\-confirm** portion of the command. It is completely optional, and you can omit it or type**A** to confirm all the files in the directory.  
![confirming files to unblock in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-confirm.jpg)

 There’s a way you can tell Windows to always trust files you download from the internet. To do that, please read our guide on [how to stop Windows 10 from blocking your downloaded files](https://www.makeuseof.com/stop-windows-10-from-blocking-your-downloaded-files/) . The instructions in the tutorial use the Registry Editor and Local Group Policy Editor, so they should also work on Windows 11.

## Now You Know How to Unblock Files You Know Are Safe

 With the instruction above unlocking a bunch of downloaded files in a directory should be easier. Keep in mind that you shouldn’t do this on files you don’t trust. The last thing you want to do is put your Windows PC at risk unnecessarily


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
<li><a href="https://article-helps.techidaily.com/2024-approved-best-practices-for-online-vhs-image-retouching-and-editing/"><u>2024 Approved  Best Practices for Online VHS Image Retouching and Editing</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-back-color-to-extend-volume-option-in-diskmgmt/"><u>Bring Back Color to Extend Volume Option in DiskMgmt</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-swiftly-move-data-fast-and-reliable-methods-to-direct-files-onto-your-computer/"><u>In 2024, Swiftly Move Data  Fast and Reliable Methods to Direct Files Onto Your Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-windows-11-stumbling-blocks-the-most-crucial-tips/"><u>Avoiding Windows 11 Stumbling Blocks: The Most Crucial Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-windows-operations-formulating-and-scrutinizing-reports/"><u>Understanding Windows Operations: Formulating & Scrutinizing Reports</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024s-elite-video-capturing-technology/"><u>2024'S Elite Video Capturing Technology</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-rectify-windows-security-faults/"><u>Comprehensive Guide to Rectify Windows Security Faults</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-a-recycle-bin-corrupted-error-on-windows-11-and-11/"><u>How to Fix a Recycle Bin Corrupted Error on Windows 11 & 11</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-macs-best-top-3-mkv-video-trimmers-for-2024/"><u>New Macs Best Top 3 MKV Video Trimmers for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-ultimate-list-the-finest-fps-titles-in-gaming/"><u>[New] 2024 Approved  Ultimate List  The Finest FPS Titles in Gaming</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-your-view-simple-fixes-for-windows-11-screen-haze/"><u>Transform Your View: Simple Fixes for Windows 11 Screen Haze</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-non-compliance-overcoming-intel-hd-graphics-errors/"><u>Addressing Non-Compliance: Overcoming Intel HD Graphics Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-managing-comic-files-in-windows-11/"><u>Comprehensive Guide to Managing Comic Files in Windows 11</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-virtualdub-vs-the-rest-a-comprehensive-review-of-video-editing-options/"><u>2024 Approved Virtualdub Vs. The Rest A Comprehensive Review of Video Editing Options</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-elevate-your-chat-with-discord-recording-techniques/"><u>[Updated] Elevate Your Chat with Discord Recording Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-windows-updates-0x80242016-hurdles/"><u>Avoiding Windows Update's 0X80242016 Hurdles</u></a></li>
<li><a href="https://extra-information.techidaily.com/samsung-secrets-crafting-compelling-time-lapses/"><u>Samsung Secrets  Crafting Compelling Time Lapses</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-reviving-photo-viewer-on-win-11-methods-explained/"><u>2024 Approved  Reviving Photo Viewer on Win 11 - Methods Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-non-admin-privilege-levels-in-windows-os/"><u>Adjusting Non-Admin Privilege Levels in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-combatting-windows-not-found-problem/"><u>Essential Tips: Combatting Windows Not Found Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-windows-11s-functionality-top-strategies-for-widget-upgrades/"><u>Enhancing Windows 11'S Functionality: Top Strategies for Widget Upgrades</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-startup-opening-sticky-notes-seamlessly-on-pc/"><u>Streamlining Startup: Opening Sticky Notes Seamlessly on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-power-of-search-implementing-it-in-win11s-task-monitor/"><u>Unlock the Power of Search: Implementing It in Win11's Task Monitor</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-clutter-software-uninstallation-tricks-for-windows-11-106-chars/"><u>Eliminating Clutter: Software Uninstallation Tricks for Windows 11 (106 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-error-code-3-nvidias-win10-and-11-woes/"><u>Tackling Error Code 3: NVIDIA's Win10 & 11 Woes</u></a></li>
<li><a href="https://windows11.techidaily.com/a-stepwise-guide-to-banishing-the-onedrive-icon-from-explorer/"><u>A Stepwise Guide to Banishing the OneDrive Icon From Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-a-keygen-examining-its-impacts-and-cleanup-techniques-for-pcs/"><u>What Is a Keygen? Examining Its Impacts and Cleanup Techniques for PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-error-trouble-with-compatibility-tool-here-are-quick-solutions/"><u>Windows Error: Trouble with Compatibility Tool? Here Are Quick Solutions.</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/where-is-the-best-place-to-catch-dratini-on-apple-iphone-xs-max-drfone-by-drfone-virtual-ios/"><u>Where Is the Best Place to Catch Dratini On Apple iPhone XS Max | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-elevate-your-productivity-io-screen-capture-secrets/"><u>[New] In 2024, Elevate Your Productivity  IO Screen Capture Secrets</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-6-ways-to-transfer-contacts-from-vivo-v30-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 6 Ways To Transfer Contacts From Vivo V30 to iPhone | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/9-ways-to-fix-the-0x8004def5-onedrive-error-code-on-windows-11/"><u>9 Ways to Fix the 0X8004def5 OneDrive Error Code on Windows 11</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-in-2024-captured-words-top-10-mobile-writing-tools-for-images/"><u>[New] In 2024, Captured Words  Top 10 Mobile Writing Tools for Images</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-navigating-zoom-video-conferencing-via-email-client/"><u>In 2024, Navigating Zoom Video Conferencing via Email Client</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-personalize-with-direct-drawing/"><u>Windows 11: Personalize with Direct Drawing</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-hot-off-the-press-todays-most-viewed-videos-on-social-platforms/"><u>[New] Hot Off the Press  Today’s Most Viewed Videos on Social Platforms</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-adopting-new-norms-analyzing-changes-in-social-media-with-tiktok-vs-snapchat/"><u>2024 Approved  Adopting New Norms  Analyzing Changes in Social Media with TikTok Vs Snapchat</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-times-ticking-off-align-it-back/"><u>Windows Time's Ticking Off? Align It Back!</u></a></li>
<li><a href="https://animation-videos.techidaily.com/in-2024-little-known-techniques-of-motion-graphics-in-premiere-pro/"><u>In 2024, Little Known Techniques of Motion Graphics in Premiere Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-down-energy-waste-without-slowing-down-games/"><u>Cutting Down Energy Waste Without Slowing Down Games</u></a></li>
<li><a href="https://fox-blue.techidaily.com/photo-refinement-essentials-expert-tips-for-efficient-background-clearance-for-2024/"><u>Photo Refinement Essentials  Expert Tips for Efficient Background Clearance for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-dream-team-top-windows-apps-for-a-winning-start/"><u>Digital Dream Team: Top Windows Apps for a Winning Start</u></a></li>
<li><a href="https://windows11.techidaily.com/the-savvy-buyers-guide-to-finding-windows-11-deals/"><u>The Savvy Buyer's Guide to Finding Windows 11 Deals</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-windows-cars-keyboard-magic-boosts-speed/"><u>Top 5 Windows Cars: Keyboard Magic Boosts Speed</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-your-windows-10-past-insights-on-activity-logs/"><u>Unlocking Your Windows 10 Past: Insights on Activity Logs</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-using-windows-11s-compatibility-fixer/"><u>Essential Guide to Using Windows 11’S Compatibility Fixer</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-the-essential-list-of-religious-ringing-sounds/"><u>[Updated] In 2024, The Essential List of Religious Ringing Sounds</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-pioneering-publishing-platforms-fb-and-its-video-distribution-insights/"><u>[Updated] Pioneering Publishing Platforms  FB and Its Video Distribution Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/top-10-uses-for-windows-powertoys-tools/"><u>Top 10 Uses for Windows PowerToys Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/tackle-interruptexception-in-win11-blue-screen/"><u>Tackle INTERRUPT_EXCEPTION in Win11 Blue Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/swipe-to-learn-comparing-windows-10-ui-with-windows-11/"><u>Swipe to Learn: Comparing Windows 10 UI with Windows 11</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-mac-video-editing-software-by-avs-easy-and-powerful/"><u>Updated Mac Video Editing Software by AVS Easy and Powerful</u></a></li>
<li><a href="https://windows11.techidaily.com/unmasking-profit-making-mechanisms-for-w11-at-microsoft/"><u>Unmasking Profit Making Mechanisms for W11 at Microsoft</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-realme-c55-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Live Location is Not Updating and How to Fix on your Realme C55 | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-unleashing-artistic-expression-aafs-premier-lyric-video-creation-kit/"><u>Updated In 2024, Unleashing Artistic Expression AAFs Premier Lyric Video Creation Kit</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-error-code-x80131500-at-store/"><u>Breaking Down Error Code: X80131500 at Store</u></a></li>
<li><a href="https://windows11.techidaily.com/strike-balance-not-conflict-choose-one-antivirus-on-your-windows-pc/"><u>Strike Balance, Not Conflict: Choose One Antivirus on Your Windows PC</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/navigating-board-features-across-apple-android-and-windows-for-effective-online-collaboration-for-2024/"><u>Navigating Board Features Across Apple, Android & Windows for Effective Online Collaboration for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-fn-keys-to-maximize-pc-efficiency-in-wins/"><u>Customizing FN Keys to Maximize PC Efficiency in Wins</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-strategies-for-using-youtube-to-boost-classroom-engagement/"><u>[New] Strategies for Using YouTube to Boost Classroom Engagement</u></a></li>
</ul></div>
