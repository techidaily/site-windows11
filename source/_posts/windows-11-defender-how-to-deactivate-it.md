---
title: "Windows 11 Defender: How to Deactivate It"
date: 2024-08-15T15:30:35.577Z
updated: 2024-08-16T15:30:35.577Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11 Defender: How to Deactivate It"
excerpt: "This Article Describes Windows 11 Defender: How to Deactivate It"
keywords: Windows 11 Security Halt,Deactivate Win 11 Guard,Disable Windows 11 Shield,Turn Off Defender Windows,Stop Windows 11 Protection,Suspend Windows 11 Safeguard,Inactive Windows 11 Antivirus
thumbnail: https://thmb.techidaily.com/72d87bf38b3f988e318217c000305d7e3da283a047b864a8cf5c572968e745b4.jpg
---

## Windows 11 Defender: How to Deactivate It

 While firewalls can protect you from malicious online threats, there may be times when it is necessary to disable them for certain tasks or applications. While it's usually not a good idea to disable the firewall for long periods of time, doing so for a few seconds while you troubleshoot a problem is usually safe.

 As such, let's explore how to turn off or disable the Microsoft Defender firewall safely and securely in Windows 11\.

## How Important Is the Microsoft Defender Firewall?

 A firewall acts as a shield against unwanted intrusions and prevents external connections from accessing your system without permission. When disabled, your computer becomes vulnerable, and you should take extra precautions while online.

 To ensure maximum security while disabling your firewall, always make sure that other protective measures such as antivirus programs are running in the background. Once these have been taken care of, you can disable the firewall on your Windows 11 PC. Here's how to do this:

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
## 1\. How to Disable the Firewall Using Windows Security

 The Windows Security program allows you to disable the firewall in Windows 11\. It is the most straightforward way to disable Microsoft Defender Firewall and you don’t need to have any additional tools or software installed. Here's how:

1. Click on **Start** and search for “Windows Security”.
2. Then select the result from the top of the list.
3. Once you are in Windows Security, click on the **Firewall & network protection** option.
4. Select the **Public network** or **Private network** profile and turn off the firewall for that selection.  
![Disable the Firewall Using Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-firewall-using-windows-security.jpeg)
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->

 The UAC prompt will require you to accept it, so make sure your computer is set up as an admin account. If UAC prompts on the screen, click **Yes** to continue.

 Now that you have completed the above steps, disable the firewall for each network profile using the same procedure.

## 2\. How to Disable the Firewall Through Control Panel

 If you are running an older version of Windows or prefer to use a more traditional method, you can disable your firewall through the Control Panel. This is a bit more technical than using Windows Security but still easy enough to do. Here’s how:

1. Open the Control Panel. If you need help with this, check out [how to open the Control Panel in Windows 11](https://www.makeuseof.com/windows-11-open-control-panel/).  
![Disable the Firewall Through Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-firewall-through-control-panel.jpeg)
2. In the Control Panel, select **System and Security** and then click **Windows Defender Firewall**.
3. From the left pane, select **Turn Windows Defender Firewall on or off**.  
![Turn off the Firewall Through Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-off-the-firewall-through-control-panel.jpeg)
<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Then select **Turn off Windows Defender Firewall (not recommended)** for each network setting.
5. Click **OK** to save your changes.

## 3\. How to Disable the Firewall Using Command Prompt

 If you are comfortable using the command line, then you can also disable your firewall through the Command Prompt. Here’s how:

 Press **Win + S** on your keyboard to open the Windows search tool. Now type "cmd" in the search field and press **Ctrl + Shift + Enter** on your keyboard. This will open Command Prompt with admin rights.

 Once you are in the Command Prompt, type in the following command and hit **Enter:**

netsh advfirewall set currentprofile state off

 Running the above command will turn off the firewall for the current network profile.

 If you wish to disable the firewall for the domain network profile, copy and paste the following command, and hit **Enter**:

netsh advfirewall set domainprofile state off

 Similarly, you can disable the firewall for the private network profile. To do this, copy and paste the following command and hit **Enter**:

netsh advfirewall set privateprofile state off

 For the public network profile, type the following command in the Command Prompt window and press **Enter**:

netsh advfirewall set publicprofile state off

 Alternatively, you can disable the Defender Firewall for all network profiles, such as domain, private, and public, with just one command. To do this, copy and paste the below command and hit **Enter**:

netsh advfirewall set allprofiles state off

 In this way, you can disable the firewall according to your selected network profiles.

## 4\. How to Turn Off the Firewall via PowerShell

 Windows PowerShell is an important tool that can be used to manage many aspects of the Windows operating system. You can also use it to disable the Microsoft Defender Firewall.

 To do this, open a PowerShell window as an administrator and run the following commands:

![Turn Off the Firewall Via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-off-the-firewall-via-powershell.jpg)
<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Set-NetFirewallProfile -Profile Domain,Public,Private -Enabled False

 After running the above command, the firewall will be disabled for all network profiles simultaneously.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->
## 5\. How to Turn Off the Firewall Using Group Policy Editor

 The Group Policy Editor is a powerful system resource that can be used to manage different settings on all Windows computers. With this tool, you can disable your firewall, but it only works with Windows Professional and Enterprise. If you are using Windows Home Edition, you need to [activate the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) in order to access it.

 To disable firewall settings using the Local group policy editor, follow these steps:

1. Right-click on Start and select **Run** from the menu list.
2. Type **gpedit.msc** in the dialog box and click **OK** or press Enter on your keyboard.
3. Inside the Group Policy Editor window, navigate to the following:  
Computer Configuration > Administrative Templates > Network > Network Connections > Windows Defender Firewall > Standard Profile
4. On the right side of the window, double-click the policy called **Windows Defender Firewall: Protect all network connections**.  
![Turn Off the Firewall Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-off-the-firewall-using-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Next, choose **Disabled** from the dialog box that appears.
6. When you're done making your changes, click **Apply** \> **OK**.
7. For the changes to take effect, restart your computer after completing the above steps.

## 6\. How to Turn Off the Firewall Using Registry Editor

 Windows also has a method for disabling the firewall that involves editing the registry. It is an advanced feature that should only be used by experienced computer users, as incorrect usage can cause serious damage to your computer.

 When using the Registry Editor, it is important not to modify any other settings than those related directly to the firewall. Making unwanted changes could potentially lead to instability within your system, including a decrease in performance or even the complete failure of your operating system. If you're ready to use this method, make sure you [back up your Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [create a restore point on Windows 11](https://www.makeuseof.com/windows-11-create-restore-point/) first.

1. Open the Registry Editor (see [how to open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) for instructions).
2. Once you're in, navigate to the following path:  
Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\WindowsFirewall\StandardProfile
3. Right-click StandardProfile and select **New > DWORD (32-bit) Value**.
4. Specify **EnableFirewall** as the key name.
5. Double-click it and enter **0** in the Value data field.  
![Turn Off the Firewall Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-off-the-firewall-using-registry-editor.jpg)
6. Once you have made the changes, click **OK**.

 When you have completed all the steps above, close the Registry Editor and restart your computer.

## Disable the Firewall With Ease on Windows

 You may want to disable the firewall for testing, developing applications, or playing online games. However, disabling the firewall can have risks, and you should always exercise caution. In case you need to do it, this guide explains multiple ways to do it, such as via Windows Security, Control Panel, Command Prompt, and more.


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
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-from-novice-to-pro-mastering-lenovos-capture-capabilities/"><u>[New] 2024 Approved  From Novice to Pro  Mastering Lenovo's Capture Capabilities</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-cutting-edge-tips-for-low-cost-youtube-sessions/"><u>[New] Cutting-Edge Tips for Low-Cost YouTube Sessions</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-key-approaches-converting-visual-content-on-pinterest-to-audio/"><u>[New] In 2024, Key Approaches  Converting Visual Content on Pinterest To Audio</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-stepping-into-the-unseen-mastering-windows-11-through-less-known-tips/"><u>[New] Stepping Into the Unseen  Mastering Windows 11 Through Less-Known Tips</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-seeking-freebies-learn-instagrams-secret-for-additional-filters/"><u>[Updated] 2024 Approved  Seeking Freebies? Learn Instagram’s Secret for Additional Filters</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-deciphering-the-art-of-reversed-visual-searches-online-fb/"><u>[Updated] Deciphering the Art of Reversed Visual Searches Online (FB)</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-voicing-it-up-how-to-save-on-iphone/"><u>[Updated] In 2024, Voicing It Up  How to Save on iPhone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-explore-the-finest-18-wireless-camcorders-today/"><u>2024 Approved  Explore the Finest 18 Wireless Camcorders Today</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-making-mp3s-from-your-facebook-videos-with-ease/"><u>2024 Approved  Making MP3s From Your Facebook Videos with Ease</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/decoding-apple-books-app-performance-expert-opinion-and-review/"><u>Decoding Apple Books App Performance: Expert Opinion & Review</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/easy-peel-mac-screenshots-for-no-cost/"><u>Easy-Peel Mac Screenshots for No Cost</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-fixes-for-frozen-terminal-apps-on-windows/"><u>Essential Fixes for Frozen Terminal Apps on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-to-correct-0x8009030e-in-virtualization/"><u>Essential Steps to Correct 0X8009030E in Virtualization</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-for-navigating-wpm-on-windows-11/"><u>Essential Tips for Navigating WPM on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-correcting-invalid-profiles-on-windows-oses/"><u>Guide to Correcting Invalid Profiles on Windows OSes</u></a></li>
<li><a href="https://fox-access.techidaily.com/harnessing-iphones-potential-for-detailed-photography-for-2024/"><u>Harnessing iPhone's Potential for Detailed Photography for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-bypass-printer-settings-on-windows-11/"><u>How to Bypass Printer Settings on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-windows-update-asking-to-update-and-restart/"><u>How to Stop Windows Update Asking to Update and Restart</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/how-to-transfer-from-apple-iphone-se-2022-to-samsung-simplified-guide-drfone-by-drfone-transfer-from-ios/"><u>How To Transfer From Apple iPhone SE (2022) to Samsung Simplified Guide | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-resolution-for-windows-network-proxy-issue/"><u>Immediate Resolution for Windows Network Proxy Issue</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-learn-how-to-lock-stolen-your-iphone-8-properly-drfone-by-drfone-ios/"><u>In 2024, Learn How To Lock Stolen Your iPhone 8 Properly | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/independent-windows-version-improvement-tactics/"><u>Independent Windows: Version Improvement Tactics</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-the-absence-of-rockalldlldll-windows/"><u>Mending the Absence of Rockalldll.dll (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-pc-a-guide-to-spotting-huge-files-and-folders/"><u>Optimize Your PC: A Guide to Spotting Huge Files & Folders</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-display-glitches-in-windows-os/"><u>Overcoming Display Glitches in Windows OS</u></a></li>
<li><a href="https://extra-information.techidaily.com/pioneering-virtual-experiences-a-report/"><u>Pioneering Virtual Experiences  A Report</u></a></li>
<li><a href="https://windows11.techidaily.com/preserve-your-files-as-you-boost-windows-drive/"><u>Preserve Your Files as You Boost Windows Drive</u></a></li>
<li><a href="https://extra-skills.techidaily.com/quick-kinemaster-techniques-for-memelore-for-2024/"><u>Quick KineMaster Techniques for Memelore for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tips-for-repairing-video-playback-errors/"><u>Quick Tips for Repairing Video Playback Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-resolving-iphone-photos-import-error-in-windows-pcs/"><u>Quick-Fix: Resolving iPhone Photos Import Error in Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-device-errors-in-windows-11/"><u>Remedying Device Errors in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-steam-data-write-functionality-in-windows/"><u>Restoring Steam Data Write Functionality in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionize-your-ad-targeting-strategies-with-innovative-insights-from-cookiebot/"><u>Revolutionize Your Ad Targeting Strategies with Innovative Insights From Cookiebot</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/rhythm-and-reel-adding-music-to-ig-feeds/"><u>Rhythm and Reel  Adding Music to IG Feeds</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-installation-of-intel-wi-fi-adapters-for-gaming/"><u>Seamless Installation of Intel Wi-Fi Adapters for Gaming</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-correcting-0xc0000005-failures-on-pcs/"><u>Strategies for Correcting 0Xc0000005 Failures on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-ways-to-elude-windows-11-screensaver/"><u>Swift Ways to Elude Windows 11 Screensaver</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-error-code-0x80070091-empty-directories-unveiled/"><u>Tackling Windows Error Code 0X80070091 - Empty Directories Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/transition-without-subsys-optimizing-for-upcoming-android-solutions/"><u>Transition Without Subsys: Optimizing for Upcoming Android Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-invisible-networks-microsoft-fix-it-guide/"><u>Unblocking Invisible Networks: Microsoft Fix-It Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unobstructed-wireless-resurrecting-disconnected-networks/"><u>Unobstructed Wireless: Resurrecting Disconnected Networks</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/unpacking-vyncs-link-tracker-insights-on-performance-reliability-and-layered-payment-schemes/"><u>Unpacking VyNCs Link Tracker: Insights on Performance Reliability and Layered Payment Schemes</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-riddle-of-windows-winerror-woes/"><u>Unraveling the Riddle of Window's WinError Woes</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/unveiling-social-network-regulations-can-you-share-videos-in-2024/"><u>Unveiling Social Network Regulations  Can You Share Videos, In 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/wins-cmd-customize-to-reflect-your-style/"><u>Win's CMD: Customize to Reflect Your Style</u></a></li>
<li><a href="https://windows11.techidaily.com/your-guide-to-selecting-a-new-window-home-or-premium-edition/"><u>Your Guide to Selecting a New Window : Home or Premium Edition</u></a></li>
</ul></div>