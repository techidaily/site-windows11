---
title: Easy Steps to Activate/Deactivate Secure Boot & TPM in VirtualBox
date: 2024-07-29T04:27:59.753Z
updated: 2024-07-30T04:27:59.753Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Easy Steps to Activate/Deactivate Secure Boot & TPM in VirtualBox
excerpt: This Article Describes Easy Steps to Activate/Deactivate Secure Boot & TPM in VirtualBox
keywords: VirtualBox Secure Boot Enable,TPM VirtualBox Setup,VM Boost Security,Activating Secure Boot,Disabling TPM VirtualBox,TPM Management in VirtualBox,Secure Boot Configuration Vbox
thumbnail: https://thmb.techidaily.com/79c7e594da2bcc4e0b5a712ad425c9a3c9c769d4308cac3ac9d4efb24f911715.jpg
---

## Easy Steps to Activate/Deactivate Secure Boot & TPM in VirtualBox

 VirtualBox released version 7.0 in October 2022\. It is the first hypervisor to support the emulation of TPM chips along with all the other system components. VirtualBox also offers a Secure Boot feature in EFI mode for virtual machines. The main reason behind these two features was Microsoft's list of elaborate system requirements for Windows 11.

 Without emulation of the TPM 2.0 chip, users couldn't install Windows 11 on a virtual machine. But with VirtualBox 7.0 it is possible to enable Secure Boot and TPM for any Windows virtual machine. This post will elaborate on the methods to enable or disable TPM and Secure Boot for any VirtualBox virtual machine.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Why Does Windows 11 Need TPM and Secure Boot?

 Windows 11 needs both a TPM chip and Secure Boot to offer robust protection against threats and not allow any malware to run when the system boots up. Secure Boot only allows signed drivers to load and the TPM chip helps in BitLocker drive data protection. So, both these features are pretty important from a security standpoint. Check out our guide on[what Secure Boot is and how it works](https://www.makeuseof.com/what-is-secure-boot-how-does-it-work/) for more information.

 While Windows 11 can work without Secure Boot and a TPM 2.0 chip, it won't be able to offer that extra layer of system protection it would do otherwise. Many features like Core-isolation, Data Encryption won't work. If you want to enable or disable these features for Windows 10 or 11 virtual machines, you can do so in VirtualBox 7.0.

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Enable or Disable Secure Boot and TPM Support in VirtualBox 7.0

 Repeat the following steps to enable TPM 2.0 and Secure Boot in VirtualBox.

1. Press the**Win** key and search VirtualBox. Click on the first relevant search result to launch the app.
2. Click on a Windows virtual machine and then click on the**Settings** icon.
3. Navigate to the**System** settings option.
4. Find the**TPM** option. If it is set to none, click on the**arrow** icon to open the drop-down menu.
5. Select the TPM**v2.0** option from the list. Windows 11 won't work with anything lower but if you are using Windows 10 then you can pick**v1.2** from the list.
6. Scroll down and locate the**Extended Features** section. Click on the**Enable EFI (special OSes only)** option check box.
7. Then click on the**Enable Secure Boot** option check box.  
![Enable Secure Boot and TPM Support in VirtualBox 7.0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/enable-secure-boot-and-tpm-support-in-virtualbox-7-0.jpg)
8. Now, click on the**OK** button. The settings window will close automatically.
9. Go to the top area and click on the**Start** button to power on the Windows virtual machine.
10. Now, press the Win key and search Security. Open the**Windows security** app.
11. Navigate to the left-hand side menu and click on the**Device Security** option. Here, all Windows security features will be active.
12. To disable TPM and Secure Boot, reopen the virtual machine settings and set the TPM version to**None** . Uncheck the**Enable EFI (special OSes only)** option check box. Click on**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### An Alternative Method to Check if TPM Is Active in the Windows Virtual Machine

Here's how to check TPM on Windows 11 virtual machine:

1. Press the**Win + R** key to launch the Run command box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**TPM.msc** and press the**Enter** key.  
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
![check TPM on Windows 11 virtual machine 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-1.jpg)
2. TPM utility will launch. Navigate to the Manufacturer Information section.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![check TPM on Windows 11 virtual machine 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-2.jpg)
3. If the Specification version entry showcases 2.0, it means that TPM chip emulation is successful.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
## Manage TPM and Secure Boot Features in VirtualBox With Ease

 You can choose to keep both features active or not. After installing Windows 11 as a virtual machine, you can turn TPM and Secure Boot off and not face any issues with the operating system. However, remember that these are important from a security perspective.


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
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-mac-excellence-unleashed-screenflows-influence-on-development/"><u>[Updated] 2024 Approved  Mac Excellence Unleashed  ScreenFlow’s Influence on Development</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-miui-screen-recorder-review/"><u>[Updated] 2024 Approved  MIUI Screen Recorder Review</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-discover-optimal-free-webm-players-for-your-browser-for-2024/"><u>[Updated] Discover Optimal Free WebM Players for Your Browser for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-xiaomi-11-a-new-era-of-high-fidelity-video-recording/"><u>[Updated] Xiaomi 11  A New Era of High Fidelity Video Recording</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-microsofts-hololens-journey-from-vision-to-reality/"><u>2024 Approved  Microsoft’s HoloLens Journey – From Vision to Reality</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/android-unlock-code-sim-unlock-your-vivo-s17-phone-and-remove-locked-screen-by-drfone-android/"><u>Android Unlock Code Sim Unlock Your Vivo S17 Phone and Remove Locked Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-lockout-overcoming-windows-11-device-error-code-22/"><u>Bypassing Lockout: Overcoming Windows 11 Device Error Code 22</u></a></li>
<li><a href="https://windows11.techidaily.com/essentials-of-implementing-windows-law-filters-effectively/"><u>Essentials of Implementing Windows LAW Filters Effectively</u></a></li>
<li><a href="https://windows11.techidaily.com/from-desktop-to-deep-dive-installing-kali-linux-on-windows/"><u>From Desktop to Deep-Dive: Installing Kali Linux on Windows</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/how-to-come-up-with-the-best-pokemon-team-on-apple-iphone-12-pro-max-drfone-by-drfone-virtual-ios/"><u>How to Come up With the Best Pokemon Team On Apple iPhone 12 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-geforce-experiences-unable-to-retrieve-settings-error-in-windows-11-and-11/"><u>How to Fix GeForce Experience’s “Unable to Retrieve Settings” Error in Windows 11 & 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-fix-oem-unlock-missing-on-asus-rog-phone-8-pro-by-drfone-android/"><u>How To Fix OEM Unlock Missing on Asus ROG Phone 8 Pro?</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-iphone-15-plus-passcode-without-itunes-without-knowing-passcode-drfone-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 15 Plus Passcode without iTunes without Knowing Passcode? | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-oneplus-open-phone-frp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your OnePlus Open Phone FRP Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/larger-than-life-boosting-taskbar-icons-in-w11/"><u>Larger-than-Life: Boosting Taskbar Icons in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-morning-routine-launching-windows-and-sticky-notes/"><u>Mastering Morning Routine: Launching Windows & Sticky Notes</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-settings-for-effortless-administration/"><u>Mastering Windows 11 Settings for Effortless Administration</u></a></li>
<li><a href="https://windows11.techidaily.com/method-to-recalibrate-windows-energy-plan/"><u>Method to Recalibrate Window's Energy Plan</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-to-solutions-faster-configuring-shortcuts-for-win-1011-tools/"><u>Navigate to Solutions Faster: Configuring Shortcuts for Win 10/11 Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/nexus-controller-detection-woes-heres-how-to-win-them-back/"><u>Nexus Controller Detection Woes? Here's How to Win Them Back</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-window-11-email-app-error-code-0x800713f/"><u>Overcoming Window 11 Email App Error Code 0X800713F</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-camera-error-code-0xa00f425d/"><u>Overcoming Windows Camera Error Code: 0XA00F425D</u></a></li>
<li><a href="https://windows11.techidaily.com/procedures-for-fixing-inoperative-ccleaner-on-windows-os/"><u>Procedures for Fixing Inoperative CCleaner on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-launch-hacks-opening-windows-11-apps-faster/"><u>Quick Launch Hacks: Opening Windows 11 Apps Faster</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-edges-continuous-desktop-appearance/"><u>Resolving Edges' Continuous Desktop Appearance</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-win-1011-zoom-fatal-error-1132/"><u>Resolving Win 10/11 Zoom Fatal Error 1132</u></a></li>
<li><a href="https://windows11.techidaily.com/responding-to-click-failures-in-windows-11-environment/"><u>Responding to Click Failures in Windows 11 Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/simple-steps-for-screen-position-changes/"><u>Simple Steps for Screen Position Changes</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-unblock-windows-nvidia-setup-window/"><u>Strategies to Unblock Windows Nvidia Setup Window</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-your-experience-using-w11s-auto-hdr/"><u>Tailoring Your Experience: Using W11's Auto HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/top-secure-password-vaults-elevating-windows-11-standards/"><u>Top Secure Password Vaults Elevating Windows 11 Standards</u></a></li>
<li><a href="https://windows11.techidaily.com/tricks-to-launch-websites-after-installation/"><u>Tricks to Launch Websites After Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-and-fix-windows-autoshrink-issue/"><u>Troubleshoot & Fix Windows' Autoshrink Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-financial-gains-with-w11-pro-key-deals/"><u>Unlock Financial Gains with W11 Pro Key Deals</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-error-code-0x80071a90-in-windows/"><u>Unraveling Error Code 0X80071A90 in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/why-microsoft-family-safety-matters-for-parents/"><u>Why Microsoft Family Safety Matters for Parents</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-machine-wattage-determining-computational-power-use/"><u>Windows Machine Wattage: Determining Computational Power Use</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-at-learning-7-efficient-techniques-for-windows/"><u>Winning at Learning: 7 Efficient Techniques for Windows</u></a></li>
</ul></div>
