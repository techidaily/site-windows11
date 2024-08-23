---
title: Expert Guide to Streamline Program Access via Context Menu
date: 2024-08-22T21:34:51.211Z
updated: 2024-08-23T21:34:51.211Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Expert Guide to Streamline Program Access via Context Menu
excerpt: This Article Describes Expert Guide to Streamline Program Access via Context Menu
keywords: Program Access Quickstart,Context Menu Streamlining,Ease-of-Use Techniques,Context UI Simplification,Swift Program Navigation,Menu Integration Guide,User Interface Optimization
thumbnail: https://thmb.techidaily.com/3c44f0be88269dfe58e87652a332c52a578262780df7f0b33d89646c55a92321.jpg
---

## Expert Guide to Streamline Program Access via Context Menu

 Context menus are the backbone of Windows—they're the little menus you see when you right-click the mouse on something. And while Windows 11 has brought in a new context menu for your desktop, there still aren’t any native customization options for it. For example, Windows 11 doesn’t include any built-in setting that enables you to add custom software shortcuts to that menu.

 Nevertheless, you can still add program shortcuts to the desktop context menu in Windows 11 by editing the registry. By doing so, you can replace desktop shortcut icons with context menu ones.

## How to Add an Edge Shortcut to the Desktop Context Menu

 As [Microsoft Edge is the default browser](https://www.makeuseof.com/how-windows-11-may-soon-force-you-to-use-microsoft-edge/) included with Windows 11, that's a software package you’ll all have to set up a context menu shortcut for. So, we’ll add an Edge shortcut to the desktop context menu for the sake of an example. This is how you can add a shortcut for that browser to the desktop context menu with a [simple tweak to the Windows registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/):

1. First, right-click the **Start** button on the taskbar and select **Run**.
2. Enter **regedit** in the Open box within Run’s window.
3. Click **OK** to [launch the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
4. Then navigate to the **Computer > HKEY\_CLASSES\_ROOT > Directory > Background > shell** registry key path.  
![The Shell registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/the-shell-key.png)
5. Right-click the **shell** key to select **New** and **Key** on the context menu.  
![The Key context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/the-key-option.png)

1. Input **Edge** as the new registry key’s title.
2. Right-click your **Edge** key and select the **New** \> **Key** options again.
3. Enter **command** to be the new subkey’s name.  
![The command registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/the-command-key.png)
4. Click File Explorer’s taskbar button.
5. Open Edge’s folder, which has this default path: **C:\\Program Files (x86)\\Microsoft\\Edge\\Application**.

1. Right-click msedge.exe there to select the **Copy as** **path** option shown directly below.  
![The Copy as path option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/copy-as-path-option.png)
2. Then return to the Registry Editor, and select the new **command** key you added.
3. Double-click **(Default)** for the **command** key on the right side of the window.
4. Press the **Ctrl** \+ **V** hotkey to paste the copied Edge path within the Value data box.  
![The Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/the-edit-string-window.png)
5. Click **OK** to confirm.

 Now you can try out your new Edge context menu shortcut. Right-click the desktop and select **Show more options** to view the classic menu. Then select **Edge** there to open that browser.

![A Microsoft Edge context menu shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/edge-context-menu-shortcut.png)

 If you prefer, you can bring up the classic context menu in Windows 11 with a handy keyboard shortcut. Press the **Shift + F10** hotkey to open the menu instead. Then select your software shortcuts from there.

## How to Add Your Own Shortcuts to the Windows 11 Context Menu

 You can add a shortcut for whatever software you'd like in a similar way to adding Edge. To do this, you need to change the name of the primary registry key to match the name of the software it’s for. Then, open the program’s folder in File Explorer to copy its full path, and paste it in the Value data box for the command subkey’s **(Default)** string.

 To remove one of your software context menu shortcuts, you’ll need to open the key for it in the Registry Editor. Then right-click its primary key to select a **Delete** option. Select **Yes** to confirm and erase.

![The delete context menu option for registry keys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/the-delete-option.png)

 This registry tweak also works much the same in Windows 10 and earlier Microsoft desktop platforms. So, this isn’t just a Windows 11 trick. As Windows 10 has a classic context menu by default, you don’t need to click **Show more options** on that menu to select the shortcut.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
## How to Add Program Shortcuts to the Context Menu With Easy Context Menu

 If you prefer not to manually edit the registry, add program shortcuts to the desktop’s context menu with Easy Context Menu. Easy Context Menu is a freeware third-party app for customizing context menus in Windows 11/10\. It enables you to add and remove shortcuts to and from the context menu. This is how you can add shortcuts for opening programs to Windows 11’s context menu with that software:

1. Open this [Easy Context Menu page](https://www.sordum.org/7615/easy-context-menu-v1-6/) in a web browser and download the app.
2. Extract the **ec\_menu** ZIP archive with a method in this article about [unzipping ZIP files in Windows 11](https://www.makeuseof.com/how-to-extract-zip-files-windows-11/).
3. Open the extracted **ec\_menu** folder and double-click the **EcMenu\_x64** file to open Easy Context Menu.
4. Click the **List Editor** button.  
![The List Editor button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/list-editor-button.jpg)
5. Press the **Add new** button.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Select the application (EXE) file for a program to add to the context menu and click **Open**.
2. Next, select **Desktop Context Menu** on the **Target Context Menu** drop-down menu for the shortcut.  
![The Target Context Menu drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/target-context-menu-drop-down-menu.jpg)
3. Click the **Show at bottom of the menu** radio button.
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
4. Press the **Save changes** button.
5. Select the checkbox for the program shortcut in the Easy Context Menu window.
6. Click the **Apply Changes** button on the Easy Context Menu window.  
![The Apply Changes button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/apply-changes-button.jpg)

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
 Now you’ve added a new program shortcut to the classic context menu in Windows 11\. Bring up the classic context menu by right-clicking anywhere on the desktop and selecting **Show more options**. Then select the new software shortcut, which will be somewhere near the bottom of the classic menu.

 You can remove that shortcut and other options from the right-click menu with Easy Context Menu. To do so, click the **ContextMenu Cleaner** button; deselect the checkbox for the software shortcut to disable it on the context menu (you can still restore it later). Then click **Refresh** to save the context menu changes.

![The ContextMenu Cleaner window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/contextmenu-cleaner-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
 There’s also much more you can add to the desktop’s right-click menu with Easy Context Menu than software shortcuts. Easy Context Menu includes many other checkboxes for adding various tools and turn-off options to the right-click menu. Select some of the checkboxes for system tools and turn-off options, and click **Apply Changes** to add handy shortcuts for accessing utilities and shutting down Windows to the context menu.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Make the Most Out of Windows 11’s Context Menu

 Now you can add program shortcuts to the context menu instead of flooding your desktop wallpaper or taskbar with them. That’s a great alternative place to add shortcuts because they don’t clutter your desktop. Keep your Windows 11 desktop clean and tidy by adding more shortcuts to the context menu instead.

 Nevertheless, you can still add program shortcuts to the desktop context menu in Windows 11 by editing the registry. By doing so, you can replace desktop shortcut icons with context menu ones.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-quick-image-transfiguration-winmac-photo-animation-pro/"><u>[New] 2024 Approved  Quick Image Transfiguration  Win/Mac Photo Animation Pro</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-twitpic-saver-streamline-ios-video-downloads-from-tweets/"><u>[New] 2024 Approved  TwitPic Saver  Streamline iOS Video Downloads From Tweets</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-box-it-up-the-top-10-online-houses-for-customized-gift-boxes/"><u>[New] Box It Up! The Top 10 Online Houses for Customized Gift Boxes</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-unlock-high-quality-video-playback-with-av1-on-youtube/"><u>[New] Unlock High-Quality Video Playback with AV1 on YouTube</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-video-transit-route-tweeting-to-tumbling/"><u>[New] Video Transit Route  Tweeting to Tumbling</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-2024-approved-building-effective-product-sponsor-relationships/"><u>[Updated] 2024 Approved  Building Effective Product-Sponsor Relationships</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-streamlined-processes-for-capturing-vimeo-video-files/"><u>[Updated] 2024 Approved  Streamlined Processes for Capturing Vimeo Video Files</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-best-5-youtube-video-editor-alternatives/"><u>[Updated] Best 5 YouTube Video Editor Alternatives</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-dive-into-the-world-of-enhanced-youtube-content-with-premium-subscription/"><u>[Updated] Dive Into the World of Enhanced YouTube Content with Premium Subscription</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-in-2024-innovative-volume-dissipation-methods-within-audacity-tools/"><u>[Updated] In 2024, Innovative Volume Dissipation Methods Within Audacity Tools</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-infinix-smart-8-hd-drfone-by-drfone-virtual-android/"><u>15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Infinix Smart 8 HD | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-inferno-captures-best-slow-motion-cameras/"><u>2024 Approved  Inferno Captures  Best Slow-Motion Cameras</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-innovative-strategies-for-vimeo-video-recording/"><u>2024 Approved  Innovative Strategies for Vimeo Video Recording</u></a></li>
<li><a href="https://printer-issues.techidaily.com/alleviating-hp-printer-error-code-oxc4eb827f/"><u>Alleviating HP Printer Error: Code OXC4EB827F</u></a></li>
<li><a href="https://buynow-help.techidaily.com/canon-eos-t7-review-a-significant-step-forward/"><u>Canon EOS T7 Review - A Significant Step Forward</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/demystifying-vimeos-triplet-plans-for-content-creators/"><u>Demystifying Vimeo's Triplet Plans for Content Creators</u></a></li>
<li><a href="https://screen-capture.techidaily.com/echo-enthusiasts-emporium-obtain-and-review-sound-files/"><u>Echo Enthusiasts Emporium  Obtain & Review Sound Files</u></a></li>
<li><a href="https://extra-resources.techidaily.com/exclusive-access-to-the-finest-ae-templates-all-free/"><u>Exclusive Access to The Finest AE Templates, All-Free</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-to-tackle-ms-store-hurdle-win1011s-error-0x0/"><u>Expert Advice to Tackle MS Store Hurdle: Win10/11's Error 0X0</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-non-starting-windows-indexing-service/"><u>Fixing Non-Starting Windows Indexing Service</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-adjust-smartscreen-settings-for-win11-users/"><u>Guide: Adjust SmartScreen Settings for Win11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-how-to-generate-a-copernic-software-offline-license/"><u>Guide: How to Generate a Copernic Software Offline License</u></a></li>
<li><a href="https://windows11.techidaily.com/harnessing-windows-powers-for-linux-enhancement/"><u>Harnessing Windows Powers for Linux Enhancement</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-electric-cars-unlock-free-benefits-hov-lane-privileges-and-dedicated-parking-spaces/"><u>How Electric Cars Unlock Free Benefits: HOV Lane Privileges and Dedicated Parking Spaces</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-frp-from-tecno-pova-5-by-drfone-android/"><u>How to Bypass FRP from Tecno Pova 5?</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-android-app-not-installed-error-on-poco-x6-pro-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android App Not Installed Error on Poco X6 Pro Quickly? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-in-ar-games-on-vivo-x90s-drfone-by-drfone-virtual-android/"><u>How to Simulate GPS Movement in AR games On Vivo X90S? | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-unravel-the-mysteries-of-efficient-story-connectivity/"><u>In 2024, Unravel the Mysteries of Efficient Story Connectivity</u></a></li>
<li><a href="https://windows11.techidaily.com/initiate-your-adventure-joining-win-11-insiders/"><u>Initiate Your Adventure: Joining Win 11 Insiders</u></a></li>
<li><a href="https://facebook.techidaily.com/instagram-unlocks-whatsapp-as-a-2fa-code-vessel/"><u>Instagram Unlocks: WhatsApp as a 2FA Code Vessel</u></a></li>
<li><a href="https://windows11.techidaily.com/instantaneous-access-to-the-calculator-in-windows-11-os/"><u>Instantaneous Access to the Calculator in Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/introducing-specific-group-policy-enforcement-on-users-profiles-in-win-oses/"><u>Introducing Specific Group Policy Enforcement on Users' Profiles in Win OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/keeping-calculator-top-displayed-in-windows/"><u>Keeping Calculator Top-Displayed in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/laymans-guide-to-setting-up-a-triple-column-board-on-windows-11/"><u>Layman's Guide to Setting Up a Triple Column Board on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/lightweight-window-navigators-ram-usage-tested-and-rated/"><u>Lightweight Window Navigators: Ram Usage Tested and Rated</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-quick-finds-in-illustrator-a-complete-guide-using-copernic/"><u>Mastering Quick Finds in Illustrator: A Complete Guide Using Copernic</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-address-failed-boot-up-display-driver/"><u>Methods to Address Failed Boot-Up Display Driver</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-flawless-file-handling-discover-copernics-software-secrets-for-maximum-efficiency/"><u>Navigating Flawless File Handling: Discover Copernic's Software Secrets for Maximum Efficiency</u></a></li>
<li><a href="https://windows11.techidaily.com/power-up-your-workflow-essential-tools-for-win-11-pros/"><u>Power Up Your Workflow: Essential Tools for Win 11 Pros</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-your-photos-after-gionee-f3-pro-has-been-deleted-by-fonelab-android-recover-photos/"><u>Recover your photos after Gionee F3 Pro has been deleted.</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-clutter-in-windows-11s-selection-options/"><u>Reducing Clutter in Windows 11'S Selection Options</u></a></li>
<li><a href="https://windows11.techidaily.com/reestablishing-active-slack-signals-in-windows-11/"><u>Reestablishing Active Slack Signals in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagining-your-windows-11-search-experience/"><u>Reimagining Your Windows 11 Search Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-touchpad-glitches-on-your-windows-machine/"><u>Remedying Touchpad Glitches on Your Windows Machine</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-step-by-step-guide-to-repairing-the-red-screen-error/"><u>Resolved: Step-by-Step Guide to Repairing the Red Screen Error</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionize-folder-management-selective-move-on-windows-11/"><u>Revolutionize Folder Management: Selective Move on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionizing-business-data-retrieval-with-advanced-copernic-search-tech-explained/"><u>Revolutionizing Business Data Retrieval with Advanced Copernic Search Tech Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/santa-skims-but-you-need-depth-discover-how-copernic-transforms-your-data-check-with-precision-and-ease/"><u>Santa Skims, But You Need Depth - Discover How Copernic Transforms Your Data Check with Precision and Ease!</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-microsofts-defender-on-edge-win-11-guide/"><u>Setting Up Microsoft's Defender on Edge: Win 11 Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/smooth-transition-to-emoji-15-for-windows-11-users/"><u>Smooth Transition to Emoji 15 for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-browsing-with-mouse-gestures-in-microsoft-edge/"><u>Streamline Your Browsing with Mouse Gestures in Microsoft Edge</u></a></li>
<li><a href="https://windows11.techidaily.com/subtlety-shifts-concealing-win-11s-control/"><u>Subtlety Shifts: Concealing Win 11'S Control</u></a></li>
<li><a href="https://windows11.techidaily.com/the-snapshot-navigating-newly-active-windows-items/"><u>The Snapshot: Navigating Newly Active Windows Items</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-ways-copernic-enhances-your-work-from-home-experience/"><u>Top 5 Ways Copernic Enhances Your Work-From-Home Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/tracing-the-blue-screen-footsteps-in-windows-xp7/"><u>Tracing the Blue Screen Footsteps in Windows XP/7</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-your-cursor-display-with-windows-1011-tweaks/"><u>Transforming Your Cursor Display with Windows 10/11 Tweaks</u></a></li>
<li><a href="https://windows11.techidaily.com/trim-excessive-resource-use-of-antimalware-tools/"><u>Trim Excessive Resource Use of Antimalware Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-maxed-out-chatgpt-error/"><u>Troubleshooting Maxed Out ChatGPT Error</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/unlock-iphone-se-2022-without-passcode-easily-drfone-by-drfone-ios/"><u>Unlock iPhone SE (2022) Without Passcode Easily | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-system-potential-mastery-of-win-registry-cli-edits/"><u>Unlocking System Potential: Mastery of Win Registry CLI Edits</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/unmasking-the-avengers-achievements-an-in-depth-film-reception-breakdown/"><u>Unmasking the Avengers' Achievements - An In-Depth Film Reception Breakdown</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-gpo-details-using-gpresult/"><u>Unveiling GPO Details Using GPResult</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/vn-video-editor-for-windows-a-concise-review-for-2024/"><u>VN Video Editor for Windows A Concise Review for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-configurations-simplified/"><u>Windows 11 Configurations Simplified</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-struggles-heres-how-to-install-icloud-seamlessly/"><u>Windows Struggles? Here’s How to Install iCloud Seamlessly</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-wasd-segregating-sounds-effectively/"><u>Windows WASD: Segregating Sounds Effectively?</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>