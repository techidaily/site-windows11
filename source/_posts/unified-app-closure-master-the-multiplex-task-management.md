---
title: "Unified App Closure: Master the Multiplex Task Management"
date: 2024-07-11T21:32:22.526Z
updated: 2024-07-12T21:32:22.526Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unified App Closure: Master the Multiplex Task Management"
excerpt: "This Article Describes Unified App Closure: Master the Multiplex Task Management"
keywords: Multiplex Task Mastery,Unified App Shutdown,Closure Skills,Workflow Optimization,Team Coordination,Productivity Boost,Efficiency Strategies
thumbnail: https://thmb.techidaily.com/db54d4e94bdc568181a5a19bde06cb60cc627002afae7c9a75d3a396e9c852b9.JPG
---

## Unified App Closure: Master the Multiplex Task Management

 Running multiple apps simultaneously can usually affect your PC’s performance. This means you might often want to close some programs to speed up your device. But here’s the thing—closing your apps one by one can be quite tedious.

 So, how can you simplify things and close your multiple apps simultaneously on Windows? Let’s find out.

## 1\. Use the Taskbar

 The Windows taskbar displays all your active and pinned programs. This means you can easily close your active apps by scrolling to the relevant taskbar icon and clicking the “close” button.

 The good news is that you can also use the taskbar to close multiple windows of the same program. However, you won’t be able to close different apps simultaneously using the taskbar.

 Here's how to close multiple windows of the same program on the taskbar:

1. Navigate to the taskbar and locate an app that has multiple active windows.
2. Right-click on the app and select the **Close all windows** option.

![Closing multiple windows on the taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/closing-multiple-windows-on-the-taskbar.jpg)

## 2\. Use the Resource Monitor

 You probably know that you can [force close your PC programs](https://www.makeuseof.com/tag/how-to-kill-unresponsive-programs-without-the-task-manager/) using the Task Manager. But the problem is that this tool doesn’t let you close your programs simultaneously.

 Wondering if there's an alternative tool you can use? Try the Resource Monitor!

 Here are the steps for closing multiple apps simultaneously using the Resource Monitor:

1. Type **Resource Monitor** in the Start menu search bar and select the **Best match**.
2. Navigate to the **Overview** tab.
3. Check the boxes of the apps you want to close.
4. Right-click on one of the results and select the **End Process** option. This should simultaneously close all the programs you selected.

![Closing multiple apps using the Resource Monitor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/closing-multiple-apps-using-the-resource-monitor.jpg)

 Want to know the best part about using the Resource Monitor? This tool allows you to re-open multiple apps simultaneously with just a few clicks!

 Here's how to reopen your apps with the Resource Monitor:

1. Access the **Resource Monitor** by applying the previous steps.
2. Check the boxes of all the apps you want to re-open.
3. Right-click on one of the results and select **Resume Process**.

## 3\. Use the Command Prompt

![Person using a Windows PC while placing it on a lap](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Person-using-a-Windows-PC-while-placing-it-on-a-lap.jpg)

 The Command Prompt can help you troubleshoot PC issues, configure some system settings, and run your Windows apps.

 Interestingly, this tool can also help you simultaneously close multiple windows of the same app. However, the Command Prompt might not be the best option if you want to close different apps simultaneously.

 Here’s how you can close multiple windows of the same app using the Command Prompt:

1. Type **Command Prompt** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as administrator**.

![Opening the Command Prompt using the Start menu search bar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/opening-the-command-prompt-using-the-start-menu-search-bar.jpg)

 Let’s say you want to close multiple File Explorer windows simultaneously. To do that, type the following command in the Command Prompt and press **Enter**:

taskkill /f /im explorer.exe

 The “taskkill /f /im” command is the one that closes the program, and the “explorer.exe” command is the name of the app. To close multiple windows of your other apps, replace the “explorer.exe” part with the relevant command.

## 4\. Create a Batch Script for Closing Multiple Apps Simultaneously

![A person using a Windows device on a desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/A-person-using-a-Windows-device-on-a-desk.jpg)

 We’ve already discovered that the Command Prompt can only help you close multiple windows of the same app.

 But if you apply a few tricks, you can close multiple apps using some commands. However, you’d need to [create a batch script](https://www.makeuseof.com/tag/write-simple-batch-bat-file/) for that.

 Here's how you can create a batch script for closing multiple apps on Windows:

1. Press **Win + D** to access the desktop. Alternatively, check out the [various ways to access the Windows desktop](https://www.makeuseof.com/windows-quickly-access-desktop/).
2. Right-click on a blank space and select **New > Text Document**. This will create an untitled document on your desktop.

 Now, let’s say you want to close the **Snipping Tool** and the **Paint.net** app simultaneously. Here are the steps you need to follow:

1. Navigate to the desktop and double-click on the text document you’ve just created.
2. Type the following command to close the Snipping Tool:

taskkill /f /im SnippingTool.exe /T > nul

 Next, type the following command to close the Paint.net app:

taskkill /f /im paintdotnet.exe /T > nul

![Creating a Batch Script for Closing Multiple Apps Simultaneously](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/creating-a-batch-script-for-closing-multiple-apps-simultaneously.jpg)

 From there, follow these steps:

1. Press the **File** tab in the top-left corner of the text file.
2. Select the **Save As** option.
3. Type **Close Multiple Apps Simultaneously.bat** in the **File name** box.
4. Press the **Save** button.

 Now, you can close the Snipping Tool and the Paint.net app simultaneously by following these steps:

1. Press **Win + E** to access File Explorer.
2. Select the **Desktop** option on the left.
3. Click the **Close Multiple Apps Simultaneously.bat** batch file.

![Clicking a batch script on the desktop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/clicking-a-batch-script-on-the-desktop.jpg)

 You can add as many apps as you want to your batch script.

 And when using the batch script, ensure that it doesn’t end up closing some important apps by mistake. This means it might be worth regularly checking what’s on the script first before running it.

## 5\. Use the Close All Windows Tool

![The Close All Windows Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-close-all-windows-tool.jpg)

 You can also quickly close your multiple active apps using a third-party program like the [Close All Windows tool](https://www.softpedia.com/get/System/System-Miscellaneous/AA-Close-All-Windows.shtml). The tool is lightweight, which means it won’t take up much of your disk space.

 This app works almost like the Windows built-in Resource Monitor. However, it comes with a basic and easy-to-understand interface. When you open the tool, it immediately displays all your active apps. All you need to do is tick the relevant boxes and then click the **OK** button to close those apps.

 The tool displays all your apps and places them under a specific category. For example, it displays all your Google Chrome windows under the Google Chrome category.

 To select all the apps on the screen, press **Ctrl + A** or navigate to the **Command** tab and click **Select All**. And if you want to uncheck all the apps, press **Ctrl + D** or click the **Deselect All** option from the **Command** tab.

 You can customize the Close All Windows tool by clicking the **View** tab and ticking the relevant boxes. And if the tool seems a bit too complicated to use, then you can navigate to the **Help** tab to get some assistance.

**Download**: Close All Windows for [Windows](https://www.softpedia.com/get/System/System-Miscellaneous/AA-Close-All-Windows.shtml) (Free, subscription available)

## Close Your Multiple Apps Simultaneously With Just a Few Clicks

 It’s always frustrating when your Windows device suddenly becomes slow or buggy. In most cases, such issues are caused by running tons of apps simultaneously.

 Want a quick way to speed up your device? Close your multiple active programs simultaneously using the tips we’ve covered. And if you end up closing some apps by mistake, you can apply some quick tricks to restore them again.


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
<li><a href="https://windows11.techidaily.com/audio-capture-while-screen-recording-with-snipping-tool-max-156/"><u>Audio Capture While Screen Recording with Snipping Tool (Max 156)</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-in-2024-downloadinstallregisteruninstall-wondershare-virbo/"><u>New In 2024, Download/Install/Register/Uninstall | Wondershare Virbo</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-craft-perfect-openings-anywhere-and-anytime/"><u>In 2024, Craft Perfect Openings, Anywhere and Anytime</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-printer-issues-a-guide-for-unresponsive-print-commands/"><u>Addressing Windows Printer Issues: A Guide for Unresponsive Print Commands.</u></a></li>
<li><a href="https://windows11.techidaily.com/building-a-linux-ecosystem-within-hyper-v-windows-environment/"><u>Building a Linux Ecosystem Within Hyper-V Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/1719311224382-tackle-snip-and-sketch-obstacles-to-perfectly-capture-entire-screen/"><u>Tackle Snip & Sketch Obstacles to Perfectly Capture Entire Screen.</u></a></li>
<li><a href="https://windows11.techidaily.com/7-key-steps-to-overcome-google-chrome-profile-faults/"><u>7 Key Steps to Overcome Google Chrome Profile Faults</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-inaccessible-router-settings-in-windows/"><u>Bypassing Inaccessible Router Settings in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/chrome-files-upload-hurdle-heres-how-to-clear-it-on-windows/"><u>Chrome Files Upload Hurdle? Here's How to Clear It on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/5-creative-routes-to-activate-windows-utilities/"><u>5 Creative Routes to Activate Windows Utilities</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-webcam-hurdles-tackling-error-a00f4289-on-win11/"><u>Bypassing Webcam Hurdles - Tackling Error A00F4289 on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-administrative-status-via-windows-terminal/"><u>Achieve Administrative Status via Windows Terminal</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-pinnacle-headlines-engineer/"><u>2024 Approved  Pinnacle Headlines Engineer</u></a></li>
<li><a href="https://windows11.techidaily.com/adapting-windows-11-multifaceted-monitor-wallpaper-strategy/"><u>Adapting Windows 11: Multifaceted Monitor Wallpaper Strategy</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-best-route-generator-apps-you-should-try-on-lava-blaze-pro-5g-drfone-by-drfone-virtual-android/"><u>5 Best Route Generator Apps You Should Try On Lava Blaze Pro 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-captioning-faults-in-win-10-systems/"><u>Addressing Captioning Faults in Win 10 Systems</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-fix-icloud-lock-from-your-apple-iphone-14-plus-and-ipad-by-drfone-ios/"><u>How to fix iCloud lock from your Apple iPhone 14 Plus and iPad</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-overload-on-windows-applications-0x80860010/"><u>Bypassing Overload on Windows Applications (0X80860010)</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unfortunately-contacts-has-stopped-error-on-oneplus-12r-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Unfortunately, Contacts Has Stopped Error on OnePlus 12R | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-failed-rpc-calls-top-tips-for-windows-users/"><u>Addressing Failed RPC Calls: Top Tips for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-application-support-limitations-on-windows-7/"><u>Addressing Application Support Limitations on Windows 7</u></a></li>
<li><a href="https://windows11.techidaily.com/cep-library-integration/"><u>CEP Library Integration</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-brief-sequences-lasting-impressions-time-lapse-with-samsung/"><u>[New] Brief Sequences, Lasting Impressions  Time-Lapse with Samsung</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-pro-iphone-hdr-photos-made-easy/"><u>2024 Approved  Pro iPhone HDR Photos Made Easy</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-top-10-best-flvto-alternatives-youtube-converter-you-can-try/"><u>In 2024, Top 10 Best Flvto Alternatives YouTube Converter You Can Try</u></a></li>
<li><a href="https://windows11.techidaily.com/1719306890834-key-collectors-rejoice-get-the-perfect-pair-of-keys-and-essential-windows-11-612lifetime/"><u>Key Collectors Rejoice – Get the Perfect Pair of Keys & Essential Windows 11, $6.12/Lifetime</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-overhauling-the-settings-app-in-win11/"><u>A Guide to Overhauling the Settings App in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/7-essential-fixes-to-tackle-the-http-too-many-requests-issue-in-windows/"><u>7 Essential Fixes to Tackle the HTTP Too Many Requests Issue in Windows</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/spectacular-showdowns-and-excursions-top-10-gaming-treasures/"><u>Spectacular Showdowns & Excursions – Top 10 Gaming Treasures</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/our-complimentary-access-to-50-premium-youtube-banners-for-2024/"><u>[New] Your Complimentary Access to 50 Premium YouTube Banners for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/breathe-life-into-dead-wi-fi-connections-on-windows-10-with-this-list/"><u>Breathe Life Into Dead Wi-Fi Connections on Windows 10 with This List</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-best-font-generators-enhance-your-discord-experience-androidios/"><u>[New] Best Font Generators  Enhance Your Discord Experience (Android/iOS)</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-11-key-inactivity-issues/"><u>Addressing Windows 11 Key Inactivity Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-sync-launch-sticky-notes-with-windows-start-up/"><u>Boosting Sync: Launch Sticky Notes with Windows Start-Up</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-taking-audio-to-the-next-level-on-desktop-and-mobile-discord-with-voicemod/"><u>2024 Approved  Taking Audio to the Next Level on Desktop & Mobile Discord with VoiceMod</u></a></li>
<li><a href="https://windows11.techidaily.com/blackview-minipc-expansive-but-sluggish-storage/"><u>Blackview MiniPC: Expansive but Sluggish Storage</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/becoming-a-master-at-the-art-of-engaging-thumbnails/"><u>Becoming a Master at the Art of Engaging Thumbnails</u></a></li>
<li><a href="https://windows11.techidaily.com/adjust-brightness-slider-look-for-the-brightness-slider-under-system-or-personalization-tabs-in-settings/"><u>Adjust Brightness Slider: Look for the Brightness Slider Under 'System' Or 'Personalization' Tabs in Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-faulty-alerts-from-windows-10s-shield/"><u>Addressing Faulty Alerts From Windows 10'S Shield</u></a></li>
<li><a href="https://windows11.techidaily.com/a-harmonious-symphony-taming-your-computers-audio-irqs/"><u>A Harmonious Symphony: Taming Your Computer’s Audio IRQs</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-frozen-wow-post-update-phases/"><u>Bypassing Frozen WoW Post-Update Phases</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-edge-guards-camera-and-mic-use/"><u>Activating Edge Guards: Camera & Mic Use</u></a></li>
<li><a href="https://windows11.techidaily.com/balance-usage-and-energy-efficiency-with-automatic-rest-mode/"><u>Balance Usage & Energy Efficiency with Automatic Rest Mode</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-leading-chrome-extensions-simplified-vimeo-retrievals/"><u>[Updated] Leading Chrome Extensions  Simplified Vimeo Retrievals</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-windows-11s-screen-capture-shortcut/"><u>Accessing Windows 11'S Screen Capture Shortcut</u></a></li>
<li><a href="https://windows11.techidaily.com/arrows-at-a-standstill-try-these-remedies/"><u>Arrows at a Standstill? Try These Remedies</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/infusing-vibrancy-into-stories-a-guide-to-choosing-the-right-emojis-for-2024/"><u>Infusing Vibrancy Into Stories  A Guide to Choosing the Right Emojis for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-lost-extra-screen-in-w11/"><u>Addressing Lost Extra Screen in W11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-remove-or-bypass-knox-enrollment-service-on-nubia-red-magic-8s-pro-by-drfone-android/"><u>In 2024, How To Remove or Bypass Knox Enrollment Service On Nubia Red Magic 8S Pro</u></a></li>
<li><a href="https://network-issues.techidaily.com/nvidia-patch-rtx210-win11-driver-update/"><u>NVIDIA Patch: RTX210 Win11 Driver Update</u></a></li>
</ul></div>
