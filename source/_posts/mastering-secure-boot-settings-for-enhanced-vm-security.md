---
title: Mastering Secure Boot Settings for Enhanced VM Security
date: 2024-10-19T19:41:14.139Z
updated: 2024-10-24T19:32:51.754Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Secure Boot Settings for Enhanced VM Security
excerpt: This Article Describes Mastering Secure Boot Settings for Enhanced VM Security
keywords: SecureBootVMSecurity,BoostVMDefense,EnhanceVMSecure,VMBootProtection,AdvancedSecurityBoot,SecurityImmuneSystem,OptimizeVMSafety
thumbnail: https://thmb.techidaily.com/5cbe5314b93a999758b5a00e2527a722031ccfee99834737192b083e09532191.jpg
---

## Mastering Secure Boot Settings for Enhanced VM Security

 VirtualBox released version 7.0 in October 2022\. It is the first hypervisor to support the emulation of TPM chips along with all the other system components. VirtualBox also offers a Secure Boot feature in EFI mode for virtual machines. The main reason behind these two features was Microsoft's list of elaborate system requirements for Windows 11.

 Without emulation of the TPM 2.0 chip, users couldn't install Windows 11 on a virtual machine. But with VirtualBox 7.0 it is possible to enable Secure Boot and TPM for any Windows virtual machine. This post will elaborate on the methods to enable or disable TPM and Secure Boot for any VirtualBox virtual machine.

## Why Does Windows 11 Need TPM and Secure Boot?

 Windows 11 needs both a TPM chip and Secure Boot to offer robust protection against threats and not allow any malware to run when the system boots up. Secure Boot only allows signed drivers to load and the TPM chip helps in BitLocker drive data protection. So, both these features are pretty important from a security standpoint. Check out our guide on[what Secure Boot is and how it works](https://www.makeuseof.com/what-is-secure-boot-how-does-it-work/) for more information.

 While Windows 11 can work without Secure Boot and a TPM 2.0 chip, it won't be able to offer that extra layer of system protection it would do otherwise. Many features like Core-isolation, Data Encryption won't work. If you want to enable or disable these features for Windows 10 or 11 virtual machines, you can do so in VirtualBox 7.0.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657396/16446" target="_top" id="1657396">
  <img src="//a.impactradius-go.com/display-ad/16446-1657396" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657396/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1983545">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983545.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983545">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983545.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983545%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983545/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### An Alternative Method to Check if TPM Is Active in the Windows Virtual Machine

Here's how to check TPM on Windows 11 virtual machine:

1. Press the**Win + R** key to launch the Run command box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**TPM.msc** and press the**Enter** key.  
![check TPM on Windows 11 virtual machine 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-1.jpg)
2. TPM utility will launch. Navigate to the Manufacturer Information section.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151870/7443" target="_top" id="2151870">
  <img src="//a.impactradius-go.com/display-ad/7443-2151870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151870/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![check TPM on Windows 11 virtual machine 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-2.jpg)
3. If the Specification version entry showcases 2.0, it means that TPM chip emulation is successful.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135408/19272" target="_top" id="2135408">
  <img src="//a.impactradius-go.com/display-ad/19272-2135408" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135408/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-hitting-high-notes-enhance-your-youtube-content-with-music-edits/"><u>[Updated] 2024 Approved Hitting High Notes Enhance Your YouTube Content with Music Edits</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-in-2024-gift-wrapping-gurus-top-10-websites-for-handcrafted-presents/"><u>[Updated] In 2024, Gift Wrapping Gurus Top 10 Websites for Handcrafted Presents</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-strategies-for-bulk-tiktok-video-acquisition/"><u>[Updated] In 2024, Strategies for Bulk TikTok Video Acquisition</u></a></li>
<li><a href="https://win-dash.techidaily.com/anti-adversarial-design/"><u>Anti-Adversarial Design</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-admin-focused-issues-in-windows-security-framework/"><u>Fixing Admin-Focused Issues in Windows Security Framework</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-xc0000142-blue-screen-in-win10win11/"><u>Fixing XC0000142 Blue Screen in WIN10/WIN11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-keep-sticky-notes-always-on-top-on-windows-10-and-11/"><u>How to Keep Sticky Notes Always on Top on Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/key-tools-enabling-seamless-shift-from-mac-os-to-windows-powered-pc/"><u>Key Tools Enabling Seamless Shift From Mac OS to Windows-Powered PC</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/passfab-apple-iphone-13-mini-backup-unlocker-top-4-alternatives-by-drfone-ios/"><u>PassFab Apple iPhone 13 mini Backup Unlocker Top 4 Alternatives</u></a></li>
<li><a href="https://driver-install.techidaily.com/quickly-enable-bluetooth-on-windows-7/"><u>Quickly Enable Bluetooth on Windows 7</u></a></li>
<li><a href="https://techtrends.techidaily.com/samsung-z-fold-4-announced-discover-the-price-point-and-exciting-features-coming-soon/"><u>Samsung Z Fold 4 Announced! Discover the Price Point and Exciting Features Coming Soon</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-turn-back-the-dial-from-dark-ui/"><u>Techniques to Turn Back the Dial From Dark UI</u></a></li>
<li><a href="https://windows11.techidaily.com/the-illusionists-toolkit-drawing-on-win-1011/"><u>The Illusionist's Toolkit: Drawing on Win 10/11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/tips-to-run-intel-graphics-in-low-end-systems/"><u>Tips to Run Intel Graphics in Low-End Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-potential-of-disks-on-win-1011-systems/"><u>Unlocking the Potential of Disks on Win 10/11 Systems</u></a></li>
<li><a href="https://program-issues.techidaily.com/unraveling-the-mystery-how-did-dual-destiny-project-come-to-an-early-conclusion/"><u>Unraveling The Mystery: How Did 'Dual Destiny' Project Come to an Early Conclusion?</u></a></li>
</ul></div>

