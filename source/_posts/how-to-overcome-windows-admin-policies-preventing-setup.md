---
title: How to Overcome Windows Admin Policies Preventing Setup
date: 2024-08-15T16:19:15.967Z
updated: 2024-08-16T16:19:15.967Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Overcome Windows Admin Policies Preventing Setup
excerpt: This Article Describes How to Overcome Windows Admin Policies Preventing Setup
keywords: Bypass WSOPs (Windows Admin),Disable Windows Configures,Unblock Windows Setup,Override Win Admin Policies,Eject Restricted Windows Install,Ignore WSOP in Setup,Circumvent Policy Blocks
thumbnail: https://thmb.techidaily.com/0464d20c8383250ad5eec7dae311ce3366a21c1ceecc558739dbb36535dbfcf9.jpg
---

## How to Overcome Windows Admin Policies Preventing Setup

 Installing software is usually a smooth process on Windows 10 and 11 PCs. However, sometimes installation hiccups can arise. For instance, some users have reported this error message appears when they try to install Windows software packages, “The system administrator has set policies to prevent this installation.”

 Users cannot install whatever programs for which that system administrator error arises. The error message suggests this issue is due to some kind of enforced admin settings. You can fix the “system administrator has set policies” error by applying the resolutions below.

## 1\. Run the Software’s Setup File as An Administrator

 First, start with the easiest of potential solutions. They don’t get much simpler than running the affected software’s installation file with administrative rights. Right-click the setup file for the software you can’t install and select **Run as administrator** on its context menu.

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-run-as-administrator-option.jpg)

## 2\. Enable the Built-in Windows Admin Account

 It has been confirmed by some users that activating and logging into the built-in (hidden) Windows admin account can fix the “system administrator has set policies” error. It’s recommended to try that even if your current user account is an administrative one. You can do that by following the instructions for the Command Prompt method in our guide to [enabling the built-in Windows administrator account](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/).

![The net user administrator /active:yes command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/net-user-admin-account-command.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->

 When you’ve activated the account, restart your Windows PC. Then sign in to the newly activated admin account and try installing the software you need from there. Disable the built-in administrator account when you’re done with it.

## 3\. Turn Off UAC (User Account Control)

 User Account Control is a security screen that can hinder the installation of programs when set at its highest setting. To ensure UAC isn’t causing any issues with installing software, temporarily turn off User Account Control by selecting its lowest **Never notify** option. You can apply this potential fix by disabling User Account Control with one of the methods in our [guide to turning off UAC](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/).

![The User Account Control Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-uac-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->

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

<!-- affiliate ads end -->
6. Select **Apply** \> **OK** to save the Windows Installer service settings.

<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
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
2. Double-click on **Enforcement**.  
![The Software Restriction Policies object types](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enforcement-option.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
3. Select the **All users except local administrators** radio button.  
![The Enforcement Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enforcement-properties-window.jpg)
4. Click the Enforcement Properties window’s **Apply** and **OK** options.
5. [Run Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/#:~:text=Press%20the%20Win%20%2B%20R%20on,Command%20Prompt%20with%20administrative%20privileges.) via the search utility.
6. Enter and execute this command for updating the policy:  
`gpupdate /force`
7. Exit the Command Prompt app and restart Windows.

## 6\. Edit the Installer Registry Key

 Editing an **Installer** registry key is a widely confirmed fix for the “system administrator has set policies” error. This registry tweak involves setting a **DisableMSI** DWORD value. You may also need to create a new **Installer** key from scratch if it’s not already there. These are the steps for applying this registry solution:

1. Click on the taskbar magnifying glass or Search box.
2. Type in a **regedit** search term to locate the Registry Editor app.
3. Select **Registry Editor** to start that app.
4. Input this path inside the Registry Editor address bar:  
`HKEY_LOCAL_MACHINE\Software\Policies\Microsoft\Windows\`
5. If you can’t see an **Installer** subkey, right-click the **Windows** key and select **New** \> **Key**. Users who can select an existing **Installer** subkey within the **Windows** key can skip through to step seven.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-new-key-options.jpg)

1. Enter **Installer** for the new key’s name.
2. Right-click the **Installer** key and select **New** \> **DWORD (32-bit) Value**.
3. Enter **DisableMSI** to be the title of the new DWORD.  
![the-disable-msi-dword](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-disable-msi-dword.jpg)
<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
4. Double-click **DisableMSI** inside the **Installer** key.
5. Make sure the **DisableMSI** value is set to **0**.  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-edit-dword-window.jpg)
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
6. Select **OK** to set the **DisableMSI** value.
7. Close Registry Editor and restart your PC.

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get Your Windows Software Installed

 The “system administrator has set policies” error is an old Windows issue many users have fixed with the troubleshooting methods covered in this guide. So, those are tried and tested resolutions that will likely fix the “system administrator has set policies” error on your PC. Then you can get all the Windows 10 and 11 software you need installed.

 Users cannot install whatever programs for which that system administrator error arises. The error message suggests this issue is due to some kind of enforced admin settings. You can fix the “system administrator has set policies” error by applying the resolutions below.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-crafting-musical-content-on-instagram/"><u>[New] In 2024, Crafting Musical Content on Instagram</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-mastering-teamsnap-essential-photography-tips/"><u>[New] Mastering TeamSnap  Essential Photography Tips</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-navigating-new-realities-metaverse-meets-omniverse/"><u>[New] Navigating New Realities  Metaverse Meets Omniverse</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-professional-posting-hacks-for-instagram-tv-for-2024/"><u>[New] Professional Posting Hacks for Instagram TV for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-profit-strategies-in-youtube-marketing/"><u>[New] Profit Strategies in YouTube Marketing</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-bridging-the-gap-between-facebook-videos-and-apple-tv-compatibility/"><u>[Updated] 2024 Approved  Bridging the Gap Between Facebook Videos and Apple TV Compatibility</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-pinnacle-programs-for-peak-webcam-video-quality/"><u>[Updated] 2024 Approved  Pinnacle Programs for Peak Webcam Video Quality</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-sharing-knowledge-via-instagrams-hyperlink-haven/"><u>[Updated] Sharing Knowledge via Instagram's Hyperlink Haven</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-hidden-recycling-bin-icon-on-windows-11/"><u>Activating Hidden Recycling Bin Icon on Windows 11</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/analysis-variety-in-fb-video-aspects/"><u>Analysis  Variety in FB Video Aspects</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/boosting-your-profile-top-25-high-gainning-instagram-tags-for-2024/"><u>Boosting Your Profile  Top 25 High-Gainning Instagram Tags for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/capture-the-essence-in-cloud-mix-free-space-plus-charged-backup-sanctuaries-for-2024/"><u>Capture the Essence in Cloud  Mix Free Space + Charged Backup Sanctuaries for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-honor-x50-gt-by-drfone-android/"><u>Complete Review & Guide to Techeligible FRP Bypass and More For Honor X50 GT</u></a></li>
<li><a href="https://fox-glue.techidaily.com/curating-the-perfect-day-to-unveil-podcast-content-for-2024/"><u>Curating the Perfect Day to Unveil Podcast Content for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-windows-strategies-for-device-id-discovery/"><u>Essential Windows Strategies for Device ID Discovery</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-tecno-pova-5-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Tecno Pova 5 Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-highlight-the-mouse-cursor-in-windows-10-and-11/"><u>How to Highlight the Mouse Cursor in Windows 10 & 11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-step-into-success-beginners-guide-to-hosting-tech-product-discussions-online/"><u>In 2024, Step-Into Success  Beginner’s Guide to Hosting Tech Product Discussions Online</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-ultimate-hunt-for-premium-costless-lut-files/"><u>In 2024, The Ultimate Hunt for Premium, Costless LUT Files</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-unlocking-mov-recording-potential-win-11s-top-six-methods/"><u>In 2024, Unlocking .MOV Recording Potential  Win 11'S Top Six Methods</u></a></li>
<li><a href="https://android-frp.techidaily.com/latest-guide-how-to-bypass-samsung-galaxy-a05-frp-without-computer-by-drfone-android/"><u>Latest Guide How To Bypass Samsung Galaxy A05 FRP Without Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/making-your-files-automatically-accessible-in-win11/"><u>Making Your Files Automatically Accessible in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11s-full-screen-with-sonic-games/"><u>Mastering Windows 11'S Full Screen with Sonic Games</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-disabled-trash-can-symbol-on-win11-os/"><u>Mending Disabled Trash Can Symbol on Win11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/momentum-builds-for-windows-11-the-future-shines-in-22h2/"><u>Momentum Builds for Windows 11: The Future Shines in 22H2</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-frequent-microsoft-teams-authentication-failures/"><u>Navigating Frequent Microsoft Teams Authentication Failures</u></a></li>
<li><a href="https://windows11.techidaily.com/regain-classic-text-bar-with-icons-for-windows-11s-search/"><u>Regain Classic Text Bar with Icons for Windows 11'S Search</u></a></li>
<li><a href="https://windows11.techidaily.com/revealing-secrets-unmasking-the-facade-of-restricted-communication/"><u>Revealing Secrets: Unmasking the Facade of Restricted Communication</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-method-for-adobe-reader-purchase-in-microsoft-store/"><u>Secure Method for Adobe Reader Purchase in Microsoft Store</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-jdk-on-windows-11-a-step-by-step-guide/"><u>Setting Up JDK on Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-steam-downloads-secrets-for-windows-gamers/"><u>Speedy Steam Downloads: Secrets for Windows Gamers</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-stop-vmware-blue-screen-in-win11/"><u>Strategies to Stop VMware Blue Screen in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/technique-to-automate-microsoft-words-attachment-display-in-read-only-view/"><u>Technique to Automate Microsoft Word's Attachment Display in Read-Only View</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-prolong-windows-10-closure-with-ongoing-processes/"><u>Techniques to Prolong Windows 10 Closure with Ongoing Processes</u></a></li>
<li><a href="https://fake-location.techidaily.com/the-best-8-vpn-hardware-devices-reviewed-on-samsung-galaxy-m54-5g-drfone-by-drfone-virtual-android/"><u>The Best 8 VPN Hardware Devices Reviewed On Samsung Galaxy M54 5G | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-ultimate-drone-journey-full-phantom-4-features-explored-for-2024/"><u>The Ultimate Drone Journey  Full Phantom 4 Features Explored for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/top-9-pc-advantages-over-macs/"><u>Top 9: PC Advantages Over Macs</u></a></li>
<li><a href="https://windows11.techidaily.com/top-bargains-on-windows-11-product-codes/"><u>Top Bargains on Windows 11 Product Codes</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-required-items-not-met-in-win11win11/"><u>Troubleshooting Required Items Not Met in Win11/Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-off-superfluous-windows-notification-tabs/"><u>Turn Off Superfluous Windows Notification Tabs</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-prohibited-windows-based-program/"><u>Unblocking Prohibited Windows-Based Program</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-unavailable-drive-letters-on-windows-os/"><u>Understanding Unavailable Drive Letters on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/what-sets-exe-installers-apart-from-standard-msis/"><u>What Sets Exe Installers Apart From Standard MSIs?</u></a></li>
<li><a href="https://windows11.techidaily.com/why-choose-dxvk-a-game-changer-on-your-windows-system/"><u>Why Choose DXVK: A Game Changer on Your Windows System?</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-meets-virtual-box-70-a-detailed-guide-for-the-tech-savvy/"><u>Windows 11 Meets Virtual Box 7.0: A Detailed Guide for the Tech-Savvy</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-reclaiming-precise-search-functionality/"><u>Windows 11: Reclaiming Precise Search Functionality</u></a></li>
<li><a href="https://extra-tips.techidaily.com/zoom-for-broadcasts-bridging-the-gap-to-fb-live/"><u>ZOOM for Broadcasts  Bridging the Gap to FB Live</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>