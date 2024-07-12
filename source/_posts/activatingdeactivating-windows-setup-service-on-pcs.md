---
title: Activating/Deactivating Windows Setup Service on PCs
date: 2024-07-11T21:53:45.517Z
updated: 2024-07-12T21:53:45.517Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Activating/Deactivating Windows Setup Service on PCs
excerpt: This Article Describes Activating/Deactivating Windows Setup Service on PCs
keywords: Activate WinSetupService,Deactivate WinSetupService,Enable Windows Service,Disable Windows Service,Adjust Setup Service,Windows Service Control,Service Modification Windows
thumbnail: https://thmb.techidaily.com/6bec6b49ef7ec1e5a2c1ba4a21123755124d462c63be6599c5bbe4007fea7d1f.jpg
---

## Activating/Deactivating Windows Setup Service on PCs

 Are you looking for a way to disable the Windows Installer Service on your device? This essential component of your operating system performs all necessary installation processes, but can sometimes interfere with other programs.

 Fortunately, there are three ways in which it can be disabled—using the Windows Service tool, Group Policy Editor, or Registry Editor. Check out our guide below to learn how.

## 1\. Use Windows Services

 Windows services are critical programs that typically initiate when you start your computer. It runs silently in the background and provides essential features to run the operating system. If you're looking to enable or disable Windows Installer service using this tool, do the following.

 To begin, press**Win + R** on your keyboard to launch the Run dialog box. In the text box, type**services.msc** , and hit enter. This will open the Services window.

![Disable Windows Installer Service Using Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-services-window.jpg)

 In the window that opens, scroll down until you find**Windows Installer** service then double-click on it for a properties window to open.

 Once you're in the Properties window, click the**Startup type** drop-down menu and select**Automatic** . Now move over towards the**Service status** section and click**Stop** .

![Disable Windows Installer Service Using Windows Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-windows-services.jpg)

 After you've done that, click**Apply** and then**OK** to save the changes. You have now successfully disabled the Windows Installer service on Windows 11.

 If you ever need to re-enable the service, follow the same procedure and click**Start** in the Service status section.

## 2\. Use Local Group Policy Editor

 You can also use the group policy editor to enable or disable the Windows Installer service on your Windows computer system. However, it is important to note that this tool only works on Windows Pro and Enterprise editions. Therefore, if you are using Windows Home Edition, you must first [activate the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 To disable the service using the group policy editor, do the following:

1. Click on Start and type in**gpedit.msc** , then press**Enter** to [launch the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) .
2. On the left side of the window, navigate to the path:  
`Computer Configuration > Administrative Templates > Windows Components > Windows Installer`
3. Now move to the right and double-click on the policy named**Turn off Windows Installer** .  
![Disable Windows Installer Service Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-group-policy.jpg)
4. In the window that opens, select**Enabled** in the radio box.
5. Under Options, click the drop-down menu and select**Always** .
6. Then click**Apply** and**OK** to save changes.

 That's all there is to it. The Windows Installer service will now be disabled on your system. To re-enable it, simply follow the same steps, but set "Turn off Windows Installer" to**Not Configured** .

## 3\. Use the Registry Editor

 Registry Editor is another method you can use to enable or disable the Windows Installer service on any version of Windows, even Home Edition. But make sure to proceed with caution as any incorrect changes can corrupt your system and force you to reinstall Windows. So be mindful and remember to back up your registry before making any modifications.

 To enable or disable this service using Registry Editor, follow these steps:

1. Press**Win + X** , type**regedit** , and press**Enter** to launch the Registry Editor. To learn more, see our guide on how to [open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. If prompted with a UAC warning, click**Yes** to continue.
3. Now once you're in, navigate to the following path:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\msiserver`
4. In the right panel, double-click on**Start** and change its value from**2** to**4** .  
![Disable Windows Installer Service Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-registry-editor.jpg)

 Once you put the Value data, make sure the Base is set to**Hexadecimal** , then click**OK** . Now close the registry editor and restart your computer for the changes to take effect.

## Turning Off the Windows Installer Service Made Easy

 If Windows Installer Service is creating issues or hindering another application, you can easily turn it off with one of the three methods outlined in our guide. See which method works best for you and get back to what matters most.


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
<li><a href="https://android-frp.techidaily.com/a-quick-guide-to-samsung-galaxy-s21-fe-5g-2023-frp-bypass-instantly-by-drfone-android/"><u>A Quick Guide to Samsung Galaxy S21 FE 5G (2023) FRP Bypass Instantly</u></a></li>
<li><a href="https://windows11.techidaily.com/brightening-up-dull-desktop-windows-appearance/"><u>Brightening Up Dull Desktop Windows Appearance</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-retrace-footsteps-android-film-inversion/"><u>2024 Approved  Retrace Footsteps  Android Film Inversion</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/beyond-fun-the-subtle-messages-in-snapchat-emojis/"><u>Beyond Fun  The Subtle Messages in Snapchat Emojis</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-complete-blueprint-for-professional-edits-in-gopro-studio/"><u>The Complete Blueprint for Professional Edits in GoPro Studio</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-cpu-utilization-checkers/"><u>Advanced CPU Utilization Checkers</u></a></li>
<li><a href="https://windows11.techidaily.com/accessible-windows-for-new-users-and-learners/"><u>Accessible Windows for New Users & Learners</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-expert-review-of-avs-video-editor-the-good-the-bad-and-the-ugly/"><u>Updated In 2024, Expert Review of AVS Video Editor The Good, the Bad, and the Ugly</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-your-cursors-appearance-in-windows-os/"><u>Boosting Your Cursor's Appearance in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/actions-for-correcting-windows-11-0x800f0922-error/"><u>Actions for Correcting Windows 11 0X800F0922 Error</u></a></li>
<li><a href="https://windows11.techidaily.com/chkdsk-sfc-and-dism-windows-tools-unveiled-and-explained/"><u>CHKDSK, SFC & DISM: Windows Tools Unveiled and Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/build-your-windows-own-text-to-speech-converter-with-whisper-and-autohotkey/"><u>Build Your Window's Own Text-To-Speech Converter with Whisper and AutoHotkey</u></a></li>
<li><a href="https://windows11.techidaily.com/bootstrapping-your-windows-version-patch-edition/"><u>Bootstrapping Your Windows Version: Patch Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-personalized-settings-alomwares-pathway-to-customization/"><u>Achieve Personalized Settings - AlomWare's Pathway to Customization</u></a></li>
<li><a href="https://windows11.techidaily.com/1719309112975-stuck-in-chrome-unfreeze-windows-11-with-simple-fixes/"><u>Stuck in Chrome? Unfreeze Windows 11 with Simple Fixes!</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-boot-speed-with-simple-steps-in-windows-11-setup/"><u>Boosting Boot Speed with Simple Steps in Windows 11 Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/christmas-theme-makeovers-for-windows-11/"><u>Christmas Theme Makeovers for Windows 11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-seamless-time-stamp-integration-on-youtube-videos/"><u>In 2024, Seamless Time-Stamp Integration on YouTube Videos</u></a></li>
<li><a href="https://howto.techidaily.com/11-ways-to-fix-it-when-my-infinix-zero-30-5g-wont-charge-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Ways to Fix it When My Infinix Zero 30 5G Wont Charge | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-catch-or-beat-sleeping-snorlax-on-pokemon-go-for-poco-x5-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Catch or Beat Sleeping Snorlax on Pokemon Go For Poco X5 Pro | Dr.fone</u></a></li>
<li><a href="https://location-fake.techidaily.com/all-must-knows-to-use-fake-gps-go-location-spoofer-on-apple-iphone-11-drfone-by-drfone-virtual-ios/"><u>All Must-Knows to Use Fake GPS GO Location Spoofer On Apple iPhone 11 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-linux-and-windows-gap-with-shared-tools/"><u>Bridging Linux & Windows Gap with Shared Tools</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-instant-immersion-mixing-tunes-in-facebook-narratives/"><u>[New] 2024 Approved  Instant Immersion  Mixing Tunes in Facebook Narratives</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-mcuicnt-file-execution-failure-on-windows/"><u>Addressing McUICnt File Execution Failure on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/batch-folder-generation-in-windows-11-for-efficiency-boost/"><u>Batch Folder Generation in Windows 11 for Efficiency Boost</u></a></li>
<li><a href="https://windows11.techidaily.com/a-detailed-guide-turning-off-windows-update-restrictions/"><u>A Detailed Guide: Turning Off Windows Update Restrictions</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-exploring-the-world-of-animated-lenses-in-snapchat/"><u>[Updated] In 2024, Exploring the World of Animated Lenses in Snapchat</u></a></li>
<li><a href="https://windows11.techidaily.com/1719374504396-dive-into-the-depth-of-complete-screenshots-via-windows-snipping-tool/"><u>Dive Into the Depth of Complete Screenshots via Windows' Snipping Tool.</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-epic-launcher-on-pcs-a-quick-guide/"><u>Accelerating Epic Launcher on PCs: A Quick Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/becoming-an-expert-learner-with-these-7-windowing-strategies/"><u>Becoming an Expert Learner with These 7 Windowing Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-game-session-rejection-by-steams-vac/"><u>Avoiding Game Session Rejection by Steam's VAC</u></a></li>
<li><a href="https://windows11.techidaily.com/bold-stealth-for-your-wi-fi-on-windows-pcs/"><u>Bold Stealth for Your Wi-Fi on Windows PCs</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/scaling-your-income-with-beauty-tutorials-for-2024/"><u>Scaling Your Income with Beauty Tutorials for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-average-gain-for-youtubers-per-ad-exposure-for-2024/"><u>[New] Average Gain for YouTubers per Ad Exposure for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-infusing-energy-youtube-music-in-film-and-media-projects/"><u>2024 Approved  Infusing Energy  YouTube Music in Film and Media Projects</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-top-10-streaming-software-in-the-gaming-world/"><u>[New] Top 10 Streaming Software in the Gaming World</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-printer-usage-errors-efficiently/"><u>Bypassing Printer Usage Errors Efficiently</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-exploring-video-edits-is-inshot-top-choice/"><u>[New] Exploring Video Edits  Is InShot Top Choice?</u></a></li>
<li><a href="https://activate-lock.techidaily.com/the-10-best-tools-to-bypass-icloud-activation-lock-from-apple-iphone-12-pro-you-should-try-out-by-drfone-ios/"><u>The 10 Best Tools to Bypass iCloud Activation Lock From Apple iPhone 12 Pro You Should Try Out</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-overview-using-bluescreenview/"><u>A Comprehensive Overview: Using BlueScreenView</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-quick-guide-on-recording-gotomeeting-chats-with-ease/"><u>[Updated] 2024 Approved  Quick Guide on Recording GoToMeeting Chats with Ease</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-2024-approved-a-comprehensive-walkthrough-to-modify-videos-speaker-output/"><u>Updated 2024 Approved A Comprehensive Walkthrough to Modify Videos Speaker Output</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-instagrams-secret-fine-tuning-fcpx-for-high-aspect-videos/"><u>[Updated] 2024 Approved  Instagram's Secret  Fine-Tuning FCPX for High Aspect Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-errors-manage-deps-for-virtualbox-on-windows/"><u>Avoid Errors: Manage Deps for VirtualBox on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-security-the-art-of-updating-gpo-in-windows/"><u>Boosting Security: The Art of Updating GPO in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-windows-prefixes-with-microsoft-services/"><u>Bridging Windows Prefixes with Microsoft Services</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-unintentional-tiktok-update-restore-past-content/"><u>[Updated] In 2024, Unintentional TikTok Update – Restore Past Content</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-scripting-sci-fi-elements-time-and-space-in-action/"><u>2024 Approved  Scripting Sci-Fi Elements  Time & Space in Action</u></a></li>
<li><a href="https://windows11.techidaily.com/breakdown-how-law-filters-transform-your-windows-experience/"><u>Breakdown: How LAW Filters Transform Your Windows Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-the-cycle-how-to-fix-your-disconnected-ps4-remote-control-on-windows/"><u>Breaking the Cycle: How to Fix Your Disconnected PS4 Remote Control on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/applying-local-group-policies-to-individual-users-windows-11-guide/"><u>Applying Local Group Policies to Individual Users: Windows 11 Guide</u></a></li>
<li><a href="https://change-location.techidaily.com/ways-to-trade-pokemon-go-from-far-away-on-samsung-galaxy-s24-ultra-drfone-by-drfone-virtual-android/"><u>Ways to trade pokemon go from far away On Samsung Galaxy S24 Ultra? | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-8-best-multiple-video-call-and-chat-tools-for-conference-and-friends/"><u>2024 Approved  8 Best Multiple Video Call & Chat Tools for Conference and Friends</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-capture-perfection-reviewing-the-best-5-hd-webcams-with-audio-for-2024/"><u>[Updated] Capture Perfection  Reviewing The Best 5 HD Webcams with Audio for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/aging-gracefully-with-your-grans-windows-machine/"><u>Aging Gracefully with Your Gran’s Windows Machine</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-chaos-with-these-three-windows-reset-methods/"><u>Bypass Chaos with These Three Windows Reset Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-list-of-10-ways-to-fine-tune-windows-11-screens/"><u>A Comprehensive List of 10 Ways to Fine-Tune Windows 11 Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-stealthed-elements-in-windows-11-ui/"><u>Accessing Stealthed Elements in Windows 11 UI</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-windows-11-app-launches/"><u>Accelerating Windows 11 App Launches</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-panic-recover-lost-data-with-these-steps/"><u>Avoid Panic, Recover Lost Data with These Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-the-gap-for-stuck-files-in-windows-11-ecosystems/"><u>Bridging the Gap for Stuck Files in Windows 11 Ecosystems</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-through-windows-tpm-restrictions-with-ease/"><u>Breaking Through Windows TPM Restrictions with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-back-windows-photo-viewer-a-1111-edition-guide/"><u>Bring Back Windows Photo Viewer: A 11/11 Edition Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/a-closer-look-at-devhome-enhancing-windows-11-performance/"><u>A Closer Look at DevHome: Enhancing Windows 11 Performance</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713965119495-updated-this-article-talks-about-pixel-art-wallpapers-it-gives-examples-of-different-pixel-art-to-show-you-how-to-customize-your-own-pixel-art-wallpapers-an/"><u>Updated This Article Talks About Pixel Art Wallpapers. It Gives Examples of Different Pixel Art to Show You How to Customize Your Own Pixel Art Wallpapers, and How to Make a Pixel Art Gif on Filmora for 2024</u></a></li>
</ul></div>
