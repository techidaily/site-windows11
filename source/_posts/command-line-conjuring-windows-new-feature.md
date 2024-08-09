---
title: "Command Line Conjuring: Windows' New Feature"
date: 2024-08-08T06:00:38.390Z
updated: 2024-08-09T06:00:38.390Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Command Line Conjuring: Windows' New Feature"
excerpt: "This Article Describes Command Line Conjuring: Windows' New Feature"
keywords: Command Line Magic,Window's CLI Tools,Windows Console Tricks,Cmdline Interface Enhancements,PowerShell Wizardry,Terminal Feature Updates,WinCLI Capabilities
thumbnail: https://thmb.techidaily.com/bbc14b435660c967866cf3c17d84e88db2c1688390de1d8678d61e0a94d5c4d0.png
---

## Command Line Conjuring: Windows' New Feature

 God Mode enables you to access hundreds of Control Panel applets from a single All Tasks window. That’s a handy thing to activate in Windows 11 for accessing Control Panel settings and creating shortcuts that open them.

 Many users activate God Mode by setting up desktop shortcuts that open the All Tasks window. However, you can instead add a **God Mode** option to the desktop’s context menu in Windows 11\. Then the All Tasks window will be directly accessible on your right-click menu. This is how you can add God Mode to Windows 11’s context menu.

## How to Add God Mode to the Context Menu by Manually Editing the Registry

 You can add God Mode to Windows 11’s desktop context menu by manually tweaking the registry. The tweaking required is relatively simple to apply and involves adding a couple of new registry entries to the Shell key. Follow these steps to manually add God Mode to Windows 11’s context menu:

1. Open the Registry Editor (see [how to open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) for instructions).
2. Click in the address bar at the top of Registry Editor to delete the current key location.
3. Input this Shell key path in the address bar and hit **Enter**:  
`Computer\HKEY_CLASSES_ROOT\DesktopBackground\Shell\`
4. Right-click on **Shell** in Registry Editor’s navigation sidebar to select **New** and **Key**.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/new-key-options.jpg)
5. Type **God Mode** in the key’s text box.

1. Right-click **God Mode** and select the **New** \> **Key** context menu options again.
2. Input **command** within the subkey’s text box.  
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The God Mode registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/god-mode-key.jpg)
3. Double-click on the **(Default)** string for the new command key you’ve added to the registry.
4. Input **explorer** **shell:::{ED7BA470-8E54-465E-825C-99712043E01C}** within the **Data value** box and click **OK**.  
![The Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-string-window.jpg)
5. Click on the Registry Editor’s **X** button.

 Check out the new **God Mode** option on your context menu for opening Task View. Right-click somewhere on the desktop background image and select **Show more options**. Then select **God Mod** to bring up the **Task View** window. You can open a multitude of Control Panel applets from there.

![A God Mode context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/god-mode-option.jpg)

 If you ever change your mind about having a **God Mode** context menu option, open the Shell key in Registry Editor again. Then right-click on the **God Mode** key you added and select delete. Click **Yes** to erase the **God Mode** key along with its **command** subkey.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-delete-option.jpg)

## How to Add God Mode to the Context Menu With Right-Click Extender

 The manual registry tweak method is straightforward, but you can add God Mode to the context menu with third-party software instead if preferred. Right-Click Extender is customization software that includes an option for adding God Mode to the context menu. This is how you can add God Mode to your context menu with Right-Click Extender:

1. Open this [Right-Click Extender](https://www.softpedia.com/get/Tweak/System-Tweak/Right-Click-Extender.shtml) download page.
2. Click on the **Download** and **Secure Download (US)** options and download the file.
3. Extract the Right-Click Extender archive by following the instructions within this guide to [unzipping ZIP files in Windows](https://www.makeuseof.com/unzip-files-windows-10/).  
![The Extract Compressed (Zipped) Folders window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/extract-compressed-zip-folder.jpg)
4. Open the extracted Right-Click Extender directory and its Right-Click Extender v2 subfolder.
5. Double-click the Right-Click Extender v2 application file.
6. Click on the **Desktop** tab in Right-Click Extender.
7. Select the **All Tasks (GodMode)** setting and its Icon checkbox.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
![The Right-Click Extender v2 window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-all-tasks-setting.jpg)
8. Press the green **Apply** button.

 Now you’ll see a new **God Mode** option on Windows 11’s classic context menu. This option will also have an icon by it. Click on **God Mode** to view the list of Control Panel applets.

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Create Control Panel Shortcuts From God Mode's All Tasks Window

 The Task View window the God Mode context menu option opens makes hundreds of Control Panel applets more accessible. You can open whatever Control Panel settings you need from that window. However, the list of applets shown in that window is quite long.

 Task View makes it easy to create desktop shortcuts for opening the Control Panel applets you need to access more regularly. To do so, left-click an applet or utility in the Task View window, drag it onto the desktop, and release the mouse button. Then you can click on the desktop shortcut to open its Control Panel applet whenever needed.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
![The All Tasks (God Mode) window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-all-tasks-window.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
## Make the Most of God Mode on Windows

 Adding God Mode to your desktop’s context menu will enable you to access a plethora of Control Panel applets and tools within a single window in a couple of clicks. That will save you from rummaging through the Control Panel to find certain applets and settings when needed. Plus, you can make more essential Control Panel applets even more accessible by creating shortcuts for them from the Task View window.

 Many users activate God Mode by setting up desktop shortcuts that open the All Tasks window. However, you can instead add a **God Mode** option to the desktop’s context menu in Windows 11\. Then the All Tasks window will be directly accessible on your right-click menu. This is how you can add God Mode to Windows 11’s context menu.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-next-gen-editing-excellence-perfect-for-vimeo-content/"><u>[New] 2024 Approved  Next-Gen Editing Excellence  Perfect for Vimeo Content</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-best-unplugged-android-gaming-apps-no-internet-required-for-2024/"><u>[New] Best Unplugged Android Gaming Apps (No Internet Required) for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-bring-your-imagination-to-life-using-cartoony-filters-in-snapchat-for-2024/"><u>[New] Bring Your Imagination to Life  Using Cartoony Filters in Snapchat for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-effortless-film-logging-how-to-use-devices-like-pros-for-2024/"><u>[New] Effortless Film Logging  How to Use Devices Like Pros for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-in-2024-effortless-itunes-for-podcast-enthusiasts/"><u>[New] In 2024, Effortless iTunes for Podcast Enthusiasts</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-proven-approaches-to-amass-elite-copyright-free-imagery/"><u>[New] Proven Approaches to Amass Elite, Copyright-Free Imagery</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-language-of-cinema-writing-as-an-art/"><u>[New] The Language of Cinema  Writing as an Art</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-navigating-the-world-of-tweets-starting-fresh/"><u>[Updated] Navigating the World of Tweets  Starting Fresh</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-preserving-gh-meetings-live/"><u>[Updated] Preserving GH Meetings Live</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-snowflakes-and-champions-highlights-from-beijing-games/"><u>[Updated] Snowflakes and Champions  Highlights From Beijing Games</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/achieve-full-screen-display-in-social-media-videos-for-2024/"><u>Achieve Full-Screen Display in Social Media Videos for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-causes-of-pc-disk-issues/"><u>Addressing Causes of PC Disk Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-power-start-cmd-as-administrator/"><u>Boosting Power: Start CMD as Administrator</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-user-interface-integrating-emoji-15-into-win11/"><u>Boosting User Interface: Integrating Emoji 15 Into Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/can-you-get-rid-of-the-windows-bt-directories/"><u>Can You Get Rid of the Windows ~BT Directories?</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-chatgpt-on-your-windows-pc/"><u>Configuring ChatGPT on Your Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-absent-msvcr110dll-in-windows/"><u>Correcting Absent msvcr110.dll in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-wins-system-alert-messages-in-windows-1011/"><u>Correcting WINS System Alert Messages in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-mysteries-of-ram-in-windows-devices/"><u>Decoding the Mysteries of RAM in Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-managing-events-with-windows-11-calendar/"><u>Efficiently Managing Events with Windows 11 Calendar</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-empty-folder-warning-in-windows-11/"><u>Eliminating 'Empty Folder' Warning in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-nvidia-connect-failure-on-windows-11-systems/"><u>Fixing Nvidia Connect Failure on Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-wire-free-audio-on-windows-airpods/"><u>Guide to Wire-Free Audio on Windows (AirPods)</u></a></li>
<li><a href="https://windows11.techidaily.com/guides-to-mastering-your-fax-interface-with-w11s-tools/"><u>Guides to Mastering Your Fax Interface with W11's Tools</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/here-are-some-of-the-best-pokemon-discord-servers-to-join-on-xiaomi-mix-fold-3-drfone-by-drfone-virtual-android/"><u>Here are Some of the Best Pokemon Discord Servers to Join On Xiaomi Mix Fold 3 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-sd-card-regain-access-with-troubleshooting-guide/"><u>Hidden SD Card: Regain Access with Troubleshooting Guide</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/how-much-footage-does-instagram-allow/"><u>How Much Footage Does Instagram Allow?</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-androidprocessmedia-has-stopped-on-lava-blaze-2-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android.Process.Media Has Stopped on Lava Blaze 2 5G | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-fix-auto-lock-greyed-out-on-iphone-15-pro-by-drfone-ios/"><u>How To Fix Auto Lock Greyed Out on iPhone 15 Pro</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-honor-magic-6-lite-phone-without-google-account-by-drfone-android/"><u>How to Unlock Honor Magic 6 Lite Phone without Google Account?</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-utilize-windows-for-handwritten-input/"><u>How to Utilize Windows for Handwritten Input</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-feasible-ways-to-fake-location-on-facebook-for-your-samsung-galaxy-m54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Feasible Ways to Fake Location on Facebook For your Samsung Galaxy M54 5G | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-apple-iphone-6s-drfone-by-drfone-virtual-ios/"><u>In 2024, Can I use iTools gpx file to catch the rare Pokemon On Apple iPhone 6s | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-cutting-edge-methods-for-recording-presentations/"><u>In 2024, Cutting Edge Methods for Recording Presentations</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-from-basic-snaps-to-expertly-crafted-images-on-snapchat/"><u>In 2024, From Basic Snaps to Expertly Crafted Images on Snapchat</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-from-zero-to-hero-amplifying-youtube-influence-via-famebit-partnerships/"><u>In 2024, From Zero to Hero  Amplifying YouTube Influence via FameBit Partnerships</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-step-into-the-future-the-best-10-free-video-call-applications/"><u>In 2024, Step Into the Future  The Best 10 FREE Video Call Applications</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-top-5-capture-tools-dethroning-bandicam-on-apple-devices/"><u>In 2024, Top 5 Capture Tools Dethroning Bandicam on Apple Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/instant-permadelete-configuring-your-desktop-trash-bin-on-windows-11-devices/"><u>Instant PermaDelete: Configuring Your Desktop Trash Bin on Windows 11 Devices</u></a></li>
<li><a href="https://some-approaches.techidaily.com/japejungle-design-original-content-instantly-for-2024/"><u>JapeJungle  Design Original Content Instantly for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/live-transcribing-made-easy-the-whisper-way/"><u>Live Transcribing Made Easy - The Whisper Way</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-correctly-installing-apps-from-ms-store/"><u>Mastering the Art of Correctly Installing Apps From MS Store</u></a></li>
<li><a href="https://windows11.techidaily.com/merge-your-world-connecting-android-and-windows-11-tablets/"><u>Merge Your World: Connecting Android and Windows 11 Tablets</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-through-faulty-shift-in-windows/"><u>Navigate Through Faulty Shift in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-wi-fi-connectivity-hurdles-clearing-action-shortcomings/"><u>Overcoming Wi-Fi Connectivity Hurdles: Clearing Action Shortcomings</u></a></li>
<li><a href="https://windows11.techidaily.com/overhauling-write-operations-failure-fixes-on-windows/"><u>Overhauling Write Operations Failure Fixes on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-access-disabled-sign-in-on-windows/"><u>Restoring Access: Disabled Sign-In on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/shaping-windows-11-square-it-off/"><u>Shaping Windows 11: Square It Off</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-manual-reverting-windows-to-a-previous-state/"><u>Step-by-Step Manual: Reverting Windows to a Previous State</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-correcting-incompatible-software-with-windows-operations/"><u>Strategies for Correcting Incompatible Software with Windows Operations</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-creative-processes-with-these-8-windows-best-apps/"><u>Streamline Creative Processes With These 8 Window's Best Apps</u></a></li>
<li><a href="https://win-amazing.techidaily.com/streamline-setup-with-speedy-downloads-of-wireless-network-drivers/"><u>Streamline Setup with Speedy Downloads of Wireless Network Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-winerror-x80780119-resolution/"><u>Techniques for WinError X80780119 Resolution</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1722165515691-the-ultimate-guide-to-boosting-your-business-with-chatgpts-power-discover-8-methods/"><u>The Ultimate Guide to Boosting Your Business with ChatGPT's Power - Discover 8 Methods!</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-password-creation-companion-for-windows-users/"><u>The Ultimate Password Creation Companion for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/the-uncharted-territory-windows-11-and-the-future-of-ai/"><u>The Uncharted Territory: Windows 11 and the Future of AI</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-realme-narzo-60-pro-5g-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive Realme Narzo 60 Pro 5G Screen | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/turning-on-hyper-v-simplified-your-win11-how-to/"><u>Turning On Hyper-V Simplified - Your Win11 How-To</u></a></li>
<li><a href="https://windows11.techidaily.com/ultimate-bundle-premier-cost-free-windows-11-assistants/"><u>Ultimate Bundle: Premier Cost-Free Windows 11 Assistants</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-telnet-enablement-steps-explained/"><u>Windows 11 Telnet Enablement Steps Explained</u></a></li>
</ul></div>
