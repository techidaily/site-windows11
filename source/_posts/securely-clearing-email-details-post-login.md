---
title: Securely Clearing Email Details Post-Login
date: 2024-07-11T21:22:58.943Z
updated: 2024-07-12T21:22:58.943Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Securely Clearing Email Details Post-Login
excerpt: This Article Describes Securely Clearing Email Details Post-Login
keywords: Login Data Wipe,Password Cleared,Secure Logout,Mail Privacy,Email Cleanup,Safe Signoff,Remove Email Info
thumbnail: https://thmb.techidaily.com/5c5beff306decd9e31c3216a57ffb320c5012e1719fd0426ca459ec8dc06e9a5.jpg
---

## Securely Clearing Email Details Post-Login

 If you frequently use your computer in public places, it's a good idea to remove your email address from the Windows login screen. This means people can't get your email address if they see your screen over your shoulder.

 You can accomplish this using the Settings app, Group Policy Editor, or Registry Editor. In this post, we've covered all these methods in detail.

## 1\. How to Hide Email Address From Windows Login Screen Using the Settings App

 The Windows Settings app provides a quick way to hide account information from the login screen. So, if you are in a rush, use the following steps to remove user email addresses from the Windows login screen.

1. Press**Win + I** or use one of the [many ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Accounts > Sign-in options** .
3. Under**Additional settings** , toggle off the switch next to **Show account details such as my email address on the sign-in screen** .  
![Hide Email From Windows Login Screen Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-settings-app.jpg)

## 2\. How to Hide Email Address From Windows Login Screen Using the Group Policy Editor

 The Group Policy Editor (or gpedit.msc) is a handy Windows tool for configuring advanced system settings. You can also this tool to hide your email address from the Windows login screen.

 Note that the Group Policy Editor is only available on Windows Professional, Education, and Enterprise editions. If your PC is running Windows Home, check out [how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

1. Press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the search box and select the first result that appears.
3. Use the left pane to navigate to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options** .
4. Double-click the **Interactive Logon: Display user information when the session is locked** policy on your right.
5. In the properties window, click the drop-down menu to select the**Do not display user information** option.
6. Click**Apply** followed by**OK** .  
![Hide Email From Windows Login Screen Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-group-policy-editor.jpg)
7. Next, double-click on the**Interactive logon: Do not display last user name** policy from the same section.
8. Select**Enabled** in the properties window.
9. Click**Apply** followed by**OK** to save changes.

## 3\. How to Hide Email Address From Windows Login Screen Using the Registry Editor

 If the above two methods don’t work for some reason, you can make changes to the Windows registry files to hide your email address from the login screen. For that, you’ll need to use the Registry Editor on Windows.

 When it comes to editing Registry files, it's important to be cautious as making incorrect changes can cause irreversible damage to your PC. We recommend you either back up all the registry files or create a restore point before you make any changes. If you need help with that, check our guides on [how to back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [how to create a restore point in Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

 Once you’re done with that, use the following steps to hide your email address from the Windows login screen via Registry Editor.

1. Press**Win + X** to open the Power User menu and select**Run** from the list.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows > System** .
5. Right-click on the**System** key and select**New > DWORD (32-bit) Value** .
6. Rename the DWORD to**BlockUserFromShowingAccountDetailsOnSignin** .
7. Double-click on the newly created DWORD and enter**1** in the**Value data** field. Then, click**OK** .  
![Hide Email From Windows Login Screen Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-registry-editor.jpg)

 Exit the Registry Editor and restart your PC for the changes to take effect.

## Hiding Your Email Address From the Windows Login Screen Is Easy

 As we just saw, hiding your personal information from the Windows login screen barely takes a couple of minutes, regardless of the method you employ.


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
<li><a href="https://windows11.techidaily.com/steps-to-restore-playback-from-black-screen/"><u>Steps to Restore Playback From Black Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-the-mystery-recovering-copilot-in-ws11/"><u>Solving the Mystery: Recovering Copilot In WS11</u></a></li>
<li><a href="https://windows11.techidaily.com/strip-onedrive-of-microsoft-id-integration-in-windows/"><u>Strip OneDrive of Microsoft ID Integration in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/proven-strategies-to-enhance-wireless-and-cable-networks-on-windows/"><u>Proven Strategies to Enhance Wireless and Cable Networks on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resurrect-your-pcs-absent-controllers/"><u>Resurrect Your PC's Absent Controllers</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-echo-of-valyria-prime-destinations-for-tts-downloads-for-2024/"><u>The Echo of Valyria  Prime Destinations for TTS Downloads for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-unravel-exception-reached-on-windows-pcs/"><u>Steps to Unravel 'Exception Reached' On Windows PCs</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-10plus-best-free-online-video-trimmers-to-edit-videos-quickly/"><u>Updated 10+ Best Free Online Video Trimmers to Edit Videos Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/install-and-enhance-edge-security-with-the-defender-application-guard-from-ms/"><u>Install and Enhance Edge Security with the Defender Application Guard From MS</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-eradicate-0x80072af9-on-windows/"><u>Steps to Eradicate 0X80072AF9 on Windows</u></a></li>
<li><a href="https://extra-resources.techidaily.com/satirical-space-the-ultimate-guide-to-20plus-humorous-metaverse-imagery/"><u>Satirical Space  The Ultimate Guide to 20+ Humorous Metaverse Imagery</u></a></li>
<li><a href="https://windows11.techidaily.com/staying-current-the-impact-of-additional-yearly-patches-on-your-pc/"><u>Staying Current: The Impact of Additional Yearly Patches on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-overcome-onedrive-authentication-xyz-error-on-windows-11/"><u>Steps to Overcome ONEDRIVE Authentication XYZ Error on Windows 11</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-what-is-ai-generated-text/"><u>New What Is AI Generated Text?</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-preventing-google-chromes-autopilot-tabs/"><u>Guide to Preventing Google Chrome's Autopilot Tabs</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-windows-backup-to-original-settings/"><u>Restoring Windows Backup to Original Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-win11-upgrades-eradicate-error-0xc1900101/"><u>Streamline Your Win11 Upgrades, Eradicate Error 0xC1900101</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-past-onedrive-sign-in-snags-with-windows-steps/"><u>Navigate Past OneDrive Sign-In Snags with Windows Steps</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/comprehensive-solution-for-partially-muted-fb-video-tracks-for-2024/"><u>Comprehensive Solution for Partially Muted FB Video Tracks for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-microsoft-store-issues-error-code-0x80072f17-fix/"><u>Resolving Microsoft Store Issues: Error Code 0X80072f17 Fix</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-saving-your-personalized-powertoys-profile/"><u>Steps for Saving Your Personalized PowerToys Profile</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-0xc0000142-problems-on-win11win7/"><u>Overcoming 0XC0000142 Problems on Win11/Win7</u></a></li>
<li><a href="https://windows11.techidaily.com/rewiring-success-restoring-troubleshooters-in-windows-11/"><u>Rewiring Success: Restoring Troubleshooters in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-spotify-link-reset-strategies/"><u>Mastering Windows Spotify Link Reset Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/resurrecting-lost-wi-fi-link-windows-edition/"><u>Resurrecting Lost Wi-Fi Link: Windows Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/reboot-to-normalcy-windows-11-permissions-reversal/"><u>Reboot to Normalcy: Windows 11 Permissions Reversal</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-windows-unlocking-diskusage-insights-for-storage-management/"><u>Maximizing Windows: Unlocking DiskUsage Insights for Storage Management</u></a></li>
<li><a href="https://windows11.techidaily.com/revival-rituals-for-lost-windows-unlocking-off-screen-restoration-in-win-1011-6-essentials/"><u>Revival Rituals for Lost Windows: Unlocking Off-Screen Restoration in Win 10/11 (6 Essentials)</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-11s-0x8007045d-bluescreen-troubleshooting/"><u>Navigating Through Windows 11'S 0X8007045D Bluescreen Troubleshooting</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-approach-for-removing-steams-dns-information/"><u>Stepwise Approach for Removing Steam's DNS Information</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-glances-to-your-favorites-windows-shortcuts-uwp-apps/"><u>Quick Glances to Your Favorites: Windows Shortcuts (UWP Apps)</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-microsoft-store-eliminating-code-x80072f30-errors/"><u>Mastering the Microsoft Store: Eliminating Code X80072F30 Errors</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-blueprint-for-buzzing-outro/"><u>In 2024, Blueprint for Buzzing Outro</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-streamlining-social-media-posts-with-srt-file-integration-tips/"><u>In 2024, Streamlining Social Media Posts with SRT File Integration Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-browsing-security-with-win-11-ms-defender-guard/"><u>Optimize Browsing Security with Win 11 MS Defender Guard</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-to-rectify-opengl-error-3-in-win11-pcs/"><u>Swift Solutions to Rectify OpenGL Error #3 in Win11 PCs</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-top-15-online-haven-for-your-favorite-ringtone-files/"><u>In 2024, Top 15 Online Haven for Your Favorite Ringtone Files</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-recover-windows-audio-glitches/"><u>Steps to Recover Windows Audio Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/identify-and-solve-hidden-disk-space-problems-in-windows/"><u>Identify & Solve Hidden Disk Space Problems in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/microsofts-profit-mechanisms-in-windows-11/"><u>Microsoft's Profit Mechanisms in Windows 11</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-techniques-to-halt-video-ad-interruptions-on-social-media/"><u>[New] Techniques to Halt Video Ad Interruptions on Social Media</u></a></li>
<li><a href="https://windows11.techidaily.com/sweep-away-unrecognized-interfaces-with-these-tips/"><u>Sweep Away Unrecognized Interfaces with These Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/resolve-null-audio-output-on-windows-pcs/"><u>Resolve Null Audio Output on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-and-secure-file-saving-ultimate-remedies-in-windows-11/"><u>Swift and Secure File Saving: Ultimate Remedies in Windows 11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-directrecorderw11-streamlined-windows-11-capture-software/"><u>[New] In 2024, DirectRecorderW11  Streamlined Windows 11 Capture Software</u></a></li>
</ul></div>
