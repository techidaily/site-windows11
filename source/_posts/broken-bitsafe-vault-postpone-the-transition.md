---
title: "Broken BitSafe Vault: Postpone the Transition"
date: 2024-07-03T11:17:28.583Z
updated: 2024-07-04T11:17:28.583Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Broken BitSafe Vault: Postpone the Transition"
excerpt: "This Article Describes Broken BitSafe Vault: Postpone the Transition"
keywords: Vault Breach Alert,Safe Access Delay,Security Upgrade Halted,Secure Storage Compromised,BitSafe Integrity Flaw,Transition Postponement,Digital Lockdown Issues
thumbnail: https://thmb.techidaily.com/57a4dd5881ee89a7ccb05cda2bbc7d01f9c197463ce070f6b273e0abf69dbbe5.jpg
---

## Broken BitSafe Vault: Postpone the Transition

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
<li><a href="https://windows11.techidaily.com/navigate-past-onedrive-sign-in-snags-with-windows-steps/"><u>Navigate Past OneDrive Sign-In Snags with Windows Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-elevate-your-old-computer-into-a-windows-11-powerhouse/"><u>How to Elevate Your Old Computer Into a Windows 11 Powerhouse</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-paths-blocked-by-shared-printers/"><u>Clearing Paths Blocked by Shared Printers</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-address-geforce-nows-error-code-xc0f1103f/"><u>How To Address GeForce Now's Error Code Xc0f1103f</u></a></li>
<li><a href="https://windows11.techidaily.com/breakdown-utilizing-bluescreenview-for-professionals/"><u>Breakdown: Utilizing BlueScreenView for Professionals</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-virtual-environments-ideal-for-windows-11-systems/"><u>Top 5 Virtual Environments Ideal for Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-file-system-woes-on-windows-11/"><u>Navigating File System Woes on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-isarcextract-error-a-window-11-solution/"><u>Overcoming ISArcExtract Error: A Window 11 Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-windows-volume-preserve-data/"><u>Enhance Windows Volume, Preserve Data</u></a></li>
<li><a href="https://windows11.techidaily.com/quickly-fixing-microsoft-store-problems-on-win-11/"><u>Quickly Fixing Microsoft Store Problems on Win 11</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/unseen-social-media-hits-top-10-meme-pages-for-2024/"><u>Unseen Social Media Hits – Top 10 Meme Pages for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/expert-insights-into-crafting-dynamic-youtube-shorts-templates-for-2024/"><u>Expert Insights Into Crafting Dynamic YouTube Shorts Templates for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-6-essential-video-editing-software-for-windows-for-2024/"><u>New 6 Essential Video Editing Software for Windows for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/cutting-edge-android-3d-viewer-tech/"><u>Cutting-Edge Android 3D Viewer Tech</u></a></li>
<li><a href="https://extra-support.techidaily.com/perfecting-sound-with-advanced-audacity-methods-for-2024/"><u>Perfecting Sound with Advanced Audacity Methods for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-top-apple-video-editors-for-creators/"><u>New 2024 Approved Top Apple Video Editors for Creators</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unleash-your-dj-iq-with-free-luts-for-djis-minis-and-air-series/"><u>[New] Unleash Your DJ IQ with FREE LUTs for DJI's Minis & Air Series</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unveiling-the-power-of-free-countdown-tools-for-time-management/"><u>2024 Approved  Unveiling the Power of Free Countdown Tools for Time Management</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-reset-a-nokia-c22-phone-that-is-locked-by-drfone-android/"><u>In 2024, How to Reset a Nokia C22 Phone that is Locked?</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-best-video-editing-software-for-mac-windows-movie-maker-alternatives/"><u>Updated Best Video Editing Software for Mac Windows Movie Maker Alternatives</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>