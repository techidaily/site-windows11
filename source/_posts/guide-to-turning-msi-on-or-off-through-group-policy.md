---
title: Guide to Turning MSI On or Off Through Group Policy
date: 2024-08-22T21:31:53.049Z
updated: 2024-08-23T21:31:53.049Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Turning MSI On or Off Through Group Policy
excerpt: This Article Describes Guide to Turning MSI On or Off Through Group Policy
keywords: MSI Start/Stop via GPO,Enabling MSI with Group Policy,Disabling MSI Group Policy,Group Policy MSI Control,Manage MSI Settings via GPO,Turning On/Off MSI Via PC,Group Policy Management
thumbnail: https://thmb.techidaily.com/77a0a1507f5da99a4dd0db6a1e358f4e656bf9fb2de63da75eb278005236e188.jpg
---

## Guide to Turning MSI On or Off Through Group Policy

 Are you looking for a way to disable the Windows Installer Service on your device? This essential component of your operating system performs all necessary installation processes, but can sometimes interfere with other programs.

 Fortunately, there are three ways in which it can be disabled—using the Windows Service tool, Group Policy Editor, or Registry Editor. Check out our guide below to learn how.

## 1\. Use Windows Services

 Windows services are critical programs that typically initiate when you start your computer. It runs silently in the background and provides essential features to run the operating system. If you're looking to enable or disable Windows Installer service using this tool, do the following.

 To begin, press**Win + R** on your keyboard to launch the Run dialog box. In the text box, type**services.msc** , and hit enter. This will open the Services window.

![Disable Windows Installer Service Using Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-services-window.jpg)

 In the window that opens, scroll down until you find**Windows Installer** service then double-click on it for a properties window to open.

 Once you're in the Properties window, click the**Startup type** drop-down menu and select**Automatic** . Now move over towards the**Service status** section and click**Stop** .

![Disable Windows Installer Service Using Windows Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-windows-services.jpg)

 After you've done that, click**Apply** and then**OK** to save the changes. You have now successfully disabled the Windows Installer service on Windows 11.

 If you ever need to re-enable the service, follow the same procedure and click**Start** in the Service status section.

## 2\. Use Local Group Policy Editor

 You can also use the group policy editor to enable or disable the Windows Installer service on your Windows computer system. However, it is important to note that this tool only works on Windows Pro and Enterprise editions. Therefore, if you are using Windows Home Edition, you must first[activate the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 To disable the service using the group policy editor, do the following:

1. Click on Start and type in**gpedit.msc** , then press**Enter** to[launch the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) .
2. On the left side of the window, navigate to the path:  
`Computer Configuration > Administrative Templates > Windows Components > Windows Installer`
3. Now move to the right and double-click on the policy named**Turn off Windows Installer** .  
![Disable Windows Installer Service Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-group-policy.jpg)
4. In the window that opens, select**Enabled** in the radio box.
5. Under Options, click the drop-down menu and select**Always** .
6. Then click**Apply** and**OK** to save changes.

 That's all there is to it. The Windows Installer service will now be disabled on your system. To re-enable it, simply follow the same steps, but set "Turn off Windows Installer" to**Not Configured** .

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Use the Registry Editor

 Registry Editor is another method you can use to enable or disable the Windows Installer service on any version of Windows, even Home Edition. But make sure to proceed with caution as any incorrect changes can corrupt your system and force you to reinstall Windows. So be mindful and remember to back up your registry before making any modifications.

 To enable or disable this service using Registry Editor, follow these steps:

1. Press**Win + X** , type**regedit** , and press**Enter** to launch the Registry Editor. To learn more, see our guide on how to[open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. If prompted with a UAC warning, click**Yes** to continue.
3. Now once you're in, navigate to the following path:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\msiserver`
4. In the right panel, double-click on**Start** and change its value from**2** to**4** .  
![Disable Windows Installer Service Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-registry-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537546&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/7_copy_2_2_hdpro.png" border="0">HD Video Converter Factory Pro</a>
<!-- affiliate ads end -->
 Once you put the Value data, make sure the Base is set to**Hexadecimal** , then click**OK** . Now close the registry editor and restart your computer for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## Turning Off the Windows Installer Service Made Easy

 If Windows Installer Service is creating issues or hindering another application, you can easily turn it off with one of the three methods outlined in our guide. See which method works best for you and get back to what matters most.


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
<li><a href="https://buynow-reviews.techidaily.com/1722695673237-invest-less-to-charge-more-powerdrive-the-ultimate-budget-option-for-rapid-portable-electric-car-battery-packs/"><u>“Invest Less to Charge More: PowerDrive – The Ultimate Budget Option for Rapid Portable Electric Car Battery Packs</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-eliminating-virtual-reality-sickness-with-hint/"><u>[New] 2024 Approved  Eliminating Virtual Reality Sickness with Hint</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/reaking-down-the-system-behind-highlighted-video-comments-for-2024/"><u>[New] Breaking Down the System Behind Highlighted Video Comments for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-deciphering-authenticity-in-your-facebook-brand-community/"><u>[New] Deciphering Authenticity in Your Facebook Brand Community</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-grow-your-channelnode-through-joint-videography-endeavors/"><u>[New] Grow Your Channelnode Through Joint Videography Endeavors</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-best-10-video-card-selections-for-peak-streaming-performance/"><u>[New] In 2024, Best 10 Video Card Selections for Peak Streaming Performance</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-new-horizons-in-media-grasping-the-fundamentals-of-screen-resolution/"><u>[New] New Horizons in Media  Grasping the Fundamentals of Screen Resolution</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-online-meeting-transcriptions/"><u>[New] Online Meeting Transcriptions</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-the-pathway-to-professional-fb-reel-development/"><u>[New] The Pathway to Professional FB Reel Development</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-ultimate-drone-journey-full-phantom-4-features-explored/"><u>[New] The Ultimate Drone Journey  Full Phantom 4 Features Explored</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-the-zen-of-broadcasting-perfecting-zooms-techniques-for-youtube-for-2024/"><u>[New] The Zen of Broadcasting  Perfecting Zoom's Techniques for YouTube for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-1-5-best-editors-apart-from-youtube-platform-for-2024/"><u>[Updated] 1-#5 Best Editors Apart From YouTube Platform for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-dual-display-dominance-top-videographer-verdict/"><u>[Updated] 2024 Approved  Dual Display Dominance  Top Videographer Verdict</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-social-media-streamlining-connect-instagram-plus-facebook/"><u>[Updated] 2024 Approved  Social Media Streamlining  Connect Instagram + Facebook</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-broadcast-preservation-in-the-age-of-web-radio/"><u>[Updated] Broadcast Preservation in the Age of Web Radio</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-instagram-stories-beyond-just-daily-sharing/"><u>[Updated] Instagram Stories  Beyond Just Daily Sharing</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-spearheading-groundbre-folks-in-vr-space/"><u>2024 Approved  Spearheading Groundbre Folks In VR Space</u></a></li>
<li><a href="https://howto.techidaily.com/app-wont-open-on-your-xiaomi-redmi-13c-here-are-all-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>App Wont Open on Your Xiaomi Redmi 13C? Here Are All Fixes | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/digital-rehearsal-mastery-in-recording-streaming-audio/"><u>Digital Rehearsal  Mastery in Recording Streaming Audio</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723125192092-dive-into-technology-comprehensive-insights-from-our-tech-hub-post-toms-hardware/"><u>Dive Into Technology: Comprehensive Insights From Our Tech Hub, Post-Tom's Hardware!</u></a></li>
<li><a href="https://driver-download.techidaily.com/download-canon-printer-driver-compatible-with-windows-11-8-and-7/"><u>Download Canon Printer Driver: Compatible with Windows 11, 8 & 7</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-to-tackle-ms-store-hurdle-win1011s-error-0x0/"><u>Expert Advice to Tackle MS Store Hurdle: Win10/11's Error 0X0</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-non-starting-windows-indexing-service/"><u>Fixing Non-Starting Windows Indexing Service</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/free-guide-to-windows-desktop-captures-and-recordings/"><u>Free Guide to Windows Desktop Captures & Recordings</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-adjust-smartscreen-settings-for-win11-users/"><u>Guide: Adjust SmartScreen Settings for Win11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-how-to-generate-a-copernic-software-offline-license/"><u>Guide: How to Generate a Copernic Software Offline License</u></a></li>
<li><a href="https://windows11.techidaily.com/harnessing-windows-powers-for-linux-enhancement/"><u>Harnessing Windows Powers for Linux Enhancement</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-fix-apple-iphone-xs-passcode-not-working-by-drfone-ios/"><u>How to Fix Apple iPhone XS Passcode not Working?</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-a-disable-iphone-6-without-icloud-by-drfone-ios-unlock-ios-unlock/"><u>How to unlock a disable iPhone 6 without icloud</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-boosting-youtube-videos-activating-av1-support/"><u>In 2024, Boosting YouTube Videos  Activating AV1 Support</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-easy-guide-to-oppo-a1x-5g-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to Oppo A1x 5G FRP Bypass With Best Methods</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-lava-blaze-curve-5g-to-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Lava Blaze Curve 5G To Phone | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-what-legendaries-are-in-pokemon-platinum-on-vivo-v30-drfone-by-drfone-virtual-android/"><u>In 2024, What Legendaries Are In Pokemon Platinum On Vivo V30? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/initiate-your-adventure-joining-win-11-insiders/"><u>Initiate Your Adventure: Joining Win 11 Insiders</u></a></li>
<li><a href="https://windows11.techidaily.com/instantaneous-access-to-the-calculator-in-windows-11-os/"><u>Instantaneous Access to the Calculator in Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/introducing-specific-group-policy-enforcement-on-users-profiles-in-win-oses/"><u>Introducing Specific Group Policy Enforcement on Users' Profiles in Win OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/laymans-guide-to-setting-up-a-triple-column-board-on-windows-11/"><u>Layman's Guide to Setting Up a Triple Column Board on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-quick-finds-in-illustrator-a-complete-guide-using-copernic/"><u>Mastering Quick Finds in Illustrator: A Complete Guide Using Copernic</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-address-failed-boot-up-display-driver/"><u>Methods to Address Failed Boot-Up Display Driver</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-flawless-file-handling-discover-copernics-software-secrets-for-maximum-efficiency/"><u>Navigating Flawless File Handling: Discover Copernic's Software Secrets for Maximum Efficiency</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-low-usb-support-error-in-windows/"><u>Overcoming Low USB Support Error in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-outdated-windows-password-a-guide/"><u>Overcoming Outdated Window's Password: A Guide</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-ways-to-recover-deleted-files-from-honor-x50-gt-by-fonelab-android-recover-data/"><u>Possible ways to recover deleted files from Honor X50 GT</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/quick-content-in-a-facebook-frame/"><u>Quick Content in a Facebook Frame</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-lost-data-from-honor-magic-v2-by-fonelab-android-recover-data/"><u>Recover lost data from Honor Magic V2</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-clutter-in-windows-11s-selection-options/"><u>Reducing Clutter in Windows 11'S Selection Options</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagining-your-windows-11-search-experience/"><u>Reimagining Your Windows 11 Search Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-touchpad-glitches-on-your-windows-machine/"><u>Remedying Touchpad Glitches on Your Windows Machine</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionize-folder-management-selective-move-on-windows-11/"><u>Revolutionize Folder Management: Selective Move on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionizing-business-data-retrieval-with-advanced-copernic-search-tech-explained/"><u>Revolutionizing Business Data Retrieval with Advanced Copernic Search Tech Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/santa-skims-but-you-need-depth-discover-how-copernic-transforms-your-data-check-with-precision-and-ease/"><u>Santa Skims, But You Need Depth - Discover How Copernic Transforms Your Data Check with Precision and Ease!</u></a></li>
<li><a href="https://windows11.techidaily.com/step-into-yesteryear-classic-pc-gaming-via-dosbox-x/"><u>Step Into Yesteryear: Classic PC Gaming via DOSBox-X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-creating-self-extracting-fx-in-win11/"><u>Step-by-Step: Creating Self-Extracting FX in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategic-use-of-powertoys-locksmith-for-files/"><u>Strategic Use of PowerToys Locksmith for Files</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-malwarebytess-failed-execution-calls-on-windows-1011/"><u>Tackling Malwarebytes's Failed Execution Calls on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/take-charge-of-your-workspace-filter-and-theme-mastery-in-the-windows-11-task-manager/"><u>Take Charge of Your Workspace: Filter and Theme Mastery in the Windows 11 Task Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essentials-of-using-microsoft-family-safety/"><u>The Essentials of Using Microsoft Family Safety</u></a></li>
<li><a href="https://windows11.techidaily.com/the-snapshot-navigating-newly-active-windows-items/"><u>The Snapshot: Navigating Newly Active Windows Items</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-showdown-should-you-assemble-or-purchase-your-next-computing-system/"><u>The Ultimate Showdown: Should You Assemble or Purchase Your Next Computing System?</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-ways-copernic-enhances-your-work-from-home-experience/"><u>Top 5 Ways Copernic Enhances Your Work-From-Home Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/tracing-the-blue-screen-footsteps-in-windows-xp7/"><u>Tracing the Blue Screen Footsteps in Windows XP/7</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-your-cursor-display-with-windows-1011-tweaks/"><u>Transforming Your Cursor Display with Windows 10/11 Tweaks</u></a></li>
<li><a href="https://windows11.techidaily.com/trim-excessive-resource-use-of-antimalware-tools/"><u>Trim Excessive Resource Use of Antimalware Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-maxed-out-chatgpt-error/"><u>Troubleshooting Maxed Out ChatGPT Error</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-resolving-synapse-on-pcs-with-windows-11-and-10/"><u>Troubleshooting: Resolving Synapse on PCs with Windows 11 & 10</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-system-potential-mastery-of-win-registry-cli-edits/"><u>Unlocking System Potential: Mastery of Win Registry CLI Edits</u></a></li>
<li><a href="https://extra-tips.techidaily.com/unmatched-choice-our-top-8-no-cost-high-quality-video-software/"><u>Unmatched Choice  Our Top 8 No-Cost, High-Quality Video Software</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-gpo-details-using-gpresult/"><u>Unveiling GPO Details Using GPResult</u></a></li>
<li><a href="https://techidaily.com/ways-to-fix-the-failed-to-parse-the-corrupted-excel-2000-file-error-by-stellar-guide/"><u>Ways to Fix the Failed to Parse the Corrupted Excel 2000 File Error</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-configurations-simplified/"><u>Windows 11 Configurations Simplified</u></a></li>
<li><a href="https://driver-install.techidaily.com/windows-11-printing-perfection-new-hp-drivers-available/"><u>Windows 11 Printing Perfection - New HP Drivers Available</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-network-auditing-for-unguarded-ip-ports/"><u>Windows Network Auditing for Unguarded IP Ports</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-struggles-heres-how-to-install-icloud-seamlessly/"><u>Windows Struggles? Here’s How to Install iCloud Seamlessly</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-wisdom-commanding-app-and-browser-flow/"><u>Windows Wisdom: Commanding App & Browser Flow</u></a></li>
</ul></div>
