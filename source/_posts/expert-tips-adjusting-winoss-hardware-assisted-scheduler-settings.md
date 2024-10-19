---
title: "Expert Tips: Adjusting WinOS's Hardware-Assisted Scheduler Settings"
date: 2024-10-16T02:47:48.301Z
updated: 2024-10-18T17:05:59.886Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Expert Tips: Adjusting WinOS's Hardware-Assisted Scheduler Settings"
excerpt: "This Article Describes Expert Tips: Adjusting WinOS's Hardware-Assisted Scheduler Settings"
keywords: WinOS Scheduling Guide,Optimize Windows Performance,Hardware Scheduler Tweaks,Enhance OS Speed Windows,WinOS System Tuning Tips,Advanced Windows Setup,Custom Scheduler Settings
thumbnail: https://thmb.techidaily.com/965071db1f866296dbd6b7c6cdfb4395621995dd58483ee49e8397ad83cab217.jpg
---

## Expert Tips: Adjusting WinOS's Hardware-Assisted Scheduler Settings

 If you were looking for new ways to get more out of your hardware, chances are you’ve enabled the Hardware accelerated GPU scheduling feature on your computer. While it’s supposed to improve your computer’s performance, it might have a negative effect, if your GPU is a bit older.

 In this case, should you disable it? But how can you turn off Hardware accelerated GPU scheduling in Windows 10 and 11?

## What Is Hardware Accelerated GPU Scheduling?

 Hardware-accelerated GPU scheduling is a feature designed to reduce the load on your CPU during intensive tasks. Usually, the CPU assigns the graphics-intensive data to the GPU, so games, media-playing apps, or editing software run smoothly. To do so, the CPU gathers, assigns, and sets the priority for each task so the GPU can render it.

 When the hardware-accelerated GPU scheduling feature is enabled, the dedicated GPU-based scheduler will handle the high-priority tasks. This way, the CPU can execute more tasks in the same amount of time.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997643/19272" target="_top" id="1997643">
  <img src="//a.impactradius-go.com/display-ad/19272-1997643" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997643/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Should You Disable Hardware Accelerated GPU Scheduling?

![Discrete GPU made by NVIDIA](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/Discrete-GPU-by-NVIDIA.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148639/16836" target="_top" id="2148639">
  <img src="//a.impactradius-go.com/display-ad/16836-2148639" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148639/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Most of the time, [GPU hardware scheduling is worth turning on in Windows](https://www.makeuseof.com/windows-10-gpu-hardware-scheduling-worth-turning-on/), especially if your computer isn’t equipped with one of the latest GPU models. But enabling the GPU scheduling feature can also backfire, and have a negative impact on your computer’s performance. For example, on an older GPU, it might cause latency between the frames or even significant lag while gaming.

 Also, GPU scheduling is known for causing conflict with Windows services, such as dxgmms2.sys, which helps render graphics, especially during gaming sessions. So, if you keep running into the [dxgmms2.sys error in Windows 11](https://www.makeuseof.com/windows-11-dxgmms2-sys-error-fix/), you’ll have to disable the Hardware- accelerated GPU scheduling feature.

 In addition to this, the feature might encounter compatibility issues with specific hardware or software. So, you have to turn off GPU scheduling to keep your computer running smoothly.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144276/7443" target="_top" id="2144276">
  <img src="//a.impactradius-go.com/display-ad/7443-2144276" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144276/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Disable Hardware Accelerated GPU Scheduling

 If the cons outweigh the pros, it’s time to disable Windows GPU scheduling. We’ll walk you through two different methods, so you can choose the one that works best for you.

### Disable Hardware Accelerated GPU Scheduling Through Windows Settings

 The easiest way to disable the Hardware Accelerated GPU Scheduling feature is through Windows Settings. Here’s how you can do it on a Windows 11 computer:

1. Press **Win + I** to bring up the Settings menu.
2. Go to **System > Display**.
3. From the **Related settings** list, click on **Graphics**.
4. Click **Change default graphics settings**.
5. At the top of the page, turn off the toggle for **Hardware-accelerated GPU scheduling**.
6. Reboot your system.

![The Optimizations for windowed games setting option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/optimizations-for-windowed-games-setting.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130532/26400" target="_top" id="2130532">
  <img src="//a.impactradius-go.com/display-ad/26400-2130532" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130532/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you’re using Windows 10, here’s how you can disable the GPU hardware scheduling feature:

1. Right-click the **Start** button and select **Settings**.
2. Head to **System > Display**.
3. From the **Multiple Displays** menu, click on **Graphics settings**.
4. Turn off the toggle below **Hardware-accelerated GPU scheduling**.
5. Restart your computer for the change to take place.

![How to disable hardware accelerated gpu-scheduling in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/hardware-acc-win10-1.jpg)

### Disable Hardware Accelerated GPU Scheduling Through Windows Registry

 If your graphics driver is outdated or corrupted, the hardware accelerated feature might be missing from the Settings menu. If you don’t have the time to replace or [update the graphics driver](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/) right now, you can still disable hardware-accelerated GPU scheduling through Windows Registry.

1. Press **Win + R** to bring up a Run dialog.
2. Type **regedit** and press **Enter**.
3. In the Registry Editor window, head to **HKEY\_LOCAL\_MACHINE > SYSTEM > CurrentControlSet > Control > GraphicsDrivers**.
4. In the right pane, open the **HwSchMode** value.
5. Set **Value data** to **1**.
6. Click **OK** and restart your computer.

![How to disable hardware accelerated GPU scheduling through Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/registry-acc-1.jpg)

## GPU Scheduling Is Good, but It’s Not Perfect

 We’ve taken a look at how Hardware accelerated GPU scheduling works and when you should disable it. As we’ve mentioned, it may cause system issues, so it might be better to turn it off and look for alternatives. Fortunately, Windows comes with more built-in features to help you improve your gaming experience.

 In this case, should you disable it? But how can you turn off Hardware accelerated GPU scheduling in Windows 10 and 11?

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-spotlight-strategies-for-solo-talent-vs-tiktok-titans/"><u>[New] 2024 Approved Spotlight Strategies for Solo Talent Vs. TikTok Titans</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-effortlessly-enhancing-tiktok-bios-with-linktree-feature/"><u>2024 Approved Effortlessly Enhancing TikTok Bios with Linktree Feature</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/critical-alert-msis-z790-motherboards-face-failures-due-to-pch-chip-problems-manufacturing-glitch-suspected-in-limited-shipments/"><u>Critical Alert: MSI's Z790 Motherboards Face Failures Due to PCH Chip Problems – Manufacturing Glitch Suspected in Limited Shipments</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-execution-shortcuts-for-microsoft-project-success/"><u>Elevate Your Execution: Shortcuts for Microsoft Project Success</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-your-windows-screenshot-game-with-these-fixes/"><u>Elevating Your Windows Screenshot Game with These Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-ad-ds-errors-impacting-windows-11-printing/"><u>Eliminating AD DS Errors Impacting Windows 11 Printing</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-error-0x8024a205-in-windows-update/"><u>Eliminating Error 0X8024a205 in Windows Update</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-issues-with-windows-alt-key-functions-47-characters/"><u>Eliminating Issues with Windows ALT Key Functions (47 Characters)</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-printer-use-within-windows-11-edge-protection/"><u>Enabling Printer Use Within Windows 11 Edge Protection</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-efficiency-crafting-shortcuts-next-to-power-on-windows-11/"><u>Enhancing Efficiency: Crafting Shortcuts Next to Power on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-user-experience-reactivating-silent-notifications/"><u>Enhancing User Experience: Reactivating Silent Notifications</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/favorite-phones-amongst-tech-experts-discover-the-choice-of-zdnets-staff/"><u>Favorite Phones Amongst Tech Experts - Discover the Choice of ZDNet's Staff</u></a></li>
<li><a href="https://tech-haven.techidaily.com/intelligent-insights-await-how-microsoft-bing-is-revolutionizing-search-with-artificial-intelligence/"><u>Intelligent Insights Await: How Microsoft Bing Is Revolutionizing Search with Artificial Intelligence</u></a></li>
<li><a href="https://fox-access.techidaily.com/reveal-new-dimensions-of-communication-access-free-vocal-effects-here-for-2024/"><u>Reveal New Dimensions of Communication - Access Free Vocal Effects Here for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/the-art-of-livestreaming-seminars-at-no-expense-for-2024/"><u>The Art of Livestreaming Seminars at No Expense for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-ultimate-solution-for-persistent-problems-with-non-opening-applications/"><u>The Ultimate Solution for Persistent Problems with Non-Opening Applications</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-guide-efficient-techniques-for-home-stereo-speaker-maintenance/"><u>Ultimate Guide: Efficient Techniques for Home Stereo Speaker Maintenance</u></a></li>
</ul></div>

