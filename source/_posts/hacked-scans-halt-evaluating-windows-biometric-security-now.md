---
title: "Hacked Scans Halt: Evaluating Window's Biometric Security Now"
date: 2024-11-14T16:03:15.088Z
updated: 2024-11-15T16:32:14.810Z
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
<span id="1975503">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975503.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975503">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975503.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975503%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975503/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### How the Hackers Breached Windows Hello on the Microsoft Surface Pro Type Cover

 The hackers believed the Surface Pro would be the hardest device to crack, but they were surprised to find the Surface Pro lacked a lot of security measures for checking valid fingerprints. In fact, they discovered that they only had to dodge past one defense, then tell the Surface Pro that the fingerprint scan was successful, and the device let them in.

## What Do These Hacks Mean for You?

![Professional Thinking With Laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/professional-thinking-with-laptop.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2052062/7443" target="_top" id="2052062">
  <img src="//a.impactradius-go.com/display-ad/7443-2052062" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052062/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 These hacks may sound pretty scary if you use fingerprints to log into your laptop. However, it's essential to remember some crucial things before you forgo fingerprint scans entirely.

### 1\. The Attacks Were Performed by Skilled Hackers

 The reason threats like [ransomware as a service](https://www.makeuseof.com/what-is-ransomware-as-a-service/) are so deadly is that anyone with minimal cybersecurity can use them. However, the above hacks require a high level of expertise, with a deep understanding of how devices authenticate fingerprints and how to avoid them.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2112007/7443" target="_top" id="2112007">
  <img src="//a.impactradius-go.com/display-ad/7443-2112007" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2112007/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://aidotcom.pxf.io/c/5597632/2134499/19576" target="_top" id="2134499">
  <img src="//a.impactradius-go.com/display-ad/19576-2134499" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134499/19576" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-premier-selector-exclusive-app-selection-for-your-videos/"><u>[Updated] In 2024, Premier Selector Exclusive App Selection for Your Videos</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-perfecting-your-screen-recording-during-games-for-2024/"><u>[Updated] Perfecting Your Screen Recording During Games for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-seamless-obs-integration-on-your-mac-a-detailed-walkthrough/"><u>[Updated] Seamless OBS Integration on Your Mac A Detailed Walkthrough</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-unveiling-the-hidden-pathways-to-earning-on-youtube/"><u>[Updated] Unveiling the Hidden Pathways to Earning on YouTube</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-save-while-you-teach-hosting-low-cost-seminars-via-youtube/"><u>2024 Approved Save While You Teach Hosting Low-Cost Seminars via YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-users-through-privilege-related-setup-hiccups/"><u>Guiding Users Through Privilege-Related Setup Hiccups</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-bypass-apple-iphone-14-pro-passcode-easily-video-inside-drfone-by-drfone-ios/"><u>How to Bypass Apple iPhone 14 Pro Passcode Easily Video Inside | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/razer-synapse-issues-step-by-step-troubleshooting-for-w11w10/"><u>Razer Synapse Issues: Step-by-Step Troubleshooting for W11/W10</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-printer-service-offline-errors/"><u>Resolving Windows Printer Service Offline Errors</u></a></li>
<li><a href="https://buynow-info.techidaily.com/reviewing-knacks-innovation-unveiling-the-charisma-of-its-main-character-within-a-common-genre/"><u>Reviewing Knack's Innovation: Unveiling the Charisma of Its Main Character Within a Common Genre</u></a></li>
<li><a href="https://win-answers.techidaily.com/step-by-step-guide-to-fixing-unwanted-shutdowns-in-your-halo-3-gaming-experience-on-computer/"><u>Step-by-Step Guide to Fixing Unwanted Shutdowns in Your Halo 3 Gaming Experience on Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-the-background-load-a-windows-guide/"><u>Taming the Background Load: A Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-effective-toolbar-navigation-with-mspcm-on-w11/"><u>The Art of Effective Toolbar Navigation with MSPCM on W11</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/the-ultimate-guide-to-mac-based-sound-capture-in-audacity/"><u>The Ultimate Guide to Mac-Based Sound Capture in Audacity</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-unresponsive-inputs-in-win11s-sleep-mode/"><u>Troubleshooting Unresponsive Inputs in Win11's Sleep Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/w11-pros-best-offers-save-and-elevate-your-spend/"><u>W11 Pro's Best Offers: Save & Elevate Your Spend</u></a></li>
<li><a href="https://windows11.techidaily.com/win11s-ingenious-techniques-for-gathering-info/"><u>Win11's Ingenious Techniques for Gathering Info</u></a></li>
</ul></div>

