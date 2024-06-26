---
title: Adjusting Non-Admin Privilege Levels in Windows OS
date: 2024-06-25T12:07:17.958Z
updated: 2024-06-26T12:07:17.958Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Non-Admin Privilege Levels in Windows OS
excerpt: This Article Describes Adjusting Non-Admin Privilege Levels in Windows OS
keywords: Windows Privileges Control,Admin Rights Management,User Permissions Edit,Privacy Settings Adjust,Secure OS Access Levels,Non-Admin Privilege Fix,Increase Security, Decrease Risk
thumbnail: https://thmb.techidaily.com/1fd97819f96aea4d97e8ac4ff57edab197b6c14d91b0c90b63f17b606d1e7ada.jpg
---

## Adjusting Non-Admin Privilege Levels in Windows OS

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

## Control UAC's Behavior for Standard Users on Windows

 UAC is an integral part of protecting your Windows computer from malicious programs that want to run with elevated privileges. While you can't make it elevate programs without prompting, you can make it stricter by setting it to **Automatically deny elevation requests**. And, as you can see, it is quite easy to do, whether you're using the Local Group Policy Editor or the Registry Editor.

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/reduce-precision-jumps-turn-off-mouse-speed-on-your-pc/"><u>Reduce Precision Jumps: Turn Off Mouse Speed on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-secrets-to-stable-apex-play-on-windows-11/"><u>Unlocking the Secrets to Stable Apex Play on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-missed-files-in-steam-and-windows-11/"><u>Overcoming Missed Files in Steam & Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/diminishing-high-cpu-impact-of-tiworkerexe-applications/"><u>Diminishing High CPU Impact of TiWorker.exe Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-windows-11s-admin-tools/"><u>Exploring Windows 11'S Admin Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-original-settings-post-deletion-win-11/"><u>Restoring Original Settings Post Deletion (Win 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-windows-cars-keyboard-magic-boosts-speed/"><u>Top 5 Windows Cars: Keyboard Magic Boosts Speed</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-resolve-high-dpi-screen-problems-on-pc/"><u>Strategies to Resolve High DPI Screen Problems on PC</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-step-by-step-process-for-capturing-top-tier-presentations/"><u>[New] In 2024, Step-by-Step Process for Capturing Top-Tier Presentations</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-choosing-pro-stream-vmix-vs-wirecast-battle/"><u>[Updated] Choosing Pro Stream  VMix Vs. Wirecast Battle</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-amazons-hot-take-tiktoks-shop-smart-with-top-picks/"><u>[New] 2024 Approved  Amazon's Hot Take TikToks  Shop Smart with Top Picks</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-pioneering-pathways-in-virtual-reality-biking/"><u>[Updated] Pioneering Pathways in Virtual Reality Biking</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-photos-from-galaxy-s24-by-fonelab-android-recover-photos/"><u>How to Rescue Lost Photos from Galaxy S24?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/where-is-the-best-place-to-catch-dratini-on-asus-rog-phone-7-drfone-by-drfone-virtual-android/"><u>Where Is the Best Place to Catch Dratini On Asus ROG Phone 7 | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-galaxy-s8-review-a-new-era-for-superior-smartphones/"><u>[New] Galaxy S8 Review - A New Era for Superior Smartphones</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-face-flaunting-visual-guidebook/"><u>[Updated] Face Flaunting Visual Guidebook</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-smartphone-storytelling-best-practices-for-vertical-video-for-2024/"><u>Updated Smartphone Storytelling Best Practices for Vertical Video for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>