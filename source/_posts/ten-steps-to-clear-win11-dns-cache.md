---
title: Ten Steps to Clear Win11 DNS Cache
date: 2024-09-24T19:59:42.270Z
updated: 2024-10-01T21:26:40.174Z
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

## How to Flush the DNS Cache on Windows 11

 There are multiple methods to flush the DNS cache on Windows 11\. You can use the Run command box, Command Prompt, or even PowerShell. In addition, you can use a batch file to clear the DNS cache in a few clicks, any time you want. Here are the four ways to clear DNS on Windows 11:

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948954/19272" target="_top" id="1948954">
  <img src="//a.impactradius-go.com/display-ad/19272-1948954" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948954/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://aligracehair.sjv.io/c/5597632/2012434/19272" target="_top" id="2012434">
  <img src="//a.impactradius-go.com/display-ad/19272-2012434" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012434/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 3\. Using PowerShell

 PowerShell has a different command to flush the DNS cache on Windows 11\. Here’s how to do it:

1. Press**Win + S** and type**PowerShell** . Click on the**Run as administrator** option in the Start menu.
2. Now, type “**Clear-DnsClientCache** ” in the PowerShell window and press the**Enter** key.  
![Flush DNS Using Powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-powershell.jpg)
3. You won’t see a message after the command executes successfully. But you can open PowerShell again and view the DNS cache to confirm.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016143/19272" target="_top" id="2016143">
  <img src="//a.impactradius-go.com/display-ad/19272-2016143" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016143/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/352557/5172" target="_top" id="352557">
  <img src="//a.impactradius-go.com/display-ad/5172-352557" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/352557/5172" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-links.techidaily.com/new-in-2024-harmonious-hushes-softening-sounds-with-garageband/"><u>[New] In 2024, Harmonious Hushes Softening Sounds with Garageband</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-mastering-pc-hd-video-viewing-and-editing-with-windows-hdr-support/"><u>[New] Mastering PC HD Video Viewing & Editing with Windows HDR Support</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-breakdown-of-leading-free-video-conferencing-services-for-commercial-and-academic-use/"><u>2024 Approved Breakdown of Leading Free Video Conferencing Services for Commercial and Academic Use</u></a></li>
<li><a href="https://howto.techidaily.com/4-solutions-to-fix-unfortunately-your-app-has-stopped-error-on-poco-c55-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Solutions to Fix Unfortunately Your App Has Stopped Error on Poco C55 | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/corrective-actions-to-address-the-absence-of-winhttpdll-file/"><u>Corrective Actions to Address the Absence of Winhttp.dll File</u></a></li>
<li><a href="https://windows11.techidaily.com/easily-switch-your-windows-11-logon-technique-ditch-pin-embrace-password/"><u>Easily Switch Your Windows 11 Logon Technique: Ditch PIN, Embrace Password</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-strategies-for-cleansing-steam-dns-cache/"><u>Effective Strategies for Cleansing Steam DNS Cache</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-strategies-to-address-directdraw-errors-in-newer-windows-editions/"><u>Efficient Strategies to Address DirectDraw Errors in Newer Windows Editions</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-to-the-top-with-these-key-windows-11-widgets/"><u>Elevate to the Top with These Key Windows 11 Widgets</u></a></li>
<li><a href="https://windows11.techidaily.com/embrace-the-best-of-both-worlds-windows-11-macos-in-parallels/"><u>Embrace the Best of Both Worlds: Windows 11, MacOS in Parallels</u></a></li>
<li><a href="https://windows11.techidaily.com/embracing-convenience-using-googles-nearby-share/"><u>Embracing Convenience: Using Google's Nearby Share</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-smooth-remote-play-via-windows-steam/"><u>Enabling Smooth Remote Play via Windows Steam</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-performance-win11-boot-routines/"><u>Enhancing Performance: Win11 Boot Routines</u></a></li>
<li><a href="https://windows11.techidaily.com/error-2e-prevention-ensure-windows-update-works/"><u>Error 2E Prevention, Ensure Windows Update Works</u></a></li>
<li><a href="https://win-blog.techidaily.com/fixing-call-of-duty-wwii-error-4103-a-comprehensive-guide/"><u>Fixing Call of Duty: WWII Error 4103 – A Comprehensive Guide</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/galactic-grandeur-in-hd-optimal-websites-featuring-the-sky-for-2024/"><u>Galactic Grandeur in HD Optimal Websites Featuring the Sky for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-can-i-get-more-stardust-in-pokemon-go-on-tecno-spark-go-2024-drfone-by-drfone-virtual-android/"><u>In 2024, How can I get more stardust in pokemon go On Tecno Spark Go (2024)? | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/is-inshot-the-best-video-editing-app-our-in-depth-review/"><u>Is InShot the Best Video Editing App? Our In-Depth Review</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/mastermind-mind-games-trivia-channel-hunt-for-24/"><u>Mastermind Mind Games - Trivia Channel Hunt for '24</u></a></li>
</ul></div>

