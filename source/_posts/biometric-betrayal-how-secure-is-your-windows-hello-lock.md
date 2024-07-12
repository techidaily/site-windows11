---
title: "Biometric Betrayal: How Secure Is Your Windows Hello Lock?"
date: 2024-07-11T21:52:42.955Z
updated: 2024-07-12T21:52:42.955Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Biometric Betrayal: How Secure Is Your Windows Hello Lock?"
excerpt: "This Article Describes Biometric Betrayal: How Secure Is Your Windows Hello Lock?"
keywords: Biometric Security,Windows Hello Truths,Facial Unlock Risks,Hello Lock Safety,Windows Lock Concerns,Secure Hello Access,User Authentication Trust
thumbnail: https://thmb.techidaily.com/bc6e0c08f36b012f885710643ac64bca838b2cd03d9601b077f3603bbf1a3a0e.jpg
---

## Biometric Betrayal: How Secure Is Your Windows Hello Lock?

 Logging into a Windows laptop with a fingerprint scanner is easy; just place your finger on a scanner, and the operating system lets you in. However, researchers have shown that, while this method is convenient, it's not hackproof.

 So, how can people hack past a Windows Hello fingerprint scan, and should you worry about it?

## Can People Hack Windows Hello Fingerprint Scanners?

![Lock Having Fingerprint in the Middle on Blue Background](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/passwords-are-a-thing-of-the-past-passwordless-logins-benefits.jpg)

 If a hacker wants to bypass a fingerprint scanner on a Windows machine, they're aiming to get past a service called Windows Hello. This service handles how you log into Windows, such as PINs, facial scans, and fingerprint scans.

 As part of research into Windows Hello's strength, two [white-hat hackers](https://www.makeuseof.com/white-hat-hacker/), Jesse D'Aguanno and Timo Teräs, posted a report on their website, [Blackwing HQ](https://blackwinghq.com/blog/posts/a-touch-of-pwn-part-i/). The report details how they breached three popular devices: the Dell Inspiron 15, Lenovo ThinkPad T14, and the Microsoft Surface Pro Type Cover.

### How the Hackers Breached Windows Hello on the Dell Inspiron 15

 For the Dell Inspiron 15, the hackers noticed they could boot into Linux on the laptop. Once logged into Linux, they can register their fingerprints in the system and give it the same ID as the Windows user they want to log into.

 Then, they perform a man-in-the-middle attack on the connection between the PC and the sensor. They set it up so that when Windows goes to double-check that a scanned fingerprint is legitimate, it ends up checking the Linux database of fingerprints instead of its own.

 To dodge Windows Hello, the hackers uploaded their fingerprints to the Linux database, assigned it the same ID as the user on Windows, and then tried to log into Windows with their fingerprints. During the authentication process, they redirected the packet to the Linux database, which told Windows that the user at the specified ID was ready to log in.

### How the Hackers Breached Windows Hello on the Lenovo ThinkPad T14

 For the Lenovo ThinkPad, the hackers discovered that the laptop used a custom encryption method to verify fingerprints. With some work, the hackers managed to decrypt it, giving them a way into the fingerprint verification process.

 Once done, the hackers could force the fingerprint database to accept their fingerprint as the user's. Then, all they had to do was scan their fingerprint to access the Lenovo ThinkPad.

### How the Hackers Breached Windows Hello on the Microsoft Surface Pro Type Cover

 The hackers believed the Surface Pro would be the hardest device to crack, but they were surprised to find the Surface Pro lacked a lot of security measures for checking valid fingerprints. In fact, they discovered that they only had to dodge past one defense, then tell the Surface Pro that the fingerprint scan was successful, and the device let them in.

## What Do These Hacks Mean for You?

![Professional Thinking With Laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/professional-thinking-with-laptop.jpg)

 These hacks may sound pretty scary if you use fingerprints to log into your laptop. However, it's essential to remember some crucial things before you forgo fingerprint scans entirely.

### 1\. The Attacks Were Performed by Skilled Hackers

 The reason threats like [ransomware as a service](https://www.makeuseof.com/what-is-ransomware-as-a-service/) are so deadly is that anyone with minimal cybersecurity can use them. However, the above hacks require a high level of expertise, with a deep understanding of how devices authenticate fingerprints and how to avoid them.

### 2\. The Attacks Require the Attacker to Physically Interact With the Device

 The hackers must have physical contact with the device to perform the above hacks. In the report, the hackers stated they might be able to create USB devices that can perform the attack once plugged in, but that means a potential attacker needs to plug something into your PC to hack it.

### 3\. The Attacks Only Work on Specific Devices

 You'll notice that each attack had to take a different path to achieve the same goal. Every device is unique, and a hack that works on one device may not work on another. As such, you shouldn't believe that Windows Hello has now been blown wide open on every device; it's just these three that failed.

 While these hacks may sound scary, they'll be challenging to perform against actual targets. The hacker will likely have to steal the device to perform these hacks, which would undoubtedly alert the previous owner.

## How to Stay Safe From Fingerprint Hacking

![The face of a man wearing a hoodie](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hacher-hat.jpg)

 As stated above, the discovered hacks are complicated to perform and may require the hacker to remove the device to hack into it physically. As such, there's an extremely low chance that these attacks will personally target you.

 However, if you're still not satisfied, there are some ways to protect yourself from fingerprint scanner hacks:

### 1\. Do Not Leave Devices Unattended and Unprotected

 Because a hacker will need to interact with your device physically, you should ensure it doesn't fall into the wrong hands. For computers, you can [take steps to stop it from being stolen](https://www.makeuseof.com/tag/stop-entire-desktop-pc-home-office-stolen/). If you're using a laptop, never leave it alone in a public space, and use an [anti-theft laptop bag](https://www.makeuseof.com/tag/anti-theft-laptop-bags/) to stop people from tearing your bag open.

### 2\. Use a Different Login Method

 Windows Hello supports many different login methods, some more secure than others. If you've fallen out of love with fingerprint scans, check out if [face, iris, fingerprint, PIN, or password logins are more secure](https://www.makeuseof.com/face-iris-fingerprint-password-pin-most-secure/), and choose one that suits you best.

 If you're worried about these hacks, it's important to remember that there's a very low chance they'll target you specifically. As such, you should be safe using fingerprint scans; just don't allow people to steal your devices.

 So, how can people hack past a Windows Hello fingerprint scan, and should you worry about it?



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/iphoneandroid-as-windows-microphones-guide/"><u>IPhone/Android as Windows Microphones Guide</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/6-methods-to-share-apple-iphone-8-screen-with-pc-drfone-by-drfone-ios/"><u>6 Methods to Share Apple iPhone 8 Screen with PC | Dr.fone</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-free-and-easy-video-editing-tools-for-beginners-desktoponlinemobile/"><u>New 2024 Approved Free and Easy Video Editing Tools for Beginners Desktop/Online/Mobile</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-clutter-best-windows-apps-to-disable/"><u>Cutting Clutter: Best Windows Apps to Disable</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-essential-snapchat-filters-20-must-have-techniques/"><u>[Updated] Essential Snapchat Filters  20 Must-Have Techniques</u></a></li>
<li><a href="https://fix-guide.techidaily.com/simple-solutions-to-fix-android-systemui-has-stopped-error-for-oppo-find-x7-ultra-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Simple Solutions to Fix Android SystemUI Has Stopped Error For Oppo Find X7 Ultra | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/monitoring-for-failed-windows-logins-a-security-checkers-guide/"><u>Monitoring for Failed Windows Logins: A Security Checker's Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-windows-arp-cache-and-its-clearance-136-chars-exceeds-limit-adjusted-to-fit-better-clearing-windows-arp/"><u>Essential Guide to Windows ARP Cache and Its Clearance (136 Chars, Exceeds Limit, Adjusted to Fit Better: Clearing Windows ARP</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-macs-top-5-mkv-decoder-software/"><u>[Updated] Mac's Top 5 MKV Decoder Software</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-step-by-step-minecraft-screenshots-and-videos/"><u>[Updated] 2024 Approved  Step-by-Step Minecraft Screenshots & Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-access-steps-for-unlocking-windows-hidden-char-personality-tracker/"><u>Mastering Access: Steps for Unlocking Windows' Hidden Char Personality Tracker</u></a></li>
<li><a href="https://windows11.techidaily.com/overriding-default-no-notify-camera-behavior-in-ws11/"><u>Overriding Default No-Notify Camera Behavior in WS11</u></a></li>
<li><a href="https://windows11.techidaily.com/precise-strategies-resetting-razers-system-integration/"><u>Precise Strategies: Resetting Razer's System Integration</u></a></li>
<li><a href="https://windows11.techidaily.com/process-to-undo-system-image-fault-0x80780119/"><u>Process to Undo System Image Fault: 0X80780119</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-conquer-recording-challenges-using-ezvides-screencasting/"><u>[New] Conquer Recording Challenges Using EZvide's Screencasting</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-software-management-using-the-windows-package-manager-wpm/"><u>Optimizing Software Management Using the Windows Package Manager (WPM)</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-system-of-iphone-14-pro-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair System of iPhone 14 Pro? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-windows-crash-0x800f0831-solution/"><u>Mastery Over Windows Crash: 0X800f0831 Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-directdraw-woes-a-users-survival-manual-for-win11/"><u>Navigating DirectDraw Woes: A User's Survival Manual for Win11</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-in-ar-games-on-meizu-21-drfone-by-drfone-virtual-android/"><u>How to Simulate GPS Movement in AR games On Meizu 21? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-decision-making-with-microsofts-ai-hub/"><u>Efficient Decision-Making with Microsoft's AI Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-navigate-and-utilize-windows-iscsi-initiator-efficiently/"><u>How to Navigate and Utilize Windows iSCSI Initiator Efficiently</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-live-streaming-pre-recorded-videos-the-facebook-approach/"><u>2024 Approved  Live Streaming Pre-Recorded Videos  The Facebook Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-faulty-function-keys-windows-10-fix-guide/"><u>Bypass Faulty Function Keys: Windows 10 Fix Guide</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-samsung-galaxy-s24-ultra-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Samsung Galaxy S24 Ultra to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/awesome-free-apps-to-transform-your-mobile-images/"><u>Awesome FREE Apps to Transform Your Mobile Images</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/how-to-add-video-transitions-in-videos-for-2024/"><u>How to Add Video Transitions in Videos for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-forth-hidden-5ghz-lans-in-windows-11-fixes-outlined/"><u>Bring Forth Hidden 5GHz LANs in Windows 11 - Fixes Outlined</u></a></li>
<li><a href="https://windows11.techidaily.com/reconnecting-mic-during-windows-powerpoint-screencast/"><u>Reconnecting Mic During Windows PowerPoint Screencast</u></a></li>
<li><a href="https://windows11.techidaily.com/bringing-lost-panes-back-top-techniques-for-windows-11/"><u>Bringing Lost Panes Back: Top Techniques for Windows 11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/viral-tweets-watchlist-the-hottest-twitch-videos-on-twitter/"><u>Viral Tweets Watchlist  The Hottest Twitch Videos on Twitter</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-audio-excellence-techniques-for-clearer-sound-in-video-editing-using-filmora-for-2024/"><u>New Audio Excellence Techniques for Clearer Sound in Video Editing Using Filmora for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-network-failure-0x800704b3-in-windows-1011/"><u>Overcoming Network Failure 0X800704B3 in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/inside-outlook-and-file-explorers-new-backup-integration-in-windows-11/"><u>Inside Outlook and File Explorer's New Backup Integration in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-opaque-windows-11-themes-via-registry-manipulation/"><u>Enabling Opaque Windows 11 Themes via Registry Manipulation</u></a></li>
<li><a href="https://windows11.techidaily.com/localize-onedrive-a-step-by-step-windows-approach/"><u>Localize OneDrive: A Step-by-Step Windows Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/rapidly-access-apps-on-windows-11/"><u>Rapidly Access Apps on Windows 11</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-unveiling-clarity-the-ultimate-blueprint-for-banishing-unwanted-acoustic-interferences/"><u>Updated Unveiling Clarity The Ultimate Blueprint for Banishing Unwanted Acoustic Interferences</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-to-clean-up-steams-networking-caches/"><u>Easy Steps to Clean Up Steam's Networking Caches</u></a></li>
<li><a href="https://windows11.techidaily.com/delaying-windows-10-shutdown-during-running-programs/"><u>Delaying Windows 10 Shutdown During Running Programs</u></a></li>
<li><a href="https://windows11.techidaily.com/cleanse-your-search-box-of-windows-graphics/"><u>Cleanse Your Search Box of Windows Graphics</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-obs-vs-twitch-hub-best-platform-debate/"><u>[New] In 2024, OBS Vs. Twitch Hub  Best Platform Debate</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-elevate-your-old-computer-into-a-windows-11-powerhouse/"><u>How to Elevate Your Old Computer Into a Windows 11 Powerhouse</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-undo-unintended-changes-to-mixer-volume-levels/"><u>How to Undo Unintended Changes to Mixer Volume Levels</u></a></li>
<li><a href="https://windows11.techidaily.com/keeping-your-win11-devices-running-smoothly-check-list-5/"><u>Keeping Your Win11 Devices Running Smoothly - Check List #5</u></a></li>
<li><a href="https://windows11.techidaily.com/peek-inside-windows-determining-your-computers-manufacturer/"><u>Peek Inside Windows: Determining Your Computer's Manufacturer</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-best-vignette-apps-for-ios-and-android-free-and-paid/"><u>Updated 2024 Approved Best Vignette Apps for iOS and Android Free & Paid</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-covert-snapsnapper-stealth-techniques-for-picture-capture/"><u>In 2024, Covert SnapSnapper  Stealth Techniques for Picture Capture</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-incredible-virtual-room-encounters-for-2024/"><u>[New] Incredible Virtual Room Encounters for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/android-gamers-rejoice-heres-kinemaster-unleashed/"><u>Android Gamers Rejoice! Here's KineMaster Unleashed</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-2024-approved-mastering-video-blur-the-best-apps-for-ios-and-android-users/"><u>Updated 2024 Approved Mastering Video Blur The Best Apps for iOS and Android Users</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-essential-bot-selections-elevate-your-discord-space/"><u>[New] Essential Bot Selections  Elevate Your Discord Space</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-the-quick-path-to-standout-instagram-reel-content/"><u>[Updated] The Quick Path to Standout Instagram Reel Content</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/crafting-professional-images-using-photoshops-powerful-luts/"><u>Crafting Professional Images  Using Photoshop's Powerful LUTs</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-wiped-call-history-on-samsung-galaxy-m54-5g-by-fonelab-android-recover-call-logs/"><u>How to restore wiped call history on Samsung Galaxy M54 5G?</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-craft-intense-conversations-on-discord-learn-effective-message-pinning-for-2024/"><u>[New] Craft Intense Conversations on Discord  Learn Effective Message Pinning for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-unlocking-an-icloud-locked-ipad-and-iphone-6-plus-by-drfone-ios/"><u>In 2024, Unlocking an iCloud Locked iPad and iPhone 6 Plus</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-cr2-to-jpg-conversion-using-windows-tools/"><u>Mastering the Art of CR2 to JPG Conversion Using Windows Tools</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-probing-deep-into-inshots-editing-capabilities/"><u>2024 Approved  Probing Deep Into InShot's Editing Capabilities</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-user-not-valid-windows-1111-errors/"><u>Navigating Through 'User Not Valid' Windows 11/11 Errors</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-the-ultimate-list-top-10-4k-video-converter-tools-free-and-paid/"><u>New The Ultimate List Top 10 4K Video Converter Tools (Free & Paid)</u></a></li>
<li><a href="https://facebook.techidaily.com/diving-into-your-timelines-past-content/"><u>Diving Into Your Timeline's Past Content</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/mastering-obs-for-android-streaming/"><u>Mastering OBS for Android Streaming</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-script-failures-windows-script-troubleshooting-guide/"><u>Bypass Script Failures: Windows Script Troubleshooting Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-11-restrictions-a-beginners-guide/"><u>Bypassing Windows 11 Restrictions: A Beginner's Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-resolving-windows-service-response-errors/"><u>Guide to Resolving Windows Service Response Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-level-insights-into-windows-non-adjacent-partition-integration/"><u>Expert-Level Insights Into Windows Non-Adjacent Partition Integration</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-check-if-your-realme-gt-5-pro-is-unlocked-by-drfone-android/"><u>How To Check if Your Realme GT 5 Pro Is Unlocked</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-rpc-errors-on-windows-os/"><u>Quick Fixes for RPC Errors on Windows OS</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-9-powerful-methods-to-make-money-on-your-youtube-shorts/"><u>2024 Approved  9 Powerful Methods to Make Money on Your YouTube Shorts</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tune-automatic-lock-settings-on-pcs/"><u>Fine-Tune Automatic Lock Settings on PCs</u></a></li>
</ul></div>
