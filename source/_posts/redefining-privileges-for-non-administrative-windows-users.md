---
title: Redefining Privileges for Non-Administrative Windows Users
date: 2024-09-13T20:14:20.550Z
updated: 2024-09-15T21:44:41.903Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Redefining Privileges for Non-Administrative Windows Users
excerpt: This Article Describes Redefining Privileges for Non-Administrative Windows Users
keywords: Admin Access Deficit,Non-Admin Rights,User Privilege Redesign,Non-Windows Admin Limitations,Privileges for Regular Users,Windows Usage Without Admin,Reimagining User Privileges
thumbnail: https://thmb.techidaily.com/97bc8f701c5a50640871957d35ec4f8e16308c84bcc3926e5048675a7dfb62d5.png
---

## Redefining Privileges for Non-Administrative Windows Users

 By default, standard users on Windows can run programs with elevated privileges if they enter an administrator password when prompted by User Access Control (UAC).

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

## The UAC Behaviors Available for Standard User Accounts

 Unlike when [changing UAC behaviors for administrator accounts](https://www.makeuseof.com/change-user-access-control-works-administrators-windows/), the behaviors for standard user accounts are a little more limited. According to the [Microsoft Learn](https://learn.microsoft.com/en-us/windows/security/threat-protection/security-policy-settings/user-account-control-behavior-of-the-elevation-prompt-for-standard-users) website, here are the behaviors you can choose and what they mean:

* **Automatically deny elevation requests**: This option returns an **Access denied** error message to standard users when they try to perform an operation that requires elevation of privilege. Most organizations that run desktops as standard users configure this policy to reduce help desk calls.
* **Prompt for credentials on the secure desktop**: When an operation requires elevation of privilege, the user is prompted on the secure desktop to enter a different username and password. If the user enters valid credentials, the operation continues with the applicable privilege.
* **Prompt for credentials**: An operation that requires elevation of privilege prompts the user to type an administrative username and password. If the user enters valid credentials, the operation continues with the applicable privilege.

 The default UAC behavior for standard user accounts is **Prompt for credentials**, but Microsoft recommends you change it to **Automatically deny elevation requests**. That way, only users with administrator accounts can decide how the UAC behaves and make choices that will keep the computer safe.

## How to Change the UAC Behavior for Standard Users in the Local Group Policy Editor

 The easiest way to change the way UAC behaves for standard users is to tweak the **User Account Control: Behavior of the elevation prompt for standard users** policy. To do that, [open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and follow the steps below.

 The Local Group Policy Editor isn't available by default on Windows Home. As such, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Head to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options**.
2. Right-click the **User Account Control: Behavior of the elevation prompt for standard users** policy and select **Properties** in the menu.  
![modifying the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
3. Expand the dropdown and choose a different UAC behavior.  
![editing the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/editing-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
4. Click **OK**.

 Keep in mind that only administrators can change the behavior of the UAC. If a standard user tried to change it using the Local Group Policy Editor, for example, they'd probably get an **Access denied** error message.

## How to Change the UAC Behavior for Standard Users in the Registry Editor

 If you're looking for another way to change UAC behavior for standard users, or the [Local Group Policy is not working](https://www.makeuseof.com/windows-local-group-policy-unresponsive/) on your computer, you can make changes in the Windows registry instead.

 Before you do that, however, we recommend you [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) to protect your computer in case you make a mistake. Once you do that, [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) and follow the steps below:

1. Copy **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** and paste it into the address bar at the top of the Registry Editor.  
![the System key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-key-registry-editor.jpg)
2. Press **Enter** on your keyboard to go to the **System** key.
3. Right-click the **ConsentPromptBehaviorUser** value in the right panel and select **Modify**.  
![modifying the ConsentPromptBehaviorUser value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-consentpromptbehavioruser-in-registry-editor.jpg)
4. In the **Value data** text box, enter **0** for **Automatically deny elevation requests**, **1** for **Prompt for credentials on the secure desktop**, or **3** for **Prompt for credentials**.  
![setting Value data for ConsentPromptbehavior Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/setting-value-data-for-consentpromptbehavior-registry-editor.jpg)
5. Click **OK**.

 Now restart your computer to allow the changes to take effect.

<!-- affiliate ads begin -->
<span id="1702748">
					<video width="192" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1702748.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18544-1702748">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1702748.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:120px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftwopages.pxf.io%2Fc%2F5597632%2F1702748%2F18544'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702748/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Control UAC's Behavior for Standard Users on Windows

 UAC is an integral part of protecting your Windows computer from malicious programs that want to run with elevated privileges. While you can't make it elevate programs without prompting, you can make it stricter by setting it to **Automatically deny elevation requests**. And, as you can see, it is quite easy to do, whether you're using the Local Group Policy Editor or the Registry Editor.

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-helps.techidaily.com/new-2024-approved-8-best-film-cameras-for-beginners-from-35mm-to-point-and-shoot/"><u>[New] 2024 Approved 8 Best Film Cameras for Beginners (From 35Mm to Point-and-Shoot)</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-adding-eye-catching-text-to-vids-without-costs/"><u>[New] Adding Eye-Catching Text to Vids Without Costs</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-can-you-lawfully-archive-youtube-content-for-2024/"><u>[New] Can You Lawfully Archive YouTube Content for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-evolving-tactics-for-crafting-immersive-mukbang-sessions/"><u>[New] In 2024, Evolving Tactics for Crafting Immersive Mukbang Sessions</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-pro-level-strategies-for-saving-and-recording-movs-on-windows-pcs-for-2024/"><u>[New] Pro-Level Strategies for Saving and Recording MOVs on Windows PCs for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-streamlinedwebcamtechniqueinstruction/"><u>[Updated] In 2024, StreamlinedWebCamTechniqueInstruction</u></a></li>
<li><a href="https://windows11.techidaily.com/five-keys-to-starting-system-repair-tools/"><u>Five Keys to Starting System Repair Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/ftdibussys-explained-the-culprit-behind-windows-memory-defects/"><u>Ftdibus.sys Explained: The Culprit Behind Windows Memory Defects</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-everything-you-need-to-know-about-lock-screen-settings-on-your-vivo-y36-by-drfone-android/"><u>In 2024, Everything You Need to Know about Lock Screen Settings on your Vivo Y36</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/music-video-shoot-estimated-financial-outlay/"><u>Music Video Shoot - Estimated Financial Outlay</u></a></li>
<li><a href="https://windows11.techidaily.com/reversing-keyboard-deletion-problems-on-windows-pcs/"><u>Reversing Keyboard Deletion Problems on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-fixes-for-eliminating-windows-error-code-0xc00000f/"><u>Swift Fixes for Eliminating Windows Error Code: 0Xc00000f</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-windows-update-malfunction-code-0x80246007-on-w10w11/"><u>Tackling Windows Update Malfunction: Code 0X80246007 on W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-power-of-windows-11s-system-restore-features/"><u>Unlocking the Power of Windows 11'S System Restore Features</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-icon-evolution-a-look-at-the-taskbar/"><u>Windows' Icon Evolution - A Look at the Taskbar</u></a></li>
</ul></div>

