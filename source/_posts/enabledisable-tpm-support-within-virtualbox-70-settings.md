---
title: Enable/Disable TPM Support Within VirtualBox 7.0 Settings
date: 2025-01-02T18:24:15.319Z
updated: 2025-01-03T17:52:07.092Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enable/Disable TPM Support Within VirtualBox 7.0 Settings
excerpt: This Article Describes Enable/Disable TPM Support Within VirtualBox 7.0 Settings
keywords: VirtualBox TPM Control,VirtualBox Security Features,Enable TPM in VMware,Disable TPM VirtualBox,TPM Compatibility in VBox,Manage TPM Within VirtualBox,Adjust VirtualBox TPM Settings
thumbnail: https://thmb.techidaily.com/6d08ef0c51b7d66c7e631fe3667e11cb568cec8b149ae12a4fa97fbfe5c6637e.jpg
---

## Enable/Disable TPM Support Within VirtualBox 7.0 Settings

 VirtualBox released version 7.0 in October 2022\. It is the first hypervisor to support the emulation of TPM chips along with all the other system components. VirtualBox also offers a Secure Boot feature in EFI mode for virtual machines. The main reason behind these two features was Microsoft's list of elaborate system requirements for Windows 11.

 Without emulation of the TPM 2.0 chip, users couldn't install Windows 11 on a virtual machine. But with VirtualBox 7.0 it is possible to enable Secure Boot and TPM for any Windows virtual machine. This post will elaborate on the methods to enable or disable TPM and Secure Boot for any VirtualBox virtual machine.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LdVT_-3gESA?si=_HfjpbUEHSRKTXjt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Does Windows 11 Need TPM and Secure Boot?

 Windows 11 needs both a TPM chip and Secure Boot to offer robust protection against threats and not allow any malware to run when the system boots up. Secure Boot only allows signed drivers to load and the TPM chip helps in BitLocker drive data protection. So, both these features are pretty important from a security standpoint. Check out our guide on[what Secure Boot is and how it works](https://www.makeuseof.com/what-is-secure-boot-how-does-it-work/) for more information.

 While Windows 11 can work without Secure Boot and a TPM 2.0 chip, it won't be able to offer that extra layer of system protection it would do otherwise. Many features like Core-isolation, Data Encryption won't work. If you want to enable or disable these features for Windows 10 or 11 virtual machines, you can do so in VirtualBox 7.0.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JAkb8Bv3AU4?si=2rHwnZYTzTLieKgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/szUqw4TLvWs?si=srv1OeLOe579gLwj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

9. Go to the top area and click on the**Start** button to power on the Windows virtual machine.
10. Now, press the Win key and search Security. Open the**Windows security** app.
11. Navigate to the left-hand side menu and click on the**Device Security** option. Here, all Windows security features will be active.
12. To disable TPM and Secure Boot, reopen the virtual machine settings and set the TPM version to**None** . Uncheck the**Enable EFI (special OSes only)** option check box. Click on**OK** to save the changes.

### An Alternative Method to Check if TPM Is Active in the Windows Virtual Machine

Here's how to check TPM on Windows 11 virtual machine:

1. Press the**Win + R** key to launch the Run command box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**TPM.msc** and press the**Enter** key.  
![check TPM on Windows 11 virtual machine 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-1.jpg)
2. TPM utility will launch. Navigate to the Manufacturer Information section.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iOVkXoUxLf4?si=QfC18T2cb5OkiaXo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![check TPM on Windows 11 virtual machine 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-2.jpg)
3. If the Specification version entry showcases 2.0, it means that TPM chip emulation is successful.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=lhdUUVYMVQjzHXBh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-easy-ipad-and-iphone-screen-recording-for-beginners/"><u>[New] In 2024, Easy iPad & iPhone Screen Recording for Beginners</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-overlapping-security-measures-stick-to-one-windows-antivirus/"><u>Avoid Overlapping Security Measures: Stick to One Windows Antivirus</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-battlenet-speed-a-win-pc-strategy-guide/"><u>Boosting Battle.net Speed: A Win-PC Strategy Guide</u></a></li>
<li><a href="https://extra-hints.techidaily.com/discovering-new-horizons-with-samsungs-updated-image-tools/"><u>Discovering New Horizons with Samsung’s Updated Image Tools</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-remove-forgotten-pin-of-your-xiaomi-redmi-k70-pro-by-drfone-android/"><u>In 2024, How to Remove Forgotten PIN Of Your Xiaomi Redmi K70 Pro</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722958323763-quick-and-simple-guide-installing-windows-7-keyboard-drivers/"><u>Quick & Simple Guide: Installing Windows 7 Keyboard Drivers</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/richest-ringtone-repositories-online-for-2024/"><u>Richest Ringtone Repositories Online for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-telegram-spy-tools-on-xiaomi-mix-fold-3-for-parents-drfone-by-drfone-virtual-android/"><u>Top 10 Telegram Spy Tools On Xiaomi Mix Fold 3 for Parents | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/transitioning-from-ios-to-a-pc-a-complete-guide-to-imessage/"><u>Transitioning From iOS to a PC: A Complete Guide to iMessage</u></a></li>
<li><a href="https://windows11.techidaily.com/unified-app-closure-master-the-multiplex-task-management/"><u>Unified App Closure: Master the Multiplex Task Management</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-steering-classic-games-to-your-pics/"><u>Windows 11: Steering Classic Games to Your Pics</u></a></li>
</ul></div>

