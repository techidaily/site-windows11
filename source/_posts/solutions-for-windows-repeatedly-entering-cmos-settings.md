---
title: Solutions for Windows Repeatedly Entering CMOS Settings
date: 2025-02-08T00:42:48.574Z
updated: 2025-02-11T07:31:38.927Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solutions for Windows Repeatedly Entering CMOS Settings
excerpt: This Article Describes Solutions for Windows Repeatedly Entering CMOS Settings
keywords: CMOS Update Guide,WinSettings Reset Tips,BIOS Troubleshooting Steps,CMOS Conflict Solutions,Repeated CMOS Issue Fixes,Windows Boot Modes Adjustment,Erratic CMOS Settings Recovery
thumbnail: https://thmb.techidaily.com/9416939e5407a18ea81200cd7e119e61ff04e31fb3c5cd004cd4601ad28e3eb8.jpg
---

## Solutions for Windows Repeatedly Entering CMOS Settings

 Does your Windows device keep booting to BIOS every time you restart it? Numerous factors could be responsible for this, such as having the boot key pressed on the keyboard, running outdated BIOS, improperly plugged-in operating system drive, misconfigured boot sequence, or a CMOS battery issue.

 If you have trouble booting the operating system repeatedly and want your device to boot to Windows rather than BIOS, here are a few checks and fixes you can apply.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aqeO4ed766s?si=AWtKHxP4hvQRd_lk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Disconnect Peripherals and Discharge Static Charge

 Disconnecting the peripherals and discharging the static charge has fixed the issue under discussion for some users. Therefore, before you proceed with any other fixes, unplug all peripherals from your device, and press the power button for half a minute to discharge static electricity. After that, reboot your device. If it boots back into BIOS, begin applying the remaining fixes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S0b9szh8vEk?si=NlGzpJ6MN_SJNk5A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Perform a Quick Restart From the BIOS

 Although it sounds pretty simple, restarting the computer after saving BIOS settings usually boots a device into Windows, which may help bypass the issue. Therefore, once your device boots into BIOS, do not make any changes; save the changes and exit BIOS. Afterward, your device may restart once and boot directly into Windows this time.

 Even if this workaround works, it isn't a permanent fix, as you will need to restart Windows through BIOS every time you turn it on, which can be annoying. Continue applying the remaining fixes for a permanent solution.

## 3\. Ensure That the Boot Key Isn't Pressed Down

 Booting into BIOS requires users to press a specific key on the keyboard, which is different for nearly every Windows laptop manufacturer. If you're unfamiliar with it, our guide on [how to enter the BIOS](https://www.makeuseof.com/tag/enter-bios-computer/) covers the correct key to enter BIOS on laptops from different manufacturers.

![HyperX Alloy Origins Core Function Keys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/02/Alloy-Origins-Core-HyperX-Function-Keys.jpg)

 When this button is pressed, Windows will boot into BIOS instead of the operating system following a turn-on. So, if your device is automatically booting into BIOS, it is possible that this key got stuck while pressed down on the keyboard, telling your PC to boot into BIOS.

 Therefore, make sure the boot key on your keyboard isn't pressed. If there are any dust particles on it, wipe them off and press the key several times to ensure nothing is stuck.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8Y-k_3N-0OI?si=1J-aFBXLJl5b3x4h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Ensure the Drive Containing the Operating System Is Plugged In

 Your device can also boot into BIOS if it does not find a bootable drive containing your operating system. Typically, it happens when your PC's hard drive disconnects or is no longer detected by your device due to a hardware issue.

 Thus, you must ensure that your drive is connected and detectable by your system and that it isn't causing your device to boot into BIOS. Since the BIOS interfaces of most laptops differ between manufacturers, the process to check that varies.

 Users facing this issue on a Dell device should navigate to the **System Information** tab in BIOS and look under **Device Information**.

![Checking the Device Information in BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/checking-the-device-information-in-bios-1.jpg)

 If you don't see the drive with your OS installed, ensure it's connected properly. If your drive is connected but not detectable by your device, you should have it inspected to see if there is a hardware problem. However, if the drive containing your operating system is listed there, move on to the next step.

## 5\. Check Your Boot Sequence

 Boot sequence refers to the order in which your device searches for bootable data. It's recommended to keep the device containing your OS at the top of the sequence, especially if you have multiple storage devices connected. With this, your device can quickly find the bootable data and boot your operating system.

 If the drive containing your OS appears connected in the previous step, ensure it comes first in the boot sequence. To check that on a Dell device, select **Boot Sequence** from the left sidebar. After that, choose **Legacy** under **Boot List Option** and make sure your desired drive appears first in the **Boot Sequence**.

![Changing the Boot Mode in BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/changing-the-boot-mode-in-bios.jpg)

 If it isn't selected, click on the **arrow button** and move the drive containing your operating system to the top.

![Putting the Drive Containing the OS at Top in Boot Sequence in BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/putting-the-drive-containing-the-os-at-top-in-boot-sequence-in-bios.jpg)

## 6\. Disable Fast Startup

 The Fast Startup feature in Windows hibernates the system and loads the files quicker. In a nutshell, it helps Windows boot faster. Even though it saves users a lot of time and helps them get back to work quickly, it is known to cause annoying issues during bootup. Often, disabling this feature fixes most of these problems.

 If you can boot into Windows from BIOS, our guide on [turning Fast Startup on and off](https://www.makeuseof.com/windows-11-turn-on-or-off-fast-startup/) can help you disable this feature. However, if you are stuck at the BIOS screen and cannot boot into Windows, you can also disable Fast Startup from there. For that, go to your laptop manufacturer's website for instructions on turning off Fast Startup from BIOS.

## 7\. Update the BIOS

 An outdated BIOS can also prevent Windows from booting correctly. It's the most neglected cause of most booting problems. Therefore, to ensure that the issue under discussion is not caused due to an outdated BIOS, you should upgrade it to the latest version.

 So, if you are able to boot to Windows from BIOS but again encounter the issue when restarting, refer to our guide on [how to update your UEFI BIOS in Windows](https://www.makeuseof.com/tag/update-uefi-bios-windows/). If you cannot boot to Windows, you will have to resort to other methods of updating BIOS.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fvAC8jgs62o?si=xqEXZ7dpAXZ4sZ7A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 8\. Replace or Reinsert the CMOS Battery

![Person tampering with a motherboard.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/cmos-battery-explained-featured.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The CMOS battery powers the BIOS firmware on the laptop. If you are unable to boot to Windows, a dead CMOS battery could also be to blame. Often, just removing and reinserting the battery fixes the issue; however, it resets a few settings, including the date and time. In case of a dead battery, you may need to replace it.

 If you want to know more about the CMOS battery and how to remove it, refer to our guide on [what a CMOS battery is](https://www.makeuseof.com/what-is-a-cmos-battery-and-how-do-you-remove-one/).

## Don’t Let Your Windows PC Boot to BIOS

 Seeing your device boot directly into BIOS rather than Windows can be extremely frustrating. We hope the above fixes will help you successfully resolve the issue and boot to Windows. If the above fixes don't work, repair or reinstall Windows. If that doesn't work either, the laptop could have a hardware problem, so take it to a technician for inspection.

 If you have trouble booting the operating system repeatedly and want your device to boot to Windows rather than BIOS, here are a few checks and fixes you can apply.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://eaxpv-info.techidaily.com/new-foundations-first-what-to-invest-in-for-youtubing-for-2024/"><u>[New] Foundations First What To Invest In for YouTubing for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ow-to-confirm-your-youtube-account-securely-in-2024/"><u>[New] How to Confirm Your YouTube Account Securely, In 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-acoustic-architects-building-with-mac-studios/"><u>[Updated] 2024 Approved Acoustic Architects Building with Mac Studios</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-legal-implications-and-tips-when-archiving-whatsapp-call-recordings/"><u>[Updated] In 2024, Legal Implications & Tips When Archiving WhatsApp Call Recordings</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-precision-settings-for-obs-studio-on-android/"><u>[Updated] Precision Settings for OBS Studio on Android</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensible-approach-to-fixing-notepad-non-openness-in-windows/"><u>A Comprehensible Approach to Fixing Notepad Non-Openness in Windows</u></a></li>
<li><a href="https://tech-hub.techidaily.com/ensuring-child-safety-with-chatgpt-discover-5-effective-methods/"><u>Ensuring Child Safety with ChatGPT: Discover 5 Effective Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/1719261046850-experience-gptclone-at-home-for-free-on-windows/"><u>Experience GPTClone at Home for FREE on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-performance-with-5-wsl-2-enhancements/"><u>Maximizing Performance with 5 WSL 2 Enhancements</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-cut-and-split-mpeg-videos-with-these-5-free-software-options-for-2024/"><u>New Cut and Split MPEG Videos with These 5 Free Software Options for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-read-only-status-in-1011s-file-directories/"><u>Remedying Read-Only Status in 10/11'S File Directories</u></a></li>
<li><a href="https://review-topics.techidaily.com/smart-yale-protection-gateway-perfectly-engineered-security-locks-for-urban-living-spaces/"><u>Smart Yale Protection Gateway - Perfectly Engineered Security Locks for Urban Living Spaces</u></a></li>
<li><a href="https://windows11.techidaily.com/starting-windows-terminal-with-quake-effects/"><u>Starting Windows Terminal with Quake Effects</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlined-startup-routines-in-modern-windows/"><u>Streamlined Startup Routines in Modern Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/surface-go-3-with-latest-chip-reviewed-mixed-outcomes-noted/"><u>Surface Go 3 with Latest Chip Reviewed: Mixed Outcomes Noted</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-windows-11s-compatibility-checker-usage-guide/"><u>Understanding Windows 11'S Compatibility Checker: Usage Guide</u></a></li>
<li><a href="https://discover-hacks.techidaily.com/1728484646586-windows-1011/"><u>Windows 10/11におけるデフォルトのダウンロードファイル消滅 - 解決策と復元手順</u></a></li>
</ul></div>

