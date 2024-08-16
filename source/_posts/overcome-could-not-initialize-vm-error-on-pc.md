---
title: Overcome 'Could Not Initialize VM' Error on PC
date: 2024-08-15T16:05:23.816Z
updated: 2024-08-16T16:05:23.816Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcome 'Could Not Initialize VM' Error on PC
excerpt: This Article Describes Overcome 'Could Not Initialize VM' Error on PC
keywords: Fix VM Startup Issue,Resolve VM Init Failure,Stop VM Initialization Error,Eliminate VM Boot Problems,Cure PC VM Not Starting,Eradicate VM Launching Fault,Overcome Virtual Machine Stalling
thumbnail: https://thmb.techidaily.com/7c98b3aa443d56db5acb03366d8aa2c1ee75e1644b06d32e3fca560857ba5e46.jpg
---

## Overcome 'Could Not Initialize VM' Error on PC

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

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. End the Java Process in Task Manager

![end java process task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/end-java-process-task-manager.jpg)

 If the error is triggered when installing Java, check if a Java process is running in the background. You can use Task Manager to find and end background processes that may prevent you from installing the Java Runtime Environment or the development kit.

1. Press**Win + X** to open the**WinX menu** and select**Task Manager** .
2. In Task Manager, open the**Processes** tab and locate instances of**Java Virtual Machine** .
3. Select and click**End Task** to close the process.

<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. Next, select**Edit the system environment variables** to open**System Properties** .
3. In the**Advanced** tab, click**Environment Variables** .  
![The Environment Variables button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/environment-variables-button.jpg)
4. In the**System Variables** section, click**New** . It is important to select the correct section.  
![Windows new system variable java options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-new-system-variable-java-options.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
6. Double-click on the**Runtime Parameters** column and type**\-Xmx512m** to assign 512 MB memory for the Java apps.  
![Java runtime environment settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/java-runtime-environment-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Click**OK** to save the changes.

## 5\. Uninstall and Reinstall Java

![uninstall java Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/uninstall-java.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->

 If the issue persists, a reinstall may be necessary. You can uninstall and reinstall Java to fix any issues with the release. These issues may remain even if you install a newer version. To fix the issue, uninstall Java using the Java uninstaller and then reinstall the latest version available.

To clean install Java:

1. Go to the [Java Uninstall Tool page](https://www.java.com/en/download/uninstalltool.jsp) and download the uninstaller.
2. Run the executable and click**Agree** .
3. Select all the versions of Java detected by the tool and click**Next** .
4. Click**Yes** and wait as the uninstaller removes Java from your computer. Click**Close** .
5. Restart your computer to apply the changes.
6. Next, go to the [Java Downloads page](https://www.java.com/en/download/manual.jsp/) and download the latest version available for your operating system. Make sure to download the correct version (32-bit/64-bit), depending on the system architecture.
7. Run the installer and click**Install** . Follow the on-screen instructions to complete the installation and restart your computer.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-spectacular-video-connections-quest/"><u>[New] 2024 Approved  Spectacular Video Connections Quest</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-how-to-proficiently-post-360-degree-content-on-fb/"><u>[New] In 2024, How to Proficiently Post 360-Degree Content on FB</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-maximize-impact-with-professional-360-video-uploads-for-youtube/"><u>[Updated] 2024 Approved  Maximize Impact with Professional 360° Video Uploads for YouTube</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-in-2024-picsart-edge-bringing-facial-movement-into-the-digital-realm/"><u>[Updated] In 2024, Picsart Edge  Bringing Facial Movement Into the Digital Realm</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-how-to-incrementally-lower-decibels-in-logic-pro/"><u>2024 Approved  How to Incrementally Lower Decibels in Logic Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-windows-11-performance-run-command-upgrade-guide/"><u>Boosting Windows 11 Performance: Run Command Upgrade Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/convenient-methods-for-local-policies-on-windows-11/"><u>Convenient Methods for Local Policies on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/craft-compelling-content-with-these-windows-tools/"><u>Craft Compelling Content with These Window's Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/creating-a-dual-disk-on-windows-independently/"><u>Creating a Dual Disk on Windows, Independently</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-high-cpu-usage-techniques-from-windows-resource-monitor/"><u>Decoding High CPU Usage: Techniques From Windows Resource Monitor</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-to-create-a-personalized-windows-text-recognition-program/"><u>Easy Steps to Create a Personalized Windows Text Recognition Program</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-for-windows-0x80780119-error-in-image/"><u>Fix for Windows' 0X80780119 Error in Image</u></a></li>
<li><a href="https://sound-issues.techidaily.com/getting-your-logitech-g-pro-x-microphone-up-and-running-again-expert-tips-and-advice/"><u>Getting Your Logitech G Pro X Microphone Up and Running Again - Expert Tips & Advice</u></a></li>
<li><a href="https://windows11.techidaily.com/halt-spotifys-autoplay-behavior-on-pc/"><u>Halt Spotify's Autoplay Behavior on PC</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-notes-from-iphone-6s-plus-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Recover Deleted Notes from iPhone 6s Plus? | Stellar</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-sharefake-location-on-whatsapp-for-honor-x9b-drfone-by-drfone-virtual-android/"><u>How to Share/Fake Location on WhatsApp for Honor X9b | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-8-ways-to-transfer-photos-from-motorola-moto-g23-to-iphone-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 8 Ways to Transfer Photos from Motorola Moto G23 to iPhone Easily | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-expanding-storytelling-with-alternative-cinematography/"><u>In 2024, Expanding Storytelling with Alternative Cinematography</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fake-the-location-to-get-around-the-mlb-blackouts-on-samsung-galaxy-xcover-7-drfone-by-drfone-virtual-android/"><u>In 2024, Fake the Location to Get Around the MLB Blackouts on Samsung Galaxy XCover 7 | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-honor-magic-6-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Honor Magic 6 to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-precision-and-power-choosing-best-kung-fu-games-ranked/"><u>In 2024, Precision & Power  Choosing Best Kung Fu Games Ranked</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-simple-strategies-for-recording-on-youtube/"><u>In 2024, Simple Strategies for Recording on YouTube</u></a></li>
<li><a href="https://win-howtos.techidaily.com/keyboard-malfunction-solved-restoring-functionality-to-broken-number-keys/"><u>Keyboard Malfunction Solved: Restoring Functionality to Broken Number Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-steam-library-synchronization-hitches/"><u>Navigating Through Steam Library Synchronization Hitches</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windowed-discord-for-flawless-search-experience/"><u>Optimizing Windowed Discord for Flawless Search Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/refinement-of-your-touchpad-settings-for-optimal-interaction/"><u>Refinement of Your Touchpad Settings for Optimal Interaction</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-closed-folder-issues-via-double-clicks-in-w10w11/"><u>Resolving Closed Folder Issues via Double-Clicks in W10/W11</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/second-screen-craftsman/"><u>Second-Screen Craftsman</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-triple-column-tiles-on-windows-11-a-quick-guide/"><u>Setting Up Triple Column Tiles on Windows 11 – A Quick Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/silencing-the-cacophony-soundcard-irq-fixes/"><u>Silencing the Cacophony: Soundcard IRQ Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/split-screen-style-selecting-separate-themes-for-each-windows-display/"><u>Split Screen Style: Selecting Separate Themes for Each Windows Display</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-disabling-onedrive-icon-on-windows-11-explore/"><u>Strategies for Disabling OneDrive Icon on Windows 11 Explore</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-your-media-experience-with-wmp/"><u>Streamlining Your Media Experience with WMP</u></a></li>
<li><a href="https://windows11.techidaily.com/the-complete-gamers-manual-to-winning-with-windows/"><u>The Complete Gamers' Manual to Winning With Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-adjusting-touchpad-sensitivity-in-windows/"><u>The Ultimate Guide to Adjusting Touchpad Sensitivity in Windows</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/the-ultimate-guide-to-free-accurate-youtube-transcript-creation-for-2024/"><u>The Ultimate Guide to Free, Accurate YouTube Transcript Creation for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-tips-for-optimizing-wsl-2-on-modern-windows/"><u>Top 5 Tips for Optimizing WSL 2 on Modern Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-11-eliminating-invisible-logins/"><u>Troubleshooting Windows 11: Eliminating Invisible Logins</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unleashing-full-fledged-gpt-conversations-a-guide-to-setting-up-freechatgpt-on-windows/"><u>Unleashing Full-Fledged GPT Conversations: A Guide to Setting Up FreeChatGPT on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-elevate-with-25-customization-tips/"><u>Windows 11: Elevate with 25 Customization Tips</u></a></li>
</ul></div>
