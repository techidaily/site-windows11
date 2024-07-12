---
title: "Clearing Up Dual Users: Fixing Their Windows Account Error"
date: 2024-07-11T22:23:19.910Z
updated: 2024-07-12T22:23:19.910Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Clearing Up Dual Users: Fixing Their Windows Account Error"
excerpt: "This Article Describes Clearing Up Dual Users: Fixing Their Windows Account Error"
keywords: Dual User Windows FIX,Resolve Windows Errors,Removing Login Issues,Unlock Windows Passwords,Eliminate User Conflict,Solve Account Mismatch,Erase Windows Logins Wrong
thumbnail: https://thmb.techidaily.com/0f399835ae801930fc09d856b55526ca68007b6aa28f7cfc8442056063114a14.jpg
---

## Clearing Up Dual Users: Fixing Their Windows Account Error

 So you're trying to sign in to your Windows device with a Microsoft account, but it throws an error that reads, "another user on this device uses this Microsoft account." You're certain that the account isn't signed in to the device, so why is Windows showing an error?

 Although this error serves as a security feature to keep your device safe, it can sometimes overdo it and lock you out. Fortunately, there are plenty of solutions for this error. Let's start by understanding what causes the error and then explore the possible solutions.

## What Is the "Another User on This Device Uses This Microsoft Account" Error?

![Windows displaying an error when adding account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-already-signedin.jpg)

 The "another user on this device uses this Microsoft account" error is a message that appears when you are trying to sign in to a Microsoft account on a device that already has a user signed in with the same account. This can happen if multiple users share a computer or if you are trying to access your account from a different device.

 The error message is a security measure to prevent unauthorized access to your account. In most scenarios, this error pops up if you've previously signed in with your account on that device, then deleted your account. If your account wasn't completely wiped off the device, you'll get this error message when you try to log in with it again.

 Another variation of this error reads "account already has been added to this PC." Fortunately, the solutions for both these errors are the same. Let's explore these solutions in more detail.

## 1\. Remove the Device from Your Microsoft Account

 When you log in to a Windows device with your Microsoft account, the two begin communicating with one another. The device adds your account to its list of recognized users, while your account also adds the device to its list of connected devices.

 However, there may be instances when your account stays linked to a device even after you've removed it. This could be a possible reason why you are encountering the "another user on this device uses this Microsoft account" error.

![Removing a device from Microsoft accounts.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/microsoft-account-devices.jpg)

 Thus, the first solution you can try is to remove the device from your Microsoft account. Here's how you can do it:

1. Go to the [Microsoft account website](https://account.microsoft.com) and sign in with your account credentials.
2. Go to the **Devices** tab and select the device you want to sign in on.
3. Click on the **Remove** hyperlink to remove the device from your Microsoft account.
4. Check **I'm ready to remove this device** and then click **Remove**.

 Restart your device and try signing in to your Microsoft account again. If this doesn't fix the error, you'll need to get your hands slightly dirty.

 The other solutions for this error require you to have access to an administrator account on the Windows device. If you don't have access to an administrator account, you'll have to ask the device owner to apply these solutions.

## 2\. Delete the Account From the Local Users and Groups Settings

 As the name implies, the Local Users and Groups Settings let you manage your computer's users and groups. You can change the permissions and memberships of each user, and in this case, you can use it to delete the excess user.

![Windows local users and groups settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-local-users.jpg)

 There are several [ways to access Windows' Local Users and Groups settings](https://www.makeuseof.com/windows-open-local-users-and-groups/). Once it's open, in the Local Users and Groups window, navigate to **Users**. Find the user account that's causing the error, right-click on it, then select **Delete**.

 Restart your device and try signing in to your Microsoft account again.

## 3\. Delete the Account Using the Registry Editor

 To ensure that the Microsoft account leaves no trails behind, you can clean up the remnants using the [Windows Registry Editor](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/). However, if the previous solution worked properly for you, you won't find the account in Registry Editor.

 Here's how you can delete the account with Registry Editor:

1. Open the Start menu and search for **Registry Editor**.
2. Open **Registry Editor**.
3. On the left-side pane, navigate to **HKEY\_USERS > .DEFAULT > Software > Microsoft > IdentityCRL > StoredIdentities**.
4. Once you expand **StoredIdentities**, you'll see a list of signed-in Microsoft accounts.  
![Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windwos-registery-user.jpg)
5. Right-click the account and select **Delete**.

 Note that this time you'll only see the Microsoft accounts on the device, not the local accounts. If these do not resolve the issue, it is likely that the problem extends beyond this specific account.

## 4\. Change the Local Security Policy Settings

 Ever since Windows 10, Microsoft has been pushing users to sign in with their Microsoft accounts rather than local Windows accounts.

 Although you can now easily [create a local account in Windows](https://www.makeuseof.com/windows-11-create-local-user-account/), security policies regarding the accounts on your computer might be causing the "another user on this device uses this Microsoft account" error.

![Local security policies in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-security-policy.jpg)

 You can change the local security policy on your device so that it doesn't block Microsoft accounts from logging in. You can do this through the Local Security Policies settings in Windows. Here's how:

1. Open the Local Security Policy window (see [how to open the Local Security Policy in Windows](https://www.makeuseof.com/windows-11-local-security-policy/) if you need help).
2. In the Local Security Policy window, navigate to **Security Settings** \> **Local Policies** \> **Security Options**.
3. Find the **Accounts: Block Microsoft accounts** policy and double-click on it.
4. From the drop-down list, select **This policy is disabled**.
5. Click on **Apply** and **OK** to save the changes.

 Restart your device and try signing in to your Microsoft account. If the error still persists, it might be time to outsource your solutions and [contact Microsoft support](https://www.makeuseof.com/contact-microsoft-support/) to have them help you out.

## Fix the "Another User on This Device Uses This Microsoft Account" Error and Get Back to Work

 This error becomes frustrating when it persists even after you've long deleted the account from that device. Hopefully, the solutions mentioned here will help you thoroughly sever the tie between your account and the device so you can sign in again.

 If all the measures here fail, you can contact Microsoft support and ask them for help. If that too fails, then there's no better fixer than a fresh installation of Windows.

 Although this error serves as a security feature to keep your device safe, it can sometimes overdo it and lock you out. Fortunately, there are plenty of solutions for this error. Let's start by understanding what causes the error and then explore the possible solutions.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/clearing-up-the-confusing-blue-screen-error-0x8007007e/"><u>Clearing Up the Confusing Blue Screen Error: 0X8007007E</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-understanding-and-leveraging-influencers-on-snapchat/"><u>2024 Approved  Understanding and Leveraging Influencers on Snapchat</u></a></li>
<li><a href="https://windows11.techidaily.com/desk-clean-up-restoring-windows-11-desktop-symbols/"><u>Desk Clean-Up: Restoring Windows 11 Desktop Symbols</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/resolve-safaris-live-streaming-stumbling-blocks-for-2024/"><u>Resolve Safari's Live-Streaming Stumbling Blocks for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-prime-streamers-selection-the-best-websites-for-2024/"><u>[Updated] Prime Streamers' Selection  The Best Websites for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-clearance-top-techniques-for-latency-free-video-on-pc/"><u>Cutting-Edge Clearance: Top Techniques for Latency-Free Video on PC</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-unleashing-potential-top-10-tiktok-data-analysis-tools/"><u>In 2024, Unleashing Potential  Top 10 TikTok Data Analysis Tools</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-master-the-art-of-professional-webcam-filming/"><u>[New] 2024 Approved  Master the Art of Professional Webcam Filming</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-dealing-with-steam-installation-fiascos-win11-style/"><u>Decoding and Dealing with Steam Installation Fiascos, Win11-Style</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/top-3-affordable-switch-game-duplicates-for-2024/"><u>Top 3 Affordable Switch Game Duplicates for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/discovery-of-four-cortana-succession-steps/"><u>Discovery of Four Cortana Succession Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-rectifying-windows-11-search-issues/"><u>Comprehensive Guide to Rectifying Windows 11 Search Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-non-selectable-items-in-win11-setup/"><u>Dealing with Non-Selectable Items in Win11 Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/coalescing-file-structures-a-windows-guide/"><u>Coalescing File Structures, A Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-windows-ram-allocation-strategies/"><u>Deciphering Windows' RAM Allocation Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-access-issues-fixing-the-no-write-allowed-error/"><u>Dealing with Access Issues: Fixing the No Write Allowed Error</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-dominance-your-must-have-msistore-picks/"><u>Digital Dominance: Your Must-Have MSIStore Picks</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-the-clutter-soundcard-irq-solutions/"><u>Cutting the Clutter: Soundcard IRQ Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/diving-deep-using-the-netstat-command-in-windows-11-os/"><u>Diving Deep: Using the Netstat Command in Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-the-secret-to-smoothly-controlling-your-touchpad-in-windows-11/"><u>Discover the Secret to Smoothly Controlling Your Touchpad in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-windows-cab-and-its-method-for-installed-content/"><u>Deciphering Windows CAB & Its Method for Installed Content</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-and-correcting-not-found-on-windows/"><u>Deciphering and Correcting 'Not Found' On Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/cost-saving-strategies-for-new-windows-11-users/"><u>Cost-Saving Strategies for New Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-down-unnecessary-memory-use-by-webview2-on-edge/"><u>Cutting Down Unnecessary Memory Use by WebView2 on Edge</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-messages-from-infinix-note-30-by-fonelab-android-recover-messages/"><u>Possible solutions to restore deleted messages from Infinix Note 30</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-iphone-camera-savvy-image-optimization-secrets/"><u>2024 Approved  IPhone Camera Savvy  Image Optimization Secrets</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/10-best-screenshot-enhancers-iphoneandroid-sticker-magic/"><u>10 Best Screenshot Enhancers  IPhone/Android Sticker Magic</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-exploring-ghoulish-auditory-extras-for-2024/"><u>Updated Exploring Ghoulish Auditory Extras for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-workings-of-windows-memory-cache/"><u>Deciphering the Workings of Windows Memory Cache</u></a></li>
<li><a href="https://windows11.techidaily.com/dive-into-game-worlds-playing-android-apps-in-windows-11-via-google-services/"><u>Dive Into Game Worlds: Playing Android Apps in Windows 11 via Google Services</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-snapchat-wizardry-flipping-your-video-narrative/"><u>[New] In 2024, Snapchat Wizardry  Flipping Your Video Narrative</u></a></li>
<li><a href="https://windows11.techidaily.com/command-line-interface-cli-addition-to-task-manager-in-windows-11/"><u>Command Line Interface (CLI) Addition to Task Manager in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/declutter-for-growth-optimize-with-win11-tiny/"><u>Declutter for Growth: Optimize With Win11 Tiny</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-unlock-6-free-youtube-endings-for-pros/"><u>[New] Unlock 6 Free YouTube Endings for Pros</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-exceptional-20-no-license-pubg-images-for-2024/"><u>[Updated] Exceptional 20 No-License PUBG Images for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-the-ultimate-guide-to-best-podcast-platforms/"><u>New 2024 Approved The Ultimate Guide to Best Podcast Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/command-your-computer-mastery-of-windows-through-alomware/"><u>Command Your Computer: Mastery of Windows Through AlomWare</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-best-mp4-editors-for-mavericks-review-and-comparison-for-2024/"><u>Updated Best MP4 Editors for Mavericks Review and Comparison for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/leading-least-expensive-stock-images-online-for-2024/"><u>Leading Least Expensive Stock Images Online for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-how-to-optimize-win11-taskbar/"><u>Discover How to Optimize Win11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-xbox-mic-blockages-for-flawless-windows-11-operation/"><u>Clearing Up Xbox Mic Blockages for Flawless Windows 11 Operation</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unlock-iphone-editing-magic-shorter-smaller-videos/"><u>[Updated] Unlock iPhone Editing Magic  Shorter, Smaller Videos</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-oppo-k11-5g-drfone-by-drfone-virtual-android/"><u>15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Oppo K11 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-updates-fault-0x8019/"><u>Clearing Updates Fault 0X8019</u></a></li>
<li><a href="https://windows11.techidaily.com/cybersecurity-commandments-winning-access-prevention-on-windows/"><u>Cybersecurity Commandments: Winning Access Prevention on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/command-center-for-direct-access-to-windows-11s-appsfolders/"><u>Command Center for Direct Access to Windows 11'S AppsFolders</u></a></li>
<li><a href="https://howto.techidaily.com/fixes-for-apps-keep-crashing-on-honor-magic5-ultimate-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixes for Apps Keep Crashing on Honor Magic5 Ultimate | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-complexity-of-wintoys-your-guide-to-a-versatile-tool/"><u>Decoding the Complexity of 'WinToys': Your Guide to a Versatile Tool</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-remove-a-previously-synced-google-account-from-your-nokia-c12-plus-by-drfone-android/"><u>In 2024, How to Remove a Previously Synced Google Account from Your Nokia C12 Plus</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-what-pokemon-evolve-with-a-dawn-stone-for-vivo-y100t-drfone-by-drfone-virtual-android/"><u>In 2024, What Pokémon Evolve with A Dawn Stone For Vivo Y100t? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-solutions-to-spy-on-oppo-reno-11-pro-5g-with-and-without-jailbreak-drfone-by-drfone-virtual-android/"><u>In 2024, Solutions to Spy on Oppo Reno 11 Pro 5G with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/command-the-past-mastering-file-history-navigation/"><u>Command the Past: Mastering File History Navigation</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-film-makers-guide-to-selecting-between-hero-and-cube-videos/"><u>In 2024, Film Maker's Guide to Selecting Between Hero and Cube Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-windows-blue-screen-code-0x0000003b-breakdown-and-fixes/"><u>Deciphering Windows Blue Screen: Code 0X0000003B Breakdown & Fixes</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-the-ultimate-guide-to-bypassing-icloud-activation-lock-on-iphone-6-by-drfone-ios/"><u>In 2024, The Ultimate Guide to Bypassing iCloud Activation Lock on iPhone 6</u></a></li>
<li><a href="https://windows11.techidaily.com/concealing-windows-firewall-areas-a-step-by-step-guide/"><u>Concealing Windows Firewall Areas: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/counteracting-microsofts-store-0x800704cf-issue/"><u>Counteracting Microsoft's Store 0X800704CF Issue</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>