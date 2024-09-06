---
title: Troubleshooting Authentication Issues in Windows OS
date: 2024-09-05T02:10:02.748Z
updated: 2024-09-06T02:10:02.748Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Authentication Issues in Windows OS
excerpt: This Article Describes Troubleshooting Authentication Issues in Windows OS
keywords: WinOS Auth Fixes,Login Windows Troubleshoot,Unlock Windows Errors,User Credentials Problems,Password Recovery Windows,Authentication Windows Guide,Secure Windows Login Help
thumbnail: https://thmb.techidaily.com/2579e58fb859f12bcf75d41bfcd2bb7289ef81a099867df0bbc5e1bf070a408f.jpg
---

## Troubleshooting Authentication Issues in Windows OS

 LSA protection is a vital security feature on Windows that prevents unauthorized access to system resources. However, corrupt system files or malware infections may lead to an error stating "this change requires you to restart your device". This error persists even after enabling Local Security Authority (LSA) protection or restarting the computer.

 It suggests an underlying problem that requires resolution to restore system security. If you have the same problem, these solutions might help.

## What Causes the LSA Protection Error?

 The exact cause of the “this change requires you to restart your device” error can vary, but it may be due to corrupted system files or malware infections. Malware can install malicious services and components that interfere with Windows' smooth functioning, including disabling Local Security Authority (LSA) protection. It can also occur if antivirus software incorrectly removes system files and causes instability.

 This error is usually triggered when Windows attempts to enable Local Security Authority (LSA) protection and fails. In some cases, the error may also appear after you enabled LSA protection and restarted your computer.

## 1\. Restart Your PC

 As the error message suggests, you first restart your Windows system. This minor step can fix several system-level errors and is worth a try. Restarting your computer involves shutting down all running programs and starting it up again.

## 2\. Scan for Malicious Programs

 If restarting the computer doesn't solve the issue, check your system for malicious software. Malware infections may corrupt system files and prevent LSA protection from working.

 To check if any malicious programs are on your system, do the following.

1. Press **Win + Q** on your keyboard to open the Taskbar search window.
2. Type **Windows Security** in the search bar and hit Enter.
3. On the left pane of Windows Security, click the **Virus & threat protection** tab.
4. Click **Scan options** on the right side of the screen.  
![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)
5. Select **Full scan** and click **Scan now**.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938682/19272" target="_top" id="1938682">
  <img src="//a.impactradius-go.com/display-ad/19272-1938682" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938682/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now wait for the scan to finish. If malicious programs are detected, Windows Security will remove them from your system automatically.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2024351/7443" target="_top" id="2024351">
  <img src="//a.impactradius-go.com/display-ad/7443-2024351" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2024351/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Change the Group Policy Settings

 If the above steps don't help, you might need to configure LSA manually. It involves editing the Local Group Policy Editor and setting some specific settings. However, this tool only works with Windows 11 Professional and Enterprise editions.

 So, if you're running Windows Home Edition, you won't have access to Local Group Policy. To make this work, [enable the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/), then follow these steps:

1. Press **Win + R** on your keyboard to open the Run dialogue box.
2. Type **gpedit.msc** in the search box and hit Enter.
3. In the Local Group Policy Editor, expand **Computer Configuration** on the left side.
4. Then navigate to the following:  
Administrative Templates > System > Local Security Authority
5. Double-click **Configure LSASS to run as a protected process** in the right pane.  
![Change the Group Policy Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-the-group-policy-settings.jpg)
6. Now, in the window that appears, alter the settings from **Not Configured** to **Enabled**.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997695/19272" target="_top" id="1997695">
  <img src="//a.impactradius-go.com/display-ad/19272-1997695" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997695/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Under the Options section, click the drop-down menu for **Configure LSASS to run as a protected process** and select **Enabled with UEFI Lock**.  
![Set as Enabled with UEFI Lock](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-as-enabled-with-uefi-lock.jpg)
8. Now click **Apply > OK** to save the changes.

 After making the above changes, restart your computer and check if the error is resolved.

## 4\. Tweak the Registry Editor

 If you're running Windows Home edition, you can tweak the Registry Editor to modify Local Security Authority protection values. The steps are pretty straightforward, but be aware that making incorrect changes to the registry can cause serious problems. To be safe, [back up the Windows Registry data](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making any changes.

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the dialog box and press the Enter key.
3. If UAC prompts appear on the screen, click **Yes** to grant permission.
4. In the Registry Editor window, navigate to the following location:  
Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa  
 You can also copy and paste the given path into the address bar at the top of the Registry window. Then, hit Enter to jump directly to the folder.
5. In the right pane, double-click on **RunAsPPL** to open Edit DWORD (32-bit) Value.  
![Change RunAsPPL regsitry values](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-runasppl-regsitry-values.jpg)
6. Change the Value data from 0 to **2** and click **OK**.
7. Similarly, find the **RunAsPPLBoot** key and set its value to **2**.  
 If you don't find the **RunAsPPL** and **RunAsPPLBoot** keys in the LSA folder, you'll need to create them manually. To do this, right-click on the LSA folder and select **New > DWORD (32-bit) Value**. Name the new value **RunAsPPL** and set its value to 2\. Then repeat this process for the **RunAsPPLBoot** key.

 Once you're done, close the Registry Editor and restart your computer. This should fix the problem.

## 5\. Reset the Windows Security App

 Windows Security is an integrated antivirus program built into the Windows OS. It's responsible for scanning your system and removing malicious content. If there's something wrong with the Windows Security app, it might trigger this error. To fix the issue, reset the app and see if it helps. Here's how to do it:

1. Press **Win + I** on your keyboard to open the system settings.
2. Select **Apps** on the left side of the window.
3. Click **Installed apps** in the right pane
4. Scroll down the list of apps until you see **Windows Security**. You can also type Windows Security into the search bar to find it quickly.
5. Now click the three dots icon and select **Advanced options** from the menu.
6. On the next page, scroll down to the **Reset** section and click **Reset**.  
![Reset Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-windows-security.jpg)
7. If the confirmation window pops up, click **Reset** to continue.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006946/19272" target="_top" id="2006946">
  <img src="//a.impactradius-go.com/display-ad/19272-2006946" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006946/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Wait for the reset process to finish and restart your computer. After restarting, check if the error is still present.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2024333/7443" target="_top" id="2024333">
  <img src="//a.impactradius-go.com/display-ad/7443-2024333" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2024333/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Perform Some Generic Fixes

 There are also some generic fixes to resolve the issue. First, [run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) command to repair incorrect or damaged system files. You may also want to use the Deployment Image Servicing and Management tool to diagnose issues with local system images. If the problem persists, try [updating Windows to the latest version](https://www.makeuseof.com/update-windows-manually/) to resolve any glitches or bugs.

 Some antivirus and security programs can be too aggressive in protecting your system. They could prevent access to the LSA feature, leading to this problem. To be sure, you can [temporarily disable your security software](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) and check if it solves the issue.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975807/19272" target="_top" id="1975807">
  <img src="//a.impactradius-go.com/display-ad/19272-1975807" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975807/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fixing the LSA Protection Error on Windows

 Local Security Authority protection safeguards unauthorized access to system resources, such as passwords or other sensitive information. However, this feature might not work as expected due to LSA Protection Error. Thanks to the potential solutions discussed in this guide, solving the problem is easy.

 It suggests an underlying problem that requires resolution to restore system security. If you have the same problem, these solutions might help.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-diy-audio-excellence-no-mic-necessary/"><u>[Updated] 2024 Approved  DIY Audio Excellence  No Mic Necessary</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-innovative-attention-grabber-designer/"><u>[Updated] Innovative Attention Grabber Designer</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-the-best-of-the-best-crafting-a-top-5-racing-game-selection-for-2024/"><u>[Updated] The Best of the Best  Crafting a Top 5 Racing Game Selection for 2024</u></a></li>
<li><a href="https://facebook.techidaily.com/exploring-the-impactful-disclosures-in-whistleblowers-report/"><u>Exploring The Impactful Disclosures in Whistleblower's Report</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-windows-canary-a-guide-for-first-timers/"><u>Exploring Windows Canary: A Guide for First-Timers</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/flipping-videos-like-a-pro-quick-easy-and-stress-free-for-2024/"><u>Flipping Videos Like a Pro Quick, Easy, and Stress-Free for 2024</u></a></li>
<li><a href="https://facebook.techidaily.com/friends-across-platforms-embodying-your-social-media-self-on-whatsapp/"><u>Friends Across Platforms: Embodying Your Social Media Self on WhatsApp</u></a></li>
<li><a href="https://windows11.techidaily.com/harness-the-power-of-windows-11-expert-level-docx-to-pdf-processes/"><u>Harness the Power of Windows 11: Expert-Level DOCX to PDF Processes</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-batch-convert-heic-images-to-jpeg-format-in-windows-11-and-11/"><u>How to Batch Convert HEIC Images to JPEG Format in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-install-microsoft-works-on-windows-10-or-11/"><u>How to Install Microsoft Works on Windows 10 or 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-leverage-windows-11-for-reliable-testing-sessions/"><u>How to Leverage Windows 11 for Reliable Testing Sessions</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-lock-down-your-pcs-external-hard-drive-access/"><u>How To Lock Down Your PC's External Hard Drive Access</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-detailed-guide-on-removing-apple-iphone-7-plus-activation-lock-without-previous-owner-by-drfone-ios/"><u>In 2024, Detailed Guide on Removing Apple iPhone 7 Plus Activation Lock without Previous Owner?</u></a></li>
<li><a href="https://windows11.techidaily.com/insights-into-ftdibussys-the-implications-for-windows-memory-safety/"><u>Insights Into ftdibus.sys: The Implications for Windows Memory Safety</u></a></li>
<li><a href="https://windows11.techidaily.com/making-windows-11-quieter-stop-non-user-apps/"><u>Making Windows 11 Quieter: Stop Non-User Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/modernize-your-tech-consider-alternatives-to-windows/"><u>Modernize Your Tech: Consider Alternatives to Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mute-non-met-requirement-notifications-on-windows/"><u>Mute Non-Met Requirement Notifications on Windows</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-fcpx-glitch-busters-quick-fixes-for-common-problems/"><u>New 2024 Approved FCPX Glitch Busters Quick Fixes for Common Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-spotify-not-replying-on-pcs-with-windows-11/"><u>Quick Fixes for Spotify Not Replying on PCs with Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/re-establish-missing-5ghz-network-link-on-windows-11-successfully/"><u>Re-Establish Missing 5GHz Network Link on Windows 11 Successfully</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivating-devices-in-sleep-mode-step-by-step-guide-for-windows-11/"><u>Reactivating Devices in Sleep Mode: Step-by-Step Guide for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstating-microsoft-store-apps-windows-11s-guide-to-fixes/"><u>Reinstating Microsoft Store Apps: Windows 11'S Guide to Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-memory-safety-in-windows-11s-system-settings/"><u>Restoring Memory Safety in Windows 11'S System Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/reversing-load-error-in-windows-store-application/"><u>Reversing 'Load Error' In Windows Store Application</u></a></li>
<li><a href="https://windows11.techidaily.com/sidestep-do-not-have-sufficient-privileges-uninstall-on-windows/"><u>Sidestep 'Do Not Have Sufficient Privileges': Uninstall on Windows</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/smile-and-shine-enhance-photos-at-zero-cost-for-2024/"><u>Smile & Shine  Enhance Photos at Zero Cost for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/solutions-to-spy-on-honor-x50-with-and-without-jailbreak-drfone-by-drfone-virtual-android/"><u>Solutions to Spy on Honor X50 with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-silent-setbacks-ccleaner-issues-in-windows-11/"><u>Solving Silent Setbacks: CCleaner Issues in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-to-supercharged-vram-on-windows-10-and-11/"><u>Step-by-Step to Supercharged VRAM on Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategic-steps-launching-your-admin-privileged-powershell-console/"><u>Strategic Steps: Launching Your Admin Privileged PowerShell Console</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-fix-system-call-failures-in-windows/"><u>Strategies to Fix System Call Failures in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/system-breakthroughs-overcoming-os-barriers-to-photoscape/"><u>System Breakthroughs: Overcoming OS Barriers to Photoscape</u></a></li>
<li><a href="https://windows11.techidaily.com/the-five-fold-windows-11-data-collection/"><u>The Five-Fold Windows 11 Data Collection</u></a></li>
<li><a href="https://windows11.techidaily.com/the-role-and-risks-involved-with-deleting-pagefilesys-files/"><u>The Role & Risks Involved with Deleting Pagefile.sys Files</u></a></li>
<li><a href="https://windows11.techidaily.com/the-win-11-and-10-way-out-of-the-s-mode-maze/"><u>The Win 11 & 10 Way Out of the 'S Mode Maze'</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-turning-onoff-windows-key-functionality/"><u>Tips for Turning On/Off Windows Key Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-cr2-images-into-jpgs-on-windows-pc/"><u>Transforming CR2 Images Into JPGs on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-steams-access-issue-for-games-on-win11/"><u>Unblocking Steam's Access Issue for Games on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-ios-calendar-in-your-windows-environment/"><u>Unlocking iOS Calendar in Your Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/unravel-the-power-of-windows-redos-using-hotkey-keys/"><u>Unravel the Power of Windows Redos Using Hotkey Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-winget-woes-solutions-for-windows-11-users/"><u>Unraveling Winget Woes: Solutions for Windows 11 Users</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-from-tape-to-digital-mastering-the-vhs-effect-in-fcp-for-2024/"><u>Updated From Tape to Digital Mastering the VHS Effect in FCP for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/win11win10s-unidentified-device-fix-guide/"><u>Win11/Win10's 'Unidentified Device' Fix Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-power-move-end-multiple-apps-with-a-single-key/"><u>Windows Power Move: End Multiple Apps with a Single Key</u></a></li>
<li><a href="https://windows11.techidaily.com/wintoys-decoded-an-introduction-to-a-pivotal-windows-app/"><u>WinToys Decoded: An Introduction to a Pivotal Windows App</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>