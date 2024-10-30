---
title: Tips for Disabling OneDrive on Windows 11'S Explore
date: 2024-10-25T16:31:23.063Z
updated: 2024-10-30T16:38:49.886Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tips for Disabling OneDrive on Windows 11'S Explore
excerpt: This Article Describes Tips for Disabling OneDrive on Windows 11'S Explore
keywords: Win11 Disable OneDrive,Turn Off OneDrive Windows,Stop OneDrive Windows 11,OneDrive Shutdown Tips,Deactivate OneDrive Windows,OneDrive OFF Windows Guide,Disable OneDrive in Win11
thumbnail: https://thmb.techidaily.com/dd1b377f0a177d81939c2e9879a9449aa15d2816c9d71de8279c052980247986.jpg
---

## Tips for Disabling OneDrive on Windows 11'S Explore

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

## How to Remove OneDrive Shortcut From File Explorer via the Registry Editor

 You can remove the OneDrive icon from File Explorer using a registry hack. This way, you can get rid of the icon in File Explorer without uninstalling the OneDrive client. If you would rather remove the app entirely, follow our guide on[removing OneDrive on Windows 11](https://www.makeuseof.com/windows-11-disable-remove-onedrive/) .

 Note that modifying the Windows registry involves risk. We recommend you[create a system restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed with the steps below. A restore point will help you restore your computer in case something goes wrong.

 Once done, follow these steps to remove the OneDrive shortcut from File Explorer:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open Registry Editor. Click**Yes** if prompted by**User Account Control (UAC).**
3. Next, in the Registry Editor, navigate to the following location. Copy and paste the registry path in the editor for quicker navigation:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
4. In the right pane, right-click on**System.IsPinnedToNameSpaceTree** DWORD value and select**Modify** .  
![remove onedrive icon windows 11 registry editor modify system is pinned to name space free](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-modify-system-is-pinnedtonamespace-free.jpg)
5. In the**Value data** field, type**0** and click**OK** .  
![remove onedrive icon windows 11 registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor.jpg)
6. Next, navigate to the following location in Registry Editor:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace`
7. In the left pane, right-click on**{018D5C66-4533-4307-9B53-224DE2ED1FE6}** and select**Delete** to remove the entry.  
![remove onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
8. Once done, close the Registry Editor.
9. When you open File Explorer, the OneDrive icon will not be visible anymore.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1186802/12108" target="_top" id="1186802">
  <img src="//a.impactradius-go.com/display-ad/12108-1186802" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1186802/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Show the OneDrive Icon Again in File Explorer

![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148642/16836" target="_top" id="2148642">
  <img src="//a.impactradius-go.com/display-ad/16836-2148642" border="0" alt="https://techidaily.com" width="300" height="50"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148642/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016170/19272" target="_top" id="2016170">
  <img src="//a.impactradius-go.com/display-ad/19272-2016170" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016170/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Remove OneDrive Icon Without Uninstalling OneDrive

 This registry hack is a handy way to make the OneDrive icon disappear without deleting the app entirely from your PC. Alternatively, if you don’t use the service, you can completely remove OneDrive on Windows 11 or disable the service using Group Policy Editor.

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
<li><a href="https://windows11.techidaily.com/handling-unsuccessful-execution-calls-in-malwarebytes-software/"><u>Handling Unsuccessful Execution Calls in Malwarebytes Software</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-can-we-unlock-our-infinix-note-30-5g-phone-screen-by-drfone-android/"><u>How Can We Unlock Our Infinix Note 30 5G Phone Screen?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-vivo-x-fold-2-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Vivo X Fold 2 Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://article-tips.techidaily.com/mastering-aquatic-cinematography-with-these-7-essential-strategies-for-2024/"><u>Mastering Aquatic Cinematography with These 7 Essential Strategies for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-reviving-access-with-past-login-details/"><u>Overcoming Reviving Access with Past Login Details</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-value-uncertainty-issues-in-windows-10/"><u>Overcoming Value Uncertainty Issues in Windows 10</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/ranked-guide-to-premium-iosdesktop-video-change-tools-for-2024/"><u>Ranked Guide to Premium iOS/Desktop Video Change Tools for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-hard-drive-errors-on-windows/"><u>Tackling Hard Drive Errors on Windows</u></a></li>
<li><a href="https://fox-that.techidaily.com/the-ultimate-way-to-get-expert-tech-help-for-your-iphone-using-apples-dedicated-app/"><u>The Ultimate Way to Get Expert Tech Help for Your iPhone Using Apple's Dedicated App</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/upcoming-tech-talk-discussing-expected-releases-and-prices-for-googles-pixel-9/"><u>Upcoming Tech Talk: Discussing Expected Releases & Prices for Google's Pixel 9.</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-nubia-red-magic-9-proplus-drfone-by-drfone-virtual-android/"><u>What is the best Pokemon for pokemon pvp ranking On Nubia Red Magic 9 Pro+? | Dr.fone</u></a></li>
</ul></div>

