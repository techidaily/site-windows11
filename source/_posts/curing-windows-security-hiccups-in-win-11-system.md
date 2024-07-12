---
title: Curing Windows Security Hiccups in Win 11 System
date: 2024-07-11T22:21:18.032Z
updated: 2024-07-12T22:21:18.032Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Curing Windows Security Hiccups in Win 11 System
excerpt: This Article Describes Curing Windows Security Hiccups in Win 11 System
keywords: Fixing Windows 11 Vulnerabilities,Remedy Windows 11 Security Issues,Resolve Windows 11 Safety Flaws,Tackling Win 11 Cyber Weaknesses,Secure Windows 11 Systems,Improving Win 11 Privacy,Enhance Windows 11 Defense
thumbnail: https://thmb.techidaily.com/4cbebb13391bd3ac3f3b9ef43b45b771ba69f0146a8bbd42e4f0e8dd5abd0510.jpg
---

## Curing Windows Security Hiccups in Win 11 System

 Windows Security is a free and default antivirus program provided by Microsoft to protect your PC from outside threats. However, there are times when the security software might stop working properly, or in some cases, not start at all. And to top off, if you’re also not using a third-party antivirus app, you're basically wide open to a myriad of security attacks.

 It's therefore crucial that Windows security is working at its best; this will keep your computer security airtight. In this article, we’ve laid down some of the best tricks that will help you fix Windows Security on your Windows 11\.

## 1\. Turn on Windows Security

 In rare cases when a PC undergoes a malicious attack one of the first things that the malicious program does is [turn off all the antivirus defenses like Microsoft Defender](https://www.makeuseof.com/how-to-turn-off-microsoft-defender-windows-11/). If your PC has undergone such an attack recently, then it might be possible that you're facing the same issue.

 If that's indeed the case then you'll have to manually enable Windows Security on your PC. Follow these steps to continue:

1. Head to the **Start menu** search bar, type in 'security,' and select the best match.
2. From there, click on **Turn on** to enable the **Virus & threat protection** of your PC.
3. A new dialog box will pop up asking you to confirm if you want to go ahead with the changes; click on **Yes** to proceed.

![security at glance menu in windows security settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-security.jpg)

 The Windows Security app will be enabled instantly.

## 2\. Update Windows 11

 How long has it been since you last updated your Windows? If it’s been a while, it might be a good time to brush off the dust from your updates.

 Follow these steps to check for updates on your Windows PC:

1. Go to the **Start menu** search bar, type in ‘settings,’ and select the Best match. Alternatively, press **Win + I** together.
2. Scroll down and select **Windows Update**.
3. Now click on **Check for updates** and Windows will start checking for updates on your PC. (If any new updates are available, they’ll be displayed on the **Windows Update** screen.)
4. Finally, click on **Download & install** to get the ball rolling.

![windows update section in the settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/windows-update-1.png)

 When the updates download is complete, give your PC a quick restart and see if the problem with Windows Security persists. If it does, then jump below to the next method.

## 3\. Disable Third-Party Antivirus

 If you have an additional antivirus installed on your PC, it might be a good time to get rid of it.

 Running Windows Security along with third-party antivirus apps has been known to cause many kinds of disruption in Windows computers. So removing the additional antivirus might, in fact, be a fair approach—remove the antivirus and see if it can get everything back to normal.

 To get started, launch the **Settings** again. Go to **Apps > Apps & features**, search for the antivirus, and when you find it, click on options (three dots) and select **Uninstall**.

![apps and features in the apps settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/apps-and-feature.png)

 The third-party antivirus will be removed. Now restart your Windows 11 and see if the problem with Windows Security persists. It shouldn’t.

## 4\. Reset the Windows Security App

 Removing the third-party antivirus app from your PC should get your Windows Security back to work in most cases. However, in cases where it's not, it might be time to do a complete reset of your Security app.

 Follow these steps to reset the Windows Security app:

1. Go to the **Settings** menu again by pressing the **Windows key + I**.
2. Select **App > Apps & features** and type in ‘security’ in the search menu box.
3. An icon for Windows Security will pop open. From there, click on the **options** (three dots) and select **Advanced options**.
4. Now scroll down to **Reset** section and click on **Reset**.

 You’ll get a confirmation asking if you really want to reset the app, along with your whole app data. Click on **Reset** to go with it.

![reset and repair option in the windows security settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/reset-and-repair.jpg)

 You can also try the **Repair** option if you don't want to reset the app right off. It’s right there above the **Reset** option. As soon you click on **Repair**, the process will begin. When the Repair is complete, it’ll leave a tick option adjacent to **Repair** box.

## 5\. Run an SFC and DISM Scan

 SFC, short for System File Checker, is a Windows utility that can be fallen back upon when some of your Windows files malfunction. In short, it checks for file corruption and then tries to repair it.

 It is accessed through the Command prompt. To get started, go to the **Start menu** search bar, type in ‘command prompt,’ and then launch it as administrator.

 This launches your Command prompt in an elevated mode, something necessary to run the SFC utility.

 In the Command prompt, type the following command and hit **Enter**:

`sfc/ scannow`

 The tool will scan your PC and you should be able to run the Security app by the end.

![execution of sfc scan in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/sfc-scan-in-command-prompt.png)

 If the SFC tool doesn't work, don't fret just yet. Another tool that you can try your luck with is the DISM; it's not the same as SFC, but it works almost similarly. You can check out the [differences between SFC and DISM](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) if you'd like to learn more.

 Much like how the SFC tool helps you fix your PC, a DISM scan finds and fixes any issues with your system image that might be causing problems with your PC's functioning.

 Like with SFC scan above, you’ll have to launch the DISM as an administrator as well. Go to the **Start menu,** type in ‘DISM,’ and run it as administrator. When you launch the DISM scan, enter the following command and hit **Enter**:

`DISM /Online /Cleanup-Image /ScanHealth`

![execution of dsim scan in the command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/dsim-scan-command-prompt.png)

 As soon as the command finishes executing, your files would've been scanned and all the corruption issues would most possibly have been resolved.

 When you’re done, [simply restart your PC](https://www.makeuseof.com/windows-restart-methods/) for the changes to take effect, and see if the problem persists.

## 6\. Restart the Windows Security Service

 Windows Security makes use of a host of programs and services for smooth functioning on your PC. One of those handy services is the Windows Security Center service which monitors the security state of the important components of your system.

 So, if your Windows Security app stopped opening, or if it crashed midway, we suggest you restart your Windows Security Center Service right away. To get started, follow the steps below:

1. Press **Win + R** and type "services.msc" and hit the Enter key.
2. Here, scroll down to find and right-click on **Security-Center** and then select **Restart**.

![security services process in the services app on windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/services-app-windows-11.jpg)

 That's it. Follow any other on-screen instructions and wait for the service to reboot of the service. When that's done, restart your PC and the Windows Security service will be fixed by the next boot-up.

## 7\. Reset Your PC

 A panacea for almost all [the common Windows bugs](https://www.makeuseof.com/common-windows-11-problems/), the **Reset Your PC** setting resets your computer and brings it to its initial state. It’s far better than reinstalling the whole Windows, as you can reset your PC while also keeping your personal files and folders intact.

 To get started, follow the steps below:

1. Go to the **Start menu** search bar, type in ‘settings,’ and select the Best match.
2. In the **Settings** menu, click on **System > Recovery**.
3. In the **Recovery options** tab, click on Reset PC.
4. Then select **Keep my files > Local reinstall** and click on **Next**.

![two types of reset options in the reset this pc on windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/reset-this-pc-windows-11.png)

 That’s it. Follow the onscreen instructions ahead and your Windows will be formatted and reinstalled in no time. When your PC restarts, all your settings will be at ground zero again.

 The whole process is fairly straightforward, but if you face any difficulties during the reset, make sure you go through a [complete guide on Windows 10 factory reset](http://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) and verify if you're making any slip-ups in between the steps.

## Fixing the Issues With Windows Security

 Windows Security is a must-have for Windows health. However, the app can sometimes malfunction and stop working properly. Hopefully, one of the methods laid out above helped you get it working once again.

 But that's not all; There are a ton of ways you can dial up your PC’s security, so make sure you aren’t simply relying only on Windows security for your PC's cyber protection.

 It's therefore crucial that Windows security is working at its best; this will keep your computer security airtight. In this article, we’ve laid down some of the best tricks that will help you fix Windows Security on your Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/disable-auto-updates-in-windows-and-office-instantly/"><u>Disable Auto-Updates in Windows & Office Instantly</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-exclusive-access-to-the-best-7-vids-for-2024/"><u>[New] Exclusive Access to the Best 7 Vids for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-frp-on-motorola-edge-2023-by-drfone-android/"><u>How to Bypass FRP on Motorola Edge 2023?</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-performance-monitoring-pcs-ram-gpu-and-cpu/"><u>Maximizing Performance: Monitoring PC's RAM, GPU & CPU</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-reimagining-communication-advanced-tactics-for-capturing-skype-calls/"><u>In 2024, Reimagining Communication  Advanced Tactics for Capturing Skype Calls</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-why-is-ipogo-not-working-on-oppo-reno-8t-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, Why is iPogo not working On Oppo Reno 8T? Fixed | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/bypass-reset-google-pixel-8-phone-screen-passcode-pattern-pin-by-drfone-android-unlock-android-unlock/"><u>Bypass/Reset Google Pixel 8 Phone Screen Passcode/Pattern/Pin</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-and-remedying-wins-error-messages/"><u>Deciphering & Remedying WINS Error Messages</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-powershell-to-break-free-from-windows-file-blocks/"><u>Mastering PowerShell to Break Free From Windows File Blocks</u></a></li>
<li><a href="https://windows11.techidaily.com/curbing-the-noise-quiet-explore-tab-behavior/"><u>Curbing the Noise: Quiet Explore Tab Behavior</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-step-into-the-world-of-vrecorder-downloading-and-using-for-2024/"><u>[Updated] Step Into the World of VRecorder  Downloading and Using for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-dive-into-the-world-of-time-lagged-footage-with-these-android-tips/"><u>2024 Approved  Dive Into the World of Time-Lagged Footage with These Android Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-sound-misstep-solving-xc00d36b4-on-windows/"><u>Decoding Sound Misstep: Solving XC00D36B4 on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-individual-user-settings-on-group-policy-level/"><u>Delving Into Individual User Settings on Group Policy Level</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-honor-90-drfone-by-drfone-virtual-android/"><u>In 2024, Can I use iTools gpx file to catch the rare Pokemon On Honor 90 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-html-display-issues-in-windows-11-email-client/"><u>Correcting HTML Display Issues in Windows 11 Email Client</u></a></li>
<li><a href="https://extra-information.techidaily.com/blueprint-for-a-thriving-portfolio-in-graphics-for-2024/"><u>Blueprint for a Thriving Portfolio in Graphics for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-unfreezing-window-taskbar/"><u>Comprehensive Guide to Unfreezing Window TaskBar</u></a></li>
<li><a href="https://windows11.techidaily.com/converting-files-a-step-by-step-windows-process/"><u>Converting Files: A Step-by-Step Windows Process</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-ins-and-outs-of-administrative-task-management-in-win11/"><u>Navigating the Ins and Outs of Administrative Task Management in Win11</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-the-complete-vocalists-toolkit-enhancing-and-changing-your-voice-on-audacity/"><u>Updated In 2024, The Complete Vocalists Toolkit Enhancing and Changing Your Voice on Audacity</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-code-of-high-quality-visuals-with-windows-11-hdr/"><u>Deciphering the Code of High-Quality Visuals with Windows 11 HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-elevate-pre-windows-upgrade-machines-into-win11/"><u>How to Elevate Pre-Windows Upgrade Machines Into Win11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-unleashing-potential-with-well-planned-instagram-content/"><u>2024 Approved  Unleashing Potential with Well-Planned Instagram Content</u></a></li>
<li><a href="https://windows11.techidaily.com/confronting-and-overcoming-failed-capture-issues-in-windows/"><u>Confronting and Overcoming Failed Capture Issues in Windows</u></a></li>
<li><a href="https://extra-support.techidaily.com/quick-and-cool-tips-for-insta-collage-creation-for-2024/"><u>Quick & Cool Tips for Insta Collage Creation for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/forgot-pattern-lock-heres-how-you-can-unlock-infinix-note-30-pattern-lock-screen-by-drfone-android/"><u>Forgot Pattern Lock? Heres How You Can Unlock Infinix Note 30 Pattern Lock Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-tips-for-individualized-pattern-security-on-windows/"><u>Cutting-Edge Tips for Individualized Pattern Security on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/instant-permadelete-configuring-your-desktop-trash-bin-on-windows-11-devices/"><u>Instant PermaDelete: Configuring Your Desktop Trash Bin on Windows 11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/control-windows-11s-emphasis-and-search-highlight/"><u>Control Windows 11'S Emphasis and Search Highlight</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-frequent-anydesk-windows-complications/"><u>Conquering Frequent AnyDesk Windows Complications</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-iphone-14-icloud-activation-lock-bypass-by-drfone-ios/"><u>In 2024, iPhone 14 iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-the-real-story-exploring-recordcast-features/"><u>2024 Approved  The Real Story  Exploring RecordCast Features</u></a></li>
<li><a href="https://windows11.techidaily.com/darkeningwindowsnotepaddisplaysettings/"><u>DarkeningWindowsNotepadDisplaySettings</u></a></li>
<li><a href="https://youtube-data.techidaily.com/0-histology-streams-for-academics-for-2024/"><u>Top 10 Histology Streams for Academics for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/is-your-iphone-11-pro-in-security-lockout-proper-ways-to-unlock-by-drfone-ios/"><u>Is Your iPhone 11 Pro in Security Lockout? Proper Ways To Unlock</u></a></li>
<li><a href="https://windows11.techidaily.com/combat-unknown-obs-record-error-on-windows-11-pc/"><u>Combat Unknown OBS Record Error on Windows 11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/how-ai-copilot-enriches-windows-11-for-everyday-users/"><u>How AI Copilot Enriches Windows 11 for Everyday Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-essential-steps-to-clear-overflowing-c-drive-data/"><u>3 Essential Steps to Clear Overflowing C: Drive Data</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-reframe-resize-and-enhance-best-video-editor-options/"><u>Updated 2024 Approved Reframe, Resize, and Enhance Best Video Editor Options</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-check-if-your-vivo-x100-is-unlocked-by-drfone-android/"><u>In 2024, How To Check if Your Vivo X100 Is Unlocked</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-specified-user-does-not-have-a-valid-profile-app-error-in-windows-10-and-11/"><u>How to Fix the Specified User Does Not Have a Valid Profile App Error in Windows 10 & 11</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/intro-maker-software-for-pc-top-10-reviews-and-comparisons-for-2024/"><u>Intro Maker Software for PC Top 10 Reviews and Comparisons for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-discord-setup-woes-on-windows-11/"><u>Correcting Discord Setup Woes on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/combining-kali-with-windows-os-seamlessly/"><u>Combining Kali with Windows OS Seamlessly</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-disparities-microsoft-and-default-windows-login-types/"><u>Dissecting Disparities: Microsoft and Default Windows Login Types</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-become-a-viral-sensation-with-these-9-proven-instagram-tricks/"><u>In 2024, Become a Viral Sensation with These 9 Proven Instagram Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/directive-for-disabling-onedrive-symbol-in-windows-11s-filesystem-viewer/"><u>Directive for Disabling OneDrive Symbol in Windows 11’S Filesystem Viewer</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-paths-opening-system-information-at-your-fingertips/"><u>Direct Paths: Opening System Information at Your Fingertips</u></a></li>
<li><a href="https://windows11.techidaily.com/keep-your-disk-space-clear-with-auto-delete-in-win11/"><u>Keep Your Disk Space Clear with Auto-Delete in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/learn-to-break-the-synergy-onedrive-and-microsoft-profile-split/"><u>Learn to Break the Synergy: OneDrive and Microsoft Profile Split</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-how-to-captivate-viewers-using-multiple-perspectives-on-fb-live/"><u>[Updated] 2024 Approved  How to Captivate Viewers Using Multiple Perspectives on FB Live</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-the-hurdle-of-ms-teams-error-80080300-with-actionable-steps/"><u>Clear the Hurdle of MS Teams Error 80080300 with Actionable Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/defeating-defunct-windows-security-hurdles-in-win-11/"><u>Defeating Defunct Windows Security Hurdles in Win 11</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/how-to-add-chapters-to-vimeo-video-for-2024/"><u>How to Add Chapters to Vimeo Video for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-comprehensive-guide-to-crafting-impeccable-srt-files/"><u>2024 Approved  The Comprehensive Guide to Crafting Impeccable SRT Files</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-from-idea-to-screen-a-simplified-movie-making-process/"><u>Updated From Idea to Screen A Simplified Movie Making Process</u></a></li>
<li><a href="https://extra-skills.techidaily.com/premium-giggle-and-graphics-editor-for-2024/"><u>Premium Giggle & Graphics Editor for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-change-location-on-yik-yak-for-your-infinix-note-30-vip-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>In 2024, Change Location on Yik Yak For your Infinix Note 30 VIP to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-windows-xc0f1103f-geforce-not-working/"><u>Correcting Windows' XC0F1103F GeForce Not Working</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>