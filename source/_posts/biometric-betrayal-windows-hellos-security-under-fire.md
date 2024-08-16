---
title: "Biometric Betrayal: Windows Hello's Security Under Fire?"
date: 2024-08-15T15:42:09.580Z
updated: 2024-08-16T15:42:09.580Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### How the Hackers Breached Windows Hello on the Dell Inspiron 15

 For the Dell Inspiron 15, the hackers noticed they could boot into Linux on the laptop. Once logged into Linux, they can register their fingerprints in the system and give it the same ID as the Windows user they want to log into.

 Then, they perform a man-in-the-middle attack on the connection between the PC and the sensor. They set it up so that when Windows goes to double-check that a scanned fingerprint is legitimate, it ends up checking the Linux database of fingerprints instead of its own.

 To dodge Windows Hello, the hackers uploaded their fingerprints to the Linux database, assigned it the same ID as the user on Windows, and then tried to log into Windows with their fingerprints. During the authentication process, they redirected the packet to the Linux database, which told Windows that the user at the specified ID was ready to log in.

### How the Hackers Breached Windows Hello on the Lenovo ThinkPad T14

 For the Lenovo ThinkPad, the hackers discovered that the laptop used a custom encryption method to verify fingerprints. With some work, the hackers managed to decrypt it, giving them a way into the fingerprint verification process.

 Once done, the hackers could force the fingerprint database to accept their fingerprint as the user's. Then, all they had to do was scan their fingerprint to access the Lenovo ThinkPad.

### How the Hackers Breached Windows Hello on the Microsoft Surface Pro Type Cover

 The hackers believed the Surface Pro would be the hardest device to crack, but they were surprised to find the Surface Pro lacked a lot of security measures for checking valid fingerprints. In fact, they discovered that they only had to dodge past one defense, then tell the Surface Pro that the fingerprint scan was successful, and the device let them in.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
## What Do These Hacks Mean for You?

![Professional Thinking With Laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/professional-thinking-with-laptop.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 These hacks may sound pretty scary if you use fingerprints to log into your laptop. However, it's essential to remember some crucial things before you forgo fingerprint scans entirely.

### 1\. The Attacks Were Performed by Skilled Hackers

 The reason threats like [ransomware as a service](https://www.makeuseof.com/what-is-ransomware-as-a-service/) are so deadly is that anyone with minimal cybersecurity can use them. However, the above hacks require a high level of expertise, with a deep understanding of how devices authenticate fingerprints and how to avoid them.

### 2\. The Attacks Require the Attacker to Physically Interact With the Device

 The hackers must have physical contact with the device to perform the above hacks. In the report, the hackers stated they might be able to create USB devices that can perform the attack once plugged in, but that means a potential attacker needs to plug something into your PC to hack it.

### 3\. The Attacks Only Work on Specific Devices

 You'll notice that each attack had to take a different path to achieve the same goal. Every device is unique, and a hack that works on one device may not work on another. As such, you shouldn't believe that Windows Hello has now been blown wide open on every device; it's just these three that failed.

 While these hacks may sound scary, they'll be challenging to perform against actual targets. The hacker will likely have to steal the device to perform these hacks, which would undoubtedly alert the previous owner.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
## How to Stay Safe From Fingerprint Hacking

![The face of a man wearing a hoodie](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hacher-hat.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 As stated above, the discovered hacks are complicated to perform and may require the hacker to remove the device to hack into it physically. As such, there's an extremely low chance that these attacks will personally target you.

 However, if you're still not satisfied, there are some ways to protect yourself from fingerprint scanner hacks:

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://extra-guidance.techidaily.com/new-mastering-close-up-cinematography-techniques-with-kinemaster-pro/"><u>[New] Mastering Close-Up Cinematography Techniques with Kinemaster Pro</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-the-ultimate-steps-for-fetching-your-fb-status-vids/"><u>[New] The Ultimate Steps for Fetching Your FB Status Vids</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-visual-storytelling-on-facebook-crafting-compelling-slideshows-for-2024/"><u>[New] Visual Storytelling on Facebook  Crafting Compelling Slideshows for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-single-frame-snipping-capturing-stillness-from-videos-in-photos-for-2024/"><u>[Updated] Single-Frame Snipping  Capturing Stillness From Videos in Photos for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-gif-creation-journey-unveiling-the-ultimate-9-tools-of-memetic-ingenuity/"><u>[Updated] The GIF Creation Journey  Unveiling the Ultimate 9 Tools of Memetic Ingenuity</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-adding-eye-catching-text-to-vids-without-costs/"><u>2024 Approved  Adding Eye-Catching Text to Vids Without Costs</u></a></li>
<li><a href="https://windows11.techidaily.com/4-ways-to-find-a-programs-install-location-on-windows/"><u>4 Ways to Find a Program's Install Location on Windows</u></a></li>
<li><a href="https://tech-haven.techidaily.com/a-comprehensive-guide-to-chatgpt-api-use/"><u>A Comprehensive Guide to ChatGPT API Use</u></a></li>
<li><a href="https://windows11.techidaily.com/claim-your-potential-in-windows-11-regain-missing-system-upgrades/"><u>Claim Your Potential in Windows 11: Regain Missing System Upgrades</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-zip-files-seamless-compressed-archives-on-windows-pcs/"><u>Conquer ZIP Files: Seamless Compressed Archives on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-accidental-windows-11-search-menu-trigger/"><u>Disabling Accidental Windows 11 Search Menu Trigger</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/elevate-view-count-prime-hashtags-strategy/"><u>Elevate View Count  Prime Hashtags Strategy</u></a></li>
<li><a href="https://windows11.techidaily.com/embracing-ai-with-microsoft-copilot-writes-and-debugging/"><u>Embracing AI with Microsoft Copilot' Writes and Debugging</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-spotting-hdd-vs-ssd-in-windows-operations/"><u>Essential Guide: Spotting HDD vs SSD in Windows Operations</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-knowledge-about-winservicesexe/"><u>Essential Knowledge About WinServices.exe</u></a></li>
<li><a href="https://windows11.techidaily.com/faster-apps-better-internet-fixes-for-windows-devices/"><u>Faster Apps, Better Internet: Fixes for Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-elevation-problem-with-error-code-740-on-windows-11/"><u>Fixing Elevation Problem with Error Code 740 on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-display-more-pinned-items-on-the-windows-11-start-menu/"><u>How to Display More Pinned Items on the Windows 11 Start Menu</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-pc-screen-to-tecno-camon-30-pro-5g-phones-drfone-by-drfone-android/"><u>How to Mirror PC Screen to Tecno Camon 30 Pro 5G Phones? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-mute-cortana-in-windows-11-os/"><u>How to Mute Cortana in Windows 11 OS</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-facebook-dating-for-your-realme-gt-3-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location On Facebook Dating for your Realme GT 3 | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-se-drfone-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone SE? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-apple-iphone-15-drfone-by-drfone-virtual-ios/"><u>In 2024, How to use Snapchat Location Spoofer to Protect Your Privacy On Apple iPhone 15? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-domain-user-biometric-control-in-windows-11/"><u>Mastering Domain User Biometric Control in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-mspcm-bar-with-finesse-in-windows-11-environment/"><u>Navigating MSPCM Bar with Finesse in Windows 11 Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-22h2-windows-woes/"><u>Navigating Through 22H2 Windows Woes</u></a></li>
<li><a href="https://windows11.techidaily.com/optimal-start-menu-no-commercials-here/"><u>Optimal Start Menu: No Commercials Here!</u></a></li>
<li><a href="https://windows11.techidaily.com/outperforming-understanding-why-pcs-triumph-over-macs-9/"><u>Outperforming: Understanding Why PCs Triumph over Macs (#9)</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-discord-from-launching-with-every-system-boots/"><u>Preventing Discord From Launching with Every System Boots</u></a></li>
<li><a href="https://windows11.techidaily.com/prove-your-prowess-top-7-zero-cost-pc-password-apps/"><u>Prove Your Prowess: Top 7 Zero-Cost PC Password Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-package-registration-failures-on-windows-devices/"><u>Resolving Package Registration Failures on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-ethernet-signal-in-windows-os/"><u>Securing Ethernet Signal in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-windows-pre-format-drive-errors/"><u>Solving Windows' Pre-Format Drive Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-correct-steam-ui-dll-not-loaded-error/"><u>Steps to Correct Steam UI DLL Not Loaded Error</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-rectify-microsoft-store-error-0x80072f30-on-pcs/"><u>Steps to Rectify Microsoft Store Error 0X80072F30 on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/tech-triumph-expert-tips-for-reinitializing-windows-11-apps/"><u>Tech Triumph: Expert Tips for Reinitializing Windows 11 Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-errors-when-opening-sound-devices-on-audacity/"><u>Troubleshooting Errors When Opening Sound Devices on Audacity</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-windows-from-s-mode-shackles/"><u>Unraveling Windows: From S Mode Shackles</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-and-linux-how-wsl-changes-the-game/"><u>Windows and Linux: How WSL Changes the Game?</u></a></li>
</ul></div>
