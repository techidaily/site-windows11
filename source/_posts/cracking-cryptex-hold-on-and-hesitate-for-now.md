---
title: "Cracking Cryptex: Hold On and Hesitate for Now"
date: 2024-08-15T15:52:37.600Z
updated: 2024-08-16T15:52:37.600Z
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

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-cutting-edge-video-meeting-techniques-on-slack-plus-filmora/"><u>[New] 2024 Approved  Cutting-Edge Video Meeting Techniques on Slack + Filmora</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-premiere-virtual-artist-streams/"><u>[New] Premiere Virtual Artist Streams</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-dividing-opinions-is-mirrorless-better-than-dslr-for-vids/"><u>[Updated] Dividing Opinions  Is Mirrorless Better than DSLR for Vids?</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-navigating-ig-videos-successfully-building-an-efficient-marketing-blueprint/"><u>[Updated] Navigating IG Videos Successfully  Building an Efficient Marketing Blueprint</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-discostreaming-101-desktop-plus-mobile-tips/"><u>2024 Approved  DiscoStreaming 101  Desktop + Mobile Tips</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-text-transformation-tactics-avoiding-3d-missteps/"><u>2024 Approved  Text Transformation Tactics  Avoiding 3D Missteps</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-the-path-to-perfect-ps3-game-footage-a-step-by-step-guide/"><u>2024 Approved  The Path to Perfect PS3 Game Footage  A Step-by-Step Guide</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-ultimate-selection-of-androids-most-innovative-music-videography-tools/"><u>2024 Approved  The Ultimate Selection of Android's Most Innovative Music Videography Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-storage-efficiency-tools-for-pcs/"><u>Activating Storage Efficiency Tools for PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/ai-horizons-redefining-windows-11-paradigms/"><u>AI Horizons: Redefining Windows 11 Paradigms</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-security-in-virtualbox-via-secure-boot-toggle/"><u>Boost Security in VirtualBox via Secure Boot Toggle</u></a></li>
<li><a href="https://windows11.techidaily.com/command-prompt-curiosities-5-fun-filled-functions/"><u>Command Prompt Curiosities: 5 Fun-Filled Functions</u></a></li>
<li><a href="https://windows11.techidaily.com/control-and-discretion-over-network-safety-in-windows/"><u>Control and Discretion Over Network Safety in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-navigation-disabling-accelerated-motion-windows-style/"><u>Efficient Navigation: Disabling Accelerated Motion Windows Style</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-strategies-to-tackle-office-errors-a-winos-approach/"><u>Efficient Strategies to Tackle Office Errors: A WinOS Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-workflow-microsoft-adds-an-ai-powered-assistant-to-the-windows-11-taskbar/"><u>Effortless Workflow: Microsoft Adds an AI-Powered Assistant to the Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-your-win11-experience-learn-to-edit-faxes-easily/"><u>Enhancing Your Win11 Experience: Learn to Edit Faxes Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-activate-and-control-fast-boot-in-your-windows-11-pc/"><u>How to Activate and Control Fast Boot in Your Windows 11 PC</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-iphone-xs-stuck-at-attempting-data-recovery-loop-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Fix iPhone XS Stuck at attempting data recovery Loop | Stellar</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-resource-monitor-app-when-its-not-working-on-windows-11/"><u>How to Fix the Resource Monitor App When It's Not Working on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-mend-screen-driver-problems-in-windows-11/"><u>How to Mend Screen Driver Problems in Windows 11</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-motorola-moto-g14-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Motorola Moto G14 Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/immersive-entertainment-showdown-google-cardboard-and-samsung-gear-for-2024/"><u>Immersive Entertainment Showdown  Google Cardboard & Samsung Gear for 2024</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-locked-for-security-reasons-from-apple-iphone-11-pro-find-the-best-solution-here-by-drfone-ios/"><u>In 2024, Apple ID Locked for Security Reasons From Apple iPhone 11 Pro? Find the Best Solution Here</u></a></li>
<li><a href="https://windows11.techidaily.com/insider-knowledge-on-folder-tagsging-in-windows-explorer/"><u>Insider Knowledge on Folder Tagsging in Windows Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-windows-accessibility-hub-in-5-simple-steps/"><u>Master the Windows Accessibility Hub - In 5 Simple Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-desktop-trash-for-permanent-deletion-on-windows-oses/"><u>Mastering Desktop Trash for Permanent Deletion on Windows OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-post-sleep-device-awareness-procedures/"><u>Mastering Post-Sleep Device Awareness Procedures</u></a></li>
<li><a href="https://extra-hints.techidaily.com/mastering-vr-travel-a-step-by-step-guide/"><u>Mastering VR Travel  A Step-by-Step Guide</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/maximizing-fun-downloading-fb-status-video/"><u>Maximizing Fun  Downloading FB Status Video</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-past-windows-update-roadblocks-effortlessly/"><u>Navigate Past Windows Update Roadblocks Effortlessly</u></a></li>
<li><a href="https://fox-that.techidaily.com/navigating-the-pitfalls-how-to-overcome-ios-gift-sending-hurdles/"><u>Navigating the Pitfalls: How to Overcome iOS Gift Sending Hurdles</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-tracking-down-your-software-install-pathways-in-windows/"><u>Quick Guide: Tracking Down Your Software' Install Pathways in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/quickly-prep-your-pc-with-win-11-via-these-3-usb-steps/"><u>Quickly Prep Your PC with Win 11 via These 3 USB Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/regaining-access-to-lost-steam-contact-list-win11/"><u>Regaining Access to Lost Steam Contact List (Win11)</u></a></li>
<li><a href="https://windows11.techidaily.com/remedies-for-no-light-gameplay-experience-on-windows/"><u>Remedies for No-Light Gameplay Experience on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resurrecting-taskbar-notification-banners/"><u>Resurrecting Taskbar Notification Banners</u></a></li>
<li><a href="https://tech-haven.techidaily.com/safer-chatgpt-experiences-for-children-embracing-five-security-measures/"><u>Safer ChatGPT Experiences for Children: Embracing Five Security Measures</u></a></li>
<li><a href="https://windows11.techidaily.com/solution-for-fixing-the-invalid-file-history-options-in-windows/"><u>Solution for Fixing the Invalid File History Options in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-revive-slow-running-asana-on-windows/"><u>Solutions to Revive Slow-Running Asana on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-unlock-windows-credentials-management/"><u>Steps to Unlock Windows Credentials Management</u></a></li>
<li><a href="https://windows11.techidaily.com/strategic-application-of-ping-for-optimal-pc-performance/"><u>Strategic Application of Ping for Optimal PC Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/top-8-windows-11-no-nos-common-pitfalls-to-skip/"><u>Top 8 Windows 11 No-Nos: Common Pitfalls to Skip</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-imei-unlokers-for-your-lava-yuva-3-pro-phone-by-drfone-android/"><u>Top IMEI Unlokers for Your Lava Yuva 3 Pro Phone</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-unexpected-security-alerts/"><u>Troubleshooting Windows' Unexpected Security Alerts</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-and-remedying-chromes-profile-anomalies/"><u>Unraveling and Remedying Chrome's Profile Anomalies</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-strategies-how-to-resolve-unison-issues-on-win11/"><u>Winning Strategies: How To Resolve Unison Issues on Win11</u></a></li>
</ul></div>
