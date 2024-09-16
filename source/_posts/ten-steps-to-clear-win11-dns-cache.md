---
title: Ten Steps to Clear Win11 DNS Cache
date: 2024-09-09T19:01:09.627Z
updated: 2024-09-15T17:56:21.795Z
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
<a href="https://unicoeye.pxf.io/c/5597632/2134246/18498" target="_top" id="2134246">
  <img src="//a.impactradius-go.com/display-ad/18498-2134246" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134246/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 3\. Using PowerShell

 PowerShell has a different command to flush the DNS cache on Windows 11\. Here’s how to do it:

1. Press**Win + S** and type**PowerShell** . Click on the**Run as administrator** option in the Start menu.
2. Now, type “**Clear-DnsClientCache** ” in the PowerShell window and press the**Enter** key.  
![Flush DNS Using Powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-powershell.jpg)
3. You won’t see a message after the command executes successfully. But you can open PowerShell again and view the DNS cache to confirm.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135369/19272" target="_top" id="2135369">
  <img src="//a.impactradius-go.com/display-ad/19272-2135369" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135369/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136619/26400" target="_top" id="2136619">
  <img src="//a.impactradius-go.com/display-ad/26400-2136619" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136619/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://extra-resources.techidaily.com/new-banish-coffee-stains-free-iphone-app-to-remove-red-eyes/"><u>[New] Banish Coffee Stains Free iPhone App to Remove Red Eyes</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-a-comprehensive-guide-to-producing-engaging-subtitles-and-captions-for-fb/"><u>[Updated] A Comprehensive Guide to Producing Engaging Subtitles and Captions for FB</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-the-pros-pathway-to-professional-video-conferencing-with-slack-and-filmora/"><u>[Updated] In 2024, The Pro's Pathway to Professional Video Conferencing with Slack & Filmora</u></a></li>
<li><a href="https://extra-information.techidaily.com/discover-a-world-of-creative-slide-show-patterns-at-no-cost/"><u>Discover a World of Creative Slide Show Patterns at No Cost</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-spy-on-text-messages-from-computer-and-motorola-defy-2-drfone-by-drfone-virtual-android/"><u>How to Spy on Text Messages from Computer & Motorola Defy 2 | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/prime-top-10-audio-capture-software-for-spotify-users/"><u>Prime Top 10 Audio Capture Software for Spotify Users</u></a></li>
<li><a href="https://windows11.techidaily.com/prioritize-your-pcs-protection-with-these-downloads/"><u>Prioritize Your PC's Protection with These Downloads</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaim-your-typing-efficiency-with-9-proven-fixes-for-broken-windows-shortcut-commands/"><u>Reclaim Your Typing Efficiency with 9 Proven Fixes for Broken Window's Shortcut Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagine-windows-interface-a-journey-to-larger-icons/"><u>Reimagine Windows Interface: A Journey to Larger Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-enabling-dark-display-on-calc-app/"><u>Step by Step: Enabling Dark Display on Calc App</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-overcome-java-virtual-machine-error-on-pcs/"><u>Steps to Overcome Java Virtual Machine Error on PCs</u></a></li>
<li><a href="https://apple-account.techidaily.com/unlock-apple-id-without-phone-number-on-apple-iphone-6s-by-drfone-ios/"><u>Unlock Apple ID without Phone Number On Apple iPhone 6s</u></a></li>
<li><a href="https://fox-that.techidaily.com/why-isnt-my-iphone-syncing-emails-solutions-to-update-your-inbox-efficiently/"><u>Why Isn't My iPhone Syncing Emails? Solutions to Update Your Inbox Efficiently</u></a></li>
</ul></div>

