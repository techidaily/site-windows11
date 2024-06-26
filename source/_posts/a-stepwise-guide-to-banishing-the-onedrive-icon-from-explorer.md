---
title: A Stepwise Guide to Banishing the OneDrive Icon From Explorer
date: 2024-06-25T12:07:16.110Z
updated: 2024-06-26T12:07:16.110Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Stepwise Guide to Banishing the OneDrive Icon From Explorer
excerpt: This Article Describes A Stepwise Guide to Banishing the OneDrive Icon From Explorer
keywords: Banish OneDrive Guide,Eliminate OneDrive Explore,Remove OneDrive Icons,Eradicate OneDrive Visibility,Dismiss OneDrive Icon,Disable OneDrive Explorer,Get Rid of OneDrive
thumbnail: https://thmb.techidaily.com/502b1cdc938497dc65859bd4dea7388cbc83b5388aae8627911832c708fd7626.jpg
---

## A Stepwise Guide to Banishing the OneDrive Icon From Explorer

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

## How to Show the OneDrive Icon Again in File Explorer

![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

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
<li><a href="https://windows11.techidaily.com/optimizing-subsystem-best-practices-for-wsl-2-users/"><u>Optimizing Subsystem: Best Practices for WSL 2 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/6-methods-for-reviving-windows-command-line-interface/"><u>6 Methods for Reviving Windows' Command Line Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-power-of-dism-in-win11-image-management/"><u>Unveiling the Power of Dism in Win11 Image Management</u></a></li>
<li><a href="https://windows11.techidaily.com/realign-your-windows-clock-through-chrome-settings/"><u>Realign Your Windows Clock Through Chrome Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-unblock-application-packages-on-windows-servers/"><u>Techniques to Unblock Application Packages on Windows Servers</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-dxgierrordeviceremoved-in-modern-win-oses/"><u>Combatting DXGI_ERROR_DEVICE_REMOVED in Modern Win OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/microsofts-profit-mechanisms-in-windows-11/"><u>Microsoft's Profit Mechanisms in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-access-disabled-sign-in-on-windows/"><u>Restoring Access: Disabled Sign-In on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-start-up-sequence-of-windows-os/"><u>Decoding the Start-Up Sequence of Windows OS</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-the-verdict-on-actives-place-among-best-recorders/"><u>[New] In 2024, The Verdict on Active's Place Among Best Recorders</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-elite-influencer-economy-leaders/"><u>[New] 2024 Approved  Elite Influencer Economy Leaders</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-perfecting-speech-recognition-on-google-platforms/"><u>[New] 2024 Approved  Perfecting Speech Recognition on Google Platforms</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-life360-on-windows-pc-for-samsung-galaxy-f34-5g-drfone-by-drfone-virtual-android/"><u>How to Use Life360 on Windows PC For Samsung Galaxy F34 5G? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-honor-magic-5-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Honor Magic 5 If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-mastering-garageband-a-comprehensive-tutorial-for-recording-music/"><u>Updated In 2024, Mastering GarageBand A Comprehensive Tutorial for Recording Music</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/capturepros-a-studio-showdown/"><u>CapturePros  A Studio Showdown</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-finding-the-ideal-image-size-a-ratio-calculator-tutorial/"><u>2024 Approved Finding the Ideal Image Size A Ratio Calculator Tutorial</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-ultimate-4k-gaming-setup-top-10-laptop-guide/"><u>[Updated] In 2024, Ultimate 4K Gaming Setup - Top 10 Laptop Guide</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-mastering-soundscapes-with-avs-an-examination-of-product-specifications-reviews-and-diverse-alternatives/"><u>Updated 2024 Approved Mastering Soundscapes with AVS An Examination of Product Specifications, Reviews, and Diverse Alternatives</u></a></li>
</ul></div>
