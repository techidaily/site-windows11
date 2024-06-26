---
title: How to Unlock Windows From Stuck Twilight Settings
date: 2024-06-25T12:39:28.786Z
updated: 2024-06-26T12:39:28.786Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Unlock Windows From Stuck Twilight Settings
excerpt: This Article Describes How to Unlock Windows From Stuck Twilight Settings
keywords: Lock Windows Remediation,Override Windows Freeze,Twilight Mode Fix,Restore Windows Start,Unlock Frozen Display,Reset Windows Settings,Bypass Screen Locking
thumbnail: https://thmb.techidaily.com/77611f2e0e7b4b101c92af3b172df9c62d2c1071591d3411a278cc0334c16e37.jpg
---

## How to Unlock Windows From Stuck Twilight Settings

 You might often enable dark mode on Windows to reduce eye strain, but it’s quite frustrating when you suddenly can’t switch from dark to normal mode again

 If you’re experiencing this issue, then we’ve got solutions for you. In this article, we’ll explore the five ways to fix your Windows PC when it’s stuck in dark mode.

## 1\. Configure Settings in the Local Group Policy Editor

 The Local Group Policy Editor (LGPE) is a tool that allows you to configure various settings on your device. Interestingly, you can also use the LGPE to troubleshoot various system issues.

 Now, let’s check out how this tool can help you when your device is stuck in dark mode:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **User Configuration > Administrative Templates > Control Panel > Personalization**.
4. Double-click on the **Prevent changing theme** option on the right-hand side pane.

![Using the Local Group Policy Editor to Prevent Others From Changing the Desktop Theme](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-the-Local-Group-Policy-Editor-to-Prevent-Others-From-Changing-the-Desktop-Theme.jpg)

 Next, select the **Not Configured** or **Disabled** option on the pop-up screen. From there, click **Apply** and then click **OK** to disable the **Prevent changing theme** option.

 If the issue persists, navigate to the **Personalization** folder as per the previous steps and then disable the following options:

* Prevent changing color and appearance
* Prevent changing desktop background
* Prevent changing screen saver
* Prevent changing color scheme
* Load a specific theme
* Force specific screen saver
* Force a specific visual style file or force Windows Classic

 Finally, restart your device to save these changes.

## 2\. Tweak the Contrast Theme Settings

 You might be stuck in dark mode simply because you’ve enabled the "High contrast" option on Windows. So, let’s check out how you can resolve this problem:

1. Press **Win + I** to open the system settings.
2. Select **Ease of Access** from the options.
3. Click **High contrast** on the left.
4. **Turn off** the button below the **Turn on high contrast** option and check if this resolves the issue.

![Turning off the button below the Turn on high contrast option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/turning-off-the-button-below-the-turn-on-high-contrast-option.jpg)

## 3\. Edit the Relevant Registry Files

 Editing some Registry files could also help you tackle the issue at hand. But to be on the safe side, [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first before you proceed. This tool is sensitive and could wreak havoc on your PC if you tweak the wrong keys.

 Now, here’s how to fix the “dark mode” problem using the Registry Editor:

1. Press **Win + R** to open the Run command dialog box.
2. Type **regedit** and press **Enter** to open the Registry Editor. Alternatively, check out [the various ways to access the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. Type the following command into the address bar:

HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Themes\Personalize

 Next, double-click on the **AppsUseLightTheme** value on the right-hand side pane.

![Clicking the AppsUseLightTheme value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/clicking-the-appsuselighttheme-value.jpg)

 Type **0** in the **Value data** box and then click **OK**.

 From there, set the **Value data** as **0** for the **ColorPrevalence**, **EnableTransparency**, and **SystemUsesLightTheme** values. When you finish, restart your device and check if this resolves the problem.

## 4\. Disable Third-Party Apps Like the Auto Dark Mode Tool

 Apps like the [Microsoft Auto Dark Mode](https://apps.microsoft.com/store/detail/auto-dark-mode/XP8JK4HZBVF435) tool switch between dark and light modes at scheduled times. If you’ve configured its settings unknowingly, then it might end up enabling the dark mode feature unexpectedly.

 To resolve the issue, the best solution would be to disable this tool (and any other similar third-party app). Alternatively, you can configure the tool’s settings to your liking. That way, your device will only go into dark mode when you want it to.

## 5\. Perform Some Generic Windows-Based Fixes

 Still struggling to resolve the issue? Perhaps the error is caused by corrupted system files. In this case, the best solution is to [repair corrupted Windows files using its built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

 And if all else fails, [update your Windows device](https://www.makeuseof.com/update-windows-manually/) and see if that helps.

## No More Getting Stuck in Dark Mode

 There’s no denying that the Windows dark mode option is quite convenient. However, being unable to switch from dark to normal mode is quite unpleasant. If your device is stuck in dark mode, try any of the solutions we’ve covered.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/how-to-speed-up-and-conclude-your-puzzled-updates/"><u>How to Speed Up and Conclude Your Puzzled Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-interactions-between-devices-and-pc-slumber/"><u>Navigating Interactions Between Devices and PC Slumber</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tune-your-system-control-delete-confirmations/"><u>Fine-Tune Your System: Control Delete Confirmations</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-eliminate-startup-disruption-due-to-winscombsvc-errors/"><u>Quick Fix: Eliminate Startup Disruption Due to WinScombSvc Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-problem-of-unrecognized-drivers-during-windows-startup/"><u>Fixing the Problem of Unrecognized Drivers During Windows Startup</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-win11-upgrades-eradicate-error-0xc1900101/"><u>Streamline Your Win11 Upgrades, Eradicate Error 0xC1900101</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-tracking-down-your-software-install-pathways-in-windows/"><u>Quick Guide: Tracking Down Your Software' Install Pathways in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-path-to-defaults-resetting-win11-admin-permissions/"><u>The Path to Defaults: Resetting Win11 Admin Permissions</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/synchronizing-creatives-videos-to-amplify-your-presence-for-2024/"><u>Synchronizing Creatives  Videos to Amplify Your Presence for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-migrate-android-data-from-honor-x9a-to-new-android-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Migrate Android Data From Honor X9a to New Android Phone? | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-anonymize-your-media-10-free-face-blurring-apps-for-photos-and-videos/"><u>2024 Approved Anonymize Your Media 10 Free Face Blurring Apps for Photos and Videos</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-techniques-for-turning-youtube-hosted-tweets-into-audio-files-for-2024/"><u>[Updated] Techniques for Turning YouTube-Hosted Tweets Into Audio Files for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-from-end-to-start-annoying-yourself-with-yt-playlist-upside-down/"><u>2024 Approved  From End to Start  Annoying Yourself with YT Playlist Upside-Down</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-techniques-for-silencing-audio-tracking-in-videos/"><u>In 2024, Techniques for Silencing Audio Tracking in Videos</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-the-roadmap-for-seamless-screen-recording-using-adobe-captivity/"><u>[New] The Roadmap for Seamless Screen Recording Using Adobe Captivity</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-truth-in-the-world-of-insta-selfies/"><u>[New] 2024 Approved  Truth in the World of Insta Selfies</u></a></li>
<li><a href="https://fix-guide.techidaily.com/why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-google-pixel-fold-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Location is Not Updating and How to Fix On Google Pixel Fold | Dr.fone</u></a></li>
</ul></div>
