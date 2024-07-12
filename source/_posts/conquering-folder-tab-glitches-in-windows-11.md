---
title: Conquering Folder Tab Glitches in Windows 11
date: 2024-07-11T22:24:17.710Z
updated: 2024-07-12T22:24:17.710Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Conquering Folder Tab Glitches in Windows 11
excerpt: This Article Describes Conquering Folder Tab Glitches in Windows 11
keywords: Fix Folder Glitch Win11,Solve File Errors Win11,Unlock Folder Issues Windows11,Address Tab Bug in Win11,Overcome Folders Malfunction Windows,Tackle Directory Freeze 11,Eliminate Glitches Win11 Filesystem
thumbnail: https://thmb.techidaily.com/104fcc0c1e7ba0020bac11684b73c47c97661f3e4742e08d1374a286a48bed4c.jpg
---

## Conquering Folder Tab Glitches in Windows 11

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
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-perfect-your-igtv-shooting-skills-tips-for-smartphonedslr-cameras/"><u>[New] In 2024, Perfect Your IGTV Shooting Skills  Tips for Smartphone/DSLR Cameras</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-updates-fault-0x8019/"><u>Clearing Updates Fault 0X8019</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-the-top-video-animation-tools-for-creating-stunning-animations-on-the-go/"><u>Updated In 2024, The Top Video Animation Tools for Creating Stunning Animations On-the-Go</u></a></li>
<li><a href="https://windows11.techidaily.com/conjoining-android-and-windows-11-tablets-effortlessly/"><u>Conjoining Android and Windows 11 Tablets Effortlessly</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-non-selectable-items-in-win11-setup/"><u>Dealing with Non-Selectable Items in Win11 Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-win-errors-post-bsod-on-modern-oses/"><u>Deciphering Win Errors Post-BSOD on Modern OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/correct-windows-11s-no-error-zero-error-flaw-quickly/"><u>Correct Windows 11'S No Error, Zero-Error Flaw Quickly</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-how-to-add-3d-effects-to-video-in-windows-computer-for-2024/"><u>New How to Add 3D Effects to Video in Windows Computer for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/disable-windows-11s-covert-surveillance/"><u>Disable Windows 11'S Covert Surveillance</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-your-clock-region-on-windows-avoiding-automatic-changes/"><u>Customize Your Clock Region on Windows, Avoiding Automatic Changes</u></a></li>
<li><a href="https://windows11.techidaily.com/ditch-default-home-port-on-w11-settings-interface/"><u>Ditch Default Home Port on W11 Settings Interface</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-superior-5-android-screenshot-and-video-tools-reviewed-for-2024/"><u>[New] Superior 5 Android Screenshot and Video Tools Reviewed for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-a-plan-for-file-explorer-in-windows-11/"><u>Crafting a Plan for File Explorer in Windows 11</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713960555334-new-2024-approved-tips-for-choosing-location-and-scheduling-music-video/"><u>New 2024 Approved Tips for Choosing Location & Scheduling Music Video</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-straightforward-guide-to-photo-uploads-on-instagram/"><u>The Straightforward Guide to Photo Uploads on Instagram</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-windows-file-explorer-path-settings/"><u>Customizing Windows File Explorer Path Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/cyber-armor-top-7-techniques-to-guard-your-os/"><u>Cyber Armor: Top 7 Techniques to Guard Your OS</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-rectifying-windows-11-search-issues/"><u>Comprehensive Guide to Rectifying Windows 11 Search Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-ios-photos-import-errors-on-windows-devices/"><u>Dealing with iOS Photos Import Errors on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/decreasing-high-cpu-usage-in-wmi/"><u>Decreasing High Cpu Usage in WMI</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-integrating-vimeo-to-instagram-posts/"><u>[New] 2024 Approved  Integrating Vimeo to Instagram Posts</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-ghostly-replay-instructional-guide/"><u>In 2024, Ghostly Replay Instructional Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/determining-hddssd-in-windows-a-step-by-step-guide/"><u>Determining HDD/SSD in Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-windows-pe-file-structure/"><u>Delving Into Windows PE File Structure</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-the-obscure-fixing-white-out-screens-in-win1011/"><u>Clearing the Obscure: Fixing White Out Screens in WIN10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/distinguishing-characteristics-of-exe-and-msi-files/"><u>Distinguishing Characteristics of EXE and MSI Files</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-ditch-adobe-10-linux-video-editing-software-you-need-to-try/"><u>New 2024 Approved Ditch Adobe 10 Linux Video Editing Software You Need to Try</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-overcoming-the-windows-virtualbox-efail-error/"><u>Decoding and Overcoming the Windows Virtualbox E_FAIL Error</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-5-traps-for-newbies-in-online-advertising-how-to-evade-them/"><u>[Updated] 5 Traps for Newbies in Online Advertising – How to Evade Them</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/ios-choice-premium-psp-emulators-ranked-1-5-for-2024/"><u>IOS Choice  Premium PSP Emulators Ranked #1-5 for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/ditching-unnecessary-wallpaper-icon-in-win11/"><u>Ditching Unnecessary Wallpaper Icon in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-your-window-11-experience-dynamic-wallpapers-guide/"><u>Customize Your Window 11 Experience: Dynamic Wallpapers Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-win11-remote-storage-paths/"><u>Configuring Win11 Remote Storage Paths</u></a></li>
<li><a href="https://windows11.techidaily.com/connected-scribbles-using-stickies-across-all-devices-in-win11/"><u>Connected Scribbles: Using Stickies Across All Devices in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/ditching-the-default-store-on-new-windows-11/"><u>Ditching the Default Store on New Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-windows-11s-user-identity-framework/"><u>Dissecting Windows 11'S User Identity Framework</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-process-system-isnt-responding-error-on-oppo-a2-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Process System Isnt Responding Error on Oppo A2 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-rectifying-windows-error-code-0x800704b3/"><u>Comprehensive Guide to Rectifying Windows Error Code 0X800704B3</u></a></li>
<li><a href="https://extra-tips.techidaily.com/crafting-podcast-episodes-essential-writing-techniques-and-examples-for-2024/"><u>Crafting Podcast Episodes  Essential Writing Techniques & Examples for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-windows-screensaver-tactics/"><u>Comprehensive Guide: Windows Screensaver Tactics</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-ten-step-window-repair-journey/"><u>Decoding the Ten-Step Window Repair Journey</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-windows-aggregatehostexe-its-functionality-and-dangers/"><u>Demystifying Windows' AggregateHost.exe: Its Functionality & Dangers</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-diablos-first-encounter-mechanics/"><u>Demystifying Diablo's First Encounter Mechanics</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-auto-triggered-console-crashes-on-windows/"><u>Disabling Auto-Triggered Console Crashes on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-fixing-error-0x80040610-in-microsoft-office-suite/"><u>Decoding and Fixing Error 0X80040610 in Microsoft Office Suite</u></a></li>
<li><a href="https://windows11.techidaily.com/comparing-ease-of-use-in-soft-installation-tools/"><u>Comparing Ease of Use in Soft Installation Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/cut-costs-not-compromise-top-5-free-media-software/"><u>Cut Costs, Not Compromise: Top 5 Free Media Software</u></a></li>
<li><a href="https://windows11.techidaily.com/covertly-masking-taskbars-language-feature-in-win11/"><u>Covertly Masking Taskbar's Language Feature in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/disable-untrusted-adobe-pop-up-on-computer/"><u>Disable Untrusted Adobe Pop-Up on Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/dism-tactics-restoring-windows-11-os-images/"><u>DISM Tactics: Restoring Windows 11 OS Images</u></a></li>
<li><a href="https://windows11.techidaily.com/clean-windows-search-interface-no-icons/"><u>Clean Windows Search Interface: No Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/decreasing-visual-noise-windows-11-tab-control/"><u>Decreasing Visual Noise: Windows 11 Tab Control</u></a></li>
</ul></div>
