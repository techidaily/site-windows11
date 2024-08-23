---
title: "Windows 11: Stop Intelligent Assistant"
date: 2024-08-22T21:37:07.046Z
updated: 2024-08-23T21:37:07.046Z
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

## How to Remove the Copilot Icon From the Windows 11 Taskbar

 By default, the Copilot icon appears in the Windows 11 taskbar. However, if you prefer not to have it there but still want to use it occasionally, it's easy to hide the Copilot icon. Simply right-click anywhere on an empty spot on your taskbar and select **Taskbar settings**. In the Settings window that appears, turn off the toggle next to **Copilot**.

![Remove Copilot Icon From Windows 11 Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/remove-copilot-icon-from-windows-11-taskbar.jpg)

 This should remove the Copilot icon from the taskbar. You can still access Copilot by pressing the **Win + C** keyboard shortcut in Windows 11\.

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

 Once you complete the above steps, Copilot will be disabled on your Windows 11 PC and you won't be able to access it even with the keyboard shortcut. If you want to re-enable Copilot later, repeat the above steps and set the **Turn off Windows Copilot** policy to **Not configured** or **Disabled**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 And that’s about it. Windows Copilot will be disabled on your PC. To re-enable it in the future, repeat the above steps and set the **TurnOffWindowsCopilot** DWORD value to 0\. You can also delete the **TurnOffWindowsCopilot** DWORD instead.

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
## Get Rid of Copilot on Windows 11

 While Windows Copilot is a powerful tool, not everyone may want to use it. Fortunately, it’s possible to get rid of it. The above steps will help you achieve your goal, whether you want to keep Copilot out of sight or turn it off entirely.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-expertly-recorded-hd-content-ultimate-screen-recorder-guide/"><u>[New] 2024 Approved  Expertly Recorded HD Content  Ultimate Screen Recorder Guide</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-from-script-to-screen-youtube-tutorial-and-alternative-pathways/"><u>[Updated] 2024 Approved  From Script to Screen  YouTube Tutorial & Alternative Pathways</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-mastering-the-mechanics-an-introduction-to-gopro-time-lapse/"><u>[Updated] 2024 Approved  Mastering the Mechanics  An Introduction to GoPro Time-Lapse</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-cultivating-a-community-building-followers-on-youtube-without-spending/"><u>[Updated] In 2024, Cultivating a Community  Building Followers on YouTube Without Spending</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-key-factors-in-understanding-youtube-tv-experience/"><u>[Updated] In 2024, Key Factors in Understanding YouTube TV Experience</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-mastering-photo-framing-best-web-and-app-solutions/"><u>2024 Approved  Mastering Photo Framing  Best Web and App Solutions</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/a-comparison-of-best-linux-screenshare-utilities/"><u>A Comparison of Best Linux Screenshare Utilities</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-drawing-software-like-procreate-for-windows/"><u>Essential Drawing Software Like Procreate, For Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-for-steams-persistent-error-code-e84/"><u>Expert Tips for Steam's Persistent Error Code E84</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-xiaomi-redmi-12-drfone-by-drfone-virtual-android/"><u>How PGSharp Save You from Ban While Spoofing Pokemon Go On Xiaomi Redmi 12? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-pgsharp-legal-when-you-are-playing-pokemon-on-honor-x50-gt-drfone-by-drfone-virtual-android/"><u>In 2024, Is pgsharp legal when you are playing pokemon On Honor X50 GT? | Dr.fone</u></a></li>
<li><a href="https://buynow-info.techidaily.com/in-depth-look-at-the-lenovo-ideapad-320-sleek-convenient-laptop-and-signature-lenovo-keyboards-evaluated/"><u>In-Depth Look at the Lenovo Ideapad 320: Sleek, Convenient Laptop and Signature Lenovo Keyboards Evaluated</u></a></li>
<li><a href="https://win-dash.techidaily.com/logitech-webcam-drivers-free-download-for-windows/"><u>Logitech Webcam Drivers Free Download for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-logging-into-windows-11-with-password-instead-of-pin/"><u>Master the Art of Logging Into Windows 11 with Password Instead of PIN</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-your-files-adding-movecopy-to-windows-context-menu/"><u>Mastering Your Files: Adding 'Move'/'Copy' To Windows Context Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-csgo-not-starting-in-windows-11/"><u>Overcoming CS:GO Not Starting in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-low-usb-support-error-in-windows/"><u>Overcoming Low USB Support Error in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/pioneering-windows-interface-next-chapter-after-11/"><u>Pioneering Windows Interface: Next Chapter After 11</u></a></li>
<li><a href="https://windows11.techidaily.com/propel-your-teams-potential-a-complete-guide-to-microsoft-teams-error-resolution-in-win11/"><u>Propel Your Teams' Potential: A Complete Guide to Microsoft Teams Error Resolution in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstate-your-image-tiles-on-windows-11-quick-guide/"><u>Reinstate Your Image Tiles on Windows 11 – Quick Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/safe-sailing-in-the-sea-of-windows-11-upgrades-top-8/"><u>Safe Sailing in the Sea of Windows 11 Upgrades (Top 8)</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-winrar-data-transfers-addressing-checksum-mistakes/"><u>Securing WinRAR Data Transfers: Addressing Checksum Mistakes</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-acquisition-download-tips-from-microsofts-app-marketplace/"><u>Speedy Acquisition: Download Tips From Microsoft's App Marketplace</u></a></li>
<li><a href="https://windows11.techidaily.com/stay-unplugged-avoiding-abrupt-updates-on-windows-11/"><u>Stay Unplugged: Avoiding Abrupt Updates on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategic-use-of-powertoys-locksmith-for-files/"><u>Strategic Use of PowerToys Locksmith for Files</u></a></li>
<li><a href="https://windows11.techidaily.com/take-charge-of-your-workspace-filter-and-theme-mastery-in-the-windows-11-task-manager/"><u>Take Charge of Your Workspace: Filter and Theme Mastery in the Windows 11 Task Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essentials-of-using-microsoft-family-safety/"><u>The Essentials of Using Microsoft Family Safety</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/the-important-checklist-key-points-for-buying-refurbished-ipads/"><u>The Important Checklist: Key Points for Buying Refurbished iPads</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-enhanced-windows-11-taskbar/"><u>Unlocking Enhanced Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/unshackling-power-the-fourfold-path-to-user-deactivation-in-windows-11/"><u>Unshackling Power: The Fourfold Path to User Deactivation in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/usb-ports-not-working-how-to-diagnose-and-fix-the-issue-in-windows/"><u>USB Ports Not Working? How to Diagnose and Fix the Issue in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-vintage-conversion-the-98-experience/"><u>Windows 11 Vintage Conversion: The ’98 Experience</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-n-11-audio-troubles-heres-how-to-restore-your-mic-functionality/"><u>Windows N 11 Audio Troubles? Here's How to Restore Your Mic Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-based-guide-recognizing-your-cpus-generational-status-8-ways/"><u>Windows-Based Guide: Recognizing Your CPU’s Generational Status (8 Ways)</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>