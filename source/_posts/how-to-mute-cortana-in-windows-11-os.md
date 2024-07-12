---
title: How to Mute Cortana in Windows 11 OS
date: 2024-07-11T21:37:07.826Z
updated: 2024-07-12T21:37:07.826Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Mute Cortana in Windows 11 OS
excerpt: This Article Describes How to Mute Cortana in Windows 11 OS
keywords: Muting Cortana Windows 11,Turn Off Cortana Windows,Disable Cortana Windows 11,Cortana Silence Guide Windows,Stop Cortana in Windows OS,Cortana Suppress Windows,How to Halt Cortana Wins
thumbnail: https://thmb.techidaily.com/897a54d20c0fe274d0937962de97f84511515ba57539d3344fb75e1f209995c6.png
---

## How to Mute Cortana in Windows 11 OS

 Windows Copilot, Microsoft's new AI assistant, can assist you with a variety of tasks, such as answering questions, changing system settings, and creating AI images. However, if you're not a fan of Copilot or simply don't need it, you can remove its taskbar icon or disable it entirely on your Windows 11 PC. Here, we'll show you how.

## How to Remove the Copilot Icon From the Windows 11 Taskbar

 By default, the Copilot icon appears in the Windows 11 taskbar. However, if you prefer not to have it there but still want to use it occasionally, it's easy to hide the Copilot icon. Simply right-click anywhere on an empty spot on your taskbar and select **Taskbar settings**. In the Settings window that appears, turn off the toggle next to **Copilot**.

![Remove Copilot Icon From Windows 11 Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/remove-copilot-icon-from-windows-11-taskbar.jpg)

 This should remove the Copilot icon from the taskbar. You can still access Copilot by pressing the **Win + C** keyboard shortcut in Windows 11\.

## How to Completely Disable Copilot via Group Policy Settings

 Although hiding the Copilot is quite easy, it does not turn it off completely, and you might inadvertently access it. Fortunately, you can turn off Copilot completely via the Local Group Policy Editor on PCs running the Professional, Education, or Enterprise edition of Windows 11\.

 If you are using Windows 11 Home, skip to the Registry Editor method below or use a [workaround to enable the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Press **Win + S** to access the search menu.
2. Type **gpedit.msc** in the search box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **User Configuration > Administrative Templates > Windows Components > Windows Copilot**.
5. Double-click the **Turn off Windows Copilot** policy on your right.
6. Select the **Enabled** option.
7. Hit **Apply** followed by **OK**.  
![Turn Off Windows Copilot Using the Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-windows-copilot-using-the-group-policy-editor.jpg)

 Once you complete the above steps, Copilot will be disabled on your Windows 11 PC and you won't be able to access it even with the keyboard shortcut. If you want to re-enable Copilot later, repeat the above steps and set the **Turn off Windows Copilot** policy to **Not configured** or **Disabled**.

## How to Completely Disable Copilot by Modifying Registry Files

 Another way to disable Copilot on Windows 11 involves modifying registry files. However, since editing the registry can be risky, you should follow the steps carefully. Also, be sure to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/). This will allow you to restore the registry files in case something goes wrong.

 Once you’ve done that, here’s what you need to do to disable Copilot via the Registry Editor:

1. Press **Win + R** to open the Run dialog.
2. Type **regedit** in the text box and press **Enter** to open the Registry Editor.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > Software > Policies > Microsoft > Windows**.
5. Right-click the **Windows** key and select **New > Key**. Name it **WindowsCopilot**.
6. Right-click on the **WindowsCopilot** DWORD, go to **New**, and select **DWORD (32-bit) Value** from the submenu. Name the DWORD **TurnOffWindowsCopilot**.
7. Double-click the **TurnOffWindowsCopilot** DWORD, type **1** in the text field, and click **OK**.
8. Restart your PC for the changes to take effect.  
![Turn Off Windows Copilot Using the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-windows-copilot-using-the-registry-editor.jpg)

 And that’s about it. Windows Copilot will be disabled on your PC. To re-enable it in the future, repeat the above steps and set the **TurnOffWindowsCopilot** DWORD value to 0\. You can also delete the **TurnOffWindowsCopilot** DWORD instead.

## Get Rid of Copilot on Windows 11

 While Windows Copilot is a powerful tool, not everyone may want to use it. Fortunately, it’s possible to get rid of it. The above steps will help you achieve your goal, whether you want to keep Copilot out of sight or turn it off entirely.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/cep-library-integration/"><u>CEP Library Integration</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-productivity-with-permanent-windows-terminal-admin-entry/"><u>Boost Productivity with Permanent Windows Terminal Admin Entry</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-edge-guards-camera-and-mic-use/"><u>Activating Edge Guards: Camera & Mic Use</u></a></li>
<li><a href="https://windows11.techidaily.com/a-deep-dive-into-winning-windows-captures-with-printscreen-or-snip-tool/"><u>A Deep Dive Into Winning Windows Captures with Printscreen or Snip Tool</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-premium-choices-in-video-capture-tools-for-websites/"><u>[New] Premium Choices in Video Capture Tools for Websites</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-breaking-barriers-download-and-store-your-fmb-conversations/"><u>2024 Approved  Breaking Barriers  Download & Store Your FMB Conversations</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-break-free-from-sony-vegas-top-video-editing-alternatives-for-windows/"><u>New Break Free From Sony Vegas Top Video Editing Alternatives for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/5-ways-to-fix-the-hypervisorerror-blue-screen-on-windows-11-and-11/"><u>5 Ways to Fix the HYPERVISOR_ERROR Blue Screen on Windows 11 & 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/still-using-pattern-locks-with-xiaomi-redmi-k70-tips-tricks-and-helpful-advice-by-drfone-android/"><u>Still Using Pattern Locks with Xiaomi Redmi K70? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-inaccessible-router-settings-in-windows/"><u>Bypassing Inaccessible Router Settings in Windows</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-the-ultimate-guide-to-youtube-seo-techniques/"><u>[New] The Ultimate Guide to YouTube SEO Techniques</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-perfect-photo-framing-digital-sites-and-apps-guide/"><u>In 2024, Perfect Photo Framing  Digital Sites and Apps Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/balance-usage-and-energy-efficiency-with-automatic-rest-mode/"><u>Balance Usage & Energy Efficiency with Automatic Rest Mode</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-sim-unlock-infinix-hot-40i-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>In 2024, Sim Unlock Infinix Hot 40i Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-iphone-6s-apples-new-iphone-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 6s, Apples New iPhone</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-sync-launch-sticky-notes-with-windows-start-up/"><u>Boosting Sync: Launch Sticky Notes with Windows Start-Up</u></a></li>
<li><a href="https://windows11.techidaily.com/adjust-brightness-slider-look-for-the-brightness-slider-under-system-or-personalization-tabs-in-settings/"><u>Adjust Brightness Slider: Look for the Brightness Slider Under 'System' Or 'Personalization' Tabs in Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/1719311224382-tackle-snip-and-sketch-obstacles-to-perfectly-capture-entire-screen/"><u>Tackle Snip & Sketch Obstacles to Perfectly Capture Entire Screen.</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlock-your-vivo-y02t-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>Unlock Your Vivo Y02T Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-edge-browsing-performance-on-win10win11/"><u>Accelerating Edge Browsing Performance on Win10/Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-webcam-hurdles-tackling-error-a00f4289-on-win11/"><u>Bypassing Webcam Hurdles - Tackling Error A00F4289 on Win11</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-how-to-record-audio-on-windows-10-5-easy-steps/"><u>New In 2024, How to Record Audio on Windows 10 5 Easy Steps</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-unlock-free-vocal-manipulation-expertise-with-in-depth-guide-to-voice-editing-via-filmora/"><u>In 2024, Unlock Free Vocal Manipulation Expertise with In-Depth Guide to Voice Editing via Filmora</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reliable-user-guide-to-fix-realme-11-proplus-running-slow-and-freezing-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reliable User Guide to Fix Realme 11 Pro+ Running Slow and Freezing | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/audio-capture-while-screen-recording-with-snipping-tool-max-156/"><u>Audio Capture While Screen Recording with Snipping Tool (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-lost-extra-screen-in-w11/"><u>Addressing Lost Extra Screen in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-frozen-wow-post-update-phases/"><u>Bypassing Frozen WoW Post-Update Phases</u></a></li>
<li><a href="https://windows11.techidaily.com/6-ways-to-fix-minecrafts-exit-code-1-on-windows/"><u>6 Ways to Fix Minecraft's Exit Code: 1 on Windows</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-2024-approved-ion-air-pro-3-action-camera-review/"><u>[Updated] 2024 Approved  ION Air Pro 3 Action Camera Review</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-onedrive-failure-in-folder-addition-on-desktop-os/"><u>Bypassing OneDrive Failure in Folder Addition on Desktop OS</u></a></li>
<li><a href="https://windows11.techidaily.com/5-creative-routes-to-activate-windows-utilities/"><u>5 Creative Routes to Activate Windows Utilities</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/selecting-the-perfect-youtube-video-downloader-for-mp4-for-2024/"><u>Selecting the Perfect YouTube Video Downloader for MP4 for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-radiance-reimagined-top-video-tools-list/"><u>[Updated] Radiance Reimagined  Top Video Tools List</u></a></li>
<li><a href="https://windows11.techidaily.com/building-a-linux-ecosystem-within-hyper-v-windows-environment/"><u>Building a Linux Ecosystem Within Hyper-V Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-administrative-status-via-windows-terminal/"><u>Achieve Administrative Status via Windows Terminal</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ultimate-guide-to-downloading-youtube-on-ios/"><u>Your Ultimate Guide to Downloading YouTube on iOS</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-ideal-summertime-screens-top-10-family-vacay-movies/"><u>[New] Ideal Summertime Screens  Top 10 Family Vacay Movies</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-how-to-make-a-youtube-reaction-video-in-2024/"><u>[New] How to Make a YouTube Reaction Video, In 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-the-ultimate-fcpx-shortcut-guide-40-time-saving-keys/"><u>New 2024 Approved The Ultimate FCPX Shortcut Guide 40 Time-Saving Keys</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-are-product-assessments-online-content-sold/"><u>[New] Are Product Assessments Online Content Sold?</u></a></li>
<li><a href="https://windows11.techidaily.com/android-meets-windows-easy-synching-protocol/"><u>Android Meets Windows: Easy Synching Protocol</u></a></li>
<li><a href="https://windows11.techidaily.com/asus-challenges-rog-ally-with-innovative-designs/"><u>ASUS Challenges ROG Ally with Innovative Designs</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-premier-band-live-streams/"><u>In 2024, Premier Band Live Streams</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-11-key-inactivity-issues/"><u>Addressing Windows 11 Key Inactivity Issues</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/leveraging-tech-for-better-facebook-live-records/"><u>Leveraging Tech for Better Facebook Live Records</u></a></li>
</ul></div>
