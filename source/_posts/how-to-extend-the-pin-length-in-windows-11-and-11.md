---
title: How to Extend the PIN Length in Windows 11 & 11
date: 2024-07-11T21:22:39.097Z
updated: 2024-07-12T21:22:39.097Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Extend the PIN Length in Windows 11 & 11
excerpt: This Article Describes How to Extend the PIN Length in Windows 11 & 11
keywords: Windows 11 Pin Length,Extend Windows 11 PIN,Increase Windows 11 Security,Customizing Windows 11 PIN,Windows 11 Unlock Methods,Personalize Windows 11 Login,Enhancing Windows 11 PIN Security
thumbnail: https://thmb.techidaily.com/14af88c4727edfc68754682f8d9e5a16b4632ead51b56f451896cf5d83dd52e4.jpg
---

## How to Extend the PIN Length in Windows 11 & 11

 Windows Hello enables users to sign into Windows 11/10 accounts with PINs. That feature restricts users to four-character PINs by default. There isn’t an option available within the Change your PIN box to set a longer PIN that includes more than four characters.

 So, it doesn’t seem users can set longer, more secure PINs for signing in to Windows. However, there are two ways to set a new minimum PIN length for the Hello PIN sign-in method. This is how you can extend the PIN length in Windows 10 and 11\.

## How to Extend the PIN Length by Editing the Registry

 Windows 11/10 Home doesn’t have any built-in setting for extending the minimum PIN length. So, many users will have to extend PIN length by creating a new PINComplexity registry key. Then you can set a new minimum PIN length value within that key. You can extend the Windows Hello PIN length by editing the registry as follows:

1. To view the file finder tool, press that utility’s **Win + S** keyboard shortcut.
2. Type **regedit** in the file search box and select its result to [open Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. Enter this path inside Registry Editor’s address bar and press **Return**:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\`
4. If the Microsoft key doesn’t have a PassportForWork subkey, you’ll need to set one up. To do so, right-click on the Microsoft key and select **New** \> **Key**.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/new-key-options3.jpg)
5. Type **PassportForWork** in the new key’s text box.

1. Next, right-click on the **PassportForWork** key to select the **New** and **Key** options on Registry Editor’s context menu.
2. Enter **PINComplexity** inside the key’s text box to set that name.
3. Right-click the **PINComplexity** key to select **New** \> **DWORD (32-bit) Value**.
4. Enter **MinimumPINLength** in the DWORD text box.  
![The MinimumPINLength DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/minimum-pin-length-dword.jpg)
5. Double-click the new **MinimumPINLength** DWORD you’ve created.

1. Select the **Decimal** option.
2. Then input a number higher than four in the **Value data** box and click **OK**. The value you enter there will be the new minimum character length for the Windows Hello PIN.  
![The Edit DWORD window for the MinimumPINLength DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-dword-window4.jpg)
3. You can also set a maximum PIN length. To do so, right-click **PINComplexity** again and select the **DWORD (32-bit) Value** option on the **New** submenu.
4. Type **MaximumPINLength** into the DWORD’s text box.  
![A MaximumPINLength DWORD text box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/maximum-pin-length-text-box.jpg)
5. Double-click **MaximumPINLength** to view the **Value box** for that DWORD.
6. Click on the **Decimal** radio button.
7. Enter a number higher than the one set for the **MinimumPINLength** DWORD and select **OK**.  
![The Edit DWORD window for the MaximumPINLength DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-dword-window-for-maximum-pin-length.jpg)
8. Finally, exit the Registry Editor window and restart your PC.

 Now you’ll see an “organization requires that you change your PIN message” when you try to sign in with the PIN usually entered. Click **OK** to view some options for setting a new PIN. Then input a longer identification number with the minimum number of characters required inside the **New** and **Confirm** PIN boxes.

![The change your PIN message](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/sign-in-message.jpg)

 If you’ve not set a Windows Hello PIN before, you can do so via Settings. Our guide to [setting a PIN in Windows](https://www.makeuseof.com/setup-remove-pin-windows-11/) includes instructions for how to do so. Your PIN must have the minimum number of characters set with the **PINComplexity** registry key.

## How to Extend the PIN Length With Group Policy Editor

 Windows Pro and Enterprise editions have a Group Policy Editor tool that includes options for setting minimum and maximum PIN lengths. So, you don’t need to manually edit the registry to set a minimum PIN length if you can access Group Policy Editor. This is how to extend Windows Hello’s PIN length with Group Policy Editor:

1. Press **Windows** logo key + **R** and enter **gpedit.msc** in Run.
2. Click on Run’s **OK** button to [access Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
3. Double-click on **Computer Configuration** in the left sidebar.
4. Next, double-click **Administrative Templates** to extend it.  
![Administrative Templates in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/administrative-templates.jpg)
5. Then click the arrow by **System** and select **PIN Complexity**.

1. Double-click on the **Minimum PIN Length** policy.  
![The PIN Complexity policy settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/pin-complexity.jpg)
2. Click the **Enabled** radio button to activate a **Minimum PIN Length** box.
3. Then input a higher value in the **Minimum PIN Length** box.  
![The Minimum PIN Length policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/minimum-pin-length-policy.jpg)
4. Select **Apply** and **OK** to set the new PIN length policy.
5. You can also set a max PIN length much the same by clicking the **Maximum PIN Length** policy, selecting **Enabled**, and inputting a new value. Then click on **Apply** and **OK** within the Maximum PIN length window.  
![The Maximum PIN Length policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/maximum-pin-length-policy.jpg)

## Extend Your Windows PIN to Make It More Secure

 Extending the minimum PIN length for logging in to Windows with one of the methods above is a good security measure. The longer your Windows Hello PIN is, the more secure your PC will be. However, an overly long PIN will be harder to remember. So, don’t make your PIN too long!

 Windows Hello also enables users to set alternative biometric authentication. Fingerprint or retina authentication types are more advanced Windows Hello features than PINs. However, you’ll need a PC that supports such biometric security features to enable them.

 So, it doesn’t seem users can set longer, more secure PINs for signing in to Windows. However, there are two ways to set a new minimum PIN length for the Hello PIN sign-in method. This is how you can extend the PIN length in Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/addressing-windows-printer-issues-a-guide-for-unresponsive-print-commands/"><u>Addressing Windows Printer Issues: A Guide for Unresponsive Print Commands.</u></a></li>
<li><a href="https://windows11.techidaily.com/a-deep-dive-into-winning-windows-captures-with-printscreen-or-snip-tool/"><u>A Deep Dive Into Winning Windows Captures with Printscreen or Snip Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/best-practices-choosing-the-right-win-video-codec/"><u>Best Practices: Choosing the Right Win Video Codec</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-when-oneplus-ace-2-has-black-screen-of-death-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do When OnePlus Ace 2 Has Black Screen of Death? | Dr.fone</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-cut-edit-share-the-top-android-video-editing-apps-free-and-paid/"><u>Updated In 2024, Cut, Edit, Share The Top Android Video Editing Apps (Free and Paid)</u></a></li>
<li><a href="https://extra-information.techidaily.com/master-guide-collages-creation-made-easy/"><u>Master Guide  Collages Creation Made Easy</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-vivo-y100frp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Vivo Y100FRP Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/a-harmonious-symphony-taming-your-computers-audio-irqs/"><u>A Harmonious Symphony: Taming Your Computer’s Audio IRQs</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-velocity-ventures-discover-the-freshest-5-virtual-race-titles/"><u>[Updated] 2024 Approved  Velocity Ventures  Discover the Freshest 5 Virtual Race Titles</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/vocal-interaction-redefined-in-the-augmented-realm/"><u>Vocal Interaction Redefined in the Augmented Realm</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-frequency-focus-mac-sound-setup/"><u>[New] Frequency Focus  Mac Sound Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-application-support-limitations-on-windows-7/"><u>Addressing Application Support Limitations on Windows 7</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-edge-guards-camera-and-mic-use/"><u>Activating Edge Guards: Camera & Mic Use</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-inaccessible-router-settings-in-windows/"><u>Bypassing Inaccessible Router Settings in Windows</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-vimeo-create-how-to-edit-videos-on-vimeo-for-free/"><u>[Updated] 2024 Approved  Vimeo Create  How to Edit Videos on Vimeo for Free?</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-edge-browsing-performance-on-win10win11/"><u>Accelerating Edge Browsing Performance on Win10/Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-faulty-alerts-from-windows-10s-shield/"><u>Addressing Faulty Alerts From Windows 10'S Shield</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-overload-on-windows-applications-0x80860010/"><u>Bypassing Overload on Windows Applications (0X80860010)</u></a></li>
<li><a href="https://windows11.techidaily.com/asus-challenges-rog-ally-with-innovative-designs/"><u>ASUS Challenges ROG Ally with Innovative Designs</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-social-media-to-mp3-converter/"><u>[New] 2024 Approved  Social Media to Mp3 Converter</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-navigating-youtubes-revenue-tools-for-mobile-creators/"><u>2024 Approved  Navigating YouTube's Revenue Tools for Mobile Creators</u></a></li>
<li><a href="https://windows11.techidaily.com/1719306890834-key-collectors-rejoice-get-the-perfect-pair-of-keys-and-essential-windows-11-612lifetime/"><u>Key Collectors Rejoice – Get the Perfect Pair of Keys & Essential Windows 11, $6.12/Lifetime</u></a></li>
<li><a href="https://vp-tips.techidaily.com/perfecting-time-sync-in-video-postings-on-youtube-for-2024/"><u>Perfecting Time Sync in Video Postings on YouTube for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-webcam-hurdles-tackling-error-a00f4289-on-win11/"><u>Bypassing Webcam Hurdles - Tackling Error A00F4289 on Win11</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-poco-c65-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Poco C65? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/blackview-minipc-expansive-but-sluggish-storage/"><u>Blackview MiniPC: Expansive but Sluggish Storage</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-failed-rpc-calls-top-tips-for-windows-users/"><u>Addressing Failed RPC Calls: Top Tips for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-lost-extra-screen-in-w11/"><u>Addressing Lost Extra Screen in W11</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/omegle-exclusion-no-more-strategies-for-removal-from-the-blacklist/"><u>Omegle Exclusion No More Strategies for Removal From the Blacklist</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-strategic-boxes-opened-marketing-excellence/"><u>2024 Approved  Strategic Boxes Opened  Marketing Excellence</u></a></li>
<li><a href="https://windows11.techidaily.com/1719311224382-tackle-snip-and-sketch-obstacles-to-perfectly-capture-entire-screen/"><u>Tackle Snip & Sketch Obstacles to Perfectly Capture Entire Screen.</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-easy-ways-to-manage-your-motorola-g24-power-location-settings-drfone-by-drfone-virtual/"><u>In 2024, Easy Ways to Manage Your Motorola G24 Power Location Settings | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/adjust-brightness-slider-look-for-the-brightness-slider-under-system-or-personalization-tabs-in-settings/"><u>Adjust Brightness Slider: Look for the Brightness Slider Under 'System' Or 'Personalization' Tabs in Settings</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/the-best-free-video-editing-software-for-gaming-content-creators/"><u>The Best Free Video Editing Software for Gaming Content Creators</u></a></li>
<li><a href="https://windows11.techidaily.com/arrows-at-a-standstill-try-these-remedies/"><u>Arrows at a Standstill? Try These Remedies</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-pristine-videos-best-android-and-iphone-apps-for-watermarks-for-2024/"><u>[New] Pristine Videos  Best Android & iPhone Apps for Watermarks for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/building-a-linux-ecosystem-within-hyper-v-windows-environment/"><u>Building a Linux Ecosystem Within Hyper-V Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-frozen-wow-post-update-phases/"><u>Bypassing Frozen WoW Post-Update Phases</u></a></li>
<li><a href="https://windows11.techidaily.com/7-key-steps-to-overcome-google-chrome-profile-faults/"><u>7 Key Steps to Overcome Google Chrome Profile Faults</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-diving-deep-into-your-twitter-archive/"><u>2024 Approved  Diving Deep Into Your Twitter Archive</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-download-adobe-premiere-pro-cs6-for-mac-os-free-trial/"><u>Updated Download Adobe Premiere Pro CS6 for Mac OS - Free Trial</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-best-bgms-and-gifs-stylish-google-meet-backdrops-for-2024/"><u>[New] Best BGMs & GIFs  Stylish Google Meet Backdrops for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-advanced-strategies-for-capturing-fb-chats/"><u>[New] 2024 Approved  Advanced Strategies for Capturing FB Chats</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-innovative-audio-techniques-for-your-podcasts/"><u>In 2024, Innovative Audio Techniques for Your Podcasts</u></a></li>
<li><a href="https://windows11.techidaily.com/adapting-windows-11-multifaceted-monitor-wallpaper-strategy/"><u>Adapting Windows 11: Multifaceted Monitor Wallpaper Strategy</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-best-microphone-for-youtubers/"><u>[New] 2024 Approved  Best Microphone for YouTubers</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unlocking-visual-storytelling-with-your-canon-timelapse-toolkit/"><u>In 2024, Unlocking Visual Storytelling with Your Canon Timelapse Toolkit</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-sync-launch-sticky-notes-with-windows-start-up/"><u>Boosting Sync: Launch Sticky Notes with Windows Start-Up</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-undisclosed-screengrabbing-invisible-photography-on-snapchat/"><u>2024 Approved  Undisclosed ScreenGrabbing  Invisible Photography on Snapchat</u></a></li>
<li><a href="https://windows11.techidaily.com/balance-usage-and-energy-efficiency-with-automatic-rest-mode/"><u>Balance Usage & Energy Efficiency with Automatic Rest Mode</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-lasting-freedom-how-to-banish-youtube-shorts-permanently/"><u>[Updated] Lasting Freedom  How To Banish YouTube Shorts Permanently</u></a></li>
<li><a href="https://windows11.techidaily.com/cep-library-integration/"><u>CEP Library Integration</u></a></li>
<li><a href="https://howto.techidaily.com/bricked-your-nokia-c32-heres-a-full-solution-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Bricked Your Nokia C32? Heres A Full Solution | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-administrative-status-via-windows-terminal/"><u>Achieve Administrative Status via Windows Terminal</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-crafting-a-pro-sports-youtube-feed-on-macos-for-2024/"><u>[Updated] Crafting a Pro Sports YouTube Feed on MacOS for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/chrome-files-upload-hurdle-heres-how-to-clear-it-on-windows/"><u>Chrome Files Upload Hurdle? Here's How to Clear It on Windows</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-inter-app-playlist-exchange-made-simple/"><u>[Updated] Inter-App Playlist Exchange Made Simple</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/become-an-influencer-grow-by-a-thousand-on-instagrammonth-for-2024/"><u>Become an Influencer  Grow by a Thousand on Instagram/Month for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/x-professional-audio-toolkit-personal-computing-for-2024/"><u>X-Professional Audio Toolkit, Personal Computing for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/lock-your-vivo-y27-4g-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>Lock Your Vivo Y27 4G Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/bridging-platform-gaps-youtube-shorts-to-mp4-transformation-for-2024/"><u>Bridging Platform Gaps  YouTube Shorts to MP4 Transformation for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/7-essential-fixes-to-tackle-the-http-too-many-requests-issue-in-windows/"><u>7 Essential Fixes to Tackle the HTTP Too Many Requests Issue in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-overhauling-the-settings-app-in-win11/"><u>A Guide to Overhauling the Settings App in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-windows-11s-screen-capture-shortcut/"><u>Accessing Windows 11'S Screen Capture Shortcut</u></a></li>
<li><a href="https://windows11.techidaily.com/5-creative-routes-to-activate-windows-utilities/"><u>5 Creative Routes to Activate Windows Utilities</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-11-key-inactivity-issues/"><u>Addressing Windows 11 Key Inactivity Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-captioning-faults-in-win-10-systems/"><u>Addressing Captioning Faults in Win 10 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/breathe-life-into-dead-wi-fi-connections-on-windows-10-with-this-list/"><u>Breathe Life Into Dead Wi-Fi Connections on Windows 10 with This List</u></a></li>
<li><a href="https://windows11.techidaily.com/audio-capture-while-screen-recording-with-snipping-tool-max-156/"><u>Audio Capture While Screen Recording with Snipping Tool (Max 156)</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-fullscape-synergy-the-smart-mcn-picking-game/"><u>[Updated] In 2024, FullScape Synergy  The Smart MCN Picking Game</u></a></li>
</ul></div>
