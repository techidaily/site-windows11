---
title: Convenient Telnet Setup for Modern Windows Systems (Wins)
date: 2025-01-06T20:47:30.604Z
updated: 2025-01-10T19:54:04.485Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Convenient Telnet Setup for Modern Windows Systems (Wins)
excerpt: This Article Describes Convenient Telnet Setup for Modern Windows Systems (Wins)
keywords: WinTelNetSetup,EasyWindowsConnect,ModernWinTelnet,SecureWindowsSession,WINS Telnet Guide,WindowsTelnetConvenience,TelnetConfigWins
thumbnail: https://thmb.techidaily.com/738b7371069538e959521966db00e5f006e9b11d983f215b33d6c4263c894748.png
---

## Convenient Telnet Setup for Modern Windows Systems (Wins)

 Despite the vulnerability issues, Telnet is still used as a client-server protocol by Windows users. It is primarily used for initial network hardware configuration, remote access, port testing and forwarding, and other tasks that don't involve sensitive information transfer.

 You can enable Telnet on Windows 10 and 11 computers via Command Prompt or the Graphics User Interface (GUI) tool. Here we show you the many ways to enable Telnet on your Windows computer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jnITUsxMz5s?si=ohwRVH6eWhVnC6Xf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Enable Telnet on Windows Using Control Panel

 You can enable Telnet Client using the Classic Control Panel. Since it is an optional feature, you can enable it using the Windows Optional Feature dialog. You can use it [add or remove other users' optional features on Windows](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) .

To enable Telnet Client using Control Panel:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel.**
3. In Control Panel, Click on**Uninstall a Program** under**Programs and Features.**  
![turn windows features on or off control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/turn-windows-features-on-or-off-control-panel.jpg)
4. In the left pane, click on the**Turn Windows feature on or off.**  
![enable telnet client windows features dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-windows-features-dialog.jpg)
5. In the Windows Features dialog, scroll down and select**Telnet Client.**
6. Click**OK** and wait for the feature to install. Once installed, restart your PC to apply the changes and enable the feature.

If you need to disable Telnet:

1. Open the**Windows Features** dialog and unselect**Telnet Client.**
2. Click**OK** and wait for the feature to uninstall.
3. Click on**Restart** now to reboot your PC and apply the changes.

## 2\. Enable Telnet Client Using Windows PowerShell

![enable telnet client powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-powershell.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5FWCFI3f_cs?si=Kt2Onr_E4c616tbH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can use the Enable-WindowsOptionalFeature cmdlet to enable Telnet Client using Windows PowerShell. Useful if you are unable to turn on the feature using the Windows Features dialog and it is also faster than the GUI method.

To enable Telnet using Windows PowerShell:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Windows Terminal(Admin)** and click**Yes** to open the terminal app as administrator. If you are using Windows 10, type**PowerShell** in**Windows Search** and open**Windows PowerShell** administrator.
3. In the PowerShell window, type the following command and press**Enter** to enable Telnet:  
`Enable-WindowsOptionalFeature -Online -FeatureName TelnetClient`
4. This process may take several minutes, so wait for it to complete and return a status report. If successful, you’ll see the result as**Online:True.**
5. If you want to disable Telnet Client, use the following command instead:  
`Disable-WindowsOptionalFeature -Online -FeatureName TelnetClient`
6. Close PowerShell and restart your PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gSKkJrJ57EA?si=WDOmInPE9EgQa_tB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Install Telnet Client Using Command Prompt

![enable telnet command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GU08CQVsZz0?si=V-SvPfzRsQysMS0e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you prefer Command Prompt over PowerShell, you can use the DISM /Online command to enable the optional features on your Windows 11 computer.

Follow these steps to install Telnet using Command Prompt:

1. Press the**Win** key and type**cmd** .
2. Right-click on**Command Prompt** and select**Run as administrator.**
3. In the Command Prompt window, type the following command and press**Enter** :  
`dism /online /Enable-Feature /FeatureName:TelnetClient`
4. Command Prompt will start enabling the feature and display the operation completed successfully message.
5. If you need to disable Telnet, type the following command and press**Enter** :  
`dism /Online /Disable-Feature /FeatureName:TelnetClient`
6. Wait for the success message.
7. Type**exit** and press**Enter** to close Command Prompt.

## How to Check the Telnet Client Status on Your PC

![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)

 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UUPt2zKtJ5k?si=LLHdsFDLzVByJsKj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## All the Ways to Enable Telnet On Your Windows 11 Computer

 Telnet is a built-in remote access utility that you can use to troubleshoot firewall and network issues. While it is still part of Windows, system administrators now prefer the more secure SSH protocol to access computers over an unsecured network.

 The major disadvantage of Telnet is that it is not secure and prone to a man-in-the-middle attack. If not for particular situations, switch to a more secure network protocol such as SSH and Mosh with better password and public key authentication.

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
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-content-creators-den/"><u>[Updated] In 2024, Content Creator's Den</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-pinnacle-of-new-zooids-in-panzoids/"><u>2024 Approved The Pinnacle of New Zooids in Panzoids</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/ace-the-choice-of-mini-tablets-for-2pertise-verified-comparisons-zdnet-insights/"><u>Ace the Choice of Mini Tablets for 2Pertise-Verified Comparisons | ZDNET Insights</u></a></li>
<li><a href="https://extra-resources.techidaily.com/discover-the-art-of-sound-modification-in-free-fire-expert-tips-and-tricks-no-charge/"><u>Discover the Art of Sound Modification in Free Fire Expert Tips and Tricks (No Charge!)</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208810863-errtoomanyredirects-fixed-fast-solutions/"><u>ERR_TOO_MANY_REDIRECTS Fixed: Fast Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-strategies-for-windows-activation-failure-0x803f700f/"><u>Expert Strategies for Windows Activation Failure: 0X803F700f</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-overcoming-the-msvcr110dll-deficit/"><u>Guide to Overcoming the Msvcr110.dll Deficit</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-re-implementing-windows-11s-search-bar-as-an-icon/"><u>Guide: Re-Implementing Windows 11'S Search Bar as an Icon</u></a></li>
<li><a href="https://win-solutions.techidaily.com/how-to-resolve-city-building-simulator-skyline-issues-on-your-windows-computer/"><u>How to Resolve City Building Simulator Skyline Issues on Your Windows Computer</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-uncovering-if-vlogger-critiques-are-paid/"><u>In 2024, Uncovering If Vlogger Critiques Are Paid</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-github-desktop-on-windows-step-by-step-guide/"><u>Mastering GitHub Desktop on Windows: Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11s-context-menu-with-additional-software-icons/"><u>Mastering Windows 11'S Context Menu with Additional Software Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-valorant-download-fix-for-windows-users/"><u>Speedy Valorant Download Fix for Windows Users</u></a></li>
<li><a href="https://discover-fantastic.techidaily.com/techniques-efficaces-pour-recuperer-votre-informations-persistantes-apres-une-attaque-malveillante-du-cybermonde-guide-pratique-et-details-essentiels/"><u>Techniques Efficaces Pour Récupérer Votre Informations Persistantes Après Une Attaque Malveillante Du Cybermonde: Guide Pratique Et Détails Essentiels</u></a></li>
<li><a href="https://windows11.techidaily.com/the-smart-way-to-mitigate-pc-cpu-spikes-via-resource-monitor/"><u>The Smart Way to Mitigate PC CPU Spikes via Resource Monitor</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-fixing-the-non-responsive-right-click-on-your-windows-10-mouse/"><u>Troubleshooting Guide: Fixing the Non-Responsive Right Click on Your Windows 10 Mouse</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-power-top-10-must-have-msistore-picks/"><u>Unleash Power: Top 10 Must-Have MSIStore Picks</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unveiling-the-secrets-how-do-these-7-gpt-4-enhanced-apps-operate/"><u>Unveiling the Secrets: How Do These 7 GPT-4 Enhanced Apps Operate?</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-troubleshooting-alternatives-to-rename-folder-functions/"><u>Win 11 Troubleshooting: Alternatives to Rename Folder Functions</u></a></li>
</ul></div>

