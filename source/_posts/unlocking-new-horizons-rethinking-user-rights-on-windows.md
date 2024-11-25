---
title: "Unlocking New Horizons: Rethinking User Rights on Windows"
date: 2024-11-20T19:28:45.403Z
updated: 2024-11-24T18:30:28.887Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlocking New Horizons: Rethinking User Rights on Windows"
excerpt: "This Article Describes Unlocking New Horizons: Rethinking User Rights on Windows"
keywords: WinUserRightsUpdate,UserRightsWindowsRevise,RedefineWinUserRights,WindowsUsersNewHorizon,HorizonsUnlockingUserRights,RethinkWindowsUserPolicy,NewHorizonsUserAccessWindows
thumbnail: https://thmb.techidaily.com/69e9ce291a37fc7b18e662948bbf53944b60034e468a1fcf01b032cc2430ea00.jpg
---

## Unlocking New Horizons: Rethinking User Rights on Windows

 If you’ve ever tried running a program on Windows as an administrator, you’ve probably come across a prompt asking you to either give or deny it permission to make high-level changes. That’s User Access Control (UAC) in action, and it adds an extra layer of security when a program or task is seeking elevated privileges. This gives you the chance to stop unwanted or malicious software from making changes on your PC.

 As an administrator, you can change how UAC behaves. In this guide, we’re going to show you how to do that using the Local Group Policy Editor and Registry Editor.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/d-COuhPT5mk?si=wLZU6jkkAdJuAn6h&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Behaviors Does UAC Have for Administrators?

 Before you go about changing the way UAC acts for administrators, it helps to know what behaviors you can choose and what they mean. We’re going to list them below, along with the definitions that are listed on [Microsoft Learn](https://learn.microsoft.com/en-us/windows/security/threat-protection/security-policy-settings/user-account-control-behavior-of-the-elevation-prompt-for-administrators-in-admin-approval-mode).

 Here’s what you can choose:

* **Elevate without prompting**: Assumes that the administrator will permit an operation that requires elevation, and more consent or credentials aren't required. This minimizes the protection that is provided by UAC.
* **Prompt for credentials on the secure desktop**: When an operation requires elevation of privilege, the user is prompted on the secure desktop to enter a privileged username and password. If the user enters valid credentials, the operation continues with the user's highest available privilege.
* **Prompt for consent on the secure desktop**: When an operation requires elevation of privilege, the user is prompted on the secure desktop to select **Permit** or **Deny**. If the user selects **Permit**, the operation continues with the user's highest available privilege.
* **Prompt for credentials**: An operation that requires elevation of privilege prompts the administrator to type the username and password. If the administrator enters valid credentials, the operation continues with the applicable privilege.
* **Prompt for consent**: An operation that requires elevation of privilege prompts the administrator to select **Permit** or **Deny**. If the administrator selects **Permit**, the operation continues with the administrator's highest available privilege.
* **Prompt for consent for non-Windows binaries**: This prompt for consent is the default. When an operation for a non-Microsoft application requires elevation of privilege, the user is prompted on the secure desktop to select **Permit** or **Deny**. If the user selects **Permit**, the operation continues with the user's highest available privilege.

 Now that you're familiar with the UAC behaviors for administrators, let’s see how to change them.

## Changing UAC Behavior for Administrators in the Local Group Policy Editor

 To change the UAC behavior for admins using the Local Group Policy Editor (LGPE), start by pressing **Win + R**, typing **gpedit.msc** in Windows Run, and hitting the **Enter** key to [open the LGPE on Windows](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

![Gpedit In Run Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Gpedit-In-Run-Menu.jpg)

 In the left panel, navigate to **Configuration > Windows Settings > Security Settings > Local Policies > Security Options**. In the right panel, double-click the **User Account Control: Behavior of the elevation prompt for administrators in Admin Approval Mode** policy to access its **Properties** window.

![the UAC behavior for admin policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/uac-behavior-admin-policy-local-group-policy-editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qv4Qm7kpeMs?si=9fv5SOS5a2DvixTK&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Click on the dropdown and select the UAC behavior you want.

![Editing the UAC behavior for admin policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-uac-behavior-admin-policy-local-group-policy-editor.jpg)

 To apply and save the changes, click on **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Jfq2Wx1Bcs?si=YQrYpTy0g4aV5QaO&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Changing UAC Behavior for Administrators in the Registry Editor

 To change the UAC behavior for administrators using the Registry Editor, start by pressing **Win + R**, typing **regedit** in Windows Run, and hitting the **Enter** key.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 In the UAC prompt, click **Yes** to [open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-local-security-policy/).

 Changing settings in the Registry Editor can impact the performance of your computer negatively if you make a mistake. To make sure you always have a way to revert the changes, we recommend learning [how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/).

 In the navigation panel on the left, head to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Policies > System**. In the right panel, double-click the **ConsentPromptBehaviorAdmin** value to modify it.

![The ConsentPromptBehaviorAdmin value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/consentpromptbehavior-value-registry-editor.jpg)

 Enter one of the following variables in the text box for **Value date**:

| Variable | UAC Behavior                                 |
| -------- | -------------------------------------------- |
| 0        | Elevate without prompting                    |
| 1        | Prompt for credentials on the secure desktop |
| 2        | Prompt for consent on the secure desktop     |
| 3        | Prompt for credentials                       |
| 4        | Prompt for consent                           |
| 5        | Prompt for consent for non-Windows binaries  |

 So, if you were to, for example, change it to **Prompt for credentials**, you’d enter **3** in the **Value data** text box.

![Editing the ConsentPromptBehaviorAdmin value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-consentpromptbehavior-value-registry-editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DBMTAJBx-X4?si=sje5pFJXiHzJJGbP&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Then, click **OK** to apply and save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Control the UAC’s Behavior as an Administrator

 Now you can change the behavior of UAC for admins as you please, depending on your situation. Just be careful not to make your computer more vulnerable in the process, which can happen if you choose **Elevate without prompting**. Microsoft recommends using that option only when you’re in a highly secure environment where the administrator accounts are tightly controlled.

 In that case, you can even disable the UAC altogether if you'd like since you know there are other measures in place to protect your computer from unwanted or malicious programs.

 As an administrator, you can change how UAC behaves. In this guide, we’re going to show you how to do that using the Local Group Policy Editor and Registry Editor.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-info.techidaily.com/new-encompassing-understanding-the-essence-of-googles-podcasts-app/"><u>[New] Encompassing Understanding The Essence of Google's Podcasts App</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-how-to-change-background-on-teams-before-or-after-calling/"><u>[New] How to Change Background on Teams Before or After Calling</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-integrating-wirecast-into-your-youtube-livestream-strategy/"><u>[Updated] Integrating WireCast Into Your YouTube Livestream Strategy</u></a></li>
<li><a href="https://win-web.techidaily.com/7-auf-windows-11-verschiebt/"><u>7 Auf Windows 11 Verschiebt</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-mspcm-bar-functionality-on-w11/"><u>Essential Guide to MSPCM Bar Functionality on W11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-non-responsive-windows-11-troubleshooters/"><u>Fixing Non-Responsive Windows 11 Troubleshooters</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-part-of-the-touch-screen-not-working-on-oneplus-nord-ce-3-lite-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Part of the Touch Screen Not Working on OnePlus Nord CE 3 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-corrupt-mp4-and-mov-files-of-zte-using-video-repair-utility-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair corrupt MP4 and MOV files of ZTE using Video Repair Utility on Mac?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-to-update-your-email-on-the-proton-vpn-browser-add-on-safely/"><u>How to Update Your Email on the Proton VPN Browser Add-On Safely</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-vivo-s18-mirror-screen-to-pc-drfone-by-drfone-android/"><u>How Vivo S18 Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-connectivity-challenges-in-winmc-minecraft/"><u>Navigating Connectivity Challenges in WinMC Minecraft</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-for-windows-no-sound-despite-connected-devices/"><u>Remedy for Windows: No Sound Despite Connected Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-address-cannot-link-with-nvidia-error-on-microsofts-latest-os/"><u>Steps to Address Cannot Link with NVIDIA Error on Microsoft's Latest OS</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-decrease-cpu-spikes-from-modules-installer/"><u>Strategies to Decrease CPU Spikes From Modules Installer</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/the-ultimate-guide-to-understanding-the-advantages-of-apples-latest-laptop-macbook-pro-16-inch-m1-2021/"><u>The Ultimate Guide to Understanding the Advantages of Apple's Latest Laptop: MacBook Pro 16-Inch (M1, 2021)</u></a></li>
<li><a href="https://solve-news.techidaily.com/transform-your-broadcasts-using-manycam-the-ultimate-virtual-camera-solution-for-seamless-livestreams/"><u>Transform Your Broadcasts Using ManyCam - The Ultimate Virtual Camera Solution for Seamless Livestreams</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-microsoft-store-error-code-x800704cf-on-windows-devices/"><u>Troubleshooting: Microsoft Store Error Code X800704CF on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-secrets-of-successful-installer-fixes/"><u>Unlocking the Secrets of Successful Installer Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-methods-identifying-active-tcpip-connections/"><u>Windows Methods: Identifying Active TCP/IP Connections</u></a></li>
</ul></div>

