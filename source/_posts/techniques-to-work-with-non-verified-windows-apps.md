---
title: Techniques to Work with Non-Verified Windows Apps
date: 2024-07-11T22:03:01.261Z
updated: 2024-07-12T22:03:01.261Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Techniques to Work with Non-Verified Windows Apps
excerpt: This Article Describes Techniques to Work with Non-Verified Windows Apps
keywords: Unverified WinApp Tools,Bypassing Verification,Safe Execution in Win,Secure Windows App Use,Workarounds for Non-Verified,Authenticity in WinApps,Stable Run Non-Certified,Unverified WinApp Tools,Bypassing Verification,Safe Execution in Win,Secure Windows App Use,Workarounds for Non-Verified,Authenticity in WinApps,Stable Run Non-Certified
thumbnail: https://thmb.techidaily.com/91dc46c6cc6911e9915591791566cdaadd16613fc33817ba0857c51273b662cd.JPG
---

## Techniques to Work with Non-Verified Windows Apps

 Have you encountered the error"the app you're trying to install isn't a Microsoft-verified app"while installing an app? The error occurs if you have configured your system to only install apps from the Microsoft Store. You could have set this permission on purpose, or it might have been set by default.

 Other than that, a corrupted Microsoft Store cache, installing an app from an unofficial source, and enabling Windows S mode can also cause the error. Below, you will find a few checks and fixes you should apply to resolve the error and install the app successfully.

## 1\. Install the App From the Microsoft Store

 Considering you get the error when downloading apps outside the Microsoft Store, it makes sense to first check if the same app is available there. If the app is available, you can download it from there, and there won't be any need to go through advanced troubleshooting.

 Therefore, [open the Microsoft Store](https://www.makeuseof.com/windows-open-microsoft-store/) and search for the app. If you find the app in the store, click the **Get** button to install it. However, if the app isn't available in the store and can only be downloaded from another source, ensure it is safe to download.

## 2\. Make Sure the App You're Downloading Is Safe

 Microsoft doesn't allow untrusted publishers to list their apps on the Microsoft Store. If you haven't found the app on the store, it could be unsafe and infect your computer. Thus, ensure that the app you want to download is secure before downloading.

 To determine if an app is safe, copy its download link and paste it into [VirusTotal's URL search box](https://www.virustotal.com/gui/home/url). After that, press **Enter**.

![Check the Authenticity of a Software by Entering its URL in VirusTotal’s Official Website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/1-check-the-authenticity-of-a-software-by-entering-its-url-in-virustotal-s-official-website.jpg)

 If the scanner doesn't find any problems with the download link, it's probably safe. After ensuring that, you can apply the remaining fixes to enable app installation outside the store.

## 3\. Change the Operating System App Settings

 Microsoft cares about the safety and security of its Windows users. To facilitate that, Windows offers a feature that blocks the installation of apps outside the Microsoft Store. The downside of enabling this feature is that it prevents users from installing popular and safe applications from the web.

 When users try to install an app with this restriction turned on, Windows will likely display an error message saying that the app isn't a Microsoft-verified app. Therefore, to avoid encountering the error described above, you should allow Windows to install apps outside the Microsoft Store.

 To modify the app permissions on Windows 10, follow the steps below:

1. Open the **Settings** app.
2. Open **Apps** settings and select **Apps and Features** from the left sidebar.
3. Select **Anywhere** from the dropdown menu under **Choose where to get apps**.

 To modify app permissions on Windows 11, open the **Settings** app, select the **Apps** tab, and then go to **Advanced app settings**.

![Go to Advanced Apps Settings in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/2-go-to-advanced-apps-settings-in-windows-settings-app.jpg)

 Select **Anywhere** from the dropdown menu next to **Choose where to get apps**.

![Select Anywhere From the Dropdown Menu Next to Choose Where to Get Apps Option in Apps Settings in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/3-select-anywhere-from-the-dropdown-menu-next-to-choose-where-to-get-apps-option-in-apps-settings-in-windows-settings-app.jpg)

## 4\. Turn Off the App Install Control Policy

 The App Install Control is a Microsoft Defender SmartScreen feature that prevents users from installing apps outside the Microsoft Store. It does this to prevent users from infecting their devices with third-party applications.

 Therefore, you should turn off this feature to remove any restrictions. To turn it off, follow these steps:

1. Open the Local Group Policy Editor. To do this, check out [how to open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) if you're not using Windows Home edition, and learn [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) if you are.
2. Navigate to **Computer Configuration > Administrative Templates > Windows Components > Windows Defender SmartScreen > Explorer**.  
![Go to Explorer Folder by Navigating to the Path in Windows Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/4-go-to-explorer-folder-by-navigating-to-the-path-in-windows-local-group-policy-editor.jpg)
3. Open the policy for **Configure App Install Control**.
4. Select **Disabled** to turn off this feature.  
![Disable the Policy for Configure App Install Control in Windows Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/5-disable-the-policy-for-configure-app-install-control-in-windows-local-group-policy-editor.jpg)

## 5\. Change the App Install Control Permission in the Registry Editor

 To modify the App Install Control permissions via the Registry Editor, follow the below steps:

1. Open the Registry Editor.
2. Navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer**.  
![Go to Explorer Folder by Navigating to the Path in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/6-go-to-explorer-folder-by-navigating-to-the-path-in-windows-registry-editor.jpg)
3. Right-click on **Explorer** and select **New > String value**.  
![Create New String Value in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/7-create-new-string-value-in-windows-registry-editor.jpg)
4. Name this new value **"AicEnabled."**  
![Name the Newly Created String Value AicEnabled in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/8-name-the-newly-created-string-value-aicenabled-in-windows-registry-editor.jpg)
5. Double-click on the newly created string and type "**Anywhere"** in the **Value data** field.  
![Type Anywhere in the Value Data Field of Newly Created String in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/9-type-anywhere-in-the-value-data-field-of-newly-created-string-in-windows-registry-editor.jpg)
6. Restart the computer for the changes to take effect.

 If the above Registry tweak does not resolve the issue, turn off S mode.

## 6\. Disable Windows S Mode

 Windows S mode is primarily the most secure environment you can get in Windows. It mainly serves as a means of protecting your children and keeping sensitive documents away from prying eyes.

 When this mode is active, users can only download apps from the Microsoft Store, can't use the command line or code editors, and can't modify the Windows Registry Editor.

 Therefore, if you have recently bought a new device and this mode is enabled there by default, Windows will probably throw the error if you attempt to install any app outside the store. Therefore, you should make sure it isn't enabled and disable it if it is.

 To determine whether your device is running S mode, open the **Settings** app, select the **System** tab on the left, and open the **About** page.

 If the S mode is enabled on your device, you'll see it there. If the feature is active, turn it off by following these steps:

1. Open the **Settings** app.
2. Navigate to the **System** tab and go to **Activation**.
3. Click on **Go to the store** under **Switch to Windows 11 Home/Pro**, which will take you to the Microsoft Store page where you can opt out of S mode.
4. Click the **Get** button and follow the on-screen instructions to get out of S mode.

## 7\. Run the Windows Store Apps Troubleshooter

 If the Windows S mode isn't enabled, and you haven't restricted your operating system from downloading apps from outside Microsoft, the error could be caused by an underlying issue with the Microsoft Store. To ensure this is not the case, you should run the Windows Store Apps troubleshooter, which is a built-in tool for troubleshooting issues with the Store.

 If you've never run the troubleshooter before, refer to our guide on [how to run a troubleshooter on Windows 10 or 11](https://www.makeuseof.com/run-troubleshooter-windows-10-11/).

## Successfully Install Third-Party Applications Again on Windows

 Microsoft blocks the installation of third-party apps for your security, but it's pointless if it prevents you from installing vital apps. Hopefully, you now better understand why the Microsoft Store presents the "the app you're trying to install isn't a Microsoft-verified app" error. Following the fixes above will enable you to download the apps from unofficial sources.

 Have you encountered the error"the app you're trying to install isn't a Microsoft-verified app"while installing an app? The error occurs if you have configured your system to only install apps from the Microsoft Store. You could have set this permission on purpose, or it might have been set by default.

 Other than that, a corrupted Microsoft Store cache, installing an app from an unofficial source, and enabling Windows S mode can also cause the error. Below, you will find a few checks and fixes you should apply to resolve the error and install the app successfully.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://ai-video-apps.techidaily.com/updated-create-stunning-videos-top-music-enabled-apps-for-android-and-ios-for-2024/"><u>Updated Create Stunning Videos Top Music-Enabled Apps for Android and iOS for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/improve-file-selection-techniques-activating-windows-11-boxes/"><u>Improve File Selection Techniques: Activating Windows 11 Boxes</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-remove-the-show-more-options-entry-from-the-context-menu-on-windows-11/"><u>How to Remove the Show More Options Entry From the Context Menu on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-epochal-passphrase-problem-in-windows-os/"><u>Deciphering “Epochal Passphrase Problem in Windows OS”</u></a></li>
<li><a href="https://windows11.techidaily.com/get-to-safety-six-steps-to-entering-safe-mode-in-windows-11/"><u>Get to Safety: Six Steps to Entering Safe Mode in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-11s-hidden-error-code-0xc1900101/"><u>Unveiling Windows 11'S Hidden Error Code #0xC1900101</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-mystery-of-mouse-controls-on-windows-11/"><u>Unlock the Mystery of Mouse Controls on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reinvigorate-the-essential-wsreset-process/"><u>How to Reinvigorate the Essential WSReset Process</u></a></li>
<li><a href="https://windows11.techidaily.com/harness-window-11-a-productivity-playbook/"><u>Harness Window 11: A Productivity Playbook</u></a></li>
<li><a href="https://windows11.techidaily.com/changing-network-address-translation-types-simplified-for-wins-oses/"><u>Changing Network Address Translation Types Simplified for Wins OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-pathways-to-successful-office-activation/"><u>Clearing Pathways to Successful Office Activation</u></a></li>
<li><a href="https://windows11.techidaily.com/winphone-users-decide-between-unison-and-phone-link-apps/"><u>WinPhone Users: Decide Between Unison and Phone Link Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-non-operational-windows-defrag-tool/"><u>Troubleshooting Non-Operational Windows Defrag Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/1719349405273-say-no-to-incompatibility-quick-solutions-for-vistawindows-7-users/"><u>Say No to Incompatibility: Quick Solutions for Vista/Windows 7 Users.</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/supreme-graphics-power-for-4k-gamers-only/"><u>Supreme Graphics Power  For 4K Gamers Only</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-11s-insufficient-uninstall-rights/"><u>Fixing Windows 11'S Insufficient Uninstall Rights</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-offline-setting-up-on-disconnected-pcs/"><u>Win11 Offline: Setting Up on Disconnected PCs</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-augmenting-realities-for-better-outcomes/"><u>[Updated] Augmenting Realities for Better Outcomes</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-windows-11-homespace-options/"><u>Accessing Windows 11 Homespace Options</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-obs-studio-basics-full-guide-to-ps4-game-recording/"><u>[Updated] 2024 Approved  Obs Studio Basics - Full Guide to PS4 Game Recording</u></a></li>
<li><a href="https://windows11.techidaily.com/convenience-at-a-click-discover-how-to-enable-gestures-on-edge-windows-11/"><u>Convenience at a Click: Discover How to Enable Gestures on Edge (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-the-absence-of-dxgidll-in-new-os-windows-11/"><u>Mending the Absence of Dxgi.dll in New OS, Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-windows-11s-admin-tools/"><u>Exploring Windows 11'S Admin Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/triumph-over-troubled-windows-credentials/"><u>Triumph over Troubled Windows Credentials</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-to-revive-winget-in-windows-profiles/"><u>Expert Tips to Revive Winget in Windows Profiles</u></a></li>
<li><a href="https://windows11.techidaily.com/triumph-over-microsoft-teams-stumbling-block-80080300-on-w11/"><u>Triumph over Microsoft Teams' Stumbling Block #80080300 on W11</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-action-to-freeze-damaged-windows-pins/"><u>Immediate Action to Freeze-Damaged Windows PINs</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-the-ultimate-fcp-guide-5-editing-tips-every-creator-should-know/"><u>New 2024 Approved The Ultimate FCP Guide 5 Editing Tips Every Creator Should Know</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-mastering-comfortable-virtual-realities/"><u>[New] Mastering Comfortable Virtual Realities</u></a></li>
<li><a href="https://fix-guide.techidaily.com/motorola-g54-5g-camera-not-working-unexpected-error-fix-it-now-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Motorola G54 5G Camera Not Working Unexpected Error? Fix It Now | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-windows-steam-performance-preventing-zero-speed-slowdowns/"><u>Elevate Windows Steam Performance: Preventing Zero-Speed Slowdowns</u></a></li>
<li><a href="https://windows11.techidaily.com/extend-the-time-windows-11-spends-in-shutdown-with-ongoing-jobs/"><u>Extend the Time Windows 11 Spends in Shutdown with Ongoing Jobs</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-scheduling-zoom-conferences-for-android-users/"><u>2024 Approved  Scheduling Zoom Conferences for Android Users</u></a></li>
<li><a href="https://windows11.techidaily.com/win11s-0x8007045d-an-effective-resolution-blueprint/"><u>Win11's 0X8007045D: An Effective Resolution Blueprint</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-user-experience-through-gpos-in-windows-11-and-11/"><u>Customizing User Experience Through GPOs in Windows 11 & 11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-bypass-icloud-activation-lock-with-imei-code-on-your-iphone-15-by-drfone-ios/"><u>In 2024, Bypass iCloud Activation Lock with IMEI Code On your iPhone 15</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-improve-auditory-experience-through-crossfade-adjustments-for-2024/"><u>New Improve Auditory Experience Through Crossfade Adjustments for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-the-windows-lsa-disablement-warning/"><u>Bypassing the Windows LSA Disablement Warning</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-unplayable-file-challenge/"><u>Addressing Windows' Unplayable File Challenge</u></a></li>
<li><a href="https://windows11.techidaily.com/effortlessly-upgrading-windows-11-in-place/"><u>Effortlessly Upgrading Windows 11 in Place</u></a></li>
<li><a href="https://windows11.techidaily.com/7-crucial-blunders-every-windows-11-novice-must-avoid/"><u>7 Crucial Blunders Every Windows 11 Novice Must Avoid</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-unlock-efficient-video-editing-6-adobe-premiere-hacks-you-need-to-know/"><u>New 2024 Approved Unlock Efficient Video Editing 6 Adobe Premiere Hacks You Need to Know</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-xiaomi-redmi-note-12-5g-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your Xiaomi Redmi Note 12 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-correct-the-internal-error-on-windows-1111-pro/"><u>Methods to Correct the Internal Error on Windows 11/11 Pro</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/how-to-speed-up-video-with-lightworks-video-editor-for-2024/"><u>How To Speed Up Video With Lightworks Video Editor for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-sonic-overlay-for-serene-scenery-on-screens/"><u>[Updated] Sonic Overlay for Serene Scenery on Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-icon-positioning-in-windows/"><u>Mastering Icon Positioning in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/curing-unable-to-retrieve-settings-issue-with-geforce-experience-on-windows-11/"><u>Curing Unable to Retrieve Settings Issue with GeForce Experience on Windows 11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/perfecting-presentations-adopt-the-ezvide-screencast-method-for-2024/"><u>Perfecting Presentations  Adopt the EZvide Screencast Method for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-command-control-on-windows-with-sudo/"><u>Maximizing Command Control on Windows with Sudo</u></a></li>
</ul></div>
