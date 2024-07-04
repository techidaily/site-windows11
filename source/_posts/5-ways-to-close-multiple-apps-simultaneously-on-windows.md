---
title: 5 Ways to Close Multiple Apps Simultaneously on Windows
date: 2024-07-03T11:18:13.114Z
updated: 2024-07-04T11:18:13.114Z
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

## 4\. Create a Batch Script for Closing Multiple Apps Simultaneously

![A person using a Windows device on a desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/A-person-using-a-Windows-device-on-a-desk.jpg)

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

 You can also quickly close your multiple active apps using a third-party program like the [Close All Windows tool](https://www.softpedia.com/get/System/System-Miscellaneous/AA-Close-All-Windows.shtml). The tool is lightweight, which means it won’t take up much of your disk space.

 This app works almost like the Windows built-in Resource Monitor. However, it comes with a basic and easy-to-understand interface. When you open the tool, it immediately displays all your active apps. All you need to do is tick the relevant boxes and then click the **OK** button to close those apps.

 The tool displays all your apps and places them under a specific category. For example, it displays all your Google Chrome windows under the Google Chrome category.

 To select all the apps on the screen, press **Ctrl + A** or navigate to the **Command** tab and click **Select All**. And if you want to uncheck all the apps, press **Ctrl + D** or click the **Deselect All** option from the **Command** tab.

 You can customize the Close All Windows tool by clicking the **View** tab and ticking the relevant boxes. And if the tool seems a bit too complicated to use, then you can navigate to the **Help** tab to get some assistance.

**Download**: Close All Windows for [Windows](https://www.softpedia.com/get/System/System-Miscellaneous/AA-Close-All-Windows.shtml) (Free, subscription available)

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
<li><a href="https://windows11.techidaily.com/rejuvenating-your-apathetic-windows-start-button-click/"><u>Rejuvenating Your Apathetic Windows Start Button Click</u></a></li>
<li><a href="https://windows11.techidaily.com/realign-your-windows-clock-through-chrome-settings/"><u>Realign Your Windows Clock Through Chrome Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/method-to-rectify-the-zero-x-error-on-windows-11s-mail-app/"><u>Method to Rectify the Zero X Error on Windows 11’S Mail App</u></a></li>
<li><a href="https://windows11.techidaily.com/key-steps-unveiled-navigating-disks-in-w10-and-w11-systems/"><u>Key Steps Unveiled: Navigating Disks in W10 & W11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/advance-work-efficiency-with-windows-smart-launcher-tool/"><u>Advance Work Efficiency with Windows' Smart Launcher Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-inaccessible-page-errors-for-windows-store-apps/"><u>Addressing Inaccessible Page Errors for Windows Store Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/transitioning-from-ios-to-a-pc-a-complete-guide-to-imessage/"><u>Transitioning From iOS to a PC: A Complete Guide to iMessage</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-leading-slow-mo-camera-apps-for-iphoneandroid-users/"><u>[New] Leading Slow Mo Camera Apps for iPhone/Android Users</u></a></li>
<li><a href="https://android-location.techidaily.com/3-effective-methods-to-fake-gps-location-on-android-for-your-infinix-note-30i-drfone-by-drfone-virtual/"><u>3 Effective Methods to Fake GPS location on Android For your Infinix Note 30i | Dr.fone</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-free-2d-animation-software-is-great-to-create-hand-drawing-animation-now-check-the-10-best-2d-animation-software-that-best-for-beginnerspros/"><u>New In 2024, Free 2D Animation Software Is Great to Create Hand Drawing Animation. Now Check the 10 Best 2D Animation Software that Best for Beginners/Pros</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/crafting-perfect-squares-imovie-guide-for-instagram-videos-for-2024/"><u>Crafting Perfect Squares  IMovie Guide for Instagram Videos for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-set-your-preferred-job-location-on-linkedin-app-of-your-samsung-galaxy-f14-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Set Your Preferred Job Location on LinkedIn App of your Samsung Galaxy F14 5G | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-masterclass-comprehensive-overview-of-dji-phantom-4/"><u>In 2024, Masterclass  Comprehensive Overview of DJI Phantom 4</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-can-realme-12-proplus-5gmirror-share-to-pc-drfone-by-drfone-android/"><u>How Can Realme 12 Pro+ 5GMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-renderforest-is-a-great-online-editing-platform-to-use-for-many-video-creators-if-you-want-to-make-an-intro-video-for-your-channel-or-daily-vlogs-yo/"><u>In 2024, Renderforest Is a Great Online Editing Platform to Use for Many Video Creators. If You Want to Make an Intro Video for Your Channel or Daily Vlogs, You Can Follow This Article to Know More Details</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-top-5-budget-friendly-windows-screen-recorders-2023-edition/"><u>[New] Top 5 Budget-Friendly Windows Screen Recorders – 2023 Edition</u></a></li>
</ul></div>
