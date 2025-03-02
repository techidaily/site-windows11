---
title: Redefining Privileges for Non-Administrative Windows Users
date: 2025-02-23T00:36:05.774Z
updated: 2025-03-01T17:36:47.991Z
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
<li><a href="https://article-posts.techidaily.com/new-2024-approved-best-video-player-apps-for-windows-phone/"><u>[New] 2024 Approved Best Video Player Apps for Windows Phone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-expanding-digital-presence-stream-to-youtube-plus-additional-platforms/"><u>[New] 2024 Approved Expanding Digital Presence Stream to YouTube + Additional Platforms</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-the-art-of-capture-and-storage-managing-snapshots-like-a-pro/"><u>[New] The Art of Capture and Storage Managing Snapshots Like a Pro</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-youtubes-best-10-cutting-edge-reaction-ideas/"><u>[New] YouTube's Best 10 Cutting-Edge Reaction Ideas</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-winterrals-visual-theme/"><u>Altering WinTerral's Visual Theme</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/compact-sound-sensation-in-the-world-of-mp3-players/"><u>Compact Sound Sensation in the World of MP3 Players</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-ways-to-revert-personalized-settings-on-windows-11s-search/"><u>Easy Ways to Revert Personalized Settings on Windows 11'S Search</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-xiaomi-redmi-12-5g-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on Xiaomi Redmi 12 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-self-shutdowns-steps-for-windows-11-users/"><u>Fix Self-Shutdowns: Steps for Windows 11 Users</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-easiest-guide-how-to-clone-honor-x50-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Easiest Guide How to Clone Honor X50 Phone? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-disconnected-windows-printer-linkup/"><u>Restoring Disconnected Windows Printer Linkup</u></a></li>
<li><a href="https://driver-error.techidaily.com/smoothing-over-elans-operational-snags-in-win10/"><u>Smoothing Over Elan's Operational Snags in Win10</u></a></li>
<li><a href="https://windows11.techidaily.com/solve-icloud-download-issues-with-these-helpful-steps/"><u>Solve iCloud Download Issues with These Helpful Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/systematic-approach-to-eliminate-flashing-on-windows/"><u>Systematic Approach to Eliminate Flashing on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-guide-to-brightening-the-windows-11-pointer/"><u>The Essential Guide to Brightening the Windows 11 Pointer</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/top-hashtags-on-instagram-boost-your-visibility/"><u>Top Hashtags on Instagram: Boost Your Visibility</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-frozen-windows-handbraked-vaults/"><u>Unlock Frozen Windows-Handbraked Vaults</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-ultimate-guide-to-selecting-mobile-speech-to-text-software/"><u>Updated 2024 Approved Ultimate Guide to Selecting Mobile Speech-to-Text Software</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-high-dynamic-range-mastered-for-the-modern-user/"><u>Windows 11'S High Dynamic Range Mastered for the Modern User</u></a></li>
</ul></div>

