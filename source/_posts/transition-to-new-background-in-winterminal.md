---
title: Transition to New Background in WinTerminal
date: 2024-10-25T17:13:47.728Z
updated: 2024-10-30T16:41:35.453Z
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136622/26400" target="_top" id="2136622">
  <img src="//a.impactradius-go.com/display-ad/26400-2136622" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136622/26400" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1061528/11832" target="_top" id="1061528">
  <img src="//a.impactradius-go.com/display-ad/11832-1061528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1061528/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then paste this path into the**backgroundImage** section of settings.json. Remember to include a comma (**,**) after the path, as shown in the image above.

 Once you have pasted the path of your image, save the settings file and close the text editor. To apply this new background image, simply restart your Windows Terminal. The new background image should be displayed on the terminal window.

 You can adjust the image transparency using the same method. Simply input values for the**backgroundImageOpacity** parameters to modify the settings. These additional settings allow you to personalize your Windows Terminal background image even further.

 Restart Windows Terminal for the changes to take effect. In this way, you can easily customize your Windows Terminal background image using the settings.json file.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/2106658/12108" target="_top" id="2106658">
  <img src="//a.impactradius-go.com/display-ad/12108-2106658" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/2106658/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148641/16836" target="_top" id="2148641">
  <img src="//a.impactradius-go.com/display-ad/16836-2148641" border="0" alt="https://techidaily.com" width="254" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148641/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://youtube-webster.techidaily.com/024-approved-voice-of-vogue-establishing-your-channel-in-the-cosmetic-world/"><u>[New] 2024 Approved Voice of Vogue Establishing Your Channel in the Cosmetic World</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-top-webinar-designers-toolset/"><u>2024 Approved Top Webinar Designer's Toolset</u></a></li>
<li><a href="https://android-location-track.techidaily.com/best-anti-tracker-software-for-tecno-pop-8-drfone-by-drfone-virtual-android/"><u>Best Anti Tracker Software For Tecno Pop 8 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-microsofts-phone-link-for-android-usage-guide/"><u>Exploring Microsoft's Phone Link for Android: Usage Guide</u></a></li>
<li><a href="https://media-tips.techidaily.com/home-cinema-evolution-the-ups-and-downs-of-building-your-own-htpc/"><u>Home Cinema Evolution: The Ups and Downs of Building Your Own HTPC</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-7-ways-to-unlock-a-locked-xiaomi-13-ultra-phone-by-drfone-android/"><u>In 2024, 7 Ways to Unlock a Locked Xiaomi 13 Ultra Phone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-passfab-iphone-x-backup-unlocker-top-4-alternatives-by-drfone-ios/"><u>In 2024, PassFab iPhone X Backup Unlocker Top 4 Alternatives</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-top-15-augmented-reality-games-like-pokemon-go-to-play-on-nokia-c110-drfone-by-drfone-virtual-android/"><u>In 2024, Top 15 Augmented Reality Games Like Pokémon GO To Play On Nokia C110 | Dr.fone</u></a></li>
<li><a href="https://fox-glue.techidaily.com/mastering-virtual-worlds-compreenas-top-8-metaverse-headgear/"><u>Mastering Virtual Worlds Compreenas Top 8 Metaverse Headgear</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-between-google-share-and-windows-direct-network-links/"><u>Navigating Between Google Share and Windows Direct Network Links</u></a></li>
<li><a href="https://windows11.techidaily.com/revel-in-easy-entry-unlocking-windows-11s-application-archive/"><u>Revel in Easy Entry: Unlocking Windows 11'S Application Archive</u></a></li>
<li><a href="https://windows11.techidaily.com/seamlessly-blend-windows-11-and-android-top-6-integrative-apps/"><u>Seamlessly Blend Windows 11 and Android: Top 6 Integrative Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-and-overcoming-errorinvalidargument-in-wsl/"><u>Unraveling and Overcoming ERROR_INVALID_ARGUMENT in WSL</u></a></li>
<li><a href="https://windows11.techidaily.com/win-printer-service-reset-guide/"><u>Win Printer Service Reset Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-advanced-integrating-dolby-atmos-support/"><u>Windows 11 Advanced: Integrating Dolby Atmos Support</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-hurdles-apps-with-dull-facades-draining-energy/"><u>Windows 11 Hurdles: Apps With Dull Facades Draining Energy</u></a></li>
<li><a href="https://win-special.techidaily.com/windows-11-users-pay-attention-microsoft-introduces-charges-for-updates-what-youll-need-to-know-about-the-costs/"><u>Windows 11 Users, Pay Attention! Microsoft Introduces Charges for Updates – What You'll Need to Know About the Costs</u></a></li>
</ul></div>

