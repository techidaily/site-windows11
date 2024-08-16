---
title: 5 Ways to Close Multiple Apps Simultaneously on Windows
date: 2024-08-15T15:14:39.293Z
updated: 2024-08-16T15:14:39.293Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 5 Ways to Close Multiple Apps Simultaneously on Windows
excerpt: This Article Describes 5 Ways to Close Multiple Apps Simultaneously on Windows
keywords: Close Apps Windows Quick,Multi-Task App Management,Closing Apps Sync,Speed up PC Efficiency,Batch App Shutdown Tool,Simultaneous Close Software,Fast App Termination Guide
thumbnail: https://thmb.techidaily.com/33139754522d3393b0a998cc016bffa1b55254150a3f5abcd672e5d0c2f8e9f3.jpg
---

## 5 Ways to Close Multiple Apps Simultaneously on Windows

 Running multiple apps simultaneously can usually affect your PC’s performance. This means you might often want to close some programs to speed up your device. But here’s the thing—closing your apps one by one can be quite tedious.

 So, how can you simplify things and close your multiple apps simultaneously on Windows? Let’s find out.

## 1\. Use the Taskbar

 The Windows taskbar displays all your active and pinned programs. This means you can easily close your active apps by scrolling to the relevant taskbar icon and clicking the “close” button.

 The good news is that you can also use the taskbar to close multiple windows of the same program. However, you won’t be able to close different apps simultaneously using the taskbar.

 Here's how to close multiple windows of the same program on the taskbar:

1. Navigate to the taskbar and locate an app that has multiple active windows.
2. Right-click on the app and select the **Close all windows** option.

![Closing multiple windows on the taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/closing-multiple-windows-on-the-taskbar.jpg)

## 2\. Use the Resource Monitor

 You probably know that you can [force close your PC programs](https://www.makeuseof.com/tag/how-to-kill-unresponsive-programs-without-the-task-manager/) using the Task Manager. But the problem is that this tool doesn’t let you close your programs simultaneously.

 Wondering if there's an alternative tool you can use? Try the Resource Monitor!

 Here are the steps for closing multiple apps simultaneously using the Resource Monitor:

1. Type **Resource Monitor** in the Start menu search bar and select the **Best match**.
2. Navigate to the **Overview** tab.
3. Check the boxes of the apps you want to close.
4. Right-click on one of the results and select the **End Process** option. This should simultaneously close all the programs you selected.

![Closing multiple apps using the Resource Monitor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/closing-multiple-apps-using-the-resource-monitor.jpg)

 Want to know the best part about using the Resource Monitor? This tool allows you to re-open multiple apps simultaneously with just a few clicks!

 Here's how to reopen your apps with the Resource Monitor:

1. Access the **Resource Monitor** by applying the previous steps.
2. Check the boxes of all the apps you want to re-open.
3. Right-click on one of the results and select **Resume Process**.

<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Use the Command Prompt

![Person using a Windows PC while placing it on a lap](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Person-using-a-Windows-PC-while-placing-it-on-a-lap.jpg)

 The Command Prompt can help you troubleshoot PC issues, configure some system settings, and run your Windows apps.

 Interestingly, this tool can also help you simultaneously close multiple windows of the same app. However, the Command Prompt might not be the best option if you want to close different apps simultaneously.

 Here’s how you can close multiple windows of the same app using the Command Prompt:

1. Type **Command Prompt** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as administrator**.

![Opening the Command Prompt using the Start menu search bar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/opening-the-command-prompt-using-the-start-menu-search-bar.jpg)

 Let’s say you want to close multiple File Explorer windows simultaneously. To do that, type the following command in the Command Prompt and press **Enter**:

taskkill /f /im explorer.exe

 The “taskkill /f /im” command is the one that closes the program, and the “explorer.exe” command is the name of the app. To close multiple windows of your other apps, replace the “explorer.exe” part with the relevant command.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Create a Batch Script for Closing Multiple Apps Simultaneously

![A person using a Windows device on a desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/A-person-using-a-Windows-device-on-a-desk.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->

 We’ve already discovered that the Command Prompt can only help you close multiple windows of the same app.

 But if you apply a few tricks, you can close multiple apps using some commands. However, you’d need to [create a batch script](https://www.makeuseof.com/tag/write-simple-batch-bat-file/) for that.

 Here's how you can create a batch script for closing multiple apps on Windows:

1. Press **Win + D** to access the desktop. Alternatively, check out the [various ways to access the Windows desktop](https://www.makeuseof.com/windows-quickly-access-desktop/).
2. Right-click on a blank space and select **New > Text Document**. This will create an untitled document on your desktop.

 Now, let’s say you want to close the **Snipping Tool** and the **Paint.net** app simultaneously. Here are the steps you need to follow:

1. Navigate to the desktop and double-click on the text document you’ve just created.
2. Type the following command to close the Snipping Tool:

taskkill /f /im SnippingTool.exe /T > nul

 Next, type the following command to close the Paint.net app:

taskkill /f /im paintdotnet.exe /T > nul

![Creating a Batch Script for Closing Multiple Apps Simultaneously](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/creating-a-batch-script-for-closing-multiple-apps-simultaneously.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->

 From there, follow these steps:

1. Press the **File** tab in the top-left corner of the text file.
2. Select the **Save As** option.
3. Type **Close Multiple Apps Simultaneously.bat** in the **File name** box.
4. Press the **Save** button.

 Now, you can close the Snipping Tool and the Paint.net app simultaneously by following these steps:

1. Press **Win + E** to access File Explorer.
2. Select the **Desktop** option on the left.
3. Click the **Close Multiple Apps Simultaneously.bat** batch file.

![Clicking a batch script on the desktop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/clicking-a-batch-script-on-the-desktop.jpg)

 You can add as many apps as you want to your batch script.

 And when using the batch script, ensure that it doesn’t end up closing some important apps by mistake. This means it might be worth regularly checking what’s on the script first before running it.

## 5\. Use the Close All Windows Tool

![The Close All Windows Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-close-all-windows-tool.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->

 You can also quickly close your multiple active apps using a third-party program like the [Close All Windows tool](https://www.softpedia.com/get/System/System-Miscellaneous/AA-Close-All-Windows.shtml). The tool is lightweight, which means it won’t take up much of your disk space.

 This app works almost like the Windows built-in Resource Monitor. However, it comes with a basic and easy-to-understand interface. When you open the tool, it immediately displays all your active apps. All you need to do is tick the relevant boxes and then click the **OK** button to close those apps.

 The tool displays all your apps and places them under a specific category. For example, it displays all your Google Chrome windows under the Google Chrome category.

 To select all the apps on the screen, press **Ctrl + A** or navigate to the **Command** tab and click **Select All**. And if you want to uncheck all the apps, press **Ctrl + D** or click the **Deselect All** option from the **Command** tab.

 You can customize the Close All Windows tool by clicking the **View** tab and ticking the relevant boxes. And if the tool seems a bit too complicated to use, then you can navigate to the **Help** tab to get some assistance.

**Download**: Close All Windows for [Windows](https://www.softpedia.com/get/System/System-Miscellaneous/AA-Close-All-Windows.shtml) (Free, subscription available)

<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
## Close Your Multiple Apps Simultaneously With Just a Few Clicks

 It’s always frustrating when your Windows device suddenly becomes slow or buggy. In most cases, such issues are caused by running tons of apps simultaneously.

 Want a quick way to speed up your device? Close your multiple active programs simultaneously using the tips we’ve covered. And if you end up closing some apps by mistake, you can apply some quick tricks to restore them again.


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
<li><a href="https://extra-tips.techidaily.com/new-adding-tunes-to-your-ios-clips-three-no-cost-ways-explored/"><u>[New] Adding Tunes to Your iOS Clips – Three No-Cost Ways Explored</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-color-gradings-secret-weapon-learning-about-luts/"><u>[New] Color Grading's Secret Weapon  Learning About LUTs</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-amplify-your-insta-impact-essential-5-lessons-for-influencers-and-real-life-proofs/"><u>[New] In 2024, Amplify Your Insta Impact  Essential 5 Lessons for Influencers & Real-Life Proofs</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-2024-approved-ranking-10-must-see-history-youtube-channels-for-learners/"><u>[Updated] 2024 Approved  Ranking 10 Must-See History YouTube Channels for Learners</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-streamlining-your-gaming-playback-for-2024/"><u>[Updated] Streamlining Your Gaming Playback for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-taking-control-youtube-visibility-personalization/"><u>[Updated] Taking Control  YouTube Visibility Personalization</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-swiftly-overcome-video-send-errors-in-facebook-chat-for-iphones-android/"><u>2024 Approved  Swiftly Overcome Video Send Errors in Facebook Chat for iPhones, Android</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-messages-from-xiaomi-redmi-13c-by-fonelab-android-recover-messages/"><u>Easy steps to recover deleted messages from Xiaomi Redmi 13C</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-color-discrepancies-on-microsoft-windows/"><u>Fixing Color Discrepancies on Microsoft Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-through-setting-up-and-adjusting-net-settings/"><u>Guide Through Setting Up and Adjusting Net Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-fix-invalid-label-alert-in-win11/"><u>Guide to Fix Invalid Label Alert in Win11</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-from-realme-11x-5g-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock from Realme 11X 5G Phones with/without a PC</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-leave-a-life360-group-on-htc-u23-pro-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How To Leave a Life360 Group On HTC U23 Pro Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-apple-iphone-6s-data-from-itunes-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Apple iPhone 6s Data From iTunes? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-best-pokemons-for-pvp-matches-in-pokemon-go-for-vivo-s17e-drfone-by-drfone-virtual-android/"><u>In 2024, Best Pokemons for PVP Matches in Pokemon Go For Vivo S17e | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-prime-10-terraria-game-enhancements/"><u>In 2024, Prime 10 Terraria Game Enhancements</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/listenlogic-evaluating-alternatives-to-dacast/"><u>ListenLogic  Evaluating Alternatives to DaCast</u></a></li>
<li><a href="https://windows11.techidaily.com/manipulating-image-summary-dimensions-w11/"><u>Manipulating Image Summary Dimensions W11</u></a></li>
<li><a href="https://windows11.techidaily.com/minimizing-resource-waste-during-device-integration-on-windows/"><u>Minimizing Resource Waste During Device Integration on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-win11-with-ease-mastering-package-control-using-wingetui/"><u>Navigate Win11 with Ease: Mastering Package Control Using WingetUI</u></a></li>
<li><a href="https://win-blog.techidaily.com/optimize-your-gameplay-overcoming-lag-spikes-in-bless-unleashed-for-pc-players/"><u>Optimize Your Gameplay: Overcoming Lag Spikes in Bless Unleashed for PC Players</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/izing-your-youtube-music-selection/"><u>Optimizing Your YouTube Music Selection</u></a></li>
<li><a href="https://windows11.techidaily.com/perfect-speech-capture-on-a-windows-device/"><u>Perfect Speech Capture on a Windows Device</u></a></li>
<li><a href="https://windows11.techidaily.com/precision-tools-for-program-harmony-on-pc/"><u>Precision Tools for Program Harmony on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/selecting-a-window-for-your-needs-the-win11-homepro-showdown/"><u>Selecting a Window for Your Needs: The Win11 Home/Pro Showdown</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/silence-the-algorithmic-intrusions-on-ig-for-2024/"><u>Silence the Algorithmic Intrusions on IG for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-solve-chrome-not-saving-or-uploading-issues-on-windows/"><u>Steps to Solve Chrome Not Saving or Uploading Issues on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-rescuing-non-transferring-usbs-in-windows/"><u>Strategies for Rescuing Non-Transferring USBs in Windows</u></a></li>
<li><a href="https://some-approaches.techidaily.com/streamline-and-enhance-with-these-key-zoom-setup-steps-for-2024/"><u>Streamline & Enhance with These Key Zoom Setup Steps for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-shifting-windows-taskbar-a-historical-view/"><u>The Shifting Windows Taskbar: A Historical View</u></a></li>
<li><a href="https://media-tips.techidaily.com/three-effective-ways-to-transform-images-into-videos-a-step-by-step-guide/"><u>Three Effective Ways to Transform Images Into Videos: A Step-by-Step Guide</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-9-oppo-a38-monitoring-apps-for-parental-controls-drfone-by-drfone-virtual-android/"><u>Top 9 Oppo A38 Monitoring Apps for Parental Controls | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-unseen-hdd-in-windows/"><u>Troubleshooting Unseen HDD in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-typing-potential-essentials-for-crafting-shortcuts-in-the-latest-windows-version/"><u>Unlock Typing Potential: Essentials for Crafting Shortcuts in the Latest Windows Version</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-efficiency-9-gains-from-the-newest-outlook-update/"><u>Unlocking Efficiency: 9 Gains From the Newest Outlook Update</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-power-of-outlook-preview-on-windows-11/"><u>Unlocking the Power of Outlook Preview on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-yourphoneexe-usefulness-on-modern-windows/"><u>Unlocking YourPhone.exe: Usefulness on Modern Windows?</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-invisible-windows-methods-to-bring-them-back-in-win10win11/"><u>Unveiling Invisible Windows: Methods to Bring Them Back in Win10/Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-steps-to-fix-rockalldlldll-not-found-error/"><u>Unveiling Steps to Fix 'Rockalldll.dll Not Found Error'</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-top-7-pencil-powerhouses-for-windows-creators/"><u>Unveiling the Top 7 Pencil Powerhouses for Windows Creators</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-with-virtualbox-deps-before-the-big-setup/"><u>Winning with VirtualBox: Deps Before the Big Setup</u></a></li>
</ul></div>
