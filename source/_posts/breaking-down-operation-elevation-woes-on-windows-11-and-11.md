---
title: Breaking Down Operation Elevation Woes on Windows 11 & 11
date: 2024-06-25T12:26:31.779Z
updated: 2024-06-26T12:26:31.779Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Breaking Down Operation Elevation Woes on Windows 11 & 11
excerpt: This Article Describes Breaking Down Operation Elevation Woes on Windows 11 & 11
keywords: WinElevationIssues,ElecWinUpdates,UpgradeWoesWindows,Win11Operational,WindowsUpdateTips,ElevateWinFix,FixWin11Issue
thumbnail: https://thmb.techidaily.com/0fffdaf6b0345d8277ec9fafebd3429c28f703cd8774f81e39bb2cfd9b5790b4.jpg
---

## Breaking Down Operation Elevation Woes on Windows 11 & 11

 Some users have reported in support forum posts that error 740 occurs when they try to run programs or access folders on Windows PCs. The error 740 message says, “The requested operation requires elevation.” Users can’t access software, folders, or files for which error 740 occurs.

 This is how you can fix error 740 within Windows 10 and 11\.

## 1\. Run the Affected Programs With Admin Rights

 The error 740 message mentions the need for operation elevation. That’s a hint to try running affected programs with elevated (administrator) rights. Check out this guide on [always running apps as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) to set affected EXE files to run with elevated rights.

![The Run this program as an administrator checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-this-program-as-an-administrator.jpg)

## 2\. Set Programs to Run in Compatibility Mode

 It’s also recommended to set older programs to run in compatibility mode. Doing so might address a compatibility issue causing error 740\. You can set an affected program to run in compatibility mode like this:

1. Open the affected software’s installation within File Explorer.
2. Right-click an affected program’s EXE (application file) and select **Properties** \> **Compatibility**.
3. Select **Run this program in compatibility mode for** and choose Windows 8 or an older platform on the drop-down menu. It’s best to select the Windows platform for which the publisher originally released the software.  
![The Run this program in compatibility mode drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-this-program-in-compatibility-mode.jpg)
4. Press the **Apply** \> **OK** buttons to set the compatibility mode setting.

## 3\. Turn Off the User Account Control Feature

 User Account Control is the security feature that throws up notifications when programs try to make changes. UAC could be a potential cause of error 740 when it’s set very high. So, try turning off UAC before running affected apps. Our [guide to disabling User Account Control](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) tells you how to turn off that feature.

![The User Account Control Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/user-account-control-settings.jpg)

## 4\. Adjust Folder Permission Settings

 This potential resolution is recommended for users who can’t access specific folders because of error 740\. In that scenario, this error can be a folder permissions issue that selecting the **Replace all child object permission entries** option could feasibly address.

 Try selecting the **Replace all child object permission** setting for an affected folder as follows:

1. Press **Win + E** to bring up File Explorer.
2. Open whatever directory contains the folder for which error 740 occurs.
3. Right-click the affected folder and select that directory’s **Properties** option.
4. Select **Security** on the window’s tab bar.
5. Click **Advanced** to access more security settings.  
![The Security tab and Advanced button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-security-tab3.jpg)
6. Select the **Replace all child object permissions entries with inheritable permission entries from this object** checkbox.  
![The Replace all child object permission entries checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/replace-all-child-objects-option.jpg)
7. Click **Apply** on the Advanced Security Settings window.
8. Select **Yes** when asked to continue.
9. Exit the folder’s properties window and restart your PC.

## 5\. Modify the Behavior of the UAC Elevation Prompt

 If your Windows PC has the Group Policy Editor, try changing the behavior of UAC’s elevation prompt with that tool. Selecting the **Elevate without prompting** setting for the User Account Control: Behavior policy could fix error 740 for some users.

 You can select that option within Windows Enterprise and Pro editions like this:

1. Open the Local Group Policy Editor. If you need help, check out the [ways to open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
2. Next, double-click **Computer Configuration** to expand that sidebar navigation option.
3. Double-click **Windows Settings** and select **Security S** **ettings**.
4. Then go to **Local Policies** and **Security Options** to access User Account Control Policy settings.  
![Security Options within Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/security-options.jpg)
5. Double-click the **User Account Control: Behavior of the elevation prompt for administrators in Admin Approval Mode** policy.
6. Select the **Elevate without prompting** option on the drop-down menu.  
![The Elevate without prompting option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/elevate-without-prompting.jpg)
7. Click **Apply** to set the **Elevate without prompting policy**.
8. Select **OK** to close the policy setting’s window.
9. Then reboot Windows after closing Group Policy Editor.

## 6\. Disable Admin Approval Mode

 Admin Approval Mode prompts administrative users for task permissions when enabled. It’s a strict Group Policy Editor security policy that can potentially cause elevation issues. Follow these steps to turn off Admin Approval Mode.

1. Go to **Security Options** in Group Policy Editor as outlined for steps one to four of resolution five.
2. Double-click the **User Account Control: Admin Approval Mode for the Built-in Administrator account** policy setting.  
![The Admin Approval Mode policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/admin-approval-mode-policy.jpg)
3. Click the **Disabled** radio button if this policy is enabled.  
![the-enabled-radio-button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enabled-radio-button.jpg)
4. Select **Apply** to turn off Admin Approval Mode.
5. To close the policy window, select the **OK** option.

## 7\. Disable Third-Party Antivirus Software Packages

 Have you installed a third-party antivirus or security app on your PC? If you have, your third-party security software could be causing error 740 by blocking the EXE file you’re trying to run. This can happen when the antivirus software flags the application file as malicious.

 The potential solution, in this case, is to temporarily disable third-party antivirus software before trying to run affected programs. Look for and select an option that turns off the antivirus shield by right-clicking on the antivirus software’s system tray icon. If there are time options available, select to turn the real-time protection off for about an hour or so.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 If disabling the security software works, you don’t necessarily have to turn the security software off whenever you want to run the application file. Your antivirus software will probably include an exclusion list to which you can add trustworthy program file exceptions. Add the affected EXE file there to exclude it from the antivirus protection.

## 8\. Migrate to a New Admin User Account

 If the “requested operation requires elevation” error persists after trying other resolutions, your user account might be corrupted. Then you might need to create and utilize a new admin account to resolve this issue. You can migrate to that account by copying files from your old user account into the new one.

![The Add account option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-account-option.jpg)

 To apply this troubleshooting method for the “requested operation requires elevation” error, follow the instructions within this article about [how to fix Windows issues by creating new user accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/). First, you’ll need to set up and sign in to the new admin account to see if the error occurs there. If not, transfer user files into the new account as covered there.

## Get Error 740 Sorted on Windows

 The “requested operation requires elevation” error is an inconvenient admin access privilege issue many users have needed to fix. Users have resolved that issue by applying the potential resolutions in this guide. So, try applying those fixes for the “requested operation requires elevation” error in the order specified to find one that works on your Windows 10 or 11 PC.

 This is how you can fix error 740 within Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/enhance-your-windows-security-incorporating-firewalls-into-context-menu/"><u>Enhance Your Windows Security: Incorporating Firewalls Into Context Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-file-scooping-6-routes-to-data-secrets/"><u>Swift File Scooping: 6 Routes to Data Secrets</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-the-process-of-disabling-windows-apps/"><u>Navigating Through the Process of Disabling Windows Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-diminished-window-11-icon-size/"><u>Understanding Diminished Window 11 Icon Size</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-financial-gains-with-w11-pro-key-deals/"><u>Unlock Financial Gains with W11 Pro Key Deals</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-workflow-efficiency-mastering-flow-launcher/"><u>Boost Workflow Efficiency: Mastering Flow Launcher</u></a></li>
<li><a href="https://windows11.techidaily.com/the-hidden-language-of-windows-update-identifiers/"><u>The Hidden Language of Windows Update Identifiers</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-xc0f1103f-flaw-with-nvidias-windows-software/"><u>Overcoming XC0F1103F Flaw with Nvidia's Windows Software</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-windows-update-error-0x8024800c/"><u>Tackling Windows Update: Error 0X8024800C</u></a></li>
<li><a href="https://some-skills.techidaily.com/transform-your-laptop-with-these-8-stylish-skins-for-2024/"><u>Transform Your Laptop with These 8 Stylish Skins for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-condense-cinematography-to-instagrams-max-on-macos/"><u>[Updated] In 2024, Condense Cinematography to Instagram's Max on macOS</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-unleash-your-inner-filmmaker-a-step-by-step-guide-to-professional-movie-making/"><u>2024 Approved Unleash Your Inner Filmmaker A Step-by-Step Guide to Professional Movie Making</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/in-2024-windows-10-video-editing-software-the-best-imovie-replacements/"><u>In 2024, Windows 10 Video Editing Software The Best iMovie Replacements</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-spotlight-on-professional-shoots-innovative-lighting-techniques/"><u>In 2024, Spotlight on Professional Shoots  Innovative Lighting Techniques</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-masterful-tiktok-makeovers-swap-video-backdrop-in-easy-steps-for-2024/"><u>[Updated] Masterful TikTok Makeovers  Swap Video Backdrop in Easy Steps for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-prime-bot-squadrons-on-discord-platform-for-2024/"><u>[New] Prime Bot Squadrons on Discord Platform for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-preserving-the-pulse-of-internet-radio-waves/"><u>In 2024, Preserving the Pulse of Internet Radio Waves</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-efficiently-engaging-with-numerous-youtube-lectures/"><u>2024 Approved  Efficiently Engaging with Numerous YouTube Lectures</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/flavorful-journeys-on-tiktoks-culinary-map/"><u>Flavorful Journeys on TikTok's Culinary Map</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>