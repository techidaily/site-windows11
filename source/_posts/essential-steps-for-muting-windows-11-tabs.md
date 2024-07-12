---
title: Essential Steps for Muting Windows 11 Tabs
date: 2024-07-11T21:21:16.354Z
updated: 2024-07-12T21:21:16.354Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Essential Steps for Muting Windows 11 Tabs
excerpt: This Article Describes Essential Steps for Muting Windows 11 Tabs
keywords: Mute Win11 Tabs,Silence Windows XTABs,Tab Muting in Win11,Windows Tabs Quieten,Stop Tab Noise Win11,Hush Windows Tabding,Shutdown Windows Tabs
thumbnail: https://thmb.techidaily.com/65300c988d41879c46efcdc0b8a7f4ebdd53e06feae865a9a356c9f8b695aec3.jpg
---

## Essential Steps for Muting Windows 11 Tabs

 Microsoft was hoping to launch the tabs feature in the File Explorer app for Windows 10\. But it scrapped the idea later on. However, with the Windows 11 22H2 update, users can now try out the tabs feature in File Explorer. The participants of the Windows Insider Program got early access to the feature and Microsoft could soon apply the tabs idea to Windows Notepad as well.

 But what if you want to turn the File Explorer Tabs feature off? An immediate idea would be to uninstall the update, but that is a temporary workaround. You can use ViVeTool to enable or disable the tabs feature or any other new feature of Windows 11.

## What Is ViVeTool?

 ViVeTool is an open-source command line tool that can enable or disable Windows operating system features. Microsoft continuously works on many experimental features and does a lot of testing before rolling out a stable version of a feature. But if you are impatient, you can use ViVeTool to enable an otherwise hidden feature. It is free and the developers recently launched a GUI version of the tool as well.

## How to Disable File Explorer Tabs In Windows 11

 You can disable the File Explorer Tabs by either using the ViVeTool or the ViVeTool GUI version. The latter is much simpler to use because you can search for a feature and activate or deactivate it in one click. But before doing that, download and install both of these tools on your system. Also,[create a system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) for added precaution, in case the tool wrecks something on your Windows 11 computer.

**Download:** [ViVeTool](https://github.com/thebookisclosed/ViVe/releases)

**Download:** [ViVeTool GUI](https://github.com/PeterStrick/ViVeTool-GUI/releases)

### 1\. Disable File Explorer Tabs Using the ViVeTool

 Since it is a command line tool, you can access it from a terminal window. Here’s how to do it:

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**CMD** in the text input area and press**Ctrl + Shift + Enter** key to launch the command prompt with administrator privileges.
3. Type**cd Drive Name:\\path** . Here, you need to enter the exact location where you extracted the tool after downloading it. For example, we extracted it to a folder name Vive in C drive. So, our command is**cd C:\\Vive** .
4. Now, you will be in the directory where ViVeTool exists. Type**vivetool** and press the**Enter** key. You will see a bunch of parameters you can use with the tool.  
![Disable File Explorer Tabs Using the ViVeTool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool.jpg)
5. Type the following two commands, one by one in the CMD and press the**Enter** key.  
vivetool /disable /id:37634385  
vivetool /disable /id:36354489
6. You will see the “**Successfully set feature configuration(s)** ” if the command executes successfully.
7. Now,**restart** your system for the changes to take effect. The File Explorer Tabs feature will no longer be active on your system.

### 2\. Disable File Explorer Tabs Using the ViVeTool GUI version

 The GUI version of ViVeTool works similarly. You can manually enter the feature ID or use the search function to find a feature in the list. Repeat the following steps to disable File Explorer Tabs using the ViVeTool GUI.

1. Launch the ViVeTool GUI with admin privileges.
2. Click on the drop-down list and select the latest Windows build number. Wait for the tool to list all the feature IDs available for the Windows build.
3. Type**37634385** in the search bar. Select the highlighted feature and click on the**Perform Action** button.  
![Disable File Explorer Tabs Using the ViVeTool GUI version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool-gui-version.jpg)
4. Select the**Deactivate Feature** option. Similarly, find the feature ID**36354489** and deactivate it.
5. Now, close the ViVeTool GUI and**restart** your system.
6. Open the File Explorer and you won’t see the tabs feature anymore.

## Disable Any Windows 11 Feature Using ViVeTool

 File Explorer tabs are more useful than you think. But if you use another File Explorer program or can make do without it, ViVeTool is a great utility to disable/enable it. Moreover, it is completely free, and you can even enable other experimental features of Windows 11.


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
<li><a href="https://some-techniques.techidaily.com/in-2024-how-to-create-unique-ringtone-experiences-on-iphone/"><u>In 2024, How to Create Unique Ringtone Experiences on iPhone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-capturing-win10-games-a-comprehensive-breakdown-for-2024/"><u>[New] Capturing Win10 Games  A Comprehensive Breakdown for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-windows-crash-0x800f0831-solution/"><u>Mastery Over Windows Crash: 0X800f0831 Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-firmware-enhancement-for-surface-devices/"><u>Seamless Firmware Enhancement for Surface Devices</u></a></li>
<li><a href="https://android-location-track.techidaily.com/two-ways-to-track-my-boyfriends-motorola-moto-g73-5g-without-him-knowing-drfone-by-drfone-virtual-android/"><u>Two Ways to Track My Boyfriends Motorola Moto G73 5G without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-user-not-valid-windows-1111-errors/"><u>Navigating Through 'User Not Valid' Windows 11/11 Errors</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-tiktok-to-see-more-content-on-your-poco-x6-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location on TikTok to See More Content On your Poco X6 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-directdraw-woes-a-users-survival-manual-for-win11/"><u>Navigating DirectDraw Woes: A User's Survival Manual for Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-software-management-using-the-windows-package-manager-wpm/"><u>Optimizing Software Management Using the Windows Package Manager (WPM)</u></a></li>
<li><a href="https://windows11.techidaily.com/revamp-desktop-by-removing-windows-11s-highlighted-icon/"><u>Revamp Desktop by Removing Windows 11'S Highlighted Icon</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-google-chrome-to-full-color-in-windows/"><u>Restoring Google Chrome to Full Color in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-access-steps-for-unlocking-windows-hidden-char-personality-tracker/"><u>Mastering Access: Steps for Unlocking Windows' Hidden Char Personality Tracker</u></a></li>
<li><a href="https://some-tips.techidaily.com/synchronizing-melodies-with-inshot-clips-for-2024/"><u>Synchronizing Melodies with InShot Clips for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-easy-guide-how-to-bypass-xiaomi-redmi-k70-pro-frp-android-10111213-by-drfone-android/"><u>In 2024, Easy Guide How To Bypass Xiaomi Redmi K70 Pro FRP Android 10/11/12/13</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-make-cartoon-characters-from-photos-for-2024/"><u>Updated Make Cartoon Characters From Photos for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/monitoring-for-failed-windows-logins-a-security-checkers-guide/"><u>Monitoring for Failed Windows Logins: A Security Checker's Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/keeping-your-win11-devices-running-smoothly-check-list-5/"><u>Keeping Your Win11 Devices Running Smoothly - Check List #5</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionize-your-pc-clear-tpm-from-windows-11/"><u>Revolutionize Your PC: Clear TPM From Windows 11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-writers-guide-to-dialogic-depth-in-screenplays/"><u>2024 Approved  The Writers' Guide to Dialogic Depth in Screenplays</u></a></li>
<li><a href="https://windows11.techidaily.com/process-to-undo-system-image-fault-0x80780119/"><u>Process to Undo System Image Fault: 0X80780119</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/instantly-accessorizing-ios-and-android-with-whatsapp-ringtones-for-2024/"><u>Instantly Accessorizing iOS and Android with WhatsApp Ringtones for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/overriding-default-no-notify-camera-behavior-in-ws11/"><u>Overriding Default No-Notify Camera Behavior in WS11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-ultimate-unboxing-logitechs-professional-4k-pro-webcam/"><u>In 2024, Ultimate Unboxing  Logitech's Professional 4K Pro Webcam</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-from-pixels-to-perfection-finding-the-ideal-picture-ratio/"><u>Updated 2024 Approved From Pixels to Perfection Finding the Ideal Picture Ratio</u></a></li>
<li><a href="https://windows11.techidaily.com/rapidly-access-apps-on-windows-11/"><u>Rapidly Access Apps on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/localize-onedrive-a-step-by-step-windows-approach/"><u>Localize OneDrive: A Step-by-Step Windows Approach</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-imovie-not-available-on-windows-try-these-top-alternatives/"><u>2024 Approved IMovie Not Available on Windows? Try These Top Alternatives</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-cr2-to-jpg-conversion-using-windows-tools/"><u>Mastering the Art of CR2 to JPG Conversion Using Windows Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/step-into-safety-with-windows-canary-channel-feature/"><u>Step Into Safety with Windows' Canary Channel Feature</u></a></li>
<li><a href="https://extra-tips.techidaily.com/excellence-in-ai-based-photo-transformations/"><u>Excellence in AI-Based Photo Transformations</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-jumpstart-your-snapchat-learn-to-create-top-boomers/"><u>[Updated] Jumpstart Your Snapchat  Learn to Create Top Boomers</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-straightforward-approach-turn-video-upside-down-with-vlc/"><u>[New] Straightforward Approach  Turn Video Upside Down with VLC</u></a></li>
<li><a href="https://windows11.techidaily.com/precise-strategies-resetting-razers-system-integration/"><u>Precise Strategies: Resetting Razer's System Integration</u></a></li>
<li><a href="https://extra-tips.techidaily.com/premium-picks-for-the-ultimate-gopro-experience/"><u>Premium Picks for the Ultimate Gopro Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/peek-inside-windows-determining-your-computers-manufacturer/"><u>Peek Inside Windows: Determining Your Computer's Manufacturer</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-network-failure-0x800704b3-in-windows-1011/"><u>Overcoming Network Failure 0X800704B3 in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-rpc-errors-on-windows-os/"><u>Quick Fixes for RPC Errors on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-shadowrunners-speed-up-your-bf2-experience/"><u>Seamless Shadowrunners: Speed up Your BF2 Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-win1011-network-failure-code-0x800704b3/"><u>Resolving Win10/11 Network Failure: Code 0X800704B3</u></a></li>
<li><a href="https://howto.techidaily.com/fix-unfortunately-settings-has-stopped-on-lava-blaze-2-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Unfortunately Settings Has Stopped on Lava Blaze 2 Quickly | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/reconnecting-mic-during-windows-powerpoint-screencast/"><u>Reconnecting Mic During Windows PowerPoint Screencast</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-imaginary-device-issue-in-win-11-os/"><u>Resolving Imaginary Device Issue in Win 11 OS</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-tackling-windows-files-swiftly-and-smartly/"><u>[New] Tackling Windows Files Swiftly and Smartly</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-unveiling-the-numbers-comprehensive-guide-to-count-views-clicks-and-cash-in-youtube/"><u>2024 Approved  Unveiling the Numbers  Comprehensive Guide to Count Views, Clicks, and Cash in YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/revitalizing-your-stalled-windows-11-mobile-network-connection/"><u>Revitalizing Your Stalled Windows 11 Mobile Network Connection</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-ultimate-guide-to-beauty-on-youtube-gear-makeup-tutorials-and-more/"><u>[New] Ultimate Guide to Beauty on YouTube - Gear, Makeup Tutorials, and More</u></a></li>
</ul></div>
