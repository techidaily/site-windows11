---
title: "Cracking Cryptex: Hold On and Hesitate for Now"
date: 2024-06-25T12:19:12.863Z
updated: 2024-06-26T12:19:12.863Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Cracking Cryptex: Hold On and Hesitate for Now"
excerpt: "This Article Describes Cracking Cryptex: Hold On and Hesitate for Now"
keywords: Cracking Cipher,Secret Puzzle Solve,Decrypt Challenge,Enigma Unlock,Riddle Breaker,Hidden Code Find,Mystery Cipher Crack
thumbnail: https://thmb.techidaily.com/26dcef27c207b8605e3fcf4585ee0822110eeb8a794c85ff8e27071c7786d452.jpg
---

## Cracking Cryptex: Hold On and Hesitate for Now

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
<li><a href="https://windows11.techidaily.com/methods-to-reverse-windows-enter-input-failure/"><u>Methods to Reverse Windows Enter Input Failure</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-command-control-on-windows-with-sudo/"><u>Maximizing Command Control on Windows with Sudo</u></a></li>
<li><a href="https://windows11.techidaily.com/augmented-folder-actions-power-up-your-file-management/"><u>Augmented Folder Actions: Power Up Your File Management</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-battlenet-game-updates-in-windows/"><u>Accelerating Battle.net Game Updates in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-common-issues-with-windows-shared-printers/"><u>Solving Common Issues with Windows Shared Printers</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-your-window-preferences-on-win11/"><u>Customize Your Window Preferences on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-firewall-settings-integration-into-windows-11s-ui/"><u>Advanced Firewall Settings Integration Into Windows 11'S UI</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-absence-of-files-alert-in-windows-11/"><u>Addressing Absence of Files Alert in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/journey-to-mastery-original-diablo-basics-explained/"><u>Journey to Mastery: Original Diablo Basics Explained</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/proactive-measures-against-typical-short-video-issues/"><u>Proactive Measures Against Typical Short Video Issues</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/2024-approved-finding-the-perfect-youtube-mp3-converter-a-beginners-guide/"><u>2024 Approved Finding the Perfect YouTube MP3 Converter A Beginners Guide</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-whimsical-worlds-kids-fun-game-selection/"><u>2024 Approved  Whimsical Worlds - Kids' Fun Game Selection</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-feasting-across-borders-top-international-dishes/"><u>2024 Approved  Feasting Across Borders  Top International Dishes</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-8-essential-video-metadata-editors-for-mac-users-updated-2023/"><u>New In 2024, 8 Essential Video Metadata Editors for Mac Users (Updated 2023)</u></a></li>
<li><a href="https://extra-resources.techidaily.com/insider-strategies-free-access-to-professional-imagery/"><u>Insider Strategies  Free Access to Professional Imagery</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-ultimate-guide-for-streamlining-iphone-video-content-for-2024/"><u>The Ultimate Guide for Streamlining iPhone Video Content for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-the-comprehensive-users-manual-on-using-ez-grabber/"><u>In 2024, The Comprehensive User's Manual on Using EZ Grabber</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-pioneering-storytelling-with-insta-and-youtube-fusion/"><u>2024 Approved  Pioneering Storytelling with Insta & YouTube Fusion</u></a></li>
<li><a href="https://animation-videos.techidaily.com/2024-approved-10-best-photoshop-cartoon-effects-for-creatives/"><u>2024 Approved 10 Best Photoshop Cartoon Effects For Creatives</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>