---
title: Clearing Up the Blocked App Notification Issue
date: 2024-07-11T22:24:44.306Z
updated: 2024-07-12T22:24:44.306Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Clearing Up the Blocked App Notification Issue
excerpt: This Article Describes Clearing Up the Blocked App Notification Issue
keywords: Fix Blocked App Alerts,Resolve App Notifications,Unblock App Notify Error,Clear App Block Notice,Stop App Blocking Message,Disable App Notification Halt,Remove Obstructed App Alert
thumbnail: https://thmb.techidaily.com/79c7e594da2bcc4e0b5a712ad425c9a3c9c769d4308cac3ac9d4efb24f911715.jpg
---

## Clearing Up the Blocked App Notification Issue

 While Windows is designed to keep your computer secure, sometimes it can be overly zealous in its protection and block an app you know is safe. If you’re seeing the “This app has been blocked for your protection” error on Windows, your system has restricted the application from running for security reasons. This article clarifies the reasons behind the problem and guides you toward resolving it.

## 1\. Restart Your Computer

 When you experience the “This app has been blocked for your protection” error, the first step is to restart your computer. A simple reboot can often do the trick and allow you run a previously blocked application.

 If you don’t experience the error after rebooting, then it is likely a temporary glitch on Windows.

## 2\. Scan for Malicious Programs

 If restarting your computer doesn’t work, the next step is to run a full antivirus scan on your system. Chances are that the application is blocked due to a virus, malware or another malicious program.

 To be sure it's not the case, check whether a file is infected with a virus. If you find one, [scan your computer for viruses](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) and remove them.

 If you prefer command line tools, you can [scan and remove malicious components using Windows PowerShell](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/). You should also use a [reputable anti-spyware program](https://www.makeuseof.com/windows-11-antivirus-apps/) to check for malicious programs that could be causing the error.

## 3\. Run the Program as an Administrator

 Some programs require administrator privileges to function properly. If you try to launch them without elevated access, Windows will block their execution and display the error message. In such a case, you can right-click on the app’s shortcut or the executable file and select **Run as administrator**.

 If it runs successfully, you can adjust the app properties to [always run as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/). Don't forget to save the changes.

## 4\. Disable the SmartScreen Filter

 SmartScreen is a security feature that protects your computer from unknown and potentially malicious applications. If it’s enabled, SmartScreen may block an application from running. To disable the feature, follow these steps.

1. Open the **Start** menu and search for _Windows Security_.
2. Click on **Windows Security** in the search results.
3. In the Windows Security app, select **App & browser control**.
4. On the right side of the window, click **Reputation-based protection settings**.  
![Disable the SmartScreen Filter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-the-smartscreen-filter.jpg)
5. Toggle off **Potentially unwanted app blocking** and **SmartScreen for Microsoft Store apps**.

 This will stop the system from blocking apps, but you should be careful with any programs you download. Once you do it, close the Windows Security app and try running the application again.

## 5\. Modify the Group Policy Settings

 The group policy editor allows you to adjust security settings on Windows and control which applications are blocked. If the other steps didn’t work, you can try to modify the group policy settings and unblock the application that triggered the error. Here's how to do it:

1. Press **Win + X** on your keyboard and select **Run** from the menu list.
2. Type **gpedit.msc** and press Enter to open the Local Group Policy Editor.  
![User Account Control Run all administrators in Admin Approval Mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/user-account-control-run-all-administrators-in-admin-approval-mode.jpg)
3. Once you're in the Local Group Policy Editor window, navigate to the following:  
`Local Computer Policy > Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options.`
4. From the list of settings, double-click on **User Account Control: Run all administrators in Admin Approval Mode** and set it to **Disabled**.
5. After making the changes, click **Apply > OK** and restart your computer to apply it.

 Keep in mind that modifying group policy settings can leave your computer vulnerable to malicious applications. Therefore, you should only do it as a last resort and revert the change as soon as you’re done.

## 6\. Tweak the Registry Editor

 If you're running Windows Home edition, you can tweak the Registry Editor to adjust the User Account Control settings and unblock the application. Here's what you need to do:

1. [Open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** and press Enter to open the Registry Editor window.
3. If UAC prompts you for permission, click **Yes**.
4. Navigate to the following key location.  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System`
5. In the right pane, double-click on **EnableLUA** and set its value to **0** (zero).  
![Disable the EnableLUA key in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-the-enablelua-key-in-registry-editor.jpg)
6. Click **OK** to save the changes.

 After making the changes, close the Registry Editor and restart your computer.

## 7\. Reset Windows Update Components

 If the issue persists, you can reset the Windows Update components, which means restarting certain services that manage the update process and enable you to launch the application.

 To reset Windows Update components, do the following:

1. Click on Start and search for **Notepad**.
2. Right-click on the Notepad icon and select **Run as administrator**.
3. Copy and paste the following code into Notepad:  
`<code>net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc  
Del "%ALLUSERSPROFILE%\Application Data\Microsoft\Network\Downloader\*.*"  
rmdir %systemroot%\SoftwareDistribution /S /Q  
rmdir %systemroot%  
system32\catroot2 /S /Q  
sc.exe sdset bits D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
sc.exe sdset wuauserv D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
cd /d %windir%  
system32  
regsvr32.exe /s atl.dll  
regsvr32.exe /s urlmon.dll  
regsvr32.exe /s mshtml.dll  
regsvr32.exe /s shdocvw.dll  
regsvr32.exe /s browseui.dll  
regsvr32.exe /s jscript.dll  
regsvr32.exe /s vbscript.dll  
regsvr32.exe /s scrrun.dll  
regsvr32.exe /s msxml.dll  
regsvr32.exe /s msxml3.dll  
regsvr32.exe /s msxml6.dll  
regsvr32.exe /s actxprxy.dll  
regsvr32.exe /s softpub.dll  
regsvr32.exe /s wintrust.dll  
regsvr32.exe /s dssenh.dll  
regsvr32.exe /s rsaenh.dll  
regsvr32.exe /s gpkcsp.dll  
regsvr32.exe /s sccbase.dll  
regsvr32.exe /s slbcsp.dll  
regsvr32.exe /s cryptdlg.dll  
regsvr32.exe /s oleaut32.dll  
regsvr32.exe /s ole32.dll  
regsvr32.exe /s shell32.dll  
regsvr32.exe /s initpki.dll  
regsvr32.exe /s wuapi.dll  
regsvr32.exe /s wuaueng.dll  
regsvr32.exe /s wuaueng1.dll  
regsvr32.exe /s wucltui.dll  
regsvr32.exe /s wups.dll  
regsvr32.exe /s wups2.dll  
regsvr32.exe /s wuweb.dll  
regsvr32.exe /s qmgr.dll  
regsvr32.exe /s qmgrprxy.dll  
regsvr32.exe /s wucltux.dll  
regsvr32.exe /s muweb.dll  
regsvr32.exe /s wuwebv.dll  
netsh winsock reset  
netsh winsock reset proxy  
net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`
4. Now click **File** in the top left corner.
5. Then select **Save as** from the options list.
6. In the Save as window, name your script **Reset.bat** and set the Save as type to **All Files**.
7. Select **Desktop** from the left menu and click **Save**.
8. Double-click on the **Reset.bat** file to run it as an administrator.
9. If the UAC window pops up on the screen, click **Yes** to continue.

 Wait for the process to finish and restart your computer. After the reboot, try running the blocked app again. It should now work without issues.

## Get Access to Your Apps and Files on Windows

 Windows is known for its tight security which prevents malicious applications from launching and infecting your PC. However, sometimes even legitimate programs are blocked by the operating system and leave an error message saying “This app has been blocked for your protection.”

 There are several reasons why this error occurs. It includes outdated security software, the firewall interfering with the program, or the application not trusted by Windows. Read this guide to learn more about this error.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-apple-iphone-8-activation-lock-by-drfone-ios/"><u>In 2024, How to Remove Apple iPhone 8 Activation Lock</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-which-screen-recording-app-wins-bandicam-vs-camtasia-analysis-for-2024/"><u>[Updated] Which Screen Recording App Wins? Bandicam Vs Camtasia Analysis for 2024</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-reset-the-security-questions-of-your-apple-id-on-your-apple-iphone-12-pro-by-drfone-ios/"><u>How To Reset the Security Questions of Your Apple ID On Your Apple iPhone 12 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-where-windows-keeps-snaps/"><u>Discover Where Windows Keeps Snaps</u></a></li>
<li><a href="https://windows11.techidaily.com/correct-keyboard-fixes-for-windows-11s-unresponsive-f-keys/"><u>Correct: Keyboard Fixes for Windows 11'S Unresponsive F Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-dual-monitor-mishaps-on-your-pc/"><u>Correcting Dual Monitor Mishaps on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/connected-scribbles-using-stickies-across-all-devices-in-win11/"><u>Connected Scribbles: Using Stickies Across All Devices in Win11</u></a></li>
<li><a href="https://discord-videos.techidaily.com/from-joiner-writhe-step-by-step-strategy-for-achieving-partner-status-for-2024/"><u>From Joiner' Writhe  Step-by-Step Strategy for Achieving Partner Status for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/create-your-own-windows-speech-recognition-app-with-autohotkey-and-whisper/"><u>Create Your Own Window's Speech Recognition App with AutoHotkey and Whisper</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-camera-not-detected-error-on-windows-11-pcs/"><u>Correcting “Camera Not Detected” Error on Windows 11 PCs</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-show-wi-fi-password-on-realme-10t-5g-by-drfone-android/"><u>How to Show Wi-Fi Password on Realme 10T 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/directing-system-thermal-output-with-customization/"><u>Directing System Thermal Output with Customization</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-windows-11s-user-identity-framework/"><u>Dissecting Windows 11'S User Identity Framework</u></a></li>
<li><a href="https://windows11.techidaily.com/curtailing-spontaneous-terminal-trigger-activations/"><u>Curtailing Spontaneous Terminal Trigger Activations</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/join-in-fun-this-weeks-top-10-challenges/"><u>Join in Fun  This Week's Top 10 Challenges</u></a></li>
<li><a href="https://windows11.techidaily.com/dial-up-the-velocity-fixing-your-stuttery-pc/"><u>Dial Up the Velocity: Fixing Your Stuttery PC</u></a></li>
<li><a href="https://windows11.techidaily.com/command-line-conjuring-windows-new-feature/"><u>Command Line Conjuring: Windows' New Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-fix-for-msvcr110dll-absence/"><u>Comprehensive Fix for msvcr110.dll Absence</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-inaccessible-steam-servers-in-home-pc-setups/"><u>Dealing With Inaccessible Steam Servers in Home PC Setups</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-solution-to-stop-0xf0831-in-windows-11/"><u>Comprehensive Solution to Stop 0xF0831 in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-systemsettings-executable-errors-on-windows-11/"><u>Correcting SystemSettings Executable Errors on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-microsofts-window-file-format-cab-for-ease-of-use/"><u>Deciphering Microsoft's Window File Format (CAB) for Ease of Use</u></a></li>
<li><a href="https://windows11.techidaily.com/determining-hddssd-in-windows-a-step-by-step-guide/"><u>Determining HDD/SSD in Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/combining-audioscapes-and-visuals-snipping-tool-guide-max-156/"><u>Combining Audioscapes & Visuals: Snipping Tool Guide (Max 156)</u></a></li>
<li><a href="https://some-techniques.techidaily.com/hooking-audience-early-with-smart-intros-for-2024/"><u>Hooking Audience Early with Smart Intros for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-the-ultimate-guide-to-blurring-faces-in-photos-and-videos-free-resources/"><u>Updated The Ultimate Guide to Blurring Faces in Photos and Videos (Free Resources)</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-full-guide-to-bypass-motorola-razr-40-frp-by-drfone-android/"><u>In 2024, Full Guide to Bypass Motorola Razr 40 FRP</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-ms-resouce-issue-for-text-display/"><u>Correcting Ms-Resouce Issue for Text Display</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-folder-tab-glitches-in-windows-11/"><u>Conquering Folder Tab Glitches in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-compatibility-issues-windows-troubleshooting-blueprint/"><u>Conquer Compatibility Issues: Windows Troubleshooting Blueprint</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-cost-analysis-strategy-for-music-video-creation/"><u>2024 Approved  Cost Analysis Strategy for Music Video Creation</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-free-video-flipper-websites-no-download-required-for-2024/"><u>New Free Video Flipper Websites No Download Required for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/how-to-secretly-share-moments-with-instagram-live/"><u>How to Secretly Share Moments with Instagram Live</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-optimal-filter-pack-for-oceanic-video-shooting/"><u>In 2024, Optimal Filter Pack for Oceanic Video Shooting</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-correcting-unspecified-obs-recording-glitches/"><u>Decoding and Correcting Unspecified OBS Recording Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/disable-windows-11s-covert-surveillance/"><u>Disable Windows 11'S Covert Surveillance</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-device-disabled-issue-with-error-code-22-on-windows-11/"><u>Correcting Device Disabled Issue with Error Code 22 on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-idle-computing-with-auto-sleep-in-w10w11/"><u>Conquering Idle Computing with Auto Sleep in W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/ditch-default-home-port-on-w11-settings-interface/"><u>Ditch Default Home Port on W11 Settings Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-windows-screen-size-setsbacks-7-easy-solutions/"><u>Conquering Windows' Screen Size Setsbacks: 7 Easy Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-a-plan-for-file-explorer-in-windows-11/"><u>Crafting a Plan for File Explorer in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/controlling-highlight-features-on-windows-11-pcs/"><u>Controlling Highlight Features on Windows 11 PCs</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-realme-v30t-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Realme V30T | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/critiquing-7-perplexing-windows-11-aesthetics/"><u>Critiquing 7 Perplexing Windows 11 Aesthetics</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>