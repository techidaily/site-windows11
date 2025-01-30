---
title: "Hacked Scans Halt: Evaluating Window's Biometric Security Now"
date: 2025-01-29T05:05:11.661Z
updated: 2025-01-29T22:47:47.382Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

## What Do These Hacks Mean for You?

![Professional Thinking With Laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/professional-thinking-with-laptop.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLlUft1ZxI0?si=pBd5QdHEE27qsNlN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 These hacks may sound pretty scary if you use fingerprints to log into your laptop. However, it's essential to remember some crucial things before you forgo fingerprint scans entirely.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XVsiIO7hWOc?si=UvWnqxaI_yHwEr74" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 1\. The Attacks Were Performed by Skilled Hackers

 The reason threats like [ransomware as a service](https://www.makeuseof.com/what-is-ransomware-as-a-service/) are so deadly is that anyone with minimal cybersecurity can use them. However, the above hacks require a high level of expertise, with a deep understanding of how devices authenticate fingerprints and how to avoid them.

### 2\. The Attacks Require the Attacker to Physically Interact With the Device

 The hackers must have physical contact with the device to perform the above hacks. In the report, the hackers stated they might be able to create USB devices that can perform the attack once plugged in, but that means a potential attacker needs to plug something into your PC to hack it.

### 3\. The Attacks Only Work on Specific Devices

 You'll notice that each attack had to take a different path to achieve the same goal. Every device is unique, and a hack that works on one device may not work on another. As such, you shouldn't believe that Windows Hello has now been blown wide open on every device; it's just these three that failed.

 While these hacks may sound scary, they'll be challenging to perform against actual targets. The hacker will likely have to steal the device to perform these hacks, which would undoubtedly alert the previous owner.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/VxFUhesNCKo?si=Ti0ui6DXYP12sjSs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Stay Safe From Fingerprint Hacking

![The face of a man wearing a hoodie](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hacher-hat.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=M69YSY0Mk_gsdU0Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-lab.techidaily.com/treamlined-processes-for-swift-comment-removal-on-youtube-for-2024/"><u>[New] Streamlined Processes for Swift Comment Removal on YouTube for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-exclusive-selections-best-virtual-reality-titles-for-cardboard/"><u>[Updated] In 2024, Exclusive Selections Best Virtual Reality Titles for Cardboard</u></a></li>
<li><a href="https://discover-alternatives.techidaily.com/1-winxvideo-ai/"><u>1. WinxVideo AI: 最常聞的技術疑問及其解決方式</u></a></li>
<li><a href="https://program-issues.techidaily.com/dark-souls-3-resolved-problems-with-game-freezing-and-crashes/"><u>Dark Souls 3: Resolved Problems with Game Freezing & Crashes</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/enhancing-speech-clarity-on-skype/"><u>Enhancing Speech Clarity on Skype</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-techniques-to-rectify-critical-discord-javascript-hiccup-in-w10w11/"><u>Essential Techniques to Rectify Critical Discord JavaScript Hiccup in W10/W11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-a-network-locked-realme-c55-phone-by-drfone-android/"><u>In 2024, How to Unlock a Network Locked Realme C55 Phone?</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/96179881-9781634242271-liber-420/"><u>Liber 420 | Free Book</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-sound-levels-windows-11s-volume-mixer-guide/"><u>Mastering Sound Levels: Windows 11'S Volume Mixer Guide</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/my-top-pick-from-ces-the-unique-laptop-pen-that-writes-like-magic-a-must-see-at-the-tech-showcase/"><u>My Top Pick From CES: The Unique Laptop Pen That Writes Like Magic - A Must-See at the Tech Showcase</u></a></li>
<li><a href="https://windows11.techidaily.com/no-more-confusion-selecting-ideal-drives-for-gameplay/"><u>No More Confusion: Selecting Ideal Drives for Gameplay</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-recovery-resolving-common-rpc-errors-on-windows/"><u>Quick Recovery: Resolving Common RPC Errors on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/realigning-windows-group-policies-for-organizational-needs/"><u>Realigning Windows Group Policies for Organizational Needs</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-logins-epic-games-fix-guide-for-win-users/"><u>Restoring Logins: Epic Games Fix Guide for Win Users</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-transition-of-imessage-from-ios-to-windows-os/"><u>Seamless Transition of iMessage From iOS to Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/simplify-win-11-repairs-with-custom-buttons/"><u>Simplify Win 11 Repairs with Custom Buttons</u></a></li>
<li><a href="https://win-trending.techidaily.com/solving-the-icloud-backup-problem-a-step-by-step-guide-to-restoring-your-greyed-out-feature/"><u>Solving the iCloud Backup Problem: A Step-by-Step Guide to Restoring Your Greyed-Out Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-windows-1111-store-error-0x800704cf/"><u>Solving Windows 11/11 Store Error 0X800704CF</u></a></li>
<li><a href="https://windows11.techidaily.com/transformative-windows-11-the-finest-replacements-guide/"><u>Transformative Windows 11: The Finest Replacements Guide</u></a></li>
</ul></div>

