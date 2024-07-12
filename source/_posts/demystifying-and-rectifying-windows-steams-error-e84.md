---
title: Demystifying and Rectifying Windows Steam's Error E84
date: 2024-07-11T22:28:05.213Z
updated: 2024-07-12T22:28:05.213Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Demystifying and Rectifying Windows Steam's Error E84
excerpt: This Article Describes Demystifying and Rectifying Windows Steam's Error E84
keywords: Fixing Steam Error E84,Resolving Windows Steam Glitch,Overcoming Steam Error E84,Steam Troubleshooting Tips,E84 Error,Unlock Steam Performance,Stop Steam Error E84
thumbnail: https://thmb.techidaily.com/bcb4dab5fca23c5552c696b1f9621ccec9d5240a378ece9f04f489b258c09834.jpg
---

## Demystifying and Rectifying Windows Steam's Error E84

 The error **"Something went wrong while attempting to sign in,"** displayed as "error code e84," occurs when Steam fails to log in users automatically. This error has been around since Steam's October 2022 update.

 If you are experiencing this error, fret not. Here are some solutions you can employ to resolve the error and sign in successfully.

## 1\. Perform Some Preliminary Checks

 First, you should perform these basic fixes, as they may resolve the problem immediately:

* Restart the Steam client and your device.
* [Delete temporary files from your Windows device](https://www.makeuseof.com/windows-11-delete-temporary-files/) , as it often fixes sign-in issues in third-party apps and clients.
* According to some users who have faced this error, using your first username (the one you chose when setting up your account, not the one you currently use) to sign in fixes this issue. Hence, try to log in using that username.
* If you have a VPN enabled on your device, disable it temporarily. If you're outside the United States and aren't currently using a VPN, install one and connect to a US server.
* Interference from other gaming clients can also cause annoying sign-in issues. If you are currently running any other gaming client, especially Riot Client, shut it down.
* Check that your system clock is displaying the correct time. If it's not, check out [how to change the date and time on Windows](https://www.makeuseof.com/windows-11-change-date-time/) for more information.

 If the issue persists after applying the above checks and fixes, start applying the remaining fixes.

## 2\. Log Out of Your Steam Account on Other Devices

 Even though using the same Steam account on multiple devices is not forbidden, doing so often leads to sign-in errors like e84\. If your Steam account is currently logged in on other devices, log out of your Steam account from all of them. After that, open the Steam client again and see if you can sign in successfully this time.

 If you don't encounter any errors this time, this confirms that using your account on multiple devices simultaneously caused the error. In the future, always log out of your Steam account before using it on another device. However, if logging out of your account from all other devices makes no difference, move on to the next solution.

## 3\. Reset Your Account Password

 Some users in a [Steam community thread](https://steamcommunity.com/discussions/forum/1/3392923906944531423/) have mentioned that they have successfully fixed this error by simply resetting their password. Therefore, you should also reset your account password. To do that, follow these steps:

1. Go to the [Steam website](https://store.steampowered.com/) .
2. Click on**login** in the top-right corner.  
![Click on the Login Button on Steam Website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/1-click-on-the-login-button-on-steam-website.jpg)
3. Enter your username, and without entering your password (even if you remember it), click on**Help, I can't sign in** .  
![Click on Help I Can’t Sign In Option From the Login Page on Steam Website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/2-click-on-help-i-can-t-sign-in-option-from-the-login-page-on-steam-website.jpg)
4. Then, click on**I forgot my Steam Account name or password** .
5. Enter the email address or phone number linked to your account, verify Captcha, and click on**Search** .  
![Click on Search Button on the Steam Support Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3-click-on-search-button-on-the-steam-support-pag.jpg)
6. By selecting the appropriate option, receive a verification code to your email address or phone number.
7. Verify your identity by clicking the link you receive via email or adding the code you receive by phone.
8. Click on**Reset my password** after that.  
![Click on Reset My Password Option on Steam Website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/4-click-on-reset-my-password-option-on-steam-website.jpg)
9. Then, follow the on-screen instructions to reset your password.

 After changing your password, restart your device once and try to sign in again with the new password. Hopefully, this time you won't encounter any errors. If resetting the account password does not resolve the issue, proceed to the next step.

## 4\. Add or Remove Launch Parameters

 Adding the**"-noreactlogin"** parameter in Steam's executable file can also resolve this issue. In technical terms, adding this flag disables the ReactJS-based login window and restores the old one. Follow these steps to add this extra flag:

1. Right-click on Steam's shortcut icon and select**Properties** .  
![Open Steam Properties in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/5-open-steam-properties-in-windows.jpg)
2. Go to the**Shortcut** tab in the**Steam Properties** window.  
![Go to Shortcut Tab in the Steam Properties Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/6-go-to-shortcut-tab-in-the-steam-properties-window.jpg)
3. To modify the**Target** field, click at its end, add a space, and type**"-noreactlogin** .**"**
4. Click**Apply** and then hit**OK** .  
![Click on OK Button After Adding a Launch Parameter in Steam Properties Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/7-click-on-ok-button-after-adding-a-launch-parameter-in-steam-properties-window.jpg)

 If you see that some launch parameters are already added to the Target field, consider removing them. According to some users on [GitHub](https://github.com/ValveSoftware/steam-for-linux/issues/9031) , Steam no longer supports the**"noreactlogin"** flag and suggests removing it. Remove this flag if it is already there. Taking this step will ensure that this extra parameter is not contributing to the problem.

## 5\. When Nothing Else Works…

 The above fixes should resolve this annoying error. However, if they don't work in your favor, here are a few final fixes you can try.

### Make a New Steam Account and Try Logging In With it

 To confirm that the issue isn't with your Steam account, sign in to Steam using a different account (If you don't have another account, create one). If you successfully log in using the other account, it indicates that your primary account has an issue. So, contact Steam support through their [official Steam Support website](https://help.steampowered.com/en/) and ask them to investigate it.

### Whitelist Steam in All Active Security Apps

 Valve recommends whitelisting Steam's executable files in Windows' built-in or third-party security suites. So, go to Steam's installation folder, filter out all the executable files, and [whitelist them from Windows Defender](https://www.makeuseof.com/how-to-whitelist-files-windows-defender/) or any other third-party antivirus software you use.

## Get Rid of Steam's Error Code 84 on Windows

 Getting an error code 84 means Steam has failed to log you in. Hopefully, the above fixes will help you resolve the main issue and allow you to sign in successfully. Reinstalling the Steam client should be your last resort if nothing else works. Ensure you create a backup of your game files before uninstalling Steam to avoid losing your progress.


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
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-after-switching-from-samsung-galaxy-f34-5g-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data After Switching From Samsung Galaxy F34 5G to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/classic-game-storage-integrating-into-the-windows-photos-space/"><u>Classic Game Storage: Integrating Into the Windows Photos Space</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-surface-laptop-studio-2-the-near-perfect-companion/"><u>Discovering Surface Laptop Studio 2 - The Near-Perfect Companion</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ow-to-captivate-audience-attention-with-your-yt-shorts/"><u>[New] How to Captivate Audience Attention with Your YT Shorts</u></a></li>
<li><a href="https://windows11.techidaily.com/defeating-disk-defenders-sync-soundcard-irq-in-windows/"><u>Defeating Disk Defenders: Sync Soundcard IRQ in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/converting-oculus-quest-2-to-windows-vr-compatibility-level/"><u>Converting Oculus Quest 2 to Windows VR Compatibility Level</u></a></li>
<li><a href="https://windows11.techidaily.com/discreet-toolbar-tactics-concealing-items-in-windows-11/"><u>Discreet Toolbar Tactics: Concealing Items in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-windows-11-security-filters-in-context-menu/"><u>Configuring Windows 11 Security Filters in Context Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/command-the-control-of-windows-accessibility-options/"><u>Command the Control of Windows' Accessibility Options</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/in-2024-ultimate-selection-guide-best-android-movie-makers/"><u>In 2024, Ultimate Selection Guide Best Android Movie Makers</u></a></li>
<li><a href="https://windows11.techidaily.com/command-center-changing-your-onedrive-storage-territory-on-windows-10/"><u>Command Center: Changing Your OneDrive Storage Territory on Windows 10</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-the-roadmap-to-increasing-traffic-top-techniques-for-fb-video-ads/"><u>In 2024, The Roadmap to Increasing Traffic  Top Techniques for FB Video Ads</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-audacitys-internal-portaudio-error-on-w10w11-pcs/"><u>Correcting Audacity's Internal PortAudio Error on W10/W11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/corrective-measures-for-xc0351000-hyprocvisor-not-found/"><u>Corrective Measures for XC0351000: Hyprocvisor Not Found</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-the-art-of-tracking-network-activity-via-netstat-in-win11/"><u>Discover the Art of Tracking Network Activity via Netstat in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/combating-writing-denials-in-windows-11-environment/"><u>Combating Writing Denials in Windows 11 Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/convenient-telnet-setup-for-modern-windows-systems-wins/"><u>Convenient Telnet Setup for Modern Windows Systems (Wins)</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-seamlessly-integrate-text-in-your-tiktok-videos/"><u>In 2024, Seamlessly Integrate Text in Your TikTok Videos</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-the-unsung-heroes-of-canvas-open-source-paintings/"><u>[New] 2024 Approved  The Unsung Heroes of Canvas  Open-Source Paintings</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-chrome-display-glitches-on-pc/"><u>Clearing Chrome Display Glitches on PC</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-boosting-engagement-uploading-and-sharing-on-instagram-desktop/"><u>[Updated] Boosting Engagement  Uploading and Sharing on Instagram Desktop</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-art-of-narrative-on-film/"><u>2024 Approved  The Art of Narrative on Film</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-high-dpi-display-issues-in-windows/"><u>Clearing Up High DPI Display Issues in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-active-directory-printer-problems-a-guide-for-win-10-users/"><u>Dealing with Active Directory Printer Problems: A Guide For WIN 10 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-setting-up-outlook-preview-for-w10w11/"><u>Comprehensive Guide: Setting up Outlook Preview for W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-differences-windows-10-meets-windows-11/"><u>Deciphering the Differences: Windows 10 Meets Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-resolving-directdraw-errors-on-win1011/"><u>Decoding and Resolving DirectDraw Errors on WIN10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-illusions-sketching-secrets-for-windows-users/"><u>Digital Illusions: Sketching Secrets for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-the-unseen-scroll-phenomenon-in-windows/"><u>Conquer the Unseen Scroll Phenomenon in Windows</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-streamlining-presentations-the-art-of-screen-casting-in-discord/"><u>[Updated] Streamlining Presentations  The Art of Screen Casting in Discord</u></a></li>
<li><a href="https://windows11.techidaily.com/de-cluttering-notifications-tips-for-windows-11-users/"><u>De-Cluttering Notifications: Tips for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/command-line-to-admin-initiating-windows-11s-task-manager-with-power/"><u>Command Line to Admin: Initiating Windows 11'S Task Manager with Power</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-windows-process-aggregatorhostexe-use-and-risks/"><u>Deciphering Windows Process AggregatorHost.exe: Use and Risks</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-techniques-for-capturing-high-quality-movies-on-all-os/"><u>[New] 2024 Approved  Techniques for Capturing High-Quality Movies on All OS</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-soundquality-synopsis/"><u>In 2024, SoundQuality Synopsis</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-factory-seal-on-windows-11/"><u>Disabling Factory Seal on Windows 11</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-explore-cost-free-professional-cam-screen-recorders/"><u>In 2024, Explore Cost-Free, Professional Cam Screen Recorders</u></a></li>
<li><a href="https://windows11.techidaily.com/cut-down-clutter-how-to-set-up-autofiledeletion-on-winos/"><u>Cut Down Clutter: How to Set Up AutoFileDeletion on WINOS</u></a></li>
<li><a href="https://windows11.techidaily.com/confronting-windows-security-blunders-with-ease/"><u>Confronting Windows Security Blunders with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-why-many-dismiss-windows-11-now/"><u>Decoding Why Many Dismiss Windows 11 Now</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-expert-review-of-the-leading-no-cost-cam-software-options/"><u>[New] 2024 Approved  Expert Review of the Leading No-Cost Cam Software Options</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-music-from-samsung-galaxy-s23-fe-by-fonelab-android-recover-music/"><u>Easy steps to recover deleted music from Samsung Galaxy S23 FE</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/the-ultimate-guide-to-understanding-and-leveraging-instagrams-reels/"><u>The Ultimate Guide to Understanding and Leveraging Instagram's Reels</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/top-3ips-precision-audio-capture-solutions/"><u>Top 3iP's Precision Audio Capture Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/discerning-the-divergences-between-terminal-and-powershell/"><u>Discerning the Divergences Between Terminal & PowerShell</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-5-solutions-for-xiaomi-redmi-note-13-pro-5g-unlock-without-password-by-drfone-android/"><u>In 2024, 5 Solutions For Xiaomi Redmi Note 13 Pro 5G Unlock Without Password</u></a></li>
<li><a href="https://apple-account.techidaily.com/your-account-has-been-disabled-in-the-app-store-and-itunes-from-iphone-xs-by-drfone-ios/"><u>Your Account Has Been Disabled in the App Store and iTunes From iPhone XS?</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-getting-the-pokemon-go-gps-signal-not-found-11-error-in-oppo-a18-drfone-by-drfone-virtual/"><u>In 2024, Getting the Pokemon Go GPS Signal Not Found 11 Error in Oppo A18 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-windows-11s-data-preservation-capabilities/"><u>Delving Into Windows 11'S Data Preservation Capabilities</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-new-horizons-for-galaxy-users-on-pc/"><u>Discovering New Horizons for Galaxy Users on PC</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/in-2024-solve-your-conversion-woes-how-to-select-a-fast-youtube-to-mp4-converter/"><u>In 2024, Solve Your Conversion Woes How to Select a Fast YouTube to MP4 Converter</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/device-unlock-oppo-f23-5g-by-drfone-android-unlock-android-unlock/"><u>Device unlock  Oppo F23 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-fixing-windows-error-0x800704b3-on-pcslaptops/"><u>Decoding & Fixing Windows Error 0X800704B3 on PCs/Laptops</u></a></li>
<li><a href="https://windows11.techidaily.com/creative-windows-users-heres-the-best-drawing-list/"><u>Creative Windows Users, Here’s the Best Drawing List</u></a></li>
<li><a href="https://windows11.techidaily.com/diminishing-drain-techniques-to-limit-vanguards-user-mode-cpu-use/"><u>Diminishing Drain: Techniques to Limit Vanguard's User-Mode CPU Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-ways-to-tackle-windows-rpc-errors-effectively/"><u>Easy Ways to Tackle Windows RPC Errors Effectively</u></a></li>
</ul></div>
