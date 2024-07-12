---
title: Overcoming No Audio Capture in OBS on Windows 11 PCs
date: 2024-07-11T21:53:11.643Z
updated: 2024-07-12T21:53:11.643Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming No Audio Capture in OBS on Windows 11 PCs
excerpt: This Article Describes Overcoming No Audio Capture in OBS on Windows 11 PCs
keywords: WinOBSNoAudioSolution,FixAudioCaptureWindows11,OBSAudioIssueResolution,NoAudioOBSSupport,CapturingSoundWinPCs,WindowsOSSBroadcastAudio,RemedyOBSAudioError
thumbnail: https://thmb.techidaily.com/d44947af2d23263a61b2bb19233d3717a7fd178394378301c673d9cd094e466a.jpg
---

## Overcoming No Audio Capture in OBS on Windows 11 PCs

 OBS Studio is a free-to-use app that allows you to record gameplay and stream online. However, like any other application, it has its own share of flaws. Many users have reported that OBS Studio fails to record audio on their Windows 11 PC.

 Luckily, it's a very common issue and can quickly be resolved. Here are all the working solutions that will help you fix OBS Studio if it is unable to record audio.

## 1\. Restart OBS Studio

 Before getting into advanced troubleshooting, consider restarting OBS Studio. The best way is to [launch the Task Manager](https://www.makeuseof.com/windows-open-device-manager/) and close all the OBS Studio-related processes.

 Next, relaunch the OBS Studio and check if it is able to record audio. If not, it's time for some more complicated fixes.

## 2\. Launch OBS Studio With Administrative Rights

 Oftentimes, issues in third-party applications occur due to a lack of administrative privileges. It can happen even when you're using an administrator account on your computer.

 The best way to resolve this problem is to configure OBS Studio to always launch as an administrator. To do that, follow the below steps:

1. Right-click on the OBS Studio icon and choose**Properties** from the context menu.
2. In the Properties window, switch to the**Compatibility** tab.
3. Check the**Run this program as an administrator** option.  
![Run as admin option for OBS Studio](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-as-admin-option.jpg)
4. Click**Apply** \>**OK** to save the settings.

## 3\. Unmute OBS Studio in the Settings App

 OBS Studio will fail to record audio if it is muted in the Settings app. Here's how to check and change OBS Studio sound settings in the Settings app.

1. Open the**Settings** app (see how to [launch the Settings app on Windows](https://www.makeuseof.com/windows-ways-to-open-system-settings/) ) and choose**System** from the left sidebar.
2. Select**Sound** from the right pane.
3. Under the**Advanced section,** choose the**Volume Mixer** option.
4. Under the**Apps section,** unmute OBS Studio if muted and adjust the slider accordingly.  
![Unmute OBS Studio in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/unmute-obs-studio.jpg)
5. Also, click the drop-down icon next to OBS Studio, then choose the correct input device.  
![Choosing default audio device for OBS Studio](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/choosing-default-audio-device.jpg)

Restart OBS Studio and check if the problem persists.

## 4\. Use the Correct Recording Device

 Windows allows you to manually choose recording and playback devices. But if you've chosen an incorrect recording device in Settings, then you're likely to face this issue. To fix this, you will have to configure the correct device as the default recording option. Here's how to do that:

1. Open the**Settings** app, and head towards**System** \>**Sound.**
2. Choose**More sound settings** under the**Advanced section.**
3. Switch to the**Recording** tab.
4. Right-click on the correct recording device and choose the**Set as Default Device** option from the context menu.  
![Set as default option in Sound properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/set-as-default-option.jpg)
5. Click**Apply** and then**OK.**

## 5\. Allow OBS Studio to Access Microphone

[Windows 11 is big on privacy and security](https://www.makeuseof.com/windows-11-privacy-options-explained/) . The OS lets you allow or restrict apps from accessing certain services of your computer. For instance, you can restrict apps from using the microphone on your computer.

 As such, if you've mistakenly restricted OBS Studio from accessing the microphone, then you'll face audio issues. The solution here is to allow OBS Studio to access the microphone. Here's how:

1. Open the Settings app and choose**Privacy & Security** from the left sidebar.
2. Under the**App permission** section, select the**Microphone** option.
3. Enable the toggle next to the**Microphone access** option.  
![Microphone access option in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/microphone-access.jpg)
4. Next, enable the toggle next to**Let desktop apps to access your microphone** option.  
![Allow desktop apps to access microphone option in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/allow-desktop-apps-to-access-microphone.jpg)

## 6\. Change the OBS Studio Settings

 OBS Studio lets you manually set audio devices and adjust their settings as per your preference. However, OBS Studio will be unable to record audio if you have chosen an incorrect audio device within its settings.

 So, head toward the OBS Studio audio settings, and choose the correct audio device to solve the issue. Here are the steps to do it:

1. Launch OBS Studio and choose**File** from the top-left corner.
2. Choose**Settings** from the context menu.
3. In the Settings window, select**Audio** from the left sidebar.
4. Under the**Global Audio Devices** section, click the drop-down icon next to**Desktop Audio** and**Desktop Audio 2** and choose**Default** in both options.
5. Next, click the drop-down icon next to**Mic/Auxiliary Audio** and**Mic/Auxiliary Audio 2** and choose**Default** in both options.  
![Audio settings of OBS Studio](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/audio-settings.jpg)
6. Choose**Apply** \>**OK** to save the changes.

## 7 . Adjust the Audio Mixer Settings

 The next solution on the list is to adjust the audio mixer settings of the OBS Studio. Here's how:

1. Open OBS Studio.
2. Under the**Audio Mixer** section, adjust the**Mic/Aux** slider to**\-2.1dB.**  
![Adjusting dB in OBS Studio](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/adjusting-db.jpg)
3. Click the three dots next to Mic/Aux and choose**Properties.**
4. Click the drop-down icon next to**Device,** select your default recording device and click**OK.**  
![Choosing correct Mic in OBS Studio](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/choosing-correct-mic.jpg)
5. Next, click the three dots next to Mic/Aux again and choose**Advanced Audio Properties.**  
![Choosing Advanced properties in OBS Studio](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/advanced-properties.jpg)
6. Under the**Audio Monitoring** tab, choose**Monitor** **and Output** for**Desktop Audio** and**Monitor Only** **(mute output)** for**Mic/Aux.**  
![Adjusting Advanced Properties in OBS Studio](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/adjusting-advanced-properties.jpg)

## 8\. Download the Latest Audio Driver Updates

 A corrupt or outdated audio driver can also be a prime reason why OBS Studio is unable to record audio. To fix this, you will have to [update the audio driver on Windows](https://www.makeuseof.com/how-to-update-audio-drivers-windows-11/) .

You can do that by following the below steps:

1. Press the**Win + X** hotkeys and choose**Device Manager** from the list.
2. Double-click the**Sound, video, and game controllers** node to expand it.
3. Right-click on your default recording device and select**Update driver** from the context menu.  
![Update driver option in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/update-driver-2.jpg)
4. Choose**Search automatically for drivers** option in the window that crops up.

 Next, allow Windows to search for and download any available driver updates for your recording device.

## 9\. Reinstall OBS Studio

 Are you still facing the issue? If yes, then there's something wrong with the OBS Studio installation file that's causing the problem. The only solution, in this case, is to reinstall the OBS Studio.

## Enjoy Uninterrupted Recording Again on OBS Studio for Windows

 OBS Studio is everyone's first choice to stream online, and there's a strong reason behind it. But sometimes, misconfigured Windows or OBS Studio settings can cause the audio issue. Fortunately, you can quickly get rid of this issue by following the above fixes.

 However, if you think it's time for a change, there are a few OBS Studio alternatives that are worth a try.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>



<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/tailoring-your-pcs-protection-the-firewall-guide/"><u>Tailoring Your PC's Protection: The Firewall Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-mystery-of-yourphoneexe-in-w10/"><u>Unveiling the Mystery of YourPhoneExe in W10</u></a></li>
<li><a href="https://windows11.techidaily.com/unexpected-rav-guard-find-its-source-and-quit-methods/"><u>Unexpected Rav Guard? Find Its Source & Quit Methods</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-2024-approved-upgrade-your-visuals-best-video-quality-improvement-software/"><u>Updated 2024 Approved Upgrade Your Visuals Best Video Quality Improvement Software</u></a></li>
<li><a href="https://windows11.techidaily.com/reinvigorating-a-non-functional-windows-taskbar/"><u>Reinvigorating a Non-Functional Windows Taskbar</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/the-complete-guide-to-xiaomi-redmi-note-12-pro-4g-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>The Complete Guide to Xiaomi Redmi Note 12 Pro 4G FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://windows11.techidaily.com/no-more-erratic-arrows-fixes-for-the-frustrated/"><u>No More Erratic Arrows: Fixes for the Frustrated</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/add-a-professional-touch-free-video-watermark-software-for-2024/"><u>Add a Professional Touch Free Video Watermark Software for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-leading-edge-stabilized-gimbals-iphoneandroidprofessional-rankings-1-10/"><u>[New] Leading-Edge Stabilized Gimbals  IPhone/Android/Professional Rankings #1-#10</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-quicken-windows-edge-on-w10-and-w11/"><u>Tips to Quicken Windows Edge on W10 & W11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-does-the-stardust-trade-cost-in-pokemon-go-on-nokia-c12-plus-drfone-by-drfone-virtual-android/"><u>In 2024, How does the stardust trade cost In pokemon go On Nokia C12 Plus? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/reversing-error-0x800704cf-in-winstore/"><u>Reversing Error 0X800704CF in WinStore</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-gain-momentum-with-these-strategies-for-trending-youtubers/"><u>[New] 2024 Approved  Gain Momentum with These Strategies for Trending YouTubers</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-system-crash-code-0xc0000001/"><u>Remedying System Crash Code 0xC0000001</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-update-iphone-11-pro-to-the-latest-iosipados-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update iPhone 11 Pro to the Latest iOS/iPadOS Version? | Dr.fone</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-the-best-of-the-rest-10plus-windows-movie-maker-alternatives-for-2024/"><u>New The Best of the Rest 10+ Windows Movie Maker Alternatives for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/prioritize-and-proliferate-elevating-notifications-in-windows-11/"><u>Prioritize and Proliferate: Elevating Notifications in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-and-streamline-with-win11s-hard-drive-defrag/"><u>Secure & Streamline with Win11's Hard Drive Defrag</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-of-a-smoother-click-lock-in-windows/"><u>Unveiling the Secrets of a Smoother Click Lock in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/paramount-procedures-for-wiping-your-windows-installation/"><u>Paramount Procedures for Wiping Your Windows Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/the-comprehensive-guide-to-getting-most-out-of-windows-11s-startup-screen/"><u>The Comprehensive Guide to Getting Most Out of Windows 11'S Startup Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-11-error-0x80070570-fixing-damaged-files/"><u>Overcoming Windows 11 Error 0X80070570: Fixing Damaged Files</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-optimal-sony-ps3-reproduction-tools-ranked-pc/"><u>2024 Approved  Optimal Sony PS3 Reproduction Tools Ranked (PC)</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-rhythm-of-the-skies-bebop-parrot-revisited/"><u>The Rhythm of the Skies  Bebop Parrot Revisited</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-unmasking-user-ids-a-guide-to-sids-in-windows-11/"><u>The Art of Unmasking User IDs: A Guide to SIDs in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reinitializing-windows-spooler/"><u>Reinitializing Windows' Spooler</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-frameworks-producing-uplifting-life-journey-broadcasts-for-2024/"><u>[Updated] Frameworks  Producing Uplifting Life Journey Broadcasts for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-full-potential-adding-portable-apps-to-w11/"><u>Unlock Full Potential: Adding Portable Apps to W11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-comprehensive-manual-for-component-settings-in-w11/"><u>The Comprehensive Manual for Component Settings in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/reset-your-screen-quickly-when-black-hits/"><u>Reset Your Screen Quickly When Black Hits</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-all-encompassing-look-at-the-ricoh-theta-s-design/"><u>[Updated] All-Encompassing Look at the Ricoh Theta S Design</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-mastering-windows-11-with-top-tips/"><u>2024 Approved  Mastering Windows 11 with Top Tips</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-mastering-youtube-thumbnails-with-ease/"><u>2024 Approved  Mastering YouTube Thumbnails with Ease</u></a></li>
</ul></div>
