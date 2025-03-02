---
title: Ten Steps to Clear Win11 DNS Cache
date: 2025-02-28T00:36:56.060Z
updated: 2025-03-01T20:03:23.794Z
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
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-the-ultimate-guide-to-efficient-mac-screenshotting-via-keyboard/"><u>[New] 2024 Approved The Ultimate Guide to Efficient Mac Screenshotting via Keyboard</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-how-to-screen-record-on-mac-with-shortcuts/"><u>[Updated] How to Screen Record on Mac with Shortcuts</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-secure-whole-page-scene-for-2024/"><u>[Updated] Secure Whole-Page Scene for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-transforming-images-via-look-up-table-techniques-in-adobes-image-editor/"><u>2024 Approved Transforming Images via Look-Up Table Techniques in Adobe's Image Editor</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/discover-the-ideal-antivirus-solutions-for-apples-ios-top-6-picks-revealed/"><u>Discover the Ideal Antivirus Solutions for Apple's iOS – Top 6 Picks Revealed</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-multiple-monitor-troubles-in-windows/"><u>Fixing Multiple-Monitor Troubles in Windows</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixing-the-issue-how-to-troubleshoot-a-non-responsive-rockstar-games-launcher/"><u>Fixing the Issue: How to Troubleshoot a Non-Responsive Rockstar Games Launcher</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/guaranteed-data-restoration-tools-for-iphones-no-more-worries/"><u>Guaranteed Data Restoration Tools for iPhones - No More Worries</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-do-cellular-service-companies-work-unveiling-the-basics/"><u>How Do Cellular Service Companies Work? Unveiling the Basics</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-halt-chromiums-automatic-creation-of-new-windows-tabs/"><u>How to Halt Chromium's Automatic Creation of New Windows Tabs</u></a></li>
<li><a href="https://article-posts.techidaily.com/master-plan-youtube-content-into-mp4-for-2024/"><u>Master Plan YouTube Content Into MP4 for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-creating-secure-window-11-lock-patterns/"><u>Master the Art of Creating Secure Window 11 Lock Patterns</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-startup-routine-windows-exploration-guide/"><u>Mastering the Startup Routine: Windows Exploration Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-activation-of-windows-11s-dialer/"><u>Seamless Activation of Windows 11'S Dialer</u></a></li>
<li><a href="https://windows11.techidaily.com/secrets-to-overcoming-non-installed-hard-drive-dilemranacies-win-11-edition/"><u>Secrets to Overcoming Non-Installed Hard Drive Dilemranacies, Win 11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-engage-windows-terminal-in-quake/"><u>Steps to Engage Windows Terminal in Quake</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-stuck-windows-handbrake-usage/"><u>Transform Stuck Windows HandBrake Usage</u></a></li>
</ul></div>

