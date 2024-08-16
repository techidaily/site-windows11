---
title: "Reversal of Extra Privileges: Win11 Standardization Tutorial"
date: 2024-08-15T15:58:26.776Z
updated: 2024-08-16T15:58:26.776Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reversal of Extra Privileges: Win11 Standardization Tutorial"
excerpt: "This Article Describes Reversal of Extra Privileges: Win11 Standardization Tutorial"
keywords: Win11 Standardization Guide,Removing Extra Windows Privileges,Win11 Security Best Practices,Streamlining Windows Operations,Secure Win11 User Accounts,Standardizing Win11 Settings,Privilege Reduction in Win11
thumbnail: https://thmb.techidaily.com/805432a26a63c24a3ad7f94c306f1a1291a2364beb1c1710fc99d1f9d71ae26e.jpg
---

## Reversal of Extra Privileges: Win11 Standardization Tutorial

 Having issues with apps or programs not running properly on your Windows computer? Resetting Windows Update permissions could be the solution you need. Similarly, if you're troubleshooting user profile problems, you can restore user permissions.

 This article covers three different methods to reset all user permissions – using the Icacls command, the Secedit command, and the Subinacl tool.

Let's now explore them in detail.

## 1\. Run the Icacls Command

 The Icacls command allows you to view, modify, and reset file system permissions on files and folders. To reset Windows Update permissions using this command, you will first have to [take ownership of the folders on Windows](https://www.makeuseof.com/windows-10-11-own-folder/) . Then [open an elevated Command Prompt on Windows](https://www.makeuseof.com/windows-run-command-prompt-admin/) and type in the following command:

`icacls * /t /q /c /reset`

 Now press Enter on your keyboard to execute the command. This will reset all user permissions to default for every folder, subfolder, and file within the current working directory.

In the above command, here are the parameters explained:

* \* – This is a wildcard character that includes all folders within the current directory.
* /t – It targets all the subfolders and files within the current folder.
* /q – Run command without displaying success messages.
* /c – Continues the operation even if errors occur.
* /reset – This parameter resets the permission options to their default values.

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Run the Secedit command

 Windows provides the Secedit command to configure and analyze system security. To reset all user permissions using this command, run the command prompt with admin access, then type in the following command:

![Run the Secedit command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-the-secedit-command.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->

`secedit /configure /cfg %windir%\inf\defltbase.inf /db defltbase.sdb /verbose`

 Now press Enter to execute the command. Wait for the process to finish and restart your computer. This will reset the user permissions to the default system settings.

<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Run the Subinacl Tool

 If you're not comfortable using the command prompt, you may use the Subinacl tool. This is a command-line utility from Microsoft that can be used to reset user permissions. Here's how to do it:

1. [Download the Subinacl tool from Microsoft's webpage](https://web.archive.org/web/20190830103837/http://www.microsoft.com/en-us/download/confirmation.aspx?id=23510) . When you open the page, the download starts automatically. If not, wait 30 seconds and click the link.
2. Once downloaded, double-click on the installer package. This will open the installation wizard.  
![Open the installation wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-the-installation-wizard.jpg)
3. Click on**Next** and then accept the license agreement terms.  
![Install the Subinacl tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-the-subinacl-tool.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
4. Next, copy and paste the following path into the Destination folder:  
`C:\Windows\System32`  
 Note: If you have installed Windows on a different drive, use that path instead.
5. Now click on**Install now** and wait for the Subinacl tool to be installed. This may take several minutes, so be patient.

1. When the installation is complete,[open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and type in the following commands:  
`subinacl /subkeyreg HKEY_LOCAL_MACHINE /grant=administrators=f  
subinacl /subkeyreg HKEY_CURRENT_USER /grant=administrators=f  
subinacl /subkeyreg HKEY_CLASSES_ROOT /grant=administrators=f  
subinacl /subdirectories %SystemDrive% /grant=administrators=f  
subinacl /subkeyreg HKEY_LOCAL_MACHINE /grant=system=f  
subinacl /subkeyreg HKEY_CURRENT_USER /grant=system=f  
subinacl /subkeyreg HKEY_CLASSES_ROOT /grant=system=f  
subinacl /subdirectories %SystemDrive% /grant=system=f`
2. On the Save As window, set the File name to**Reset.cmd** and then select**All Files** from the drop-down menu next to it.  
![Reset Windows Update permissions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-update-permissions.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
3. Next, select**Desktop** from the left pane and click on**Save** .
4. Now double-click on it to reset the user permissions to default.
5. This may take a while to complete the procedure, so wait for it to finish.

 Once done, close any running program, and then restart your computer. Your Windows Update permissions will be reset to their default settings. These are three different methods you can use to reset the user permission settings on Windows.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## Restore User Permissions to Default on Windows

 User permissions play a crucial role in computer security. If you're experiencing user permission issues, you must reset them to their default settings. This guide helps you reset all user permissions on Windows using three different methods. You can use the ICACLS command, Secedit command, or Subinacl tool, depending on your preference.


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
<li><a href="https://instagram-videos.techidaily.com/updated-elevate-your-content-game-with-these-instagram-story-tips/"><u>[Updated] Elevate Your Content Game with These Instagram Story Tips</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-best-nintendo-switch-fighter-ranks-max-156/"><u>[Updated] In 2024, Best Nintendo Switch Fighter Ranks (Max 156)</u></a></li>
<li><a href="https://tech-revival.techidaily.com/dispelling-myths-the-consistent-capability-of-chatgpt-as-confirmed-by-openai/"><u>Dispelling Myths: The Consistent Capability of ChatGPT as Confirmed by OpenAI</u></a></li>
<li><a href="https://sound-issues.techidaily.com/effortless-fixes-for-headphone-noise-problems-get-quiet-audio-now/"><u>Effortless Fixes for Headphone Noise Problems - Get Quiet Audio Now!</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-compatibility-nightmares-in-windows-without-troubleshooting-tools/"><u>Fix Compatibility Nightmares in Windows without Troubleshooting Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-device-not-reset-issue-in-win-11/"><u>Fixing 'Device Not Reset' Issue in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-microsoft-store-error-0x80072efd-on-pcs/"><u>Fixing Microsoft Store Error 0X80072EFD on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-store-failure-codes/"><u>Fixing Windows Store Failure Codes</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-self-clearing-windows-recycle-bin/"><u>Guide to Self-Clearing Windows Recycle Bin</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-to-correct-err-87-on-windows-loadlib/"><u>Guidelines to Correct Err 87 on Windows LoadLib</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-no-supported-devices-problem-in-windows-update/"><u>Handling 'No Supported Devices' Problem in Windows Update</u></a></li>
<li><a href="https://windows11.techidaily.com/harness-full-potential-of-windows-11-task-manager-filters-and-themes-at-your-fingertips/"><u>Harness Full Potential of Windows 11 Task Manager: Filters & Themes at Your Fingertips</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-microsoft-store-error-0x80073d26-in-windows-10-and-11/"><u>How to Fix the Microsoft Store Error 0X80073D26 in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-halt-windows-desktop-keys-effectively/"><u>How to Halt Windows Desktop Keys Effectively</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-repair-unable-to-fetch-error-in-nvidia-geforce-experience/"><u>How To Repair 'Unable To Fetch' Error in NVIDIA GeForce Experience</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-stop-life360-from-tracking-you-on-vivo-v29-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Vivo V29? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-intervention-for-directdraw-fails-in-windows-1011/"><u>Immediate Intervention for DirectDraw Fails in Windows 10/11</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-how-to-transfer-from-apple-iphone-12-mini-to-samsung-simplified-guide-drfone-by-drfone-transfer-from-ios/"><u>In 2024, How To Transfer From Apple iPhone 12 mini to Samsung Simplified Guide | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-mastering-android-device-manager-the-ultimate-guide-to-unlocking-your-samsung-galaxy-a15-4g-device-by-drfone-android/"><u>In 2024, Mastering Android Device Manager The Ultimate Guide to Unlocking Your Samsung Galaxy A15 4G Device</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-mastering-film-making-top-video-cameras/"><u>In 2024, Mastering Film Making  Top Video Cameras</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-step-by-step-manual-kickstart-your-bite-sized-gadget-reviews-channel/"><u>In 2024, Step-by-Step Manual  Kickstart Your Bite-Sized Gadget Reviews Channel</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-the-ultimate-guide-to-itel-a05s-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Ultimate Guide to Itel A05s Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-tips-and-tricks-for-locating-recent-videos-youve-liked/"><u>In 2024, Tips & Tricks for Locating Recent Videos You've Liked</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unlocking-the-power-of-shareable-internet-humor/"><u>In 2024, Unlocking the Power of Shareable Internet Humor</u></a></li>
<li><a href="https://vp-tips.techidaily.com/inaugural-zooid-creations-ranked-for-2024/"><u>Inaugural Zooid Creations Ranked for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/masterful-windows-11-app-launch-strategies/"><u>Masterful Windows 11 App Launch Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-development-navigating-dev-drive-in-windows-11/"><u>Mastering Development: Navigating Dev Drive in Windows 11</u></a></li>
<li><a href="https://extra-support.techidaily.com/mastering-instagram-reels-incorporating-tracks-seamlessly-for-2024/"><u>Mastering Instagram Reels  Incorporating Tracks Seamlessly for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-repairing-windows-email-failures-error-code-0x800713f/"><u>Mastering the Art of Repairing Windows' Email Failures (Error Code 0X800713F)</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-task-scheduler-for-file-batch-execution/"><u>Mastering Windows Task Scheduler for File Batch Execution</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-two-users-shared-ms-login-fails/"><u>Navigating Through Two Users' Shared MS Login Fails</u></a></li>
<li><a href="https://review-topics.techidaily.com/oneplus-data-recovery-recover-lost-data-from-oneplus-12r-by-fonelab-android-recover-data/"><u>OnePlus Data Recovery – recover lost data from OnePlus 12R</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-command-execution-setting-terminal-preference/"><u>Optimize Command Execution: Setting Terminal Preference</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-connectivity-issues-via-winvpn/"><u>Overcoming Windows Connectivity Issues via WinVPN</u></a></li>
<li><a href="https://windows11.techidaily.com/proven-tactics-for-heic-to-jpeg-conversion-process-on-windows-11-systems/"><u>Proven Tactics for Heic to JPEG Conversion Process on Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/redefining-phones-role-in-windows-11-networking/"><u>Redefining Phones' Role in Windows 11 Networking</u></a></li>
<li><a href="https://windows11.techidaily.com/reinvigorate-discolored-volume-settings-in-win/"><u>Reinvigorate Discolored Volume Settings in Win</u></a></li>
<li><a href="https://windows11.techidaily.com/safeguarding-your-os-managing-usb-device-use/"><u>Safeguarding Your OS: Managing USB Device Use</u></a></li>
<li><a href="https://windows11.techidaily.com/secrecy-startup-the-invisible-power-button-guide/"><u>Secrecy Startup: The Invisible Power Button Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-a-static-backdrop-on-modern-windows-11-pcs/"><u>Secure a Static Backdrop on Modern Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/slash-wms-high-graphics-consumption-for-efficient-windows-11/"><u>Slash WM's High Graphics Consumption for Efficient Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-common-disk-errors-on-windows-devices/"><u>Solutions for Common Disk Errors on Windows Devices</u></a></li>
<li><a href="https://driver-install.techidaily.com/startech-fixing-windows-11-8-and-7-drivers-resolved/"><u>StarTech: Fixing Windows 11, 8, & 7 Drivers (Resolved)</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-restore-active-window-defense-system/"><u>Strategies to Restore Active Window Defense System</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-prevent-overheating-in-w11-pcs/"><u>Techniques to Prevent Overheating in W11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-reinstate-lost-mcuicnt-file-in-windows/"><u>Techniques to Reinstate Lost McUICnt File in Windows</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-future-of-podcasts-starts-with-smart-name-generation/"><u>The Future of Podcasts Starts with Smart Name Generation</u></a></li>
<li><a href="https://windows11.techidaily.com/the-rotation-rulebook-six-secrets-to-snap-spins-in-windows-11/"><u>The Rotation Rulebook: Six Secrets to Snap-Spins in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/turbo-steam-downloads-overcoming-frustrating-speed-halts/"><u>Turbo Steam Downloads: Overcoming Frustrating Speed Halts</u></a></li>
<li><a href="https://windows11.techidaily.com/uncovering-and-correcting-cant-access-mail-errors-in-windows-11-mail-app/"><u>Uncovering and Correcting Can't Access Mail Errors in Windows 11 Mail App</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-transition-phasing-out-old-traits/"><u>Windows Transition: Phasing Out Old Traits</u></a></li>
</ul></div>
