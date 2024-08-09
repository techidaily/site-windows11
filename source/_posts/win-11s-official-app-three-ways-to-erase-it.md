---
title: "Win 11'S Official App: Three Ways to Erase It"
date: 2024-08-08T06:13:08.927Z
updated: 2024-08-09T06:13:08.927Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Win 11'S Official App: Three Ways to Erase It"
excerpt: "This Article Describes Win 11'S Official App: Three Ways to Erase It"
keywords: Win11EraseApp,UninstallWin11,EliminateWin11,RemoveWin11,DeleteWin11Official,UninstallWin11Installed,DisableWin11App
thumbnail: https://thmb.techidaily.com/0fffdaf6b0345d8277ec9fafebd3429c28f703cd8774f81e39bb2cfd9b5790b4.jpg
---

## Win 11'S Official App: Three Ways to Erase It

 Microsoft Store is the go-to place for Windows users if they want to install an app. The app library is slowly expanding, and you will find all the popular apps without any difficulty. But sometimes the Microsoft Store application behaves abnormally and requires troubleshooting.

 But what if it still doesn’t work, even after repairing and resetting? There is no uninstall option in the Settings app, so it is possible to uninstall Microsoft Store? Well, it is possible to remove and reinstall the Microsoft Store app. Here’s how.

<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
## Why Should You Uninstall the Microsoft Store App?

 Microsoft Store houses all the useful and popular applications for Windows devices. Moreover, it guarantees safe and malware-free application downloads. But if the app fails to start or doesn’t work properly, removing it makes sense.

 But don’t worry. You can remove the app and then reinstall it if you want. Reinstallation can fix persistent issues with the current version of the Microsoft Store app. It will remove the current app installation and all its related files and corrupt data. After that, you can reinstall the Microsoft app with a single command.

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Uninstall Microsoft Store App From Windows 11

 You can remove the Microsoft Store app from Windows 11 using the winget tool and run it using the command prompt. In addition, you can use the PowerShell cmdlet to remove the Microsoft Store application package from your system or use a batch file.

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
### 1\. Using Winget

 Winget is a handy Windows package manager tool available with the newer releases of Windows 10 and 11\. It makes it ridiculously easy to search and manage applications on your system. You can use it to remove any application, even the Microsoft Store app from your system. Here’s how:

1. Press the**Win + R** key to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** and press the**Ctrl + Shift + Enter** keys to launch the Command Prompt with administrator privileges.
2. Now, we need to locate the ID of the Microsoft Store app installed on the system. Type the following command in the command prompt window and press the enter key:**Winget list Store**
3. Winget will list all the installed programs on your system containing the string “store” in their name. Find the Microsoft Store app in the list and**copy** its**ID** .
4. After that, you need to run the uninstall command using winget. The syntax is**winget uninstall \[app ID\]** . So, the command will be:  
winget uninstall Microsoft.WindowsStore_8wekyb3d8bb
5. Press enter to execute the command and wait for it to execute successfully.  
![Uninstall Microsoft Store App using winget](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-winget.jpg)
6. Type**exit** in the command prompt window and press enter to close it.

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Using PowerShell

 Before winget was officially integrated into Windows 10 and 11, there was a method to[remove the Microsoft Store app using PowerShell](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) . The method still works and all you need to do is list the package name and then use the**Remove-AppxPackage** cmdlet to uninstall the Microsoft Store app from your system. Make sure to run PowerShell with elevated permissions.

### 3\. Using a Batch File

 If you want to save the hassle of typing commands every time you want to uninstall the Microsoft Store app, you can use a batch file. It will help you to remove Microsoft Store app from your system in a couple of clicks whenever the normal troubleshooting methods don’t work for you. Repeat the following steps:

1. Press**Win + D** to switch to the Desktop. Right-click on the Desktop and select the**New > Text Document** option.
2. Open the newly created text document file on the desktop. A Notepad window will pop up. Paste the following text in it:  
@echo off winget uninstall "Microsoft Store" exit
3. Now, press**Ctrl + Shift + S** to open the "Save as" window. Name the batch file as**UninstallStore.bat** and keep the**Save as** type option as**All files** .  
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
![Uninstall Microsoft Store App using batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-batch-file.jpg)
4. Click on the**Save** button. Close the Notepad window.
5. Press**Win + D** to switch to the desktop again. Right-click on the batch file and select the**Run as administrator** option from the context menu.
6. A command prompt window will open, run the Microsoft Store app uninstallation command, and close automatically. You don’t need to interact with the window.
7. Open the Start menu and search for Microsoft Store. You won’t find any matching app on your system.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Easily Remove the Microsoft Store From Windows

 Windows 10 and 11 don’t offer an option to uninstall Microsoft Store. So, you are only left at the mercy of a system restore or reset. However, you can now uninstall the Microsoft Store app from your system using any of the three methods mentioned above. You can also reinstall it using the PowerShell cmdlet and continue using the app again.


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
<li><a href="https://extra-tips.techidaily.com/new-best-tools-and-techniques-adding-frames-to-digital-images-2023-edition/"><u>[New] Best Tools & Techniques - Adding Frames to Digital Images, 2023 Edition</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-channel-building-strategies-to-hit-a-million-view-mark/"><u>[New] Channel Building Strategies to Hit a Million-View Mark</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-console-chronos-review/"><u>[New] In 2024, Console Chronos Review</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-cutting-edge-videography-bordering-techniques-for-ig/"><u>[New] In 2024, Cutting-Edge Videography  Bordering Techniques for IG</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-secrets-to-effortless-obs-broadcasts-on-fb/"><u>[New] In 2024, Secrets to Effortless OBS Broadcasts on FB</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-the-insiders-guide-to-creating-viral-instagram-reels/"><u>[New] In 2024, The Insider’s Guide to Creating Viral Instagram Reels</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-raise-the-bar-top-8-speed-up-video-apps/"><u>[New] Raise the Bar  Top 8 Speed Up Video Apps</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-saving-smiles-techniques-for-capturing-twitters-gifs-for-2024/"><u>[New] Saving Smiles  Techniques for Capturing Twitter's GIFs for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-tricks-to-upgrade-streaming-quality-on-mobile-apps-like-facebook/"><u>[New] Tricks to Upgrade Streaming Quality on Mobile Apps Like Facebook</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-8-best-tablets-for-photo-editing-worth-a-try-filmora/"><u>[Updated] 2024 Approved  8 Best Tablets for Photo Editing Worth a Try - Filmora</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-ultimate-gecata-analyzer-report/"><u>[Updated] 2024 Approved  Ultimate GECATA Analyzer Report</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-revolutionary-tactics-for-enhanced-roi-in-animated-facebook-advertising-for-2024/"><u>[Updated] Revolutionary Tactics for Enhanced ROI in Animated Facebook Advertising for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-strategies-for-finding-high-impact-keywords-for-youtube-content/"><u>[Updated] Strategies for Finding High-Impact Keywords for YouTube Content</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-designing-intriguing-instagram-post-thumbnails/"><u>2024 Approved  Designing Intriguing Instagram Post Thumbnails</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-enablingdisabling-picture-in-picture-a-step-by-step-guide-for-iphones/"><u>2024 Approved  Enabling/Disabling Picture-in-Picture  A Step-by-Step Guide for iPhones</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-in-video-earnings-techno-gamers-guide/"><u>2024 Approved  In-Video Earnings  Techno Gamers' Guide</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-revolutionizing-photo-quality-with-auto-and-smart-hdr-features/"><u>2024 Approved  Revolutionizing Photo Quality with Auto and Smart HDR Features</u></a></li>
<li><a href="https://windows11.techidaily.com/7-crucial-blunders-every-windows-11-novice-must-avoid/"><u>7 Crucial Blunders Every Windows 11 Novice Must Avoid</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/access-the-newest-drivers-for-your-hp-officejet-975c-all-in-one-printer/"><u>Access the Newest Drivers for Your HP OfficeJet 975C All-in-One Printer</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-windows-11-homespace-options/"><u>Accessing Windows 11 Homespace Options</u></a></li>
<li><a href="https://extra-information.techidaily.com/activate-windows-11s-automatic-high-dynamic-range-auto-hdr-for-2024/"><u>Activate Windows 11'S Automatic High Dynamic Range (Auto HDR) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-the-deadly-js-error-in-discord-a-quick-guide-for-win-11-users/"><u>Banish the Deadly JS Error in Discord: A Quick Guide for Win 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/changing-network-address-translation-types-simplified-for-wins-oses/"><u>Changing Network Address Translation Types Simplified for Wins OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/convenience-at-a-click-discover-how-to-enable-gestures-on-edge-windows-11/"><u>Convenience at a Click: Discover How to Enable Gestures on Edge (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-user-experience-through-gpos-in-windows-11-and-11/"><u>Customizing User Experience Through GPOs in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-window-11-ui-elements-larger-icons/"><u>Customizing Window 11 UI Elements - Larger Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-epochal-passphrase-problem-in-windows-os/"><u>Deciphering “Epochal Passphrase Problem in Windows OS”</u></a></li>
<li><a href="https://windows11.techidaily.com/effortlessly-upgrading-windows-11-in-place/"><u>Effortlessly Upgrading Windows 11 in Place</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-windows-steam-performance-preventing-zero-speed-slowdowns/"><u>Elevate Windows Steam Performance: Preventing Zero-Speed Slowdowns</u></a></li>
<li><a href="https://windows11.techidaily.com/enforcing-originality-windows-screensaver-non-alterability/"><u>Enforcing Originality: Windows Screensaver Non-Alterability</u></a></li>
<li><a href="https://windows11.techidaily.com/epic-backup-strategies-to-avoid-loss/"><u>Epic Backup Strategies to Avoid Loss</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-windows-11s-admin-tools/"><u>Exploring Windows 11'S Admin Tools</u></a></li>
<li><a href="https://howto.techidaily.com/fix-app-not-available-in-your-country-play-store-problem-on-samsung-galaxy-a15-4g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix App Not Available in Your Country Play Store Problem on Samsung Galaxy A15 4G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-11s-insufficient-uninstall-rights/"><u>Fixing Windows 11'S Insufficient Uninstall Rights</u></a></li>
<li><a href="https://windows11.techidaily.com/get-to-safety-six-steps-to-entering-safe-mode-in-windows-11/"><u>Get to Safety: Six Steps to Entering Safe Mode in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/harness-window-11-a-productivity-playbook/"><u>Harness Window 11: A Productivity Playbook</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-honor-90-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Honor 90 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-windows-11-version-22h2-update-not-installing/"><u>How to Fix the Windows 11 Version 22H2 Update Not Installing</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reinvigorate-the-essential-wsreset-process/"><u>How to Reinvigorate the Essential WSReset Process</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-my-spouse-from-spying-on-my-infinix-note-30-vip-drfone-by-drfone-virtual-android/"><u>How to Stop My Spouse from Spying on My Infinix Note 30 VIP | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-realme-narzo-60x-5g-by-phone-number-drfone-by-drfone-virtual-android/"><u>How to Track Realme Narzo 60x 5G by Phone Number | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/icy-images-cozier-cinematics-best-bgs-selection-for-2024/"><u>Icy Images, Cozier Cinematics  Best Bgs Selection for 2024</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-detailed-guide-of-ispoofer-for-pogo-installation-on-apple-iphone-14-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, Detailed guide of ispoofer for pogo installation On Apple iPhone 14 Pro Max | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-honor-magic-6-prowithwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Honor Magic 6 Prowith/without a PC</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-proven-ways-in-how-to-hide-location-on-life360-for-lava-blaze-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Proven Ways in How To Hide Location on Life360 For Lava Blaze Pro 5G | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-sim-unlock-code-generators-unlock-your-vivo-v30-pro-phone-hassle-free-by-drfone-android/"><u>In 2024, The Best Android SIM Unlock Code Generators Unlock Your Vivo V30 Pro Phone Hassle-Free</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-two-ways-to-track-my-boyfriends-vivo-y36-without-him-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Two Ways to Track My Boyfriends Vivo Y36 without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/insights-on-why-companies-are-wary-of-conversational-ai-tools/"><u>Insights on Why Companies Are Wary of Conversational AI Tools</u></a></li>
<li><a href="https://tech-haven.techidaily.com/leading-ai-powered-search-engines-and-utilities-to-transform-your-online-research/"><u>Leading AI Powered Search Engines and Utilities to Transform Your Online Research</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-the-absence-of-dxgidll-in-new-os-windows-11/"><u>Mending the Absence of Dxgi.dll in New OS, Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-words-silent-mode-fix-for-pc-users/"><u>Microsoft Word's Silent Mode Fix for PC Users</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11-multi-display-setup/"><u>Navigating Windows 11 Multi-Display Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/power-preservation-pitfalls-the-reality-of-modern-standby/"><u>Power Preservation Pitfalls: The Reality of Modern Standby</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-dual-device-names-on-your-windows-network/"><u>Preventing Dual Device Names on Your Windows Network</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-access-to-troubleshooters-in-windows-11-with-custom-keys/"><u>Quick Access to Troubleshooters in Windows 11 with Custom Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tricks-to-pinpoint-your-graphic-card-on-windows-11/"><u>Quick Tricks to Pinpoint Your Graphic Card on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-powerful-usage-in-modern-host-computers/"><u>Reducing Powerful Usage in Modern Host Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/reinvigorate-windows-search-top-11-remedies-explored/"><u>Reinvigorate Windows Search: Top 11 Remedies Explored</u></a></li>
<li><a href="https://technical-tips.techidaily.com/resolving-the-problem-of-unopened-microsoft-word-files-easily/"><u>Resolving the Problem of Unopened Microsoft Word Files Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/security-enhancement-manual-add-a-self-designed-lock-pattern/"><u>Security Enhancement Manual: Add a Self-Designed Lock Pattern</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-absence-of-windows-1011-search-outcomes/"><u>Solving Absence of Windows 10/11 Search Outcomes</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-overcome-onedrive-errors-on-w11-systems/"><u>Strategies to Overcome OneDrive Errors on W11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-approach-to-bypass-cant-add-your-folder-now-error-in-windows-onedrive-drive/"><u>Swift Approach to Bypass 'Can't Add Your Folder Now' Error in Windows OneDrive Drive</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-group-policies-focusing-on-one-user-at-a-time/"><u>Tailoring Group Policies: Focusing on One User at a Time</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/the-ultimate-guide-to-free-youtube-intros-and-templates-for-2024/"><u>The Ultimate Guide to Free YouTube Intros & Templates for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-list-of-windows-11-navshortcuts/"><u>The Ultimate List of Windows 11 NavShortcuts</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-overcoming-black-screen-on-store-app/"><u>Tips for Overcoming Black Screen on Store App</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-5-ai-driven-reading-platforms-for-tailored-book-choices/"><u>Top 5 AI-Driven Reading Platforms for Tailored Book Choices</u></a></li>
<li><a href="https://windows11.techidaily.com/top-7-win-11-desk-aids-boosting-workflow/"><u>Top 7 Win 11 Desk Aids Boosting Workflow</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-zoom-error-1132-on-windows-11/"><u>Troubleshooting Zoom Error 1132 on Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/ultimate-guide-to-free-pptp-vpn-for-beginners-on-lava-blaze-2-pro-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Free PPTP VPN For Beginners On Lava Blaze 2 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-the-widget-toolbar-functionality-in-win11/"><u>Understanding the Widget Toolbar Functionality in Win11</u></a></li>
<li><a href="https://some-skills.techidaily.com/unlocking-the-potential-of-windows-movie-maker-in-windows-8-environments-for-2024/"><u>Unlocking the Potential of Windows Movie Maker in Windows 8 Environments for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-1011-auto-cleanup-a-step-by-step-guide/"><u>Windows 10/11 Auto-Cleanup: A Step-by-Step Guide</u></a></li>
</ul></div>
