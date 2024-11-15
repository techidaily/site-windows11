---
title: Tips for Restricting Removable Storage via Windows Settings
date: 2024-11-12T17:06:41.297Z
updated: 2024-11-15T16:48:50.156Z
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
<a href="https://bluetties.sjv.io/c/5597632/2141688/17094" target="_top" id="2141688">
  <img src="//a.impactradius-go.com/display-ad/17094-2141688" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluetties.sjv.io/i/5597632/2141688/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The Local Group Policy Editor (LGPE) is a reliable tool for troubleshooting system errors. Interestingly, you can also use it for other tasks such as [preventing others from changing your Windows desktop background](https://www.makeuseof.com/stop-others-change-windows-desktop-background/).

 Now, here’s how to use the LGPE to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **Computer Configuration > Administrative Templates > System > Device Installation > Device Installation Restrictions**.
4. Double-click on the **Prevent installation of removable devices** option on the right-hand side.

![Clicking the prevent installation of removable devices option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-prevent-installation-of-removable-devices-option.jpg)

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098705/14409" target="_top" id="2098705">
  <img src="//a.impactradius-go.com/display-ad/14409-2098705" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098705/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Select **Enabled** on the next screen to prevent others from installing removable storage devices into your PC. Alternatively, select **Disabled** or **Not Configured** to restore the default settings.

 Finally, press **Apply** and then press **OK** to save these changes.

 Struggling to access the LGPE on Windows Home? There are a few tricks you can apply to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). But if that sounds complicated to you, then skip to the Registry Editor method.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151868/7443" target="_top" id="2151868">
  <img src="//a.impactradius-go.com/display-ad/7443-2151868" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151868/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Using the Registry Editor

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997648/19272" target="_top" id="1997648">
  <img src="//a.impactradius-go.com/display-ad/19272-1997648" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997648/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-blog.techidaily.com/n-2024-supercharge-your-channels-a-guide-to-the-best-keyword-research-software/"><u>[New] In 2024, Supercharge Your Channels A Guide to the Best Keyword Research Software</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-dissecting-a-day-in-the-life-hero5-edition/"><u>[Updated] Dissecting a Day in the Life Hero5 Edition</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-capture-every-moment-the-power-of-spring-screenrecorder/"><u>2024 Approved Capture Every Moment - The Power of Spring ScreenRecorder</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-techniques-to-transfer-data-from-xiaomi-redmi-a2-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Techniques to Transfer Data from Xiaomi Redmi A2 to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/best-websites-for-digital-gold-and-silver-text-effects-for-2024/"><u>Best Websites for Digital Gold and Silver Text Effects for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-change-your-sim-pin-code-on-your-vivo-x-flip-phone-by-drfone-android/"><u>How To Change Your SIM PIN Code on Your Vivo X Flip Phone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-on-itel-a70-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location on Itel A70 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-revert-the-search-bar-lookup-of-windows-11/"><u>How to Revert the Search Bar Lookup of Windows 11</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-virtualdub-review-still-a-relevant-video-editor-explore-the-best-alternatives/"><u>New Virtualdub Review Still a Relevant Video Editor ? Explore the Best Alternatives</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-bandwidth-issues-for-steam-broadcasting/"><u>Overcoming Bandwidth Issues for Steam Broadcasting</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-learning-mode-in-win-11/"><u>Personalize Learning Mode in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-charmap-issues-a-practical-guide/"><u>Unlocking Windows CharMap Issues: A Practical Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/which-browser-saves-system-resources-winmaccros-edition/"><u>Which Browser Saves System Resources? Win/Mac/CrOS Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/win-against-interfaces-not-supported-by-windows/"><u>Win Against Interfaces Not Supported by Windows</u></a></li>
</ul></div>

