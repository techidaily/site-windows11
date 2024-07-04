---
title: "Breached Byte Bastion: Maintain, Reflect, Then Switch"
date: 2024-07-03T11:11:01.336Z
updated: 2024-07-04T11:11:01.336Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Breached Byte Bastion: Maintain, Reflect, Then Switch"
excerpt: "This Article Describes Breached Byte Bastion: Maintain, Reflect, Then Switch"
keywords: Cybersecurity Breach Maintenance,Data Security Strategies,Resilience in IT Safety,Security Update Protocols,Protecting Digital Assets,Safe System Reflection,Transition After Hacking
thumbnail: https://thmb.techidaily.com/38249dc1564a485522fb48e31e168d5147b5976c3d300d00e74bbaf1c0b88604.jpg
---

## Breached Byte Bastion: Maintain, Reflect, Then Switch

### Quick Links

* [How Was BitLocker's Encryption Broken?](#how-was-bitlocker-39-s-encryption-broken)
* [Is It Time to Ditch BitLocker?](#is-it-time-to-ditch-bitlocker)

### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

## Is It Time to Ditch BitLocker?

 Interestingly, [Microsoft was already aware](https://learn.microsoft.com/en-us/windows/security/operating-system-security/data-protection/bitlocker/countermeasures#attacker-countermeasures) of the potential for this attack. However, this is the first time a practical attack has surfaced at large, illustrating just how fast BitLocker encryption keys can be stolen.

 It raises the vital question of whether you should consider switching to a BitLocker alternative, like the [free and open-source VeraCrypt](https://www.makeuseof.com/encrypt-windows-system-drive-veracrypt/). The good news is that you don't need to jump ship for a few reasons.

 First, the exploit only works with external TPMs that request data from the module using the LPC bus. Most modern hardware integrates the TPM. While a motherboard-based TPM could theoretically be exploited, it would require more time, effort, and an extensive period with the target device. Extracting BitLocker Volume Master Key data from a TPM becomes even more difficult if the module is integrated into the CPU.

 AMD CPUs have integrated TPM 2.0 since 2016 (with the launch of AM4, known as fTPM), while Intel CPUs integrated TPM 2.0 with the launch of its 8th Generation Coffee Lake CPUs in 2017 (known as PTT). Suffice to say, if you're using a machine with an AMD or Intel CPU manufacturer after those dates, you're most likely safe.

 It's also worth noting that despite this exploit, BitLocker remains secure, and the actual encryption underpinning it, AES-128 or AES-256, is still secure.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/streamlining-policy-settings-with-proven-gpo-update-methods/"><u>Streamlining Policy Settings with Proven GPO Update Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-the-challenge-0x80072af9-errors/"><u>Conquering the Challenge: 0X80072AF9 Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-the-gap-enabling-smooth-steam-connection/"><u>Mending the Gap: Enabling Smooth Steam Connection</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-task-management-view-in-windows-11/"><u>Accelerate Task Management View in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windows-11-programs-for-faster-startups/"><u>Optimizing Windows 11 Programs for Faster Startups</u></a></li>
<li><a href="https://windows11.techidaily.com/unblock-windows-task-scheduler-issues-quickly/"><u>Unblock Windows Task Scheduler Issues Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-for-rockalldlldll-not-found-on-windows-devices/"><u>Fix for 'Rockalldll.dll' Not Found on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-correcting-incompatible-software-with-windows-operations/"><u>Strategies for Correcting Incompatible Software with Windows Operations</u></a></li>
<li><a href="https://windows11.techidaily.com/7-unique-windows-methods-for-launching-applications/"><u>7 Unique Windows Methods for Launching Applications</u></a></li>
<li><a href="https://extra-hints.techidaily.com/lightning-fast-windowed-photo-reader-for-win11/"><u>Lightning-Fast Windowed Photo Reader for Win11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-highlighting-progress-in-photo-shooting-algorithms/"><u>[New] Highlighting Progress in Photo Shooting Algorithms</u></a></li>
<li><a href="https://howto.techidaily.com/stuck-at-android-system-recovery-of-vivo-x90s-fix-it-easily-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Stuck at Android System Recovery Of Vivo X90S ? Fix It Easily | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-fake-snapchat-location-without-jailbreak-on-oneplus-nord-n30-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fake Snapchat Location without Jailbreak On OnePlus Nord N30 5G | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-apple-iphone-8-plus-with-a-mask-on-drfone-by-drfone-ios/"><u>How to Unlock Apple iPhone 8 Plus with a Mask On | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/discover-the-top-8-cost-free-videography-suites-for-digital-filmmakers/"><u>Discover the Top 8 Cost-Free Videography Suites for Digital Filmmakers</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-maximizing-your-reach-live-360-videos-on-facebook/"><u>[Updated] Maximizing Your Reach  Live 360 Videos on Facebook</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-real-time-recording-rivals-obs-and-shadowtoolkit/"><u>[New] Real-Time Recording Rivals  OBS & ShadowToolKit</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-the-art-of-logging-streaming-services-with-fidelity/"><u>[Updated] The Art of Logging Streaming Services with Fidelity</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-fix-ipad-or-apple-iphone-8-stuck-on-activation-lock-by-drfone-ios/"><u>How to Fix iPad or Apple iPhone 8 Stuck On Activation Lock?</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>