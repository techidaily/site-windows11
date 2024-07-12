---
title: "Biometric Betrayal: Windows Hello's Security Under Fire?"
date: 2024-07-11T21:49:34.024Z
updated: 2024-07-12T21:49:34.024Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Biometric Betrayal: Windows Hello's Security Under Fire?"
excerpt: "This Article Describes Biometric Betrayal: Windows Hello's Security Under Fire?"
keywords: Biometric Security Risks,Windows Hello Vulnerabilities,Facial Recognition Threats,Digital Identity Safety,Microsoft Login Concerns,Tech Privacy Issues,Online Authentication Challenges
thumbnail: https://thmb.techidaily.com/4b1d432d185a9307d4c64d844f91526f6a3048c24d149908b382d0c549a92a65.jpg
---

## Biometric Betrayal: Windows Hello's Security Under Fire?

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
<li><a href="https://windows11.techidaily.com/overcoming-common-errors-in-microsoft-office-activation/"><u>Overcoming Common Errors in Microsoft Office Activation</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-behind-the-screen-essential-post-vidcon-gatherings-for-2024/"><u>[New] Behind the Screen  Essential Post-VidCon Gatherings for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-task-execution-on-windows-adding-an-improved-run-utility/"><u>Optimizing Task Execution on Windows: Adding an Improved Run Utility</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-avoiding-frequent-sign-ins-on-ms-teams-platform/"><u>Solutions for Avoiding Frequent Sign-Ins on MS Teams Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-restarting-resistant-spotify-program/"><u>Quick Fix: Restarting Resistant Spotify Program</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-oppo-a78-5g-phone-without-pin-by-drfone-android/"><u>How to Unlock Oppo A78 5G Phone without PIN</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-top-5-election-simulation-games/"><u>[New] 2024 Approved  Top 5 Election Simulation Games</u></a></li>
<li><a href="https://extra-information.techidaily.com/guide-to-picking-best-free-online-srt-translation-providers/"><u>Guide to Picking Best Free Online SRT Translation Providers</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-crafting-memes-perfecting-social-media-videos-on-fb-and-insta/"><u>[Updated] 2024 Approved  Crafting Memes  Perfecting Social Media Videos on FB & Insta</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-ad-ds-printing-issues-in-windows-11-pro/"><u>Overcoming AD DS Printing Issues in Windows 11 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/redefine-window-management-embrace-adaptive-wmlayouts/"><u>Redefine Window Management: Embrace Adaptive WMLayouts</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-overcoming-disruptions-after-a-windows-update/"><u>Swiftly Overcoming Disruptions After a Windows Update</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-value-not-found-error-message-in-windows-setups/"><u>Solving 'Value Not Found' Error Message in Windows Setups</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-comparative-analysis-of-ar-stickers-focusing-on-google/"><u>[New] Comparative Analysis of AR Stickers, Focusing on Google</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windows-11-programs-for-faster-startups/"><u>Optimizing Windows 11 Programs for Faster Startups</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-solutions-for-non-deliverable-facebook-messenger-videos-on-androidios-for-2024/"><u>[New] Solutions for Non-Deliverable Facebook Messenger Videos on Android/iOS for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-things-you-need-to-know-about-wipe-datafactory-reset-for-nokia-c32-drfone-by-drfone-reset-android-reset-android/"><u>All Things You Need to Know about Wipe Data/Factory Reset For Nokia C32 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-solve-no-device-camera-error-in-win11/"><u>Steps to Solve No Device: Camera Error in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-visibility-of-missing-disk-in-win/"><u>Restoring Visibility of Missing Disk in Win</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-steam-setup-obstacles-on-windows-11-devices/"><u>Overcoming Steam Setup Obstacles on Windows 11 Devices</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/the-updated-method-to-bypass-xiaomi-civi-3-frp-by-drfone-android/"><u>The Updated Method to Bypass Xiaomi Civi 3 FRP</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-a-working-guide-for-pachirisu-pokemon-go-map-on-samsung-galaxy-a14-5g-drfone-by-drfone-virtual-android/"><u>In 2024, A Working Guide For Pachirisu Pokemon Go Map On Samsung Galaxy A14 5G | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/calls-on-vivo-v27-pro-go-straight-to-voicemail-12-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Calls on Vivo V27 Pro Go Straight to Voicemail? 12 Fixes | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/significance-and-uses-for-vcplusplus-releases/"><u>Significance and Uses for VC++ Releases</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-offline-errors-for-windows-11s-printer-port/"><u>Resolving Offline Errors for Windows 11'S Printer Port</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resurrect-a-dormant-windows-tab-key/"><u>Steps to Resurrect a Dormant Windows Tab Key</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/remove-the-lock-screen-fingerprint-of-your-poco-m6-pro-5g-by-drfone-android/"><u>Remove the Lock Screen Fingerprint Of Your Poco M6 Pro 5G</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unraveling-the-itunes-radio-download-process/"><u>2024 Approved  Unraveling the iTunes Radio Download Process</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-step-by-step-guide-to-professional-podcast-scriptwriting-techniques/"><u>[New] Step-by-Step Guide to Professional Podcast Scriptwriting Techniques</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-resolve-lava-storm-5g-screen-not-working-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Resolve Lava Storm 5G Screen Not Working | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/innovate-your-screenshots-unveiling-ezvides-screen-casting-features-for-2024/"><u>Innovate Your Screenshots  Unveiling EZvide's Screen Casting Features for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-rectify-win-1011-onedrive-issues/"><u>Steps to Rectify Win 10/11 OneDrive Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/restore-your-window-11-drag-functionality/"><u>Restore Your Window 11 Drag Functionality</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/20-best-free-platforms-for-youtube-channel-beginners/"><u>20 Best Free Platforms for YouTube Channel Beginners</u></a></li>
<li><a href="https://windows11.techidaily.com/pro-tips-for-mastering-local-user-groups-on-win1110/"><u>Pro Tips for Mastering Local User Groups on Win11/10</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-beats-and-bites-mastering-music-in-instagram-stories-for-2024/"><u>[New] Beats & Bites  Mastering Music in Instagram Stories for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/seamlessly-access-lately-used-documents-in-windows/"><u>Seamlessly Access Lately Used Documents in Windows</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/lyric-video-maker-software-top-picks-for-2024/"><u>Lyric Video Maker Software Top Picks for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-to-open-adobe-ps-in-w11-after-updates/"><u>Step-by-Step to Open Adobe PS in W11 After Updates</u></a></li>
</ul></div>
