---
title: Tackling Network Link Lost on Windows
date: 2024-08-31T22:06:11.232Z
updated: 2024-09-01T22:06:11.232Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling Network Link Lost on Windows
excerpt: This Article Describes Tackling Network Link Lost on Windows
keywords: WinLinkLossResolution,WindowsNetworkIssue,FixWindowsConnectivity,ResolveNetLinkLost,RestoreWindowsLinks,StopWinLinkDropout,AddressWndConnectError
thumbnail: https://thmb.techidaily.com/934c09a684ad314c00e00ed21a2e7539ae4858551b2266da80c837988bee503d.jpg
---

## Tackling Network Link Lost on Windows

 People utilize VPNs (Virtual Private Networks) for more secure and anonymous web browsing. However, some users can’t utilize VPN connections on their Windows PCs because of an error message that says, “connection to the remote computer could not be established.” Some users see that error message within Settings when they try to connect to VPNs.

 This error will prevent you from connecting to a VPN on your Windows 11/10 PCs. Is that same error affecting your PC’s VPN connectivity? If so, this is how you can probably fix that VPN connection issue on a Windows PC.

## 1\. Run the Network Adapter Troubleshooting Tool

 Windows troubleshooters can often be useful for fixing network-related issues. The Network Adapter troubleshooter will likely be the most useful troubleshooting tool for resolving this VPN error. However, the Internet Connection troubleshooter could also address issues causing the VPN connection error.

 You can access both troubleshooters within Settings. This [how to run any Windows troubleshooter](https://www.makeuseof.com/run-troubleshooter-windows-10-11/#:~:text=Press%20Win%20%2B%20I%20to%20open,Click%20on%20Other%20troubleshooters.) article provides step-by-step instructions for opening troubleshooters in the Windows 10 or 11 Settings app. Then go through the Network Adapter or Internet Connection troubleshooter to apply any manual resolutions they recommend.

![The Network Adapter troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/network-adapter-troubleshooter.jpg)

## 2\. Turn Off the Proxy Server Setting

 An intermediary proxy server can act as a firewall for enhanced network security. However, having proxy servers enabled can cause issues for VPN connections. So, it’s recommended to [disable the "use a proxy server" setting](https://www.makeuseof.com/windows-11-disable-proxy/) to eliminate that potential cause for this VPN error.

![The Turn off Windows Defender Firewall options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-defender-firewall-settings.jpg)

## 3\. Reconfigure Your VPN Connection’s Security Settings

 This VPN error message suggests that you try reconfiguring some network settings to resolve the issue. Changing VPN connection security settings could feasibly resolve this issue for some users. Try changing your VPN’s connection’s security settings like this:

1. Launch Run (simultaneously press the **Win + R** keys) and input "ncpa.cpl" in that accessory’s **Open** box.
2. Click **OK** in Run to bring up a Network Connections window.
3. Then right-click on your VPN connection and select **Properties**.
4. Click **Security** in the VPN properties window.
5. Select the **Point to Point Tunnelling Protocol** option on the **Type of VPN** drop-down menu.  
![The Type of VPN drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/vpn-settings.jpg)
6. Click the **Allow these protocols** radio button.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
7. Select the **Challenge Handbrake Authentication Protocol (CHAP)** checkbox.
8. Next, click the **Microsoft CHAP Version 2** checkbox to select that option.
9. Click **OK** to set the new VPN security settings.

 Misconfigured settings in your VPN client software can also feasibly cause connection issues. To remedy that, try resetting your VPN client software settings to default. Look for and select an option within your VPN software that generally restores default settings.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Disable the Windows Firewall

 Windows Defender Firewall might be causing this error by blocking the VPN connection. To ensure WDF isn’t blocking your VPN connection, try temporarily [disabling Windows Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/). Then return to Settings to see if the “Connection to the remote computer could not be established” error persists.

 If this works, don’t leave the firewall off. Instead, add your VPN connection to Windows Defender Firewall’s allowed list. To do that, you’ll need to select the **Private** and **Public** checkboxes for your VPN connection, as covered within this guide to [allowing apps through Windows Firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/).

![The Turn off Windows Defender Firewall options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-defender-firewall-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
## 5\. Disable Third-Party Security Software Packages

 Many third-party security (antivirus) software packages also have integrated firewalls that can block VPN connections. If there’s third-party security software installed on your PC, turn off its firewall component to see if that makes any difference to your VPN connection. Then set up a firewall exception for your VPN connection within your security software if that does resolve the issue.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
## 6\. Reinstall the WAN Miniport Devices

 Reinstalling WAN Miniport devices is a potential resolution many users confirm fixes the “Connection to the remote computer could not be established.” Applying this potential solution will reinstall the drivers for virtual network adapters that have variable protocols, which often resolves this VPN error. You can reinstall WAN Miniport devices like this:

1. First, right-click on the Windows taskbar icon (**Start** button) and select **Device Manager**.
2. Click the little arrow beside **Network adapters** to view all devices for that category.
3. Right-click on the WAN Miniport (IKEv2) adapter and select **Uninstall device**.  
![The Uninstall device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/uninstall-device-option.jpg)
4. Press **Uninstall** within the confirmation dialog box.  
![The Uninstall button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/uninstall-button.jpg)
5. Repeat the previous two steps for all WAN Miniport adapters shown within Device Manager.
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
6. When you’ve uninstalled all the WAN Miniport devices, click the **Action** menu.  
![The Scan for hardware changes option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/scan-for-hardware-changes-option.jpg)
7. Select the **Scan for hardware changes** option to reinstall the WAN Miniport devices.

 Then return to Settings and try connecting with your VPN again.

## 7\. Reset Your PC’s Network Settings

 A network reset will reinstall all your PC’s network adapters. So, this potential resolution could have a similar effect to the preceding one, and some users have confirmed it to work. However, a network reset also restores network components to default settings.

 You can reset network adapter settings by inputting and executing a series of netsh and ipconfig commands. However, it’s more straightforward to apply this fix by clicking the **Reset now** button in Settings. Check out our [how to reset your network settings](https://www.makeuseof.com/reset-network-settings-windows-11/) guide for further details about how you can access that option.

![The Reset now button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/reset-now-button.jpg)

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
<!-- affiliate ads end -->
## 8\. Reinstall Your VPN Software

 Reinstallation of your VPN software might be necessary if none of the other potential solutions here work for you. Applying such a solution will likely address software issues causing this VPN connection error. You’ll also update your VPN software by installing its latest version.

 You can remove your VPN client software within Programs or Features or Settings as outlined in this guide to [uninstalling Windows software](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/). Make sure you also remove any additional extras installed with your VPN client, such as network TAP adapters. Resetting your PC’s network settings will also probably uninstall VPN software.

![The Programs and Features Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/programs-and-features2.jpg)

 Then open the official publisher download page for your VPN software. Select to download the latest VPN client software version for Windows 11/10 from there. Run the downloaded VPN software installer to reinstall.

## Re-establish Your VPN Connection on Windows

 Those potential fixes for the “Connection to the remote computer could not be established” error will probably re-establish your VPN connection. In many cases, reinstalling WAN Miniport adapters or disabling proxy servers will often do the trick. However, you might need to try alternative resolutions here to get this VPN connection issue resolved.

 This error will prevent you from connecting to a VPN on your Windows 11/10 PCs. Is that same error affecting your PC’s VPN connectivity? If so, this is how you can probably fix that VPN connection issue on a Windows PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>