---
title: "Broken BitSafe Vault: Postpone the Transition"
date: 2025-01-21T16:39:50.303Z
updated: 2025-01-22T20:00:07.978Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4qA2pGQ5qmw?si=1mAA9WTi2Z5F7n6s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [How Was BitLocker's Encryption Broken?](#how-was-bitlocker-39-s-encryption-broken)
* [Is It Time to Ditch BitLocker?](#is-it-time-to-ditch-bitlocker)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-BHGGIC0zE?si=FzUQKZa-bx8OlKuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pRR3Oq03EuE?si=ZTy8-WH0AesA9zRh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aqeO4ed766s?si=AWtKHxP4hvQRd_lk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-best-windows-video-calls-the-top-8-list/"><u>[Updated] In 2024, Best Windows Video Calls The Top 8 List</u></a></li>
<li><a href="https://windows11.techidaily.com/a-primer-to-installation-of-the-java-sdkjdk-on-windows-11/"><u>A Primer to Installation of the Java SDK/JDK on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/amplifying-security-the-art-of-longer-pin-codes-in-win11/"><u>Amplifying Security: The Art of Longer Pin Codes in Win11</u></a></li>
<li><a href="https://blog-min.techidaily.com/android-to-apple-how-to-transfer-photos-from-motorola-moto-g23-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Android to Apple How To Transfer Photos From Motorola Moto G23 to iPad Easily | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-windows-with-top-2023-ms-store-winners/"><u>Boost Windows with Top 2023 MS Store Winners</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ing-bank-balance-crafting-commercial-video-content-for-2024/"><u>Boosting Bank Balance Crafting Commercial Video Content for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-network-analysis-on-windows-11-the-netstat-command-guide/"><u>Conquer Network Analysis on Windows 11: The Netstat Command Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-unilateral-audio-issue-on-win-os-headphones/"><u>Correcting Unilateral Audio Issue on WIN OS Headphones</u></a></li>
<li><a href="https://windows11.techidaily.com/curtailing-windows-updates-and-restarts/"><u>Curtailing Windows Updates and Restarts</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-automatic-shutdown-timer-on-windows/"><u>Disabling Automatic Shutdown Timer on Windows</u></a></li>
<li><a href="https://driver-download.techidaily.com/download-canon-pixma-mx340-printer-drivers-compatible-with-windows-11-8-and-7/"><u>Download Canon PIXMA MX340 Printer Drivers: Compatible with Windows 11, 8 & 7</u></a></li>
<li><a href="https://youtube-web.techidaily.com/tless-fusion-of-youtube-audio-with-imovie-masterpieces-for-2024/"><u>Effortless Fusion of YouTube Audio with iMovie Masterpieces for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-frp-hijacker-by-hagard-download-and-bypass-your-vivo-y78t-frp-locks-by-drfone-android/"><u>In 2024, FRP Hijacker by Hagard Download and Bypass your Vivo Y78t FRP Locks</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-uncover-sites-with-aggregated-ad-spots-on-youtube/"><u>In 2024, Uncover Sites with Aggregated Ad Spots on YouTube</u></a></li>
<li><a href="https://win-remarkable.techidaily.com/stunning-full-screen-automobile-designs-and-photos-for-desktop-and-mobile-professional-imagery-from-yl-software/"><u>Stunning Full-Screen Automobile Designs and Photos for Desktop & Mobile – Professional Imagery From YL Software</u></a></li>
</ul></div>

