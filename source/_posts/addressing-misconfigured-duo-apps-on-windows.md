---
title: Addressing Misconfigured Duo Apps on Windows
date: 2024-08-15T16:09:02.393Z
updated: 2024-08-16T16:09:02.393Z
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

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->

 You should see a right checkmark next to the Repair button once the process is complete.

 Alternatively, you can repair your apps and programs from Control Panel. To learn more about this, check our guide on [how to repair apps and programs on Windows](https://www.makeuseof.com/windows-repair-apps-programs/) and follow the steps outlined there.

## 5\. Reinstall the Problematic App

 Repairing the app may not help much if the existing app data is corrupted or missing. In that case, your only option is to uninstall the problematic app and install it again.

1. Press**Win + S** to open the search menu.
2. Type in the name of your app or program and select**Uninstall** from the right pane.
3. Select**Uninstall** again to confirm.  
![Uninstall App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Uninstall-App-on-Windows.jpg)
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Head over to Microsoft Store and install the app again. Following this, the error should not bother you.

## 6\. Scan for Malware

 If your computer is infected with malware, you may encounter such errors when launching apps and programs. To check for this possibility, you can run a full system scan of your PC with Windows Defender. You can also use one of the [best third-party antivirus programs for Windows](https://www.makeuseof.com/tag/best-antivirus-for-windows-10/) for this.

 If the scan uncovers anything suspicious, take the recommended steps to fix the issue and reboot your PC after that.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## 7\. Install Pending Windows Updates

 Microsoft regularly releases updates for the Windows operating system. Aside from new features and security patches, these updates also bring much-needed fixes for bugs and other errors. You can try updating Windows to its most recent version to see if that makes a difference.

 Press**Win + I** to open the Settings app and navigate to the**Windows Update** section. Click on**Check for updates** to download and install pending updates.

![Check for System Updates on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Check-for-System-Updates-on-Windows.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->

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
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Windows will restart and revert to the specified restore point. Following that, the error should be resolved.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-crafting-an-easy-to-use-youtube-subscription-tagline/"><u>[New] 2024 Approved  Crafting an Easy-to-Use YouTube Subscription Tagline</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-the-art-of-hashtagging-strategies-for-maximum-impact-on-facebook/"><u>[New] 2024 Approved  The Art of Hashtagging  Strategies for Maximum Impact on Facebook</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-get-savvy-with-chromebook-snaps-explore-these-4-methods-for-2024/"><u>[New] Get Savvy with Chromebook Snaps - Explore These 4 Methods for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-streamlined-social-media-management-our-picks-of-the-best-8-planners/"><u>[New] Streamlined Social Media Management  Our Picks of the Best 8 Planners</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-best-gif-fetchers-on-ios-iphone-x-compatible-guide/"><u>[Updated] Best GIF Fetchers on iOS  IPhone X-Compatible Guide</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-demystifying-the-instagram-selfie-process-for-2024/"><u>[Updated] Demystifying the Instagram Selfie Process for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-unveiling-todays-instagram-trends-and-tags/"><u>[Updated] Unveiling Today's #Instagram Trends and Tags</u></a></li>
<li><a href="https://tech-revival.techidaily.com/a-comprehensive-guide-to-what-usechatgpt-copilot-can-accomplish-in-one-click/"><u>A Comprehensive Guide to What UseChatGPT Copilot Can Accomplish in One Click</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-no-audio-devices-in-windows/"><u>Addressing 'No Audio Devices' In Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/blocking-windows-update-prompts/"><u>Blocking Windows Update Prompts</u></a></li>
<li><a href="https://windows11.techidaily.com/cherishing-the-slumber-of-your-computer/"><u>Cherishing the Slumber of Your Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-windows-for-wordpad-operability/"><u>Exploring Windows for WordPad Operability</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/full-guide-on-mirroring-your-realme-gt-neo-5-se-to-your-pcmac-drfone-by-drfone-android/"><u>Full Guide on Mirroring Your Realme GT Neo 5 SE to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://buynow-info.techidaily.com/fusing-fashion-and-functionality-an-expert-review-on-the-trendy-efficient-swagtrn-swagger-electric-scooter-for-modern-commuting/"><u>Fusing Fashion and Functionality: An Expert Review on the Trendy, Efficient Swagtrn Swagger Electric Scooter for Modern Commuting</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-windows-11-theme-treasures-revealed/"><u>Hidden Windows 11 Theme Treasures Revealed</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-can-i-use-a-fake-gps-without-mock-location-on-infinix-note-30-5g-drfone-by-drfone-virtual-android/"><u>How Can I Use a Fake GPS Without Mock Location On Infinix Note 30 5G? | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-can-we-bypass-oppo-f25-pro-5g-frp-by-drfone-android/"><u>In 2024, How Can We Bypass Oppo F25 Pro 5G FRP?</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-show-wi-fi-password-on-realme-narzo-n53-by-drfone-android/"><u>In 2024, How to Show Wi-Fi Password on Realme Narzo N53</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-iphone-11-with-a-mask-on-drfone-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 11 with a Mask On | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-innovative-watermarks-for-impactful-insta-imagery/"><u>In 2024, Innovative Watermarks for Impactful Insta Imagery</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-error-handling-fixing-missing-updates-error-code-0x80070003/"><u>Mastering Windows Error Handling: Fixing Missing Updates (Error Code: 0X80070003)</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-internet-options-tweaks-for-windows-11/"><u>Mastery of Internet Options Tweaks for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-common-windo-errors-quickly/"><u>Navigating Through Common Windo Errors, Quickly</u></a></li>
<li><a href="https://extra-support.techidaily.com/premier-accessible-stopwatches-for-2024/"><u>Premier Accessible Stopwatches for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/preserving-calculator-precedence-on-windows-systems/"><u>Preserving Calculator Precedence on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-guide-to-restore-windows-11-troubleshooters/"><u>Quick FIX Guide to Restore Windows 11 Troubleshooters</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-win-ethernet-no-internet-error/"><u>Resolving Win Ethernet No Internet Error</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-smooth-operation-fix-frozen-epic-games-launcher/"><u>Securing Smooth Operation: Fix Frozen Epic Games Launcher</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-rearranged-characters-in-windows-os/"><u>Solutions for Rearranged Characters in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-ipad-image-import-issues-in-windows-1111-pro/"><u>Solving iPad Image Import Issues in Windows 11/11 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-docx-to-pdf-migration-for-windows-users/"><u>Step-by-Step DOCX to PDF Migration for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-to-switching-notepad-to-dark-theme-in-windows-11/"><u>Step-by-Step Guide to Switching Notepad to Dark Theme in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-github-desktop-on-windows-11-os/"><u>The Ultimate Guide to GitHub Desktop on Windows 11 OS</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-oppo-reno-10-5g-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Oppo Reno 10 5G? | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/top-strategies-for-in-depth-nba-game-watching-for-2024/"><u>Top Strategies for In-Depth NBA Game Watching for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-device-synergy-with-google-nearby-sharing/"><u>Unlocking Device Synergy with Google Nearby Sharing</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-windows-blue-screen-error-0x8007007e/"><u>Unraveling the Mystery of Windows Blue Screen Error: 0X8007007E</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/vlc-media-recording-evaluation/"><u>VLC Media Recording Evaluation</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-wisdom-efficiently-eliminate-partitioned-areas-on-your-pc/"><u>Windows Wisdom: Efficiently Eliminate Partitioned Areas on Your PC</u></a></li>
</ul></div>
