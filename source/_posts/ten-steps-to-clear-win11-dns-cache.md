---
title: Ten Steps to Clear Win11 DNS Cache
date: 2024-10-03T05:49:52.634Z
updated: 2024-10-06T16:02:15.654Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Ten Steps to Clear Win11 DNS Cache
excerpt: This Article Describes Ten Steps to Clear Win11 DNS Cache
keywords: Wi-Fi DNS Clearance,Windows 11 Cache Fix,Accelerate Win11 Speed,Domain Name Resolution,Network Performance Boost,Router Reconnection,Flush DNS Efficiency
thumbnail: https://thmb.techidaily.com/3826690fad2bdad4d7aa62bd8a31b6771b07791104399fd4c0b5ca08b831fc4c.jpg
---

## Ten Steps to Clear Win11 DNS Cache

 Facing internet connectivity issues on your Windows PC? DNS cache corruption is among the most common reasons for connectivity problems. The quickest fix for this problem is to flush the DNS cache and force the computer to recreate it.

 But do you know that there are multiple ways to flush the DNS cache on Windows 11? We will elaborate on the benefits of clearing the DNS cache along with the multiple methods which you can use on your Windows 11 PC. Without further ado, let’s dive into the post.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is the DNS Cache and Why Should You Flush It?

 When you access a website, you usually do so by typing its URL in a browser. However, computers don't "understand" URLs, and each URL has a corresponding IP address that a computer can actually use. When you search for a website, your computer accesses a DNS server that contains records of URLs and their corresponding IP addresses.

 This process is known as DNS lookup, but it is time-consuming to search for an IP address every time, especially for websites that you visit repeatedly. So, the computer maintains a local copy of the DNS known as the DNS resolver cache. When you search for a URL, it checks the resolver cache first and then uses that information to find the website.

 The DNS resolver cache can become outdated or corrupt over time which can pose connectivity issues. There is also a looming risk of[DNS cache poisoning](https://www.makeuseof.com/tag/what-is-dns-cache-poisoning/) , which is why you should make it a habit to clean the DNS cache periodically.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938693/19272" target="_top" id="1938693">
  <img src="//a.impactradius-go.com/display-ad/19272-1938693" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938693/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Flush the DNS Cache on Windows 11

 There are multiple methods to flush the DNS cache on Windows 11\. You can use the Run command box, Command Prompt, or even PowerShell. In addition, you can use a batch file to clear the DNS cache in a few clicks, any time you want. Here are the four ways to clear DNS on Windows 11:

### 1\. Using the Run Command Box

To flush the DNS cache using the Run command box, do as follows:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type “**ipconfig /flushdns** ” command.  
![Flush DNS Using the Run Command Box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-the-run-command-box.jpg)
3. Press**Ctrl + Shift + Enter** keys at once. The Command Prompt will launch, execute the flush command, and close automatically.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148643/16836" target="_top" id="2148643">
  <img src="//a.impactradius-go.com/display-ad/16836-2148643" border="0" alt="https://techidaily.com" width="300" height="75"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148643/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Using CMD

 To clear the DNS resolver cache using CMD, repeat the following steps:

1. Press**Win + R** to open the run dialog box. Type**cmd** and press**Ctrl + Shift + Enter** keys at once.
2. CMD will open with admin privileges.
3. Type “**ipconfig /flushdns** ” command and press the**Enter** key.  
![Flush DNS Using CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-cmd.jpg)
4. You will see a “**Successfully flushed the DNS Resolver Cache.** ” message after the command execution.

### 3\. Using PowerShell

 PowerShell has a different command to flush the DNS cache on Windows 11\. Here’s how to do it:

1. Press**Win + S** and type**PowerShell** . Click on the**Run as administrator** option in the Start menu.
2. Now, type “**Clear-DnsClientCache** ” in the PowerShell window and press the**Enter** key.  
![Flush DNS Using Powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-powershell.jpg)
3. You won’t see a message after the command executes successfully. But you can open PowerShell again and view the DNS cache to confirm.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068412/7443" target="_top" id="2068412">
  <img src="//a.impactradius-go.com/display-ad/7443-2068412" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068412/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 4\. Using a Batch File

 Opening an app is a slightly time-consuming process. You can save time by creating a batch file once and then running it whenever you need to flush DNS. No need to open the CMD or PowerShell app.

Repeat the following steps to create a DNS-clearing batch file:

1. Press**Win + S** to open Windows Search. Type**Notepad** and click on the first search result.
2. Type the following command in Notepad:**cmd.exe /k ipconfig /flushdns**  
![Flush DNS Using A Batch File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-a-batch-file.jpg)
3. Press**Ctrl + S** to save the file. Enter the name “**flushDNS.bat** ” and keep the**Save as type** as**All Files** .
4. Click on the**Save** button.
5. Now go to the batch file location and double-click on it.
6. The Command Prompt will launch and execute the "**/** flushdns" command.
7. Type**exit** and press the**Enter** key to close the command prompt window.

## How to Flush Your Browser's DNS Records

 Do you know that browsers maintain a DNS cache as well? If you face connectivity issues, you should clear the browser's DNS cache and force the browser to rebuild the cache.

 Repeat the following steps to clear Chrome browser’s DNS cache:

1. Launch the Chrome browser and press**Ctrl + T** to open a new tab.
2. Now, type “**chrome://net-internals/#dns** ” in the search bar and press the**Enter** key.
3. Navigate to the**Host resolver cache** section. Click on the**Clear host cache** button to clear cached DNS records in the Chrome browser.

 The process to clear a browser's DNS cache may differ with other browsers like Safari, Opera, and Mozilla. You will have to locate the DNS settings and then wipe out the DNS cache.

<!-- affiliate ads begin -->
<span id="1993650">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Keep Your DNS Cache Clean on Windows

 Flushing the system's DNS cache periodically can reduce the risk of DNS spoofing and website connectivity issues. The simplest method is to use the ipconfig utility with appropriate parameters to flush the DNS cache. Alternatively, you can use the PowerShell method or create a batch file for the same.

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
<li><a href="https://program-issues.techidaily.com/1723007560545-half-life-alyx-pc-version-latency-and-stutter-no-more/"><u>'Half-Life: Alyx PC Version - Latency and Stutter No More</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-enabling-autoplay-youtube-videos-in-social-media-network/"><u>[New] 2024 Approved Enabling Autoplay Youtube Videos in Social Media Network</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-cutting-edge-av-producers-compendium-online/"><u>[New] Cutting-Edge AV Producers' Compendium Online</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-premier-camera-drones-10-filmmakers-dream-fleet-for-2024/"><u>[New] Premier Camera Drones #10 Filmmakers' Dream Fleet for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-twitch-user-introduction-measurements-format-duration/"><u>[New] Twitch User Introduction Measurements, Format, Duration</u></a></li>
<li><a href="https://program-issues.techidaily.com/solved-forza-horizon-4-wont-launch-2024-tips/"><u>[SOLVED] Forza Horizon 4 Won't Launch | 2024 Tips</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-best-practices-for-designing-an-engaging-youtube-teaser-for-2024/"><u>[Updated] Best Practices for Designing an Engaging YouTube Teaser for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/from-zero-to-hero-establishing-a-new-social-media-presence-facebook-for-2024/"><u>From Zero to Hero Establishing a New Social Media Presence (Facebook) for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/hacks-to-do-pokemon-go-trainer-battles-for-oppo-a1-5g-drfone-by-drfone-virtual-android/"><u>Hacks to do pokemon go trainer battles For Oppo A1 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-start-w11s-on-demand-repair-service/"><u>How to Start W11’s On-Demand Repair Service</u></a></li>
<li><a href="https://windows11.techidaily.com/joining-the-ranks-of-windows-11-insiders-explained/"><u>Joining the Ranks of Windows 11 Insiders Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-erased-typing-on-windows-systems/"><u>Mending Erased Typing on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/off-sight-panes-not-anymore-revive-them-with-these-6-secrets-for-windows-users/"><u>Off-Sight Panes? Not Anymore! Revive Them with These 6 Secrets for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-0x80072af9-error-in-windows-os/"><u>Overcoming 0X80072AF9 Error in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-reduce-cpu-and-ram-overuse-from-unrealcefsubprocess-on-pcs/"><u>Strategies to Reduce CPU and RAM Overuse From UnrealCEFSubprocess on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-winstore-problems-effective-fix-for-0x80072f17/"><u>Tackling WinStore Problems: Effective Fix for 0X80072f17</u></a></li>
<li><a href="https://windows11.techidaily.com/transcending-boundaries-how-windows-enhances-gameplay/"><u>Transcending Boundaries: How Windows Enhances Gameplay</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-edges-additional-taskers/"><u>Unraveling the Mystery of Edge's Additional Taskers</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/unveiling-the-highest-scoring-usb-memory-sticks-for-this-year-2/"><u>Unveiling the Highest-Scoring USB Memory Sticks for This Year, 2</u></a></li>
</ul></div>

