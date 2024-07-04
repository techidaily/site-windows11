---
title: "Broken Binkey Bastion: Proceed Prudently, Not Promptly"
date: 2024-07-03T11:17:45.311Z
updated: 2024-07-04T11:17:45.311Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Broken Binkey Bastion: Proceed Prudently, Not Promptly"
excerpt: "This Article Describes Broken Binkey Bastion: Proceed Prudently, Not Promptly"
keywords: Broke Bastion Sec,Careful Bastion Gate,Prudent Bastion Path,Steady Bastion Entry,Cautionous Bastion Passage,Wise Bastion Approach,Thoughtful Bastion Opening
thumbnail: https://thmb.techidaily.com/0a8efd832e4ff850ed2946c105917f658a3e5ec7d74782a26831b6d30a49981c.jpg
---

## Broken Binkey Bastion: Proceed Prudently, Not Promptly

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
<li><a href="https://windows11.techidaily.com/addressing-why-files-cant-sync-in-steam-library/"><u>Addressing Why Files Can't Sync in Steam Library</u></a></li>
<li><a href="https://windows11.techidaily.com/1719202743817-function-failures-on-win10-quick-remedies-available/"><u>Function Failures on Win10? Quick Remedies Available</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-vibrance-to-dull-desktop-windows-effects/"><u>Restoring Vibrance to Dull Desktop Windows Effects</u></a></li>
<li><a href="https://windows11.techidaily.com/utilizing-portable-gpus-no-internal-graphic-needed/"><u>Utilizing Portable GPUs: No Internal Graphic Needed</u></a></li>
<li><a href="https://windows11.techidaily.com/revealing-the-make-of-your-windows-machine-in-six-steps/"><u>Revealing the Make of Your Windows Machine in Six Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-to-fix-error-code-0xc0000001-on-windows-pcs/"><u>Easy Steps To Fix Error Code 0XC0000001 on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/the-financial-engine-behind-windows-11/"><u>The Financial Engine Behind Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-addressing-undetectable-disks/"><u>Strategies for Addressing Undetectable Disks</u></a></li>
<li><a href="https://windows11.techidaily.com/banishing-0x800700e9-glitches-in-xbox-game-pass-on-windows-11-devices/"><u>Banishing 0X800700E9 Glitches in Xbox Game Pass on Windows 11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/experts-selection-7-best-windows-photos-apps-reviewed/"><u>Expert's Selection: 7 Best Windows Photos Apps Reviewed</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-which-video-editor-wins-filmora-or-democreator-reviewed-for-2024/"><u>[Updated] Which Video Editor Wins? Filmora or Democreator Reviewed for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/enhance-viewing-pleasure-no-more-lags/"><u>Enhance Viewing Pleasure - No More Lags</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/efficiently-archiving-mov-movies-on-windows-10-pcs-for-2024/"><u>Efficiently Archiving .mov Movies on Windows 10 PCs for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-melodic-freedom-fbs-music-library/"><u>[New] 2024 Approved  Melodic Freedom  FB's Music Library</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-top-8-best-zombie-games/"><u>[Updated] In 2024, Top 8 Best Zombie Games</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-secrets-to-successful-scrape-mass-tiktok-videos/"><u>In 2024, Secrets to Successful Scrape  Mass TikTok Videos</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-oppo-a59-5g-to-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Oppo A59 5G To Phone | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/facebook-video-orientation-dilemma-for-2024/"><u>Facebook  Video Orientation Dilemma for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-smooth-sailing-the-top-free-online-video-stabilization-software/"><u>New Smooth Sailing The Top Free Online Video Stabilization Software</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-huawei-mate-and-p-series-phones-activating-built-in-recorders-for-screen-capture/"><u>[Updated] Huawei Mate and P Series Phones  Activating Built-In Recorders for Screen Capture</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>