---
title: "Cracked Codekeepers: Stay Secure in the Now"
date: 2024-07-11T22:25:06.734Z
updated: 2024-07-12T22:25:06.734Z
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
<li><a href="https://sim-unlock.techidaily.com/tutorial-to-change-oppo-reno-11f-5g-imei-without-root-a-comprehensive-guide-by-drfone-android/"><u>Tutorial to Change Oppo Reno 11F 5G IMEI without Root A Comprehensive Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-the-advantages-of-microsofts-copilot-key-for-windows-11/"><u>Demystifying the Advantages of Microsoft's Copilot Key for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/diagnosing-partially-functioning-windows-earphones/"><u>Diagnosing Partially Functioning Windows Earphones</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-rectifying-the-pink-screen-dilemma/"><u>Decoding and Rectifying the Pink Screen Dilemma</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/pokemon-go-no-gps-signal-heres-every-possible-solution-on-tecno-spark-10-4g-drfone-by-drfone-virtual-android/"><u>Pokemon Go No GPS Signal? Heres Every Possible Solution On Tecno Spark 10 4G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-what-windows-11s-new-updates-signify-for-users/"><u>Delving Into What Windows 11'S New Updates Signify For Users</u></a></li>
<li><a href="https://windows11.techidaily.com/dazzling-holiday-windows-a-celebration-of-joy-and-light/"><u>Dazzling Holiday Windows: A Celebration of Joy & Light</u></a></li>
<li><a href="https://windows11.techidaily.com/compact-guide-best-windows-forecasting-tools/"><u>Compact Guide: Best Windows Forecasting Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-words-best-writing-software-for-windows-users/"><u>Conquer Words: Best Writing Software for Windows Users</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-refine-your-remote-sessions-zoom-in-effectively/"><u>[Updated] Refine Your Remote Sessions  Zoom in Effectively</u></a></li>
<li><a href="https://fix-guide.techidaily.com/stuck-at-android-system-recovery-of-nokia-c22-fix-it-easily-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Stuck at Android System Recovery Of Nokia C22 ? Fix It Easily | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-an-efficient-menu-choice-for-regular-system-checks-on-win11plus11/"><u>Crafting an Efficient Menu Choice for Regular System Checks on Win11+11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unlock-optimal-performance-with-these-key-tricks/"><u>In 2024, Unlock Optimal Performance with These Key Tricks</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-perfect-your-titling-skills-with-our-best-practices/"><u>[New] Perfect Your Titling Skills with Our Best Practices</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-harnessing-hashtags-for-hitting-video-hotspots-on-fb/"><u>2024 Approved  Harnessing Hashtags for Hitting Video Hotspots on FB</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/mastering-social-media-fame-on-instagram-for-2024/"><u>Mastering Social Media Fame on Instagram for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/cleanse-your-screen-history-3-strategies/"><u>Cleanse Your Screen History - 3 Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/decrease-resource-load-managing-news-app-consumption/"><u>Decrease Resource Load: Managing News App Consumption</u></a></li>
<li><a href="https://extra-hints.techidaily.com/full-review-for-hero4-black/"><u>Full Review for Hero4 Black</u></a></li>
<li><a href="https://howto.techidaily.com/want-to-uninstall-google-play-service-from-infinix-hot-30i-here-is-how-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Want to Uninstall Google Play Service from Infinix Hot 30i? Here is How | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-ways-to-trade-pokemon-go-from-far-away-on-honor-play-8t-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to trade pokemon go from far away On Honor Play 8T? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/defensive-operations-mastering-windows-unauthorized-prevention/"><u>Defensive Operations: Mastering Windows Unauthorized Prevention</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-parsing-setback-code-0xc00ce556/"><u>Conquering Parsing Setback: Code 0xC00CE556</u></a></li>
<li><a href="https://windows11.techidaily.com/command-your-way-through-windows-11-nircmd-tips-and-tricks/"><u>Command Your Way Through Windows 11: NirCmd Tips & Tricks</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-android-unlock-code-sim-unlock-your-infinix-note-30-phone-and-remove-locked-screen-by-drfone-android/"><u>In 2024, Android Unlock Code Sim Unlock Your Infinix Note 30 Phone and Remove Locked Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-the-past-updating-decrepit-windows-cards/"><u>Clearing the Past: Updating Decrepit Windows Cards</u></a></li>
<li><a href="https://location-fake.techidaily.com/8-solutions-to-fix-find-my-friends-location-not-available-on-realme-v30t-drfone-by-drfone-virtual-android/"><u>8 Solutions to Fix Find My Friends Location Not Available On Realme V30T | Dr.fone</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-discover-the-best-top-10-intro-maker-websites-for-creators/"><u>New 2024 Approved Discover the Best Top 10 Intro Maker Websites for Creators</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-file-damage-enigma-winning-over-error-0x80070570-on-windows-11/"><u>Deciphering the File Damage Enigma - Winning Over Error 0X80070570 on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-drives-c-vs-d-explanation/"><u>Deciphering Drives: C: Vs D: Explanation</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-graphics-output-dpi-adjustment-guide/"><u>Customizing Graphics Output: DPI Adjustment Guide</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-tick-tock-tally-calculating-pewdiepies-cash/"><u>In 2024, Tick-Tock Tally  Calculating PewDiePie’s Cash</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-filehistoryfaults-in-windows-os/"><u>Dealing with FileHistoryFaults in Windows OS</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-in-2024-how-to-add-selective-color-effect-to-your-videos/"><u>New In 2024, How to Add Selective Color Effect to Your Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-dilemma-deciphered-7-strategies-to-reopen-browsers-in-win-os/"><u>Digital Dilemma Deciphered: 7 Strategies to Reopen Browsers in WIN OS</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>