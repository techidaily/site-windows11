---
title: Tips for Restricting Removable Storage via Windows Settings
date: 2024-12-02T05:56:11.747Z
updated: 2024-12-04T03:24:16.508Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nmj7aVvEeAs?si=OcR7USXKGyLcn09q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Prevent Others From Installing Any Removable Storage Devices

 Let's start by checking out how you can prevent others from installing any removable storage device into your PC. You can do this using either the Local Group Policy Editor or the Registry Editor.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xtylXDY9YfA?si=VonzSiDFGCpJm2uC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Using the Local Group Policy Editor

![Using a Windows laptop on a brown desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Using-a-Windows-laptop-on-a-brown-desk.jpg)

 The Local Group Policy Editor (LGPE) is a reliable tool for troubleshooting system errors. Interestingly, you can also use it for other tasks such as [preventing others from changing your Windows desktop background](https://www.makeuseof.com/stop-others-change-windows-desktop-background/).

 Now, here’s how to use the LGPE to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **Computer Configuration > Administrative Templates > System > Device Installation > Device Installation Restrictions**.
4. Double-click on the **Prevent installation of removable devices** option on the right-hand side.

![Clicking the prevent installation of removable devices option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-prevent-installation-of-removable-devices-option.jpg)

 Select **Enabled** on the next screen to prevent others from installing removable storage devices into your PC. Alternatively, select **Disabled** or **Not Configured** to restore the default settings.

 Finally, press **Apply** and then press **OK** to save these changes.

 Struggling to access the LGPE on Windows Home? There are a few tricks you can apply to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). But if that sounds complicated to you, then skip to the Registry Editor method.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jjGL9wFdlbo?si=Vb1JgZqRXNc03UGG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Using the Registry Editor

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RBN1gYY5hUs?si=p89CMiMzeJzU0wGu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

 Now, follow these steps:

1. Double-click on the **DenyRemovableDevices** value.
2. Set the **Value data** as **1** and then press **OK** to prevent others from installing storage devices into your PC. Alternatively, set the **Value data** as **0** and press **OK** to allow others to install removable storage devices on your PC.
3. Close the Registry Editor and restart your device to save these changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U6lCtLUeROA?si=se6OFuis9JpcTGJf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-footage.techidaily.com/updated-essential-list-5-leading-youtube-shortened-url-services-for-2024/"><u>[Updated] Essential List 5 Leading YouTube Shortened URL Services for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-best-places-to-find-3d-silver-and-gold-lettering-effects/"><u>2024 Approved Best Places to Find 3D Silver and Gold Lettering Effects</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-premier-playwriting-for-podcasts-and-radios/"><u>2024 Approved Premier Playwriting for Podcasts & Radios</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-always-show-task-manager-on-top-of-other-open-windows/"><u>How to Always Show Task Manager on Top of Other Open Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-open-the-calculator-in-windows-11/"><u>How to Open the Calculator in Windows 11</u></a></li>
<li><a href="https://win-blog.techidaily.com/improve-dota-2-gaming-experience-overcome-frame-rate-drops-on-windows-1110/"><u>Improve Dota 2 Gaming Experience: Overcome Frame Rate Drops on Windows 11/10</u></a></li>
<li><a href="https://fox-direct.techidaily.com/kickstarting-a-vlog-key-hardware-and-apps-for-2024/"><u>Kickstarting a Vlog Key Hardware & Apps for 2024</u></a></li>
<li><a href="https://win-solutions.techidaily.com/master-your-coding-skills-with-windows-11-notebook-the-new-ai-powered-guide-to-decoding-programming-constructs/"><u>Master Your Coding Skills with Windows 11 Notebook - The New AI-Powered Guide to Decoding Programming Constructs</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-win11-settings-for-defaults/"><u>Navigating Win11 Settings for Defaults</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-freeze-frames-in-windows-league-of-legends/"><u>Overcoming Freeze Frames in Windows League of Legends</u></a></li>
<li><a href="https://windows11.techidaily.com/overhauling-fatal-exception-error-0x8007045d-on-pc/"><u>Overhauling Fatal Exception Error 0X8007045D on PC</u></a></li>
<li><a href="https://common-error.techidaily.com/solve-unresponsive-laptop-mouse-problems-with-simple-usb-fixes/"><u>Solve Unresponsive Laptop Mouse Problems with Simple USB Fixes</u></a></li>
<li><a href="https://tech-hub.techidaily.com/step-by-step-tutorial-for-ios-devotees-how-to-refresh-the-firmware-on-an-apple-studio-display/"><u>Step-by-Step Tutorial for iOS Devotees: How to Refresh the Firmware on an Apple Studio Display</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-data-management-in-windows-with-custom-commands/"><u>Streamlining Data Management in Windows with Custom Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-clearing-darkened-windows-remote-pc/"><u>Techniques for Clearing Darkened Windows Remote PC</u></a></li>
<li><a href="https://windows11.techidaily.com/the-secret-of-eradicating-linguistic-line-from-win11-taskbar/"><u>The Secret of Eradicating Linguistic Line From Win11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/two-email-systems-together-merging-gmail-and-outlook-in-windows/"><u>Two Email Systems Together: Merging Gmail and Outlook in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-widget-personalization-in-microsofts-latest-os/"><u>Unveiling Widget Personalization in Microsoft's Latest OS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-wont-turn-off-here-are-the-fixes-to-your-computer-issue-resolved/"><u>Windows 10 Won’t Turn Off? Here Are the Fixes to Your Computer Issue - RESOLVED</u></a></li>
</ul></div>

