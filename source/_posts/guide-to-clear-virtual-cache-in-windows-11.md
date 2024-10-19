---
title: Guide to Clear Virtual Cache in Windows 11
date: 2024-10-16T21:39:53.033Z
updated: 2024-10-19T00:28:33.224Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915810/19272" target="_top" id="1915810">
  <img src="//a.impactradius-go.com/display-ad/19272-1915810" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915810/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Use the System Properties window

 If you want to reset virtual memory settings on your Windows device, you can use the System Properties window. To do this, press **Win + R** on your keyboard to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).

 In the text box, type **sysdm.cpl**, and hit Enter. A system properties window will open up. Then, go to the **Advanced** tab and click the **Settings** button in the Performance section.

![How to Reset Virtual Memory on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/how-to-reset-virtual-memory-on-windows-11.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139121/17108" target="_top" id="2139121">
  <img src="//a.impactradius-go.com/display-ad/17108-2139121" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139121/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This will open up the Performance Options window, where you can manage virtual memory settings. For this, switch to the **Advanced** tab and click on **Change** in the Virtual Memory section.

![Reset Page Size](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-page-size.jpg)

 On the next screen, uncheck the **Automatically manage paging file size for all drives** checkbox and select the drive you want to configure virtual memory. Normally, this will be the drive on which Windows is installed.

 Set the custom size for virtual memory. Then, check the **No paging file** radio button and click **Set**. If you see a warning message, click **Yes** to confirm.

 After following the above steps, click **OK** to save your changes. Now close the System Properties and Settings windows and restart your computer. The new virtual memory settings should now be in effect.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130885/7443" target="_top" id="2130885">
  <img src="//a.impactradius-go.com/display-ad/7443-2130885" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130885/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Use Group Policy Editor

 You can also use the Local Group Policy Editor to reset virtual memory settings on your Windows device. But remember that this method is only available on Pro and Enterprise editions.

 If you're using a Home edition, you should first [enable the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To get started, open the Run dialog box and type **gpedit.msc** into the text box. Then click **OK** or press Enter to open the Local Group Policy Editor window.

![Clear virtual memory pagefile Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clear-virtual-memory-pagefile-using-group-policy.jpg)

 Then navigate to the following location:

Local Computer Policy > Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Option

 Scroll down and double-click **Shutdown: Clear virtual memory pagefile** policy. In the Properties window, select Enabled and then click **Apply**. Next, click **OK** to save it.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151856/7443" target="_top" id="2151856">
  <img src="//a.impactradius-go.com/display-ad/7443-2151856" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151856/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Use Registry Editor

 If you don't have access to the Local Group Policy Editor, you can also use the Registry Editor to reset virtual memory settings on Windows. Before proceeding, you should [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) in case something gets wrong.

![Reset Virtual Memory Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-virtual-memory-using-registry.jpg)

 To get started, search for **Registry Editor** in the Start menu and click on it. Once you open the Registry Editor, navigate to the following path:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Memory Management

 Next, double-click on the **ClearPageFileAtShutdown** key and set its value to **1**. Click on the **OK** button to save your changes.

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
<li><a href="https://fox-info.techidaily.com/new-2024-approved-unlock-the-potential-of-audience-feedback-on-youtube/"><u>[New] 2024 Approved Unlock the Potential of Audience Feedback on YouTube</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-how-to-install-your-complete-guide-to-vrecord-for-2024/"><u>[New] How to Install Your Complete Guide to VRecord for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-charting-the-undisclosed-territories-of-youtube-videos/"><u>[New] In 2024, Charting the Undisclosed Territories of YouTube Videos</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-in-2024-accelerating-video-conversion-youtube-to-mpeg-edition/"><u>[Updated] In 2024, Accelerating Video Conversion YouTube to MPEG Edition</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-style-sleuths-influential-beauty-creators/"><u>[Updated] In 2024, Style Sleuths Influential Beauty Creators</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-step-by-step-guide-live-broadcast-of-recorded-videos-on-fb-for-2024/"><u>[Updated] Step-by-Step Guide Live Broadcast of Recorded Videos on FB for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-chrome-crashes-or-wont-open-on-xiaomi-redmi-note-12-4g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Chrome Crashes or Wont Open on Xiaomi Redmi Note 12 4G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/downloading-woes-fixing-file-transfer-issues-in-windows-11/"><u>Downloading Woes: Fixing File Transfer Issues in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-techniques-for-deactivating-win11s-hyper-v/"><u>Easy Techniques for Deactivating Win11's Hyper-V</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-low-sound-levels-for-external-speakers/"><u>Elevating Low Sound Levels for External Speakers</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-night-vision-with-dark-mode-for-notepad-on-win-11/"><u>Enhance Night Vision with Dark Mode for Notepad on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-speech-recognition-in-windows-pc/"><u>Enhance Speech Recognition in Windows PC</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-analyzing-tseries-earnings-via-youtube-engagement/"><u>In 2024, Analyzing TSeries Earnings via YouTube Engagement</u></a></li>
</ul></div>

