---
title: "Windows 11: Stop Intelligent Assistant"
date: 2024-11-24T02:03:21.110Z
updated: 2024-11-25T01:15:32.513Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11: Stop Intelligent Assistant"
excerpt: "This Article Describes Windows 11: Stop Intelligent Assistant"
keywords: Win 11 Smart Assist Cut Off,Windows 11 End IntelliSense,Disable Windows 11 Cortana,Stop W11 AI Features,Turn Off Microsoft's AI in Win11,Cease Windows 11 Voice Assistant,Block Intelligent Assist in Win11
thumbnail: https://thmb.techidaily.com/3c096ca7006d9a28f3f7e555f29e64435eb73c0052911cf681dfac2286fbe4f4.jpg
---

## Windows 11: Stop Intelligent Assistant

 Windows Copilot, Microsoft's new AI assistant, can assist you with a variety of tasks, such as answering questions, changing system settings, and creating AI images. However, if you're not a fan of Copilot or simply don't need it, you can remove its taskbar icon or disable it entirely on your Windows 11 PC. Here, we'll show you how.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Remove the Copilot Icon From the Windows 11 Taskbar

 By default, the Copilot icon appears in the Windows 11 taskbar. However, if you prefer not to have it there but still want to use it occasionally, it's easy to hide the Copilot icon. Simply right-click anywhere on an empty spot on your taskbar and select **Taskbar settings**. In the Settings window that appears, turn off the toggle next to **Copilot**.

![Remove Copilot Icon From Windows 11 Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/remove-copilot-icon-from-windows-11-taskbar.jpg)

 This should remove the Copilot icon from the taskbar. You can still access Copilot by pressing the **Win + C** keyboard shortcut in Windows 11\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hHPljBHrvkA?si=HwdfDM9rlbABSIrx&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Completely Disable Copilot via Group Policy Settings

 Although hiding the Copilot is quite easy, it does not turn it off completely, and you might inadvertently access it. Fortunately, you can turn off Copilot completely via the Local Group Policy Editor on PCs running the Professional, Education, or Enterprise edition of Windows 11\.

 If you are using Windows 11 Home, skip to the Registry Editor method below or use a [workaround to enable the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Press **Win + S** to access the search menu.
2. Type **gpedit.msc** in the search box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **User Configuration > Administrative Templates > Windows Components > Windows Copilot**.
5. Double-click the **Turn off Windows Copilot** policy on your right.
6. Select the **Enabled** option.
7. Hit **Apply** followed by **OK**.  
![Turn Off Windows Copilot Using the Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-windows-copilot-using-the-group-policy-editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the above steps, Copilot will be disabled on your Windows 11 PC and you won't be able to access it even with the keyboard shortcut. If you want to re-enable Copilot later, repeat the above steps and set the **Turn off Windows Copilot** policy to **Not configured** or **Disabled**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LeKJBWb6Jhk?si=AnViizAPiIT1YCRA&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Completely Disable Copilot by Modifying Registry Files

 Another way to disable Copilot on Windows 11 involves modifying registry files. However, since editing the registry can be risky, you should follow the steps carefully. Also, be sure to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/). This will allow you to restore the registry files in case something goes wrong.

 Once you’ve done that, here’s what you need to do to disable Copilot via the Registry Editor:

1. Press **Win + R** to open the Run dialog.
2. Type **regedit** in the text box and press **Enter** to open the Registry Editor.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > Software > Policies > Microsoft > Windows**.
5. Right-click the **Windows** key and select **New > Key**. Name it **WindowsCopilot**.
6. Right-click on the **WindowsCopilot** DWORD, go to **New**, and select **DWORD (32-bit) Value** from the submenu. Name the DWORD **TurnOffWindowsCopilot**.
7. Double-click the **TurnOffWindowsCopilot** DWORD, type **1** in the text field, and click **OK**.
8. Restart your PC for the changes to take effect.  
![Turn Off Windows Copilot Using the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-windows-copilot-using-the-registry-editor.jpg)

 And that’s about it. Windows Copilot will be disabled on your PC. To re-enable it in the future, repeat the above steps and set the **TurnOffWindowsCopilot** DWORD value to 0\. You can also delete the **TurnOffWindowsCopilot** DWORD instead.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GBWcw6rXIdg?si=Tlue44bW-bPA4tH9&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get Rid of Copilot on Windows 11

 While Windows Copilot is a powerful tool, not everyone may want to use it. Fortunately, it’s possible to get rid of it. The above steps will help you achieve your goal, whether you want to keep Copilot out of sight or turn it off entirely.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-essential-techniques-for-efficient-utilization-of-zooms-whiteboard-feature/"><u>[New] 2024 Approved Essential Techniques for Efficient Utilization of Zoom's Whiteboard Feature</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-fb-video-capture-toolkit-for-2024/"><u>[New] FB Video Capture Toolkit for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-unveiling-the-essence-of-top-tier-screen-recorders-with-obs/"><u>[Updated] 2024 Approved Unveiling the Essence of Top-Tier Screen Recorders with OBS</u></a></li>
<li><a href="https://blog-min.techidaily.com/8-ways-to-transfer-photos-from-nokia-xr21-to-iphone-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>8 Ways to Transfer Photos from Nokia XR21 to iPhone Easily | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/complete-guide-to-protect-and-transfer-iphone-13-files-without-dependence-on-apples-itunes-for-windowsmac-users/"><u>Complete Guide to Protect and Transfer iPhone 13 Files Without Dependence on Apple's iTunes for Windows/Mac Users</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-insights-access-and-customize-your-fax-cover-in-win11/"><u>Essential Insights: Access & Customize Your Fax Cover in Win11</u></a></li>
<li><a href="https://solve-latest.techidaily.com/free-steps-to-move-your-ibook-collection-from-ios-to-android/"><u>Free Steps to Move Your iBook Collection From iOS to Android</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-to-fix-windows-alt-key-issues-49-characters/"><u>Guidelines to Fix Windows Alt Key Issues (49 Characters)</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-spoofing-life360-how-to-do-it-on-apple-iphone-xs-max-drfone-by-drfone-virtual-ios/"><u>In 2024, Spoofing Life360 How to Do it on Apple iPhone XS Max? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/inside-tools-for-windows-11-management/"><u>Inside Tools for Windows 11 Management</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-remedy-for-windows-10-print-failure-xffffff/"><u>Mastering the Remedy for Windows 10 Print Failure XFFFFFF</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-active-directory-printer-issues-on-microsofts-latest-os/"><u>Overcoming Active Directory Printer Issues on Microsoft's Latest OS</u></a></li>
<li><a href="https://windows11.techidaily.com/pinpointing-voice-input-anomalies-on-pcs/"><u>Pinpointing Voice Input Anomalies on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-rectify-windows-geforce-error-x0001/"><u>Solutions to Rectify Windows' GeForce Error X0001</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-circumvent-file-cap-on-windows/"><u>Strategies to Circumvent File Cap on Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-and-improve-your-pcs-gpu-usage-tackling-windows-1n-desktop-manager-issues/"><u>Troubleshoot and Improve Your PC's GPU Usage – Tackling Windows 1N Desktop Manager Issues</u></a></li>
<li><a href="https://vp-tips.techidaily.com/ultimate-choice-top-android-3d-players/"><u>Ultimate Choice Top Android 3D Players</u></a></li>
<li><a href="https://buynow-help.techidaily.com/unveiling-the-grim-realm-an-in-depth-analysis-of-bloodbornes-haunting-adventure/"><u>Unveiling the Grim Realm: An In-Depth Analysis of Bloodborne's Haunting Adventure</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-device-health-essential-steps-to-confirm-availability/"><u>Windows 11 Device Health: Essential Steps to Confirm Availability</u></a></li>
</ul></div>

