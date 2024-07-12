---
title: Identifying Programs by Their Launch Shorthand Labels
date: 2024-07-11T21:27:49.973Z
updated: 2024-07-12T21:27:49.973Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Identifying Programs by Their Launch Shorthand Labels
excerpt: This Article Describes Identifying Programs by Their Launch Shorthand Labels
keywords: ShortLabelID,LaunchShorthand,ProgramIDSearch,ShorthandProgramID,LaunchCodeMatching,IdentifyShortLabels,LabelIDIdentification
thumbnail: https://thmb.techidaily.com/227bd0353ed763348ef514468bae7b22e2b22e0109d88910437782328b50ad10.jpg
---

## Identifying Programs by Their Launch Shorthand Labels

 If you're trying to open an app like Microsoft Paint in the Run Dialog and see an error message, it could be caused by your app aliases. But what exactly are App Execution Aliases, where do you find them, and how do you use them?

## What Are App Execution Aliases?

 An alias is an alternative name given to something. The most obvious example is the codename given to a spy or undercover agent. On Windows, aliases have nothing to do with spying. Instead, they are used for streamlining tasks, such as entering commands.

 Windows 10 and 11 both allow aliases to be declared for some apps by default. The available apps vary but are often those commonly associated with command line tools. Giving an app an alias allows it to be executed using a shorter title rather than the full name or path.

 App aliases can be used in several [Windows Command Line Interfaces](https://www.makeuseof.com/what-is-cli-what-does-it-stand-for/) (CLI), including the Run Dialog, Command Prompt, and [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) . If you use these tools with any regularity, app aliases can help to streamline entering commands.

## How to Enable App Execution Aliases in Settings

 You can enable and disable aliases for compatible apps in the main settings in both Windows 10 and 11\. If more than one app uses the same alias name, you can choose which has the alias applied to it.

In Windows 11:

1. Open**Settings > Apps** , and look for**Advanced app settings** .
2. In the advanced app settings, click**App execution aliases** to see the list of compatible apps.
3. Use the slider switches to enable or disable the alias for each app. You can see the alias name below each app.

![app aliases in windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win11.jpg)

In Windows 10:

1. If you're using Windows 10, you'll find the aliases in**Settings > Apps & features** .
2. Click the**App execution aliases** link near the top of the Apps & features page.
3. You can then enable and disable aliases using the switches.

![app aliases in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win10.jpg)

 By default, in both Windows 10 and 11, you can only enable or disable existing app aliases. But if you don't mind editing the Registry, you can create new aliases for many other apps.

## Create App Execution Aliases in Registry Editor

 Before editing or creating registry keys, it is advisable to [create a full backup of the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . Of course, you should also ensure you understand how to restore the Registry from that backup.

 The process below for creating app execution aliases in the Registry Editor should be the same in both Windows 10 and 11.

1. Open**Windows Search** , type**Registry Editor** , and click on the search result to open it.
2. In the editor, navigate to **HKEY\_CURRENT\_USER\\Software\\Microsoft\\Windows\\CurrentVersion\\App Paths** .
3. Next, right-click on the**App Paths** key in the left-hand pane, and select**New > Key** .
4. Give the new key an alias name that relates to the app and ends with .exe. For example, if the alias is for Calendar, call it something like cal.exe.
5. With the alias selected, double-click the**Default** value in the right-hand pane.  
![editing app aliases in registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-regedit.jpg)
6. In the Value data field, you will need to enter the full path to the app executable file. For example**C:\\Program Files (x86)\\Calendar.exe** .
7. Right-click in the right pane and select**New > String value** . Name the string**path** . The change the Value data to the same path as above, but without the app filename.

 You can now close the Registry Editor. The new App Execution Alias will now be available to use in the Windows CLIs.

## Using and Creating App Execution Aliases

 Entering commands into tools such as Command Prompt and PowerShell can be laborious. You can streamline that process by enabling or creating aliases for apps that commonly feature in those commands. Why type out a full path to an executable file when you can point to it with a few keystrokes?


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
<li><a href="https://windows11.techidaily.com/reboot-to-normalcy-windows-11-permissions-reversal/"><u>Reboot to Normalcy: Windows 11 Permissions Reversal</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-the-mystery-recovering-copilot-in-ws11/"><u>Solving the Mystery: Recovering Copilot In WS11</u></a></li>
<li><a href="https://windows11.techidaily.com/rewiring-success-restoring-troubleshooters-in-windows-11/"><u>Rewiring Success: Restoring Troubleshooters in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolve-null-audio-output-on-windows-pcs/"><u>Resolve Null Audio Output on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/proven-strategies-to-enhance-wireless-and-cable-networks-on-windows/"><u>Proven Strategies to Enhance Wireless and Cable Networks on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-microsoft-store-issues-error-code-0x80072f17-fix/"><u>Resolving Microsoft Store Issues: Error Code 0X80072f17 Fix</u></a></li>
<li><a href="https://fox-helps.techidaily.com/reducing-noise-sensitivity-in-logic-pro-mixes/"><u>Reducing Noise Sensitivity in Logic Pro Mixes</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/unlocking-apple-iphone-8-passcode-without-a-computer-by-drfone-ios/"><u>Unlocking Apple iPhone 8 Passcode without a Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-approach-for-removing-steams-dns-information/"><u>Stepwise Approach for Removing Steam's DNS Information</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-deal-with-the-itel-s23-screen-black-but-still-works-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Deal With the Itel S23 Screen Black But Still Works? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-eradicate-0x80072af9-on-windows/"><u>Steps to Eradicate 0X80072AF9 on Windows</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-dive-into-vlogging-easy-content-projects-for-2024/"><u>[New] Dive Into Vlogging  Easy Content Projects for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-spectrumstreams-2024-worldwide-selection-at-fingertips/"><u>[New] SpectrumStreams 2024  Worldwide Selection at Fingertips</u></a></li>
<li><a href="https://windows11.techidaily.com/staying-current-the-impact-of-additional-yearly-patches-on-your-pc/"><u>Staying Current: The Impact of Additional Yearly Patches on Your PC</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-secure-your-visuals-the-most-efficient-face-masking-apps/"><u>In 2024, Secure Your Visuals  The Most Efficient Face-Masking Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-glances-to-your-favorites-windows-shortcuts-uwp-apps/"><u>Quick Glances to Your Favorites: Windows Shortcuts (UWP Apps)</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-overcome-onedrive-authentication-xyz-error-on-windows-11/"><u>Steps to Overcome ONEDRIVE Authentication XYZ Error on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-win11-upgrades-eradicate-error-0xc1900101/"><u>Streamline Your Win11 Upgrades, Eradicate Error 0xC1900101</u></a></li>
<li><a href="https://windows11.techidaily.com/revival-rituals-for-lost-windows-unlocking-off-screen-restoration-in-win-1011-6-essentials/"><u>Revival Rituals for Lost Windows: Unlocking Off-Screen Restoration in Win 10/11 (6 Essentials)</u></a></li>
<li><a href="https://fix-guide.techidaily.com/simple-solutions-to-fix-android-systemui-has-stopped-error-for-vivo-s17e-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Simple Solutions to Fix Android SystemUI Has Stopped Error For Vivo S17e | Dr.fone</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ing-channels-earning-dollars-a-beginners-guide-for-2024/"><u>Creating Channels, Earning Dollars  A Beginner's Guide for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-captivating-channels-spotlight-on-the-most-popular-female-creators/"><u>2024 Approved  Captivating Channels  Spotlight on the Most Popular Female Creators</u></a></li>
<li><a href="https://android-unlock.techidaily.com/10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-lenovo-by-drfone-android/"><u>10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Lenovo</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-perfecting-your-shoot-selecting-quality-equipment/"><u>2024 Approved  Perfecting Your Shoot  Selecting Quality Equipment</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-busting-vlogger-shakiness-leading-camera-stabilizer-brands/"><u>2024 Approved  Busting Vlogger Shakiness  Leading Camera Stabilizer Brands</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-do-you-get-sun-stone-evolutions-in-pokemon-for-vivo-v30-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How Do You Get Sun Stone Evolutions in Pokémon For Vivo V30 Pro? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-restore-playback-from-black-screen/"><u>Steps to Restore Playback From Black Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/resurrect-your-pcs-absent-controllers/"><u>Resurrect Your PC's Absent Controllers</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-move-contacts-from-tecno-spark-20c-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Move Contacts From Tecno Spark 20C to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-recover-windows-audio-glitches/"><u>Steps to Recover Windows Audio Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-saving-your-personalized-powertoys-profile/"><u>Steps for Saving Your Personalized PowerToys Profile</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/enhance-visibility-top-9-thumbnail-design-tools-for-creators/"><u>Enhance Visibility  Top 9 Thumbnail Design Tools for Creators</u></a></li>
<li><a href="https://windows11.techidaily.com/resurrecting-lost-wi-fi-link-windows-edition/"><u>Resurrecting Lost Wi-Fi Link: Windows Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-windows-backup-to-original-settings/"><u>Restoring Windows Backup to Original Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-unravel-exception-reached-on-windows-pcs/"><u>Steps to Unravel 'Exception Reached' On Windows PCs</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-m1-pro-vs-m1-max-examining-the-advancements-in-apples-cpu-technology/"><u>In 2024, M1 Pro Vs. M1 Max  Examining the Advancements in Apple's CPU Technology</u></a></li>
</ul></div>
