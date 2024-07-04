---
title: Changing Terminal's Default Backdrop
date: 2024-06-25T12:18:18.232Z
updated: 2024-06-26T12:18:18.232Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Changing Terminal's Default Backdrop
excerpt: This Article Describes Changing Terminal's Default Backdrop
keywords: Terminal Wallpaper Change,Default Backdrop Update,Changing Terminal Background,Set Terminal Backdrop,Customize Terminal Appearance,Alter Terminal Design,Terminal Theme Adjustment
thumbnail: https://thmb.techidaily.com/a9af59315aea8cc232d9e9df37ddf4fb252ec7cdb030d740feb1460fb864db26.jpg
---

## Changing Terminal's Default Backdrop

 Changing the background image of the Windows Terminal is an easy way to customize your command line experience. This adds a personal touch and makes your experience visually appealing.

 This tutorial will explain three methods to change the Terminal background image in Windows 11.

## How to Change Windows Terminal Background Image

 You can change the background image of Windows Terminal in three ways: using the**Default** option within the Terminal app or manually editing the settings.json file using**File Explorer** and**Run** dialog box. All three methods achieve the same result and are easy to use.

 Using the default option is the simplest way to change your background image while editing the settings.json file provides more control and customization options. Below, we will guide you through each option.

## 1\. Change Windows Terminal Background Image via Its Options

 The easiest way to change the background image of Windows Terminal is by using its option. This can be done by opening Windows Terminal and changing settings within the app. Here's how to do it:

 To get started, open the Windows Terminal application first. For this, click on the Windows icon to open the Start menu. Then type**Terminal** into the search box, and select it from the list.

 Once you open the Terminal application, click on the dropdown menu icon in the top left corner, and select the**Settings** option.

 In the settings window's left column, go to**Defaults** . Now move to the right side of the page and tap**Appearance** to expand it.

![Change Windows Terminal Background Image via Default Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-windows-terminal-background-image-via-default-option.jpg)

 Scroll down to the**Background image** section, then click the**Background image path** option. Next, click the**Browse** option and select an image you want to use as a background.

 Click**Open** to confirm your selection. Now you should be able to see the selected image as the background of the terminal.

 You can also copy and paste the file path of an image directly into the Background image path option. Finally, click the**Save** button and the background image will be set.

 To improve the appearance of your image in the Windows Terminal, you can customize it using several options. You can use**Background image stretch mode** to change how the image is resized to fill the window. Further, you can change the**Background image alignment** to adjust the image position, and**Background image opacity** to make it more or less transparent.

 Once you are satisfied with the changes, click the**Save** button in order to apply them. Your custom background image should now be visible in the Windows Terminal.

 If you want to switch to the default image,[reset the Windows Terminal to its default settings](https://www.makeuseof.com/windows-11-reset-terminal-settings/) . This will automatically restore your background to the default image.

## 2\. Change the Windows Terminal Background Image via Windows File Explorer

 Manually editing settings.json is another great way to customize your Windows Terminal background image. For this, you need to open the settings.json file in any text editor, such as Notepad. Here's how to do it:

1. Open Windows File Explorer (see our guide on[how to open File Explorer on a Windows PC](https://www.makeuseof.com/windows-open-file-explorer/) ).
2. Once you're in File Explorer, navigate to your**C:** drive and select the**Users** folder.
3. Locate your**username** in this folder, then open the**AppData** folder and the**Local** folder.
4. In the Local folder, find and open the**Packages** folder.
5. Look for the**Microsoft.WindowsTerminal\_8wekyb3d8bbwe** folder and open it.
6. Finally, in this folder, double-click on**Settings** to open settings.json in any text editor.

 In the settings.json file, you will find a section called**backgroundImage** . You can use**Ctrl + F** to find it quickly.

 This is where you can enter the path of your own image to set as the Windows Terminal background. To do this, first copy the full file path for the image you want to use, including the file name.

![How to Change Windows Terminal Background Image From Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/how-to-change-windows-terminal-background-image-from-windows-file-explorer.jpg)

 Then paste this path into the**backgroundImage** section of settings.json. Remember to include a comma (**,**) after the path, as shown in the image above.

 Once you have pasted the path of your image, save the settings file and close the text editor. To apply this new background image, simply restart your Windows Terminal. The new background image should be displayed on the terminal window.

 You can adjust the image transparency using the same method. Simply input values for the**backgroundImageOpacity** parameters to modify the settings. These additional settings allow you to personalize your Windows Terminal background image even further.

 Restart Windows Terminal for the changes to take effect. In this way, you can easily customize your Windows Terminal background image using the settings.json file.

## 3\. Change the Windows Terminal Background Image Using the Run Command

 The Run Command can also help you change your Windows Terminal background image. Instead of searching for the settings.json file in Windows File Explorer, you can directly access and modify it using this tool.

 Follow these instructions to customize your Windows Terminal background image using the Run Command tool:

1. Right-click on Start and select**Run** from the menu list. If you prefer using shortcut keys, press**Win + R** on your keyboard to open the tool directly.
2. In the text box, type the following command and press Enter:  
`%localappdata%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState`
3. This will open the Local State folder containing the settings.json file. Right-click on**Settings** and select**Open with** \>**Notepad** .  
![Change Windows Terminal Background Image From Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-windows-terminal-background-image-from-windows-file-explorer.jpg)
4. Scroll down to the**backgroundImage** section and replace the image path with your own.
5. Then press**Ctrl + S** on your keyboard to save the changes.
6. Close Notepad, then open Windows Terminal to see your new background image.

 You’re done! Now you know how to customize your Windows Terminal background image using the Run Command tool. You can further explore the settings.json file or use other tools to[customize and personalize your Windows Terminal](https://www.makeuseof.com/windows-terminal-customization/) .

## Set a New Background Image for Windows Terminal

 It's easy to customize your Windows Terminal by adding or changing the background image. All you need to do is access the settings.json file, where you can also adjust your image's transparency. Just remember to restart Windows Terminal after making changes. Read this guide to learn how to customize your Windows Terminal background image easily.

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
<li><a href="https://windows11.techidaily.com/unlocking-power-settings-for-cpu-state-insights/"><u>Unlocking Power Settings for CPU State Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-invisibility-of-task-view-on-bar/"><u>Techniques for Invisibility of Task View on Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-snipping-tool-keyboard-failures-on-pc/"><u>Fixing Snipping Tool Keyboard Failures on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-ppt-file-saving-challenges-swift-solutions-in-windows-11/"><u>Conquer PPT File Saving Challenges: Swift Solutions in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/discreetly-putting-an-end-to-invisible-window-tasks/"><u>Discreetly Putting an End to Invisible Window Tasks</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-activities-gain-more-in-less-time-with-flow-launcher/"><u>Streamline Activities: Gain More in Less Time With Flow Launcher</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-language-input-change-keyboard-layouts-in-win-11/"><u>Simplifying Language Input: Change Keyboard Layouts in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-challenge-of-non-working-win-plus-printer-feature-in-windows/"><u>Tackling the Challenge of Non-Working Win + Printer Feature in Windows.</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-unresponsive-f-keys-troubleshooting-in-windows-11-os/"><u>Fix: Unresponsive F Keys - Troubleshooting in Windows 11 OS</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-fake-snapchat-location-without-jailbreak-on-apple-iphone-xs-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Fake Snapchat Location without Jailbreak On Apple iPhone XS | Dr.fone</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-in-2024-best-free-video-editors-with-no-watermark/"><u>New In 2024, Best Free Video Editors with No Watermark</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-unlocking-fullscreen-footage-screen-recording-made-simple-for-mac-users/"><u>[Updated] 2024 Approved  Unlocking Fullscreen Footage  Screen Recording Made Simple for Mac Users</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-engage-efficiently-leading-insta-filters/"><u>[New] In 2024, Engage Efficiently  Leading Insta Filters</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-breakdown-of-pewdiepies-monthly-earning-trends/"><u>[New] Breakdown of PewDiePie's Monthly Earning Trends</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-perfect-pair-merging-your-youtube-video-library/"><u>[New] Perfect Pair  Merging Your YouTube Video Library</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-life360-notify-when-you-log-out-on-infinix-smart-8-hd-drfone-by-drfone-virtual-android/"><u>In 2024, Does Life360 Notify When You Log Out On Infinix Smart 8 HD? | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-streamlining-post-editing-the-art-of-vimeos-final-screens/"><u>[New] 2024 Approved  Streamlining Post-Editing  The Art of Vimeo's Final Screens</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-direct-unwatermarked-tiktok-content-download-to-iphone-for-2024/"><u>[Updated] Direct Unwatermarked TikTok Content Download to iPhone for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-ultimate-guide-to-prime-3ds-reproduction-software/"><u>[Updated] Ultimate Guide to Prime 3Ds Reproduction Software</u></a></li>
</ul></div>
