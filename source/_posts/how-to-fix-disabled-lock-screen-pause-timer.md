---
title: How to Fix Disabled Lock Screen Pause Timer
date: 2024-11-20T00:37:47.929Z
updated: 2024-11-24T20:44:51.135Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix Disabled Lock Screen Pause Timer
excerpt: This Article Describes How to Fix Disabled Lock Screen Pause Timer
keywords: Disable Lock Screen Timer,Enable Touchscreen Timer,Reset Pause Timer,Lock Screen Pause Fixed,Unpause Timer Settings,Fix Timer on Lock Screen,Reactivate Lock Screen Timer
thumbnail: https://thmb.techidaily.com/5cbaf66469602d9e14b1e36573f2e9339160b8c34b23ecf9268274ee16a01385.jpg
---

## How to Fix Disabled Lock Screen Pause Timer

 Have you ever left your computer unattended for a while, only to return and find that it was still unlocked? Several users have reported problems getting their Windows computers to lock automatically after a certain period of inactivity.

 To help out, we have listed some useful tips that should get the lock screen timeout to work on your Windows 10 or 11 PC.

## 1\. Check Screen Timeout Settings

 Before we get to any advanced troubleshooting tips, it’s a good idea to double-check the screen timeout settings on Windows. Here are the steps for the same.

1. Press **Win + I** to open the Settings app.
2. Navigate to **System > Power & battery**.
3. Click on **Screen and sleep** to expand it.
4. Click the drop-down menus next to **On battery power, turn off my screen after** and **When plugged in, turn off my screen after** to select your preferred timeout.  
![Screen and Sleep Settings in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/screen-and-sleep-settings-in-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1dR4tF3VgyU?si=AJipgqZsNNxsRsBW&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After setting your preferred timeout, observe if Windows locks your PC after the specified period.

## 2\. Configure Screen Saver Settings

 Incorrectly configured screen saver settings on Windows can also be the cause of this issue. Here's how you can configure Windows to display the lock screen after you resume from a screensaver.

1. Press **Win + S** to open the search menu.
2. Type **change screen saver** in the box and select the first result that appears.
3. In the Screen Saver Settings window, set the preferred wait time.
4. Tick the **On resume, display logon screen** checkbox.
5. Hit **Apply** followed by **OK**.  
![Screen Saver Settings on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/screen-saver-settings-on-windows.jpg)

 Once you complete the above steps, Windows should lock your system once the screen saver activates.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-yZKNLxj3po?si=-RbF6nCJEVlHWP-M&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Check Screen Saver Settings in the Local Group Policy

 If the issue remains even after you configure the screen saver settings, you will need to check the policies related to the screen saver and make sure they are configured correctly.

 As you may be aware, the Local Group Policy Editor is only available on Windows Pro, Enterprise, and Education editions. However, if you are using the Home edition, you can use a workaround to [access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To modify group policies related to screen saver, use these steps:

1. Press **Win + R** to open the Run dialog box.
2. Type **gpedit.msc** in the box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **User Configuration > Administrative Templates > Control Panel > Personalization**.
5. Double-click the **Enable Screen Saver** policy on your right.
6. Select the **Enabled** option.
7. Hit **Apply** and then click **OK**.
8. Similarly, enable the **Password protect the screen saver** policy as well.  
![Password Protect Screen Saver Policy in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/password-protect-screen-saver-policy-in-group-policy-editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DxUX4R6Cf7c?si=prHevNQJivSkIfUt&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Restart your PC after applying the above changes and check if the issue is still there.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Other Generic Fixes to Try

 If the above solutions do not work, you can try some generic Windows fixes to get the lock screen timeout working on Windows.

* **Disconnect External Devices:** It is possible that an external device connected to your system is keeping Windows awake. To test this, disconnect all external devices and see if the problem persists.
* **Reset Your Power Plan:** Issues with the power plan settings could also cause such problems. To fix this, you can try [resetting the power plan to default on Windows](https://www.makeuseof.com/reset-power-plans-to-default-in-windows/).
* **Install Windows Updates:** It's possible that the lock screen timeout problem is occurring due to a bug within the Windows build your PC is running. If that's the case, [installing Windows updates](https://www.makeuseof.com/update-windows-manually/) should help.
* **Try a Clean Boot:**[Performing a clean boot on Windows](https://www.makeuseof.com/how-perform-clean-boot-windows-10/) can help you determine whether a third-party program or service is causing issues with the lock screen timeout. Once you find the problematic program, consider removing it from your system to avoid such issues in the future.
* **Perform a System Restore:** If the issue has only started occurring recently, you can [perform a system restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) to undo recent changes and fix the problem.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LT4sdZgUvRQ?si=SvQD5FouEzu4UHpJ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get the Lock Screen Timeout Working Again on Windows

 When the lock screen timeout fails to work as expected, it can potentially put your Windows computer at risk. Hopefully, one or more of the above tips have helped you solve the problem and you are at peace.

 To help out, we have listed some useful tips that should get the lock screen timeout to work on your Windows 10 or 11 PC.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-info.techidaily.com/new-2024-approved-free-game-themes-and-melodies-10-best-websites/"><u>[New] 2024 Approved Free Game Themes & Melodies – 10 Best Websites</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/outube-beats-now-at-your-fingertips-in-imovie-editing/"><u>[New] YouTube Beats, Now at Your Fingertips in iMovie Editing</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-2024-approved-the-art-of-animated-text-in-video-landscapes/"><u>[Updated] 2024 Approved The Art of Animated Text in Video Landscapes</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-perfect-your-presence-with-solo-video-setups-and-techniques/"><u>[Updated] Perfect Your Presence with Solo Video Setups and Techniques</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-top-10-hd-android-videos-ultimate-players-guide/"><u>2024 Approved Top 10 HD Android Videos Ultimate Players Guide</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/english-worlds-apart/"><u>English Worlds Apart</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-error-2e-to-enable-windows-update/"><u>Fixing Error 2E to Enable Windows Update</u></a></li>
<li><a href="https://games-able.techidaily.com/get-back-online-essential-ps4-wi-fi-fixes-unveiled/"><u>Get Back Online: Essential PS4 Wi-Fi Fixes Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-actions-to-mend-windows-office-errors/"><u>Immediate Actions to Mend Windows Office Errors</u></a></li>
<li><a href="https://extra-information.techidaily.com/m1-chip-unmasked-apples-engineering-feat/"><u>M1 Chip Unmasked Apple's Engineering Feat</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/mastering-multi-image-instagram-stories-a-step-by-step-tutorial-for-2024/"><u>Mastering Multi-Image Instagram Stories A Step-by-Step Tutorial for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/minimizing-delays-boosting-speed-of-windows-discord-app/"><u>Minimizing Delays: Boosting Speed of Windows Discord App</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-frequent-rainmeter-quirks-on-your-system/"><u>Navigating Through Frequent Rainmeter Quirks on Your System</u></a></li>
<li><a href="https://windows11.techidaily.com/no-apps-needed-windows-11-note-hacks/"><u>No Apps Needed: Windows 11 Note Hacks</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-overcoming-fullscreen-obstacles-on-windows/"><u>Quick Guide: Overcoming Fullscreen Obstacles on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-directx-install-failures-on-pcs/"><u>Resolving DirectX Install Failures on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-accuracy-fixed-discord-games-status-errors-windows/"><u>Restoring Accuracy: Fixed Discord Games Status Errors (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-invisible-additional-screen/"><u>Tackling Invisible Additional Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-recover-unseen-additional-monitor/"><u>Windows 11: Recover Unseen Additional Monitor</u></a></li>
</ul></div>

