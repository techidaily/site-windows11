---
title: "How To Uninstall Oneself: Avoiding Admin Restrictions in WINDOWS"
date: 2024-07-11T21:13:04.198Z
updated: 2024-07-12T21:13:04.198Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes How To Uninstall Oneself: Avoiding Admin Restrictions in WINDOWS"
excerpt: "This Article Describes How To Uninstall Oneself: Avoiding Admin Restrictions in WINDOWS"
keywords: Win Uninstall Self Tricks,Bypass Windows Admin Locks,Evasion Admin Restrictions,Unlocking OS User Limits,Skip Admin-Enforced Deletion,Override Windows Security,Circumvent Admin Controls
thumbnail: https://thmb.techidaily.com/13464bbf7702e727674e34228111122f1f619fb5b014ebf3cf5f5ddd4c2dec0d.jpg
---

## How To Uninstall Oneself: Avoiding Admin Restrictions in WINDOWS

 Some users have reported an uninstall issue on Microsoft’s forum with an error message that says, “You do not have sufficient access to uninstall.” That error message pops up when users try to uninstall certain software in Windows 11/10\. As a result, users can’t uninstall whatever software packages that error occurs for.

 That error message highlights the issue is caused by insufficient access. However, the error can arise for users even when they have administrator privileges. This is how you can fix the “do not have sufficient access to uninstall” error in Windows 11/10\.

## 1\. Enable the Windows Admin Account

 First, make sure you’re utilizing an admin account. You can [activate a built-in Windows admin account](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/) via the Command Prompt. Then log in to that built-in admin account and try uninstalling the software from there.

 Alternatively, you can switch a current standard user account to an admin one. Check out this guide to [changing Windows account types](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) for full instructions about how to do so.

## 2\. Run the Affected Software’s Uninstaller File as an Administrator

 Also, run the software’s uninstaller file as an administrator. The software’s installation directory will include its uninstaller file. Right-click that file to select a **Run as administrator** context menu option.

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-as-administrator-option5.jpg)

## 3\. Troubleshoot With the Program Install and Uninstall Troubleshooter

 Windows doesn’t include any troubleshooter for fixing uninstallation issues. However, there is a Microsoft Program Install and Uninstall troubleshooter that might be useful for fixing the “You do not have sufficient access to uninstall” error. This is how you can run the Program Install and Uninstall troubleshooter:

1. Bring up the troubleshooter's [Microsoft download page](https://support.microsoft.com/en-us/topic/fix-problems-that-block-programs-from-being-installed-or-removed-cca7d1b6-65a9-3d98-426b-e9f927e1eb4d).
2. Then click on the **Download** troubleshooter button.
3. Double-click on the **MicrosoftProgram\_Install\_and\_Uninstall.meta.diagcab** troubleshooter file.  
![The Program Install and Uninstall troubleshooter window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/program-install-and-uninstall-troubleshooter.jpg)
4. Click on **Next** \> **Uninstalling** to bring up a program list.  
![The Uninstalling option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/uninstalling-option.jpg)
5. Then select the program you can’t uninstall and select **Next**.  
![The Program Install and Uninstall troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/program-list.jpg)

## 4\. Turn Off User Account Control

 The “You do not have sufficient access to uninstall” error can sometimes arise because User Account Control is set to high. So, try temporarily turning UAC off before uninstalling the affected software. Our guide on [disabling User Account Control](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) tells you how to turn off UAC.

![The User Account Control settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/user-account-control.jpg)

## 5\. Set Full Control Permissions for the Software’s Installation Folder

 You might need to fix this error because the full user control permission setting isn’t set for the software installation’s folder. So, check the control permission settings for the software installation folder. This is how you can set full control permission for a folder:

1. Open the folder that contains the installation directory of the affected software.
2. Right-click on the installation folder and select **Properties**.  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/properties-option3.jpg)
3. Click **Edit** on the **Security** tab.
4. Select your user account name.
5. Click the **Full control** checkbox to select that setting if it’s not already.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-control-window.jpg)
6. Then select **Apply** \> **OK** on the folder’s permissions window.
7. Select **OK** to exit the properties window.
8. Repeat the above instructions for the program’s EXE (application) file.

## 6\. Uninstall the Software With an UninstallString Value

 Some users have resolved this error by uninstalling the affected software packages with their UninstallString values. You can do that by copying and pasting the UninstallString value for a program from the registry into the Command Prompt. These are the steps for uninstalling software with an UninstallString value:

1. Open Windows Search with **Win + S**.
2. Type in **regedit** to find the Registry Editor.
3. Select Registry Editor to launch that app.
4. Next, input this location into Registry Editor’s address bar:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Wow6432Node\Microsoft\Windows\CurrentVersion\Uninstall`
5. Click on the subkeys in the **Uninstall** key to view the **DisplayName** strings for them.

1. Select the key for the software you can’t install by identifying it with the **DisplayName** string.  
![DisplayName string](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/display-name.jpg)
2. Double-click on the key's **UninstallString** string.
3. Copy the text in the **Value data** box by selecting it and pressing **Ctrl** \+ **C**.  
![The Edit String window for the UninstallString](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-string-window3.jpg)
4. Open Command Prompt as an admin (See [how to open Command Prompt with admin permissions](https://www.makeuseof.com/windows-run-command-prompt-admin/)).
5. Click inside the Command Prompt and press **Ctrl** \+ **V** to paste in the string.  
![An uninstall command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/undostring-command.jpg)
6. Press **Enter** to run the command and remove the software.

 Note that the above registry string is for 64-bit software. To find the strings for 32-bit software, you’ll need to go to this registry path:

`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Uninstall`

## 7\. Try Uninstalling the Software With a Third-Party Uninstaller Tool

 Third-party uninstaller tools have helped some users fix the “do not have sufficient access to uninstall” error. The [best third-party uninstaller tools](https://www.makeuseof.com/windows-11-uninstallers-stubborn-apps/) are superior to Windows’ Programs and Features applet for removing software. So, try uninstalling the software with a freely available utility like Revo Uninstaller, IObit Uninstaller, or Advanced Uninstaller Pro. This is how you can do that with IObit Uninstaller:

1. Open this [IObit Uninstaller](https://www.iobit.com/en/advanceduninstaller.php) download page.
2. Select **Free Download** to save IObit Uninstaller’s setup wizard within a folder.
3. Bring up the directory containing the **iobituninstaller.exe** file.
4. Double-click the **iobituninstaller.exe** file and click **Install** in the setup wizard.
5. Open IObit Uninstaller and select the **All programs** tab.  
![The IObit Uninstaller software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-iobit-uninstaller-software.jpg)
6. Select the program and click **Uninstall**.
7. Click on the checkbox labeled **Automatically remove residual files**.
8. Select **Uninstall** to remove the software.  
![The Uninstall button in IObit Uninstaller](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-uninstall-button.jpg)

## 8\. Uninstall the Software Within Safe Mode

 Safe mode is Windows troubleshooting mode in which only essential drivers and services run. Uninstalling affected software in that mode might work since it will disable things like UAC that can interfere with the uninstallation process. This guide about [entering Windows safe mode](https://www.makeuseof.com/windows-11-boot-safe-mode/) covers the different ways you can enter that mode.

 However, the safe mode also disables Windows Installer (MSI). So, you’ll need to tweak the registry to prevent the disabling of Windows Installer before entering safe mode. Edit the registry as follows:

1. Start the Registry Editor as covered in steps one to three of the sixth potential solution.
2. Then input the following registry key address:  
`HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Control\SafeBoot\Minimal`
3. Click the **Minimal** key with your right mouse button and select **New**.
4. Select **Key** and input **MSIServer** within the text box. If that key already exists, then you need not set up a new key.  
![The New > Key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-key-option.jpg)
5. Next, select the **MSIServer** key and double-click its **(Default)** string.
6. Enter **Service** in the **Value data** box and select **OK**.  
![The Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-string-window4.jpg)
7. Then enter safe mode and try uninstalling the affected software.

## Uninstall the Software You Need to Remove on Windows

 Although not guaranteed, there’s a pretty good chance one of the resolutions in this guide will resolve the “do not have sufficient access to uninstall” error on your PC. If not, consider troubleshooting the issue with a third-party PC repair tool.

 A more drastic troubleshooting method, like resetting Windows 11/10 or performing an in-place upgrade, might be required to fix system file and registry issues.

 That error message highlights the issue is caused by insufficient access. However, the error can arise for users even when they have administrator privileges. This is how you can fix the “do not have sufficient access to uninstall” error in Windows 11/10\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/a-new-look-for-you-top-methods-to-alter-windows-11-themes/"><u>A New Look for You: Top Methods to Alter Windows 11 Themes</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-10-upgrade-fault-code-0xc004f050/"><u>Bypassing Windows 10 Upgrade Fault: Code 0XC004F050</u></a></li>
<li><a href="https://howto.techidaily.com/7-fixes-for-unfortunately-phone-has-stopped-on-realme-narzo-n53-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Fixes for Unfortunately, Phone Has Stopped on Realme Narzo N53 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-forbidden-page-in-windows-setup/"><u>Addressing Forbidden Page in Windows Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-windows-vram-a-step-by-step-guide/"><u>Boosting Windows VRAM: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-non-existent-files-message-on-windows-11/"><u>Addressing Non-Existent Files Message on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/best-data-shields-on-windows-encryption-apps-analysis-150-chars/"><u>Best Data Shields on Windows: Encryption Apps Analysis (150 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/antiquated-tech-awakened-atlasos-upgrade/"><u>Antiquated Tech Awakened: AtlasOS Upgrade</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-for-placing-antique-games-into-photos-folder/"><u>A Step-by-Step for Placing Antique Games Into Photos Folder</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/instagrams-secret-fine-tuning-fcpx-for-high-aspect-videos/"><u>Instagram's Secret  Fine-Tuning FCPX for High Aspect Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/5-ways-to-close-multiple-apps-simultaneously-on-windows/"><u>5 Ways to Close Multiple Apps Simultaneously on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-crisp-visuals-leveraging-background-blur-in-w11s-photos-app/"><u>Achieve Crisp Visuals: Leveraging Background Blur in W11's Photos App</u></a></li>
<li><a href="https://howto.techidaily.com/app-wont-open-on-your-lava-blaze-2-pro-here-are-all-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>App Wont Open on Your Lava Blaze 2 Pro? Here Are All Fixes | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-customizable-rgb-in-windows-11-os/"><u>Activating Customizable RGB in Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/1719361633854-enhance-your-pcs-screen-glow-with-these-fixes/"><u>Enhance Your PC's Screen Glow with These Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/access-androids-gaming-joy-on-pc-from-phone-to-window-11-via-google-linkup/"><u>Access Android's Gaming Joy on PC: From Phone to Window 11 via Google Linkup</u></a></li>
<li><a href="https://techidaily.com/recover-apple-iphone-14-pro-data-from-ios-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover Apple iPhone 14 Pro Data From iOS iCloud | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-ultimate-video-mastery-for-professional-vimeo-users/"><u>[Updated] In 2024, Ultimate Video Mastery for Professional Vimeo Users</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/streamline-your-workflow-with-top-10-free-mac-screen-recorders/"><u>Streamline Your Workflow with Top 10 Free Mac Screen Recorders</u></a></li>
<li><a href="https://extra-hints.techidaily.com/craftsmanship-in-focus-leading-android-collage-tools/"><u>Craftsmanship in Focus – Leading Android Collage Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/5-proven-strategies-for-superior-windows-11-search-performance/"><u>5 Proven Strategies for Superior Windows 11 Search Performance</u></a></li>
<li><a href="https://fox-glue.techidaily.com/how-to-reverse-color-saturation-quickly-for-2024/"><u>How to Reverse Color Saturation Quickly for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-tips-and-tricks-for-effective-azure-speech-to-text-use/"><u>[Updated] Tips and Tricks for Effective Azure Speech-to-Text Use</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-changing-printer-behavior-on-windows/"><u>Avoiding Changing Printer Behavior on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/7-solutions-for-enabling-windows-11s-memory-check/"><u>7 Solutions for Enabling Windows 11'S Memory Check</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-proxy-in-windows-11-for-enhanced-privacy/"><u>Adjusting Proxy in Windows 11 for Enhanced Privacy</u></a></li>
<li><a href="https://windows11.techidaily.com/a-visual-journey-to-custom-window-design-with-winbubbles-insights/"><u>A Visual Journey to Custom Window Design with WinBubble's Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-unresponsive-windows-11-login-screens/"><u>Bypassing Unresponsive Windows 11 Login Screens</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-navigating-av1-your-initial-journey/"><u>[Updated] Navigating AV1  Your Initial Journey</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-revolutionize-your-podcasts-rankings-with-effective-seo-methods/"><u>[Updated] Revolutionize Your Podcast's Rankings with Effective SEO Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-rgb-customization-in-win11/"><u>Activating RGB Customization in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/amplify-your-pcs-wi-fi-with-8-effective-fixes-for-windows-11/"><u>Amplify Your PC's Wi-Fi with 8 Effective Fixes for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/arp-cache-in-windows-what-and-how-to-purge/"><u>ARP Cache in Windows: What and How to Purge?</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-start-page-in-windows-11-task-manager/"><u>Altering Start Page in Windows 11 Task Manager</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-apple-iphone-se-ios-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair Apple iPhone SE iOS? | Dr.fone</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-vegaspro-2019-a-comprehensive-analysis/"><u>[Updated] In 2024, VegasPro 2019  A Comprehensive Analysis</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/uniting-tiktok-and-twitter-with-one-click/"><u>Uniting TikTok and Twitter with One Click</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-insufficient-access-errors-during-software-removal/"><u>Avoiding Insufficient Access Errors During Software Removal</u></a></li>
<li><a href="https://windows11.techidaily.com/best-practices-for-disabling-noncritical-windows-11-services/"><u>Best Practices for Disabling Noncritical Windows 11 Services</u></a></li>
<li><a href="https://windows11.techidaily.com/boot-old-gear-into-latest-windows-11-22h2/"><u>Boot Old Gear Into Latest Windows 11 22H2</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-xiaomi-14-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Xiaomi 14 Hard Reset | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/add-command-to-windows-11-context-menu-for-file-moves-and-copies/"><u>Add Command to Windows 11 Context Menu for File Moves & Copies</u></a></li>
<li><a href="https://windows11.techidaily.com/beat-the-burn-how-to-cool-down-your-gamers-windows-laptop/"><u>Beat The Burn: How to Cool Down Your Gamers’ Windows Laptop</u></a></li>
<li><a href="https://windows11.techidaily.com/9-ways-to-fix-blurry-screen-issues-on-windows-11/"><u>9 Ways to Fix Blurry Screen Issues on Windows 11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-inside-screencasting-obs-tools-analyzed-for-optimal-broadcasts/"><u>2024 Approved  Inside Screencasting  OBS Tools Analyzed for Optimal Broadcasts</u></a></li>
<li><a href="https://windows11.techidaily.com/briefly-explain-what-cultural-relativism-means-in-your-own-words/"><u>Briefly Explain What Cultural Relativism Means in Your Own Words.</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-camcraze-evaluation-excellence-beyond-one-brand/"><u>[Updated] 2024 Approved  CamCraze Evaluation  Excellence Beyond One Brand</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-photos-problem-package-not-registered/"><u>Addressing Windows Photos Problem - Package Not Registered</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-the-pathway-to-immaculate-audio-integration-in-video-production/"><u>In 2024, The Pathway to Immaculate Audio Integration in Video Production</u></a></li>
<li><a href="https://fake-location.techidaily.com/which-is-the-best-fake-gps-joystick-app-on-tecno-camon-20-drfone-by-drfone-virtual-android/"><u>Which is the Best Fake GPS Joystick App On Tecno Camon 20? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-guide-to-modifying-windows-file-attributes/"><u>A Step-by-Step Guide to Modifying Windows File Attributes</u></a></li>
</ul></div>
