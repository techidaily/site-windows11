---
title: "Cracking Cryptex: Hold On and Hesitate for Now"
date: 2024-07-11T21:39:02.806Z
updated: 2024-07-12T21:39:02.806Z
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/streamlining-microphone-setup-with-the-latest-windows-11-features/"><u>Streamlining Microphone Setup with the Latest Windows 11 Features</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-top-15-video-capture-for-gamers-guide/"><u>[Updated] Top 15 Video Capture for Gamers Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/time-is-money-restoring-windows-server-time-quickly/"><u>Time Is Money: Restoring Windows Server Time Quickly</u></a></li>
<li><a href="https://android-frp.techidaily.com/top-5-oppo-find-n3-flip-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Oppo Find N3 Flip Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://windows11.techidaily.com/what-does-s-mode-mean-in-the-world-of-windows-11-updates/"><u>What Does 'S Mode' Mean in the World of Windows 11 Updates?</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-unlock-accessibility-adding-subtitles-and-captions-in-final-cut-pro-x/"><u>Updated Unlock Accessibility Adding Subtitles and Captions in Final Cut Pro X</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-from-meta-to-omni-a-new-age-digital-odyssey-guide/"><u>In 2024, From Meta to Omni  A New Age Digital Odyssey Guide</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-6-social-media-outlets-boosting-business-revenue-for-2024/"><u>Top 6 Social Media Outlets Boosting Business Revenue for 2024</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-in-2024-master-the-art-of-costless-sound-transformation-and-advanced-audio-editing-in-filmora-videos/"><u>Updated In 2024, Master the Art of Costless Sound Transformation and Advanced Audio Editing in Filmora Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/7-essential-steps-to-resolve-chrome-profile-errors/"><u>7 Essential Steps to Resolve Chrome Profile Errors</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-money-making-moves-now-with-over-500-subscribers/"><u>In 2024, Money-Making Moves  Now With Over 500 Subscribers</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-restoring-bluetooth-visibility-win/"><u>Steps for Restoring Bluetooth Visibility WIN</u></a></li>
<li><a href="https://windows11.techidaily.com/taskers-curiosity-non-edge-process-puzzles/"><u>Tasker's Curiosity: Non-Edge Process Puzzles</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-creativity-windows-outlook-calendar-personalization-guide/"><u>Unleash Creativity: Windows Outlook Calendar Personalization Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-alt-key-code-issues-in-windows-systems/"><u>Solving ALT Key Code Issues in Windows Systems</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-use-ispoofer-on-honor-x50-drfone-by-drfone-virtual-android/"><u>In 2024, How to use iSpoofer on Honor X50? | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/imovie-basics-for-new-users-how-to-seamlessly-add-sounds-and-music-for-2024/"><u>IMovie Basics for New Users How to Seamlessly Add Sounds and Music for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-to-stop-fluctuating-printer-choices-on-pc/"><u>Tactics to Stop Fluctuating Printer Choices on PC</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-maximizing-video-quality-mastering-insta-to-mp4-conversion/"><u>2024 Approved  Maximizing Video Quality  Mastering Insta-to-MP4 Conversion</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-install-non-verified-windows-applications/"><u>Steps to Install Non-Verified Windows Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-microsoft-store-crash-error-0x800704cf/"><u>Tackling Microsoft Store Crash: Error 0X800704CF</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-oneplus-nord-ce-3-lite-5g-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset OnePlus Nord CE 3 Lite 5G phone? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-the-terminal-workflow-setting-it-as-main/"><u>Transforming the Terminal Workflow: Setting It As Main</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-venturing-through-tiktoks-anime-landscape-choreographies-melodic-intrigues-and-visual-delights-for-2024/"><u>[Updated] Venturing Through TikTok’s Anime Landscape  Choreographies, Melodic Intrigues and Visual Delights for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unwinding-windows-11s-0x8004def5-onedrive-snags/"><u>Unwinding Windows 11'S 0X8004DEF5 Onedrive Snags</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/can-i-bypass-a-forgotten-phone-password-of-nokia-c110-by-drfone-android/"><u>Can I Bypass a Forgotten Phone Password Of Nokia C110?</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/web-development-hacks-embedding-youtubes-playlists-effortlessly-for-2024/"><u>Web Development Hacks  Embedding YouTube's Playlists Effortlessly for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/alleviating-overuse-of-wmi-in-windows-installer/"><u>Alleviating Overuse of WMI in Windows Installer</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-at-win-11-games-easy-steps-for-enhancing-fun-and-performance/"><u>Winning at Win 11 Games: Easy Steps for Enhancing Fun and Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-at-world-of-warcraft-defy-error-132/"><u>Winning at World of Warcraft: Defy Error #132</u></a></li>
<li><a href="https://windows11.techidaily.com/top-techniques-to-quell-input-delay-on-windows-11/"><u>Top Techniques to Quell Input Delay on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-updating-windows-cards-a-comprehensive-guide/"><u>Swiftly Updating Windows Cards: A Comprehensive Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-overhaul-pretend-its-windows-98-edition/"><u>Windows Overhaul: Pretend It's Windows 98 Edition</u></a></li>
<li><a href="https://extra-tips.techidaily.com/top-editors-for-action-cam-footage/"><u>Top Editors for Action Cam Footage</u></a></li>
<li><a href="https://windows11.techidaily.com/best-approaches-to-regulate-device-connections-in-windows/"><u>Best Approaches to Regulate Device Connections in Windows</u></a></li>
</ul></div>
