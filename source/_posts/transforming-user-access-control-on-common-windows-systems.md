---
title: Transforming User Access Control on Common Windows Systems
date: 2024-10-17T18:49:53.637Z
updated: 2024-10-19T00:32:49.857Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Transforming User Access Control on Common Windows Systems
excerpt: This Article Describes Transforming User Access Control on Common Windows Systems
keywords: Windows Access Control Transformation,UAC Enhancement Windows,Secure Windows Security Update,Improving Windows Permissions,User Access Control Upgrade,Windows Authentication Advancement,Elevated Privilege Management Windows
thumbnail: https://thmb.techidaily.com/b1dd0483f32a09412f335f94508f9f7301d5aa196fe907bac96fdd29e9d8162d.png
---

## Transforming User Access Control on Common Windows Systems

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1972665/19272" target="_top" id="1972665">
  <img src="//a.impactradius-go.com/display-ad/19272-1972665" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972665/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![editing the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/editing-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
4. Click **OK**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049379/7443" target="_top" id="2049379">
  <img src="//a.impactradius-go.com/display-ad/7443-2049379" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049379/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Keep in mind that only administrators can change the behavior of the UAC. If a standard user tried to change it using the Local Group Policy Editor, for example, they'd probably get an **Access denied** error message.

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2141680/17091" target="_top" id="2141680">
  <img src="//a.impactradius-go.com/display-ad/17091-2141680" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettieu.pxf.io/i/5597632/2141680/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://aligracehair.sjv.io/c/5597632/1997643/19272" target="_top" id="1997643">
  <img src="//a.impactradius-go.com/display-ad/19272-1997643" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997643/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-decoding-vsdcs-technology-against-top-screen-recorder-competitors/"><u>[New] 2024 Approved Decoding VSDC's Technology Against Top Screen Recorder Competitors</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-enhance-gaming-bliss-ps5xbox-series-x-screen-revelations-for-2024/"><u>[New] Enhance Gaming Bliss PS5/Xbox Series X Screen Revelations for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-the-top-10-most-accessible-costless-lut-tools-unveiled/"><u>[Updated] In 2024, The Top 10 Most Accessible, Costless LUT Tools Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-ways-to-open-the-remote-desktop-connection-tool-in-windows-11/"><u>10 Ways to Open the Remote Desktop Connection Tool in Windows 11</u></a></li>
<li><a href="https://change-location.techidaily.com/home-button-not-working-on-nokia-105-classic-here-are-real-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Home Button Not Working on Nokia 105 Classic? Here Are Real Fixes | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-your-apple-iphone-11-pro-max-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Reset Your Apple iPhone 11 Pro Max Without iTunes? | Dr.fone</u></a></li>
<li><a href="https://article-tips.techidaily.com/inside-polarrs-magic-box-the-ultimate-digital-image-enhancer/"><u>Inside Polarr's Magic Box The Ultimate Digital Image Enhancer</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-past-windows-terminal-lockup/"><u>Navigating Past Windows Terminal Lockup</u></a></li>
<li><a href="https://windows11.techidaily.com/purge-your-pcs-defender-footprint-with-easy-steps/"><u>Purge Your PC’s Defender Footprint with Easy Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-windows-7-techniques-against-uac-intrusions/"><u>Securing Windows: 7 Techniques Against UAC Intrusions</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-copy-and-paste-features-with-application-guard-in-edge-w11-edition/"><u>Unlocking Copy & Paste Features with Application Guard in Edge, W11 Edition</u></a></li>
</ul></div>

