---
title: Can't Choose a Drive to Install Games on the Xbox App for Windows? Try These Fixes
date: 2024-07-03T11:14:30.254Z
updated: 2024-07-04T11:14:30.254Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Can't Choose a Drive to Install Games on the Xbox App for Windows? Try These Fixes
excerpt: This Article Describes Can't Choose a Drive to Install Games on the Xbox App for Windows? Try These Fixes
keywords: Xbox Game Installation Guide,Xbox App Error Resolution,Windows Gaming Setup Tips,Fixed Game Drive Issue Xbox,Xbox App Driver Fix,Games Install on Xbox PC,Troubleshooting Xbox App
thumbnail: https://thmb.techidaily.com/a926f3585163fc206a043d86defc31e04aa0b8209e0df21f919437f2401fbd1a.jpg
---

## Can't Choose a Drive to Install Games on the Xbox App for Windows? Try These Fixes

 The Xbox app lets you purchase and install games on any of your system drives. Usually, this process works well, but sometimes, the Xbox app won't let you install games in any location other than the default directory. This can be problematic, especially when you want to install a big-size game, but the default directory doesn't have enough space.

 Such situations usually arise due to corruption in the Xbox app or misconfigured registry settings. Fortunately, it's very easy to troubleshoot this problem. Here are some fixes to try when you can't choose a drive to install games on the Xbox app.

## 1\. Restart the Computer

![Restart option in Power menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/restart.jpg)

 You might fail to change the installation drive in the Xbox app due to a temporary system glitch or bug. Luckily, you can quickly eliminate such bugs and glitches by restarting your computer.

 To restart, press the**Alt + F4** hotkeys to open the Shut Down Windows prompt, click the drop-down icon, choose**Restart** from the context menu, and then click**OK.** After restart, launch the Xbox app and check if you can choose a different drive to install games. If not, then it's time to dive into the advanced troubleshooting methods.

## 2\. Change the Installation Directory in the Xbox App Settings

 There are two places from where you can change the installation drive on the Xbox app. One is while installing the game, whereas the other is the Xbox settings menu.

 If the first method is not working, you can use the second method to change the installation drive in the Xbox app. So, here's how to edit the Xbox app settings to change its default download location.

1. Launch the Xbox app, click on your profile in the top left corner, and choose**Settings** from the context menu.
2. Choose**General** from the left sidebar.
3. Click the**Change folder** option under**Change where this app installs games by default** .  
![Change Folder in Xbox app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/change-folder.jpg)
4. Choose the location where you want to install the game and then click the**Select Folder** option.

## 3\. Customize the System Settings

 If editing the Xbox app settings wasn't helpful, you can edit the system settings and check if it makes a difference. Here's what you need to do:

1. Press the**Win + I** hotkeys to open the**Settings app.**
2. Choose**System** from the left sidebar and then click on the**Storage** option in the right pane.
3. Click the drop-down icon next to**Advanced storage settings** and choose**Where new content** **is saved** option from the context menu.  
![Where new content is saved option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/where-new-content-is-saved.png)
4. Click the drop-down icon under the**New** **apps** **will save to** section, choose the drive where you want to install the game, and then click**Apply.**  
![New apps will save to section in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/new-apps-will-save-to-section.jpg)

 That's it! Restart your computer and check if the problem continues.

## 4\. Restart Important Xbox Services

![Restart Service option in Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/restart-service.jpg)

 There are certain Xbox services that must be running for you to use the Xbox app properly. If any of these services fail to start properly, you might face the problem at hand.

 To fix that, restart each service manually. Here's how to do that:

1. Open the Run dialog box by pressing the**Win + R** hotkeys.
2. Type**services.msc** in the search bar and click OK.
3. In the Services window, locate and right-click on the following services and choose**Restart** from the context menu.  
`Xbox Accessory Management  
Xbox Live Game Save  
Xbox Live Auth Manager  
Xbox Live Networking Service`

## 5\. Reinstall the Gaming Services App

 The Gaming Services app allows you to seamlessly download apps and games from the Microsoft Store and the Xbox app. But if the app gets corrupt, you might face various issues, including the one in question.

 The solution, in this case, is to reinstall the Gaming Services app on your computer. You can do that by following the below instructions:

 Editing the registry can be dangerous, as one wrong edit can make your system unstable. To ensure that your data is secure even if something goes wrong,[back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

1. Open the Run dialog box, type**regedit,** and click OK.
2. In the Registry Editor, navigate to the below location:  
`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services`
3. Right-click on the**GamingServices** folder in the left sidebar and choose**Delete** from the context menu.  
![Delete option in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/delete-option.jpg)
4. Click**Yes** to confirm your selection.
5. Next, delete the**GamingServicesNet** folder as well in the left sidebar.

 Now, open the elevated PowerShell window (see how to [open Windows PowerShell as an administrator](https://www.makeuseof.com/windows-powershell-always-open-as-administrator/) ), type the following command, and press**Enter** .

`Get-AppxPackage *gamingservices* -allusers | remove-appxpackage -allusers`

![Remove Gaming Services command in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/remove-gaming-services.jpg)

 After uninstalling the Gaming Services app, restart your computer. Then, open the Microsoft Store, search for and [download the Gaming Services](https://apps.microsoft.com/store/detail/gaming-services/9MWPM2CQNLHN?hl=en-us&gl=us) app again.

## 6\. Repair the Xbox App

 It's very common for the Xbox app to get corrupt and throw various issues. The best way to remove corruption from the UWP apps like the Xbox app is to use the Windows repair feature.

 Check out [how to repair apps and programs on Windows](https://www.makeuseof.com/windows-repair-apps-programs/) for information on how to do this.

## 7\. Update the Xbox App

 If repairing the Xbox app doesn't remove the corruption, consider updating the app. Downloading the latest update of the Xbox app will not only remove the corruption but also introduce new features.

To update the Xbox app, follow the below steps:

1. Open the Microsoft Store and click the**Library** option in the left sidebar.
2. Click the**Get updates** button to allow the Microsoft Store to search for available updates of the installed apps.

 The Microsoft Store will now automatically download updates for installed apps, including the Xbox app.

 While you're at installing updates, we'd also recommend [downloading any available Windows updates](https://www.makeuseof.com/tag/update-windows-software-guide/) . To do so, launch the Settings app, choose**Windows Update** from the left sidebar, and then click the**Check for Updates** button to install any available update on your computer. Following this, you will be able to choose a drive to install games on the Xbox app.

## Change the Download Location of the Xbox App

 The Xbox app is a great place to download your favorite games. However, the app might fail to change the installation location of games. Fortunately, you can quickly eliminate this issue by following the above fixes.

 Meanwhile, you might be interested to know how to increase downloading speed of the Xbox app.


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
<li><a href="https://windows11.techidaily.com/notepaddarksettingsinstructionswin1011/"><u>NotepadDarkSettingsInstructionsWin10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-to-prevent-not-working-on-your-pc/"><u>Swift Solutions to Prevent 'Not Working' On Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/syncing-sound-levels-across-windows-and-bt-audio-gear/"><u>Syncing Sound Levels Across Windows and BT Audio Gear</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-list-of-windows-11-navshortcuts/"><u>The Ultimate List of Windows 11 NavShortcuts</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-full-potential-of-the-windows-11-taskbar/"><u>Unlock the Full Potential of the Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-common-errors-in-microsoft-office-activation/"><u>Overcoming Common Errors in Microsoft Office Activation</u></a></li>
<li><a href="https://windows11.techidaily.com/initiating-contact-accessing-windows-printer-administration-tools/"><u>Initiating Contact: Accessing Windows' Printer Administration Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-rectify-microsoft-store-error-0x80072f30-on-pcs/"><u>Steps to Rectify Microsoft Store Error 0X80072F30 on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-and-remedying-chromes-profile-anomalies/"><u>Unraveling and Remedying Chrome's Profile Anomalies</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-se-to-other-iphone-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone SE To Other iPhone? | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-best-free-video-cutters-and-joiners-for-beginners/"><u>Updated Best Free Video Cutters and Joiners for Beginners</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-ultimate-resource-compendium-for-optimizing-on-screen-captioning/"><u>In 2024, The Ultimate Resource Compendium for Optimizing On-Screen Captioning</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-top-ten-applications-that-alter-male-vocalizations-into-a-feminine-hue-for-2024/"><u>New Top Ten Applications That Alter Male Vocalizations Into a Feminine Hue for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-defining-the-basics-the-art-of-digital-stories/"><u>[Updated] Defining the Basics  The Art of Digital Stories</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-eliminating-sound-techniques-to-remove-background-noise-from-video-on-pc-and-mac/"><u>2024 Approved Eliminating Sound Techniques to Remove Background Noise From Video on PC & MAC</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-elevating-your-content-with-instagram-videos/"><u>In 2024, Elevating Your Content with Instagram Videos</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-5-steps-to-transform-your-photos-hues-right-away/"><u>In 2024, 5 Steps to Transform Your Photo's Hues Right Away</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/what-does-jailbreaking-iphone-15-i-do-get-answers-here-drfone-by-drfone-ios/"><u>What Does Jailbreaking iPhone 15 i Do? Get Answers here | Dr.fone</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-in-2024-from-screen-to-video-how-to-record-your-desktop-with-filmora-scrn/"><u>New In 2024, From Screen to Video How to Record Your Desktop with Filmora Scrn</u></a></li>
</ul></div>
