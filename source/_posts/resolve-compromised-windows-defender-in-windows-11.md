---
title: Resolve Compromised Windows Defender in Windows 11
date: 2024-07-11T21:21:39.687Z
updated: 2024-07-12T21:21:39.687Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolve Compromised Windows Defender in Windows 11
excerpt: This Article Describes Resolve Compromised Windows Defender in Windows 11
keywords: Fixing Defender Issues,Secure Windows 11,Disable Compromised Antivirus,Protect Against Malware,Enhance Windows Security,Restore Defender Integrity,Unlock Safe Mode
thumbnail: https://thmb.techidaily.com/0cc7e321d1f451639d7bc59d3e2137f7bee3ef2e1c2be15bafe3ca0804538ad9.jpg
---

## Resolve Compromised Windows Defender in Windows 11

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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/curate-your-own-win11-screen-saver/"><u>Curate Your Own Win11 Screen Saver</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-folders-to-the-context-menu-in-windows-11/"><u>How to Add Folders to the Context Menu in Windows 11</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-tuning-into-audio-bliss-your-iphone-as-a-podcasters-companion/"><u>[Updated] 2024 Approved  Tuning Into Audio Bliss - Your iPhone as a Podcaster's Companion</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-in-2024-how-to-amass-a-picture-collection-for-free-the-ultimate-12-website-guide/"><u>[Updated] In 2024, How to Amass a Picture Collection for Free – The Ultimate 12 Website Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-data-handling-navigate-4-steps-to-open-disk-management-in-windows-11/"><u>Effortless Data Handling: Navigate 4 Steps to Open Disk Management in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-overcoming-unidentified-obs-recording-issue-on-win-11/"><u>Decoding and Overcoming Unidentified OBS Recording Issue on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/initiate-your-narrative-with-a-click-on-windows-11/"><u>Initiate Your Narrative with a Click on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/interpretation-of-the-red-x-icon-in-file-management/"><u>Interpretation of the Red “X” Icon in File Management</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-minecraft-filming-101-from-start-to-finish-for-2024/"><u>[New] Minecraft Filming 101  From Start to Finish for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/future-screens-innovating-beyond-windows-11/"><u>Future Screens: Innovating Beyond Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-overcome-media-error-input-not-recognized-by-vlc/"><u>How to Overcome Media Error: Input Not Recognized by VLC</u></a></li>
<li><a href="https://windows11.techidaily.com/installing-icloud-is-easy-troubleshoot-issues-on-windows/"><u>Installing iCloud Is Easy: Troubleshoot Issues on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-microsofts-enhancements-in-februarys-win11-patch/"><u>Exploring Microsoft's Enhancements in February's Win11 Patch</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-leading-cloud-services-with-best-price/"><u>[New] The Leading Cloud Services with Best Price</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-innovating-human-interface-a-guide-to-hand-perception/"><u>[New] Innovating Human Interface  A Guide to Hand Perception</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-the-power-of-background-blur-a-windows-11-photo-guide/"><u>Discover the Power of Background Blur: A Windows 11 Photo Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-restore-your-desktop-icon-positions-on-windows/"><u>How to Restore Your Desktop Icon Positions on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-file-selection-adding-directories-to-context-menu/"><u>Enhancing File Selection: Adding Directories to Context Menu</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-charting-a-course-through-websites-of-youtube-affiliates/"><u>[Updated] Charting a Course Through Websites of YouTube Affiliates</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-behind-pretense-apps-slowdown-your-modern-windows/"><u>Hidden Behind Pretense: Apps Slowdown Your Modern Windows</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-a-step-by-step-blueprint-to-enhance-videos-by-merging-soundtracks-without-incurring-fees/"><u>New In 2024, A Step-by-Step Blueprint to Enhance Videos by Merging Soundtracks Without Incurring Fees</u></a></li>
<li><a href="https://windows11.techidaily.com/circumventing-windows-security-controlled-by-domain-admins/"><u>Circumventing Windows Security Controlled by Domain Admins</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-perfect-your-channel-info-a-template-approach/"><u>[New] 2024 Approved  Perfect Your Channel Info  A Template Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-to-vanquish-your-pcs-win11-blue-screen/"><u>Expert Tips to Vanquish Your PC's Win11 Blue Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/is-windows-11-running-slow-or-lagging-on-your-computer-7-ways-to-fix-it/"><u>Is Windows 11 Running Slow or Lagging on Your Computer? 7 Ways to Fix It</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-past-the-activation-hurdle-in-microsoft-office/"><u>Navigating Past the Activation Hurdle in Microsoft Office</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-solving-win-1011-ad-ds-printer-problems-efficiently/"><u>Guide to Solving Win 10/11 AD DS Printer Problems Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/highlighting-key-windows-processes-for-virus-alerts/"><u>Highlighting Key Windows Processes for Virus Alerts</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-rejuvenate-a-dysfunctional-search-bar-in-windows-11/"><u>Guide to Rejuvenate a Dysfunctional Search Bar in Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/why-does-the-pokemon-go-battle-league-not-available-on-tecno-spark-10-pro-drfone-by-drfone-virtual-android/"><u>Why does the pokemon go battle league not available On Tecno Spark 10 Pro | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-premium-audio-visual-leading-blu-ray-devices/"><u>[Updated] Premium Audio, Visual  Leading Blu-Ray Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-activation-error-0x803f700f-fix-guide/"><u>Overcoming Windows Activation Error: 0X803F700F Fix Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/ideal-mobile-software-for-windows-pc-owners-on-android/"><u>Ideal Mobile Software for Windows PC Owners on Android</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-streamlining-video-uploads-tips-for-transforming-h-vids-for-igtv/"><u>[New] In 2024, Streamlining Video Uploads  Tips for Transforming H-Vids for IGTV</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-gopro-hero5-session-vs-hero-session/"><u>In 2024, GoPro Hero5 Session Vs Hero Session</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/4-easy-ways-for-your-realme-narzo-n53-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>4 Easy Ways for Your Realme Narzo N53 Hard Reset | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-user-interface-fastest-uninstall-actions-with-context/"><u>Elevate User Interface: Fastest Uninstall Actions with Context</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-superior-tools-for-group-online-calls/"><u>[Updated] 2024 Approved  Superior Tools for Group Online Calls</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-win10-blue-screen-recovery/"><u>Mastering the Art of Win10 Blue Screen Recovery</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-all-you-need-to-know-about-mega-greninja-for-oneplus-nord-ce-3-lite-5g-drfone-by-drfone-virtual-android/"><u>In 2024, All You Need To Know About Mega Greninja For OnePlus Nord CE 3 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-file-explorer-opening-tabs-in-windows-11/"><u>Mastery of File Explorer: Opening Tabs in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-the-future-ui-design-with-new-folder-integration-in-windows-11/"><u>Navigate the Future UI Design with New Folder Integration in Windows 11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/disable-screen-lock-on-galaxy-s24-ultra-by-drfone-android-unlock-android-unlock/"><u>Disable screen lock on Galaxy S24 Ultra</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-podcasters-roadmap-to-seo-excellence/"><u>In 2024, The Podcaster’s Roadmap to SEO Excellence</u></a></li>
<li><a href="https://windows11.techidaily.com/correction-of-inaccessible-device-path-issue-in-win/"><u>Correction of Inaccessible Device Path Issue in Win</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-bridging-worlds-unveiling-the-best-6-in-nft-art/"><u>[New] Bridging Worlds  Unveiling the Best 6 in NFT Art</u></a></li>
</ul></div>
