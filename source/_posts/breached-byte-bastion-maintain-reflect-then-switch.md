---
title: "Breached Byte Bastion: Maintain, Reflect, Then Switch"
date: 2024-08-15T15:22:08.533Z
updated: 2024-08-16T15:22:08.533Z
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
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
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-guffaw-generator-pictorial-mixer/"><u>[New] 2024 Approved  Guffaw Generator  Pictorial Mixer</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-beginners-path-to-screen-casting-with-apple-devices-for-2024/"><u>[New] Beginner’s Path to Screen Casting with Apple Devices for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-behind-the-scenes-mastering-screen-recordings-in-games/"><u>[New] Behind the Scenes  Mastering Screen Recordings in Games</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-effortless-webm-creation-10-best-youtube-video-transformers/"><u>[New] In 2024, Effortless WebM Creation  10 Best YouTube Video Transformers</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-free-webinar-creation-and-management-on-youtube/"><u>[New] In 2024, Free Webinar Creation & Management on Youtube</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-launch-film-studio-windows-xp-edition-essentials/"><u>[New] Launch Film Studio  Windows XP Edition Essentials</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-boost-your-channel-game-essential-video-editing-advice/"><u>[Updated] 2024 Approved  Boost Your Channel Game  Essential Video Editing Advice</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-bring-out-the-vibes-using-radial-blurs-in-your-projects/"><u>[Updated] 2024 Approved  Bring Out the Vibes  Using Radial Blurs in Your Projects</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-ethereal-solution-for-digital-realities/"><u>[Updated] 2024 Approved  Ethereal Solution for Digital Realities</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-audience-retention-the-key-to-a-great-youtube-conclusion-for-2024/"><u>[Updated] Audience Retention  The Key to a Great YouTube Conclusion for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-selecting-the-perfect-online-source-15-best-royalty-free-music-urls/"><u>[Updated] Selecting the Perfect Online Source  15 Best Royalty-Free Music URLs</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-ultimate-10plus-list-of-online-church-streaming/"><u>[Updated] The Ultimate 10+ List of Online Church Streaming</u></a></li>
<li><a href="https://windows11.techidaily.com/5-tips-for-turning-around-a-frozen-windows-hello-system/"><u>5 Tips for Turning Around a Frozen Windows Hello System</u></a></li>
<li><a href="https://android-location-track.techidaily.com/5-ways-to-track-realme-c67-5g-without-app-drfone-by-drfone-virtual-android/"><u>5 Ways to Track Realme C67 5G without App | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/automate-image-display-7-clever-strategies-for-windows-11/"><u>Automate Image Display: 7 Clever Strategies for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-charge-awareness-customizing-battery-indicators-in-win11/"><u>Boosting Charge Awareness: Customizing Battery Indicators in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/cost-effective-solutions-affordable-windows-11-key-access/"><u>Cost-Effective Solutions: Affordable Windows 11 Key Access</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-transformation-for-windows-old-to-new-drivers/"><u>Digital Transformation for Windows: Old to New Drivers</u></a></li>
<li><a href="https://unlock-android.techidaily.com/downloading-samfw-frp-tool-30-for-xiaomi-redmi-note-13-proplus-5g-by-drfone-android/"><u>Downloading SamFw FRP Tool 3.0 for Xiaomi Redmi Note 13 Pro+ 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-strategies-for-engagingdisengaging-focus-mode-in-terminal/"><u>Efficient Strategies for Engaging/Disengaging Focus Mode in Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-remote-access-stability-a-step-by-step-approach/"><u>Enhancing Remote Access Stability: A Step-by-Step Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-strategies-for-effortless-integration-of-directories-win-11/"><u>Expert Strategies for Effortless Integration of Directories, Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-a-faulty-windows-11-temporary-storage/"><u>Fixing a Faulty Windows 11 Temporary Storage</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-non-detecting-speakers-or-headphones-in-winos/"><u>Fixing Non-Detecting Speakers or Headphones in WinOS</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-download-fonts-for-all-languages-on-windows/"><u>How to Download Fonts for All Languages on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-something-went-wrong-office-error-on-windows/"><u>How to Fix the “Something Went Wrong” Office Error on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-most-common-blue-screen-errors-on-windows/"><u>How to Fix the Most Common Blue Screen Errors on Windows</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-6-plus-to-others-android-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 6 Plus To Others Android Devices? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-xiaomi-redmi-note-12-5g-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Xiaomi Redmi Note 12 5G to New Android? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-upgrade-to-virtualbox-70-on-windows-11/"><u>How to Upgrade to VirtualBox 7.0 on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-guide-forcibly-disabledelete-printer-on-pc/"><u>Immediate Guide: Forcibly Disable/Delete Printer on PC</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-fixing-video-transmission-issues-on-facebook-chat-for-iosandroid/"><u>In 2024, Fixing Video Transmission Issues on Facebook Chat for iOS/Android</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-prime-array-of-unplugged-digital-pastimes/"><u>In 2024, Prime Array of Unplugged Digital Pastimes</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unleashing-voice-commands-with-top-mac-translation-programs/"><u>In 2024, Unleashing Voice Commands with Top Mac Translation Programs</u></a></li>
<li><a href="https://buynow-info.techidaily.com/interactive-exploration-of-the-nook-lenovo-9-inch-slate-tablet/"><u>Interactive Exploration of the Nook Lenovo 9-Inch Slate Tablet</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/lilliputian-storyboard-outline-for-2024/"><u>Lilliputian Storyboard Outline for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-terminal-personalize-colors-and-style/"><u>Mastering Terminal: Personalize Colors & Style</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-work-around-microsoft-verified-app-restrictions/"><u>Methods to Work Around Microsoft-Verified App Restrictions</u></a></li>
<li><a href="https://fix-guide.techidaily.com/my-videos-arent-playing-on-oneplus-ace-2v-what-can-i-do-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>My Videos Arent Playing on OnePlus Ace 2V – What Can I Do? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-efficiently-techniques-bypassing-ls-command/"><u>Navigating Windows Efficiently: Techniques Bypassing LS Command</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-chrome-freeze-windows-edition/"><u>Overcoming Chrome Freeze: Windows Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-for-inverted-keyboard-input-windows/"><u>Quick Fix for Inverted Keyboard Input Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-invalid-temp-directories-in-windows-11/"><u>Resolving Invalid Temp Directories in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-non-existent-device-alerts-on-windows-1011/"><u>Resolving Non-Existent Device Alerts on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/simple-steps-to-enable-windows-11s-search-feature-in-task-manager/"><u>Simple Steps to Enable Windows 11'S Search Feature in Task Manager</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-recent-calls-back-from-a78-by-fonelab-android-recover-call-logs/"><u>Simple ways to get recent calls back from A78</u></a></li>
<li><a href="https://windows11.techidaily.com/sync-software-unlocking-the-fourfold-compatibility-troubleshooter/"><u>Sync Software: Unlocking the Fourfold Compatibility Troubleshooter</u></a></li>
<li><a href="https://windows11.techidaily.com/taskbar-chatting-feature-in-windows-11-user-implications/"><u>Taskbar Chatting Feature in Windows 11: User Implications</u></a></li>
<li><a href="https://windows11.techidaily.com/the-artisans-approach-to-high-dynamic-range-mastery-on-windows-11/"><u>The Artisan’s Approach to High Dynamic Range Mastery on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/turbocharging-windows-solid-state-drives-utilizing-fresh-tools/"><u>Turbocharging Windows' Solid State Drives - Utilizing Fresh Tools</u></a></li>
<li><a href="https://extra-information.techidaily.com/unraveling-the-imovie-video-edge-policy/"><u>Unraveling the iMovie Video Edge Policy</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-non-existent-mmc-snaps/"><u>Unraveling the Mystery of Non-Existent MMC Snaps</u></a></li>
<li><a href="https://windows11.techidaily.com/winrars-corrected-compression-overcoming-sum-errors/"><u>WinRAR's Corrected Compression: Overcoming Sum Errors</u></a></li>
</ul></div>
