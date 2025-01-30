---
title: 10 Ways to Clean Up Your Firewall Rules
date: 2025-01-27T18:34:30.614Z
updated: 2025-01-29T19:54:32.321Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 10 Ways to Clean Up Your Firewall Rules
excerpt: This Article Describes 10 Ways to Clean Up Your Firewall Rules
keywords: Firewall Optimization Tips,Streamlining Firewall Rules,Enhancing Network Security,Firewall Management Strategies,Simplifying Firewall Configurations,Firewall Rule Cleanup Guide,Improving Firewall Efficiency
thumbnail: https://thmb.techidaily.com/4740430244a268b3ae9a4b1e15c683b234a7cf8bdf323c545591ca9aaa0e0818.jpg
---

## 10 Ways to Clean Up Your Firewall Rules

 The Windows Firewall protects your device from malicious threats. But if you don't configure its settings correctly, this tool might prevent you from accessing most of the apps on your device.

 So, what's the solution if you've configured the wrong firewall settings by mistake? It's simple—all you need to do is reset these settings to their defaults.

 Let’s dive in and explore all the solutions.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vQbNyknjJJ8?si=RGVIEWLdPbvRC_r6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Use the Control Panel

 The Control Panel is an incredible tool that allows you to troubleshoot system issues or tweak PC settings. Now, let’s check out how this tool can help you reset the firewall settings:

1. Type **Control Panel** in the Start menu search bar and select the **Best match**. Alternatively, check out [the various way to access the Control Panel](https://www.makeuseof.com/windows-open-control-panel/).
2. Click the **View by** drop-down menu and select either the **Small icons** or **Large icons** option.
3. Select **Windows Defender Firewall** from the menu items.
4. Click the **Restore defaults** option on the left-hand side and follow the on-screen instructions.

![Clicking the Restore defaults option on the Windows Defender Firewall screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/clicking-the-restore-defaults-option-on-the-windows-defender-firewall-screen.jpg)

## 2\. Use the Command Prompt

 Ever used the Command Prompt before? It’s an incredible tool that helps you configure system settings, troubleshoot PC issues, and access various apps.

 In fact, you can perform a lot of tasks with this tool as long as you [type in the correct commands](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/).

 Now, let’s check out how to reset the firewall settings using the Command Prompt:

1. Type **Command Prompt** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as administrator**.
3. Type the following command and press **Enter**:

netsh advfirewall reset

 Wait for the process to complete. From there, restart your device to save these changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/VxFUhesNCKo?si=Ti0ui6DXYP12sjSs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Use Windows PowerShell

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DCARjc5g5VI?si=9OfovbKBrpoJeXTY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Struggling to reset the firewall settings using the Command Prompt? If so, then try [Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/).

 Here’s how to reset the firewall settings using PowerShell:

1. Type **Windows PowerShell** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as Administrator**.
3. Copy-paste the following command into PowerShell and press **Enter**:

(New-Object -ComObject HNetCfg.FwPolicy2).RestoreLocalFirewallDefaults()

 Wait for the process to complete, and then restart your device.

## 4\. Use the Windows Security App

 The Windows Security app is a tool that helps you scan and fix system bugs. Interestingly, you can also use this tool to reset the firewall settings.

 Here are the steps you need to follow:

1. Press **Win + I** to access the system settings.
2. Select the **Update & Security** option.
3. Click the **Windows Security** option on the left-hand side.
4. Select the **Firewall & network protection** tool in the middle pane.
5. Click the **Restore firewalls to default** option on the next screen.

![Clicking the Restore firewalls to default option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/clicking-the-restore-firewalls-to-default-option.jpg)

## 5\. Use the "Firewall with Advanced Security" Tool

 Still can’t reset the firewall settings? Try one of the options in the “Windows Firewall with Advanced Security” screen.

 As the name suggests, the “Windows Firewall with Advanced Security” tool allows you to configure various advanced settings. So, you can use it later if you want to tweak various firewall settings.

 For now, let’s check out how this tool can help you reset the firewall settings:

1. Press **Win + R** to open the Run command dialog box.
2. Type **wf.msc** and press **Enter** to open the “Windows Defender Firewall with Advanced Security” screen.
3. Navigate to the top-left corner and right-click on the **Windows Defender Firewall with Advanced Security on Local Computer** option.
4. Select the **Restore Default Policy** option.

![Selecting the Restore Default Policy option on the Firewall with Advanced Security screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-restore-default-policy-option-on-the-firewall-with-advanced-secutiry-screen.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fm0XhU5H8R4?si=cFPk6XK3X3CQSI7Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Can’t access the “Windows Defender Firewall with Advanced Security” screen using the steps we’ve covered? Try these methods:

1. Press **Win + I** to access the system settings.
2. Select the **Update & Security** option.
3. Click the **Windows Security** option on the left-hand side.
4. Select the **Firewall & network protection** tool in the middle pane.
5. Click **Advanced settings** in the middle pane.

 From there, right-click on the **Windows Defender Firewall with Advanced Security on Local Computer** option and select the **Restore Default Policy** option.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KKFdFHaVIJg?si=x2vLw7ty3FtHX-9T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Restoring the Firewall Settings to Their Default Settings

 It’s quite frustrating when the firewall settings prevent you from accessing the apps on your PC. But the good news is that you can simply resolve such issues by resetting these settings.

 To reset the firewall settings with ease, check out any of the tips we’ve covered. And if you want to reset the Settings app instead, there are solutions for that too!

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
<li><a href="https://article-tips.techidaily.com/new-2024-approved-connect-play-and-share-the-essentials-of-xbox-zoom/"><u>[New] 2024 Approved Connect, Play and Share The Essentials of Xbox Zoom</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-shadowed-browsing-in-fb-stories/"><u>[New] 2024 Approved Shadowed Browsing in Fb Stories</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-uncover-free-photo-and-video-resources-from-esteemed-4-online-sources/"><u>[Updated] 2024 Approved Uncover Free Photo and Video Resources From Esteemed 4 Online Sources</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-effective-ways-to-leverage-zoom-on-chrome-os-devices-for-2024/"><u>[Updated] Effective Ways to Leverage Zoom on Chrome OS Devices for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-syncing-separate-iphone-videos-for-one-story/"><u>[Updated] Syncing Separate IPhone Videos for One Story</u></a></li>
<li><a href="https://technical-tips.techidaily.com/essential-twitter-management-software-expert-recommendations/"><u>Essential Twitter Management Software – Expert Recommendations</u></a></li>
<li><a href="https://article-helps.techidaily.com/experience-gaming-savings-get-700-off-an-alienware-oled-display-and-our-top-pick-aurora-r16-computer-in-one-epic-offer/"><u>Experience Gaming Savings: Get $700 Off an Alienware OLED Display and Our Top-Pick Aurora R16 Computer in One Epic Offer</u></a></li>
<li><a href="https://windows11.techidaily.com/get-up-to-speed-on-windows-11s-user-friendly-taskbar-search-feature/"><u>Get up to Speed on Windows 11’S User-Friendly Taskbar Search Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-window-11-stealthy-hiding-of-linguistic-signal/"><u>Mastering Window 11: Stealthy Hiding of Linguistic Signal</u></a></li>
<li><a href="https://windows11.techidaily.com/rapid-dns-flush-techniques-for-win11-devices/"><u>Rapid DNS Flush Techniques for Win11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/reigniting-disappearing-windows-on-your-screen-top-6-fixes-for-win11/"><u>Reigniting Disappearing Windows on Your Screen: Top 6 Fixes for Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-counteract-error-x80300024-in-winxp/"><u>Steps to Counteract Error X80300024 in WinXP</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-tackle-corrupted-files-and-directories-win10-11-edition/"><u>Strategies to Tackle 'Corrupted' Files & Directories: Win10-11 Edition</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/ways-to-trade-pokemon-go-from-far-away-on-apple-iphone-15-pro-max-drfone-by-drfone-virtual-ios/"><u>Ways to trade pokemon go from far away On Apple iPhone 15 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-design-faux-pas-a-list-of-7/"><u>Windows 11'S Design Faux Pas: A List of 7</u></a></li>
</ul></div>

