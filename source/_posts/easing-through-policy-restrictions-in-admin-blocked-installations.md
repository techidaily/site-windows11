---
title: Easing Through Policy Restrictions in Admin-Blocked Installations
date: 2024-08-15T15:40:15.736Z
updated: 2024-08-16T15:40:15.736Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Easing Through Policy Restrictions in Admin-Blocked Installations
excerpt: This Article Describes Easing Through Policy Restrictions in Admin-Blocked Installations
keywords: Policy Limits Overview,Administrative Blocks Guide,Software Installation Tips,Manage Permissions Effectively,Adapting to Admin Policies,Bypass Restrictions Efficiently,Optimizing Unblocked Settings
thumbnail: https://thmb.techidaily.com/84b555054820124f11889e906637732ab71a15523e1f3cc982eace446c58606e.jpg
---

## Easing Through Policy Restrictions in Admin-Blocked Installations

 Installing software is usually a smooth process on Windows 10 and 11 PCs. However, sometimes installation hiccups can arise. For instance, some users have reported this error message appears when they try to install Windows software packages, “The system administrator has set policies to prevent this installation.”

 Users cannot install whatever programs for which that system administrator error arises. The error message suggests this issue is due to some kind of enforced admin settings. You can fix the “system administrator has set policies” error by applying the resolutions below.

## 1\. Run the Software’s Setup File as An Administrator

 First, start with the easiest of potential solutions. They don’t get much simpler than running the affected software’s installation file with administrative rights. Right-click the setup file for the software you can’t install and select **Run as administrator** on its context menu.

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-run-as-administrator-option.jpg)

## 2\. Enable the Built-in Windows Admin Account

 It has been confirmed by some users that activating and logging into the built-in (hidden) Windows admin account can fix the “system administrator has set policies” error. It’s recommended to try that even if your current user account is an administrative one. You can do that by following the instructions for the Command Prompt method in our guide to [enabling the built-in Windows administrator account](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/).

![The net user administrator /active:yes command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/net-user-admin-account-command.jpg)

 When you’ve activated the account, restart your Windows PC. Then sign in to the newly activated admin account and try installing the software you need from there. Disable the built-in administrator account when you’re done with it.

## 3\. Turn Off UAC (User Account Control)

 User Account Control is a security screen that can hinder the installation of programs when set at its highest setting. To ensure UAC isn’t causing any issues with installing software, temporarily turn off User Account Control by selecting its lowest **Never notify** option. You can apply this potential fix by disabling User Account Control with one of the methods in our [guide to turning off UAC](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/).

![The User Account Control Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-uac-settings.jpg)

## 4\. Run or Restart the Windows Installer Service

 Windows Installer is a service that needs to be running for users to install software with MSI packages. So, check that service is enabled and running. Even if it is, restarting that service might also resolve the “system administrator has set policies” error. This is how you can run or restart Windows Installer:

1. To access the file finder tool, right-click **Start** and select the **Search** shortcut.
2. Next, input a **services** search phrase.
3. Click the **Services** app found by the search tool.
4. Double-click **Windows Installer** to see that service’s property settings.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-services-window.jpg)
5. If the service is stopped, click its **Start** button. Or select **Stop** and **Start** to restart Windows Installer.  
![The Windows Installer Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-windows-installer-properties-service-window.jpg)
<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Select **Apply** \> **OK** to save the Windows Installer service settings.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
## 5\. Change Group Policy Settings

 Lots of users have fixed the “system administrator has set policies” error by setting the Windows Installer policy to never disable Windows Installer. However, you will need to access Local Group Policy Editor, available in the Windows Pro and Enterprise editions, to apply this potential fix. If you can utilize that tool, change the **Turn Off Windows Installer** policy like this:

1. Press **Win + R**, input the **gpedit.msc** command, and click **OK** to [openLocal Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
2. Double-click on **Computer Configuration** and **Administrative Templates** inside Group Policy’s left sidebar.
3. Then go to **Windows Components** \> **Windows Installer** to access policy settings.
4. Double-click the **Turn off Windows Installer** policy setting.  
![The Turn off Windows Installer policy setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-installer-policy-settings.jpg)
5. Select **Enabled** if that option isn’t already set.
6. Then click **Never** on the **Disable Windows Installer** drop-down menu.  
![The Never option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-never-option.jpg)
<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
7. Select the policy window’s **Apply** and **OK** options.

 On top of that, delete software restriction policies. These are the steps for deleting software restriction policies:

1. Double-click **Windows Settings** \> **Security Settings** in Group Policy’s sidebar.
2. Right-click **Software Restriction Policies** and select **Delete Software Restriction Policies** if that option is available.  
![delete-software-restriction-policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/delete-software-restriction-policies.jpg)
3. Click **Yes** to confirm the deletion of software restriction policies.

 Some users also say they went even further and created a new software restriction policy in Group Policy Editor to resolve the “system administrator has set policies” error. You can try doing that after selecting to delete software restriction policies. Create a new software restriction policy like this:

1. Click **Software Restriction Policies** with the right mouse button to select **New Software Restriction Policies**.  
![The New Software Restriction Policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-software-restriction-policies.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
2. Double-click on **Enforcement**.  
![The Software Restriction Policies object types](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enforcement-option.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
3. Select the **All users except local administrators** radio button.  
![The Enforcement Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enforcement-properties-window.jpg)
4. Click the Enforcement Properties window’s **Apply** and **OK** options.
5. [Run Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/#:~:text=Press%20the%20Win%20%2B%20R%20on,Command%20Prompt%20with%20administrative%20privileges.) via the search utility.
6. Enter and execute this command for updating the policy:  
`gpupdate /force`
7. Exit the Command Prompt app and restart Windows.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Edit the Installer Registry Key

 Editing an **Installer** registry key is a widely confirmed fix for the “system administrator has set policies” error. This registry tweak involves setting a **DisableMSI** DWORD value. You may also need to create a new **Installer** key from scratch if it’s not already there. These are the steps for applying this registry solution:

1. Click on the taskbar magnifying glass or Search box.
2. Type in a **regedit** search term to locate the Registry Editor app.
3. Select **Registry Editor** to start that app.
4. Input this path inside the Registry Editor address bar:  
`HKEY_LOCAL_MACHINE\Software\Policies\Microsoft\Windows\`
5. If you can’t see an **Installer** subkey, right-click the **Windows** key and select **New** \> **Key**. Users who can select an existing **Installer** subkey within the **Windows** key can skip through to step seven.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-new-key-options.jpg)
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Enter **Installer** for the new key’s name.
2. Right-click the **Installer** key and select **New** \> **DWORD (32-bit) Value**.
3. Enter **DisableMSI** to be the title of the new DWORD.  
![the-disable-msi-dword](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-disable-msi-dword.jpg)
4. Double-click **DisableMSI** inside the **Installer** key.
5. Make sure the **DisableMSI** value is set to **0**.  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-edit-dword-window.jpg)
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Select **OK** to set the **DisableMSI** value.
7. Close Registry Editor and restart your PC.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
## Get Your Windows Software Installed

 The “system administrator has set policies” error is an old Windows issue many users have fixed with the troubleshooting methods covered in this guide. So, those are tried and tested resolutions that will likely fix the “system administrator has set policies” error on your PC. Then you can get all the Windows 10 and 11 software you need installed.

 Users cannot install whatever programs for which that system administrator error arises. The error message suggests this issue is due to some kind of enforced admin settings. You can fix the “system administrator has set policies” error by applying the resolutions below.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-uploading-and-showcasing-videos-on-instagram-made-easy/"><u>[New] 2024 Approved  Uploading and Showcasing Videos on Instagram Made Easy</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/eciphering-adsense-profits-on-youtube-revenue-per-kv-watched-for-2024/"><u>[New] Deciphering AdSense Profits on YouTube  Revenue per KV Watched for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-navigating-fade-inout-processes-in-audacity/"><u>[New] Navigating Fade-In/Out Processes in Audacity</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-tune-and-trends-a-guide-to-sound-in-social-media-snapshots/"><u>[New] Tune & Trends  A Guide to Sound in Social Media Snapshots</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-the-insiders-guide-to-recording-on-itunes/"><u>[Updated] 2024 Approved  The Insider's Guide to Recording on iTunes</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-ultimate-guide-to-sharper-meeting-experience-with-google/"><u>[Updated] In 2024, Ultimate Guide to Sharper Meeting Experience with Google</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-instagram-highlight-cover-art-inspiration-and-techniques-guide-for-2024/"><u>[Updated] Instagram Highlight Cover Art  Inspiration & Techniques Guide for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-safeguarding-photos-best-software-guide-uncovered/"><u>2024 Approved  Safeguarding Photos  Best Software Guide Uncovered</u></a></li>
<li><a href="https://review-topics.techidaily.com/4-feasible-ways-to-fake-location-on-facebook-for-your-tecno-spark-20-proplus-drfone-by-drfone-virtual-android/"><u>4 Feasible Ways to Fake Location on Facebook For your Tecno Spark 20 Pro+ | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/6-routines-to-reclaim-your-desktops-daytime-look/"><u>6 Routines To Reclaim Your Desktop's Daytime Look</u></a></li>
<li><a href="https://windows11.techidaily.com/7-solutions-when-apps-arent-working-properly-on-windows/"><u>7 Solutions When Apps Aren't Working Properly on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/8-red-flags-before-factory-resetting-your-machine/"><u>8 Red Flags Before Factory Resetting Your Machine</u></a></li>
<li><a href="https://unlock-android.techidaily.com/a-complete-guide-to-oem-unlocking-on-infinix-smart-8-plus-by-drfone-android/"><u>A Complete Guide To OEM Unlocking on Infinix Smart 8 Plus</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-launch-times-for-windows-11-apps/"><u>Accelerate Launch Times for Windows 11 Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-win-valorant-loading-times-quickly/"><u>Accelerate Win-Valorant Loading Times Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/android-meets-windows-easy-synching-protocol/"><u>Android Meets Windows: Easy Synching Protocol</u></a></li>
<li><a href="https://windows11.techidaily.com/arrow-keys-in-distress-heres-what-you-can-do/"><u>Arrow Keys in Distress? Here's What You Can Do</u></a></li>
<li><a href="https://windows11.techidaily.com/best-slate-companions-selecting-top-7-windows-tabs/"><u>Best Slate Companions: Selecting Top 7 Windows Tabs</u></a></li>
<li><a href="https://windows11.techidaily.com/bold-windows-11-remove-curved-edges/"><u>Bold Windows 11: Remove Curved Edges</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-productivity-and-grades-essential-study-methods-on-a-windows-pc/"><u>Boost Productivity and Grades: Essential Study Methods on a Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/breakdown-how-law-filters-transform-your-windows-experience/"><u>Breakdown: How LAW Filters Transform Your Windows Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/browser-woes-7-methods-to-reach-elusive-pages-on-pc/"><u>Browser Woes? 7 Methods to Reach Elusive Pages on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-windows-11-pc-life-hacks-for-older-systems/"><u>Bypass Windows 11: PC Life Hacks for Older Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/choosing-a-fresh-termbackground-pic/"><u>Choosing a Fresh TermBackground Pic</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-procedure-call-failures-in-malwarebytes-for-windows-os/"><u>Combatting Procedure Call Failures in Malwarebytes for Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-erratic-movement-7-windows-mouse-solutions/"><u>Conquer Erratic Movement: 7 Windows Mouse Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/correct-keyboard-fixes-for-windows-11s-unresponsive-f-keys/"><u>Correct: Keyboard Fixes for Windows 11'S Unresponsive F Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-quick-repair-pathways-creating-custom-win-shortcuts/"><u>Crafting Quick Repair Pathways: Creating Custom Win Shortcuts</u></a></li>
<li><a href="https://windows11.techidaily.com/create-a-gratis-local-gptclone-with-gpt4all-for-windows/"><u>Create a Gratis, Local GPTClone with GPT4All for Windows</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/dailymotion-vs-youtubes-revenue-battle-analysis/"><u>Dailymotion vs YouTubes  Revenue Battle Analysis</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-filehistoryfaults-in-windows-os/"><u>Dealing with FileHistoryFaults in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-success-in-playing-ps1-games-on-win-with-duckstations-tips/"><u>Deciphering Success in Playing PS1 Games on WIN with Duckstation’s Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-workings-of-windows-memory-cache/"><u>Deciphering the Workings of Windows Memory Cache</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-windows-11s-backup-and-sync-an-overview-of-its-functionality/"><u>Deciphering Windows 11’S Backup & Sync: An Overview of Its Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-x80070091-error-in-windows-steps-for-empty-directory-problem-solving/"><u>Deciphering X80070091 Error in Windows - Steps for 'Empty Directory' Problem Solving</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/enhancing-video-calls-incorporating-snap-camera-on-teams/"><u>Enhancing Video Calls  Incorporating Snap Camera on Teams</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/flawlessrecorder-suite-w10-edition/"><u>FlawlessRecorder Suite W10 Edition</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-the-soft-bricked-oneplus-12r-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix the Soft Bricked OnePlus 12R? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-apple-iphone-se-withwithout-sim-card-by-drfone-ios/"><u>How to Unlock Apple iPhone SE with/without SIM Card</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-apple-id-from-apple-iphone-12-pro-without-password-by-drfone-ios/"><u>In 2024, How to Remove Apple ID from Apple iPhone 12 Pro without Password?</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-imei-unlokers-for-your-samsung-galaxy-m14-4g-phone-by-drfone-android/"><u>In 2024, Top IMEI Unlokers for Your Samsung Galaxy M14 4G Phone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-blur-unwanted-parts-of-your-videos-with-these-mobile-apps/"><u>New Blur Unwanted Parts of Your Videos with These Mobile Apps</u></a></li>
<li><a href="https://games-able.techidaily.com/scores-dont-count-the-real-deal-with-game-reviews/"><u>Scores Don't Count: The Real Deal with Game Reviews</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-10-and-missing-cursor-mystery-solved-tips-and-fixes/"><u>Windows 10 and Missing Cursor Mystery Solved – Tips & Fixes!</u></a></li>
</ul></div>
