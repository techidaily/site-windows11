---
title: Directive for Disabling OneDrive Symbol in Windows 11’S Filesystem Viewer
date: 2024-08-15T15:12:00.864Z
updated: 2024-08-16T15:12:00.864Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Directive for Disabling OneDrive Symbol in Windows 11’S Filesystem Viewer
excerpt: This Article Describes Directive for Disabling OneDrive Symbol in Windows 11’S Filesystem Viewer
keywords: OneDrive Disable Directive,Windows 11 FileViewer Change,Disable OneDrive Icon,Remove OneDrive Symbol,Windows Filesystem Update,OneDrive Exclusion Method,Diverting OneDrive in Win11
thumbnail: https://thmb.techidaily.com/35eb7ec70c3d68bdd6223aba9efbf03bc030e84e65b3cf939f3e4c2fcf3f5d40.jpg
---

## Directive for Disabling OneDrive Symbol in Windows 11’S Filesystem Viewer

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

## How to Remove OneDrive Shortcut From File Explorer via the Registry Editor

 You can remove the OneDrive icon from File Explorer using a registry hack. This way, you can get rid of the icon in File Explorer without uninstalling the OneDrive client. If you would rather remove the app entirely, follow our guide on [removing OneDrive on Windows 11](https://www.makeuseof.com/windows-11-disable-remove-onedrive/) .

 Note that modifying the Windows registry involves risk. We recommend you [create a system restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed with the steps below. A restore point will help you restore your computer in case something goes wrong.

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
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Show the OneDrive Icon Again in File Explorer

![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-best-practices-expert-picks-for-4k-dslr-mounts/"><u>[New] 2024 Approved  Best Practices  Expert Picks for 4K DSLR Mounts</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-essential-instagram-repost-strategies-for-2024/"><u>[New] Essential Instagram Repost Strategies for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-vcs-vision-recorder-check-detailed-scrutiny/"><u>[New] In 2024, VCS Vision Recorder Check  Detailed Scrutiny</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-2024-approved-exploring-the-gridiron-a-detailed-review-of-vegas-pro-2021/"><u>[Updated] 2024 Approved  Exploring the Gridiron  A Detailed Review of Vegas Pro 2021</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-become-a-pro-at-snap-ad-development-hacks-and-strategies/"><u>[Updated] Become a Pro at Snap Ad Development - Hacks and Strategies</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-advanced-techniques-for-effective-mobile-screen-capturing-with-mobizen/"><u>2024 Approved  Advanced Techniques for Effective Mobile Screen Capturing with Mobizen</u></a></li>
<li><a href="https://android-frp.techidaily.com/about-samsung-galaxy-s23-tactical-edition-frp-bypass-by-drfone-android/"><u>About Samsung Galaxy S23 Tactical Edition FRP Bypass</u></a></li>
<li><a href="https://windows11.techidaily.com/evaluating-the-significance-of-audio-device-isolation-in-windows/"><u>Evaluating the Significance of Audio Device Isolation in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/examining-why-drive-letters-are-missing-from-windows-systems/"><u>Examining Why Drive Letters Are Missing From Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-11-ignore-or-prevent-expiry-errors/"><u>Fixing Windows 11: Ignore or Prevent 'Expiry' Errors?</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-cease-built-in-desktop-keyboard-in-windows-os/"><u>Guide to Cease Built-In Desktop Keyboard in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-clearing-winsec-error-limited-administrator/"><u>Guide to Clearing WinSec Error - 'Limited Administrator'</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-install-and-activate-defender-application-guard-on-edge-for-enhanced-safety/"><u>How to Install and Activate Defender Application Guard on Edge for Enhanced Safety</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-unlink-your-onedrive-from-your-microsoft-account-on-windows/"><u>How to Unlink Your OneDrive From Your Microsoft Account on Windows</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-benq-bl2711u-a-journey-through-professional-4k-display-tech/"><u>In 2024, BenQ BL2711U - A Journey Through Professional 4K Display Tech</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-captivating-video-content-tips-for-pinterest-boards/"><u>In 2024, Captivating Video Content Tips for Pinterest Boards</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-driving-engagement-and-sales-a-step-by-step-guide-to-influencer-marketing/"><u>In 2024, Driving Engagement and Sales  A Step-by-Step Guide to Influencer Marketing</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-realme-gt-5-drfone-by-drfone-virtual-android/"><u>In 2024, The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Realme GT 5 | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-zoomed-success-on-set-harnessing-kinemasters-viewer-focus/"><u>In 2024, Zoomed Success on Set  Harnessing Kinemaster’s Viewer Focus</u></a></li>
<li><a href="https://windows11.techidaily.com/interactive-insights-microsofts-innovative-ai-hub/"><u>Interactive Insights: Microsoft's Innovative AI Hub</u></a></li>
<li><a href="https://extra-skills.techidaily.com/iphone-camera-savvy-image-optimization-secrets-for-2024/"><u>IPhone Camera Savvy  Image Optimization Secrets for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/masterful-mix-select-5-free-pc-audio-programs/"><u>Masterful Mix: Select 5 FREE PC Audio Programs</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-fixing-nvidia-cp-errors-in-ws1110/"><u>Mastering the Art of Fixing Nvidia CP Errors in WS11/10</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-winerror-fixes-for-oculus-app-installation/"><u>Mastering WinError Fixes for Oculus App Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-pathway-to-start-elevated-powershell-on-win11-systems/"><u>Secure Pathway to Start Elevated PowerShell on Win11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-defender-application-guard-for-secure-edge-use-in-win-11/"><u>Setting Up Defender Application Guard for Secure Edge Use in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-unsupported-device-for-windows-hello-login/"><u>Solving 'Unsupported Device' For Windows Hello Login</u></a></li>
<li><a href="https://windows11.techidaily.com/stay-ahead-of-the-game-with-w11-pro-special-deals/"><u>Stay Ahead of the Game with W11 Pro Special Deals</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-to-correctly-handle-windows-updater-issue-error-0x80070003/"><u>Step-by-Step Guide to Correctly Handle Windows' Updater Issue (Error 0X80070003)</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/streaming-software-showdown-the-ultimate-guide-to-obs-vs-shadowplay/"><u>Streaming Software Showdown  The Ultimate Guide to OBS Vs. ShadowPlay</u></a></li>
<li><a href="https://windows11.techidaily.com/sustained-prominence-of-win-calculator-display/"><u>Sustained Prominence of Win Calculator Display</u></a></li>
<li><a href="https://windows11.techidaily.com/synchronize-access-controls-with-powertoys-locksmith/"><u>Synchronize Access Controls with PowerToys' Locksmith</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-crafting-a-better-windows-11/"><u>The Art of Crafting a Better Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-non-functional-shift-in-windows/"><u>Troubleshoot Non-Functional Shift in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unblock-onedrive-windows-methods-to-reclaim-file-storage/"><u>Unblock OneDrive: Windows Methods to Reclaim File Storage</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-power-of-windows-11-overcome-11-errors/"><u>Unlock the Power of Windows 11 - Overcome 11 Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-power-of-component-services-in-windows-11/"><u>Unlocking the Power of Component Services in Windows 11</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-the-ultimate-guide-to-animating-photos-top-8-tools-and-software/"><u>Updated 2024 Approved The Ultimate Guide to Animating Photos Top 8 Tools and Software</u></a></li>
<li><a href="https://windows11.techidaily.com/wake-lock-woes-keyboard-mouse-in-win11/"><u>Wake Lock Woes: Keyboard, Mouse in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/waking-up-off-screen-windows-mastering-6-strategies-in-win11/"><u>Waking Up Off-Screen Windows: Mastering 6 Strategies in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/why-does-tasker-show-other-processes/"><u>Why Does Tasker Show Other Processes?</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11s-official-app-three-ways-to-erase-it/"><u>Win 11'S Official App: Three Ways to Erase It</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-adjusting-your-personalized-fn-keys/"><u>Windows 11: Adjusting Your Personalized FN Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-paper-management-reboot-steps/"><u>Windows Paper Management Reboot Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-sign-in-how-to-delete-your-email/"><u>Windows Sign In: How to Delete Your Email</u></a></li>
</ul></div>
