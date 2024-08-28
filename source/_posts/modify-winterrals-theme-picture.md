---
title: Modify WinTerral's Theme Picture
date: 2024-08-27T16:02:07.983Z
updated: 2024-08-28T16:02:07.983Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Modify WinTerral's Theme Picture
excerpt: This Article Describes Modify WinTerral's Theme Picture
keywords: Terral Theme Image Edit,Change WinTerral Design,Customize Terral Look,Update Terral Photo,Alter Terral Visuals,Redesign WinTerral Pics,Reimagine WinTerral Art
thumbnail: https://thmb.techidaily.com/42e80c71c3e676d07f669fb711246bda708f83a958555a8cf5d9869ea65371d4.jpg
---

## Modify WinTerral's Theme Picture

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
 Then paste this path into the**backgroundImage** section of settings.json. Remember to include a comma (**,**) after the path, as shown in the image above.

 Once you have pasted the path of your image, save the settings file and close the text editor. To apply this new background image, simply restart your Windows Terminal. The new background image should be displayed on the terminal window.

 You can adjust the image transparency using the same method. Simply input values for the**backgroundImageOpacity** parameters to modify the settings. These additional settings allow you to personalize your Windows Terminal background image even further.

 Restart Windows Terminal for the changes to take effect. In this way, you can easily customize your Windows Terminal background image using the settings.json file.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
5. Then press**Ctrl + S** on your keyboard to save the changes.
6. Close Notepad, then open Windows Terminal to see your new background image.

 You’re done! Now you know how to customize your Windows Terminal background image using the Run Command tool. You can further explore the settings.json file or use other tools to[customize and personalize your Windows Terminal](https://www.makeuseof.com/windows-terminal-customization/) .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537546&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/7_copy_2_2_hdpro.png" border="0">HD Video Converter Factory Pro</a>
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
<li><a href="https://fox-direct.techidaily.com/updated-building-a-winning-portfolio-with-windows-11-video-editing-skills-for-2024/"><u>[Updated] Building a Winning Portfolio with Windows 11 Video Editing Skills for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-discovering-if-muted-on-snapstreak/"><u>[Updated] Discovering If Muted on Snapstreak</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-the-drone-that-never-loses-you-top-10-list/"><u>[Updated] The Drone that Never Loses You - Top 10 List</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-from-beginner-to-expert-with-a-complete-fcp-guidebook/"><u>2024 Approved  From Beginner to Expert with a Complete FCP Guidebook</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-the-impact-and-innovations-in-vegaspro-a-2019-review/"><u>2024 Approved  The Impact and Innovations in VegasPro  A 2019 Review</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/essential-android-ad-blocking-the-top-7-app-list-for-2024/"><u>Essential Android Ad Blocking  The Top 7 App List for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-failed-steam-remote-links-on-pc/"><u>Fixing Failed Steam Remote Links on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-outlooks-restricted-folder-access-on-desktop-computers/"><u>Fixing Outlook's Restricted Folder Access on Desktop Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/halt-high-contrast-customization-in-windows/"><u>Halt High Contrast Customization in Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-android-unlock-code-sim-unlock-your-tecno-camon-30-pro-5g-phone-and-remove-locked-screen-by-drfone-android/"><u>In 2024, Android Unlock Code Sim Unlock Your Tecno Camon 30 Pro 5G Phone and Remove Locked Screen</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlocking-made-easy-the-best-10-apps-for-unlocking-your-vivo-t2-pro-5g-device-by-drfone-android/"><u>In 2024, Unlocking Made Easy The Best 10 Apps for Unlocking Your Vivo T2 Pro 5G Device</u></a></li>
<li><a href="https://windows11.techidaily.com/integrate-your-windows-fileshare-seamlessly/"><u>Integrate Your Windows Fileshare Seamlessly</u></a></li>
<li><a href="https://windows11.techidaily.com/keeping-winrunhist-intact-for-future-use/"><u>Keeping WinRunHist Intact for Future Use</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windowed-discords-search-tweaks/"><u>Mastering Windowed Discord's Search Tweaks</u></a></li>
<li><a href="https://windows11.techidaily.com/method-to-modify-display-settings/"><u>Method to Modify Display Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-fix-windows-update-code-error-0x8024800c/"><u>Methods to Fix Windows Update: Code Error 0X8024800C</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/multilingualism-made-easy-with-media-content/"><u>Multilingualism Made Easy with Media Content</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-top-cartoon-animation-software-for-mobile-devices/"><u>New In 2024, Top Cartoon Animation Software for Mobile Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/optimized-browsing-the-least-ram-and-cpu-hungry-on-all-major-operating-systems/"><u>Optimized Browsing: The Least RAM & CPU-Hungry On All Major Operating Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-discrepancy-in-windows-11s-power-life-predictor/"><u>Overcoming Discrepancy in Windows 11'S Power Life Predictor</u></a></li>
<li><a href="https://windows11.techidaily.com/perfect-visuals-your-guide-to-leveraging-background-blur-on-windows-11-photos-app/"><u>Perfect Visuals: Your Guide to Leveraging Background Blur on Windows 11 Photos App</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-your-powerpoint-presentations-printouts-on-windows-platforms/"><u>Perfecting Your PowerPoint Presentations' Printouts on Windows Platforms</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/propel-your-video-writes-the-ai-way-for-2024/"><u>Propel Your Video' Writes  The AI Way for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-route-to-your-windows-disk-space-win-1011/"><u>Quick Route to Your Windows Disk Space (Win 10/11)</u></a></li>
<li><a href="https://windows11.techidaily.com/re-estaminig-balanced-sound-from-both-sides-of-win-audio-device/"><u>Re-Estaminig Balanced Sound From Both Sides of Win Audio Device</u></a></li>
<li><a href="https://windows11.techidaily.com/safe-journey-in-windows-11-the-top-8-slippery-slope/"><u>Safe Journey in Windows 11: The Top 8 Slippery Slope</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-non-responsive-windows-shift/"><u>Solutions for Non-Responsive Windows Shift.</u></a></li>
<li><a href="https://windows11.techidaily.com/systematic-success-guiding-through-windows-11-renewal/"><u>Systematic Success: Guiding Through Windows 11 Renewal</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-managing-windows-users-via-cli/"><u>The Art of Managing Windows Users via CLI</u></a></li>
<li><a href="https://windows11.techidaily.com/the-intricate-world-of-user-identification-in-win11/"><u>The Intricate World of User Identification in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/top-8-compatible-windows-and-android-programs/"><u>Top 8 Compatible Windows and Android Programs</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-contacts-from-infinix-zero-30-5g-by-fonelab-android-recover-contacts/"><u>Undelete lost contacts from Infinix Zero 30 5G.</u></a></li>
<li><a href="https://windows11.techidaily.com/unfreeze-shift-button-on-your-pc/"><u>Unfreeze Shift Button on Your PC.</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secret-recognizing-and-resolving-non-installed-hdd-issue-win-11-style/"><u>Unveiling the Secret: Recognizing & Resolving Non-Installed HDD Issue, Win 11 Style</u></a></li>
<li><a href="https://windows11.techidaily.com/upgrade-video-quality-from-yesteryears-using-madvr-windows-edition/"><u>Upgrade Video Quality From Yesteryears Using MadVR, Windows Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/wake-up-call-reviving-sleeping-pcs-with-inputs-on-1011/"><u>Wake-Up Call: Reviving Sleeping PCs with Inputs on 10/11</u></a></li>
<li><a href="https://change-location.techidaily.com/which-pokemon-can-evolve-with-a-moon-stone-for-samsung-galaxy-a14-5g-drfone-by-drfone-virtual-android/"><u>Which Pokémon can Evolve with a Moon Stone For Samsung Galaxy A14 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/why-windows-supercomputers-are-game-changers/"><u>Why Windows Supercomputers Are Game-Changers</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-arp-cache-explained-clears-and-management/"><u>Windows ARP Cache Explained: Clears & Management</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-back-your-disconnected-wi-fi/"><u>Winning Back Your Disconnected Wi-Fi</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-the-game-of-cutting-top-8-video-edits-for-pc/"><u>Winning the Game of Cutting: Top 8 Video Edits for PC</u></a></li>
<li><a href="https://windows11.techidaily.com/wintools-comparison-how-chkdsk-and-sfc-differ-from-dissect/"><u>WinTools Comparison: How CHKDSK and SFC Differ From Dissect</u></a></li>
</ul></div>
