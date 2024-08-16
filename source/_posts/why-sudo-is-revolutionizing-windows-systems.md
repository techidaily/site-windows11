---
title: Why Sudo Is Revolutionizing Windows Systems
date: 2024-08-15T15:51:25.556Z
updated: 2024-08-16T15:51:25.556Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Why Sudo Is Revolutionizing Windows Systems
excerpt: This Article Describes Why Sudo Is Revolutionizing Windows Systems
keywords: Sudo Impact Windows,System Security Sudo,Sudo Windows Control,Sudo Enhances PCs,Sudo OS Improvement,Secure Sudo Windows,Efficient Sudo Systems
thumbnail: https://thmb.techidaily.com/f0f1add4f06bedd9b4441c0d9e38e221d87204ef26ea2cde0e10ae3ca9b9c9f6.jpg
---

## Why Sudo Is Revolutionizing Windows Systems

### Key Takeaways

* The sudo command on Windows lets you run commands with elevated privileges.
* Microsoft is introducing sudo in Windows 11 to make using the command line more convenient.
* Enable sudo via Settings, the Command Prompt, or PowerShell.

 If you're a fan of tweaking your Windows setup, you often need to run "elevated" or Administrator-level commands. You're probably used to doing this by running a Command Prompt as administrator, but it's about to get a lot easier with sudo on Windows.

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
## What Does the sudo Command Do?

 Despite the general focus on configuring everything through the Settings apps and easy-to-use configuration wizards on Windows, every once in a while, you still need to type in commands. Many of these won't work with your standard user account. Instead, you need to run them as an administrator. Requiring administrator permissions is still a relatively new concept in Windows, but it was prevalent for far longer in older operating systems.

 It was so prevalent that operating system developers thought about a solution to the problem decades ago. Unix installations had, and still do have, a `su` command, which means "switch user." This would allow you to switch accounts to any other user, but could also let you run as the administrator, or superuser, account of the system by default.

 This solution worked, but logging in as the administrator to run one command seemed like overkill. As a solution, developers created the sudo command, which means either "switch user and do," or "superuser do," depending on various opinions. Long story short, the sudo command lets you easily run one command with elevated privileges—we've covered [the differences between su and sudo](http://www.makeuseof.com/sudo-vs-su/) if you're curious.

 This means that the sudo command is roughly equivalent to right-clicking on the Command Prompt app, selecting **Run as administrator**, and running a command, like `do_something`. With the help of the sudo command, you don't need to worry about remembering to run the Command Prompt as administrator. Instead, simply type `sudo do_something`, and the command will work in exactly the same way.

## Which Windows Versions Can Run the sudo Command?

 Microsoft is adding the sudo command to Windows 11, and considering that support for Windows 10 is winding down, we don't expect to see the command coming there anytime soon. At the time of writing, the sudo command is only available for Windows Insider participants (builds 26045 and later), specifically those on the Developer and [Windows Canary channels](https://www.makeuseof.com/what-is-windows-insider-canary-channel/).

 Unlike some features that Microsoft tests in these versions, it seems fairly likely that sudo is going to arrive on the operating system soon.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Enable the sudo Command on Windows

 If the sudo command isn't yet available for your version of Windows, you'll need to [sign up for Windows Insider](https://www.makeuseof.com/windows-11-insider-program-join/). This is a simple process, but be warned: the Developer and Canary options can be unstable, so don't use them on a PC you're not willing to lose data on.

 Once you're running a version of Windows that has the sudo command available, enabling it is a simple process. Open the **Settings** app, then select **System** on the left and **For developers** from the main area of the window.

 Here, scroll down and enable the checkbox that reads **Enable sudo**.

![Enabling sudo on Window in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-window-in-the-settings-app.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
### Enable sudo via the Command Prompt

 If you're more command-line oriented, you can also enable sudo via the Commmand Prompt. Somewhat ironically, this requires you to run an elevated CMD window. Press the **Windows** key, type "command," then right-click on **Command Prompt** (or **PowerShell**) and select **Run as administrator**.

 In this prompt, run the following command:

`sudo config --enable enable`

![Enabling sudo on Windows via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-windows-via-powershell.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Use the sudo Command on Windows

 After you've enabled the sudo command on Windows, it's simple to use. Simply prepend the `sudo` command to any command you'd typically need to run as an administrator, then accept the prompts that follow.

 An example from Microsoft uses the `netstat` command:

`sudo netstat -ab  
`

![Running a command on Windows via sudo](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/running-a-command-on-windows-via-sudo.jpg)
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->

 This feature may seem a tad unnecessary—and for many people, it is. That said, if you spend your day running command after command on Windows and wish for the simplicity of the sudo command, its addition will make your life easier.

 Microsoft seems committed to its implementation of sudo, even going so far as to release [sudo on GitHub](http://github.com/microsoft/sudo) as open source. If reading this entices you to learn more about what goes on under the hood in Windows, make sure to take a look at our list of [commands every Windows user should know](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/).

 If you're a fan of tweaking your Windows setup, you often need to run "elevated" or Administrator-level commands. You're probably used to doing this by running a Command Prompt as administrator, but it's about to get a lot easier with sudo on Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-tips.techidaily.com/new-craft-the-harmony-editing-and-merging-sounds-in-windows-11-videos/"><u>[New] Craft the Harmony  Editing & Merging Sounds in Windows 11 Videos</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-lens-legends-best-video-cameras-for-professional-use/"><u>[Updated] In 2024, Lens Legends  Best Video Cameras for Professional Use</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-masterclass-setting-up-your-first-facebook-page-for-2024/"><u>[Updated] Masterclass  Setting Up Your First Facebook Page for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-relaxed-riffs-20-country-songs-that-make-you-want-to-dance-and-chill-on-tiktok-for-2024/"><u>[Updated] Relaxed Riffs  20 Country Songs That Make You Want to Dance and Chill on TikTok for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-windows-best-video-conferencing-apps-2-1/"><u>[Updated] Windows' Best Video Conferencing Apps, #2-#1</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-where-to-find-high-quality-pixel-ringers/"><u>2024 Approved  Where to Find High-Quality Pixel Ringers</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-fake-gps-without-root-on-realme-v30t-drfone-by-drfone-virtual-android/"><u>3 Ways to Fake GPS Without Root On Realme V30T | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/8-solutions-to-solve-youtube-app-crashing-on-oppo-reno-10-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Solutions to Solve YouTube App Crashing on Oppo Reno 10 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/a-working-guide-for-pachirisu-pokemon-go-map-on-vivo-y200-drfone-by-drfone-virtual-android/"><u>A Working Guide For Pachirisu Pokemon Go Map On Vivo Y200 | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/advanced-hdr-creation-in-photoshop-workflows-for-2024/"><u>Advanced HDR Creation in Photoshop Workflows for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/brother-hl-l2n60dw-printer-drivers-download-free-and-official/"><u>Brother HL-L2n60DW Printer Drivers Download – Free & Official</u></a></li>
<li><a href="https://vp-tips.techidaily.com/elevate-your-articles-with-proper-slug-lines/"><u>Elevate Your Articles with Proper Slug Lines</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-win-compatibility-troubleshooting-guide/"><u>Expert Tips: Win Compatibility Troubleshooting Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-windows-pathways-to-filefolder-secrets/"><u>Expert Windows Pathways to File/Folder Secrets</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-error-0x8019-in-windows-updates/"><u>Fixing Error 0X8019 in Windows Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/from-novice-to-pro-mastering-github-desktop-on-windows-11/"><u>From Novice to Pro: Mastering GitHub Desktop on Windows 11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/guided-approach-to-saving-exact-youtube-segments-for-2024/"><u>Guided Approach to Saving Exact YouTube Segments for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-activatedeactivate-vm-security-with-secure-boot-on-virtualbox-70/"><u>How to Activate/Deactivate VM Security with Secure Boot on VirtualBox 7.0</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-win11-from-showing-00-error-codes/"><u>How to Stop Win11 From Showing 00 Error Codes</u></a></li>
<li><a href="https://windows11.techidaily.com/ideal-choices-premium-windows-systems-for-switch-gaming/"><u>Ideal Choices: Premium Windows Systems for Switch Gaming</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-oppo-a38-by-phone-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Oppo A38 by Phone Number | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-use-ispoofer-on-realme-gt-3-drfone-by-drfone-virtual-android/"><u>In 2024, How to use iSpoofer on Realme GT 3? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/managing-windows-modules-installer-resource-demand/"><u>Managing Windows Modules Installer Resource Demand</u></a></li>
<li><a href="https://windows11.techidaily.com/master-note-taking-on-win11-easy-as-pie/"><u>Master Note-Taking on Win11, Easy as Pie</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/master-the-art-of-audio-alteration-in-sony-games/"><u>Master the Art of Audio Alteration in Sony Games</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-1drive-operation-restoration-in-windows-os/"><u>Mastering 1Drive Operation Restoration in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-fixes-for-hardware-detection-faults/"><u>Mastering Fixes for Hardware Detection Faults</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-sefx-windows-11-sfx-creation/"><u>Mastering SEFX: Windows 11 SFX Creation</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-the-best-virtualdub-alternatives-a-review-of-top-video-editing-tools/"><u>New The Best Virtualdub Alternatives A Review of Top Video Editing Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-microphone-performance-with-xbox-app-windows-11/"><u>Optimizing Microphone Performance with Xbox App Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-grayscale-windows-backdrops-tips-for-enhancement/"><u>Overcoming Grayscale Windows Backdrops: Tips for Enhancement</u></a></li>
<li><a href="https://windows11.techidaily.com/preventive-measures-for-csgo-launch-woes-on-windows-11/"><u>Preventive Measures for CS:GO Launch Woes on Windows 11</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/pros-and-cons-free2webcam-software-analysis-for-2024/"><u>Pros & Cons  Free2WebCam Software Analysis for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-lsa-errors-on-windows-pcs/"><u>Quick Fixes for LSA Errors on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-the-heat-lowering-cpu-consumption-in-setups/"><u>Reducing the Heat: Lowering CPU Consumption in Setups</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-issues-for-microsoft-store-access-on-windows-11/"><u>Resolving Issues for Microsoft Store Access on Windows 11</u></a></li>
<li><a href="https://games-able.techidaily.com/1719166879528-revitalize-your-pc-with-the-newest-nvidia-driver-update/"><u>Revitalize Your PC with the Newest Nvidia Driver Update</u></a></li>
<li><a href="https://data-wizards.techidaily.com/stellar-software-quick-downloads/"><u>Stellar Software: Quick Downloads</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/step-by-step-approach-to-saving-instagram-stories/"><u>Step-by-Step Approach to Saving Instagram Stories</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-ax201-wi-fi-6-error-on-windows/"><u>Steps to Resolve AX201 Wi-Fi 6 Error on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-windows-app-start-counter/"><u>Stop Windows App Start Counter</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-development-essential-wsl-2-tips-for-pcs/"><u>Streamlining Development: Essential WSL 2 Tips for PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/systematic-steps-for-nullifying-your-windows-drive-partitions/"><u>Systematic Steps for Nullifying Your Windows Drive Partitions</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-deal-with-missing-values-on-pcs-running-winos/"><u>Techniques to Deal with Missing Values on PCs Running WinOS</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-comprehensive-tutorial-on-tuning-into-hulu-from-your-lg-smart-tv-screen/"><u>The Comprehensive Tutorial on Tuning Into Hulu From Your LG Smart TV Screen</u></a></li>
<li><a href="https://techidaily.com/top-8-iphone-13-pro-smsmessagetext-recovery-software-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Top 8 iPhone 13 Pro SMS/Message/Text Recovery Software | Stellar</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-hidden-potential-in-vintage-video-gaming-titles-using-retroarch/"><u>Unlocking Hidden Potential in Vintage Video Gaming Titles Using Retroarch</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-microsoft-family-safety-potential/"><u>Unlocking Microsoft Family Safety Potential</u></a></li>
<li><a href="https://windows11.techidaily.com/unmasking-windows-not-found-top-fixes-and-strategies/"><u>Unmasking Windows 'Not Found': Top Fixes and Strategies</u></a></li>
<li><a href="https://change-location.techidaily.com/unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-samsung-galaxy-a15-5g-drfone-by-drfone-virtual-android/"><u>Unova Stone Pokémon Go Evolution List and How Catch Them For Samsung Galaxy A15 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-vivetool-enable-unseen-features-on-windows-pcs/"><u>Unraveling ViVeTool: Enable Unseen Features on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-the-0x0000003b-bsod-in-windows-heres-how-to-fix-it/"><u>What Is the 0X0000003B BSOD in Windows? Here's How to Fix It</u></a></li>
<li><a href="https://windows11.techidaily.com/workaround-for-win10-and-11s-audacity-device-opening-issue/"><u>Workaround for Win10 & 11’S Audacity Device Opening Issue</u></a></li>
</ul></div>
