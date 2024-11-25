---
title: Tips for Restricting Removable Storage via Windows Settings
date: 2024-11-21T19:45:43.950Z
updated: 2024-11-24T22:25:14.417Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tips for Restricting Removable Storage via Windows Settings
excerpt: This Article Describes Tips for Restricting Removable Storage via Windows Settings
keywords: Storage Limit Windows,Remove Device Control,Windows Security Tip,USB Accessibility Lock,Data Privacy Windows,Restrict Removable Storage,Secure Devices WIndows
thumbnail: https://thmb.techidaily.com/6bec6b49ef7ec1e5a2c1ba4a21123755124d462c63be6599c5bbe4007fea7d1f.jpg
---

## Tips for Restricting Removable Storage via Windows Settings

 Want to prevent others from stealing your PC data through removable storage devices? Or do you want to protect your device from harmful files contained on removable storage devices?

 In this article, we’ll explore how you can prevent others from installing removable storage devices on Windows. That way, your device won't read any removable storage devices without your permission. Lastly, we’ll also show you how to allow others to install specific removable storage devices.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Prevent Others From Installing Any Removable Storage Devices

 Let's start by checking out how you can prevent others from installing any removable storage device into your PC. You can do this using either the Local Group Policy Editor or the Registry Editor.

### Using the Local Group Policy Editor

![Using a Windows laptop on a brown desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Using-a-Windows-laptop-on-a-brown-desk.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RBN1gYY5hUs?si=p89CMiMzeJzU0wGu&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The Local Group Policy Editor (LGPE) is a reliable tool for troubleshooting system errors. Interestingly, you can also use it for other tasks such as [preventing others from changing your Windows desktop background](https://www.makeuseof.com/stop-others-change-windows-desktop-background/).

 Now, here’s how to use the LGPE to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **Computer Configuration > Administrative Templates > System > Device Installation > Device Installation Restrictions**.
4. Double-click on the **Prevent installation of removable devices** option on the right-hand side.

![Clicking the prevent installation of removable devices option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-prevent-installation-of-removable-devices-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/620kcQ7Dw7w?si=a5ussGs5HV7sG3hF&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Select **Enabled** on the next screen to prevent others from installing removable storage devices into your PC. Alternatively, select **Disabled** or **Not Configured** to restore the default settings.

 Finally, press **Apply** and then press **OK** to save these changes.

 Struggling to access the LGPE on Windows Home? There are a few tricks you can apply to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). But if that sounds complicated to you, then skip to the Registry Editor method.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iOVkXoUxLf4?si=QfC18T2cb5OkiaXo&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Using the Registry Editor

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

 The Registry Editor is another reliable tool you can use for tweaking system settings and troubleshooting PC issues.

 However, this tool is quite sensitive. So, it’s often worth [backing up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first before editing its keys.

 Now, here’s how to use the Registry Editor to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **Regedit** and press **Enter** to open the Registry Editor.
3. Copy-paste the following command into the address bar and press **Enter**:

HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows

 From there, follow these steps:

1. Right-click on the **Windows** folder and select **New > Key**. From there, name this key as **DeviceInstall** and press **Enter**.
2. Right-click on the **DeviceInstall** key and select **New > Key**. Next, name the key as **Restrictions** and press **Enter**.
3. Click the **Restrictions** folder, right-click on a blank space on the right, and then select **New > DWORD (32-bit) Value**. From there, name the value as **DenyRemovableDevices** and press **Enter**.

![Clicking the DenyRemovableDevices value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-DenyRemovableDevices-value.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now, follow these steps:

1. Double-click on the **DenyRemovableDevices** value.
2. Set the **Value data** as **1** and then press **OK** to prevent others from installing storage devices into your PC. Alternatively, set the **Value data** as **0** and press **OK** to allow others to install removable storage devices on your PC.
3. Close the Registry Editor and restart your device to save these changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aYH0B2HqcIM?si=3fkoG85L6hAeB4ok&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Prevent Others From Installing Specific Removable Storage Devices

 In some instances, you might want to prevent others from installing specific removable storage devices. So, let’s show you how you can do that using either the LGPE or the Registry Editor.

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
<li><a href="https://instagram-clips.techidaily.com/new-perfecting-your-content-a-comprehensive-guide-to-instagram-video-enhancement/"><u>[New] Perfecting Your Content A Comprehensive Guide to Instagram Video Enhancement</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-inside-polarr-the-powerhouse-photo-toolkit/"><u>[Updated] Inside Polarr The Powerhouse Photo Toolkit</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/(3-icon-tutorial-creating-digital-expressions-of-affection-with-keys/"><u><3 Icon Tutorial: Creating Digital Expressions of Affection with Keys</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-capturing-the-world-from-every-angle-best-practices-9-rules/"><u>2024 Approved Capturing the World From Every Angle Best Practices (9 Rules)</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-barriers-regaining-computer-management-access/"><u>Breaking Down Barriers: Regaining Computer Management Access</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-fixes-for-windows-hellos-recognition-failures/"><u>Essential Fixes for Windows Hello's Recognition Failures</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-tackling-windows-11-logins/"><u>Essential Guide: Tackling Windows 11 Logins</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-blue-screen-in-win11-5-methods-to-prevent-hybrid-errors/"><u>Fixing Blue Screen in Win11: 5 Methods to Prevent Hybrid Errors</u></a></li>
<li><a href="https://driver-download.techidaily.com/improve-wireless-performance-with-updated-network-adapter-drivers-download-now/"><u>Improve Wireless Performance with Updated Network Adapter Drivers - Download Now!</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-on-nokia-g310-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock on Nokia G310 Devices</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-prevent-cross-site-tracking-on-samsung-galaxy-a24-and-browser-drfone-by-drfone-virtual-android/"><u>In 2024, Prevent Cross-Site Tracking on Samsung Galaxy A24 and Browser | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-directx-downloading-and-updating-steps/"><u>Mastering DirectX: Downloading & Updating Steps</u></a></li>
<li><a href="https://program-issues.techidaily.com/overcome-pc-game-glitches-fixed-guide-to-no-more-dauntless-crashes/"><u>Overcome PC Game Glitches: Fixed Guide to No More Dauntless Crashes</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-absence-of-display-on-remote-workspace-win/"><u>Overcoming Absence of Display on Remote Workspace Win</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-re-establish-winning-online-wol-experience/"><u>Steps to Re-Establish Winning Online WoL Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/the-path-to-professional-print-perfection-nine-key-techniques-for-powerpoint-on-pcs/"><u>The Path to Professional Print Perfection: Nine Key Techniques for PowerPoint on PCs</u></a></li>
<li><a href="https://win-dash.techidaily.com/troubleshooting-and-fixing-xbox-gaming-device-driver-errors-on-multiple-windows-versions/"><u>Troubleshooting and Fixing Xbox Gaming Device Driver Errors on Multiple Windows Versions</u></a></li>
</ul></div>

