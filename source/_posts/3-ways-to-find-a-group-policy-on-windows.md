---
title: 3 Ways to Find a Group Policy on Windows
date: 2024-08-15T15:55:36.547Z
updated: 2024-08-16T15:55:36.547Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 3 Ways to Find a Group Policy on Windows
excerpt: This Article Describes 3 Ways to Find a Group Policy on Windows
keywords: Windows Group Policy Guide,Policy Finder in WinOS,Windows PC Policies Locate,Navigating WinGroup Settings,Group Policy Search Tips,Find Windows Policy Changes,Windows Security Policy Tools,Group Policy Guide Windows,Find WinOS Policies,Locate PC Policies Win,Navigate WinGroup Settings,Tips Search Group Win,Change Windows Policies,Tools Secure WinPolicy
thumbnail: https://thmb.techidaily.com/a6435a313e4469213bebd5ae38a7530a7b0364be00feda91bc9b60c48edb8ed3.jpg
---

## 3 Ways to Find a Group Policy on Windows

 Changing a group policy is something that many Windows users will have to do at some point in their life. However, knowing the path to a particular setting in the Local Group Policy Editor (LGPE) is not so simple, considering the sheer scale of the folders and subfolders within the tool.

 In this guide, we're going to show you three ways to search for the group policies you need so you don't get lost.

## 1\. Search Using the Local Group Policy Editor's Filter Option

 Press **Win + S** to bring up Windows Search, search for **edit group policy**, and click on **Edit group policy** in the search results. This will launch the LGPE.

 Only the Pro and Enterprise editions of Windows come with the LGPE pre-installed, but there is a way you can [access the LGPE on Home editions](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 In the left pane, right-click the **Administrative Templates** folder (it's the only folder that allows you to search this way), and click **Filter On** to enable filtering. Right-click the folder again, and this time, select **Filter Options**.

![the menu that shows up when you right-click Administrative Templates in the Loca Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/lgpe-search-filter-option.jpg)

 In the Filter Options dialog box, make sure to check the **Enable Keyword Filters** checkbox. Next, in the text box next to **Filter for word(s)**, enter the search terms for the policy or, if you know it, the exact name of the policy.

![the Filter Options dialog box with the Enable Keywords and filter text box part showing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/lgpe-search-filter-options-search-phrase-windows.jpg)

 In the dropdown next to that filter text box, you can choose the following options:

* **Any**: The policy you’re searching for contains one or more of the words entered in the filter text box.
* **All**: The policy you’re searching for contains each word entered in the filter text box.
* **Exact**: The policy you're searching for contains the exact phrase entered in the filter text box.

 Next, check the **Enable Requirement Filters** checkbox and click the **Select All** button (this means you want to search for the policy on all platforms). Then, click **OK**.

![the Filter Options dialog box showing the requirements section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/lgpe-search-filter-option-requirements-filters.jpg)

 Back in the LGPE, you should start to see the folders and policies decrease in number since others have been filtered out. To quickly find the policy you were searching for, click **All Settings**.

![All Settings selected in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/lgpe-search-filter-results-windows.jpg)

 While editing, keep in mind that changing the right [group policies can make your PC better](https://www.makeuseof.com/tag/12-ways-windows-group-policy-can-make-pc-better/), or, if you tweak the wrong one, make it worse.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Search Using the Group Policy Website

 Besides using filters in the LGPE, you can also use the [Group Policy Search](https://gpsearch.azurewebsites.net/) website. While on the site, click the **filter icon** in the top left corner and uncheck all the products you don’t want to include in the search.

![filtering out products on the Group Policy Search website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/gps-website-filters.jpg)

 Click on the search box at the top, enter the search terms for the policy, and hit the **Enter** key. If you want to do an exact search, be sure to put the search string within quotes, like “disable context menu,” for example.

![searching for a group policy on the Group Policy Search website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/gps-website-searching-policy.jpg)
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The search policy will appear in the second column, so click on it to reveal more information about it in a pop-up. You will see where to find the policy in the LGPE directly under the heading.

![the search results on the Group Policy Search website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/gps-website-searching-policy-results.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->

 Where it says **Key**, you can see where to find the setting in the Registry Editor.

## 3\. Search Using the Group Policy Settings Reference

 If you prefer something offline and a little easier to access compared to searching with the LGPE's filters and the Group Policy Search website, Microsoft has a document you can use. So, download the [Group Policy Settings Reference](https://www.microsoft.com/en-us/download/details.aspx?id=25250) sheet and open it in Excel.

 To search for a policy, click on the **filter icon** next to the **Policy Setting Name** heading in the **C** column. In the text box that says **Search**, type in search terms for the policy you want to find, and then hit the **Enter** key.

![searching the group policy reference sheet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/group-policy-reference-sheet-text-filter.jpg)
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35408920&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/FR-200-1.png" border="0">Glarysoft File Recovery Pro - Helps to recover your lost file/data, even permanently deleted data. </a>
<!-- affiliate ads end -->

 The policies that match the search terms will appear in column **C**. You can find the location of the policy in column **E** under the **Policy Path** heading.

![the results of searching for a group policy in the reference sheet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/group-policy-reference-sheet-policy-path.jpg)
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 That’s the folder you need to look at in the LGPE to find the policy that you need to edit.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
## Find the Group Policy You Need on Windows

 Now you should be able to find the group policies you need to make your PC better. We know how overwhelming it can be to use the Local Group Policy Editor, but with these tools, it should become a little easier. And if your edits don't take effect right away, there’s a way for you to manually refresh the LGPE to apply the settings immediately.

 In this guide, we're going to show you three ways to search for the group policies you need so you don't get lost.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-screen-separation-assessing-splitcams-leadership/"><u>[New] 2024 Approved  Screen Separation  Assessing SplitCam's Leadership</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-best-apps-for-3d-video-intros-on-social-platforms-for-2024/"><u>[New] Best Apps for 3D Video Intros on Social Platforms for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-elite-psd-fill-and-stroke-effects/"><u>[New] Elite PSD Fill & Stroke Effects</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-exploring-6-exquisite-eastern-themed-homes-in-mc-for-2024/"><u>[New] Exploring 6 Exquisite Eastern Themed Homes in MC for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-from-ordinary-to-outstanding-photos-ios-and-androids-leading-sticker-adders/"><u>[New] From Ordinary to Outstanding Photos  IOS & Android's Leading Sticker Adders</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-professional-choices-the-very-best-8-tripods-for-4k/"><u>[New] Professional Choices  The Very Best 8 Tripods for 4K</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-superior-mac-capture-apps-different-than-bandicam-for-2024/"><u>[New] Superior Mac Capture Apps, Different Than Bandicam for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-youtube-to-webm-the-10-best-youtube-to-webm-converters/"><u>[New] YouTube to WebM  The 10 Best YouTube to WebM Converters</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-10plus-leading-web-based-screen-capture-tools-for-2024/"><u>[Updated] 10+ Leading Web-Based Screen Capture Tools for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-best-online-deals-on-webcam-protection-kits-for-2024/"><u>[Updated] Best Online Deals on Webcam Protection Kits for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-conquering-competition-crafting-standout-youtube-advertising-banners-for-2024/"><u>[Updated] Conquering Competition  Crafting Standout YouTube Advertising Banners for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-effortless-integration-uploading-and-showcasing-imovie-videos-to-vimeo-for-2024/"><u>[Updated] Effortless Integration  Uploading and Showcasing iMovie Videos to Vimeo for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-how-user-generated-feedback-influences-video-ranks/"><u>[Updated] In 2024, How User-Generated Feedback Influences Video Ranks</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-in-2024-instagram-stories-mastering-the-art-of-time-manipulation/"><u>[Updated] In 2024, Instagram Stories – Mastering the Art of Time Manipulation</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-a-comprehensible-approach-to-masterful-gopro-studio-edits/"><u>2024 Approved  A Comprehensible Approach to Masterful GoPro Studio Edits</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-boxing-vs-streaming-ultimate-showdown/"><u>2024 Approved  Boxing vs Streaming  Ultimate Showdown</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/2024-approved-whats-your-potential-income-from-youtube-sponsored-videos/"><u>2024 Approved  What's Your Potential Income From YouTube Sponsored Videos?</u></a></li>
<li><a href="https://location-social.techidaily.com/3-things-you-must-know-about-fake-snapchat-location-on-realme-narzo-60x-5g-drfone-by-drfone-virtual-android/"><u>3 Things You Must Know about Fake Snapchat Location On Realme Narzo 60x 5G | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/a-step-by-step-manual-for-stunning-slow-motion-with-gopro-hero-10/"><u>A Step-by-Step Manual for Stunning Slow Motion with GoPro Hero 10</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-non-compliance-overcoming-intel-hd-graphics-errors/"><u>Addressing Non-Compliance: Overcoming Intel HD Graphics Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-error-code-x80131500-at-store/"><u>Breaking Down Error Code: X80131500 at Store</u></a></li>
<li><a href="https://windows11.techidaily.com/command-prompt-oddities-learn-5-amusing-anomalies/"><u>Command Prompt Oddities: Learn 5 Amusing Anomalies</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-rectify-windows-security-faults/"><u>Comprehensive Guide to Rectify Windows Security Faults</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/comprehensive-toshiba-55lf711u20-55-fire-tv-edition-guide-a-top-pick-for-prime-subscribers/"><u>Comprehensive Toshiba 55LF711U20 55 Fire TV Edition Guide - A Top Pick for Prime Subscribers</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-dream-team-top-windows-apps-for-a-winning-start/"><u>Digital Dream Team: Top Windows Apps for a Winning Start</u></a></li>
<li><a href="https://windows11.techidaily.com/discreetly-putting-an-end-to-invisible-window-tasks/"><u>Discreetly Putting an End to Invisible Window Tasks</u></a></li>
<li><a href="https://review-topics.techidaily.com/edit-and-send-fake-location-on-telegram-for-your-xiaomi-redmi-k70-pro-in-3-ways-drfone-by-drfone-virtual-android/"><u>Edit and Send Fake Location on Telegram For your Xiaomi Redmi K70 Pro in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-data-retrieval-how-to-master-the-art-of-qr-scanning-with-windows/"><u>Effortless Data Retrieval: How to Master the Art of QR Scanning with Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-hidden-programs-on-windows-pc/"><u>Enabling Hidden Programs on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-smart-color-settings-in-windows-11-apps/"><u>Enabling Smart Color Settings in Windows 11 Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-real-time-performance-for-smooth-vlc-viewing/"><u>Enhancing Real-Time Performance for Smooth VLC Viewing</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-using-windows-11s-compatibility-fixer/"><u>Essential Guide to Using Windows 11’S Compatibility Fixer</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-for-diablo-gameplay-enthusiasts/"><u>Essential Tips for Diablo Gameplay Enthusiasts</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-to-fully-erase-wsl-from-windows-11-systems/"><u>Expert Tips to Fully Erase WSL From Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-a-non-compatible-device-after-windows-11-installation/"><u>Fixing a Non-Compatible Device After Windows 11 Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-correctly-handle-iomap64sys-failures-in-winos/"><u>How To Correctly Handle IOMap64.sys Failures in WinOS</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reset-freezes-and-crashes-in-virtual-worlds/"><u>How to Reset Freezes & Crashes in Virtual Worlds</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-apple-iphone-11-pro-apples-new-iphone-drfone-by-drfone-ios/"><u>How to Unlock Apple iPhone 11 Pro, Apples New iPhone | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/huggingchat-or-chatgpt-analyzing-which-ai-leads-in-natural-language-processing/"><u>HuggingChat or ChatGPT? Analyzing Which AI Leads in Natural Language Processing</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-google-pixel-fold-by-drfone-android/"><u>In 2024, AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Google Pixel Fold</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-hacks-to-do-pokemon-go-trainer-battles-for-tecno-spark-20c-drfone-by-drfone-virtual-android/"><u>In 2024, Hacks to do pokemon go trainer battles For Tecno Spark 20C | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-master-live-broadcast-a-step-by-step-guide-to-recording-webcam-via-vlc/"><u>In 2024, Master Live Broadcast  A Step-by-Step Guide to Recording Webcam via VLC</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-mastering-design-principles-essential-knowledge-of-yt-banners-and-art/"><u>In 2024, Mastering Design Principles  Essential Knowledge of YT Banners & Art</u></a></li>
<li><a href="https://windows11.techidaily.com/introducing-real-space-sound-on-windows-11/"><u>Introducing Real-Space Sound on Windows 11</u></a></li>
<li><a href="https://techidaily.com/is-your-tecno-spark-10-5g-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Tecno Spark 10 5G working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/master-the-art-of-iphone-image-rotation-effortless-methods-for-2024/"><u>Master the Art of iPhone Image Rotation - Effortless Methods for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/motorola-razr-40-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>Motorola Razr 40 ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-experience-adding-uninstall-shortcut-in-windows-10/"><u>Optimize Your Experience: Adding Uninstall Shortcut in Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-corruption-unlock-write-permissions-in-win10win11/"><u>Overcoming Corruption: Unlock Write Permissions in Win10/Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-roadblocks-activating-non-functional-scripts-in-windows/"><u>Overcoming Roadblocks: Activating Non-Functional Scripts in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-browser-security-incorporating-trusted-websites-in-windows-11/"><u>Personalize Browser Security: Incorporating Trusted Websites in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-chromeedge-from-hiding-taskbar-on-large-screens/"><u>Preventing Chrome/Edge From Hiding Taskbar on Large Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-removing-isdonedll-malfunctions-from-windows-11/"><u>Quick Guide: Removing ISDone.dll Malfunctions From Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-failed-zip-operations-on-win-11-system/"><u>Recovering Failed ZIP Operations on Win 11 System</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-robustness-of-ccleaner-on-your-win11-pc/"><u>Recovering Robustness of CCleaner on Your Win11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/safekeep-your-files-setting-up-folder-restrictions-in-windows-11/"><u>Safekeep Your Files: Setting Up Folder Restrictions in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-window-11s-missing-clickables-problem/"><u>Solving Window 11'S Missing Clickables Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharge-efficiency-select-windows-software-for-success/"><u>Supercharge Efficiency: Select Windows Software for Success</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-error-0x80042306-on-windows-to-reset-successfully/"><u>Tackling Error 0X80042306 on Windows to Reset Successfully</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-unblock-application-packages-on-windows-servers/"><u>Techniques to Unblock Application Packages on Windows Servers</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-tab-navigation-windows-11-enhanced-guide/"><u>The Art of Tab Navigation: Windows 11 Enhanced Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/top-4-microcomputers-pure-windows-environment/"><u>Top 4 Microcomputers: Pure Windows Environment</u></a></li>
<li><a href="https://games-able.techidaily.com/vision-meets-movement-in-game-setups/"><u>Vision Meets Movement in Game Setups</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-are-location-permissions-life360-on-oneplus-nord-ce-3-lite-5g-drfone-by-drfone-virtual-android/"><u>What are Location Permissions Life360 On OnePlus Nord CE 3 Lite 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-insider-clandestine-context-creation-techniques/"><u>Windows 11 Insider: Clandestine Context Creation Techniques</u></a></li>
</ul></div>
