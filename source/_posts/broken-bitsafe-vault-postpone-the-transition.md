---
title: "Broken BitSafe Vault: Postpone the Transition"
date: 2024-08-15T15:15:25.404Z
updated: 2024-08-16T15:15:25.404Z
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

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-capturing-ps4-gaming-magic-in-full-detail-using-obs/"><u>[New] 2024 Approved  Capturing PS4 Gaming Magic in Full Detail Using OBS</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-dissecting-youtubes-activities-post-uploading-videos/"><u>[New] 2024 Approved  Dissecting YouTube's Activities Post-Uploading Videos</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-fascination-on-screen-top-6-engaging-video-categories-for-2024/"><u>[New] Fascination on Screen  Top 6 Engaging Video Categories for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-captureclub-bout/"><u>[New] In 2024, CaptureClub Bout</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-in-2024-mastering-your-syma-x8c-flight-patterns/"><u>[New] In 2024, Mastering Your Syma X8C Flight Patterns</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-quickshot-screen-grab-reviews/"><u>[New] In 2024, QuickShot Screen Grab Reviews</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-mastering-the-art-of-online-marketing-for-newcomers/"><u>[New] Mastering the Art of Online Marketing for Newcomers</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unleashing-hidden-features-funimate-guide/"><u>[New] Unleashing Hidden Features - Funimate Guide</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-effortless-snaptweet-videos-from-twitter-for-2024/"><u>[Updated] Effortless SnapTweet Videos From Twitter for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-free-range-humor-development-unleash-your-wit/"><u>[Updated] Free-Range Humor Development  Unleash Your Wit</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-mastering-wide-angle-postings-integrating-360-photos-on-mobile-apps/"><u>[Updated] In 2024, Mastering Wide Angle Postings  Integrating 360 Photos on Mobile Apps</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-pro-tools-for-non-pro-youtubers/"><u>[Updated] In 2024, Pro Tools for Non-Pro YouTubers</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-top-picks-of-screen-recording-applications-for-modern-windows-users-for-2024/"><u>[Updated] Top Picks of Screen Recording Applications for Modern Windows Users for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/2-ways-to-monitor-asus-rog-phone-8-pro-activity-drfone-by-drfone-virtual-android/"><u>2 Ways to Monitor Asus ROG Phone 8 Pro Activity | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-crafty-concepts-designing-unforgettable-instagram-puzzle-feeds/"><u>2024 Approved  Crafty Concepts  Designing Unforgettable Instagram Puzzle Feeds</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-cutting-edge-mounts-uninterrupted-mobile-shooting/"><u>2024 Approved  Cutting-Edge Mounts  Uninterrupted Mobile Shooting</u></a></li>
<li><a href="https://tech-hub.techidaily.com/6-free-artificial-intelligence-services-similar-to-sora/"><u>6 Free Artificial Intelligence Services Similar to Sora</u></a></li>
<li><a href="https://win-blog.techidaily.com/comprehensive-solutions-to-cut-down-discords-hefty-cpu-usage-in-todays-tech-landscape/"><u>Comprehensive Solutions to Cut Down Discord's Hefty CPU Usage in Today’s Tech Landscape</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/dissecting-dji-flyer-x20-fpv-headset-capabilities/"><u>Dissecting DJi Flyer X20 FPV Headset Capabilities</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/expert-ff-video-extractor-kit-efficient-file-grabbing-firefox-compatibility/"><u>Expert FF Video Extractor Kit  Efficient File Grabbing, Firefox Compatibility</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-microsoft-store-error-0x80072efd-on-pcs/"><u>Fixing Microsoft Store Error 0X80072EFD on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-overcoming-java-installation-errors-on-pc/"><u>Guide to Overcoming Java Installation Errors on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-to-correct-err-87-on-windows-loadlib/"><u>Guidelines to Correct Err 87 on Windows LoadLib</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-maintain-notebook-visibility-on-win-1011/"><u>How to Maintain Notebook Visibility on Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-return-to-original-windows-setup-settings/"><u>How to Return to Original Windows Setup Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/improving-system-performance-by-curbing-browser-activity/"><u>Improving System Performance by Curbing Browser Activity</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-about-infinix-hot-40-frp-bypass-by-drfone-android/"><u>In 2024, About Infinix Hot 40 FRP Bypass</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-remove-a-previously-synced-google-account-from-your-nokia-c22-by-drfone-android/"><u>In 2024, How to Remove a Previously Synced Google Account from Your Nokia C22</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-oneplus-11r-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>In 2024, How to Unlock OnePlus 11R Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-secrets-unlocked-becoming-a-leader-in-online-social-media-live-events/"><u>In 2024, Secrets Unlocked  Becoming a Leader in Online Social Media Live Events</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-unlock-oneplus-nord-n30-5g-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>In 2024, Unlock OnePlus Nord N30 5G Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-unlocking-potential-metaverse-marketing-secrets/"><u>In 2024, Unlocking Potential  Metaverse Marketing Secrets</u></a></li>
<li><a href="https://windows11.techidaily.com/launch-successfully-guiding-through-startup-services-in-windows-11/"><u>Launch Successfully: Guiding Through Startup Services in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/maintain-full-size-icons-on-your-windows-11-machine/"><u>Maintain Full-Size Icons on Your Windows 11 Machine</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-wake-on-lid-closure-in-windows-devices/"><u>Mastering Wake on Lid Closure in Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-command-execution-setting-terminal-preference/"><u>Optimize Command Execution: Setting Terminal Preference</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-slow-download-issues-with-ease-win/"><u>Overcoming Slow Download Issues with Ease (Win)</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-speakers-unresponsiveness/"><u>Overcoming Windows Speakers Unresponsiveness</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-for-disabling-audio-playback-errors/"><u>Quick Fix for Disabling Audio Playback Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-update-breakdown-overcoming-error-0x80246007-on-win11/"><u>Resolving Update Breakdown: Overcoming Error 0X80246007 on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/safeguarding-your-os-managing-usb-device-use/"><u>Safeguarding Your OS: Managing USB Device Use</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-your-wi-fi-blocking-networks-on-windows-pc/"><u>Secure Your Wi-Fi: Blocking Networks on Windows PC</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/simplified-methods-for-google-meet-recordings/"><u>Simplified Methods for Google Meet Recordings</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-restore-active-window-defense-system/"><u>Strategies to Restore Active Window Defense System</u></a></li>
<li><a href="https://windows11.techidaily.com/success-tips-reviving-your-intel-unison-app/"><u>Success Tips: Reviving Your Intel Unison App</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-reinstate-lost-mcuicnt-file-in-windows/"><u>Techniques to Reinstate Lost McUICnt File in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-path-to-a-fortified-pc-with-windows-11-and-tpmsecure-boot/"><u>The Path to a Fortified PC with Windows 11 & TPM/Secure Boot</u></a></li>
<li><a href="https://windows11.techidaily.com/the-rotation-rulebook-six-secrets-to-snap-spins-in-windows-11/"><u>The Rotation Rulebook: Six Secrets to Snap-Spins in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-switching-offon-windows-11s-smartscreen/"><u>Tips for Switching Off/On Windows 11'S SmartScreen</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-blackwhite-windows-store-errors/"><u>Troubleshooting Black/White Windows Store Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/turbo-steam-downloads-overcoming-frustrating-speed-halts/"><u>Turbo Steam Downloads: Overcoming Frustrating Speed Halts</u></a></li>
<li><a href="https://windows11.techidaily.com/turbo-type-tips-quick-key-input-enhancements-for-win-1011/"><u>Turbo-Type Tips: Quick Key Input Enhancements for Win 10/11</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-gionee-f3-pro-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Location is Not Updating and How to Fix On Gionee F3 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-5ghz-wi-fi-connection-woes-how-to-solve-them/"><u>Win11 5GHz Wi-Fi Connection Woes: How to Solve Them</u></a></li>
<li><a href="https://network-issues.techidaily.com/windows-10-amd-failure-loaded-driver-issue-resolved/"><u>Windows 10, AMD Failure: Loaded Driver Issue Resolved</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-widgets-configuration-the-triad-approach/"><u>Windows 11 Widgets Configuration: The Triad Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-photos-clever-trick-for-image-renewal/"><u>Windows Photos' Clever Trick for Image Renewal</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-woos-resolve-opera-download-hitch/"><u>Windows Woos: Resolve Opera Download Hitch</u></a></li>
<li><a href="https://windows11.techidaily.com/winfix-guide-reviving-dormant-wsreset-service-process/"><u>Winfix Guide: Reviving Dormant WSReset Service Process</u></a></li>
</ul></div>
