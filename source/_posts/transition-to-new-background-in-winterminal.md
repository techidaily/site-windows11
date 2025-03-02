---
title: Transition to New Background in WinTerminal
date: 2025-02-24T23:51:21.170Z
updated: 2025-03-02T09:07:48.827Z
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
<li><a href="https://fox-links.techidaily.com/updated-clipcomposer-critique-thorough-examination-for-2024/"><u>[Updated] ClipComposer Critique – Thorough Examination for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-contacts-files-on-galaxy-z-fold-5-by-fonelab-android-recover-contacts/"><u>Complete guide for recovering contacts files on Galaxy Z Fold 5.</u></a></li>
<li><a href="https://win11.techidaily.com/guarantee-stable-performance-of-your-windows-ui/"><u>Guarantee Stable Performance of Your Window's UI</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-additional-tips-about-sinnoh-stone-for-vivo-y100t-drfone-by-drfone-virtual-android/"><u>In 2024, Additional Tips About Sinnoh Stone For Vivo Y100t | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-the-secret-to-social-success-innovative-square-videography-tactics/"><u>In 2024, The Secret to Social Success Innovative Square Videography Tactics</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-uninterrupted-video-with-proper-obs-settings/"><u>In 2024, Uninterrupted Video with Proper OBS Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-admin-access-unlocking-windows-control-panel/"><u>Mastering Admin Access: Unlocking Windows Control Panel</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-your-gaming-setup-for-valorants-peak-performance/"><u>Optimizing Your Gaming Setup for Valorant's Peak Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/pathfinders-guide-unveiling-the-sixest-steps-for-copying-windows-11-file-and-folders/"><u>Pathfinder's Guide: Unveiling the Sixest Steps for Copying Windows 11 File & Folders</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-data-corruption-in-win11-os/"><u>Remedying Data Corruption in Win11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-utorrent-setup-failures-on-windows-systems/"><u>Resolving uTorrent Setup Failures on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-workflows-microsoft-to-do-plus-ifttt/"><u>Streamline Your Workflows: Microsoft To-Do + IFTTT</u></a></li>
<li><a href="https://games-able.techidaily.com/the-science-behind-xboxs-strike-process/"><u>The Science Behind Xbox's Strike Process</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-your-photos-innovative-erase-on-windows/"><u>Transform Your Photos: Innovative Erase on Windows</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unlocking-tech-secrets-the-ultimate-resource-for-hardware-enthusiasts-at-toms-review/"><u>Unlocking Tech Secrets: The Ultimate Resource for Hardware Enthusiasts at Tom's Review</u></a></li>
</ul></div>

