---
title: Transition to New Background in WinTerminal
date: 2024-10-13T21:14:20.259Z
updated: 2024-10-18T16:17:37.596Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Transition to New Background in WinTerminal
excerpt: This Article Describes Transition to New Background in WinTerminal
keywords: Terminal Background Update,Change WinTerminal Backdrop,WinTerminal New BG Applied,WinTerminal Color Scheme Switch,WinTerminal Visual Adjustment,Terminal Theme Transition,Update Terminal Appearance
thumbnail: https://thmb.techidaily.com/a55de6d667ce151e4f6994d9b6a4777fce149eccc985ca7253a27ff290bf8c11.jpg
---

## Transition to New Background in WinTerminal

 Changing the background image of the Windows Terminal is an easy way to customize your command line experience. This adds a personal touch and makes your experience visually appealing.

 This tutorial will explain three methods to change the Terminal background image in Windows 11.

## How to Change Windows Terminal Background Image

 You can change the background image of Windows Terminal in three ways: using the**Default** option within the Terminal app or manually editing the settings.json file using**File Explorer** and**Run** dialog box. All three methods achieve the same result and are easy to use.

 Using the default option is the simplest way to change your background image while editing the settings.json file provides more control and customization options. Below, we will guide you through each option.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136620/26400" target="_top" id="2136620">
  <img src="//a.impactradius-go.com/display-ad/26400-2136620" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136620/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Change Windows Terminal Background Image via Its Options

 The easiest way to change the background image of Windows Terminal is by using its option. This can be done by opening Windows Terminal and changing settings within the app. Here's how to do it:

 To get started, open the Windows Terminal application first. For this, click on the Windows icon to open the Start menu. Then type**Terminal** into the search box, and select it from the list.

 Once you open the Terminal application, click on the dropdown menu icon in the top left corner, and select the**Settings** option.

 In the settings window's left column, go to**Defaults** . Now move to the right side of the page and tap**Appearance** to expand it.

![Change Windows Terminal Background Image via Default Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/change-windows-terminal-background-image-via-default-option.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975816/19272" target="_top" id="1975816">
  <img src="//a.impactradius-go.com/display-ad/19272-1975816" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975816/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Scroll down to the**Background image** section, then click the**Background image path** option. Next, click the**Browse** option and select an image you want to use as a background.

 Click**Open** to confirm your selection. Now you should be able to see the selected image as the background of the terminal.

 You can also copy and paste the file path of an image directly into the Background image path option. Finally, click the**Save** button and the background image will be set.

 To improve the appearance of your image in the Windows Terminal, you can customize it using several options. You can use**Background image stretch mode** to change how the image is resized to fill the window. Further, you can change the**Background image alignment** to adjust the image position, and**Background image opacity** to make it more or less transparent.

 Once you are satisfied with the changes, click the**Save** button in order to apply them. Your custom background image should now be visible in the Windows Terminal.

 If you want to switch to the default image,[reset the Windows Terminal to its default settings](https://www.makeuseof.com/windows-11-reset-terminal-settings/) . This will automatically restore your background to the default image.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036472/19272" target="_top" id="2036472">
  <img src="//a.impactradius-go.com/display-ad/19272-2036472" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036472/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123508/26400" target="_top" id="2123508">
  <img src="//a.impactradius-go.com/display-ad/26400-2123508" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123508/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://article-posts.techidaily.com/new-unlocking-windows-high-dynamic-range-potential-for-2024/"><u>[New] Unlocking Windows' High Dynamic Range Potential for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-snap-to-perfection-editing-strategies-that-work-wonders/"><u>[Updated] Snap to Perfection Editing Strategies That Work Wonders</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-from-base-to-brilliance-comparing-gopro-hero5-black-and-hero4-silver/"><u>2024 Approved From Base to Brilliance Comparing GoPro Hero5 Black and Hero4 Silver</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/androids-best-moba-games-roundup-10-edition-for-2024/"><u>Android's Best MOBA Games Roundup - #10 Edition for 2024</u></a></li>
<li><a href="https://win-answers.techidaily.com/beat-pc-crash-woes-with-these-9-effective-tips-for-stable-gameplay-in-ark-survival-evolved/"><u>Beat PC Crash Woes with These 9 Effective Tips for Stable Gameplay in ARK: Survival Evolved</u></a></li>
<li><a href="https://techtrends.techidaily.com/error-resolution-guide-restoring-missing-python24dll-component-in-python/"><u>Error Resolution Guide: Restoring Missing python24.dll Component in Python</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-tune-into-trends-integrating-songs-with-reels/"><u>In 2024, Tune Into Trends Integrating Songs with Reels</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-store-troubleshoot-guide-for-error-x80072f30/"><u>Microsoft Store Troubleshoot Guide for Error X80072F30</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/navigating-privacy-settings-in-apple-music-discover-4-essential-tips-for-a-confidential-audio-journey/"><u>Navigating Privacy Settings in Apple Music: Discover 4 Essential Tips for a Confidential Audio Journey</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-for-inaudible-recordings-while-using-powerpoint/"><u>Remedy for Inaudible Recordings While Using PowerPoint</u></a></li>
<li><a href="https://windows11.techidaily.com/step-into-flexibility-opening-fax-editor-on-windows-11-pcs/"><u>Step Into Flexibility: Opening Fax Editor on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-eradicating-installer-problems-on-windows-11/"><u>Strategies for Eradicating Installer Problems on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/sustained-calculator-visibility-on-windows-os/"><u>Sustained Calculator Visibility on Windows OS</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/the-allure-of-gpt-to-malicious-actors/"><u>The Allure of GPT to Malicious Actors</u></a></li>
<li><a href="https://windows11.techidaily.com/unexplored-avenues-in-windows-11-boost-your-usability/"><u>Unexplored Avenues in Windows 11 - Boost Your Usability</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-and-solving-windows-exit-point-error/"><u>Unraveling and Solving Windows Exit Point Error</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-tips-for-better-mouseclicklock-implementation/"><u>Unveiling Tips for Better MouseClickLock Implementation</u></a></li>
</ul></div>

