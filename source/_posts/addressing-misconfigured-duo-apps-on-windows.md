---
title: Addressing Misconfigured Duo Apps on Windows
date: 2024-07-11T21:22:10.252Z
updated: 2024-07-12T21:22:10.252Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Misconfigured Duo Apps on Windows
excerpt: This Article Describes Addressing Misconfigured Duo Apps on Windows
keywords: Fix Duo Mismatch,Resolve Duo Errors,Unlock Duo Configs,Adjust Duo Settings,Correct Duo Login,Optimize Duo Apps,Streamline Duo Windows
thumbnail: https://thmb.techidaily.com/0464d20c8383250ad5eec7dae311ce3366a21c1ceecc558739dbb36535dbfcf9.jpg
---

## Addressing Misconfigured Duo Apps on Windows

 It's frustrating when you can't launch your favorite apps and programs on Windows due to the "Side-by-side configuration is incorrect" error. While determining the exact cause of this error can be difficult, it is possible to resolve it.

 In most cases, the “Side-by-side configuration is incorrect” error occurs due to a damaged Visual C++ package or a compatibility issue. However, there can be other reasons for it. So, what can you do to resolve this unforeseen error on Windows? Let's find out.

## 1\. Reinstall Microsoft Visual C++ Packages

 Problems with the current Visual C++ packages on your PC can often result in the “Side-by-side configuration is incorrect” error on Windows. If that's the case, you must reinstall the problematic Visual C++ package on your computer. To do so, you'll need to find its version number using Event Viewer. Here's how you can go about it.

1. Press**Win + S** to open the search menu.
2. Type**event viewer** in the search box and select the first result that appears.
3. Use the left pane to navigate to**Custom Views > Summary page events** .  
![Event Viewer on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Event-Viewer-on-Windows.jpg)
4. Choose the most recent side-by-side error from the middle pane and note down the version number under the**General** tab.
5. Open up your web browser and head over to the [Microsoft Visual C++ Redistributable download page](https://learn.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170) .
6. Download and install the Visual C++ package corresponding to your version number.

 Restart your PC after this (see [how to restart your Windows PC](https://www.makeuseof.com/windows-restart-methods/) ) and try to launch your app or program one more time.

## 2\. Run the SFC and DISM Scans

 Corrupted or missing system files on your computer can also trigger such errors. Fortunately, Windows includes a useful command-line utility called SFC (or System File Checker) scan for such occasions. It can automatically detect any damaged system files on your PC and replace them with their cached versions.

To run the SFC scan on your computer:

1. Press**Win + X** to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt shows up.
4. In the console, type**sfc /scannow** and press**Enter** .  
![Run SFC Scan on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Run-SFC-Scan-on-Windows.jpg)

 Wait for the scan to complete and then run the DISM (or Deployment Image Servicing and Management) scan by entering the following command:

`DISM.exe /Online /Cleanup-image /Restorehealth`

 After the process is complete, exit the Command Prompt window and restart your PC. The error should not appear anymore after the reboot.

## 3\. Run the Program Compatibility Troubleshooter

 If the “Side-by-side configuration is incorrect” error only appears when you try to launch a specific program, you can run the program compatibility troubleshooter on Windows. It’ll try to fix any compatibility issues with your program and help you fix the error. Here’s how you can run it.

1. Right-click on your app or program that’s producing the error and select**Troubleshoot compatibility** .
2. In the Program Compatibility Troubleshooter window, select**Troubleshoot program** .
3. Mark the checkbox that reads **The program worked in earlier versions of Windows but won’t install or run now** and hit**Next** .
4. Follow the on-screen prompts to run the troubleshooter and see if the error occurs again.  
![Program Compatibility Troubleshooter Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Program-Compatibility-Troubleshooter-Windows.jpg)

## 4\. Repair the Problematic App

 If the Windows troubleshooter fails to find any problems, you can try repairing the problematic app on Windows. Here's how to do it.

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Apps** tab.
3. Go to**Installed apps** .
4. Scroll down to locate the problematic app on the list. Click the**three-dot menu icon** next to it and select**Advanced options** .
5. Scroll down to the Reset section and click on**Repair** .  
![Repair App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Repair-App-on-Windows.jpg)

 You should see a right checkmark next to the Repair button once the process is complete.

 Alternatively, you can repair your apps and programs from Control Panel. To learn more about this, check our guide on [how to repair apps and programs on Windows](https://www.makeuseof.com/windows-repair-apps-programs/) and follow the steps outlined there.

## 5\. Reinstall the Problematic App

 Repairing the app may not help much if the existing app data is corrupted or missing. In that case, your only option is to uninstall the problematic app and install it again.

1. Press**Win + S** to open the search menu.
2. Type in the name of your app or program and select**Uninstall** from the right pane.
3. Select**Uninstall** again to confirm.  
![Uninstall App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Uninstall-App-on-Windows.jpg)

 Head over to Microsoft Store and install the app again. Following this, the error should not bother you.

## 6\. Scan for Malware

 If your computer is infected with malware, you may encounter such errors when launching apps and programs. To check for this possibility, you can run a full system scan of your PC with Windows Defender. You can also use one of the [best third-party antivirus programs for Windows](https://www.makeuseof.com/tag/best-antivirus-for-windows-10/) for this.

 If the scan uncovers anything suspicious, take the recommended steps to fix the issue and reboot your PC after that.

## 7\. Install Pending Windows Updates

 Microsoft regularly releases updates for the Windows operating system. Aside from new features and security patches, these updates also bring much-needed fixes for bugs and other errors. You can try updating Windows to its most recent version to see if that makes a difference.

 Press**Win + I** to open the Settings app and navigate to the**Windows Update** section. Click on**Check for updates** to download and install pending updates.

![Check for System Updates on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Check-for-System-Updates-on-Windows.jpg)

## 8\. Perform a System Restore

 Windows System Restore performs a backup of the entire system on a regular basis. You can use it to revert your system to a point before the error first started appearing.

To perform a system restore on Windows:

1. Press**Win + R** to open the Run dialog box.
2. Type**sysdm.cpl** in the box and press**Enter** .
3. In the System Properties window, switch to the**System Protection** tab.
4. Click on**System Restore** .
5. Click**Next** .
6. Select a restore point before the first appeared and hit**Next** .
7. Check all the details and hit**Finish** .  
![System Restore Dialog on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/System-Restore-Dialog-on-Windows.jpg)

 Windows will restart and revert to the specified restore point. Following that, the error should be resolved.

## Start Using Your Apps Again

 By applying the above fixes, you should be able to fix the “Side-by-side configuration is incorrect” error in no time. However, if none of the solutions work, you may have to reset your Windows computer as a last resort.


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
<li><a href="https://extra-tips.techidaily.com/premier-plugins-for-dynamic-type-design-in-ae/"><u>Premier Plugins for Dynamic Type Design in AE</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-expert-tips-for-slide-presentation-with-youtube-for-2024/"><u>[Updated] Expert Tips for Slide Presentation with YouTube for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/activation-indicators-for-windows-11-systems/"><u>Activation Indicators for Windows 11 Systems</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-streamlined-teaching-mastering-lecture-capture-on-mac-systems/"><u>[Updated] Streamlined Teaching  Mastering Lecture Capture on Mac Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tuning-windows-11-taskbar-date-and-time-display/"><u>Fine-Tuning Windows 11 Taskbar Date and Time Display</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-speed-and-ban-lags-in-windows-11-installation/"><u>Boost Speed & Ban Lags in Windows 11 Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/assessment-of-differences-onsite-vs-cloud-based-windows-downloads/"><u>Assessment of Differences: Onsite vs Cloud-Based Windows Downloads</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-dissecting-the-hidden-mechanics-behind-youtubes-popularity-index/"><u>2024 Approved  Dissecting the Hidden Mechanics Behind YouTube's Popularity Index</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-classics-seamless-integration-of-achievements-using-retroarch-software/"><u>Boosting Classics: Seamless Integration of Achievements Using Retroarch Software</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-diablos-first-epic-a-novices-primer/"><u>Decoding Diablo's First Epic: A Novice's Primer</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-tweaking-your-web-privacy-via-proxies-in-win-11/"><u>Expert Advice: Tweaking Your Web Privacy via Proxies in Win 11</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-fix-apple-iphone-13-pro-max-unavailable-issue-with-ease-by-drfone-ios/"><u>In 2024, How To Fix Apple iPhone 13 Pro Max Unavailable Issue With Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/advancing-mouse-functionality-through-clicklock-mechanism/"><u>Advancing Mouse Functionality Through ClickLock Mechanism</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-your-honor-magic-v2-auto-does-not-work-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do if Your Honor Magic V2 Auto Does Not Work | Dr.fone</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-premium-quick-insight-for-pics-on-win-11/"><u>[Updated] Premium Quick Insight for Pics on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-create-custom-snap-layouts-in-windows-with-powertoys/"><u>How to Create Custom Snap Layouts in Windows With PowerToys</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-tips-avoiding-discords-auto-start-and-update-checks/"><u>Windows Tips: Avoiding Discord's Auto-Start & Update Checks</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-clashes-in-windows-desktop-ordering/"><u>Avoid Clashes in Windows Desktop Ordering</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-mistakes-to-dodge-on-windows-11-upgrade/"><u>Essential Mistakes to Dodge on Windows 11 Upgrade</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-quiet-browser-alerts-chrome-guide-for-windows/"><u>How to Quiet Browser Alerts: Chrome Guide for Windows</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-webcam-wizardry-on-macbook-pro/"><u>[Updated] In 2024, Webcam Wizardry on MacBook Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-firewall-settings-integration-into-windows-11s-ui/"><u>Advanced Firewall Settings Integration Into Windows 11'S UI</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-latest-guide-on-ipad-23-and-apple-iphone-6-plus-icloud-activation-lock-bypass-by-drfone-ios/"><u>In 2024, Latest Guide on iPad 2/3 and Apple iPhone 6 Plus iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://windows11.techidaily.com/1719291887266-eliminating-obstacles-in-capturing-whole-screen-with-windows-snipping-tool/"><u>Eliminating Obstacles in Capturing Whole-Screen with Windows Snipping Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/establishing-safe-operating-temps-for-windows-devices/"><u>Establishing Safe Operating Temps for Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/breakdown-utilizing-bluescreenview-for-professionals/"><u>Breakdown: Utilizing BlueScreenView for Professionals</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-for-accessing-windows-11s-policy-editor/"><u>Easy Steps for Accessing Windows 11'S Policy Editor</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-fixes-regaining-full-synapse-functionality/"><u>Essential Fixes: Regaining Full Synapse Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-windows-signing-you-in-with-a-temporary-profile/"><u>How to Fix Windows Signing You In With a Temporary Profile</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-selecting-a-best-fit-video-codec-in-windows/"><u>Essential Guide to Selecting a Best Fit Video Codec in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/esd-to-iso-converting-esd-files-in-windows/"><u>ESD to ISO: Converting ESD Files in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-guide-to-fix-windows-non-functional-start/"><u>A Step-by-Step Guide to Fix Window's Non-Functional Start</u></a></li>
<li><a href="https://unlock-android.techidaily.com/delete-gmail-account-withwithout-password-on-vivo-y100i-power-5g-by-drfone-android/"><u>Delete Gmail Account With/Without Password On Vivo Y100i Power 5G</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-strategies-for-creating-hit-memes/"><u>2024 Approved  Strategies for Creating Hit Memes</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-system-performance-essential-tips-for-installing-optional-windows-components/"><u>Elevate Your System Performance: Essential Tips for Installing Optional Windows Components</u></a></li>
</ul></div>
