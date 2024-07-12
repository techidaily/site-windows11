---
title: 5 Tips for Turning Around a Frozen Windows Hello System
date: 2024-07-11T21:54:45.663Z
updated: 2024-07-12T21:54:45.663Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 5 Tips for Turning Around a Frozen Windows Hello System
excerpt: This Article Describes 5 Tips for Turning Around a Frozen Windows Hello System
keywords: Fix Frozen WinHello,Revive HoloSign-In,Windows Hello Recovery,Sign-In Fix Guide,Unfreeze Windows Login,Rehab Windows Hello,Quick WinLogin Fix
thumbnail: https://thmb.techidaily.com/f86f99b6d8051e2301c0b59b59f0f49d547931786fc3f8df51522ef8e8e5d47b.jpg
---

## 5 Tips for Turning Around a Frozen Windows Hello System

 Using a fingerprint scanner is perhaps the most convenient way to log in to your Windows computer. It not only eliminates the need to type in a complex password or PIN every time you want to access your computer but also saves you time. But what if Windows Hello fingerprint authentication stops working on your computer?

 Fortunately, there are several ways to fix this annoying issue. So, let’s dive in and explore what you should do when Windows Hello fingerprint login isn’t working.

## 1\. Remove and Re-Register Your Fingerprint

 Your first step is to remove your Windows Hello fingerprint and register it again. This may sound basic, but it is one of the most straightforward ways to get your fingerprint reader to work again. Here are the steps you can follow.

1. Press **Win + I** to open the Settings app.
2. Head to **Accounts > Sign-in options**.
3. Under the **Windows Hello** section, click the **Remove** button.  
![Windows Sign-in Options window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Remove-Windows-Hello-Fingerprint-1.jpg)
4. Once removed, click the **Set up** button and follow the on-screen instructions to register your fingerprint again.

 If the issue persists or if you are unable to remove and re-add your fingerprint due to the "This option is currently unavailable" error on the Windows Hello page, there may be a problem with the Biometric drivers on your PC.

## 2\. Reinstall the Biometric Device Driver

 Biometric drivers on your PC help Windows communicate with your PC's fingerprint scanner. If these drivers are outdated or malfunctioning, you may run into problems.

 Most of the time, you can fix the problem by simply uninstalling and reinstalling the driver on your PC. Here’s how you can go about it.

1. Right-click on the **Start** icon to open the Power User menu.
2. Select **Device Manager** from the list.
3. Expand **Biometric devices**.  
![Biometric Driver selected in Device Manager window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Biometric-Driver-in-Device-Manager-1.jpg)
4. Right-click on your fingerprint scanner device and select **Uninstall device**.
5. Select **Uninstall** to confirm.

 Additionally, you should also expand the **Universal Serial Bus Controllers** section in the Device Manager and look for any entries with a yellow exclamation. If you find any, right-click on them one by one and select **Uninstall device** to remove them.

 Restart your PC after completing the above steps and check if the issue still occurs.

## 3\. Run the Hardware and Devices Troubleshooter

 Windows 10 and 11 include a number of [troubleshooters for resolving various system-related issues](https://www.makeuseof.com/windows-11-troubleshooters/). In this case, you should run the Hardware and Devices troubleshooter. It will scan your computer’s fingerprint scanner for any issues and attempt to fix them.

 Follow these steps to run the Hardware and Devices troubleshooter on Windows:

1. Press **Win + R** to open the Run dialog box.
2. Type **msdt.exe -id DeviceDiagnostic** in the Open field and press **Enter**.
3. In the Hardware and Devices window, click **Next**.  
![Hardware and Devices Troubleshooter Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Hardware-and-Devices-Troubleshooter-Window.jpg)

 Wait for Windows to diagnose any issues with your computer. If any issues are detected, follow the on-screen instructions to apply the recommended fixes.

## 4\. Turn Off Fast Startup

 Fast Startup is a handy Windows feature that speeds up your PC's boot time after shutdown. However, this feature might sometimes prevent Windows from loading properly. When this happens, the fingerprint scanner may not work on your Windows 10 or 11 PC.

 Use one of the many ways to [disable Fast Startup on your Windows computer](https://www.makeuseof.com/windows-11-turn-on-or-off-fast-startup/) and see if that gets the fingerprint scanner to work.

## 5\. Configure Windows Biometric Service to Start Automatically

 The Windows Biometric Service is an essential program for Windows Hello, as it captures and manages your fingerprint data. Ideally, the service should start automatically every time Windows boots. However, this might not happen if the service is not configured correctly.

 Use these steps to configure the Windows Biometric Service:

1. Open the **Services** app using the search menu.
2. Scroll down to locate the **Windows Biometric Service** on the list.
3. Right-click on it and select **Properties**.
4. Click the drop-down menu to change the **Startup type** to **Automatic**.
5. Hit **Apply** followed by **OK**.  
![Windows Biometric Service Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Windows-Biometric-Service-Properties.jpg)

 Restart your PC after this. Following that, you should be able to sign in with your fingerprint.

## 6\. Enable Biometrics via the Local Group Policy Editor

 Another reason why Windows Hello fingerprint sign-in may not work is if the feature is disabled from the Local Group Policy. It's important to note that Group Policy Settings are only available on Professional, Education, and Enterprise editions of Windows. If you are on Windows Home, you don't need to worry about this step.

 To enable fingerprint authentication via the Local Group Policy Editor, use these steps:

1. Press **Win + S** to open the search menu.
2. Type **gpedit.msc** in the search box and press **Enter** to [open the Local Group Policy Editor](https://www.makeuseof.com/tag/open-local-group-policy-editor-windows/).
3. Use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Components > Biometrics**.
4. Check if all the policies within the Biometrics folder are enabled. If not, double-click each policy one by one and set them to **Enabled**.  
![Biometric Policies in Local Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Local-Group-Policy-Editor-Window-1.jpg)

 Restart your PC one more time and check if the issue is still there.

## 7\. Create a New User Account

 An issue with your current user account can also cause certain Windows features to stop working. This usually happens when your user account files get corrupted. If you suspect that to be the case, you can [create and switch to a new user account](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) to fix the issue. Here’s how you can go about it.

1. Press **Win + I** to open the Settings app.
2. Head to **Accounts > Other users**.
3. Click the **Add account** button.
4. In the Microsoft account window, click on **I don't have this person's sign-in information** and follow the on-screen prompts to create a new user account.  
![Microsoft Account Sign In Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Microsoft-Account-Sign-In-Window.jpg)

 Set up Windows Hello fingerprint login for your new user account and see if you can sign in with your fingerprint.

## 8\. Perform a System Restore

 If the fingerprint not working issue only occurred recently, you can use System Restore to revert Windows to a previous state. This will allow you to undo any changes that may have caused the issue. Note that this is only possible if you have previously [enabled System Restore on your PC](https://www.makeuseof.com/windows-11-enable-system-restore/).

 Follow these steps to perform a system restore on Windows:

1. Press **Win + S** to open the search menu.
2. Type **Create a restore point in the search box** and press **Enter**.
3. Under the **System Protection** tab, click on **System Restore**.
4. Click **Next**.
5. Select a restore point before the issue first appeared and hit **Next**.
6. Review all the details one more time before hitting **Finish**.  
![System Restore Dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/System-Restore-Dialog.jpg)

 Windows will restart and revert to the specified restore point. After that, the fingerprint should work as before.

## 9\. Install the Latest Windows Updates

 Microsoft regularly releases software updates for Windows 10 and Windows 11 to add new features, improve performance, and—crucially for our purposes—fix bugs. If the fingerprint not working issue is caused by a system bug, updating Windows to its most recent version should help.

 You can check for new updates by going to the **Windows Update** tab in the **Settings** app. Download and install any pending updates on your PC. Hopefully, this will resolve the issue.

## Fixing Windows Hello's Fingerprint Check

 It’s annoying when your PC's fingerprint scanner stops working all of a sudden. However, that shouldn’t force you to use your password or PIN to sign in to your computer.

 We hope one of the methods mentioned above has helped and you are able to sign in with your fingerprint again. However, if all else fails, you may want to consider resetting your Windows computer.

 Fortunately, there are several ways to fix this annoying issue. So, let’s dive in and explore what you should do when Windows Hello fingerprint login isn’t working.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-recording.techidaily.com/new-key-components-to-a-smooth-watching-experience-facebook-livestream/"><u>[New] Key Components to a Smooth Watching Experience  Facebook Livestream</u></a></li>
<li><a href="https://windows11.techidaily.com/why-microsoft-family-safety-matters-for-parents/"><u>Why Microsoft Family Safety Matters for Parents</u></a></li>
<li><a href="https://windows11.techidaily.com/reinventing-tech-windows-leap-from-version-11/"><u>Reinventing Tech: Windows' Leap From Version 11</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-perfecting-the-art-of-slow-motion-in-snapchat-stories/"><u>[Updated] Perfecting the Art of Slow Motion in Snapchat Stories</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-tecno-camon-30-pro-5g-to-mac-drfone-by-drfone-android/"><u>How to Mirror Tecno Camon 30 Pro 5G to Mac? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-financial-gains-with-w11-pro-key-deals/"><u>Unlock Financial Gains with W11 Pro Key Deals</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-edges-continuous-desktop-appearance/"><u>Resolving Edges' Continuous Desktop Appearance</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-unlock-your-creative-potential-top-7-hidden-tiktok-emojis/"><u>2024 Approved  Unlock Your Creative Potential  Top 7 Hidden TikTok Emojis</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-resolving-winirq-conflicts-for-clear-audio/"><u>Decoding and Resolving WinIRQ Conflicts for Clear Audio</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-the-ultimate-guide-screen-recording-minecraft-with-your-macos/"><u>[Updated] In 2024, The Ultimate Guide  Screen Recording Minecraft with Your MacOS</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-something-you-may-need-to-know-about-rap-music-for-2024/"><u>New Something You May Need To Know About Rap Music for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-complication-windows-11-plus-nvidia-x0001/"><u>Rectifying Complication: Windows 11 + Nvidia X0001</u></a></li>
<li><a href="https://win11.techidaily.com/ideal-apps-to-monitor-win-os-temperatures/"><u>Ideal Apps to Monitor Win OS Temperatures</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/2024-approved-mastering-multimedia-production-on-chromebook-with-audacity-setup-and-uninstall-guide/"><u>2024 Approved Mastering Multimedia Production on Chromebook with Audacity - Setup & Uninstall Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-launch-hacks-opening-windows-11-apps-faster/"><u>Quick Launch Hacks: Opening Windows 11 Apps Faster</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-terminal-for-quake-in-windows/"><u>Configuring Terminal for Quake in Windows</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-discovering-the-stars-that-sparkle-in-your-domains-social-space/"><u>[Updated] Discovering the Stars that Sparkle in Your Domain's Social Space</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-xbox-mic-issues-on-windows-1111-pro/"><u>Resolving Xbox Mic Issues on Windows 11/11 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-machine-wattage-determining-computational-power-use/"><u>Windows Machine Wattage: Determining Computational Power Use</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-win-1011-zoom-fatal-error-1132/"><u>Resolving Win 10/11 Zoom Fatal Error 1132</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-tips-for-efficient-toolbar-usage-in-microsoft-win11-pcm/"><u>Advanced Tips for Efficient Toolbar Usage in Microsoft Win11 PCM</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-your-experience-using-w11s-auto-hdr/"><u>Tailoring Your Experience: Using W11's Auto HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-search-tweaks-enhancing-your-experience/"><u>Windows 11'S Search Tweaks: Enhancing Your Experience</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-3-ways-to-fake-gps-without-root-on-xiaomi-14-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Fake GPS Without Root On Xiaomi 14 | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-unveiling-the-best-tiktok-marketing-techniques/"><u>[Updated] Unveiling the Best TikTok Marketing Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/simple-steps-for-screen-position-changes/"><u>Simple Steps for Screen Position Changes</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-a-unique-win11-screenscape-display/"><u>Setting Up a Unique Win11 Screenscape Display</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-soar-in-popularity-with-key-seo-strategies-for-your-youtube-content/"><u>[New] In 2024, Soar in Popularity with Key SEO Strategies for Your YouTube Content</u></a></li>
<li><a href="https://windows11.techidaily.com/unsticking-wows-initialization-on-pcs/"><u>Unsticking WoW's Initialization on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-unblock-windows-nvidia-setup-window/"><u>Strategies to Unblock Windows Nvidia Setup Window</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-partitioned-presence-ranking-splittest-cam/"><u>2024 Approved  Partitioned Presence  Ranking Splittest Cam</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-in-depth-list-of-best-virtual-playgrounds/"><u>[New] 2024 Approved  In-Depth List of Best Virtual Playgrounds</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-access-permissions-biometrics-on-w11-domains/"><u>Streamlining Access Permissions: Biometrics on W11, Domains</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-the-secret-sauce-for-stellar-telegram-campaigns-for-2024/"><u>[New] The Secret Sauce for Stellar Telegram Campaigns for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-windows-11-in-place-update-mastery/"><u>Step-by-Step Windows 11, In-Place Update Mastery</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-mastering-android-device-manager-the-ultimate-guide-to-unlocking-your-zte-axon-40-lite-device-by-drfone-android/"><u>In 2024, Mastering Android Device Manager The Ultimate Guide to Unlocking Your ZTE Axon 40 Lite Device</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-get-the-best-facebook-mp3-converter-online-top-picks/"><u>New 2024 Approved Get the Best Facebook MP3 Converter Online Top Picks</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-in-2024-archive-aesthetics-merge-infinite-gratis-storage-with-elite-subscriptions/"><u>[Updated] In 2024, Archive Aesthetics  Merge Infinite, Gratis Storage with Elite Subscriptions</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-eliminate-startup-disruption-due-to-winscombsvc-errors/"><u>Quick Fix: Eliminate Startup Disruption Due to WinScombSvc Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/responding-to-click-failures-in-windows-11-environment/"><u>Responding to Click Failures in Windows 11 Environment</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-a-network-locked-honor-x9b-phone-by-drfone-android/"><u>How to Unlock a Network Locked Honor X9b Phone?</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-error-code-0x80071a90-in-windows/"><u>Unraveling Error Code 0X80071A90 in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-and-fix-windows-autoshrink-issue/"><u>Troubleshoot & Fix Windows' Autoshrink Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-for-no-sound-during-system-tests/"><u>Remedy for No Sound During System Tests</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-unpredictable-power-estimator-display-on-windows-11/"><u>Correcting Unpredictable Power Estimator Display on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-error-0x80072f8f-0x20000-in-windows/"><u>Troubleshooting Error 0X80072f8f - 0X20000 in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/cut-the-clutter-quickly-reduce-programs-with-system-tray-keys/"><u>Cut the Clutter: Quickly Reduce Programs with System Tray Keys</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-a-thorough-analysis-elevating-video-recording-with-obs/"><u>In 2024, A Thorough Analysis  Elevating Video Recording with OBS</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-windows-11-camera-app-error-0xa00f425d-fixes/"><u>Disabling Windows 11 Camera App Error 0xA00F425D Fixes</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fake-the-location-to-get-around-the-mlb-blackouts-on-vivo-y100i-power-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Fake the Location to Get Around the MLB Blackouts on Vivo Y100i Power 5G | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-perfect-pan-and-tilt-for-clearer-captures/"><u>[New] Perfect Pan & Tilt for Clearer Captures</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-making-the-cursor-more-noticeable-in-windows/"><u>Step-by-Step: Making the Cursor More Noticeable in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-pointer-design-in-microsoft-systems/"><u>Customize Pointer Design in Microsoft Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/tricks-to-launch-websites-after-installation/"><u>Tricks to Launch Websites After Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-the-process-anydesk-fixes-for-windows-users/"><u>Simplifying the Process: AnyDesk Fixes for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/6-quick-ways-to-fix-the-powerpoint-cant-save-file-error-in-windows-11/"><u>6 Quick Ways to Fix the PowerPoint Can't Save File Error in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-to-successful-os-transition-in-virtual-worlds/"><u>Unveiling the Secrets to Successful OS Transition in Virtual Worlds</u></a></li>
<li><a href="https://windows11.techidaily.com/top-secure-password-vaults-elevating-windows-11-standards/"><u>Top Secure Password Vaults Elevating Windows 11 Standards</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-guide-on-how-to-change-your-apple-id-email-address-on-iphone-14-plus-by-drfone-ios/"><u>In 2024, Guide on How To Change Your Apple ID Email Address On iPhone 14 Plus</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-at-learning-7-efficient-techniques-for-windows/"><u>Winning at Learning: 7 Efficient Techniques for Windows</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-remove-device-supervision-from-your-apple-iphone-15-plus-drfone-by-drfone-ios/"><u>In 2024, Remove Device Supervision From your Apple iPhone 15 Plus | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/betrayed-by-touch-the-latest-vulnerabilities-in-windows-fingerprint-tech/"><u>Betrayed by Touch: The Latest Vulnerabilities in Windows Fingerprint Tech</u></a></li>
<li><a href="https://windows11.techidaily.com/curating-edthemes-experience-on-windows-11/"><u>Curating EdThemes Experience on Windows 11</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-for-people-wanting-to-mock-gps-on-samsung-galaxy-z-fold-5-devices-drfone-by-drfone-virtual/"><u>In 2024, For People Wanting to Mock GPS on Samsung Galaxy Z Fold 5 Devices | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-how-to-record-movies-on-pc-mac-and-smartphones-in-2024/"><u>[New] How to Record Movies on PC, Mac, and Smartphones, In 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/sharpening-performance-with-optimized-news-and-video-consumption/"><u>Sharpening Performance with Optimized News & Video Consumption</u></a></li>
</ul></div>
