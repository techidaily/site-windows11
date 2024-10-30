---
title: Ten Steps to Clear Win11 DNS Cache
date: 2024-10-28T16:18:31.101Z
updated: 2024-10-30T16:51:36.938Z
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
<span id="1834903">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1834903.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16836-1834903">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1834903.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2F25home.pxf.io%2Fc%2F5597632%2F1834903%2F16836'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1834903/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Flush the DNS Cache on Windows 11

 There are multiple methods to flush the DNS cache on Windows 11\. You can use the Run command box, Command Prompt, or even PowerShell. In addition, you can use a batch file to clear the DNS cache in a few clicks, any time you want. Here are the four ways to clear DNS on Windows 11:

### 1\. Using the Run Command Box

To flush the DNS cache using the Run command box, do as follows:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type “**ipconfig /flushdns** ” command.  
![Flush DNS Using the Run Command Box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-the-run-command-box.jpg)
3. Press**Ctrl + Shift + Enter** keys at once. The Command Prompt will launch, execute the flush command, and close automatically.

### 2\. Using CMD

 To clear the DNS resolver cache using CMD, repeat the following steps:

1. Press**Win + R** to open the run dialog box. Type**cmd** and press**Ctrl + Shift + Enter** keys at once.
2. CMD will open with admin privileges.
3. Type “**ipconfig /flushdns** ” command and press the**Enter** key.  
![Flush DNS Using CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-cmd.jpg)
4. You will see a “**Successfully flushed the DNS Resolver Cache.** ” message after the command execution.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075472/7443" target="_top" id="2075472">
  <img src="//a.impactradius-go.com/display-ad/7443-2075472" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075472/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 3\. Using PowerShell

 PowerShell has a different command to flush the DNS cache on Windows 11\. Here’s how to do it:

1. Press**Win + S** and type**PowerShell** . Click on the**Run as administrator** option in the Start menu.
2. Now, type “**Clear-DnsClientCache** ” in the PowerShell window and press the**Enter** key.  
![Flush DNS Using Powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-powershell.jpg)
3. You won’t see a message after the command executes successfully. But you can open PowerShell again and view the DNS cache to confirm.

### 4\. Using a Batch File

 Opening an app is a slightly time-consuming process. You can save time by creating a batch file once and then running it whenever you need to flush DNS. No need to open the CMD or PowerShell app.

Repeat the following steps to create a DNS-clearing batch file:

1. Press**Win + S** to open Windows Search. Type**Notepad** and click on the first search result.
2. Type the following command in Notepad:**cmd.exe /k ipconfig /flushdns**  
![Flush DNS Using A Batch File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-a-batch-file.jpg)
3. Press**Ctrl + S** to save the file. Enter the name “**flushDNS.bat** ” and keep the**Save as type** as**All Files** .

<!-- affiliate ads begin -->
<span id="1983474">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983474.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983474">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983474.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983474%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983474/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137203/26400" target="_top" id="2137203">
  <img src="//a.impactradius-go.com/display-ad/26400-2137203" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137203/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-helps.techidaily.com/new-2024-approved-dramatic-fades-in-a-flash/"><u>[New] 2024 Approved Dramatic Fades in a Flash</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-optimize-video-search-with-these-top-7-youtube-tags-extractor-tools/"><u>[New] Optimize Video Search with These Top 7 Youtube Tags Extractor Tools</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-selecting-the-ultimate-gear-for-stellar-4k-production/"><u>[Updated] Selecting the Ultimate Gear for Stellar 4K Production</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-notorious-0xc00d36b4-windows-sound-issue/"><u>Fixing the Notorious 0XC00D36B4 Windows Sound Issue</u></a></li>
<li><a href="https://fox-access.techidaily.com/how-to-do-live-streaming-with-periscope-for-2024/"><u>How to Do Live Streaming with Periscope for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-iphone-se-2020-system-issues-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair iPhone SE (2020) System Issues? | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-lava-yuva-2frp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Lava Yuva 2FRP Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-lost-access-to-windows-command-center/"><u>Recovering Lost Access to Windows Command Center</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/shades-of-genius-3-proven-tricks-for-color-correction-success-for-2024/"><u>Shades of Genius 3 Proven Tricks for Color Correction Success for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-the-windows-search-interface-no-graphics/"><u>Simplifying the Windows Search Interface: No Graphics</u></a></li>
<li><a href="https://windows11.techidaily.com/websites-as-apps-step-by-step-windows-installation/"><u>Websites as Apps: Step-by-Step Windows Installation</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/windows-11-premium-video-grabber-selections-for-2024/"><u>Windows 11 Premium Video Grabber Selections for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/winvolume-fix-resetting-saving-settings-for-audio/"><u>WinVolume Fix: Resetting Saving Settings for Audio</u></a></li>
</ul></div>

