---
title: "Breached Byte Bastion: Maintain, Reflect, Then Switch"
date: 2024-07-11T22:10:48.141Z
updated: 2024-07-12T22:10:48.141Z
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-videos.techidaily.com/enhancing-roku-experience-for-facebook-live-broadcasts-for-2024/"><u>Enhancing Roku Experience for Facebook Live Broadcasts for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/identifying-legitimate-and-false-positive-login-attempts-on-pcs/"><u>Identifying Legitimate and False-Positive Login Attempts on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/did-rav-antivirus-suddenly-appear-on-your-windows-pc-heres-where-it-came-from-and-how-to-uninstall-it/"><u>Did RAV Antivirus Suddenly Appear on Your Windows PC? Here's Where It Came From & How to Uninstall It</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-for-reestablishing-connection-with-steams-game-servers/"><u>Guidelines for Reestablishing Connection with Steam's Game Servers</u></a></li>
<li><a href="https://vp-tips.techidaily.com/lightning-fast-windowed-photo-reader-for-win11-for-2024/"><u>Lightning-Fast Windowed Photo Reader for Win11 for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-common-windo-errors-quickly/"><u>Navigating Through Common Windo Errors, Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/launching-the-driver-verifier-in-win11-os/"><u>Launching the Driver Verifier in Win11 OS</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/10-best-free-live-streaming-apps-for-android-and-iphone-for-2024/"><u>10 Best Free Live Streaming Apps for Android and iPhone for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/charting-creators-fortune-revenue-generated-from-youtube-advertisements/"><u>Charting Creator's Fortune  Revenue Generated From Youtube Advertisements?</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-recurrent-enter-to-bios-in-windows-boot-cycle/"><u>Overcoming Recurrent Enter To BIOS in Windows Boot Cycle</u></a></li>
<li><a href="https://windows11.techidaily.com/interpreting-launch-identifiers-for-applications/"><u>Interpreting Launch Identifiers for Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-and-forge-a-friendly-startup-in-windows-amidst-errors/"><u>Fix and Forge a Friendly Startup in Windows Amidst Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-prints-with-microsoft-defender-smartscreen-edge/"><u>Configuring Prints with Microsoft Defender SmartScreen Edge</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-unable-to-open-shares-on-windows-1011s-geforce/"><u>Fixing Unable to Open Shares on Windows 10/11'S GeForce</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-resolve-unreal-device-issue-in-win-11/"><u>How to Resolve Unreal Device Issue in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-internet-options-tweaks-for-windows-11/"><u>Mastery of Internet Options Tweaks for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/improve-sound-quality-top-5-free-windows-tools/"><u>Improve Sound Quality: Top 5 Free Windows Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-windows-for-wordpad-operability/"><u>Exploring Windows for WordPad Operability</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-errors-during-amd-195-installation/"><u>Eliminating Windows Errors During AMD 195 Installation</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-quicksnap-pause-and-capture-techniques/"><u>[New] In 2024, QuickSnap  Pause & Capture Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-windows-11-theme-treasures-revealed/"><u>Hidden Windows 11 Theme Treasures Revealed</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-the-experts-manual-to-efficient-screencasting/"><u>[New] In 2024, The Expert's Manual to Efficient Screencasting</u></a></li>
<li><a href="https://windows11.techidaily.com/preserving-calculator-precedence-on-windows-systems/"><u>Preserving Calculator Precedence on Windows Systems</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-the-art-of-time-manipulation-speeding-updown-videos-in-camtasia/"><u>Updated In 2024, The Art of Time Manipulation Speeding Up/Down Videos in Camtasia</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-steam-login-errors-on-windows-via-rust-coding/"><u>Eliminating Steam Login Errors on Windows via Rust Coding</u></a></li>
<li><a href="https://windows11.techidaily.com/freeze-yourself-no-more-9-techniques-for-easing-windows-install-locks/"><u>Freeze Yourself No More: 9 Techniques for Easing Windows Install Locks</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-top-4-strategies-for-success-in-instagram-loop-creation/"><u>[New] 2024 Approved  Top 4 Strategies for Success in Instagram Loop Creation</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-credentials-error-loop/"><u>Overcoming Windows Credentials Error Loop</u></a></li>
<li><a href="https://extra-resources.techidaily.com/navigating-through-the-10-leading-countdown-clock-apps-for-your-big-day-androidios/"><u>Navigating Through the 10 Leading Countdown Clock Apps for Your Big Day (Android/iOS)</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reveal-hidden-sd-card-in-file-explorer/"><u>How to Reveal Hidden SD Card in File Explorer?</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-bypass-issue-twitter-video-on-chrome-freeze/"><u>2024 Approved  Bypass Issue  Twitter Video on Chrome Freeze</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-10-fingerprint-lock-apps-to-lock-your-vivo-v27-pro-phone-by-drfone-android/"><u>In 2024, Top 10 Fingerprint Lock Apps to Lock Your Vivo V27 Pro Phone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-creative-spaces-the-hottest-discotheme-trends-for-2024/"><u>[Updated] Creative Spaces  The Hottest DiscoTheme Trends for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-chromes-erroneous-threat-detection-a-guide/"><u>Navigating Chrome's Erroneous Threat Detection: A Guide</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-evaluating-tseries-business-model-with-youtube-viewership-metrics/"><u>[Updated] Evaluating TSeries' Business Model with YouTube Viewership Metrics</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/deactivating-instagrams-igtv-feature-for-2024/"><u>Deactivating Instagram's IGTV Feature for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-and-constructive-icon-arrangement-ideas/"><u>Clear and Constructive Icon Arrangement Ideas</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-5-best-mp3-music-mixer-for-mac/"><u>2024 Approved 5 Best Mp3 Music Mixer for Mac</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-the-best-free-and-paid-imovie-alternatives-for-windows-1110-for-2024/"><u>New The Best Free and Paid iMovie Alternatives for Windows 11/10 for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/instant-clearing-the-best-ios-apps-for-precise-image-editing-for-2024/"><u>Instant Clearing  The Best iOS Apps for Precise Image Editing for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-actions-to-mend-post-windows-update-issues/"><u>Immediate Actions to Mend Post-Windows Update Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-exploration-of-windows-narrators-legacy-keys/"><u>Comprehensive Exploration of Windows Narrator's Legacy Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-reminders-in-every-window-of-your-pc/"><u>Efficient Reminders in Every Window of Your PC</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unlocking-the-potential-of-audacitys-audio-features/"><u>[New] Unlocking the Potential of Audacity's Audio Features</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-tips-install-outlook-preview-in-w10w11/"><u>Easy Tips: Install Outlook Preview in W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-error-handling-fixing-missing-updates-error-code-0x80070003/"><u>Mastering Windows Error Handling: Fixing Missing Updates (Error Code: 0X80070003)</u></a></li>
</ul></div>
