---
title: "Cracked Codekeepers: Stay Secure in the Now"
date: 2025-01-09T13:53:57.256Z
updated: 2025-01-15T20:12:32.688Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Cracked Codekeepers: Stay Secure in the Now"
excerpt: "This Article Describes Cracked Codekeepers: Stay Secure in the Now"
keywords: Cracked Cybersecurity,KeepSecureNow,CodeKeepersTips,SecurityInTheNow,SafeHackingMethods,DigitalSecurityStay,NowSafeCyberspace
thumbnail: https://thmb.techidaily.com/1d7a3c5b577ddb7940a6a2457c0bee5c40f1807e21452ed2f6065cb51e5a9f16.jpg
---

## Cracked Codekeepers: Stay Secure in the Now

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X4q6gyaEojM?si=ImdFm6Zsr0azykqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [How Was BitLocker's Encryption Broken?](#how-was-bitlocker-39-s-encryption-broken)
* [Is It Time to Ditch BitLocker?](#is-it-time-to-ditch-bitlocker)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eMEJvwMM0vk?si=EQF_jo_4u9v5iJ_C" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_dOmuXhsV6Y?si=aT6vgPbDx4ajjvdr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_SbYznUy_zY?si=ThBkP934r3mizi48" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Is It Time to Ditch BitLocker?

 Interestingly, [Microsoft was already aware](https://learn.microsoft.com/en-us/windows/security/operating-system-security/data-protection/bitlocker/countermeasures#attacker-countermeasures) of the potential for this attack. However, this is the first time a practical attack has surfaced at large, illustrating just how fast BitLocker encryption keys can be stolen.

 It raises the vital question of whether you should consider switching to a BitLocker alternative, like the [free and open-source VeraCrypt](https://www.makeuseof.com/encrypt-windows-system-drive-veracrypt/). The good news is that you don't need to jump ship for a few reasons.

 First, the exploit only works with external TPMs that request data from the module using the LPC bus. Most modern hardware integrates the TPM. While a motherboard-based TPM could theoretically be exploited, it would require more time, effort, and an extensive period with the target device. Extracting BitLocker Volume Master Key data from a TPM becomes even more difficult if the module is integrated into the CPU.

 AMD CPUs have integrated TPM 2.0 since 2016 (with the launch of AM4, known as fTPM), while Intel CPUs integrated TPM 2.0 with the launch of its 8th Generation Coffee Lake CPUs in 2017 (known as PTT). Suffice to say, if you're using a machine with an AMD or Intel CPU manufacturer after those dates, you're most likely safe.

 It's also worth noting that despite this exploit, BitLocker remains secure, and the actual encryption underpinning it, AES-128 or AES-256, is still secure.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-skills.techidaily.com/new-ultimate-unison-unit-for-voice-broadcasting/"><u>[New] Ultimate Unison Unit for Voice Broadcasting</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-copyright-concerns-with-recording-youtube-content-for-2024/"><u>[Updated] Copyright Concerns with Recording YouTube Content for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/a-perfect-guide-to-remove-or-disable-google-smart-lock-on-honor-x50-by-drfone-android/"><u>A Perfect Guide To Remove or Disable Google Smart Lock On Honor X50</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-can-life360-track-or-see-text-messages-what-can-you-do-with-life360-on-vivo-s17-drfone-by-drfone-virtual-android/"><u>In 2024, Can Life360 Track Or See Text Messages? What Can You Do with Life360 On Vivo S17? | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-demystifying-youtubes-keyword-power-play/"><u>In 2024, Demystifying YouTube's Keyword Power Play</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-to-win-11s-insider-program-enrollment/"><u>Navigating to Win 11'S Insider Program Enrollment</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-image-clarity-windows-11s-background-blur-tricks/"><u>Perfecting Image Clarity: Windows 11'S Background Blur Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-systemsettings-errors-in-windows-11/"><u>Preventing SystemSettings Errors in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-fingerprint-scanning-not-found-in-windows/"><u>Remedying Fingerprint Scanning Not Found in Windows</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/resolving-startup-issues-a-comprehensive-guide-on-overcoming-code-1-malfunctions/"><u>Resolving Startup Issues: A Comprehensive Guide on Overcoming 'Code #1' Malfunctions</u></a></li>
<li><a href="https://windows11.techidaily.com/touching-your-world-better-the-ultimate-guide-to-pc-touch-adjustment/"><u>Touching Your World Better: The Ultimate Guide to PC Touch Adjustment</u></a></li>
</ul></div>

