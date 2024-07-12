---
title: "Broken BitSafe Vault: Postpone the Transition"
date: 2024-07-11T22:17:39.774Z
updated: 2024-07-12T22:17:39.774Z
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://location-social.techidaily.com/in-2024-set-your-preferred-job-location-on-linkedin-app-of-your-realme-gt-neo-5-se-drfone-by-drfone-virtual-android/"><u>In 2024, Set Your Preferred Job Location on LinkedIn App of your Realme GT Neo 5 SE | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-obstacles-downloading-icloud-on-windows/"><u>Bypassing Obstacles: Downloading iCloud on Windows</u></a></li>
<li><a href="https://howto.techidaily.com/android-safe-mode-how-to-turn-off-safe-mode-on-realme-note-50-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Safe Mode - How to Turn off Safe Mode on Realme Note 50? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/amplify-windows-efficiency-with-innovative-layouts/"><u>Amplify Windows Efficiency with Innovative Layouts</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-how-to-change-video-resolution-in-filmora-for-2024/"><u>Updated How to Change Video Resolution in Filmora for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/christmas-tech-surprises-through-microsofts-marketplace/"><u>Christmas Tech Surprises Through Microsoft's Marketplace</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-illuminating-insights-for-iphone-night-photos/"><u>[Updated] Illuminating Insights for iPhone Night Photos</u></a></li>
<li><a href="https://windows11.techidaily.com/best-slate-companions-selecting-top-7-windows-tabs/"><u>Best Slate Companions: Selecting Top 7 Windows Tabs</u></a></li>
<li><a href="https://windows11.techidaily.com/asus-vs-rog-the-battle-for-the-ultimate-portable-pc/"><u>ASUS Vs. ROG: The Battle for the Ultimate Portable PC?</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-your-typing-on-win-1011-top-7-tricks-revealed/"><u>Accelerate Your Typing on WIN 10/11: Top 7 Tricks Revealed</u></a></li>
<li><a href="https://windows11.techidaily.com/adding-disk-usage-viewers-to-windows-menu-bar/"><u>Adding Disk Usage Viewers to Windows Menu Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/chrome-freezing-woes-on-win11-try-these-swift-solutions/"><u>Chrome Freezing Woes on Win11? Try These Swift Solutions.</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-non-operational-state-of-ccleaner-on-win1011-systems/"><u>Addressing Non-Operational State of CCleaner on Win10/11 Systems</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-accessing-your-curated-music-lists-on-youtube/"><u>[New] 2024 Approved  Accessing Your Curated Music Lists on Youtube</u></a></li>
<li><a href="https://windows11.techidaily.com/a-closer-look-at-windows-sound-system-segregation/"><u>A Closer Look at Windows' Sound System Segregation</u></a></li>
<li><a href="https://windows11.techidaily.com/7-key-adjustments-for-obs-studio-connection-woes-on-pcs/"><u>7 Key Adjustments for OBS Studio Connection Woes on PCs</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/easily-unlock-your-oppo-reno-9a-device-sim-by-drfone-android/"><u>Easily Unlock Your Oppo Reno 9A Device SIM</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-inside-the-high-definition-world-of-nikon-j5/"><u>[New] Inside the High-Definition World of Nikon J5</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-home-view-in-windows-11-settings/"><u>Unlock Home View in Windows 11 Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-inaccuracy-of-power-usage-predictor-on-win-11-devices/"><u>Addressing Inaccuracy of Power Usage Predictor on Win 11 Devices</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/2024-approved-create-stunning-videos-top-music-enabled-apps-for-android-and-ios/"><u>2024 Approved Create Stunning Videos Top Music-Enabled Apps for Android and iOS</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-unavailable-display-settings-in-nvidia-software/"><u>Addressing Unavailable Display Settings in Nvidia Software</u></a></li>
<li><a href="https://windows11.techidaily.com/5-steps-to-reclaim-your-windows-daylight-look/"><u>5 Steps to Reclaim Your Windows' Daylight Look</u></a></li>
<li><a href="https://windows11.techidaily.com/building-artificially-inspired-pictures-in-paint-cocreator-win11/"><u>Building Artificially-Inspired Pictures in Paint Cocreator (Win11)</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/free-youtube-endings-that-stand-out-ranked-in-2024/"><u>Free YouTube Endings That Stand Out - Ranked, In 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/adding-comprehensive-firewall-tools-to-windows-11s-menu-bar/"><u>Adding Comprehensive Firewall Tools to Windows 11’S Menu Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/circumventing-endless-credential-entry-alerts-in-windows/"><u>Circumventing Endless Credential Entry Alerts in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/amplifying-security-the-art-of-longer-pin-codes-in-win11/"><u>Amplifying Security: The Art of Longer Pin Codes in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/6-underestimated-downsides-of-saving-on-activation-keys/"><u>6 Underestimated Downsides of Saving on Activation Keys</u></a></li>
</ul></div>
