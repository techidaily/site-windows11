---
title: "Optimizing Privileges: A Guide to Modifying Standard Users' Access in Windows"
date: 2024-09-14T22:23:38.166Z
updated: 2024-09-15T22:22:24.844Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Optimizing Privileges: A Guide to Modifying Standard Users' Access in Windows"
excerpt: "This Article Describes Optimizing Privileges: A Guide to Modifying Standard Users' Access in Windows"
keywords: WinUserRightsEnhance,UserAccessModifyWin,AdjustWinPermsGuide,PrivilegeCustomizeWin,ElevateWindowsUsers,AccessControlWinOS,StandardUserPrivilege
thumbnail: https://thmb.techidaily.com/5a6b81e19407a604be22bf69df443b0f8b7b5bc4d3841b542775d6677ac13b8e.jpg
---

## Optimizing Privileges: A Guide to Modifying Standard Users' Access in Windows

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
<a href="https://bluettius.sjv.io/c/5597632/2139112/17108" target="_top" id="2139112">
  <img src="//a.impactradius-go.com/display-ad/17108-2139112" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139112/17108" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-live-streaming-made-easy-expert-reviews-of-top-obs-tools/"><u>[New] 2024 Approved Live Streaming Made Easy Expert Reviews of Top OBS Tools</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/effettuare-la-registrazione-di-disco-con-winxdvd-su-sistemi-windows-11-e-7-tutto-in-quattro-fasi-facili/"><u>Effettuare La Registrazione Di Disco Con WinXDVD Su Sistemi Windows 11 E 7 - Tutto in Quattro Fasi Facili</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-to-resurrect-itunes-on-windows-devices/"><u>Essential Steps to Resurrect iTunes on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-mute-amdnvidia-graphic-enhancements/"><u>How to Mute AMD/Nvidia Graphic Enhancements</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-getting-the-pokemon-go-gps-signal-not-found-11-error-in-vivo-v29e-drfone-by-drfone-virtual/"><u>In 2024, Getting the Pokemon Go GPS Signal Not Found 11 Error in Vivo V29e | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-apple-iphone-14-plus-location-on-twitter-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Change your Apple iPhone 14 Plus Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-prevent-cross-site-tracking-on-tecno-phantom-v-fold-and-browser-drfone-by-drfone-virtual-android/"><u>In 2024, Prevent Cross-Site Tracking on Tecno Phantom V Fold and Browser | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-the-complete-guide-to-honor-play-40c-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Complete Guide to Honor Play 40C FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://windows11.techidaily.com/silent-steps-a-quick-guide-to-stopping-windows-11-activities/"><u>Silent Steps: A Quick Guide to Stopping Windows 11 Activities</u></a></li>
<li><a href="https://windows11.techidaily.com/steady-your-cursor-fixing-erratic-movements-in-windows-11/"><u>Steady Your Cursor: Fixing Erratic Movements in Windows 11</u></a></li>
<li><a href="https://sound-issues.techidaily.com/step-by-step-solutions-for-fixing-a-broken-bose-audio-unit/"><u>Step-by-Step Solutions for Fixing a Broken Bose Audio Unit</u></a></li>
<li><a href="https://windows11.techidaily.com/the-winning-edge-a-compilation-of-top-8-editors-for-windows/"><u>The Winning Edge: A Compilation of Top 8 Editors for Windows</u></a></li>
<li><a href="https://tech-hub.techidaily.com/top-5-web-based-learning-pathways-to-become-an-expert-in-ai-prompt-creation/"><u>Top 5 Web-Based Learning Pathways to Become an Expert in AI Prompt Creation</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/tuneful-translations-sing-your-way-to-second-language-success/"><u>Tuneful Translations: Sing Your Way to Second Language Success</u></a></li>
<li><a href="https://windows11.techidaily.com/unveil-if-your-pc-is-prepared-for-the-upcoming-os/"><u>Unveil If Your PC Is Prepared for the Upcoming OS</u></a></li>
</ul></div>

