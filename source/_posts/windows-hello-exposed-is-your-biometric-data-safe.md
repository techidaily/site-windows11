---
title: "Windows Hello Exposed: Is Your Biometric Data Safe?"
date: 2024-09-09T12:11:22.833Z
updated: 2024-09-10T12:11:22.833Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Hello Exposed: Is Your Biometric Data Safe?"
excerpt: "This Article Describes Windows Hello Exposed: Is Your Biometric Data Safe?"
keywords: Windows Hello Security,Biometric Safety,Facial Recognition Risks,Windows Privacy Concerns,Digital Identity Protection,Biometric Data Exposure,Safe Login Methods
thumbnail: https://thmb.techidaily.com/14a22e63716263e4dbf21490561e8b1d60bb16b34f9d12286d81f3b90aa95801.jpg
---

## Windows Hello Exposed: Is Your Biometric Data Safe?

 Logging into a Windows laptop with a fingerprint scanner is easy; just place your finger on a scanner, and the operating system lets you in. However, researchers have shown that, while this method is convenient, it's not hackproof.

 So, how can people hack past a Windows Hello fingerprint scan, and should you worry about it?

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135411/19272" target="_top" id="2135411">
  <img src="//a.impactradius-go.com/display-ad/19272-2135411" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135411/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Can People Hack Windows Hello Fingerprint Scanners?

![Lock Having Fingerprint in the Middle on Blue Background](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/passwords-are-a-thing-of-the-past-passwordless-logins-benefits.jpg)

 If a hacker wants to bypass a fingerprint scanner on a Windows machine, they're aiming to get past a service called Windows Hello. This service handles how you log into Windows, such as PINs, facial scans, and fingerprint scans.

 As part of research into Windows Hello's strength, two [white-hat hackers](https://www.makeuseof.com/white-hat-hacker/), Jesse D'Aguanno and Timo Teräs, posted a report on their website, [Blackwing HQ](https://blackwinghq.com/blog/posts/a-touch-of-pwn-part-i/). The report details how they breached three popular devices: the Dell Inspiron 15, Lenovo ThinkPad T14, and the Microsoft Surface Pro Type Cover.

### How the Hackers Breached Windows Hello on the Dell Inspiron 15

 For the Dell Inspiron 15, the hackers noticed they could boot into Linux on the laptop. Once logged into Linux, they can register their fingerprints in the system and give it the same ID as the Windows user they want to log into.

 Then, they perform a man-in-the-middle attack on the connection between the PC and the sensor. They set it up so that when Windows goes to double-check that a scanned fingerprint is legitimate, it ends up checking the Linux database of fingerprints instead of its own.

 To dodge Windows Hello, the hackers uploaded their fingerprints to the Linux database, assigned it the same ID as the user on Windows, and then tried to log into Windows with their fingerprints. During the authentication process, they redirected the packet to the Linux database, which told Windows that the user at the specified ID was ready to log in.

<!-- affiliate ads begin -->
<span id="1702748">
					<video width="192" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1702748.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18544-1702748">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1702748.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:120px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftwopages.pxf.io%2Fc%2F5597632%2F1702748%2F18544'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702748/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### How the Hackers Breached Windows Hello on the Lenovo ThinkPad T14

 For the Lenovo ThinkPad, the hackers discovered that the laptop used a custom encryption method to verify fingerprints. With some work, the hackers managed to decrypt it, giving them a way into the fingerprint verification process.

 Once done, the hackers could force the fingerprint database to accept their fingerprint as the user's. Then, all they had to do was scan their fingerprint to access the Lenovo ThinkPad.

### How the Hackers Breached Windows Hello on the Microsoft Surface Pro Type Cover

 The hackers believed the Surface Pro would be the hardest device to crack, but they were surprised to find the Surface Pro lacked a lot of security measures for checking valid fingerprints. In fact, they discovered that they only had to dodge past one defense, then tell the Surface Pro that the fingerprint scan was successful, and the device let them in.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123476/16836" target="_top" id="2123476">
  <img src="//a.impactradius-go.com/display-ad/16836-2123476" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123476/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Do These Hacks Mean for You?

![Professional Thinking With Laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/professional-thinking-with-laptop.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139117/17108" target="_top" id="2139117">
  <img src="//a.impactradius-go.com/display-ad/17108-2139117" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139117/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 These hacks may sound pretty scary if you use fingerprints to log into your laptop. However, it's essential to remember some crucial things before you forgo fingerprint scans entirely.

### 1\. The Attacks Were Performed by Skilled Hackers

 The reason threats like [ransomware as a service](https://www.makeuseof.com/what-is-ransomware-as-a-service/) are so deadly is that anyone with minimal cybersecurity can use them. However, the above hacks require a high level of expertise, with a deep understanding of how devices authenticate fingerprints and how to avoid them.

### 2\. The Attacks Require the Attacker to Physically Interact With the Device

 The hackers must have physical contact with the device to perform the above hacks. In the report, the hackers stated they might be able to create USB devices that can perform the attack once plugged in, but that means a potential attacker needs to plug something into your PC to hack it.

<!-- affiliate ads begin -->
<span id="1743243">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1743243.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19272-1743243">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1743243.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Faligracehair.sjv.io%2Fc%2F5597632%2F1743243%2F19272'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1743243/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 3\. The Attacks Only Work on Specific Devices

 You'll notice that each attack had to take a different path to achieve the same goal. Every device is unique, and a hack that works on one device may not work on another. As such, you shouldn't believe that Windows Hello has now been blown wide open on every device; it's just these three that failed.

 While these hacks may sound scary, they'll be challenging to perform against actual targets. The hacker will likely have to steal the device to perform these hacks, which would undoubtedly alert the previous owner.

## How to Stay Safe From Fingerprint Hacking

![The face of a man wearing a hoodie](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hacher-hat.jpg)

<!-- affiliate ads begin -->
<span id="1542129">
					<video width="864" height="1152" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1542129.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16836-1542129">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1542129.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2F25home.pxf.io%2Fc%2F5597632%2F1542129%2F16836'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1542129/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 As stated above, the discovered hacks are complicated to perform and may require the hacker to remove the device to hack into it physically. As such, there's an extremely low chance that these attacks will personally target you.

 However, if you're still not satisfied, there are some ways to protect yourself from fingerprint scanner hacks:

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137394/7443" target="_top" id="2137394">
  <img src="//a.impactradius-go.com/display-ad/7443-2137394" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Do Not Leave Devices Unattended and Unprotected

 Because a hacker will need to interact with your device physically, you should ensure it doesn't fall into the wrong hands. For computers, you can [take steps to stop it from being stolen](https://www.makeuseof.com/tag/stop-entire-desktop-pc-home-office-stolen/). If you're using a laptop, never leave it alone in a public space, and use an [anti-theft laptop bag](https://www.makeuseof.com/tag/anti-theft-laptop-bags/) to stop people from tearing your bag open.

### 2\. Use a Different Login Method

 Windows Hello supports many different login methods, some more secure than others. If you've fallen out of love with fingerprint scans, check out if [face, iris, fingerprint, PIN, or password logins are more secure](https://www.makeuseof.com/face-iris-fingerprint-password-pin-most-secure/), and choose one that suits you best.

 If you're worried about these hacks, it's important to remember that there's a very low chance they'll target you specifically. As such, you should be safe using fingerprint scans; just don't allow people to steal your devices.

 So, how can people hack past a Windows Hello fingerprint scan, and should you worry about it?

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-compile-presentation-asset-to-video/"><u>[New] 2024 Approved Compile Presentation Asset to Video</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-uniting-your-network-with-cross-platform-skype-chat-groups-a-how-to-guide/"><u>[New] 2024 Approved Uniting Your Network with Cross-Platform Skype Chat Groups A How-To Guide</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-next-gen-televisions-elite-10-rankings/"><u>[New] Next-Gen Televisions Elite #10 Rankings</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-comprehensive-guide-to-choosing-podcast-names-plus-creative-ideas-list/"><u>[Updated] Comprehensive Guide to Choosing Podcast Names + Creative Ideas List</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-digital-storytelling-creating-compelling-gifs-for-2024/"><u>[Updated] Digital Storytelling Creating Compelling GIFs for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-elevate-your-channel-game-tubebuddy-insights-for-2024/"><u>[Updated] Elevate Your Channel Game - TubeBuddy Insights for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-expert-tips-on-jump-cuts-for-dynamic-video-editing/"><u>[Updated] Expert Tips on Jump Cuts for Dynamic Video Editing</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-the-seamless-blend-of-images-into-majestic-collage-art/"><u>[Updated] In 2024, The Seamless Blend of Images Into Majestic Collage Art</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-next-level-mac-cam-apps-avoiding-the-bandicamp-route-for-2024/"><u>[Updated] Next-Level Mac Cam Apps Avoiding the Bandicamp Route for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-and-update-intel-hd-graphics-drivers-on-windows-11-step-by-step-guide/"><u>Download & Update Intel HD Graphics Drivers on Windows 11: Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/harness-the-power-of-folder-and-file-unification-in-windows-11/"><u>Harness the Power of Folder & File Unification in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-your-browser-is-managed-by-your-organization-on-chrome-and-edge-for-windows/"><u>How to Fix Your Browser Is Managed by Your Organization on Chrome and Edge for Windows</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-tiktok-to-see-more-content-on-your-honor-90-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location on TikTok to See More Content On your Honor 90 | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-vivo-y27-4g-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Vivo Y27 4G to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-ideal-audio-gear-compatible-with-cutting-edge-4k-technology/"><u>In 2024, Ideal Audio Gear Compatible with Cutting-Edge 4K Technology</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-set-your-preferred-job-location-on-linkedin-app-of-your-infinix-smart-7-hd-drfone-by-drfone-virtual-android/"><u>In 2024, Set Your Preferred Job Location on LinkedIn App of your Infinix Smart 7 HD | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/insider-tips-for-manual-windows-security-scanning/"><u>Insider Tips for Manual Windows Security Scanning</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-downloads-weighing-choco-against-wm/"><u>Mastering Windows Downloads: Weighing Choco Against WM</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-machine-identification-in-under-150-characters/"><u>Mastering Windows Machine Identification in Under 150 Characters</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-delete-temp-files-easily/"><u>Mastering Windows: Delete Temp Files Easily</u></a></li>
<li><a href="https://techtrends.techidaily.com/1722864398764-no-more-distractions-a-step-by-step-guide-to-blocking-unwanted-sms-on-iphone/"><u>No More Distractions: A Step-By-Step Guide to Blocking Unwanted SMS on iPhone.</u></a></li>
<li><a href="https://windows11.techidaily.com/optimal-6-tracking-applications-to-enhance-pc-productivity/"><u>Optimal 6 Tracking Applications to Enhance PC Productivity</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-0x80246007-update-obstacle-on-windows-1011/"><u>Overcoming 0X80246007 Update Obstacle on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-services-woes-a-guide-to-fixing-the-non-operational-tool/"><u>Overcoming Windows Services Woes: A Guide to Fixing the Non-Operational Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-battery-status-alerts-windows-edition/"><u>Perfecting Battery Status Alerts: Windows Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/removing-aw-snap-from-your-chrome-browser-on-windows/"><u>Removing “Aw, Snap!” From Your Chrome Browser on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/reverse-webp-images-in-chrome-for-windows-users/"><u>Reverse WebP Images in Chrome for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/simple-steps-reactivating-and-customizing-the-old-photo-viewer-in-win11/"><u>Simple Steps: Reactivating and Customizing the Old Photo Viewer in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-freezes-aps-for-pcs/"><u>Taming Freezes: APS for PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-resolving-stranded-on-xbox-app-in-windows-devices/"><u>Troubleshooting: Resolving 'Stranded' On Xbox App in Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/unclutter-your-windows-desktop-space/"><u>Unclutter Your Windows Desktop Space</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-ftdibussys-the-enigma-of-memory-standards-violation/"><u>Unveiling ftdibus.sys: The Enigma of Memory Standards Violation</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-of-microsoft-family-safety/"><u>Unveiling the Secrets of Microsoft Family Safety</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-full-disclosure-on-nero-audiomanipulation-kit-features/"><u>Updated Full Disclosure on Nero AudioManipulation Kit Features</u></a></li>
<li><a href="https://windows11.techidaily.com/why-your-wi-fi-mouse-isnt-working-quick-fixes-for-windows/"><u>Why Your Wi-Fi Mouse Isn't Working? Quick Fixes for Windows</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>