---
title: Disabling Another User's Microsoft Account on Shared Device
date: 2024-07-11T22:25:08.868Z
updated: 2024-07-12T22:25:08.868Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disabling Another User's Microsoft Account on Shared Device
excerpt: This Article Describes Disabling Another User's Microsoft Account on Shared Device
keywords: Disable Access,Microsoft Account Restriction,User Account Lockout,Prevent Shared Login,Disabling Multiple Logins,Unauthorized Device Management,Secure Shared Computers
thumbnail: https://thmb.techidaily.com/b9c87935bcb636b8006c11267defd1b13d4f0a5467f4617c51e1bd762f7f5db4.png
---

## Disabling Another User's Microsoft Account on Shared Device

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
<li><a href="https://windows11.techidaily.com/clearing-up-the-blocked-app-notification-issue/"><u>Clearing Up the Blocked App Notification Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/directing-system-thermal-output-with-customization/"><u>Directing System Thermal Output with Customization</u></a></li>
<li><a href="https://windows11.techidaily.com/command-your-way-through-windows-11-nircmd-tips-and-tricks/"><u>Command Your Way Through Windows 11: NirCmd Tips & Tricks</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/from-empty-screens-to-thriving-content-why-no-one-watched-your-video-for-2024/"><u>From Empty Screens to Thriving Content  Why No One Watched Your Video for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/cracked-codekeepers-stay-secure-in-the-now/"><u>Cracked Codekeepers: Stay Secure in the Now</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-the-past-updating-decrepit-windows-cards/"><u>Clearing the Past: Updating Decrepit Windows Cards</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-the-concealed-aspects-understanding-the-unique-stories-of-followers/"><u>[Updated] The Concealed Aspects  Understanding the Unique Stories of Followers</u></a></li>
<li><a href="https://windows11.techidaily.com/command-line-conjuring-windows-new-feature/"><u>Command Line Conjuring: Windows' New Feature</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2023-best-facebook-video-downloader-and-addons-for-firefox/"><u>[Updated] 2023 | Best Facebook Video Downloader And Addons for Firefox</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-what-windows-11s-new-updates-signify-for-users/"><u>Delving Into What Windows 11'S New Updates Signify For Users</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-mastering-instagrams-latest-trends-reels-and-stories/"><u>[Updated] 2024 Approved  Mastering Instagram's Latest Trends  Reels and Stories</u></a></li>
<li><a href="https://windows11.techidaily.com/decrease-resource-load-managing-news-app-consumption/"><u>Decrease Resource Load: Managing News App Consumption</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-the-advantages-of-microsofts-copilot-key-for-windows-11/"><u>Demystifying the Advantages of Microsoft's Copilot Key for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-microsofts-window-file-format-cab-for-ease-of-use/"><u>Deciphering Microsoft's Window File Format (CAB) for Ease of Use</u></a></li>
<li><a href="https://windows11.techidaily.com/cool-off-cycles-in-the-world-of-computers/"><u>Cool-Off Cycles in the World of Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/diagnosing-partially-functioning-windows-earphones/"><u>Diagnosing Partially Functioning Windows Earphones</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-finding-pixel-ringtone-treasures-online/"><u>2024 Approved  Finding Pixel Ringtone Treasures Online</u></a></li>
<li><a href="https://animation-videos.techidaily.com/2024-approved-how-to-analyze-an-editorial-cartoon-easily/"><u>2024 Approved How to Analyze an Editorial Cartoon Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/cleanse-your-screen-history-3-strategies/"><u>Cleanse Your Screen History - 3 Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/create-your-own-windows-speech-recognition-app-with-autohotkey-and-whisper/"><u>Create Your Own Window's Speech Recognition App with AutoHotkey and Whisper</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-file-damage-enigma-winning-over-error-0x80070570-on-windows-11/"><u>Deciphering the File Damage Enigma - Winning Over Error 0X80070570 on Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-android-to-apple-how-to-transfer-photos-from-itel-a60s-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Android to Apple How To Transfer Photos From Itel A60s to iPad Easily | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-an-efficient-menu-choice-for-regular-system-checks-on-win11plus11/"><u>Crafting an Efficient Menu Choice for Regular System Checks on Win11+11</u></a></li>
<li><a href="https://windows11.techidaily.com/dazzling-holiday-windows-a-celebration-of-joy-and-light/"><u>Dazzling Holiday Windows: A Celebration of Joy & Light</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-words-best-writing-software-for-windows-users/"><u>Conquer Words: Best Writing Software for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-dilemma-deciphered-7-strategies-to-reopen-browsers-in-win-os/"><u>Digital Dilemma Deciphered: 7 Strategies to Reopen Browsers in WIN OS</u></a></li>
<li><a href="https://windows11.techidaily.com/defensive-operations-mastering-windows-unauthorized-prevention/"><u>Defensive Operations: Mastering Windows Unauthorized Prevention</u></a></li>
<li><a href="https://windows11.techidaily.com/combining-audioscapes-and-visuals-snipping-tool-guide-max-156/"><u>Combining Audioscapes & Visuals: Snipping Tool Guide (Max 156)</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-harmonizing-sounds-with-imagery-professional-strategies-to-boost-your-videography/"><u>In 2024, Harmonizing Sounds with Imagery Professional Strategies to Boost Your Videography</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-drives-c-vs-d-explanation/"><u>Deciphering Drives: C: Vs D: Explanation</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-a-closer-look-at-youtubes-payment-system-and-its-potential/"><u>[Updated] A Closer Look at YouTube's Payment System and Its Potential</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-top-ae-scripting-tools-and-plug-ins/"><u>2024 Approved  Top AE Scripting Tools & Plug-Ins</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-parsing-setback-code-0xc00ce556/"><u>Conquering Parsing Setback: Code 0xC00CE556</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-filehistoryfaults-in-windows-os/"><u>Dealing with FileHistoryFaults in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-graphics-output-dpi-adjustment-guide/"><u>Customizing Graphics Output: DPI Adjustment Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/compact-guide-best-windows-forecasting-tools/"><u>Compact Guide: Best Windows Forecasting Tools</u></a></li>
<li><a href="https://howto.techidaily.com/vivo-v27-pro-bootloop-problem-how-to-fix-it-without-data-loss-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Vivo V27 Pro Bootloop Problem, How to Fix it Without Data Loss | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-rectifying-the-pink-screen-dilemma/"><u>Decoding and Rectifying the Pink Screen Dilemma</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-mastering-game-capture-windows-11-edition/"><u>[New] 2024 Approved  Mastering Game Capture  Windows 11 Edition</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-a-oppo-reno-11f-5g-easily-by-drfone-android/"><u>In 2024, How To Unlock a Oppo Reno 11F 5G Easily?</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-in-2024-12-best-marketing-slideshow-templates/"><u>New In 2024, 12 Best Marketing Slideshow Templates</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/dial-up-the-impact-with-50-free-branding-graphics-in-2024/"><u>Dial Up the Impact with 50 FREE Branding Graphics, In 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-ace-the-art-of-altering-and-amplifying-vhs-photos-on-computers-for-2024/"><u>[Updated] Ace the Art of Altering and Amplifying VHS Photos on Computers for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>