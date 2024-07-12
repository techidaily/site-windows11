---
title: Install and Enhance Edge Security with the Defender Application Guard From MS
date: 2024-07-11T21:18:06.123Z
updated: 2024-07-12T21:18:06.123Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Install and Enhance Edge Security with the Defender Application Guard From MS
excerpt: This Article Describes Install and Enhance Edge Security with the Defender Application Guard From MS
keywords: Secure Edge Installation,Defender APG Benefits,Edge Protection Boost,APG Upgrade Guide,Enhance Edge Security,Microsoft Edge Guard,Advanced Edge Defense
thumbnail: https://thmb.techidaily.com/eb0b88fc8ea01a6f57ac593062a230bcd4f411a04c405e68f58f5857acd450ec.jpg
---

## Install and Enhance Edge Security with the Defender Application Guard From MS

 If you work in an environment that deals with sensitive data, then you must install Microsoft Defender Application Guard for Edge on your Windows computer. It opens Microsoft Edge in an isolated container so that suspicious or potentially harmful files will not be able to access trusted resources.

 In this guide, we will show you different methods to install Microsoft Defender Application Guard for Edge on your Windows 11 PC.

## 1\. How to Install Microsoft Defender Application Guard Using Windows Settings

 Installing Microsoft Defender Application Guard for Edge on your Windows PC is a quick and simple process. You just need to access the Windows Settings app, and then follow a few steps to enable the feature. Here's how to do it:

1. Press**Win + I** on your keyboard to open the Settings app. See our guide if you're [having trouble opening Windows Settings](https://www.makeuseof.com/fixes-unable-to-open-windows-settings/) .
2. On the left, click**Privacy and security** , and then on the right, click**Windows Security** .
3. Under the Protection areas, click**App & browser control** .
4. Then, on the Windows Security page, click the**Install Microsoft Defender Application Guard** link below Isolated browsing.  
![How to Install Microsoft Defender Application Guard Using Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/how-to-install-microsoft-defender-application-guard-using-windows-security.jpg)
5. If you see the UAC prompt on your computer screen, click Yes to confirm your action.
6. Next, check the box next to**Microsoft Defender Application Guard** and click**OK** .  
![Add Microsoft Defender Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/add-microsoft-defender-application-guard-for-edge.jpg)

 Once you perform the above steps, you must need to restart your computer to finish installing the requested changes. This way you can install the feature on your computer.

 If you have already installed Microsoft Defender Application Guard and want to uninstall it, the process is quite easy. All you need to do is follow the steps mentioned above until you reach the Windows Security page.

![Uninstall Microsoft Defender Application Guard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-defender-application-guard.jpg)

 Then click**Uninstall Microsoft Defender Application Guard** and uncheck the box next to**Microsoft Defender Application Guard** .

## 2\. How to Install Microsoft Defender Application Guard Using the Control Panel

 You can also install Microsoft Defender Application Guard for Edge on your Windows 11 computer using the classic Control Panel. Here's how to do it:

1. Search for**Control Panel** in the Start menu and open it.
2. Select**Programs and Features** from the menu items.
3. From the left pane, click**Turn Windows features on or off** .
4. Tick the box next to**Microsoft Defender Application Guard** and click**OK** .
5. Then restart your computer for the changes to take effect.

 In order to uninstall it, follow the same steps and uncheck the box next to**Microsoft Defender Application Guard** . Then click OK and reboot your computer to save the changes.

## 3\. How to Install Microsoft Defender Application Guard Using Local Group Policy Editor

 Another method to install Microsoft Defender Application Guard is through the Local Group Policy Editor. This method requires some advanced knowledge and might be challenging for some users but don't worry; if you follow the steps, you'll be okay.

 You'll also find that if you're on Windows Home, the below instructions won't work. This is because it's not enabled by default on Home. Fortunately, you can learn [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before you perform this fix.

 Follow the steps given below to install Microsoft Defender Application Guard using Local Group Policy Editor:

1. Press the**Win + R** shortcut key to launch the Run window.
2. Type**gpedit.msc** in the dialog box and press Enter or click**OK** .
3. In the Local Group Policy Editor window, navigate to the following path:  
`Computer Configuration > Administrative Templates > Windows Components > Microsoft Defender Application Guard`
4. Now go to the right pane and double-click on the **Turn On Microsoft Defender Application Guard in Managed Mode** policy.  
![Microsoft Defender Application Guard Using Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/microsoft-defender-application-guard-using-local-group-policy-editor.jpg)
5. This will open a new window, select the**Enabled** checkbox.
6. You can now go to**Options** and change it to**2** or**3** .  
![Turn on Microsoft Defender Application Guard in Managed Mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/turn-on-microsoft-defender-application-guard-in-managed-mode.jpg)
7. Once done, click**Apply** and then**OK** to save all the changes you have made.

 Now restart your computer and Microsoft Defender Application Guard will be installed on your PC.

## 4\. How to Install Microsoft Defender Application Guard Using Command Prompt

 If you are comfortable with the command prompt, you can also install Microsoft Defender Application Guard using the Command Prompt. Follow the steps here:

1. Right-click on Start and select**Run** from the menu list.
2. In the dialog box, type**cmd** and then press**Ctrl + Shift + Enter** on your keyboard.
3. If UAC prompts, click**Yes** to run the command prompt with admin access.
4. In the elevated command prompt window, type the following command and hit Enter:  
`Dism /online /Enable-Feature /FeatureName:"Windows-Defender-ApplicationGuard"​`
5. When Command Prompt asks you to restart, type**Y** and hit Enter to complete this operation.

 Once you restart your computer, Microsoft Defender Application Guard will be installed and ready to use. In case you want to uninstall the Application Guard, you can do so by using the same command prompt steps. Just make sure to run the following command instead:

`Dism /online /Disable-Feature /FeatureName:"Windows-Defender-ApplicationGuard"​`

 At this point, you may be asked to restart your computer. To proceed, type**Y** and press Enter. After restarting, you will have successfully installed Microsoft Defender Application Guard on your system.

## 5\. How to Install Microsoft Defender Application Guard Using Windows PowerShell

 Alternatively, you can use Windows PowerShell to install Microsoft Defender Application Guard for Edge on Windows 11\. This is also a command-line process but is different from the Command Prompt application. Follow these steps to install Microsoft Defender Application Guard using Windows PowerShell:

1. Open Windows PowerShell with admin access. If you need help, see our guide on [how to open Windows PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. Once you're in the PowerShell window, type the following command:  
`Enable-WindowsOptionalFeature -Online -FeatureName "Windows-Defender-ApplicationGuard"​`
3. Now press**Enter** on your keyboard to execute it.
4. When PowerShell asks you to restart your computer, type**Y** and hit Enter.

 Upon restarting the computer, you will have successfully installed Microsoft Defender Application Guard on your system. Now you can make sure that you are browsing in a secure and protected environment.

 If you ever want to uninstall Microsoft Defender Application Guard, you can do so by using the same PowerShell command. Just make sure to use**Disable** \-WindowsOptionalFeature instead of**Enable** . So, this way the command should look like this:

`Disable-WindowsOptionalFeature -Online -FeatureName "Windows-Defender-ApplicationGuard"​`

 Now press Enter on your keyboard to execute the command and restart your system. Once it is done, Microsoft Defender Application Guard will be uninstalled from your PC.

 This is how you can install and uninstall Microsoft Defender Application Guard using Windows PowerShell on Windows 11.

## Get Microsoft Defender Application Guard and Stay Safe

 Microsoft Defender Application Guard uses isolated secure containers to protect your device from malicious files and threats. In the above-described methods, you can follow the installation steps and remain safe while browsing the web.


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
<li><a href="https://windows11.techidaily.com/microsofts-profit-mechanisms-in-windows-11/"><u>Microsoft's Profit Mechanisms in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-windows-backup-to-original-settings/"><u>Restoring Windows Backup to Original Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/sweep-away-unrecognized-interfaces-with-these-tips/"><u>Sweep Away Unrecognized Interfaces with These Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/resolve-null-audio-output-on-windows-pcs/"><u>Resolve Null Audio Output on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/revival-rituals-for-lost-windows-unlocking-off-screen-restoration-in-win-1011-6-essentials/"><u>Revival Rituals for Lost Windows: Unlocking Off-Screen Restoration in Win 10/11 (6 Essentials)</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-driver-verifier-management-in-windows-11/"><u>Guide: Driver Verifier Management in Windows 11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/twitters-number-one-video-trends/"><u>Twitter's Number One Video Trends</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-oneplus-ace-2-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my OnePlus Ace 2 Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-sourav-joshis-income-tactics-the-future-of-monetizing-content/"><u>2024 Approved  Sourav Joshi's Income Tactics  The Future of Monetizing Content</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/-cuts-big-impact-top-editors-for-youtube-short-videos-on-mobile/"><u>Short Cuts, Big Impact  Top Editors for YouTube Short Videos on Mobile</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-halt-video-size-bloat-convert-fb-vids-to-720p-and-1080p-mp4/"><u>[New] Halt Video Size Bloat  Convert FB Vids to 720P & 1080P MP4</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-saving-your-personalized-powertoys-profile/"><u>Steps for Saving Your Personalized PowerToys Profile</u></a></li>
<li><a href="https://windows11.techidaily.com/resurrect-your-pcs-absent-controllers/"><u>Resurrect Your PC's Absent Controllers</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-eradicate-0x80072af9-on-windows/"><u>Steps to Eradicate 0X80072AF9 on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-the-mystery-recovering-copilot-in-ws11/"><u>Solving the Mystery: Recovering Copilot In WS11</u></a></li>
<li><a href="https://windows11.techidaily.com/resurrecting-lost-wi-fi-link-windows-edition/"><u>Resurrecting Lost Wi-Fi Link: Windows Edition</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-professional-ppt-recording-tactics-and-tricks/"><u>[Updated] In 2024, Professional PPT Recording Tactics and Tricks</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-edit-like-a-pro-10-must-know-tips-for-newbies-for-2024/"><u>[Updated] Edit Like a Pro  10 Must-Know Tips for Newbies for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-discover-the-best-video-trimmers-for-desktop-and-online-use/"><u>Updated Discover the Best Video Trimmers for Desktop and Online Use</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-5-essential-ios-downloader-apps-for-your-favorite-facebook-videos/"><u>[New] In 2024, 5 Essential iOS Downloader Apps for Your Favorite Facebook Videos</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-top-stock-photos-their-journey-to-internet-fame/"><u>In 2024, Top Stock Photos  Their Journey to Internet Fame</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-recover-windows-audio-glitches/"><u>Steps to Recover Windows Audio Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-windows-unlocking-diskusage-insights-for-storage-management/"><u>Maximizing Windows: Unlocking DiskUsage Insights for Storage Management</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-some-of-the-top-sites-to-replace-a-sky-background-in-videos/"><u>Updated 2024 Approved Some of the Top Sites to Replace a Sky Background in Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-approach-for-removing-steams-dns-information/"><u>Stepwise Approach for Removing Steam's DNS Information</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/step-by-step-lyric-video-crafting-with-lyric-video-maker/"><u>Step-by-Step Lyric Video Crafting with Lyric Video Maker</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/maximize-your-macs-audio-potential-with-these-podcast-apps-for-2024/"><u>Maximize Your Mac's Audio Potential with These Podcast Apps for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-microsoft-store-eliminating-code-x80072f30-errors/"><u>Mastering the Microsoft Store: Eliminating Code X80072F30 Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/identify-and-solve-hidden-disk-space-problems-in-windows/"><u>Identify & Solve Hidden Disk Space Problems in Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-card-on-iphone-6-plus-online-without-jailbreak-by-drfone-ios/"><u>How to Unlock SIM Card on iPhone 6 Plus online without jailbreak</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-restore-playback-from-black-screen/"><u>Steps to Restore Playback From Black Screen</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-pinnacle-advice-for-creating-stellar-music-videos/"><u>In 2024, Pinnacle Advice for Creating Stellar Music Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-glances-to-your-favorites-windows-shortcuts-uwp-apps/"><u>Quick Glances to Your Favorites: Windows Shortcuts (UWP Apps)</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-win11-upgrades-eradicate-error-0xc1900101/"><u>Streamline Your Win11 Upgrades, Eradicate Error 0xC1900101</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-tricks-to-increase-viewership-on-your-tiktok-unboxing-sessions/"><u>[New] Tricks to Increase Viewership on Your TikTok Unboxing Sessions</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-preventing-google-chromes-autopilot-tabs/"><u>Guide to Preventing Google Chrome's Autopilot Tabs</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-vidma-screen-capture-a-thorough-examination-and-alternative-options/"><u>[New] Vidma Screen Capture - A Thorough Examination & Alternative Options</u></a></li>
<li><a href="https://windows11.techidaily.com/reboot-to-normalcy-windows-11-permissions-reversal/"><u>Reboot to Normalcy: Windows 11 Permissions Reversal</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-past-onedrive-sign-in-snags-with-windows-steps/"><u>Navigate Past OneDrive Sign-In Snags with Windows Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/staying-current-the-impact-of-additional-yearly-patches-on-your-pc/"><u>Staying Current: The Impact of Additional Yearly Patches on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-browsing-security-with-win-11-ms-defender-guard/"><u>Optimize Browsing Security with Win 11 MS Defender Guard</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-unravel-exception-reached-on-windows-pcs/"><u>Steps to Unravel 'Exception Reached' On Windows PCs</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/in-2024-youtube-movie-maker-pro-tips-for-efficient-editing/"><u>In 2024, YouTube Movie Maker Pro Tips for Efficient Editing</u></a></li>
<li><a href="https://extra-tips.techidaily.com/reimagine-your-screen-mastery-of-win11-backdrops/"><u>Reimagine Your Screen  Mastery of Win11 Backdrops</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-unlocking-potential-snapchat-insights-for-companies/"><u>In 2024, Unlocking Potential  Snapchat Insights for Companies</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-vivo-s18-pro-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Vivo S18 Pro If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-echoes-of-celebration-finding-the-perfect-applaud-tones-for-2024/"><u>New Echoes of Celebration Finding the Perfect Applaud Tones for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-ragnors-rebirth-warriors-alliance/"><u>In 2024, Ragnor's Rebirth  Warriors Alliance</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-0xc0000142-problems-on-win11win7/"><u>Overcoming 0XC0000142 Problems on Win11/Win7</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-galleryguide-adjusting-post-dimensions-in-instagram/"><u>[Updated] 2024 Approved  GalleryGuide  Adjusting Post Dimensions in Instagram</u></a></li>
<li><a href="https://windows11.techidaily.com/rewiring-success-restoring-troubleshooters-in-windows-11/"><u>Rewiring Success: Restoring Troubleshooters in Windows 11</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-chromebook-video-editing-mastery-how-to-use-any-app-regardless-of-os-for-2024/"><u>Updated Chromebook Video Editing Mastery How to Use Any App, Regardless of OS for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-11s-0x8007045d-bluescreen-troubleshooting/"><u>Navigating Through Windows 11'S 0X8007045D Bluescreen Troubleshooting</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-and-secure-file-saving-ultimate-remedies-in-windows-11/"><u>Swift and Secure File Saving: Ultimate Remedies in Windows 11</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/ultimate-guide-to-exclusive-youtube-gamers-intros-freepaid/"><u>Ultimate Guide to Exclusive YouTube Gamers' Intros (Free/Paid)</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/divide-and-conquer-a-step-by-step-guide-to-splitting-videos-in-windows-live-movie-maker-for-2024/"><u>Divide and Conquer A Step-by-Step Guide to Splitting Videos in Windows Live Movie Maker for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-microsoft-store-issues-error-code-0x80072f17-fix/"><u>Resolving Microsoft Store Issues: Error Code 0X80072f17 Fix</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-spotify-link-reset-strategies/"><u>Mastering Windows Spotify Link Reset Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-to-rectify-opengl-error-3-in-win11-pcs/"><u>Swift Solutions to Rectify OpenGL Error #3 in Win11 PCs</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-taming-the-wildscape-techniques-for-subtracting-unwanted-audio-disturbances/"><u>2024 Approved Taming The Wildscape Techniques for Subtracting Unwanted Audio Disturbances</u></a></li>
<li><a href="https://windows11.techidaily.com/strip-onedrive-of-microsoft-id-integration-in-windows/"><u>Strip OneDrive of Microsoft ID Integration in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-overcome-onedrive-authentication-xyz-error-on-windows-11/"><u>Steps to Overcome ONEDRIVE Authentication XYZ Error on Windows 11</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-detailed-tutorial-shifting-audio-tracks-within-multimedia-files/"><u>Updated In 2024, Detailed Tutorial Shifting Audio Tracks Within Multimedia Files</u></a></li>
<li><a href="https://windows11.techidaily.com/proven-strategies-to-enhance-wireless-and-cable-networks-on-windows/"><u>Proven Strategies to Enhance Wireless and Cable Networks on Windows</u></a></li>
</ul></div>
