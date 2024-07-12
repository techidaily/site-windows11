---
title: Securing Memory Integrity with Win11 Tweaks & Tricks
date: 2024-07-11T21:59:47.312Z
updated: 2024-07-12T21:59:47.312Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Securing Memory Integrity with Win11 Tweaks & Tricks
excerpt: This Article Describes Securing Memory Integrity with Win11 Tweaks & Tricks
keywords: Secure Windows Memory,Win11 Security Tweaks,Protecting Memory Win11,Memory Integrity Fixes,Enhancing Win11 Memory,Win11 Safety Tips,Memory Verification Tricks
thumbnail: https://thmb.techidaily.com/91ba55faa148d92407dbc1d9a9fedc994b551d4a3d25bebb5c143d9e5179f4c7.jpg
---

## Securing Memory Integrity with Win11 Tweaks & Tricks

 Does the memory integrity feature in Windows Security appear grayed out? Is your PC saying, "Memory integrity is off. Your device may be vulnerable," but you can't turn on the toggle? The memory integrity feature prevents malicious software from accessing high-security processes when your device is invaded by malware.

 But what causes this feature to be grayed out? In this article, we'll discuss why you cannot turn on this feature and how to identify and fix the underlying problem.

## What Causes Memory Integrity to Become Grayed Out on Windows 11?

 The primary cause of memory integrity not working on Windows 11 is your drivers. When they become outdated or corrupt, you are likely to run into this problem. Likewise, if your system is outfitted with incompatible drivers, the memory integrity feature may stop working.

 The error message itself usually explains where the problem lies, so fixing the problem is simple. You can fix faulty drivers, repair corrupted system files, update your operating system, revert an update, or remove incompatible drivers. Let's discuss some fixes to get the feature working again.

 As you apply each fix listed below, go to the Windows Security app and try enabling memory integrity again. It will help you identify what was causing the problem and fix it quickly without going through unnecessary fixes.

## 1\. Identify and Fix Driver Issues

 In most cases, the primary cause of the problem under discussion is outdated or incompatible drivers, so let's start by checking your drivers. To begin with, uninstall any third-party drivers you installed recently. After that, open the **Windows Security** app, click on the **Device security** tab from the left sidebar, and click on **Core isolation details**.

![Clicking on the Core Isolation Details Option in the Device Security Tab of Windows Security App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/1-Clicking-on-the-Core-Isolation-Details-Option-in-the-Device-Security-Tab-of-Windows-Security-App.jpg)

 Here, enable Memory integrity. If you encounter an error saying, **"Resolve any driver incompatibilities and scan again,"** click on the **Review incompatible drivers** link.

![Clicking on the Review Incompatible Drivers Link in Core Isolation Settings of Windows Security App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/2-Clicking-on-the-Review-Incompatible-Drivers-Link-in-Core-Isolation-Settings-of-Windows-Security-App.jpg)

 Then, note down any drivers Memory Integrity suspects are incompatible.

![Noting Down the List of Incompatible Drivers in the Core Isolation Settings Within Windows Security App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/3-Noting-Down-the-List-of-Incompatible-Drivers-in-the-Core-Isolation-Settings-Within-Windows-Security-App.jpg)

 Following the above checks, follow these steps to rule out driver-related problems:

1. Right-click on the Windows **Start** button and select **Device Manager**.
2. Go to the **View** tab and click **Show hidden devices**.  
![Clicking on the Show Hidden Devices Option in the View Tab Dropdown Menu Of Windows Device Manager App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/4-Clicking-on-the-Show-Hidden-Devices-Option-in-the-View-Tab-Dropdown-Menu-Of-Windows-Device-Manager-App.jpg)
3. Look for the device that has a yellow triangle on it with an exclamation mark inside it or the driver(s) with problems indicated by the Memory integrity.
4. Right-click on that device and select **Update driver**.  
![Clicking on the Update Driver Option by Right-clicking on the Incompatible Driver in Windows Device Manager App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/5-Clicking-on-the-Update-Driver-Option-by-Right-clicking-on-the-Incompatible-Driver-in-Windows-Device-Manager-App.jpg)
5. If updating the driver does not solve the problem, right-click it and select **Properties**.
6. Under the **General** tab, read the message in the **Device status** box.  
![Checking the Message in the Device Status Box Under the General Tab of Properties Window of Driver in Windows Device Manager App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/6-Checking-the-Message-in-the-Device-Status-Box-Under-the-General-Tab-of-Properties-Window-of-Driver-in-Windows-Device-Manager-App.jpg)
7. Take note of the error code and visit the [official Microsoft Support documentation](https://support.microsoft.com/en-us/topic/error-codes-in-device-manager-in-windows-524e9e89-4dee-8883-0afa-6bca0456324e) where all Device Manager-related errors are listed.
8. Find the relevant code information and apply the Microsoft recommended fix to fix the problem.

 What if applying the Microsoft recommended fix doesn't fix the problem with the driver, or there is no driver with a yellow triangle? In that case, you'll have to use third-party software to locate and uninstall the incompatible or corrupt driver.

## 2\. Find and Uninstall Incompatible Drivers

 If you cannot locate the incompatible driver in Device Manager, use a third-party program, such as Autoruns, to identify corrupt or incompatible drivers and uninstall them.

 You can follow these steps to do that:

1. Download **Autoruns** from the [Microsoft website](https://learn.microsoft.com/en-us/sysinternals/downloads/autoruns).
2. Unzip the compressed file.
3. To run the app as an administrator, right-click on its executable file and select **Run as administrator**.
4. Go to the **Drivers** tab.
5. The drivers with issues will be highlighted, so locate them.  
![Checking the Corrupt Drivers Highlighted in the Autoruns Software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/7-Clicking-on-the-Run-as-Administrator-Option-by-Right-clicking-on-the-Autoruns-Executable-File-in-Windows-File-Explorer.jpg)
6. Once they have been located, uncheck the box to disable them.  
![Unchecking the Box for the Incompatible Driver in the Drivers Tab of Autoruns App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/8-Unchecking-the-Box-for-the-Incompatible-Driver-in-the-Drivers-Tab-of-Autoruns-App.jpg)
7. If any driver gives an error when disabling, right-click it and select **Delete**.
8. Install the latest drivers from the official website or reboot your device to let Windows install them automatically.

 If you can't locate drivers identified as incompatible by Memory integrity before, the Autoruns app will facilitate finding and removing them.

## 3\. Uninstall Relevant Apps

 If uninstalling the incompatible drivers does not work, you should uninstall the apps or software you installed from the same manufacturer as the drivers. Follow these steps to do that:

1. Right-click on the Windows **Start** button and select **Apps and Features**.  
![Clicking on the Apps and Features by Right-clicking on the Windows Start Button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/9-Clicking-on-the-Apps-and-Features-by-Right-clicking-on-the-Windows-Start-Button.jpg)
2. In the list of installed apps, locate the software from the same manufacturer.
3. Upon finding them, click on the **three vertical dots** next to them and select **Uninstall**.  
![Clicking on the Uninstall Button After Clicking on the Three Vertical Dots Next to Software in the Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/10-Clicking-on-the-Uninstall-Button-After-Clicking-on-the-Three-Vertical-Dots-Next-to-Software-in-the-Windows-Settings-App.jpg)

 Uninstalling the relevant apps from the same manufacturer should resolve the issue. If it does not, ensure it isn't a Windows Update issue.

## 4\. Fix Update-Related Issues

 If incompatible or corrupt drivers aren't the problem, you should ensure your system is up-to-date and no updates are pending. To do this, right-click on the Windows **Start** button and select **Settings**. Next, navigate to **Windows Update** and click the **Check for updates** button on the right.

![Check for Updates Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Check-for-Updates-Windows.jpg)

 If they are paused, click **Resume updates** to let Windows update your system.

![Resuming Windows Update by Clicking on Resume Updates Button in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Image-4-Resuming-Windows-Update-by-Clicking-on-Resume-Button-in-Windows-Settings-App.jpg)

 Moreover, if you've encountered a problem after installing an update recently, you should uninstall it. Our guide on [uninstalling updates in Windows 10 and 11](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) explains how to do it. If pending or recently installed updates are not to blame, apply the next fix.

## 5\. Fix Corrupt System Files

 Corrupt system files are also a major cause of unforeseen issues with Windows features. The Memory integrity feature may have stopped working after a virus invaded your device and corrupted your system files. Thus, you must ensure that your system files are intact to rule out this possibility. An SFC scan can be helpful in this case.

 Search for **"Command Prompt"** in Windows Search, right-click on the **Command Prompt** in search results and click **Run as administrator**. Then type **"SFC /scannow"** and press **Enter**.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/sfc-scannow-command-1.jpg)

 Once the scan is complete, refer to our guide on repairing corrupt system files with Windows built-in tools so you can properly analyze the results.

## 6\. Reset the Windows Security App

 Issues with the Windows Security app can also interfere with the functionality of security features, like memory integrity.

 One way to rule out such issues is to reset the Windows Security app. Keep one caveat in mind, though: resetting Windows Security will revert any security customizations you've made to date. If you don't mind that, you can reset Windows Security.

 The process of resetting Windows Security is similar to [resetting any other Windows app](https://www.makeuseof.com/windows-reset-app/). Do that, and hopefully, the grayed-out memory integrity problem will resolve itself.

## 7\. Alternative Method to Enable the Memory Integrity Feature

 Using the Windows Security app isn't the only way to enable Windows' memory integrity feature. You can also adjust this setting within Registry Editor, which lets you access and modify Windows OS configuration settings. Therefore, if you are unable to turn on this feature from Windows Security, try enabling it from the Registry Editor.

 Follow these steps to enable the memory integrity feature from Registry Editor:

1. Type **"Registry Editor"** in Windows Search and open the **Registry Editor**.
2. Navigate to the following path:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\DeviceGuard\Scenarios\HypervisorEnforcedCodeIntegrity`
3. Right-click on the **Enabled** key in the right pane and select **Modify...**
4. Enter **"1"** under **Value data** if it is not already there.  
![Tweaking a Key Related to Memory Integrity in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/tweaking-a-key-realted-to-memory-integrity-in-windows-registry-editor.jpg)

 Misconfiguring keys in the Registry Editor can have unintended consequences. If you are unfamiliar with tweaking the registry, you can skip this step.

## Turn On the Memory Integrity Feature Again

 Memory integrity is a critical security feature, and if it is not enabled, it can seriously compromise the security of your device. Hopefully, by applying the fixes mentioned in the article, you will solve the problem and easily turn on Memory Integrity.

 But what causes this feature to be grayed out? In this article, we'll discuss why you cannot turn on this feature and how to identify and fix the underlying problem.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/iphoneandroid-as-windows-microphones-guide/"><u>IPhone/Android as Windows Microphones Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-software-management-using-the-windows-package-manager-wpm/"><u>Optimizing Software Management Using the Windows Package Manager (WPM)</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-navigate-and-utilize-windows-iscsi-initiator-efficiently/"><u>How to Navigate and Utilize Windows iSCSI Initiator Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/process-to-undo-system-image-fault-0x80780119/"><u>Process to Undo System Image Fault: 0X80780119</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-top-rated-free-mov-video-rotators-for-windowsmac/"><u>New 2024 Approved Top-Rated Free MOV Video Rotators for Windows/Mac</u></a></li>
<li><a href="https://some-techniques.techidaily.com/expertise-guide-for-effective-text-overlays-on-images-for-2024/"><u>Expertise Guide for Effective Text Overlays on Images for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-access-steps-for-unlocking-windows-hidden-char-personality-tracker/"><u>Mastering Access: Steps for Unlocking Windows' Hidden Char Personality Tracker</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-rpc-errors-on-windows-os/"><u>Quick Fixes for RPC Errors on Windows OS</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/2024-approved-youtube-style-essentials-download-for-free/"><u>2024 Approved  YouTube Style Essentials - Download for FREE</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-user-not-valid-windows-1111-errors/"><u>Navigating Through 'User Not Valid' Windows 11/11 Errors</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-advanced-techniques-for-simplifying-screen-capture-in-os-x/"><u>[Updated] Advanced Techniques for Simplifying Screen Capture in OS X</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-from-jokes-to-laughter-waves-how-to-craft-memes-on-9gag/"><u>[Updated] From Jokes to Laughter Waves  How to Craft Memes on 9GAG</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-elevate-your-old-computer-into-a-windows-11-powerhouse/"><u>How to Elevate Your Old Computer Into a Windows 11 Powerhouse</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-remove-forgotten-pin-of-your-xiaomi-redmi-13c-5g-by-drfone-android/"><u>In 2024, How to Remove Forgotten PIN Of Your Xiaomi Redmi 13C 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/overriding-default-no-notify-camera-behavior-in-ws11/"><u>Overriding Default No-Notify Camera Behavior in WS11</u></a></li>
<li><a href="https://windows11.techidaily.com/precise-strategies-resetting-razers-system-integration/"><u>Precise Strategies: Resetting Razer's System Integration</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-imaginary-device-issue-in-win-11-os/"><u>Resolving Imaginary Device Issue in Win 11 OS</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-enhance-visual-storytelling-techniques-for-seamless-audio-integration-in-adobe-after-effects/"><u>Updated In 2024, Enhance Visual Storytelling Techniques for Seamless Audio Integration in Adobe After Effects</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-undo-unintended-changes-to-mixer-volume-levels/"><u>How to Undo Unintended Changes to Mixer Volume Levels</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-top-10-alternatives-of-facetime-on-android-you-can-find-for-2024/"><u>New Top 10 Alternatives of FaceTime on Android You Can Find for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/monitoring-for-failed-windows-logins-a-security-checkers-guide/"><u>Monitoring for Failed Windows Logins: A Security Checker's Guide</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-forgot-iphone-passcode-again-unlock-apple-iphone-se-2022-without-passcode-now-drfone-by-drfone-ios/"><u>In 2024, Forgot iPhone Passcode Again? Unlock Apple iPhone SE (2022) Without Passcode Now | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/keeping-your-win11-devices-running-smoothly-check-list-5/"><u>Keeping Your Win11 Devices Running Smoothly - Check List #5</u></a></li>
<li><a href="https://windows11.techidaily.com/inside-outlook-and-file-explorers-new-backup-integration-in-windows-11/"><u>Inside Outlook and File Explorer's New Backup Integration in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/rapidly-access-apps-on-windows-11/"><u>Rapidly Access Apps on Windows 11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/ultimate-top-11-gk-quizzes-best-online-channels-2024/"><u>Ultimate Top 11 GK Quizzes  Best Online Channels 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/bypassing-google-account-with-vnrom-bypass-for-vivo-s17-pro-by-drfone-android/"><u>Bypassing Google Account With vnROM Bypass For Vivo S17 Pro</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-inside-the-box-logitechs-expertly-designed-4k-pro-webcam/"><u>[Updated] 2024 Approved  Inside the Box  Logitech’s Expertly Designed 4K Pro Webcam</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-strategic-approaches-broadcasting-live-sports-with-precision/"><u>[New] Strategic Approaches  Broadcasting Live Sports with Precision</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-resolving-windows-service-response-errors/"><u>Guide to Resolving Windows Service Response Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-directdraw-woes-a-users-survival-manual-for-win11/"><u>Navigating DirectDraw Woes: A User's Survival Manual for Win11</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-elevate-your-instagram-imagery-with-striking-borders/"><u>[Updated] Elevate Your Instagram Imagery with Striking Borders</u></a></li>
<li><a href="https://windows11.techidaily.com/localize-onedrive-a-step-by-step-windows-approach/"><u>Localize OneDrive: A Step-by-Step Windows Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/reconnecting-mic-during-windows-powerpoint-screencast/"><u>Reconnecting Mic During Windows PowerPoint Screencast</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-15-camera-shake-preset-for-premiere-pro/"><u>2024 Approved 15 Camera Shake Preset for Premiere Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-win1011-network-failure-code-0x800704b3/"><u>Resolving Win10/11 Network Failure: Code 0X800704B3</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/accelerated-methods-for-macs-visual-blend/"><u>Accelerated Methods for Mac's Visual Blend</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-cr2-to-jpg-conversion-using-windows-tools/"><u>Mastering the Art of CR2 to JPG Conversion Using Windows Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-windows-crash-0x800f0831-solution/"><u>Mastery Over Windows Crash: 0X800f0831 Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-network-failure-0x800704b3-in-windows-1011/"><u>Overcoming Network Failure 0X800704B3 in Windows 10/11</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-optimizing-media-experience-best-windows-phone-videos/"><u>In 2024, Optimizing Media Experience  Best Windows Phone Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/peek-inside-windows-determining-your-computers-manufacturer/"><u>Peek Inside Windows: Determining Your Computer's Manufacturer</u></a></li>
</ul></div>
