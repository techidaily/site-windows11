---
title: Techniques to Unblock Application Packages on Windows Servers
date: 2024-07-11T21:26:07.469Z
updated: 2024-07-12T21:26:07.469Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Techniques to Unblock Application Packages on Windows Servers
excerpt: This Article Describes Techniques to Unblock Application Packages on Windows Servers
keywords: Unlock Apps,Server Fix,Windows Package Unblock,App Deployment,Server Restore,Windows Unblock Guide,Blocked Apps Fix
thumbnail: https://thmb.techidaily.com/453561a8ca0d834b48f18b90c63e8754b707ad468e25eb7e04a5333cdbe19d66.jpg
---

## Techniques to Unblock Application Packages on Windows Servers

 You can sideload apps in Windows 10 and 11 using the Msixbundle, Appx, or AppxPackage. This comes in handy to install a package unavailable on Microsoft Store or when the store acts up and prevents you from installing from its server.

 Even then, when you try to install a msixbundle or appx package downloaded from a third-party source, you may encounter the "this app package is not supported for installation by app installer" error.

 Fortunately, you can work around this error and sideload a msixbundle app using PowerShell and the App Installer. Here we show you how.

## What Causes the "App Package Is Not Support for Installation by Installer" Error?

 The error often occurs if the Msixbundle installer is not Microsoft Store signed. In such a case, you may not be able to use the built-in app installer to sideload the app and end up with an error. Other times, the error may occur even with Store signed mxis installers with restrictive capabilities.

 To fix the error, check if Developer Mode is enabled on your Windows computer, as it is required to sideload apps on your PC.

To enable Developer Mode on Windows 11:

![enable developer mode windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-developer-mode-windows-11.jpg)

1. Press**Win + I** to open**Settings** .
2. Open the P**rivacy & Security** tab in the left pane.
3. Click on the**For Developer** options.
4. Toggle the**Developer Mode** switch to turn it on.

 Once the developer is enabled, you can use PowerShell to sideload a Msixbundle or AppxPackage on your Windows computer.

## 1\. Install the Msixbundle App Files Using PowerShell

![install msixbundle sideload powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/install-msixbundle-sideload-powershell.jpg)

 You can use [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) to sideload and install msix files on your Windows computer. This should also work if you are trying to sideload an app that is not Store signed.

 To install the app, you can use the Add-AppxPackage cmdlet in PowerShell with administrative privilege.

Follow these steps to sideload msix files using PowerShell.

1. Press the**Win** key and type**PowerShell.**
2. Right-click o**n Windows PowerShell** and select**Run as administrator.**
3. In the PowerShell window, type the following command and press Enter:  
`Add-AppxPackage -Path $MsixFilePath`
4. In the above command, replace MsixFilePath with the file path of the msix file saved on your PC. For example, if you want to run a Msixbundle file is located in**"C:\\Users\\Username\\Downloads\\Msixbundle"** the full command to install the file should look like this:  
`Add-AppxPackage -Path $C:\Users\Username\Downloads\Files.Package.msixbundle`
5. To get the file path, right-click on the package and select**Copy as path** .
6. Next, press**Enter** and wait as PowerShell installs the app.
7. Once installed, type exit and press Enter to close Command Prompt.

## 2\. Install Msixbundle Apps Using the App Installer

![install files app msixbundle](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/install-files-app-msixbundle.jpg)

 App Installer is an official app package installer for Windows 10\. It lets you install msixbundle and appxpackage with a double click. Useful if you don't want to deal with Windows PowerShell and associated commands.

 While the app was officially released for Windows 10, it works just as well on Windows 11\. Make sure to [create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you install App Installer, as it may conflict with your system's ability to sideload apps via PowerShell.

 Once the restore point is created, follow these steps to install App Installer:

1. Go to the [App Installer page](https://apps.microsoft.com/store/detail/app-installer/9NBLGGH4NNS1) on Microsoft Store.
2. Click on**Install** to download and install the app.
3. Once installed, locate and double-click on the**.appx** or .**msixbundle** app package you want to install.
4. Click on the**Install** button in the app installer dialog. The installer may download the required dependencies and then install the app.
5. Once done, your newly installed app will auto-launch.

## Install Msixbundle, Appx, and AppxPackage on Windows 10 and 11

 This error is often triggered when you try to install a non-Store signed app package with restricted capabilities on your Windows computer. Fortunately, you can work around this restriction using PowerShell or App Installer.


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
<li><a href="https://windows11.techidaily.com/cleanse-your-search-box-of-windows-graphics/"><u>Cleanse Your Search Box of Windows Graphics</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-to-clean-up-steams-networking-caches/"><u>Easy Steps to Clean Up Steam's Networking Caches</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-undo-unintended-changes-to-mixer-volume-levels/"><u>How to Undo Unintended Changes to Mixer Volume Levels</u></a></li>
<li><a href="https://howto.techidaily.com/8-quick-fixes-unfortunately-snapchat-has-stopped-on-vivo-v29e-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Quick Fixes Unfortunately, Snapchat has Stopped on Vivo V29e | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/full-guide-to-bypass-infinix-smart-8-plus-frp-by-drfone-android/"><u>Full Guide to Bypass Infinix Smart 8 Plus FRP</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-final-cut-pro-creating-engaging-picture-in-picture-effects/"><u>New In 2024, Final Cut Pro Creating Engaging Picture-in-Picture Effects</u></a></li>
<li><a href="https://windows11.techidaily.com/keeping-your-win11-devices-running-smoothly-check-list-5/"><u>Keeping Your Win11 Devices Running Smoothly - Check List #5</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/reset-itunes-backup-password-of-apple-iphone-xs-max-prevention-and-solution-by-drfone-ios/"><u>Reset iTunes Backup Password Of Apple iPhone XS Max Prevention & Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-cr2-to-jpg-conversion-using-windows-tools/"><u>Mastering the Art of CR2 to JPG Conversion Using Windows Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-win1011-network-failure-code-0x800704b3/"><u>Resolving Win10/11 Network Failure: Code 0X800704B3</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tune-automatic-lock-settings-on-pcs/"><u>Fine-Tune Automatic Lock Settings on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-elevate-your-old-computer-into-a-windows-11-powerhouse/"><u>How to Elevate Your Old Computer Into a Windows 11 Powerhouse</u></a></li>
<li><a href="https://games-able.techidaily.com/xbox-unlock-the-past-seven-iconic-blizzard-games-need-you/"><u>Xbox, Unlock the Past: Seven Iconic Blizzard Games Need You</u></a></li>
<li><a href="https://windows11.techidaily.com/rapidly-access-apps-on-windows-11/"><u>Rapidly Access Apps on Windows 11</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-in-2024-before-you-learn-m4r-converter-some-things-you-should-know/"><u>Updated In 2024, Before You Learn M4R Converter Some Things You Should Know</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-decision-making-with-microsofts-ai-hub/"><u>Efficient Decision-Making with Microsoft's AI Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-access-steps-for-unlocking-windows-hidden-char-personality-tracker/"><u>Mastering Access: Steps for Unlocking Windows' Hidden Char Personality Tracker</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/in-2024-the-best-video-joiners-with-no-watermark-limitations/"><u>In 2024, The Best Video Joiners with No Watermark Limitations</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-user-not-valid-windows-1111-errors/"><u>Navigating Through 'User Not Valid' Windows 11/11 Errors</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-lost-data-of-apple-iphone-13-pro-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Lost Data of Apple iPhone 13 Pro? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/precise-strategies-resetting-razers-system-integration/"><u>Precise Strategies: Resetting Razer's System Integration</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-rpc-errors-on-windows-os/"><u>Quick Fixes for RPC Errors on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/peek-inside-windows-determining-your-computers-manufacturer/"><u>Peek Inside Windows: Determining Your Computer's Manufacturer</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-top-5-best-screen-recorders-for-windows-1110-for-2024/"><u>[New] Top 5 Best Screen Recorders for Windows 11/10 for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-post-extended-clip-on-youtube-per-your-request/"><u>2024 Approved  Post Extended Clip on YouTube Per Your Request</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/leading-video-conference-software-picks-for-2024/"><u>Leading Video-Conference Software Picks for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-windows-arp-cache-and-its-clearance-136-chars-exceeds-limit-adjusted-to-fit-better-clearing-windows-arp/"><u>Essential Guide to Windows ARP Cache and Its Clearance (136 Chars, Exceeds Limit, Adjusted to Fit Better: Clearing Windows ARP</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-google-chrome-to-full-color-in-windows/"><u>Restoring Google Chrome to Full Color in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-clutter-best-windows-apps-to-disable/"><u>Cutting Clutter: Best Windows Apps to Disable</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-in-2024-the-soundless-way-enhancing-your-video-experience-on-windows-10-without-downloads/"><u>New In 2024, The Soundless Way Enhancing Your Video Experience on Windows 10 without Downloads</u></a></li>
<li><a href="https://windows11.techidaily.com/process-to-undo-system-image-fault-0x80780119/"><u>Process to Undo System Image Fault: 0X80780119</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-easiest-guide-how-to-clone-oneplus-ace-2-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Easiest Guide How to Clone OnePlus Ace 2 Phone? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/inside-outlook-and-file-explorers-new-backup-integration-in-windows-11/"><u>Inside Outlook and File Explorer's New Backup Integration in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/localize-onedrive-a-step-by-step-windows-approach/"><u>Localize OneDrive: A Step-by-Step Windows Approach</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-combine-videos-effortlessly-best-easy-video-joiner-alternatives-for-2024/"><u>Updated Combine Videos Effortlessly Best Easy Video Joiner Alternatives for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/perfecting-music-in-instagram-videos-and-stories-for-2024/"><u>Perfecting Music in Instagram Videos & Stories for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-windows-crash-0x800f0831-solution/"><u>Mastery Over Windows Crash: 0X800f0831 Solution</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-elevate-vlogging-effective-use-of-jump-cuts/"><u>[New] 2024 Approved  Elevate Vlogging  Effective Use of Jump Cuts</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionize-your-pc-clear-tpm-from-windows-11/"><u>Revolutionize Your PC: Clear TPM From Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/delaying-windows-10-shutdown-during-running-programs/"><u>Delaying Windows 10 Shutdown During Running Programs</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-asus-mg28uq-monitor-review-bridging-the-high-res-divide/"><u>In 2024, ASUS MG28UQ Monitor Review  Bridging the High-Res Divide</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-resolving-windows-service-response-errors/"><u>Guide to Resolving Windows Service Response Errors</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-x-passcode-screen-drfone-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone X Passcode Screen? | Dr.fone</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-ultimate-live-band-webcasts/"><u>In 2024, Ultimate Live Band Webcasts</u></a></li>
<li><a href="https://location-fake.techidaily.com/8-solutions-to-fix-find-my-friends-location-not-available-on-honor-100-drfone-by-drfone-virtual-android/"><u>8 Solutions to Fix Find My Friends Location Not Available On Honor 100 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/iphoneandroid-as-windows-microphones-guide/"><u>IPhone/Android as Windows Microphones Guide</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-foodie-festivals-viral-virtues-of-tiktok-meals/"><u>[New] Foodie Festivals  Viral Virtues of TikTok Meals</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-how-to-blur-parts-of-a-video-online-for-free-a-beginners-guide/"><u>New 2024 Approved How to Blur Parts of a Video Online for Free A Beginners Guide</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-elevate-your-content-11-steps-to-amplify-fb-video-performance-for-2024/"><u>[New] Elevate Your Content  11 Steps to Amplify FB Video Performance for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-frp-hijacker-by-hagard-download-and-bypass-your-samsung-galaxy-a14-4g-frp-locks-by-drfone-android/"><u>In 2024, FRP Hijacker by Hagard Download and Bypass your Samsung Galaxy A14 4G FRP Locks</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-what-here-can-tell-you-about-12-best-audio-converter/"><u>New 2024 Approved What Here Can Tell You About 12 Best Audio Converter</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-network-failure-0x800704b3-in-windows-1011/"><u>Overcoming Network Failure 0X800704B3 in Windows 10/11</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-tips-and-tricks-for-apple-id-locked-issue-from-apple-iphone-14-by-drfone-ios/"><u>In 2024, Tips and Tricks for Apple ID Locked Issue From Apple iPhone 14</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-learn-the-basics-of-digital-distortion/"><u>[Updated] Learn the Basics of Digital Distortion</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-unmasking-the-hype-fact-based-insights-into-instagrams-reels/"><u>[Updated] 2024 Approved  Unmasking the Hype  Fact-Based Insights Into Instagram's Reels</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-text-motion-tracking-expert-approved-software/"><u>Updated In 2024, Text Motion Tracking Expert-Approved Software</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-6-proven-ways-to-unlock-vivo-x-flip-phone-when-you-forget-the-password-by-drfone-android/"><u>In 2024, 6 Proven Ways to Unlock Vivo X Flip Phone When You Forget the Password</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-crafting-the-perfect-visual-identity-podcast-covers-unveiled/"><u>[New] In 2024, Crafting the Perfect Visual Identity  Podcast Covers Unveiled</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-ultimate-guide-to-get-the-meltan-box-pokemon-go-for-vivo-y100i-power-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Ultimate guide to get the meltan box pokemon go For Vivo Y100i Power 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/revitalizing-your-stalled-windows-11-mobile-network-connection/"><u>Revitalizing Your Stalled Windows 11 Mobile Network Connection</u></a></li>
<li><a href="https://windows11.techidaily.com/overriding-default-no-notify-camera-behavior-in-ws11/"><u>Overriding Default No-Notify Camera Behavior in WS11</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/exploring-the-most-reliable-cost-free-tiktok-mp3-converter-apps-6/"><u>Exploring the Most Reliable, Cost-Free TikTok MP3 Converter Apps (6)</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-laughters-playground-top-15-youtube-hits-for-fun/"><u>[Updated] In 2024, Laughter's Playground  Top 15 YouTube Hits for Fun</u></a></li>
<li><a href="https://ai-topics.techidaily.com/new-in-2024-breakthrough-how-to-make-a-picture-speak/"><u>New In 2024, Breakthrough How to Make A Picture Speak</u></a></li>
<li><a href="https://windows11.techidaily.com/monitoring-for-failed-windows-logins-a-security-checkers-guide/"><u>Monitoring for Failed Windows Logins: A Security Checker's Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-software-management-using-the-windows-package-manager-wpm/"><u>Optimizing Software Management Using the Windows Package Manager (WPM)</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-imaginary-device-issue-in-win-11-os/"><u>Resolving Imaginary Device Issue in Win 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-level-insights-into-windows-non-adjacent-partition-integration/"><u>Expert-Level Insights Into Windows Non-Adjacent Partition Integration</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/crack-the-code-twitter-video-aspect-ratio-secrets-revealed-for-2024/"><u>Crack the Code Twitter Video Aspect Ratio Secrets Revealed for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-navigate-and-utilize-windows-iscsi-initiator-efficiently/"><u>How to Navigate and Utilize Windows iSCSI Initiator Efficiently</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-best-mac-image-sorter/"><u>[New] 2024 Approved  Best Mac Image Sorter</u></a></li>
<li><a href="https://windows11.techidaily.com/reconnecting-mic-during-windows-powerpoint-screencast/"><u>Reconnecting Mic During Windows PowerPoint Screencast</u></a></li>
<li><a href="https://windows11.techidaily.com/revamp-desktop-by-removing-windows-11s-highlighted-icon/"><u>Revamp Desktop by Removing Windows 11'S Highlighted Icon</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-web-based-movie-trailer-creation-platforms/"><u>2024 Approved Web-Based Movie Trailer Creation Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-opaque-windows-11-themes-via-registry-manipulation/"><u>Enabling Opaque Windows 11 Themes via Registry Manipulation</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-directdraw-woes-a-users-survival-manual-for-win11/"><u>Navigating DirectDraw Woes: A User's Survival Manual for Win11</u></a></li>
</ul></div>
