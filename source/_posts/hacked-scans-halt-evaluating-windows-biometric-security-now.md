---
title: "Hacked Scans Halt: Evaluating Window's Biometric Security Now"
date: 2024-12-02T20:04:36.915Z
updated: 2024-12-03T22:21:46.497Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cBCyRXC1-Tw?si=lN9P2xo0hsfyD8K6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Can People Hack Windows Hello Fingerprint Scanners?

![Lock Having Fingerprint in the Middle on Blue Background](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/passwords-are-a-thing-of-the-past-passwordless-logins-benefits.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DBMTAJBx-X4?si=sje5pFJXiHzJJGbP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If a hacker wants to bypass a fingerprint scanner on a Windows machine, they're aiming to get past a service called Windows Hello. This service handles how you log into Windows, such as PINs, facial scans, and fingerprint scans.

 As part of research into Windows Hello's strength, two [white-hat hackers](https://www.makeuseof.com/white-hat-hacker/), Jesse D'Aguanno and Timo Teräs, posted a report on their website, [Blackwing HQ](https://blackwinghq.com/blog/posts/a-touch-of-pwn-part-i/). The report details how they breached three popular devices: the Dell Inspiron 15, Lenovo ThinkPad T14, and the Microsoft Surface Pro Type Cover.

### How the Hackers Breached Windows Hello on the Dell Inspiron 15

 For the Dell Inspiron 15, the hackers noticed they could boot into Linux on the laptop. Once logged into Linux, they can register their fingerprints in the system and give it the same ID as the Windows user they want to log into.

 Then, they perform a man-in-the-middle attack on the connection between the PC and the sensor. They set it up so that when Windows goes to double-check that a scanned fingerprint is legitimate, it ends up checking the Linux database of fingerprints instead of its own.

 To dodge Windows Hello, the hackers uploaded their fingerprints to the Linux database, assigned it the same ID as the user on Windows, and then tried to log into Windows with their fingerprints. During the authentication process, they redirected the packet to the Linux database, which told Windows that the user at the specified ID was ready to log in.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/L603QXgjb3I?si=sMYHfMGy2kNPSHPt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 3\. The Attacks Only Work on Specific Devices

 You'll notice that each attack had to take a different path to achieve the same goal. Every device is unique, and a hack that works on one device may not work on another. As such, you shouldn't believe that Windows Hello has now been blown wide open on every device; it's just these three that failed.

 While these hacks may sound scary, they'll be challenging to perform against actual targets. The hacker will likely have to steal the device to perform these hacks, which would undoubtedly alert the previous owner.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YZma8PBO0D8?si=9-qQgGVTuChYd27a" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://extra-resources.techidaily.com/2024-approved-advanced-tutorial-exploiting-googles-automatic-transcription-features/"><u>2024 Approved Advanced Tutorial Exploiting Google's Automatic Transcription Features</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/advanced-color-grading-techniques-with-luts-for-after-effects-users/"><u>Advanced Color Grading Techniques with LUTs for After Effects Users</u></a></li>
<li><a href="https://printer-issues.techidaily.com/canon-printer-not-printing-conquer-this-issue-with-our-top-5-solutions-for-windows-11/"><u>Canon Printer Not Printing? Conquer This Issue with Our Top 5 Solutions for Windows 11</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/disabling-the-audio-narration-feature-in-your-samsung-television/"><u>Disabling the Audio Narration Feature in Your Samsung Television</u></a></li>
<li><a href="https://android-location.techidaily.com/fake-android-location-without-rooting-for-your-vivo-y27s-drfone-by-drfone-virtual/"><u>Fake Android Location without Rooting For Your Vivo Y27s | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-showhide-directories-on-modern-windows-11-pcs/"><u>Guide to Show/Hide Directories on Modern Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-plain-out-windows-edges/"><u>How to Plain Out Windows Edges</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-tecno-pova-5-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Read This Guide to Find a Reliable Alternative to Fake GPS On Tecno Pova 5 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/iphoneandroid-your-smartphone-as-a-windows-microphone/"><u>IPhone/Android: Your Smartphone as a Windows Microphone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/key-techniques-to-optimize-igtv-video-dimensions/"><u>Key Techniques to Optimize IGTV Video Dimensions</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-image-spin-6-tactics-for-windows-11/"><u>Mastering Image Spin: 6 Tactics for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-quick-start-for-rdc-on-windows-11/"><u>Mastering the Art of Quick Start for RDC on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-local-gpo-on-windows-with-ease/"><u>Navigating Local GPO on Windows with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-error-x8019-on-windows-xp/"><u>Preventing Error X8019 on Windows XP</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/the-ultimate-handbook-for-vr-gameplay-capture/"><u>The Ultimate Handbook for VR Gameplay Capture</u></a></li>
</ul></div>

