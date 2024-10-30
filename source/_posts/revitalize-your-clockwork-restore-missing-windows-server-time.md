---
title: "Revitalize Your Clockwork: Restore Missing Windows Server Time"
date: 2024-10-28T16:43:57.486Z
updated: 2024-10-30T16:34:13.184Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Revitalize Your Clockwork: Restore Missing Windows Server Time"
excerpt: "This Article Describes Revitalize Your Clockwork: Restore Missing Windows Server Time"
keywords: Server Time Update,Windows Time Fix,Missing Window Time,Clockwork Reset,Time Sync Issue,Server Date Align,Restore Time Patch
thumbnail: https://thmb.techidaily.com/e2b01a1128735e3ec5310f2cbee0a0035159bd501806692c9cb150d9959d92bc.jpg
---

## Revitalize Your Clockwork: Restore Missing Windows Server Time

 Start your Windows computer and notice that the time is wrong. It might be a minor issue, or you accidentally changed the setting. But what if Windows Time Service is missing entirely?

 Fortunately, restoring the Windows Time Service is not complicated. This guide will discuss quickly restoring the missing Windows Time Service and setting the correct time on your computer.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Reboot Your PC

 Restart your computer before attempting any major troubleshooting. While it may sound simple, restarting the computer resolves minor errors and glitches that prevent the service from running. It flushes out temporary files and refreshes the operating system to ensure everything works correctly.

1. Press **Alt + F4** to bring up the Shutdown dialog
2. Select **Restart** from the drop-down menu and then hit **OK**.

 Once the computer restarts, check if Windows Time Service is available. If it's still missing, move on to the next step.

## 2\. Change the Time Server

 If restarting the computer does not work, you must change the time server. Changing the time server synchronizes your system clock with an online one, displaying your computer's correct date and time.

 Follow the steps to change the time server:

1. Press the **Windows key** to open the Start Menu.
2. Type **control panel** in the search box and click the result. This opens the Control Panel window.
3. Select **View by: Large icons** and click **Date and Time**.
4. Switch to the **Internet Time** tab and click **Change settings**.
5. Check the **Synchronize with an Internet time server** box and select a time server from the drop-down menu.  
![Change the Time Server](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/change-the-time-server.jpg)
6. Click the **Update now** button to synchronize your computer with the time server.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144281/7443" target="_top" id="2144281">
  <img src="//a.impactradius-go.com/display-ad/7443-2144281" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144281/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Once completed, click **OK** to save the changes and exit.

 After these steps, you should see the Windows Time Service running on your system. Check the time to ensure it is correct and make further adjustments.

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1557743/17382" target="_top" id="1557743">
  <img src="//a.impactradius-go.com/display-ad/17382-1557743" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1557743/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Add More Time Servers

 If the Windows Time Service is still missing, you can try adding more time servers to the list. Multiple time servers increase the chance of finding an active server and keeping your system in sync. If one server goes down, your computer can automatically switch to another.

 The solution requires editing the Windows registry. Even a small mistake can damage your system, so proceed with caution. To avoid data loss, [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing.

 To add time servers, do the following:

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the dialog box and click **OK**.
3. If the UAC window pops up on the screen, click **Yes** to grant permission.
4. In the Registry Editor window, navigate to the following directory.  
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\DateTime\Servers  
 Copy and paste the path into the Registry Editor address bar and press Enter. This will take you to the Location key.
5. From the left navigation panel, right-click the Servers folder and select **New** \> **String Value**.  
![Add More Time Servers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/add-more-time-servers.jpg)
6. Name the new value **Server N**, and replace **N** with a number starting from 1.  

 You can't have the same number twice. That means if there are already 3 values named _Server 1_, _Server 2_, and _Server 3_, you must call the new one as **Server 4**.
7. Double-click the newly created value and add a time server address in the Value data field.
8. Here are some time server addresses:  
`time.windows.com  

time.nist.gov  

time-a-wwv.nist.gov  

time-c-wwv.nist.gov  

ntp-wwv.nist.gov`

 After adding the time server, click **OK** and close the Registry Editor window. Now restart your computer to apply the changes and check if Windows Time Service is available.

## 4\. Re-register the Windows Time Service

 If the above steps fail, you can try re-registering the Windows Time Service. Re-registering a service refreshes its configuration and forces it to start again. Doing this may fix the missing Windows Time Service and recover clock synchronization.

 To re-register the Windows Time Service, follow these steps:

1. Press the **Win + S** keys to open the Windows Search.
2. Type **cmd** in the search box and simultaneously press **Ctrl + Shift + Enter**. This opens the Command Prompt with administrative privileges.
3. If the UAC window pops up, click **Yes** to grant permission.
4. Type the following command in the Command Prompt and press Enter:  
net stop w32time
5. This command will stop the Windows Time Service. Now type the following command to unregister the service and press **Enter**:  
w32tm /unregister
6. After that, run the following command to register the service:  
w32tm /register
7. Next, type the following command and hit **Enter**. This starts the Windows Time Service.  
net start w32time

 After performing these steps, close the Command Prompt window and restart your system. You should see that the Windows Time Service is running, and your clock syncs with the time server.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094479/7443" target="_top" id="2094479">
  <img src="//a.impactradius-go.com/display-ad/7443-2094479" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094479/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Repair Corrupted System Files

![SFC Command Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/sfc-command-preview.jpg)

 Corrupt system files can also cause Windows services to fail. So, if the Windows Time Service is still missing, try repairing corrupt system files. You can do this using the System File Checker tool. This tool scans your system for missing files and repairs the errors it finds.

 Wait for the scan to complete, and restart your computer. After that, check if the Windows Time Service is still missing. If it is, try running the Deployment Image Servicing and Management tool. This tool repairs corrupted system files and restores your Windows installation's health.

 If you're not sure how to run either of these tools, check out how to repair corrupt Windows files with its built-in tools for instructions.

## 6\. Scan for Malware

 Sometimes, malware is to blame for Windows services acting a little odd. As such, it's worth [running a full system scan](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) and removing all detected threats.

![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)

 If you feel your PC isn't as secure as it could be, you could try downloading one of the [best antivirus apps for Windows](http://www.makeuseof.com/windows-11-antivirus-apps/). These will both actively block malicious program from installing themselves on your PC, and remove any that are currently infesting your computer.

 For those who prefer a command-line approach, you can [use Windows PowerShell to scan Windows for malware](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/).

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1521325/16446" target="_top" id="1521325">
  <img src="//a.impactradius-go.com/display-ad/16446-1521325" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1521325/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Restore the Missing Windows Time Service

 Hopefully, one or more of these tips worked for you. Missing Windows services can be a huge pain, but hopefully, one of these methods has brought back the Windows Time Service back to working order.

 Fortunately, restoring the Windows Time Service is not complicated. This guide will discuss quickly restoring the missing Windows Time Service and setting the correct time on your computer.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-blue.techidaily.com/new-beyond-virality-understanding-what-makes-triller-different-from-tiktok/"><u>[New] Beyond Virality Understanding What Makes Triller Different From TikTok</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-craft-professional-edits-with-story-remix-in-windows-photos-app/"><u>[New] In 2024, Craft Professional Edits with Story Remix in Windows Photos App</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-figure-skatings-top-talent-review-of-22-moments/"><u>[Updated] Figure Skating's Top Talent Review of '22 Moments</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-perfecting-soundtracks-with-imovie-tools/"><u>2024 Approved Perfecting Soundtracks with iMovie Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-for-opening-wordpad-on-windows-os/"><u>Essential Tips for Opening WordPad on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-cannot-open-issue-with-files-in-office-365-mail/"><u>Fixing 'Cannot Open' Issue with Files in Office 365 Mail</u></a></li>
<li><a href="https://extra-resources.techidaily.com/freeze-frame-creation-through-stabilized-capture/"><u>Freeze-Frame Creation Through Stabilized Capture</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-automatically-shut-down-a-windows-10-and-11-pc-when-its-idle/"><u>How to Automatically Shut Down a Windows 10 and 11 PC When It's Idle</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-complete-fixes-to-solve-apple-iphone-14-plus-randomly-asking-for-apple-id-password-drfone-by-drfone-ios/"><u>In 2024, Complete Fixes To Solve Apple iPhone 14 Plus Randomly Asking for Apple ID Password | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-track-imei-number-of-infinix-smart-8-hd-through-google-earth-by-drfone-android/"><u>In 2024, How To Track IMEI Number Of Infinix Smart 8 HD Through Google Earth?</u></a></li>
<li><a href="https://windows11.techidaily.com/instant-access-enabling-windows-11-writable-search-box/"><u>Instant Access: Enabling Windows 11’ Writable Search Box</u></a></li>
<li><a href="https://windows11.techidaily.com/quickly-locate-new-windows-files-and-folders/"><u>Quickly Locate New Windows Files and Folders</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-windows-should-you-stop-phonelinkexe/"><u>Securing Windows: Should You Stop PhoneLink.exe?</u></a></li>
<li><a href="https://some-guidance.techidaily.com/transformacion-facil-de-archivo-mkv-a-mp4-para-usuarios-de-mac-paso-a-paso/"><u>Transformación Fácil De Archivo MKV a MP4 Para Usuarios De Mac: Paso a Paso</u></a></li>
<li><a href="https://win-able.techidaily.com/troubleshooting-your-nvidia-geforce-setup-fixing-sudden-shutdown-issues/"><u>Troubleshooting Your NVIDIA GeForce Setup - Fixing Sudden Shutdown Issues</u></a></li>
<li><a href="https://win-answers.techidaily.com/ultimate-guide-resolving-call-of-duty-warzone-dev-error-6634/"><u>Ultimate Guide: Resolving Call of Duty Warzone Dev Error 6634</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-file-corruption-mystery-in-windows-11/"><u>Unraveling the File Corruption Mystery in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-decorations-monitors-wallpaper-differentiation-guide/"><u>Windows 11 Decorations: Monitors Wallpaper Differentiation Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-without-drive-letters-analyzing-problems-and-proposed-solutions/"><u>Windows Without Drive Letters: Analyzing Problems and Proposed Solutions</u></a></li>
</ul></div>

