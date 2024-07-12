---
title: Windows Hello Biometrics Endangered by Recent Cyberattacks
date: 2024-07-11T21:41:00.441Z
updated: 2024-07-12T21:41:00.441Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Windows Hello Biometrics Endangered by Recent Cyberattacks
excerpt: This Article Describes Windows Hello Biometrics Endangered by Recent Cyberattacks
keywords: Windows Hello Biosecurity Threats,Cyber Attacks,Biometric Security Breaches Windows,Windows Hello Hacking Vulnerabilities,Protect Windows Biometrics From Cyberattacks,Safeguard Windows Hello Against Hackers,Biometrics at Risk
thumbnail: https://thmb.techidaily.com/907f940c68ac3ee45f8b59683cc047cc04665184817513adef7255fa53df8a70.jpg
---

## Windows Hello Biometrics Endangered by Recent Cyberattacks

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
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-optimized-vimeo-video-exporting-apps/"><u>[Updated] In 2024, Optimized Vimeo Video Exporting Apps</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-fake-gps-without-root-on-oppo-a56s-5g-drfone-by-drfone-virtual-android/"><u>3 Ways to Fake GPS Without Root On Oppo A56s 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/7-tricks-for-rejuvenating-non-responsive-windows-service-explorer/"><u>7 Tricks for Rejuvenating Non-Responsive Windows Service Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-evolution-unveiling-the-latest-system-updates/"><u>Windows 11'S Evolution: Unveiling the Latest System Updates</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/best-capcut-templates-for-slow-motion-video-trend/"><u>Best CapCut Templates for Slow Motion Video Trend</u></a></li>
<li><a href="https://windows11.techidaily.com/snip-and-sketch-vs-prtsc-the-best-tools-for-windows-users/"><u>Snip & Sketch Vs. PrtSc: The Best Tools for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/scrutinizing-underused-windows-features-for-system-checks/"><u>Scrutinizing Underused Windows Features for System Checks</u></a></li>
<li><a href="https://driver-install.techidaily.com/upgrade-to-aocs-e1659fwv-winos-compatibility/"><u>Upgrade to AOC's E1659FWV: WinOS Compatibility</u></a></li>
<li><a href="https://windows11.techidaily.com/reestablishing-clear-audio-conversations-on-valorant-pc/"><u>Reestablishing Clear Audio Conversations on Valorant PC</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-picking-a-software-dependency-provider/"><u>The Ultimate Guide to Picking a Software Dependency Provider</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-absence-of-thumbnail-images-on-windows-11-screens/"><u>Troubleshooting Absence of Thumbnail Images on Windows 11 Screens</u></a></li>
<li><a href="https://extra-hints.techidaily.com/dive-deep-into-dreamy-asmr-scenarios-for-rest/"><u>Dive Deep Into Dreamy ASMR Scenarios for Rest</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-registry-shortcomings-solutions/"><u>Unveiling Windows Registry Shortcomings: Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/reconnecting-to-ea-servers-in-a-windows-environment/"><u>Reconnecting to EA Servers in a Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-power-settings-for-cpu-state-insights/"><u>Unlocking Power Settings for CPU State Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/a-visual-journey-top-7-windows-10-drawing-tools-unveiled/"><u>A Visual Journey: Top 7 Windows 10 Drawing Tools Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-full-potential-mastering-multiple-screens-in-win11/"><u>Unlock Full Potential: Mastering Multiple Screens in Win11</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-if-you-want-to-know-how-to-create-animation-drawing-easily-check-this-post-to-master-animation-drawing-skills-with-7-steps-only/"><u>2024 Approved If You Want to Know How to Create Animation Drawing Easily, Check This Post to Master Animation Drawing Skills with 7 Steps Only</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-effective-utilization-of-whiteboards-on-mobile-and-desktop-for-online-learning/"><u>[New] In 2024, Effective Utilization of Whiteboards on Mobile and Desktop for Online Learning</u></a></li>
<li><a href="https://windows11.techidaily.com/silencing-the-audio-stutter-taming-winirq-errors/"><u>Silencing the Audio Stutter: Taming WinIRQ Errors</u></a></li>
<li><a href="https://howto.techidaily.com/why-your-samsung-galaxy-m14-4g-screen-might-be-unresponsive-and-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Your Samsung Galaxy M14 4G Screen Might be Unresponsive and How to Fix It | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-remedy-for-rearranged-character-inputs/"><u>Quick Remedy for Rearranged Character Inputs</u></a></li>
<li><a href="https://windows11.techidaily.com/tracking-windows-logins-identifying-successes-and-failures/"><u>Tracking Windows Logins: Identifying Successes & Failures</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-identifying-kits-with-intense-grumble-implementations-for-2024/"><u>Updated Identifying Kits with Intense Grumble Implementations for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-steam-service-problems-for-a-smooth-windows-11-experience/"><u>Solving Steam Service Problems for a Smooth Windows 11 Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/tracing-untapped-functions-within-windows-system-health-tools/"><u>Tracing Untapped Functions Within Windows' System Health Tools</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-should-you-keep-previewing-fb-activity-visible-insights/"><u>[New] Should You Keep Previewing FB Activity Visible? Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-overcome-endless-startup-in-bios-for-windows-systems/"><u>Steps to Overcome Endless Startup in BIOS for Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-activities-gain-more-in-less-time-with-flow-launcher/"><u>Streamline Activities: Gain More in Less Time With Flow Launcher</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-inside-sharex-analysis-reviews-and-counterparts/"><u>[Updated] In 2024, Inside ShareX Analysis  Reviews & Counterparts</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-to-activate-rgb-settings-in-windows-11/"><u>Step-by-Step to Activate RGB Settings in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-overcome-run-as-command-issues/"><u>Strategies to Overcome 'Run As' Command Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-task-execution-windows-keyboard-tips-and-tricks/"><u>Speedy Task Execution: Windows Keyboard Tips & Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-to-prevent-not-working-on-your-pc/"><u>Swift Solutions to Prevent 'Not Working' On Your PC</u></a></li>
<li><a href="https://activate-lock.techidaily.com/3-effective-ways-to-bypass-activation-lock-from-apple-iphone-7-by-drfone-ios/"><u>3 Effective Ways to Bypass Activation Lock from Apple iPhone 7</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-elevate-your-instagram-storytelling-with-automated-captions/"><u>In 2024, Elevate Your Instagram Storytelling with Automated Captions</u></a></li>
<li><a href="https://android-frp.techidaily.com/full-guide-to-bypass-realme-c67-5g-frp-by-drfone-android/"><u>Full Guide to Bypass Realme C67 5G FRP</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-steam-friendship-disconnect-on-pcs/"><u>Steps to Resolve Steam Friendship Disconnect on PCs</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-dive-into-high-end-slow-motion-filming-a-guide-for-aspiring-tiktok-stars/"><u>[New] 2024 Approved  Dive Into High-End Slow Motion Filming  A Guide for Aspiring TikTok Stars</u></a></li>
<li><a href="https://windows11.techidaily.com/why-is-nvidia-control-panel-inaccessible-on-win11/"><u>Why Is Nvidia Control Panel Inaccessible on Win11?</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-control-for-apps-and-browsers/"><u>Unveiling Windows Control for Apps & Browsers</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-apple-iphone-xs-max-passcode-without-itunes-without-knowing-passcode-by-drfone-ios/"><u>How to Unlock Apple iPhone XS Max Passcode without iTunes without Knowing Passcode?</u></a></li>
</ul></div>
