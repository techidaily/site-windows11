---
title: Redefining Privileges for Non-Administrative Windows Users
date: 2024-10-15T01:27:43.873Z
updated: 2024-10-18T22:42:22.605Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123735/7443" target="_top" id="2123735">
  <img src="//a.impactradius-go.com/display-ad/7443-2123735" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123735/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Keep in mind that only administrators can change the behavior of the UAC. If a standard user tried to change it using the Local Group Policy Editor, for example, they'd probably get an **Access denied** error message.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938750/19272" target="_top" id="1938750">
  <img src="//a.impactradius-go.com/display-ad/19272-1938750" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938750/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Change the UAC Behavior for Standard Users in the Registry Editor

 If you're looking for another way to change UAC behavior for standard users, or the [Local Group Policy is not working](https://www.makeuseof.com/windows-local-group-policy-unresponsive/) on your computer, you can make changes in the Windows registry instead.

 Before you do that, however, we recommend you [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) to protect your computer in case you make a mistake. Once you do that, [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) and follow the steps below:

1. Copy **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** and paste it into the address bar at the top of the Registry Editor.  
![the System key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-key-registry-editor.jpg)
2. Press **Enter** on your keyboard to go to the **System** key.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118320/7443" target="_top" id="2118320">
  <img src="//a.impactradius-go.com/display-ad/7443-2118320" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118320/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Right-click the **ConsentPromptBehaviorUser** value in the right panel and select **Modify**.  
![modifying the ConsentPromptBehaviorUser value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-consentpromptbehavioruser-in-registry-editor.jpg)
4. In the **Value data** text box, enter **0** for **Automatically deny elevation requests**, **1** for **Prompt for credentials on the secure desktop**, or **3** for **Prompt for credentials**.  

![setting Value data for ConsentPromptbehavior Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/setting-value-data-for-consentpromptbehavior-registry-editor.jpg)
5. Click **OK**.

 Now restart your computer to allow the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118323/7443" target="_top" id="2118323">
  <img src="//a.impactradius-go.com/display-ad/7443-2118323" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118323/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-top-action-capturing-software-guide/"><u>[New] In 2024, Top Action-Capturing Software Guide</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-pivot-past-moments-an-android-video-reversal-tutorial/"><u>[New] Pivot Past Moments An Android Video Reversal Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deal-makers-delight-windows-10-612-lifetime-bf-discount/"><u>Deal-Makers' Delight: Windows 10, $6.12 Lifetime BF Discount</u></a></li>
<li><a href="https://driver-download.techidaily.com/download-and-install-the-newest-quadro-graphics-drivers-on-windows-11/"><u>Download and Install the Newest Quadro Graphics Drivers on Windows 11</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/experience-championship-caliber-play-in-nba-2k19-the-definitive-virtual-basketball-challenge/"><u>Experience Championship-Caliber Play in NBA 2K19 – The Definitive Virtual Basketball Challenge</u></a></li>
<li><a href="https://windows11.techidaily.com/linux-desktops-analyzing-wsl-role/"><u>Linux Desktops: Analyzing WSL Role?</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-for-alleviating-power-management-issues-on-windows-devices/"><u>Methods for Alleviating Power Management Issues on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-remove-access-error-in-windows-file-explorer/"><u>Methods to Remove Access Error in Windows File Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/muting-windows-update-alerts-and-reminders/"><u>Muting Windows Update Alerts and Reminders</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-updating-problem-error-x8019/"><u>Overcoming Updating Problem: Error X8019</u></a></li>
<li><a href="https://screen-capture.techidaily.com/pro-moviemakers-manual-for-pc-mac-and-mobile-systems/"><u>Pro Moviemaker's Manual for PC, Mac & Mobile Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-organization-owned-chromeedge-issues-on-desktops/"><u>Resolving Organization-Owned Chrome/Edge Issues on Desktops</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-ultimate-guide-to-personalizing-your-whatsapp-ringtone-iphonesandroids-included/"><u>The Ultimate Guide to Personalizing Your WhatsApp Ringtone - iPhones/Androids Included</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/watch-educational-video-lessons-on-spotifys-latest-learning-platform/"><u>Watch Educational Video Lessons on Spotify's Latest Learning Platform!</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-the-ipogo-get-you-banned-and-how-to-solve-it-on-lava-yuva-2-drfone-by-drfone-virtual-android/"><u>Will the iPogo Get You Banned and How to Solve It On Lava Yuva 2 | Dr.fone</u></a></li>
</ul></div>

