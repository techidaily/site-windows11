---
title: Remedying 'Could Not Create VM' Problems in Microsoft OS
date: 2024-08-15T15:51:08.683Z
updated: 2024-08-16T15:51:08.683Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Remedying 'Could Not Create VM' Problems in Microsoft OS
excerpt: This Article Describes Remedying 'Could Not Create VM' Problems in Microsoft OS
keywords: Fixing VM Creation Errors (MSO),Troubleshoot O/S VM Issue,Resolve VM Failure on MSO,Microsoft OS Virtual Setup,Eliminate 'Could Not' Problems,Overcoming OS VM Issues,Solve Creation Error (MSO)
thumbnail: https://thmb.techidaily.com/29ac8237603a8a16889982067f296c3f071e4f84b086086a9248bc69fcf254fa.jpg
---

## Remedying 'Could Not Create VM' Problems in Microsoft OS

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
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. End the Java Process in Task Manager

![end java process task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/end-java-process-task-manager.jpg)
<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the error is triggered when installing Java, check if a Java process is running in the background. You can use Task Manager to find and end background processes that may prevent you from installing the Java Runtime Environment or the development kit.

1. Press**Win + X** to open the**WinX menu** and select**Task Manager** .
2. In Task Manager, open the**Processes** tab and locate instances of**Java Virtual Machine** .
3. Select and click**End Task** to close the process.

## 3\. Run Java as an Administrator

 Insufficient permission can prevent some Java apps from running on your computer. To fix the problem, run Java with administrative privilege. To run Java as an administrator on Windows, right-click on**Java.exe** and select**Run as administrator** .

 Alternatively, you can set the Java.exe to always run as administrator. This way, you don’t need to run Java with administrative privileges each time you want to launch it. Check out [how to always run a program as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) for more information.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Increase the System Memory for Java

 A common reason for the Could not create the Java virtual machine error is insufficient memory allocation, also known as Java heaps. Insufficient memory allocation can throttle the performance or cause the app to crash.

 To remedy this issue, you can increase the Java heap size. You can do this by modifying the**Runtime Parameters** from**Java Runtime Environment Settings** or changing the**\_JAVA\_OPTIONS** variable value to your preference.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
### How to Increase Java Heap Size by Manually Modifying Variables

To change Java heap size by modifying the \_JAVA\_OPTIONS variable:

1. Press the**Win** key and type**environmental variables** .  
![edit the system environmental variables](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/edit-the-system-environmental-variables.jpg)
2. Next, select**Edit the system environment variables** to open**System Properties** .
3. In the**Advanced** tab, click**Environment Variables** .  
![The Environment Variables button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/environment-variables-button.jpg)
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. In the**System Variables** section, click**New** . It is important to select the correct section.  
![Windows new system variable java options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-new-system-variable-java-options.jpg)
5. Type**\-JAVA\_OPTIONS** in the**Variable name** field.
6. Next, type**\-Xmx512M** in the**Variable value** field. Here,**\-Xmx512M** defines the amount of memory you want to allocate. In this case, it is**512MB** of system memory.
7. Click**OK** , and**OK** once more to save the changes.

 Next, launch the app that shows the error and check if the error is resolved. If not, open**Environmental Variables** again. Select the -**JAVA\_OPTIONS** variable and click**Edit** . In the**Value data** field, type**\-Xmx1024M** to increase the memory size to 1**024 MB (1GB)** . Click**OK** and check for any improvements.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-instagram-ready-guide-to-cropping-and-exporting-videos/"><u>[New] 2024 Approved  Instagram-Ready  Guide to Cropping & Exporting Videos</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-tech-unity-expert-easeus-reviews/"><u>[New] 2024 Approved  Tech Unity  Expert EaseUS Reviews</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-terror-in-town-a-list-of-intense-zombie-games/"><u>[New] Terror in Town  A List of Intense Zombie Games</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-intellects-ultimate-guide-to-premium-gk-quiz-sites/"><u>[Updated] Intellect's Ultimate Guide to Premium GK Quiz Sites</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unveiling-best-video-software-vlc-against-mx/"><u>[Updated] Unveiling Best Video Software  VLC Against MX</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-vlcs-advanced-webcam-functionality-for-video-archiving/"><u>[Updated] VLC's Advanced Webcam Functionality for Video Archiving</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-adapting-to-diverse-candidate-personalities/"><u>2024 Approved  Adapting to Diverse Candidate Personalities</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-apex-1-written-by-assistant/"><u>2024 Approved  Apex 1 Written by Assistant</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-top-10-digital-storefronts-for-exquisite-presentation-boxes/"><u>2024 Approved  Top 10 Digital Storefronts for Exquisite Presentation Boxes</u></a></li>
<li><a href="https://extra-resources.techidaily.com/choosing-between-gopro-max-and-hero-11-top-cameras-compared/"><u>Choosing Between GoPro Max and Hero 11  Top Cameras Compared</u></a></li>
<li><a href="https://windows11.techidaily.com/easily-knock-off-the-onedrive-feature-from-file-explorer/"><u>Easily Knock Off the OneDrive Feature From File Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-to-activatedeactivate-secure-boot-and-tpm-in-virtualbox/"><u>Easy Steps to Activate/Deactivate Secure Boot & TPM in VirtualBox</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-steps-to-stop-and-fix-iomap64-bsod-on-windows-pcs/"><u>Effective Steps to Stop and Fix IOMap64 BSoD on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-file-transfers-the-top-5-windows-apps/"><u>Effortless File Transfers: The Top 5 Windows Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/effortlessly-organize-your-desks-icons/"><u>Effortlessly Organize Your Desk's Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/effortlessly-syncing-files-in-windows-1011/"><u>Effortlessly Syncing Files in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-workflow-choosing-the-best-6-to-do-list-apps-on-windows-11/"><u>Elevate Your Workflow: Choosing the Best 6 To-Do List Apps on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-virtual-battles-why-windows-reigns-supreme/"><u>Elevating Virtual Battles: Why Windows Reigns Supreme</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-chrome-aw-snap-glitch-on-windows/"><u>Eliminate Chrome “Aw, Snap!” Glitch on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-common-roadblocks-in-windows-11/"><u>Eliminating Common Roadblocks in WINDOWS 11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-steam-hurdles-to-play-your-favorite-game-on-win-11/"><u>Eliminating Steam Hurdles to Play Your Favorite Game on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-visibility-of-windows-11-task-view/"><u>Eliminating Visibility of Windows 11 Task View</u></a></li>
<li><a href="https://windows11.techidaily.com/enforcing-controlled-directory-access-on-modern-windows-os/"><u>Enforcing Controlled Directory Access on Modern Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-system-without-microsofts-core-software/"><u>Enhance Your System Without Microsoft's Core Software</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-power-feedback-setting-up-fully-charged-notifications-in-win11/"><u>Enhancing Power Feedback: Setting Up Fully Charged Notifications in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-productivity-with-custom-keybinds-in-windows-11-and-11/"><u>Enhancing Productivity with Custom Keybinds in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-user-experience-with-automatic-updates-toolbar-in-windows-11plus11/"><u>Enhancing User Experience with Automatic Updates Toolbar in Windows 11+11</u></a></li>
<li><a href="https://windows11.techidaily.com/enriching-linux-experience-via-windows-collaboration/"><u>Enriching Linux Experience via Windows Collaboration</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-a-smooth-transition-for-linux-subsystem-within-the-new-windows-paradigm/"><u>Ensuring a Smooth Transition for Linux Subsystem Within the New Windows Paradigm</u></a></li>
<li><a href="https://windows11.techidaily.com/entering-quake-modes-through-windows-terminal/"><u>Entering Quake Modes Through Windows Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/epic-launcher-uninstallation-hurdles-bust-them-on-windows-11/"><u>Epic Launcher Uninstallation Hurdles, Bust Them On Windows 11!</u></a></li>
<li><a href="https://windows11.techidaily.com/escalate-emulation-faster-yuzu-win-users/"><u>Escalate Emulation: Faster Yuzu, WIN Users</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/from-joke-to-jest-constructing-impactful-social-media-memes-for-2024/"><u>From Joke to Jest  Constructing Impactful Social Media Memes for 2024</u></a></li>
<li><a href="https://iphone-location.techidaily.com/how-to-see-someones-location-on-apple-iphone-15-pro-drfone-by-drfone-virtual-ios/"><u>How to See Someones Location on Apple iPhone 15 Pro | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-send-and-fake-live-location-on-facebook-messenger-of-your-infinix-note-30i-drfone-by-drfone-virtual-android/"><u>How to Send and Fake Live Location on Facebook Messenger Of your Infinix Note 30i | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-enhancing-engagement-on-video-calls-using-snap-features/"><u>In 2024, Enhancing Engagement on Video Calls Using Snap Features</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-high-definition-gameplay-capture-mastery/"><u>In 2024, High-Definition Gameplay Capture Mastery</u></a></li>
<li><a href="https://hardware-help.techidaily.com/install-the-newest-realtek-driver-software-directly-from-our-site-for-optimal-windows-11-support/"><u>Install the Newest Realtek Driver Software Directly From Our Site for Optimal Windows 11 Support</u></a></li>
<li><a href="https://extra-hints.techidaily.com/peak-laughter-edit-suite/"><u>Peak Laughter Edit Suite</u></a></li>
<li><a href="https://extra-hints.techidaily.com/refine-image-quality-on-canon-devices-using-free-plus-payable-lut-tools/"><u>Refine Image Quality on Canon Devices Using Free + Payable LUT Tools</u></a></li>
<li><a href="https://win-blog.techidaily.com/tackling-cod-warzones-challenge-a-comprehensive-guide-to-defeating-error-6328-2024-edition/"><u>Tackling COD Warzone's Challenge: A Comprehensive Guide to Defeating Error 6328 - 2024 Edition</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/unlocking-video-content-potential-integrating-interactive-features-in-youtube-cards-for-2024/"><u>Unlocking Video Content Potential  Integrating Interactive Features in Youtube Cards for 2024</u></a></li>
</ul></div>
