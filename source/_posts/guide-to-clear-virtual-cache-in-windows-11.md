---
title: Guide to Clear Virtual Cache in Windows 11
date: 2024-09-05T02:09:22.820Z
updated: 2024-09-06T02:09:22.820Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Clear Virtual Cache in Windows 11
excerpt: This Article Describes Guide to Clear Virtual Cache in Windows 11
keywords: Virtual Cache Cleanup Guide,Windows 11 Cache Management,Clearing Cache in Win11,Optimize Virtual Cache,Cache Purge for Windows Users,Virtual Storage Maintenance,Streamlining Cache in Win11
thumbnail: https://thmb.techidaily.com/2b667f6d425e137d74634d5b5e43d01ba3b3015e34fc38e54ba016f1aa0f02aa.jpg
---

## Guide to Clear Virtual Cache in Windows 11

 Are you having trouble with virtual memory on Windows 11? Resetting virtual memory on Windows can improve system performance or free up extra hard drive space. So, we'll show you exactly how to reset the virtual memory on your Windows 11 computer.

## What Is Virtual Memory and How Does It Work?

 Virtual memory, also known as a paging file, is a technology used in computers to allow programs to use more memory than what's physically available on it. When you run out of RAM, your operating system relies on virtual memory to continue running programs.

 The computer creates a special file called a page or swap file on the hard drive. It stores some data temporarily removed from RAM and written to the hard drive. This way, the computer can access more memory than what's installed.

 Although virtual memory allows programs to operate smoothly, it can also hurt overall performance. For example, if your computer runs out of RAM, it will use more of the hard drive to store data. This also significantly slows overall performance as HDDs and SSDs are much slower than RAM.

 Let's now see how to reset Virtual Memory on Windows.

## 1\. Use the System Properties window

 If you want to reset virtual memory settings on your Windows device, you can use the System Properties window. To do this, press **Win + R** on your keyboard to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).

 In the text box, type **sysdm.cpl**, and hit Enter. A system properties window will open up. Then, go to the **Advanced** tab and click the **Settings** button in the Performance section.

![How to Reset Virtual Memory on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/how-to-reset-virtual-memory-on-windows-11.jpg)

 This will open up the Performance Options window, where you can manage virtual memory settings. For this, switch to the **Advanced** tab and click on **Change** in the Virtual Memory section.

![Reset Page Size](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-page-size.jpg)

 On the next screen, uncheck the **Automatically manage paging file size for all drives** checkbox and select the drive you want to configure virtual memory. Normally, this will be the drive on which Windows is installed.

 Set the custom size for virtual memory. Then, check the **No paging file** radio button and click **Set**. If you see a warning message, click **Yes** to confirm.

 After following the above steps, click **OK** to save your changes. Now close the System Properties and Settings windows and restart your computer. The new virtual memory settings should now be in effect.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016134/19272" target="_top" id="2016134">
  <img src="//a.impactradius-go.com/display-ad/19272-2016134" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016134/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Use Group Policy Editor

 You can also use the Local Group Policy Editor to reset virtual memory settings on your Windows device. But remember that this method is only available on Pro and Enterprise editions.

 If you're using a Home edition, you should first [enable the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To get started, open the Run dialog box and type **gpedit.msc** into the text box. Then click **OK** or press Enter to open the Local Group Policy Editor window.

![Clear virtual memory pagefile Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clear-virtual-memory-pagefile-using-group-policy.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2052063/7443" target="_top" id="2052063">
  <img src="//a.impactradius-go.com/display-ad/7443-2052063" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052063/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Then navigate to the following location:

Local Computer Policy > Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Option

 Scroll down and double-click **Shutdown: Clear virtual memory pagefile** policy. In the Properties window, select Enabled and then click **Apply**. Next, click **OK** to save it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1972670/19272" target="_top" id="1972670">
  <img src="//a.impactradius-go.com/display-ad/19272-1972670" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972670/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Use Registry Editor

 If you don't have access to the Local Group Policy Editor, you can also use the Registry Editor to reset virtual memory settings on Windows. Before proceeding, you should [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) in case something gets wrong.

![Reset Virtual Memory Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-virtual-memory-using-registry.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484944/16446" target="_top" id="1484944">
  <img src="//a.impactradius-go.com/display-ad/16446-1484944" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484944/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To get started, search for **Registry Editor** in the Start menu and click on it. Once you open the Registry Editor, navigate to the following path:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Memory Management

 Next, double-click on the **ClearPageFileAtShutdown** key and set its value to **1**. Click on the **OK** button to save your changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037359/7443" target="_top" id="2037359">
  <img src="//a.impactradius-go.com/display-ad/7443-2037359" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037359/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Reset Virtual Memory To Get Better Performance

 Resetting virtual memory settings improves Windows computer performance. This guide introduces three methods to learn how to reset virtual memory on Windows. Give it a try and see which methods work best for you. If you face any issues while doing this, you can always use system restore to revert to the previous settings.


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
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-master-plan-top-6-modernist-minecraft-villas/"><u>[Updated] 2024 Approved  Master Plan  Top 6 Modernist Minecraft Villas</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-inside-the-revolutionary-world-of-jaunt-vr/"><u>[Updated] Inside the Revolutionary World of Jaunt VR</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/2024-approved-best-10-chinese-video-to-english-translator/"><u>2024 Approved Best 10 Chinese Video to English Translator</u></a></li>
<li><a href="https://howto.techidaily.com/7-fixes-for-unfortunately-phone-has-stopped-on-motorola-razr-40-ultra-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Fixes for Unfortunately, Phone Has Stopped on Motorola Razr 40 Ultra | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-windows-canary-a-guide-for-first-timers/"><u>Exploring Windows Canary: A Guide for First-Timers</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-unlisted-device-detected-error-in-win1011/"><u>Fixing Unlisted Device Detected Error in Win10/11</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-exit-android-factory-mode-on-vivo-y100i-power-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Exit Android Factory Mode On Vivo Y100i Power 5G? | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-dailymotion-vs-youtube-monetization-which-is-more-profitable/"><u>In 2024, Dailymotion vs YouTube Monetization  Which Is More Profitable?</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-double-location-dongle-all-to-know-about-apple-iphone-xipad-gps-spoofing-drfone-by-drfone-virtual-ios/"><u>In 2024, Double Location Dongle All to Know About Apple iPhone X/iPad GPS Spoofing | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/insights-into-ftdibussys-the-implications-for-windows-memory-safety/"><u>Insights Into ftdibus.sys: The Implications for Windows Memory Safety</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/navigating-spanish-language-with-correct-accents-and-typography/"><u>Navigating Spanish Language with Correct Accents and Typography</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolve-print-hang-up-swiftly/"><u>Resolve Print Hang-Up Swiftly</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolve-non-displaying-full-screen-in-windows-11-pcs/"><u>Resolve: Non-Displaying Full Screen in Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-inaudible-audio-on-wireless-devices/"><u>Resolving Inaudible Audio on Wireless Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-memory-safety-in-windows-11s-system-settings/"><u>Restoring Memory Safety in Windows 11'S System Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/revamping-your-networks-first-line-of-defense/"><u>Revamping Your Network's First Line of Defense</u></a></li>
<li><a href="https://windows11.techidaily.com/solve-your-inked-woes-a-guide-to-fixing-windows-pen-devices/"><u>Solve Your Inked Woes: A Guide to Fixing Windows Pen Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-silent-setbacks-ccleaner-issues-in-windows-11/"><u>Solving Silent Setbacks: CCleaner Issues in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-w10w11-interruptexception-bsod-a-comprehensible-guide/"><u>Solving W10/W11 INTERRUPT_EXCEPTION BSOD: A Comprehensible Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-boot-streamlining-your-win11-routines/"><u>Speedy Boot: Streamlining Your Win11 Routines</u></a></li>
<li><a href="https://windows11.techidaily.com/strategic-steps-launching-your-admin-privileged-powershell-console/"><u>Strategic Steps: Launching Your Admin Privileged PowerShell Console</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-fix-system-call-failures-in-windows/"><u>Strategies to Fix System Call Failures in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-pc-functionality-addressing-11-windows-problems/"><u>Streamlining PC Functionality - Addressing 11 Windows Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/the-audio-advantage-top-4-programs-for-surpassing-windows-100-limit/"><u>The Audio Advantage: Top 4 Programs for Surpassing Windows' 100%% Limit</u></a></li>
<li><a href="https://windows11.techidaily.com/the-easy-switch-for-classic-gaming-in-the-windows-photo-hub/"><u>The Easy Switch for Classic Gaming in the Windows Photo Hub</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/the-future-of-high-speed-connections-pci-sigs-latest-unveil-superior-copperlynk-cabling-for-the-upcoming-pcie-5and6-standards-anticipating-release-of-gen-7.106/"><u>The Future of High-Speed Connections: PCI-SIG's Latest Unveil - Superior CopperLynk Cabling for the Upcoming PCIe 5&6 Standards; Anticipating Release of Gen 7</u></a></li>
<li><a href="https://windows11.techidaily.com/the-os-metamorphosis-insights-into-w10-and-w11-developments/"><u>The OS Metamorphosis: Insights Into W10 and W11 Developments</u></a></li>
<li><a href="https://windows11.techidaily.com/the-unseen-consequences-of-cost-saving-windows-activation/"><u>The Unseen Consequences of Cost-Saving Windows Activation</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-compressed-storage-on-windows-11/"><u>Unlocking Compressed Storage on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-ios-calendar-in-your-windows-environment/"><u>Unlocking iOS Calendar in Your Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-successful-remote-steam-connectivity/"><u>Unlocking Successful Remote Steam Connectivity</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-system-restore-issue-0x80042306-in-win10/"><u>Unraveling System Restore Issue 0X80042306 in Win10</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-ram-cache-basics-and-cleansing-methods/"><u>Windows RAM Cache Basics and Cleansing Methods</u></a></li>
</ul></div>
