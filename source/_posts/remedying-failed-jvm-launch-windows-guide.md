---
title: "Remedying Failed JVM Launch: Windows Guide"
date: 2024-07-11T21:55:24.860Z
updated: 2024-07-12T21:55:24.860Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Remedying Failed JVM Launch: Windows Guide"
excerpt: "This Article Describes Remedying Failed JVM Launch: Windows Guide"
keywords: JVM Launch Troubleshoot,Java Startup Solutions,Fixing JVM Failures,Windows Java Errors,Resolving JVM Issues,Optimizing JVM Performance,Java Launch Guide Windows
thumbnail: https://thmb.techidaily.com/1e0694b6112d675bbb8f0d747ab36517f01502f4062f523abbe17fcfc5ae5fc7.jpg
---

## Remedying Failed JVM Launch: Windows Guide

 Your Windows 11 computer may require the latest version of Java installed for some applications to work. However, sometimes some Java apps may abruptly crash with the error Could not create the Java virtual machine.

 This error is often a case of insufficient memory allocation for Java apps. Additionally, check for permission issues and glitches with the Java release itself. If you are using it on your work computer for programming purposes, check if you have the correct version of Java IDE installed.

 Here we show you a few troubleshooting steps to fix the could not create the java virtual machine error on Windows.

## 1\. Verify Your Java Installation

![verify java installation command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/verify-java-intallation-command-prompt.jpg)

 Verifying your Java installation can help you determine issues with the release itself. You can use the**java -version** command in Command Prompt to check the current version of Java installed along with the date of installation.

To check the Java version installed on Windows:

1. Press the**Win** key and type**cmd** .
2. Right-click on**Command Prompt** and select**Run as administrator** .
3. In the Command Prompt window, type the following command and press**Enter** :  
`java -version`
4. The output will list the JDK version installed on your computer and the installation date.
5. If you have recently installed an update, check if the information checks out. If not, try to install the latest version available from the [Java website](https://www.oracle.com/in/java/technologies/downloads/) .

## 2\. End the Java Process in Task Manager

![end java process task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/end-java-process-task-manager.jpg)

 If the error is triggered when installing Java, check if a Java process is running in the background. You can use Task Manager to find and end background processes that may prevent you from installing the Java Runtime Environment or the development kit.

1. Press**Win + X** to open the**WinX menu** and select**Task Manager** .
2. In Task Manager, open the**Processes** tab and locate instances of**Java Virtual Machine** .
3. Select and click**End Task** to close the process.

## 3\. Run Java as an Administrator

 Insufficient permission can prevent some Java apps from running on your computer. To fix the problem, run Java with administrative privilege. To run Java as an administrator on Windows, right-click on**Java.exe** and select**Run as administrator** .

 Alternatively, you can set the Java.exe to always run as administrator. This way, you don’t need to run Java with administrative privileges each time you want to launch it. Check out [how to always run a program as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) for more information.

## 4\. Increase the System Memory for Java

 A common reason for the Could not create the Java virtual machine error is insufficient memory allocation, also known as Java heaps. Insufficient memory allocation can throttle the performance or cause the app to crash.

 To remedy this issue, you can increase the Java heap size. You can do this by modifying the**Runtime Parameters** from**Java Runtime Environment Settings** or changing the**\_JAVA\_OPTIONS** variable value to your preference.

### How to Increase Java Heap Size by Manually Modifying Variables

To change Java heap size by modifying the \_JAVA\_OPTIONS variable:

1. Press the**Win** key and type**environmental variables** .  
![edit the system environmental variables](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/edit-the-system-environmental-variables.jpg)
2. Next, select**Edit the system environment variables** to open**System Properties** .
3. In the**Advanced** tab, click**Environment Variables** .  
![The Environment Variables button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/environment-variables-button.jpg)
4. In the**System Variables** section, click**New** . It is important to select the correct section.  
![Windows new system variable java options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-new-system-variable-java-options.jpg)
5. Type**\-JAVA\_OPTIONS** in the**Variable name** field.
6. Next, type**\-Xmx512M** in the**Variable value** field. Here,**\-Xmx512M** defines the amount of memory you want to allocate. In this case, it is**512MB** of system memory.
7. Click**OK** , and**OK** once more to save the changes.

 Next, launch the app that shows the error and check if the error is resolved. If not, open**Environmental Variables** again. Select the -**JAVA\_OPTIONS** variable and click**Edit** . In the**Value data** field, type**\-Xmx1024M** to increase the memory size to 1**024 MB (1GB)** . Click**OK** and check for any improvements.

### How to Increase Java Heap Size Using the Java Control Panel

 You can also modify the default Java heap size from Java Runtime Environment Settings. Here’s how to do it.

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open Control Panel.
3. Next, click on**Programs** and click on**Java (32-bit)** .  
![windows control panel Java 32 bit programs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-control-panel-java-32-bit-programs.jpg)
4. In the**Java Control Panel** dialog, open the**Java** tab.
5. Click the**View** button.  
![java control panel java tab view](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/java-control-panel-java-tab-view.jpg)
6. Double-click on the**Runtime Parameters** column and type**\-Xmx512m** to assign 512 MB memory for the Java apps.  
![Java runtime environment settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/java-runtime-environment-settings.jpg)
7. Click**OK** to save the changes.

## 5\. Uninstall and Reinstall Java

![uninstall java Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/uninstall-java.jpg)

 If the issue persists, a reinstall may be necessary. You can uninstall and reinstall Java to fix any issues with the release. These issues may remain even if you install a newer version. To fix the issue, uninstall Java using the Java uninstaller and then reinstall the latest version available.

To clean install Java:

1. Go to the [Java Uninstall Tool page](https://www.java.com/en/download/uninstalltool.jsp) and download the uninstaller.
2. Run the executable and click**Agree** .
3. Select all the versions of Java detected by the tool and click**Next** .
4. Click**Yes** and wait as the uninstaller removes Java from your computer. Click**Close** .
5. Restart your computer to apply the changes.
6. Next, go to the [Java Downloads page](https://www.java.com/en/download/manual.jsp/) and download the latest version available for your operating system. Make sure to download the correct version (32-bit/64-bit), depending on the system architecture.
7. Run the installer and click**Install** . Follow the on-screen instructions to complete the installation and restart your computer.

## 6\. Install Java in a WindowsClean Boot State

 In Clean Boot State, Windows starts with only essential Microsoft services and apps. It’s a troubleshooting method to determine and find third-party app conflicts causing system errors. If you continue to see the error when installing Java,[start your Windows computer in a clean boot state](https://www.makeuseof.com/clean-boot-windows-11/) and try installing it again.

## Fixing the "Could Not Create the Java Virtual Machine" Error on Windows

 Insufficient Java heap size is what often triggers the Java virtual machine error. To fix the issue, modify the default heap size to be able to run Java apps without any problems.

 If the error occurs when installing Java, try to install the app in a clean boot state. Installing pending Windows updates can also help fix compatibility issues with the release.


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
<li><a href="https://windows11.techidaily.com/circumventing-windows-security-controlled-by-domain-admins/"><u>Circumventing Windows Security Controlled by Domain Admins</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-earning-by-critiquing-goodies-a-youtube-guide/"><u>[Updated] Earning by Critiquing Goodies  A YouTube Guide</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-video-basics-made-simple-a-list-of-10-accessible-youtube-projects/"><u>[Updated] Video Basics Made Simple  A List of 10 Accessible YouTube Projects</u></a></li>
<li><a href="https://windows11.techidaily.com/snip-and-sketch-vs-prtsc-the-best-tools-for-windows-users/"><u>Snip & Sketch Vs. PrtSc: The Best Tools for Windows Users</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-the-most-engaging-tiktok-stars-for-your-drive/"><u>[New] In 2024, The Most Engaging TikTok Stars for Your Drive</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-the-power-of-background-blur-a-windows-11-photo-guide/"><u>Discover the Power of Background Blur: A Windows 11 Photo Guide</u></a></li>
<li><a href="https://howto.techidaily.com/calls-on-oppo-find-n3-flip-go-straight-to-voicemail-12-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Calls on Oppo Find N3 Flip Go Straight to Voicemail? 12 Fixes | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-overcoming-unidentified-obs-recording-issue-on-win-11/"><u>Decoding and Overcoming Unidentified OBS Recording Issue on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reestablishing-clear-audio-conversations-on-valorant-pc/"><u>Reestablishing Clear Audio Conversations on Valorant PC</u></a></li>
<li><a href="https://windows11.techidaily.com/tracing-untapped-functions-within-windows-system-health-tools/"><u>Tracing Untapped Functions Within Windows' System Health Tools</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-maximize-your-fcpx-potential-top-40-keyboard-shortcuts-and-tricks/"><u>Updated 2024 Approved Maximize Your FCPX Potential Top 40 Keyboard Shortcuts and Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-optimal-performance-self-updating-updated-amd-driver/"><u>Achieve Optimal Performance: Self-Updating, Updated AMD Driver</u></a></li>
<li><a href="https://windows11.techidaily.com/curate-your-own-win11-screen-saver/"><u>Curate Your Own Win11 Screen Saver</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-registry-shortcomings-solutions/"><u>Unveiling Windows Registry Shortcomings: Solutions</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-efficient-screen-capture-devices-for-education/"><u>[Updated] In 2024, Efficient Screen Capture Devices for Education</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/essential-tools-top-8-mirrorless-cams-for-professional-filmmakers-for-2024/"><u>Essential Tools  Top 8 Mirrorless Cams For Professional Filmmakers for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/prioritize-and-achieve-a-guide-to-top-6-win-11-task-management-tools/"><u>Prioritize & Achieve - A Guide to Top 6 Win 11 Task Management Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-steam-friendship-disconnect-on-pcs/"><u>Steps to Resolve Steam Friendship Disconnect on PCs</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-do-you-get-sun-stone-evolutions-in-pokemon-for-oneplus-nord-ce-3-lite-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How Do You Get Sun Stone Evolutions in Pokémon For OnePlus Nord CE 3 Lite 5G? | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-liberating-your-account-beyond-the-shadowban/"><u>[Updated] 2024 Approved  Liberating Your Account  Beyond the Shadowban</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-your-shorts-are-here-no-more-waiting-game/"><u>[New] Your Shorts Are Here – No More Waiting Game</u></a></li>
<li><a href="https://windows11.techidaily.com/automatic-windows-tweak-transition-to-latest-amd-driver/"><u>Automatic Windows Tweak: Transition to Latest AMD Driver</u></a></li>
<li><a href="https://windows11.techidaily.com/reconnecting-to-ea-servers-in-a-windows-environment/"><u>Reconnecting to EA Servers in a Windows Environment</u></a></li>
<li><a href="https://screen-capture.techidaily.com/the-in-depth-guide-to-screen-capturing-in-online-meetings/"><u>The In-Depth Guide to Screen Capturing in Online Meetings</u></a></li>
<li><a href="https://windows11.techidaily.com/tracking-windows-logins-identifying-successes-and-failures/"><u>Tracking Windows Logins: Identifying Successes & Failures</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-apple-iphone-14-pro-drfone-by-drfone-ios/"><u>How to Unlock Apple iPhone 14 Pro? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-picking-a-software-dependency-provider/"><u>The Ultimate Guide to Picking a Software Dependency Provider</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-remedy-for-rearranged-character-inputs/"><u>Quick Remedy for Rearranged Character Inputs</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-activities-gain-more-in-less-time-with-flow-launcher/"><u>Streamline Activities: Gain More in Less Time With Flow Launcher</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-autonomous-scrolling-on-os-windows/"><u>Preventing Autonomous Scrolling on OS Windows</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-split-a-clip-in-davinci-resolve-step-by-step/"><u>Updated Split a Clip in DaVinci Resolve Step by Step</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-easy-mastery-of-ipad-video-recording-for-2024/"><u>[Updated] Easy Mastery of iPad Video Recording for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/why-is-nvidia-control-panel-inaccessible-on-win11/"><u>Why Is Nvidia Control Panel Inaccessible on Win11?</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-delving-into-youtubes-complex-calculation-of-viewer-stats/"><u>[New] 2024 Approved  Delving Into YouTube's Complex Calculation of Viewer Stats</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-evolution-unveiling-the-latest-system-updates/"><u>Windows 11'S Evolution: Unveiling the Latest System Updates</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/complete-guide-to-using-zd-softs-recording-tools/"><u>Complete Guide to Using ZD Soft's Recording Tools</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/the-essential-guide-to-populating-powerpoint-decks-with-youtube-videos-for-2024/"><u>The Essential Guide to Populating PowerPoint Decks With YouTube Videos for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/silencing-the-audio-stutter-taming-winirq-errors/"><u>Silencing the Audio Stutter: Taming WinIRQ Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-to-activate-rgb-settings-in-windows-11/"><u>Step-by-Step to Activate RGB Settings in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-overcome-run-as-command-issues/"><u>Strategies to Overcome 'Run As' Command Issues</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-essential-directories-the-premier-10-sites-for-acquiring-montage-soundtracks/"><u>New In 2024, Essential Directories The Premier 10 Sites for Acquiring Montage Soundtracks</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-overcome-endless-startup-in-bios-for-windows-systems/"><u>Steps to Overcome Endless Startup in BIOS for Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-steam-service-problems-for-a-smooth-windows-11-experience/"><u>Solving Steam Service Problems for a Smooth Windows 11 Experience</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-prime-gratis-programs-for-streaming-video-capture/"><u>[Updated] In 2024, Prime, Gratis Programs for Streaming Video Capture</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-top-secret-instagram-stories-viewer-apps/"><u>[Updated] In 2024, Top Secret Instagram Stories Viewer Apps</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-forgotten-pin-of-your-tecno-camon-20-by-drfone-android/"><u>How to Remove Forgotten PIN Of Your Tecno Camon 20</u></a></li>
<li><a href="https://windows11.techidaily.com/7-tricks-for-rejuvenating-non-responsive-windows-service-explorer/"><u>7 Tricks for Rejuvenating Non-Responsive Windows Service Explorer</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/the-seamless-guide-to-saving-gifs-on-iphonesandroids-for-2024/"><u>The Seamless Guide to Saving GIFs on iPhones/Androids for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-task-execution-windows-keyboard-tips-and-tricks/"><u>Speedy Task Execution: Windows Keyboard Tips & Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-power-settings-for-cpu-state-insights/"><u>Unlocking Power Settings for CPU State Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/a-visual-journey-top-7-windows-10-drawing-tools-unveiled/"><u>A Visual Journey: Top 7 Windows 10 Drawing Tools Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-data-handling-navigate-4-steps-to-open-disk-management-in-windows-11/"><u>Effortless Data Handling: Navigate 4 Steps to Open Disk Management in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/correction-of-inaccessible-device-path-issue-in-win/"><u>Correction of Inaccessible Device Path Issue in Win</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-inject-photos-with-focal-spread-outer-radius-adobe-psx/"><u>[Updated] Inject Photos with Focal Spread Outer Radius Adobe PSX</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-crafting-visual-harmony-a-color-grading-journey/"><u>In 2024, Crafting Visual Harmony  A Color Grading Journey</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-the-ultimate-list-of-mac-screen-capture-software/"><u>In 2024, The Ultimate List of Mac Screen Capture Software</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-the-ultimate-guide-to-video-uploads-on-instagram/"><u>[Updated] In 2024, The Ultimate Guide to Video Uploads on Instagram</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-weaving-in-youtubes-video-selection-a-step-by-step-guide/"><u>[Updated] Weaving in YouTube's Video Selection  A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-desktop-aesthetics-best-pc-time-saver-apps-listed/"><u>Boost Desktop Aesthetics – Best PC Time Saver Apps Listed</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-revolutionize-your-workflow-top-free-mac-dictation-apps/"><u>2024 Approved Revolutionize Your Workflow Top Free Mac Dictation Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-to-prevent-not-working-on-your-pc/"><u>Swift Solutions to Prevent 'Not Working' On Your PC</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-breaking-the-freeze-reviving-your-obs-cam/"><u>2024 Approved  Breaking the Freeze  Reviving Your OBS Cam</u></a></li>
<li><a href="https://windows11.techidaily.com/scrutinizing-underused-windows-features-for-system-checks/"><u>Scrutinizing Underused Windows Features for System Checks</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/securely-transforming-youtube-videos-into-mp3-files-3-techniques-for-2024/"><u>Securely Transforming YouTube Videos Into MP3 Files - 3 Techniques for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-user-interface-fastest-uninstall-actions-with-context/"><u>Elevate User Interface: Fastest Uninstall Actions with Context</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-learn-how-to-fix-distorted-audio-using-different-methods-for-2024/"><u>New Learn How To Fix Distorted Audio Using Different Methods for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-full-potential-mastering-multiple-screens-in-win11/"><u>Unlock Full Potential: Mastering Multiple Screens in Win11</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-15-top-video-to-gif-app-on-iphone-and-android/"><u>New 15 Top Video to GIF App on iPhone and Android</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-absence-of-thumbnail-images-on-windows-11-screens/"><u>Troubleshooting Absence of Thumbnail Images on Windows 11 Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-control-for-apps-and-browsers/"><u>Unveiling Windows Control for Apps & Browsers</u></a></li>
</ul></div>
