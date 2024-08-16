---
title: "Method: Rectifying Disks Not Available on Windows PCs"
date: 2024-08-15T15:44:38.052Z
updated: 2024-08-16T15:44:38.052Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Method: Rectifying Disks Not Available on Windows PCs"
excerpt: "This Article Describes Method: Rectifying Disks Not Available on Windows PCs"
keywords: Windows Disk Error Fix,Windows No Disk Found,Unavailable Disk in Windows,Solve Missing Disks Issue,Windows PC Disk Repair,Rectify Windows Disk Not Available,Troubleshoot Disk Non-Existence on PC
thumbnail: https://thmb.techidaily.com/8dc1e121faf37e853cf5b4a2c9e429100f4acf86a44ca231431cd5b1e8fdd239.jpg
---

## Method: Rectifying Disks Not Available on Windows PCs

 Disk Management is a Windows utility with which users can partition and rename drives. However, some users have reported this Windows error message pops up when they try to access Disk Management: “Disk Management could not start Virtual Disk Service (VDS).” A variation of that error message also says, “Unable to connect to Virtual Disk Service.”

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.

## 1\. Disconnect External Drives From Your PC

 First, try disconnecting all non-essential USB devices from your PC. Make sure there aren’t any external drives, USB sticks, mobile phones, or card readers connected to your PC. Then try [opening the Disk Management utility](https://www.makeuseof.com/ways-open-disk-management-windows-10/) again.

## 2\. Run System File and Image Repair Scans

 System file corruption could feasibly cause the Disk Management Virtual Disk Service error. So, check the integrity of system files on your PC with the Windows System File Checker command-line tool. That utility will also usually repair corrupted system files detected. This [how to run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide includes instructions for utilizing that tool.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command.jpg)
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->

 If SFC detects corrupted system files but can’t repair them, you may need to run a Deployment Image Service Management scan. That’s a tool for fixing issues with the Windows system image. You can run that utility by executing this Deployment Image command within the Command Prompt:

`DISM /Online /Cleanup-Image /RestoreHealth`

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Enable and Run the Virtual Disk Service

 A disabled Virtual Disk service is a common cause of the Disk Management VDS error. Disk Management can’t connect to VDS when the Virtual Disk service is disabled. So, try enabling and running the Virtual Disk service like this:

1. To access Run, press **Win + R**.
2. Enter **services.msc** inside the Run command dialog and press **Return**.
3. Scroll down and double-click on **Virtual Disk** within the Services window.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/services-window.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->
4. Select the **Automatic** setting on the **Startup type** menu.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-type-drop-down-menu.jpg)
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
5. Press **Start** within the Virtual Disk Properties window.

1. Select the window’s **Log on** tab.
2. Next, click the **Allow service to interact with desktop** checkbox to select that option.  
![The Log On tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/log-on-tab.jpg)
3. Click **Apply** to save your new Virtual Disk service settings.
4. Select the Virtual Disk Properties window’s **OK** option.
5. If you encounter the Disk Management VDS error within a remote connection environment, repeat the above steps to check the Virtual Disk service is enabled on both the local and remote PCs.

## 4\. Allow Remote Volume Management Through Windows Defender Firewall

 Windows Defender Firewall can cause the Disk Management VDS error by blocking that utility from connecting with Virtual Disk. So, make sure Remote Volume Management is allowed through that firewall on both local and remote PCs. Our [guide to allowing apps through the Windows firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) includes instructions for applying this resolution.

![The allowed apps firewall settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/firewall-options.jpg)

## 5\. Turn Off Third-Party Security Software

 If your PC includes a third-party security (antivirus) app, that software could be blocking Disk Management from establishing a VDS connection. Remember that many third-party security apps also incorporate firewalls along with antivirus components. So, try temporarily disabling both the firewall and antivirus module within your third-party security software.

 To disable the firewall part, look for a turn-off firewall option within the settings tab of your antivirus software. You can usually turn off antivirus shields by right-clicking on security apps’ system tray icons and selecting disable options on their context menus. Select to turn off the antivirus shield for about an hour if you can, and try accessing Disk Management again to see if the issue persists.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## Manage Your Drives With Disk Management Again

 The potential solutions in this guide aren’t totally guaranteed, but they’re the most likely ways to fix the Disk Management VDS error on a Windows PC. So, maybe one will get the Disk Management VDS issue sorted on your PC. Then you can manage and partition your drives with Disk Management again.

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-unveiling-8-exceptional-mirrorless-cameras-for-vloggers/"><u>[New] Unveiling 8 Exceptional Mirrorless Cameras for Vloggers</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-utilizing-zoom-services-directly-from-your-inbox-gmail-edition/"><u>[New] Utilizing Zoom Services Directly From Your Inbox - Gmail Edition</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-x-sound-engineer-desktop-suite/"><u>[New] X-Sound Engineer  Desktop Suite</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-step-into-professionalism-aiseesofts-screen-recording-made-accessible/"><u>[Updated] 2024 Approved  Step Into Professionalism  Aiseesoft's Screen Recording Made Accessible</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-tech-insight-pulling-and-keeping-twitters-vids-in-phone/"><u>2024 Approved  Tech Insight  Pulling and Keeping Twitters Vids in Phone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/android-unlock-code-sim-unlock-your-honor-magic5-ultimate-phone-and-remove-locked-screen-by-drfone-android/"><u>Android Unlock Code Sim Unlock Your Honor Magic5 Ultimate Phone and Remove Locked Screen</u></a></li>
<li><a href="https://article-files.techidaily.com/audiophiles-ultimate-narrative-guides/"><u>Audiophile's Ultimate Narrative Guides</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-microsoft-store-error-0x80072efd-on-pcs/"><u>Fixing Microsoft Store Error 0X80072EFD on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-to-correct-err-87-on-windows-loadlib/"><u>Guidelines to Correct Err 87 on Windows LoadLib</u></a></li>
<li><a href="https://windows11.techidaily.com/harness-full-potential-of-windows-11-task-manager-filters-and-themes-at-your-fingertips/"><u>Harness Full Potential of Windows 11 Task Manager: Filters & Themes at Your Fingertips</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-microsoft-store-error-0x80073d26-in-windows-10-and-11/"><u>How to Fix the Microsoft Store Error 0X80073D26 in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-maintain-notebook-visibility-on-win-1011/"><u>How to Maintain Notebook Visibility on Win 10/11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-successfully-bypass-icloud-activation-lock-on-apple-iphone-11-pro-by-drfone-ios/"><u>How to Successfully Bypass iCloud Activation Lock on Apple iPhone 11 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-intervention-for-directdraw-fails-in-windows-1011/"><u>Immediate Intervention for DirectDraw Fails in Windows 10/11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-detailed-guide-of-ispoofer-for-pogo-installation-on-itel-p40-drfone-by-drfone-virtual-android/"><u>In 2024, Detailed guide of ispoofer for pogo installation On Itel P40 | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-forgot-iphone-passcode-again-unlock-apple-iphone-8-plus-without-passcode-now-drfone-by-drfone-ios/"><u>In 2024, Forgot iPhone Passcode Again? Unlock Apple iPhone 8 Plus Without Passcode Now | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-how-to-build-your-personal-brand-on-youtube/"><u>In 2024, How to Build Your Personal Brand on YouTube</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-detect-and-remove-spyware-on-vivo-x-fold-2-drfone-by-drfone-virtual-android/"><u>In 2024, How to Detect and Remove Spyware on Vivo X Fold 2? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/launch-successfully-guiding-through-startup-services-in-windows-11/"><u>Launch Successfully: Guiding Through Startup Services in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-development-navigating-dev-drive-in-windows-11/"><u>Mastering Development: Navigating Dev Drive in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-microphone-issues-on-laptops-effective-solutions-unveiled/"><u>Mastering Microphone Issues on Laptops - Effective Solutions Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-command-execution-setting-terminal-preference/"><u>Optimize Command Execution: Setting Terminal Preference</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-connectivity-issues-via-winvpn/"><u>Overcoming Windows Connectivity Issues via WinVPN</u></a></li>
<li><a href="https://extra-tips.techidaily.com/perfecting-your-live-stream-our-picks-from-the-top-6-microphones/"><u>Perfecting Your Live Stream  Our Picks From the Top 6 Microphones</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-for-disabling-audio-playback-errors/"><u>Quick Fix for Disabling Audio Playback Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/safeguarding-your-os-managing-usb-device-use/"><u>Safeguarding Your OS: Managing USB Device Use</u></a></li>
<li><a href="https://windows11.techidaily.com/secrecy-startup-the-invisible-power-button-guide/"><u>Secrecy Startup: The Invisible Power Button Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/slash-wms-high-graphics-consumption-for-efficient-windows-11/"><u>Slash WM's High Graphics Consumption for Efficient Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-common-disk-errors-on-windows-devices/"><u>Solutions for Common Disk Errors on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-restore-active-window-defense-system/"><u>Strategies to Restore Active Window Defense System</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-reinstate-lost-mcuicnt-file-in-windows/"><u>Techniques to Reinstate Lost McUICnt File in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-rotation-rulebook-six-secrets-to-snap-spins-in-windows-11/"><u>The Rotation Rulebook: Six Secrets to Snap-Spins in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/turbo-steam-downloads-overcoming-frustrating-speed-halts/"><u>Turbo Steam Downloads: Overcoming Frustrating Speed Halts</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-2024-approved-discovering-the-value-a-comprehensive-guide-to-using-pexelscom-imagery/"><u>Updated 2024 Approved Discovering the Value A Comprehensive Guide to Using Pexels.com Imagery</u></a></li>
</ul></div>
