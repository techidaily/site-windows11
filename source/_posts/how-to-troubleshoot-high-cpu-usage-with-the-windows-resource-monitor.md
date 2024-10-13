---
title: How to Troubleshoot High CPU Usage With the Windows Resource Monitor
date: 2024-10-07T19:36:19.501Z
updated: 2024-10-12T16:01:03.587Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Troubleshoot High CPU Usage With the Windows Resource Monitor
excerpt: This Article Describes How to Troubleshoot High CPU Usage With the Windows Resource Monitor
keywords: Solve Win CPU Spikes,Lowering PC Overuse,Resource Monitor Guide,Reducing CPU Load,Troubleshoot High Usage,Manage Windows Resources,Optimize Task Performance
thumbnail: https://thmb.techidaily.com/264e08da433495c55cd3d8de7fab0afb684fb451a8ac533f579ade7f75a2ecaa.png
---

## How to Troubleshoot High CPU Usage With the Windows Resource Monitor

 The Resource Monitor application offers a detailed graphical user interface to help you monitor the behavior of your system resources. The app's interface may seem confusing at first, but once you get to know it better, it'll become an indispensable tool when troubleshooting high CPU usage issues on Windows.

 So, let's take a look at some use cases of the Resource Monitor application on Windows.

## What Does the Resource Monitor Utility on Windows do?

 You may have experienced the headache of a Windows PC slowing to a crawl due to high CPU usage. Generally, CPU usage increases due to either background processes or heavy applications currently running on your system. The good news is that you can easily pinpoint which apps or services are consuming your CPU cycles. This is where Windows' built-in Resource Monitor tool comes in handy.

 Resource Monitor provides you with real-time information on hardware utilization by all processes and services. With its graphical charts and numerical data, you can quickly diagnose high CPU issues and take action to resolve them.

## What Can You Monitor Using Resource Monitor?

 The Resource Monitor dashboard provides an overview of current system-wide resource utilization across four key areas:

* **CPU usage:** This section graphs overall CPU usage over time and displays a list of processes with their CPU impact. It provides details like PID, status, thread count, and CPU cycles consumed.
* **Memory usage:** You can view details about your system’s memory like the total physical memory and the processes consuming memory from here.
* **Disk activity:** This tab is for monitoring current disk operations broken down by reads/writes. It includes a histogram that charts the response time distribution.
* **Network activity:** Here, you can track sent/received bytes by process along with real-time network utilization graphs.

![Resource Monitor Overview Tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/resource-monitor-overview-tab.jpg)

 Combined, these categories give you full visibility into all hardware resource consumption by every process and service. If you’re not a technical geek, you can still get some useful information from there for troubleshooting.

## 1\. How to Troubleshoot High CPU Usage With the Resource Monitor

 In the event of an unresponsive, sluggish computer, the first step is to [open the Resource Monitor](https://www.makeuseof.com/windows-11-open-resource-monitor/) and check the **CPU** tab.

 Here, you'll find two types of sections - the overall CPU usage graph and the per-process CPU usage list. The usage graph is pretty easy to understand, but the main use is of the processes list with all the details.

![Resource Monitor CPU Tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/resource-monitor-cpu-tab.jpg)

 The CPU history graphs at the top show overall CPU usage over time, broken down by category. If you see a blue-colored spike, it indicates that there was a sudden increase in CPU usage. This could be due to a specific process or application consuming a considerable portion of your overall CPU resources.

 On your left side, click the **CPU** column header to sort processes in descending order of current CPU usage. Note that the numbers are just the percentage of the process consuming the CPU. So, a higher number means it's consuming more CPU power than others.

 If your system is slow, and you’re unable to use Resource Monitor, check [how to fix Resource Monitor on Windows](https://www.makeuseof.com/how-to-fix-resource-monitor-not-working-windows-11/) for help.

## 2\. How to Diagnose a Slow Internet Connection With the Resource Monitor

 Resource Monitor also makes it easy to determine if network connectivity issues like slow internet or high latency are being caused by a bandwidth-hogging application.

 Simply click the **Total (B/sec)** column header to sort processes by network usage rate and identify any heavy bandwidth consumers. Programs such as your active web browser or any game you're currently running will surely consume more data. But, besides such programs, if any of the processes is displaying a high number, it's a warning sign for you.

![Resource Monitor Network Tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/resource-monitor-network-tab.jpg)

 With network-related metrics isolated per process, Resource Monitor helps simplify diagnosing connectivity slowdowns. After that, you can also read [how to fix a slow internet connection on Windows](https://www.makeuseof.com/tag/fix-internet-speed-windows-tweaks/) to learn more useful ways.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880940/19272" target="_top" id="1880940">
  <img src="//a.impactradius-go.com/display-ad/19272-1880940" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880940/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. How to Check Disk Activity With the Resource Monitor

 Sluggish system performance is not always the CPU's fault. Sometimes, poor disk activity can also be a major drag if processes are queuing excessive read/write operations.

 This is where Resource Monitor's Disk tab provides valuable insight. The disk usage graphs on the right side show you real-time reads and writes.

 But most importantly, the process disk activity list reveals which specific apps or services are doing all that writing and reading. Click the **Total (B/sec)** column to sort by disk usage rate and see the top troubling processes. The rest of the columns show separate read and write operations for each process.

![Resource Monitor Disk Tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/resource-monitor-disk-tab.jpg)

<!-- affiliate ads begin -->
<span id="2135471">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2135471.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2135471">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2135471.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2135471%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2135471/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you're unable to decide which process to stop, please check out [how to fix high disk usage](https://www.makeuseof.com/tips-fix-100-disk-usage-improve-windows-performance/) to improve your disk's performance.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398455/3022" target="_top" id="398455">
  <img src="//a.impactradius-go.com/display-ad/3022-398455" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398455/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. How to Find Memory-Consuming Processes With the Resource Monitor

 Available memory is as important to performance as CPU and disk resources. A memory leak can bring even the beefiest system to its knees. The best part is that Resource Monitor provides you with enough details to [troubleshoot your system’s memory](https://www.makeuseof.com/windows-computer-low-memory/).

 In Resource Monitor's Memory tab, there are multiple metrics to monitor. The main ones are **Free memory**, **In Use memory**, and **Hard Faults/sec**.

![Resource Monitor Memory Tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/resource-monitor-memory-tab.jpg)

 The **Free** and **In Use** memory count display the amount of memory currently unused and the amount used by the system, respectively. If you see the In Use memory count rising too high, make sure to close some unnecessary running programs.

 On the other side, if the values of Hard Faults/sec are higher (click on its name to sort), it indicates that your system is experiencing memory pressure. In simple terms, a higher value shows that your system is relying on virtual memory to compensate for the lack of physical RAM.

 To see which processes are consuming the most memory, click the **Working Set (Memory)** column header to sort by current memory usage. Then, you can identify any outliers hogging available RAM.

 With the available memory information and our below-given tips, you can troubleshoot memory bottlenecks easily:

* If a process shows high memory usage, try closing that specific application (via the Task Manager) and then restart your PC.
* If possible, add more RAM if available memory maxes out regularly. The applications you use on your PC may require more RAM than currently installed.
* Check out [how to disable startup programs on Windows](https://www.makeuseof.com/windows-11-disable-startup-programs/) and try disabling those that you won't require immediately when you turn on your PC.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137223/26400" target="_top" id="2137223">
  <img src="//a.impactradius-go.com/display-ad/26400-2137223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137223/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Keep an Eye Out for CPU-Consuming Processes With the Resource Monitor

 By understanding the basics of using Resource Monitor, you can move from simply staring blankly at a slow, unresponsive computer to pinpointing exactly which processes or services are hogging your system resources.

 We highly recommend going through each tab and using the sorting capabilities to check the offenders by CPU, network, disk, and memory usage. Once you identify the resource hogs, you can stop the problematic processes/tasks.

 So, let's take a look at some use cases of the Resource Monitor application on Windows.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-helps.techidaily.com/new-2024-approved-how-to-navigate-apples-podcast-acceptance-policy/"><u>[New] 2024 Approved How to Navigate Apple's Podcast Acceptance Policy</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-the-perfect-screen-recording-toolkit-systematic-how-to-manual-for-2024/"><u>[New] The Perfect Screen Recording Toolkit Systematic How-To Manual for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-inside-vidma-a-new-chapter-in-video-capture-tech/"><u>[Updated] 2024 Approved Inside Vidma A New Chapter in Video Capture Tech</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-your-key-to-digital-audio-conversion-from-srt-to-xmlssattml-guide/"><u>2024 Approved Your Key to Digital Audio Conversion From SRT to XML/SSA/TTML Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-guide-to-hyper-v-installation-in-win-11-home/"><u>A Comprehensive Guide to Hyper-V Installation in Win 11 Home</u></a></li>
<li><a href="https://windows11.techidaily.com/adapting-the-oculus-quest-2-for-windows-os-virtual-reality/"><u>Adapting the Oculus Quest 2 for Windows OS Virtual Reality</u></a></li>
<li><a href="https://win-great.techidaily.com/best-blu-ray-media-playback-devices-for-windows-8-users-streamline-your-cinema-experience/"><u>Best Blu-Ray Media Playback Devices for Windows 8 Users: Streamline Your Cinema Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-your-gameplay-overcoming-lags-in-warfare/"><u>Elevating Your Gameplay: Overcoming Lags in Warfare</u></a></li>
<li><a href="https://discover-advanced.techidaily.com/enhancing-customer-onboarding-with-mobile-ocr-technology/"><u>Enhancing Customer Onboarding with Mobile OCR Technology</u></a></li>
<li><a href="https://win-extraordinary.techidaily.com/how-to-allow-local-downloads-of-your-created-flipbooks-on-flipbuildercom/"><u>How To Allow Local Downloads of Your Created Flipbooks on FlipBuilder.com</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/is-it-possible-to-share-a-spotify-stream-simultaneously/"><u>Is It Possible to Share a Spotify Stream Simultaneously?</u></a></li>
<li><a href="https://buynow-info.techidaily.com/moto-g-power-analysis-exceptional-endurance-and-consistent-efficiency/"><u>Moto G Power Analysis: Exceptional Endurance & Consistent Efficiency</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-nitpicking-colors-8-tips-for-a-neutral-desktop/"><u>Navigating Nitpicking Colors: 8 Tips for a Neutral Desktop</u></a></li>
<li><a href="https://win-amazing.techidaily.com/parties-have-the-autonomy-to-choose-arbitrators-with-specific-expertise-relevant-to-their-dispute-something-not-possible-in-traditional-litigation/"><u>Parties Have the Autonomy to Choose Arbitrators with Specific Expertise Relevant to Their Dispute, Something Not Possible in Traditional Litigation.</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-setup-google-play-on-windows-11/"><u>Quick Setup: Google Play on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/recover-hidden-5ghz-link-in-windows-11-using-these-fixes/"><u>Recover Hidden 5GHz Link in Windows 11 Using These Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-language-input-change-keyboard-layouts-in-win-11/"><u>Simplifying Language Input: Change Keyboard Layouts in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unplugged-no-more-six-methods-to-restore-functioning-network-hardware-on-your-pc/"><u>Unplugged No More: Six Methods to Restore Functioning Network Hardware on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/utilizing-windows-widgets-for-real-time-resource-tracking/"><u>Utilizing Windows Widgets for Real-Time Resource Tracking</u></a></li>
</ul></div>

