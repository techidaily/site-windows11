---
title: "Hacked Scans Halt: Evaluating Window's Biometric Security Now"
date: 2024-10-01T02:19:00.254Z
updated: 2024-10-06T16:26:30.598Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Hacked Scans Halt: Evaluating Window's Biometric Security Now"
excerpt: "This Article Describes Hacked Scans Halt: Evaluating Window's Biometric Security Now"
keywords: Windows Bios Security Check,Biometric Hack Alert,Secure Windows Login,Impaired Window Access,Password Scan Stop,Lockout Scanner Error,Biometrics Failed Test
thumbnail: https://thmb.techidaily.com/de25cad762d1b1da1023e95cc7ce6ed0cc716ab658bda48c421a9e8a9c4e4418.png
---

## Hacked Scans Halt: Evaluating Window's Biometric Security Now

 Logging into a Windows laptop with a fingerprint scanner is easy; just place your finger on a scanner, and the operating system lets you in. However, researchers have shown that, while this method is convenient, it's not hackproof.

 So, how can people hack past a Windows Hello fingerprint scan, and should you worry about it?

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868575/19272" target="_top" id="1868575">
  <img src="//a.impactradius-go.com/display-ad/19272-1868575" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868575/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### How the Hackers Breached Windows Hello on the Microsoft Surface Pro Type Cover

 The hackers believed the Surface Pro would be the hardest device to crack, but they were surprised to find the Surface Pro lacked a lot of security measures for checking valid fingerprints. In fact, they discovered that they only had to dodge past one defense, then tell the Surface Pro that the fingerprint scan was successful, and the device let them in.

## What Do These Hacks Mean for You?

![Professional Thinking With Laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/professional-thinking-with-laptop.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037338/7443" target="_top" id="2037338">
  <img src="//a.impactradius-go.com/display-ad/7443-2037338" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037338/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657400/16446" target="_top" id="1657400">
  <img src="//a.impactradius-go.com/display-ad/16446-1657400" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657400/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 1\. Do Not Leave Devices Unattended and Unprotected

 Because a hacker will need to interact with your device physically, you should ensure it doesn't fall into the wrong hands. For computers, you can [take steps to stop it from being stolen](https://www.makeuseof.com/tag/stop-entire-desktop-pc-home-office-stolen/). If you're using a laptop, never leave it alone in a public space, and use an [anti-theft laptop bag](https://www.makeuseof.com/tag/anti-theft-laptop-bags/) to stop people from tearing your bag open.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267">
  <img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://instagram-videos.techidaily.com/new-the-trap-of-tricksy-traffic-instagrams-hidden-hazard/"><u>[New] The Trap of Tricksy Traffic Instagram's Hidden Hazard</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-global-viewership-kings-youtubes-viral-royalty/"><u>[Updated] In 2024, Global Viewership Kings YouTube's Viral Royalty</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-prime-action-cameras-with-superior-mics-for-2024/"><u>[Updated] Prime Action Cameras with Superior Mics for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-complete-pacera-free-audio-liberation-handbook/"><u>[Updated] The Complete Pacera Free Audio Liberation Handbook</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-guide-to-fixing-webcam-error-codes-on-w1011/"><u>Expert Guide to Fixing Webcam Error Codes on W10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixed-your-input-not-recognized-windows-vlc-error/"><u>Fixed: Your Input Not Recognized – Windows VLC Error</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-users-through-printer-access-errors/"><u>Guiding Users Through Printer Access Errors</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-strategic-trailer-planning-for-increased-channels-profitability/"><u>In 2024, Strategic Trailer Planning for Increased Channels' Profitability</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-the-boomerang-edge-captivating-your-instagram-audience/"><u>In 2024, The Boomerang Edge Captivating Your Instagram Audience</u></a></li>
<li><a href="https://windows11.techidaily.com/leverage-full-power-of-windows-11-today/"><u>Leverage Full Power of Windows 11 Today</u></a></li>
<li><a href="https://extra-tips.techidaily.com/olyx-zones-the-creme-de-la-snowspeedcross/"><u>OlyX-Zones The Crème De La Snowspeedcross</u></a></li>
<li><a href="https://extra-resources.techidaily.com/pro-gopro-filming-techniques-unveiled/"><u>Pro-Gopro Filming Techniques Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-non-active-windows-volume-snapshot/"><u>Reviving Non-Active Windows Volume Snapshot</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-integration-of-google-play-store-in-win11/"><u>Seamless Integration of Google Play Store in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-your-connection-top-fixes-for-hidden-wireless-networks-in-windows/"><u>Secure Your Connection: Top Fixes for Hidden Wireless Networks in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-your-windows-11-experience/"><u>Streamlining Your Windows 11 Experience</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/unique-outro-music-files-at-your-fingertips-free-for-2024/"><u>Unique Outro Music Files at Your Fingertips - Free for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-the-ipogo-get-you-banned-and-how-to-solve-it-on-oppo-reno-9a-drfone-by-drfone-virtual-android/"><u>Will the iPogo Get You Banned and How to Solve It On Oppo Reno 9A | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-at-wifi-less-windows-11-setup/"><u>Winning at Wifi-Less Windows 11 Setup</u></a></li>
</ul></div>

