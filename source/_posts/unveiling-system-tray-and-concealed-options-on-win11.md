---
title: Unveiling System Tray & Concealed Options on Win11
date: 2024-08-08T06:11:15.857Z
updated: 2024-08-09T06:11:15.857Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unveiling System Tray & Concealed Options on Win11
excerpt: This Article Describes Unveiling System Tray & Concealed Options on Win11
keywords: Win11 Tray Access,Hidden Win11 Features,System Tray Windows,Unlocking Win11 UI,Concealed Options Win11,Enhancing Win11 Interface,Explore Win11 Settings
thumbnail: https://thmb.techidaily.com/e1e3cd6b008cdab8aeee33309c0a15674cf83671f125b94d0f79189ce7d24b4f.jpg
---

## Unveiling System Tray & Concealed Options on Win11

 The system tray, which is part of the Taskbar and shows the apps you use frequently, among other things, can become overcrowded.

 If that happens, you can remove a couple of app icons, as well as the hidden icons menu, to make it less cluttered. And if you can’t find the app icons you need or the hidden icons menu is missing, you can add those too.

## How to Show or Hide System Tray Icons on Windows 11

 To show more icons in the system tray, you need to access the Taskbar's settings by pressing **Win + I**, selecting **Personalization** on the left side menu, and then clicking **Taskbar** in the right panel.

![Go to Taskbar Settings in the Personalization Tab of Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/6-go-to-taskbar-settings-in-the-personalization-tab-of-windows-settings-app.jpg)

 In Taskbar settings, scroll down and expand the **Other system tray icons** section. Find the icon you want to show (its toggle will be set to **Off** if it isn’t in the system tray) and click on the toggle on its right to set it to the **On** position.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![you can turn system tray icons on and off in the Taskbar settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-tray-icons-windows-11.jpg)

 If you want to remove the system tray icon, simply set the toggle to **Off**.

 Another way to remove icons from the system tray is to place them in the hidden icons menu. This is the menu that appears when you click the **up caret** icon in the system tray. When the menu is opened, the icon becomes a **down caret**.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
![the hidden icons menu on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hidden-icons-menu-windows-11.jpg)

 To remove an icon from the system tray and place it into the hidden icons menu, click and drag it into the **up caret**. And when you expand the hidden icons menu, you will see that the icon is inside.

 When you remove system tray icons from the settings, they will not appear in the hidden icons menu but will be removed completely.

 To add the icon back in the system tray, click and drag it from the hidden icons menu and then place it in the system tray.

<!-- affiliate ads begin -->

<!-- affiliate ads end -->
## How to Show or Hide the Hidden Icon Menu

 As mentioned earlier, the hidden icon menu is what appears when you click the **up caret** in the system tray. You can also hide and show this menu as you please.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
### Using the Settings App

 If you can't see the hidden icon menu, you can show it from the Taskbar settings as well. To get there, right-click an empty part of the Taskbar and select **Taskbar settings**.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
![opening Taskbar settings by right clicking an empty part of the Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/opening-taskbar-settings.jpg)

 Scroll down until you reach the **Other system tray icons** section and expand it. To reveal the hidden icon menu, set the toggle next to the **Hidden menu icon** option to **On**. To hide it, set the toggle to **Off**.

### Using the Registry Editor

 If you’re not familiar with the Registry Editor, we recommend that you read our guide on [what the Windows Registry is](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) before continuing. It’s crucial that you know what you’re working with before moving forward. Also, be sure to [make a backup of the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) while you're at it.

 With that out of the way, you can open the Registry Editor by pressing **Win + R**, entering **regedit** in the text box, and then clicking on **OK**. In the UAC prompt, click **Yes** to launch the tool.

 For more methods to launch the Registry Editor, please check out our guide on [ways to open the Registry Editor on Windows 11](https://www.makeuseof.com/windows-11-open-registry-editor/).

 Afterward, copy and paste the following path into the address bar of the Registry Editor and hit the **Enter** key:

HKEY_CURRENT_USER\Software\Classes\Local Settings\Software\Microsoft\Windows\CurrentVersion\TrayNotify

 Next, double-click the **SystemTrayChevronVisibility** value in the right panel.

![the SystemTrayChevronVisibility value in the Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/systemtraychevronvisibility-value-regedit-windows.jpg)

 To show the hidden icon menu, set the **Value data** text box to **1** and click **OK**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
![setting the SystemTrayChevronVisibility value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/systemtraychevronvisibility-value-data.jpg)

 And to hide the hidden icon menu set the **Value data** text box to **0** and click **OK**.

## Control the Icons that Appear in the System Tray on Windows 11

 Whether you want to add icons or remove them from the system tray, the process is simple. Just go to the Taskbar settings and turn them on or off as needed. You can also hide or show the hidden icon menu in the process.

 And if you want to show or hide the clock and date in the system tray, you can do that too.

 If that happens, you can remove a couple of app icons, as well as the hidden icons menu, to make it less cluttered. And if you can’t find the app icons you need or the hidden icons menu is missing, you can add those too.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-exploring-youtubes-strategy-for-video-short-promotion/"><u>[New] 2024 Approved  Exploring YouTube's Strategy for Video Short Promotion</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-swift-seize-video-with-soundtracking/"><u>[New] 2024 Approved  Swift Seize  Video with Soundtracking</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-does-immediate-subscribing-affect-content-recommendations-in-2024/"><u>[New] Does Immediate Subscribing Affect Content Recommendations, In 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-key-techniques-for-smooth-screen-sharing-on-mobiledesktop-for-2024/"><u>[New] Key Techniques for Smooth Screen Sharing on Mobile/Desktop for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-2024-approved-amped-arcs-and-zigzags-in-olympic-speed/"><u>[Updated] 2024 Approved  Amped Arcs & Zigzags in Olympic Speed</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-elevate-your-photos-utilizing-luts-in-adobes-image-editor/"><u>[Updated] 2024 Approved  Elevate Your Photos  Utilizing LUTs in Adobe's Image Editor</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-quickshot-flipslow-mpeg/"><u>[Updated] QuickShot FlipSlow MPEG</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-subscription-made-simple-building-a-user-friendly-button-for-channels/"><u>[Updated] Subscription Made Simple  Building a User-Friendly Button for Channels</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-the-essential-guide-to-blur-techniques-for-dynamic-artwork/"><u>[Updated] The Essential Guide to Blur Techniques for Dynamic Artwork</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-essential-photography-top-10-watermark-software/"><u>2024 Approved  Essential Photography  Top 10 Watermark Software</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-optimal-steadicam-devices-for-professional-drone-cinematography/"><u>2024 Approved  Optimal Steadicam Devices for Professional Drone Cinematography</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-mouse-click-agility-nine-strategies-to-tweak-speeds/"><u>Boost Mouse Click Agility: Nine Strategies to Tweak Speeds</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-windows-11-performance-run-command-upgrade-guide/"><u>Boosting Windows 11 Performance: Run Command Upgrade Guide</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-oppo-reno-10-5g-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Oppo Reno 10 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/convenient-methods-for-local-policies-on-windows-11/"><u>Convenient Methods for Local Policies on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-capabilities-directories-with-a-click-in-win11/"><u>Crafting Capabilities: Directories with a Click in Win11</u></a></li>
<li><a href="https://article-posts.techidaily.com/create-brand-symbols-from-templates-at-no-cost/"><u>Create Brand Symbols From Templates at No Cost</u></a></li>
<li><a href="https://windows11.techidaily.com/creating-a-dual-disk-on-windows-independently/"><u>Creating a Dual Disk on Windows, Independently</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-high-cpu-usage-techniques-from-windows-resource-monitor/"><u>Decoding High CPU Usage: Techniques From Windows Resource Monitor</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-to-create-a-personalized-windows-text-recognition-program/"><u>Easy Steps to Create a Personalized Windows Text Recognition Program</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-classics-to-full-hd-perfection-with-windows-and-scummvm-expertise/"><u>Elevate Classics to Full HD Perfection with Windows & ScummVM Expertise</u></a></li>
<li><a href="https://android-unlock.techidaily.com/full-guide-to-unlock-your-motorola-razr-40-by-drfone-android/"><u>Full Guide to Unlock Your Motorola Razr 40</u></a></li>
<li><a href="https://windows11.techidaily.com/halt-spotifys-autoplay-behavior-on-pc/"><u>Halt Spotify's Autoplay Behavior on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-increase-disk-size-in-windows-carefully/"><u>How to Increase Disk Size in Windows Carefully</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-pictures-from-vivo-y78plus-by-fonelab-android-recover-pictures/"><u>How to recover deleted pictures from Vivo Y78+.</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-card-on-nubia-red-magic-9-proplus-online-without-jailbreak-by-drfone-android/"><u>In 2024, How to Unlock SIM Card on Nubia Red Magic 9 Pro+ online without jailbreak</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-memorable-moments-downloading-tweets-emotive-graphics/"><u>In 2024, Memorable Moments  Downloading Tweets’ Emotive Graphics</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-steam-library-synchronization-hitches/"><u>Navigating Through Steam Library Synchronization Hitches</u></a></li>
<li><a href="https://windows11.techidaily.com/reconciling-windows-game-bar-with-inferior-hardware/"><u>Reconciling Windows Game Bar with Inferior Hardware</u></a></li>
<li><a href="https://techidaily.com/remove-infinix-lock-screen-without-password-infinix-note-30-vip-by-drfone-android-unlock-android-unlock/"><u>Remove Infinix Lock Screen without Password(Infinix Note 30 VIP)</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-lost-nvidia-configuration-a-guide-for-winx-users/"><u>Restoring Lost NVIDIA Configuration: A Guide for WinX Users</u></a></li>
<li><a href="https://windows11.techidaily.com/revitalizing-fall-guys-gaming-experience-after-disconnections-on-windows/"><u>Revitalizing Fall Guys Gaming Experience After Disconnections on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionize-your-security-crafting-unique-lock-patterns-for-windows-11/"><u>Revolutionize Your Security: Crafting Unique Lock Patterns for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/silencing-the-cacophony-soundcard-irq-fixes/"><u>Silencing the Cacophony: Soundcard IRQ Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/split-screen-style-selecting-separate-themes-for-each-windows-display/"><u>Split Screen Style: Selecting Separate Themes for Each Windows Display</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-disabling-onedrive-icon-on-windows-11-explore/"><u>Strategies for Disabling OneDrive Icon on Windows 11 Explore</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-image-enhancement-building-engaging-slideshows-and-fixing-windows-11-photo-flaws/"><u>The Art of Image Enhancement: Building Engaging Slideshows & Fixing Windows 11 Photo Flaws</u></a></li>
<li><a href="https://windows11.techidaily.com/the-complete-gamers-manual-to-winning-with-windows/"><u>The Complete Gamers' Manual to Winning With Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-list-of-6-performance-monitor-apps-for-pcs/"><u>The Ultimate List of 6 Performance Monitor Apps For PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/tricks-save-and-access-onedrive-around-clients/"><u>Tricks: Save & Access OneDrive Around Clients</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-11-eliminating-invisible-logins/"><u>Troubleshooting Windows 11: Eliminating Invisible Logins</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/standing-and-proficiently-implementing-cc-copyrights-for-2024/"><u>Understanding and Proficiently Implementing CC Copyrights for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-code-0x0001-complication-in-windows-11/"><u>Unraveling Code 0X0001 Complication in Windows 11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/when-should-you-share-your-insta-story/"><u>When Should You Share Your Insta Story?</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-resizing-discover-the-top-six-efficient-methods/"><u>Windows 11 Resizing: Discover the Top Six Efficient Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-elevate-with-25-customization-tips/"><u>Windows 11: Elevate with 25 Customization Tips</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>