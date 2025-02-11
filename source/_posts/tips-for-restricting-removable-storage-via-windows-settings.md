---
title: Tips for Restricting Removable Storage via Windows Settings
date: 2025-02-04T06:14:14.243Z
updated: 2025-02-10T23:16:34.216Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/dKjioJQaUh8?si=Ls_AeuvGsSyL5ny2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Prevent Others From Installing Any Removable Storage Devices

 Let's start by checking out how you can prevent others from installing any removable storage device into your PC. You can do this using either the Local Group Policy Editor or the Registry Editor.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GBWcw6rXIdg?si=Tlue44bW-bPA4tH9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Using the Local Group Policy Editor

![Using a Windows laptop on a brown desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Using-a-Windows-laptop-on-a-brown-desk.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/DEqoiNArwjQ?si=oaL_lgnI-RxY5Qy_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Using the Registry Editor

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AcAYRX0cwwA?si=DxqWU39vqksZbe1s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://extra-lessons.techidaily.com/new-advanced-strategies-for-removing-background-in-figma/"><u>[New] Advanced Strategies for Removing Background in Figma</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-cross-sonic-blending-a-deep-dive-into-crossfade/"><u>[New] In 2024, Cross-Sonic Blending - A Deep Dive Into Crossfade</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-2024-approved-streamlining-conversions-mp4-files-with-vlc-media-player/"><u>[Updated] 2024 Approved Streamlining Conversions MP4 Files with VLC Media Player</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-link-length-limit-check-out-these-5-youtube-minisizers/"><u>[Updated] In 2024, Link Length Limit? Check Out These 5 YouTube Minisizers</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-smooth-sailing-for-iphone-video-content-creators/"><u>[Updated] Smooth Sailing for iPhone Video Content Creators</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-ultimate-guide-premier-live-streaming-plus-local-channels-2024/"><u>[Updated] Ultimate Guide Premier Live Streaming + Local Channels 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/advancing-mouse-functionality-through-clicklock-mechanism/"><u>Advancing Mouse Functionality Through ClickLock Mechanism</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/complete-timeline-of-macos-revisions-understanding-what-version-you-are-running-now/"><u>Complete Timeline of macOS Revisions – Understanding What Version You Are Running Now</u></a></li>
<li><a href="https://screen-recording.techidaily.com/effortless-and-accurate-how-to-capture-every-hulu-playback/"><u>Effortless and Accurate How To Capture Every Hulu Playback</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-fixes-regaining-full-synapse-functionality/"><u>Essential Fixes: Regaining Full Synapse Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-selecting-a-best-fit-video-codec-in-windows/"><u>Essential Guide to Selecting a Best Fit Video Codec in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-tweaking-your-web-privacy-via-proxies-in-win-11/"><u>Expert Advice: Tweaking Your Web Privacy via Proxies in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-ms-sql-disconnects-malwarebytes-errors-in-1011-windows/"><u>Overcoming MS SQL Disconnects: Malwarebytes Errors in 10/11 Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-unseen-messages-in-windows-discord-software/"><u>Solving Unseen Messages in Windows Discord Software</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-power-indicators-set-up-full-charge-notification-in-win11/"><u>Streamlining Power Indicators: Set Up Full Charge Notification in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/win11s-0x8007045d-an-effective-resolution-blueprint/"><u>Win11's 0X8007045D: An Effective Resolution Blueprint</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/youtube-film-craft-mastering-thumbnail-creation-on-mobiles-for-2024/"><u>YouTube Film Craft Mastering Thumbnail Creation on Mobiles for 2024</u></a></li>
</ul></div>

