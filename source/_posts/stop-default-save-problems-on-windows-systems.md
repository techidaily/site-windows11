---
title: Stop 'Default Save' Problems on Windows Systems
date: 2024-09-09T12:01:32.702Z
updated: 2024-09-10T12:01:32.702Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stop 'Default Save' Problems on Windows Systems
excerpt: This Article Describes Stop 'Default Save' Problems on Windows Systems
keywords: Stop Default Saves,Fix Save Issues,Win Save Errors,Prevent Save Glitches,Stop System Saves,Resolve Save Problems,Avoid Windows Save Failures
thumbnail: https://thmb.techidaily.com/9b6e560f5ae8bf8946a31c995d6c73a4779b962b2219e90738423fb3fbbee898.jpg
---

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137413/7443" target="_top" id="2137413">
  <img src="//a.impactradius-go.com/display-ad/7443-2137413" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137413/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Stop 'Default Save' Problems on Windows Systems

 Users have reported error 0x80070005 or 0x80070539 arises when they try to set new apps to save to different external drive locations with Settings. Those error codes have the same message that says, “We couldn’t set your default save location.” This means users can’t change the default save location for apps.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135405/19272" target="_top" id="2135405">
  <img src="//a.impactradius-go.com/display-ad/19272-2135405" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135405/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Set Your User Account to Administrator

 If you’re utilizing a standard Windows account, [change your user account type](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) to an administrative one. A standard user account will prevent you from applying any more complicated system changes. Changing the save location for apps is something you might need admin privileges for.

![The Account type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-account-type-window.jpg)

## 2\. Rename the WindowsApps Directory

 This error can arise because the WindowsApps folder where apps save is corrupted. Renaming the WindowsApps folder on the drive or partition you want to save apps can address such an issue. To do so, rename that folder as follows:

1. If you’re trying to set apps to save on an external drive, connect that hard drive to your PC.
2. [Open the File Explorer folder navigator](https://www.makeuseof.com/windows-open-file-explorer/) and click **This PC**.
3. Double-click the drive/partition you want to set as your default save location for apps.
4. Then, right-click on the WindowsApps folder and select its **Rename** context menu option. You should find that directory within the drive’s root directory.  
![The Rename option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-button.jpg)
5. Rename the folder to **WindowsApps.old** and press **Enter**.
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134233/18498" target="_top" id="2134233">
  <img src="//a.impactradius-go.com/display-ad/18498-2134233" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134233/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Thereafter, try changing the default save location for apps again via Settings.

 If that still doesn’t work, then proceed to the next resolution.

<!-- affiliate ads begin -->
<a href="https://smilemakers.pxf.io/c/5597632/2123901/26106" target="_top" id="2123901">
  <img src="//a.impactradius-go.com/display-ad/26106-2123901" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://smilemakers.pxf.io/i/5597632/2123901/26106" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Delete or Rename the WpSystem Folder

 Many users confirm that renaming or deleting the WpSystem folder fixes error 0x80070005\. WpSystem is a folder created to store app data. Try renaming that folder to **WpSystem.old** on the drive you can’t set to be a save location for apps, as outlined for the previous method. The WpSystem will be in the same directory as the WindowsApps folder.

 Alternatively, delete the WpSystem folder. You can [erase a file or folder in Explorer](https://www.makeuseof.com/windows-11-delete-select-files/) by right-clicking it and selecting **Delete**. If you can’t find that folder or this potential solution doesn’t work, try the next resolution.

![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-option.jpg)

## 4\. Set Full System Permission for the System Volume Folder

 Setting full permission for the System Volume folder is another confirmed fix for error 0x80070005\. Follow these steps to set full permission for the System Volume directory:

1. Go into File Explorer and click the three-dot **See more** menu > **Options**. In Windows 10, click **Options** on the **View** tab.
2. Select **View** on the Folder Options window.
3. Deselect the **Hide protected operating system files (Recommended)** option.  
![The Hide protected operating system files checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hide-protected-operating-system-files.jpg)
4. Select the **Show hidden files, folders and drives** radio button.
5. Click **Apply** to save the new Explorer settings.

1. Select the drive you need to set as the default save location for apps.
2. Right-click the System Volume Information folder and select **Properties**.
3. Click **Security > Advanced** to bring up an Advanced Security Settings window.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/security-tab.jpg)
4. Press the **Continue** button.
5. Next, click **Add** to view a Permission Entry window.

1. Click the **Select a principal** option.
2. Input **SYSTEM** inside the object name box.  
![The Select User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/select-user-group.jpg)
3. Click on the **OK** button.
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136624/26400" target="_top" id="2136624">
  <img src="//a.impactradius-go.com/display-ad/26400-2136624" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136624/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Select the **Full control permission** setting.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/full-control-option.jpg)
5. Then select the **OK** options on the Permission Entry and Advanced Security Settings windows.

 Close all remaining open windows. Then, restart your PC and try changing the default save location.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2128844/7443" target="_top" id="2128844">
  <img src="//a.impactradius-go.com/display-ad/7443-2128844" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2128844/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Set a New Default Save Location in Windows 11/10

 Many users have needed to fix error 0x80070005 and have done so by applying the potential solutions in this guide. The WpSystem folder is often the source of the error, and resolution two is the most widely confirmed method for fixing this issue.

 However, some users have also fixed the issue by applying the less widely cited fourth method.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-capturing-your-lenovo-display-with-ease/"><u>[New] 2024 Approved Capturing Your Lenovo Display with Ease</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-2024-approved-zoom-video-refinement-best-three-enhancement-steps/"><u>[New] 2024 Approved Zoom Video Refinement Best Three Enhancement Steps</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-achieve-perfect-screen-captures-on-the-mi-11-lite-for-2024/"><u>[New] Achieve Perfect Screen Captures on the Mi 11 Lite for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-captureelite-series-best-windowsmac-imaging-apps/"><u>[New] CaptureElite Series Best Windows/Mac Imaging Apps</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-cut-to-clarity-the-power-of-onscreen-text-in-film/"><u>[New] Cut to Clarity The Power of Onscreen Text in Film</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-future-sighted-the-foremost-cameras-excellence/"><u>[New] Future Sighted The Foremost Cameras Excellence</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-heaviest-airborran-aerial-haulers-ultimate-choices/"><u>[New] Heaviest Airborran Aerial Haulers - Ultimate Choices</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-chasing-likes-and-loads-jake-pauls-youtube-ambition/"><u>[Updated] 2024 Approved Chasing Likes and Loads Jake Paul's YouTube Ambition</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-enhancing-video-presence-editing-and-changing-facebook-covers/"><u>[Updated] 2024 Approved Enhancing Video Presence Editing and Changing Facebook Covers</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-how-to-upload-shorts-video-on-youtube/"><u>[Updated] 2024 Approved How to Upload Shorts Video on YouTube?</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-2024-approved-yi-4k-action-excellence-choosing-the-best-extras/"><u>[Updated] 2024 Approved YI 4K Action Excellence Choosing the Best Extras</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-adjust-privacy-settings-for-secure-online-viewing-for-2024/"><u>[Updated] Adjust Privacy Settings for Secure Online Viewing for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-get-more-out-of-youtube-with-8-handpicked-download-apps/"><u>[Updated] Get More Out of YouTube with 8 Handpicked Download Apps</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-effortless-transferring-5-pathways-to-download-igtv-on-computers/"><u>[Updated] In 2024, Effortless Transferring 5 Pathways to Download IGTV on Computers</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-snapshot-excellence-the-finest-software-on-market-for-2024/"><u>[Updated] Snapshot Excellence The Finest Software on Market for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-the-impact-of-testimonial-videos-today/"><u>[Updated] The Impact of Testimonial Videos Today</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-pixels-perfection-leading-online-photo-correction-tech/"><u>2024 Approved Pixels Perfection Leading Online Photo Correction Tech</u></a></li>
<li><a href="https://program-issues.techidaily.com/best-methods-to-solve-rocket-league-failure-to-start-dilemma/"><u>Best Methods to Solve Rocket League Failure to Start Dilemma</u></a></li>
<li><a href="https://screen-recording.techidaily.com/discovering-expert-seed-selection-for-valheimers-for-2024/"><u>Discovering Expert Seed Selection for Valheimers for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-to-resolve-powerpoint-print-issues-on-windows-os/"><u>Essential Tips to Resolve PowerPoint Print Issues on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tuning-the-size-of-windows-taskbar/"><u>Fine-Tuning the Size of Windows Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-erroneous-dual-camera-access-error-code-a00f4243/"><u>Fixing Erroneous Dual-Camera Access (Error Code: A00F4243)</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-utorrent-non-installation-on-pcs-running-windows-os/"><u>Fixing uTorrent Non-Installation on PCs Running Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-isdonedll-malfunction-a-guide-for-w10w11/"><u>Handling ISDone.dll Malfunction: A Guide for W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/harmonizing-your-win-key-with-microsoft-profile-access/"><u>Harmonizing Your WIN Key with Microsoft Profile Access</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-eliminate-call-not-successful-problems-in-windows-malwarebytes/"><u>How to Eliminate Call Not Successful Problems in Windows Malwarebytes</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-merge-windows-id-with-microsoft-profile/"><u>How to Merge Windows ID with Microsoft Profile</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-modify-microsoft-admin-for-windows-11-networks/"><u>How to Modify Microsoft Admin for Windows 11 Networks</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-windows-unsuccessful-auto-detect-of-network-proxy/"><u>How to Rectify Windows' Unsuccessful Auto Detect of Network Proxy</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/how-to-translate-audiovideo-content-from-spanish-to-english-and-vice-versa-for-2024/"><u>How to Translate Audio/Video Content From Spanish to English and Vice Versa for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/ideal-selections-the-best-9-mobile-video-meeting-solutions-reviewed/"><u>Ideal Selections The Best 9 Mobile Video Meeting Solutions Reviewed</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-2023-full-movement-analysis/"><u>In 2024, 2023 Full Movement Analysis</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-frp-from-honor-80-pro-straight-screen-edition-by-drfone-android/"><u>In 2024, How to Bypass FRP from Honor 80 Pro Straight Screen Edition?</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-use-pokemon-go-joystick-on-honor-v-purse-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Pokemon Go Joystick on Honor V Purse? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/insights-into-ftdibussys-windows-memory-safeguard-breach/"><u>Insights Into ftdibus.sys: Windows' Memory Safeguard Breach</u></a></li>
<li><a href="https://driver-download.techidaily.com/install-new-drivers-compatible-with-windows-for-the-hp-envy-4500-printing-device/"><u>Install New Drivers: Compatible with Windows, for the HP Envy 4500 Printing Device</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/joining-friends-showtime-on-tiktok-with-ease-for-2024/"><u>Joining Friends’ Showtime on TikTok with Ease for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/master-quick-settings-with-ease-on-your-win-11-pc/"><u>Master Quick Settings with Ease on Your Win 11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11s-character-display-tool/"><u>Mastering Windows 11'S Character Display Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-your-network-the-windows-iscsi-initiator-explained/"><u>Mastering Your Network: The Windows iSCSI Initiator Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-security-activating-tpm-and-secure-boot-for-windows-11-upgrades/"><u>Maximizing Security: Activating TPM & Secure Boot for Windows 11 Upgrades</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-resuscitate-flaky-slack-notifications/"><u>Methods to Resuscitate Flaky Slack Notifications</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-unexpected-errors-in-windows-security-fixes/"><u>Navigating Unexpected Errors in Windows Security Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-task-management-on-windows-10-and-11/"><u>Optimize Task Management on Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-yellow-screen-distortion-on-laptops/"><u>Overcoming Yellow Screen Distortion on Laptops</u></a></li>
<li><a href="https://driver-install.techidaily.com/power-up-your-dell-latest-driver-update-release-notes/"><u>Power Up Your Dell: Latest Driver Update Release Notes</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/preparation-to-beat-giovani-in-pokemon-go-for-realme-12plus-5g-drfone-by-drfone-virtual-android/"><u>Preparation to Beat Giovani in Pokemon Go For Realme 12+ 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/refine-your-mouses-click-speed-three-simple-adjustments/"><u>Refine Your Mouse's Click Speed: Three Simple Adjustments</u></a></li>
<li><a href="https://windows11.techidaily.com/resize-images-in-win11-a-step-by-step/"><u>Resize Images in Win11: A Step-by-Step</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-default-read-only-mode-for-words-email-attachments/"><u>Setting Default Read-Only Mode for Word's Email Attachments</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/sim-unlock-vivo-s17t-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>Sim Unlock Vivo S17t Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/standby-tech-in-windows-os-a-comprehensive-analysis/"><u>Standby Tech in Windows OS: A Comprehensive Analysis</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-linking-your-wireless-mouse-with-pcs-or-macbooks/"><u>Step-by-Step Guide: Linking Your Wireless Mouse with PCs or Macbooks</u></a></li>
<li><a href="https://windows11.techidaily.com/strategic-fixes-to-lower-wlanextexe-consumption/"><u>Strategic Fixes to Lower Wlanext.EXE Consumption</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/tailoring-igtv-titles-and-summaries-for-impact-for-2024/"><u>Tailoring IGTV Titles & Summaries for Impact for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-reversing-fatal-application-crashes/"><u>Techniques for Reversing Fatal Application Crashes</u></a></li>
<li><a href="https://windows11.techidaily.com/the-perfect-font-theme-match-for-your-notepad/"><u>The Perfect Font, Theme Match for Your Notepad</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-significance-of-a-chatgpt-code-interpreter-an-in-depth-overview/"><u>The Significance of a ChatGPT Code Interpreter – An In-Depth Overview</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-dfs-sudden-shutdown-issue-on-pc/"><u>Troubleshooting DF's Sudden Shutdown Issue on PC</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-tips-restoring-malfunctioning-software-packages-on-ubuntu-and-debian-based-distros/"><u>Troubleshooting Tips: Restoring Malfunctioning Software Packages on Ubuntu and Debian-Based Distros</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-update-failure-code-0x8024800c/"><u>Troubleshooting Windows Update Failure: Code 0X8024800C</u></a></li>
<li><a href="https://windows11.techidaily.com/tutorial-initiating-clipboard-operations-within-microsoft-edges-protected-environment-windows-11/"><u>Tutorial: Initiating Clipboard Operations Within Microsoft Edge's Protected Environment, Windows 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/ultimate-visualizer-speedster-for-windows-10/"><u>Ultimate Visualizer - Speedster for Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-future-of-shopping-microsoft-ai-hub/"><u>Unveiling the Future of Shopping: Microsoft AI Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/utilizing-the-newly-overhauled-widget-selection-window/"><u>Utilizing the Newly Overhauled Widget Selection Window</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-resetting-how-to-bring-back-microsoft-store-apps/"><u>Win 11 Resetting: How to Bring Back Microsoft Store Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-calmness-dial-down-the-hidden-processes/"><u>Win11 Calmness: Dial Down the Hidden Processes</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-keyboard-graphic-helper/"><u>Windows 11'S Keyboard Graphic Helper</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-startup-a-quick-route-walkthrough/"><u>Windows Startup: A Quick Route Walkthrough</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-against-apexs-hurdles-in-windows-11-crashes/"><u>Winning Against Apex's Hurdles in Windows 11 Crashes</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>