---
title: Fixing Unable to Launch Java VM on Windows Systems
date: 2024-08-27T16:09:26.034Z
updated: 2024-08-28T16:09:26.034Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Unable to Launch Java VM on Windows Systems
excerpt: This Article Describes Fixing Unable to Launch Java VM on Windows Systems
keywords: Java VM Error Fix,Launch Java on Win,Troubleshoot Java Start,Resolve Java Boot Failure,JVM Unresponsive Solutions,Windows Java Launch Issue,Debug Java VM Launch
thumbnail: https://thmb.techidaily.com/ff2e2b344a8396c6bab8264d1025798025a6c7a29bed97ca0ab60000543775d0.jpg
---

## Fixing Unable to Launch Java VM on Windows Systems

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
5. If you have recently installed an update, check if the information checks out. If not, try to install the latest version available from the[Java website](https://www.oracle.com/in/java/technologies/downloads/) .

## 2\. End the Java Process in Task Manager

![end java process task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/end-java-process-task-manager.jpg)

 If the error is triggered when installing Java, check if a Java process is running in the background. You can use Task Manager to find and end background processes that may prevent you from installing the Java Runtime Environment or the development kit.

1. Press**Win + X** to open the**WinX menu** and select**Task Manager** .
2. In Task Manager, open the**Processes** tab and locate instances of**Java Virtual Machine** .
3. Select and click**End Task** to close the process.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Run Java as an Administrator

 Insufficient permission can prevent some Java apps from running on your computer. To fix the problem, run Java with administrative privilege. To run Java as an administrator on Windows, right-click on**Java.exe** and select**Run as administrator** .

 Alternatively, you can set the Java.exe to always run as administrator. This way, you don’t need to run Java with administrative privileges each time you want to launch it. Check out[how to always run a program as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) for more information.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
## 4\. Increase the System Memory for Java

 A common reason for the Could not create the Java virtual machine error is insufficient memory allocation, also known as Java heaps. Insufficient memory allocation can throttle the performance or cause the app to crash.

 To remedy this issue, you can increase the Java heap size. You can do this by modifying the**Runtime Parameters** from**Java Runtime Environment Settings** or changing the**\_JAVA\_OPTIONS** variable value to your preference.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
### How to Increase Java Heap Size by Manually Modifying Variables

To change Java heap size by modifying the \_JAVA\_OPTIONS variable:

1. Press the**Win** key and type**environmental variables** .  
![edit the system environmental variables](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/edit-the-system-environmental-variables.jpg)
2. Next, select**Edit the system environment variables** to open**System Properties** .
3. In the**Advanced** tab, click**Environment Variables** .  
![The Environment Variables button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/environment-variables-button.jpg)
4. In the**System Variables** section, click**New** . It is important to select the correct section.  
<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
![Windows new system variable java options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-new-system-variable-java-options.jpg)
5. Type**\-JAVA\_OPTIONS** in the**Variable name** field.
6. Next, type**\-Xmx512M** in the**Variable value** field. Here,**\-Xmx512M** defines the amount of memory you want to allocate. In this case, it is**512MB** of system memory.
7. Click**OK** , and**OK** once more to save the changes.

 Next, launch the app that shows the error and check if the error is resolved. If not, open**Environmental Variables** again. Select the -**JAVA\_OPTIONS** variable and click**Edit** . In the**Value data** field, type**\-Xmx1024M** to increase the memory size to 1**024 MB (1GB)** . Click**OK** and check for any improvements.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
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
6. Double-click on the**Runtime Parameters** column and type**\-Xmx512m** to assign 512 MB memory for the Java apps.  
![Java runtime environment settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/java-runtime-environment-settings.jpg)
7. Click**OK** to save the changes.
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Uninstall and Reinstall Java

![uninstall java Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/uninstall-java.jpg)

<!-- affiliate ads begin -->
<span id="1793213">
					<video width="1080" height="1620" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:1080px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If the issue persists, a reinstall may be necessary. You can uninstall and reinstall Java to fix any issues with the release. These issues may remain even if you install a newer version. To fix the issue, uninstall Java using the Java uninstaller and then reinstall the latest version available.

To clean install Java:

1. Go to the[Java Uninstall Tool page](https://www.java.com/en/download/uninstalltool.jsp) and download the uninstaller.
2. Run the executable and click**Agree** .
3. Select all the versions of Java detected by the tool and click**Next** .
4. Click**Yes** and wait as the uninstaller removes Java from your computer. Click**Close** .
5. Restart your computer to apply the changes.
6. Next, go to the[Java Downloads page](https://www.java.com/en/download/manual.jsp/) and download the latest version available for your operating system. Make sure to download the correct version (32-bit/64-bit), depending on the system architecture.
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
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-efficient-ways-to-clean-your-youtube-watch-later-playlist/"><u>[New] In 2024, Efficient Ways to Clean Your YouTube Watch Later Playlist</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-movavi-video-2024-innovations-and-review/"><u>[New] Movavi Video 2024  Innovations and Review</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-top-tier-mp4-director-for-facebook/"><u>[Updated] 2024 Approved  Top-Tier MP4 Director for Facebook</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-in-2024-innovate-visual-signatures-for-free-using-graphic-patterns/"><u>[Updated] In 2024, Innovate Visual Signatures for Free Using Graphic Patterns</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-your-key-to-creative-advertising-access-all-50-free-youtube-banner-designs/"><u>[Updated] Your Key to Creative Advertising  Access All 50 FREE YouTube Banner Designs</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-5-top-tier-gaming-displays-in-4k-quality/"><u>2024 Approved  5 Top-Tier Gaming Displays in 4K Quality</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-masterclass-choosing-the-pinnacle-in-hdr-cameras/"><u>2024 Approved  Masterclass  Choosing the Pinnacle in HDR Cameras</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-photo-perfection-for-newbies-the-lunapic-way/"><u>2024 Approved  Photo Perfection for Newbies  The LunaPic Way</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-ultimate-guide-to-funny-image-memes/"><u>2024 Approved  The Ultimate Guide to Funny Image Memes</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/breaking-down-razer-portal-a-comprehensive-review-for-gaming-enthusiasts-seeking-wi-fi-freedom/"><u>Breaking Down Razer Portal – A Comprehensive Review for Gaming Enthusiasts Seeking Wi-Fi Freedom</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/detailed-guide-of-ispoofer-for-pogo-installation-on-apple-iphone-13-pro-drfone-by-drfone-virtual-ios/"><u>Detailed guide of ispoofer for pogo installation On Apple iPhone 13 Pro | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-videos-from-honor-play-8t-by-fonelab-android-recover-video/"><u>Easy steps to recover deleted videos from Honor Play 8T</u></a></li>
<li><a href="https://windows11.techidaily.com/expeditiously-mute-windows-11-pings/"><u>Expeditiously Mute Windows 11 Pings</u></a></li>
<li><a href="https://sound-issues.techidaily.com/fix-mute-mic-and-speaker-problems-in-windows-10-instantly/"><u>Fix Mute Mic and Speaker Problems in Windows 10 Instantly</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-through-windows-media-storage-woes-in-cam/"><u>Guiding Through Windows Media Storage Woes in Cam</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/harnessing-microsoft-teams-power-with-simple-snap-camera-use/"><u>Harnessing Microsoft Teams' Power with Simple Snap Camera Use</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-combat-fall-guys-gameplay-interruptions-on-windows-devices/"><u>How To Combat Fall Guys Gameplay Interruptions on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-unresponsive-keys-on-your-microsoft-windows-computer-versions-11-7-and-8/"><u>How to Fix Unresponsive Keys on Your Microsoft Windows Computer (Versions 11, 7 & 8)</u></a></li>
<li><a href="https://techidaily.com/how-to-update-or-downgrade-apple-iphone-se-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade Apple iPhone SE Without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-vivo-x-flip-get-deleted-photos-back-with-ease-and-safety-by-fonelab-android-recover-photos/"><u>How to Vivo X Flip Get Deleted photos Back with Ease and Safety?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-move-contacts-from-gionee-f3-pro-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Move Contacts From Gionee F3 Pro to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-beautys-buzz-youtube-gurus-predicted/"><u>In 2024, Beauty's Buzz  YouTube Gurus Predicted</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-explore-costless-methods-for-superior-photo-quality/"><u>In 2024, Explore Costless Methods for Superior Photo Quality</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-tomorrows-digital-playground-a-comparative-study-of-metaverse-and-omniverse/"><u>In 2024, Tomorrow's Digital Playground  A Comparative Study of Metaverse & Omniverse</u></a></li>
<li><a href="https://windows11.techidaily.com/is-the-intel-unison-app-not-working-on-windows-11-heres-how-to-fix-it/"><u>Is the Intel Unison App Not Working on Windows 11? Here's How to Fix It</u></a></li>
<li><a href="https://windows11.techidaily.com/launching-startup-repair-in-windows-a-guide/"><u>Launching Startup Repair in Windows: A Guide</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/live-commerce-success-stories-lessons-learned-and-predictions-for-the-future/"><u>Live Commerce Success Stories Lessons Learned & Predictions for the Future</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-fixed-windows-update-blockades/"><u>Navigating Fixed Windows Update Blockades</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-past-s-mode-a-windows-users-roadmap/"><u>Navigating Past 'S Mode': A Windows User's Roadmap</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-error-0x80070194-on-windows-onedrive/"><u>Overcoming Error 0X80070194 on Windows' OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-dilemma-of-disrupted-device-use-by-other-software/"><u>Overcoming the Dilemma of Disrupted Device Use by Other Software</u></a></li>
<li><a href="https://windows11.techidaily.com/postponing-edges-tab-transition-on-windows-11/"><u>Postponing Edge's Tab Transition on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/power-up-your-command-line-discover-the-top-20-cmd-commands/"><u>Power Up Your Command Line: Discover the Top 20 CMD Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/proven-strategies-for-combining-diverse-windows-partitions/"><u>Proven Strategies for Combining Diverse Windows Partitions</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-to-mend-operation-0x0000011b-error-on-windows-11/"><u>Quick Guide to Mend Operation 0X0000011B Error on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-display-driver-startup-issue-in-windows-11/"><u>Remedying Display Driver Startup Issue in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-steam-cloud-connectivity-issues/"><u>Resolving Steam Cloud Connectivity Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/restarting-method-for-a-non-functional-windows-11-wi-fi-connection/"><u>Restarting Method for a Non-Functional Windows 11 Wi-Fi Connection</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-lost-wi-fi-connection-on-windows-11-devices/"><u>Restoring Lost Wi-Fi Connection on Windows 11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-for-windows-11-dolby-atmos-audio/"><u>Step-by-Step for Windows 11: Dolby Atmos Audio</u></a></li>
<li><a href="https://win-dash.techidaily.com/successfully-installing-western-digital-ses-external-hard-drive-drivers-effective-methods-for-models-released-after-2011/"><u>Successfully Installing Western Digital SES External Hard Drive Drivers (Effective Methods for Models Released After 2011)</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-govern-devices-on-slumbering-pcs/"><u>Techniques to Govern Devices on Slumbering PCs</u></a></li>
<li><a href="https://vp-tips.techidaily.com/the-art-of-sound-in-slides-adding-and-capturing-audiotracks/"><u>The Art of Sound in Slides  Adding and Capturing Audiotracks</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-artisans-guide-to-creating-sound-alterations-without-cost/"><u>The Artisan's Guide to Creating Sound Alterations Without Cost</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/the-best-way-to-study-portuguese-6-tips-that-will-work-wonders/"><u>The Best Way To Study Portuguese - 6 Tips That Will Work Wonders</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/the-key-to-quick-and-effective-small-image-generation/"><u>The Key to Quick and Effective Small Image Generation</u></a></li>
<li><a href="https://windows11.techidaily.com/the-transformation-ai-integration-into-windows-11/"><u>The Transformation: AI Integration Into Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-making-your-cursor-stand-out-in-windows-11/"><u>The Ultimate Guide to Making Your Cursor Stand Out in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-address-steams-file-privilege-problem-in-win11/"><u>Tips to Address Steam's File Privilege Problem in Win11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-4-strategies-for-leveraging-ai-in-higher-education-research/"><u>Top 4 Strategies for Leveraging AI in Higher Education Research</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-power-of-openais-whisper-on-your-windows-pc/"><u>Unveiling the Power of OpenAI's Whisper on Your Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/why-choose-linux-without-windows-subsystem/"><u>Why Choose Linux without Windows Subsystem?</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-faces-issue-file-thumbnails-not-appearing/"><u>Windows 11 Faces Issue: File Thumbnails Not Appearing</u></a></li>
<li><a href="https://windows11.techidaily.com/winwm-energy-hack-lowering-gpu-draw-in-windows-11/"><u>WinWM Energy Hack: Lowering GPU Draw in Windows 11</u></a></li>
</ul></div>
