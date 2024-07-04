---
title: "Activating Telnet on Windows: 3 Key Methods"
date: 2024-07-03T11:10:25.537Z
updated: 2024-07-04T11:10:25.537Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Activating Telnet on Windows: 3 Key Methods"
excerpt: "This Article Describes Activating Telnet on Windows: 3 Key Methods"
keywords: WinTelNetSetup,EnableWinTelnet,TelnetConfigWin,WindowsTelnetEnable,ActivateWindowsTelnet,ProcedureWinTelnet,MethodsTelnetWin
thumbnail: https://thmb.techidaily.com/04735b88e1441114a8925bb5e15d2369f293d2c3a93400105413a698d6a65c62.jpg
---

## Activating Telnet on Windows: 3 Key Methods

 Despite the vulnerability issues, Telnet is still used as a client-server protocol by Windows users. It is primarily used for initial network hardware configuration, remote access, port testing and forwarding, and other tasks that don't involve sensitive information transfer.

 You can enable Telnet on Windows 10 and 11 computers via Command Prompt or the Graphics User Interface (GUI) tool. Here we show you the many ways to enable Telnet on your Windows computer.

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

## 3\. Install Telnet Client Using Command Prompt

![enable telnet command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-command-prompt.jpg)

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
<li><a href="https://windows11.techidaily.com/step-by-step-guide-to-manipulating-fax-cover-pages-on-win11/"><u>Step-by-Step Guide to Manipulating Fax Cover Pages on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-elevating-notetaking-on-windows/"><u>Master the Art of Elevating Notetaking on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/10-command-prompt-wonders-you-didnt-know/"><u>10 Command Prompt Wonders You Didn’t Know!</u></a></li>
<li><a href="https://windows11.techidaily.com/rapidly-access-apps-on-windows-11/"><u>Rapidly Access Apps on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-obstacle-fixing-windows-system-function-interruption/"><u>Overcoming the Obstacle: Fixing Windows System Function Interruption</u></a></li>
<li><a href="https://windows11.techidaily.com/reset-windows-strategies-8-techniques-unveiled/"><u>Reset Windows Strategies: 8 Techniques Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-manual-reverting-windows-to-a-previous-state/"><u>Step-by-Step Manual: Reverting Windows to a Previous State</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-the-premier-screenshot-applications-for-linux-users/"><u>[New] 2024 Approved  The Premier Screenshot Applications for Linux Users</u></a></li>
<li><a href="https://games-able.techidaily.com/retro-controller-enhancing-classic-games/"><u>Retro Controller: Enhancing Classic Games</u></a></li>
<li><a href="https://android-location.techidaily.com/easy-ways-to-manage-your-vivo-y02t-location-settings-drfone-by-drfone-virtual/"><u>Easy Ways to Manage Your Vivo Y02T Location Settings | Dr.fone</u></a></li>
<li><a href="https://fox-info.techidaily.com/tick-tock-tally-calculating-pewdiepies-cash-for-2024/"><u>Tick-Tock Tally  Calculating PewDiePie’s Cash for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-beyond-basics-why-hdr-dominates-in-video-editing-workflows/"><u>2024 Approved  Beyond Basics  Why HDR Dominates in Video Editing Workflows</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-premier-tech-to-record-your-on-air-video-on-youtube/"><u>[Updated] Premier Tech to Record Your On-Air Video on YouTube</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-your-step-by-step-kinemaster-meme-creation/"><u>In 2024, Your Step-by-Step KineMaster Meme Creation</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-mediacutmaster-review-in-depth-evaluation/"><u>[New] MediaCutMaster Review – In-Depth Evaluation</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-best-apple-iphone-15-and-ipad-screen-mirroring-app-drfone-by-drfone-ios/"><u>In 2024, Best Apple iPhone 15 & iPad Screen Mirroring App | Dr.fone</u></a></li>
</ul></div>
