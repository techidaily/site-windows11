---
title: "Utilizing Portable GPUs: No Internal Graphic Needed"
date: 2024-08-15T15:31:39.807Z
updated: 2024-08-16T15:31:39.807Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Utilizing Portable GPUs: No Internal Graphic Needed"
excerpt: "This Article Describes Utilizing Portable GPUs: No Internal Graphic Needed"
keywords: Portable GPU Use,External Graphics,GFX On-the-Go,Mobile Rendering,Outdoor Graphics,PGPU No Internal,Graphics Portability
thumbnail: https://thmb.techidaily.com/7270266df833210c4618ef395558e4a1dd14a566be785a358865debf94836fef.jpg
---

## Utilizing Portable GPUs: No Internal Graphic Needed

 Your Windows computer probably has integrated graphics, especially if it's a laptop. The problem with this type of GPU, which is built into the motherboard, is that it's usually less powerful than a dedicated GPU. So, if you have a dedicated GPU, which is usually more powerful, it makes sense that you might want it to take over the graphical performance of your computer.

 In this guide, we're going to show you how to disable integrated graphics on your Windows computer.

## How to Check If You Have A Dedicated GPU

 Before you disable your integrated GPU (iGPU), you need to verify that your computer has a dedicated GPU installed and that it's working properly. To do that, right-click an empty part of the Taskbar and select **Task Manager**.

![Task Manager Option in the Taskbar Context Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Task-Manager-Option.jpg)

 In Task Manager, select the **Performance** tab on the left and look at the number of GPUs available for your PC on the right. If there is more than one, then the other one is the dedicated GPU. In our case, **GPU 1** is the dedicated GPU, and if we click on it and scroll to the bottom, we can see that it says **Dedicated GPU Memory** in the rightmost panel.

![the Performace tab of Task Manager with the dedicated GPU selected](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/performace-tab-of-task-manager-with-gpu-selected-1.jpg)

 After you confirm you have an extra GPU on your computer, you can disable the iGPU.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
## How To Turn Off Your Windows Computer’s Integrated Graphics

 You can disable your iGPU in the Device Manager. To do that press **Win + R** to open Windows Run. Type **devmgmt.msc** in the text box and hit the **Enter** key to [open Device Manager](https://www.makeuseof.com/windows-open-device-manager/).

![Opening device driver with windows run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/opening-device-manager-with-run.png)
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->

 Expand the **Display adapters** section, right-click your integrated GPU, and select **Disable device**.

![disabling an iGPU in Device Manager on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disabling-igpu-in-device-manager.jpg)
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In the prompt that appears, confirm you want to disable the iGPU by clicking on **Yes**. That should turn off the integrated graphics on your Windows computer so that the system relies on the dedicated graphics.

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
## Should You Turn Off Integrated Graphics?

 While dedicated GPUs tend to be more powerful than iGPUs and can boost your computer's graphical performance, that is not always the case.

 So the decision to disable your integrated graphics is dependent on whether you have stronger dedicated graphics, and if you'll be running a lot of graphics-intensive applications, such as games and design software. As we covered in our [integrated vs. dedicated GPU](https://www.makeuseof.com/tag/can-shared-graphics-finally-compete-with-a-dedicated-graphics-card/) guide, dedicated GPUs are ideal for more intense operations.

 On the other hand, if you're not running anything graphics-intensive applications, or you need to reduce power consumption on a laptop, you don't need to disable the iGPU. Also, your Windows system might support switchable graphics, which allows it to decide which GPU to use depending on the application you're running.

 However, this may cause the iGPU to bottleneck the dedicated GPU in some scenarios if they're both running applications and there aren't enough system resources to go around.

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Use Your Dedicated Graphics Card When You Need It

 All in all, you're better off using your dedicated graphics card, especially if you are into graphically demanding applications. But if your computer doesn't have a dedicated GPU, disabling integrated graphics is not an option. The decision depends on what you're ultimately trying to achieve on your Windows computer.

 In this guide, we're going to show you how to disable integrated graphics on your Windows computer.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-blog.techidaily.com/024-approved-unveiling-10-high-growth-youtube-channels-that-inspire-you/"><u>[New] 2024 Approved  Unveiling 10 High-Growth YouTube Channels that Inspire You</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-strategies-to-outlast-your-competitors-in-snapping/"><u>[New] In 2024, Strategies to Outlast Your Competitors in Snapping</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-maximize-your-online-interactions-with-these-5-devices-for-2024/"><u>[New] Maximize Your Online Interactions with These 5 Devices for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-speeding-up-periscope-live-streams-explained/"><u>[New] Speeding Up Periscope Live Streams Explained</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-a-comprehensive-guide-to-softening-images-with-iphone-software-for-2024/"><u>[Updated] A Comprehensive Guide to Softening Images with iPhone Software for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-blissful-bites-best-stress-busting-gaming/"><u>[Updated] Blissful Bites  Best Stress-Busting Gaming</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-how-to-embed-facebook-live-on-a-website/"><u>[Updated] In 2024, How to Embed Facebook Live on a Website</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/3-ways-to-unlock-iphone-13-pro-without-passcode-or-face-id-drfone-by-drfone-ios/"><u>3 Ways to Unlock iPhone 13 Pro without Passcode or Face ID | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/6-quick-ways-to-fix-the-powerpoint-cant-save-file-error-in-windows-11/"><u>6 Quick Ways to Fix the PowerPoint Can't Save File Error in Windows 11</u></a></li>
<li><a href="https://change-location.techidaily.com/additional-tips-about-sinnoh-stone-for-vivo-y78plus-drfone-by-drfone-virtual-android/"><u>Additional Tips About Sinnoh Stone For Vivo Y78+ | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-tips-for-efficient-toolbar-usage-in-microsoft-win11-pcm/"><u>Advanced Tips for Efficient Toolbar Usage in Microsoft Win11 PCM</u></a></li>
<li><a href="https://extra-information.techidaily.com/blending-beats-and-visuals-a-tutorial-on-youtube-music-addition/"><u>Blending Beats and Visuals  A Tutorial on YouTube Music Addition</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722970972801-creep-occurs-at-high-temperatures-typically-above-04-times-a-materials-melting-temperature-in-kelvin/"><u>Creep Occurs at High Temperatures, Typically Above 0.4 Times a Material's Melting Temperature (in Kelvin).</u></a></li>
<li><a href="https://windows11.techidaily.com/curating-edthemes-experience-on-windows-11/"><u>Curating EdThemes Experience on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-windows-11-camera-app-error-0xa00f425d-fixes/"><u>Disabling Windows 11 Camera App Error 0xA00F425D Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-vivetool-your-ticket-to-access-latest-windows-innovations/"><u>Discover ViVeTool: Your Ticket to Access Latest Windows Innovations</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/dragons-echo-leading-places-to-acquire-got-audio-calls/"><u>Dragon's Echo  Leading Places to Acquire GoT Audio Calls</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-integration-portable-software-menus-for-w11plus/"><u>Easy Integration: Portable Software Menus for W11+</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-stable-windows-printer-connections/"><u>Ensuring Stable Windows-Printer Connections</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-your-input-cant-be-opened-vlc-error/"><u>Eradicating 'Your Input Can't Be Opened' VLC Error</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-for-seamlessly-entering-fullscreen-mode/"><u>Expert Advice for Seamlessly Entering Fullscreen Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-monochrome-errors-with-marketplace/"><u>Fixing Monochrome Errors with Marketplace</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-nvidia-setup-not-available-glitch/"><u>Fixing the 'Nvidia Setup Not Available' Glitch</u></a></li>
<li><a href="https://unlock-android.techidaily.com/forgotten-the-voicemail-password-of-itel-p55t-try-these-fixes-by-drfone-android/"><u>Forgotten The Voicemail Password Of Itel P55T? Try These Fixes</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/free-gaming-music-archives-no-restrictions-for-2024/"><u>Free Gaming Music Archives (No Restrictions) for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-oppo-reno-11-pro-5g-mirror-screen-to-pc-drfone-by-drfone-android/"><u>How Oppo Reno 11 Pro 5G Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-bypass-android-lock-screen-using-emergency-call-on-tecno-spark-10-pro-by-drfone-android/"><u>How to Bypass Android Lock Screen Using Emergency Call On Tecno Spark 10 Pro?</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-change-country-on-app-store-for-apple-iphone-xs-max-with-7-methods-by-drfone-ios/"><u>How To Change Country on App Store for Apple iPhone XS Max With 7 Methods</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-the-soft-bricked-realme-c67-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix the Soft Bricked Realme C67 5G? | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-purerecorder-capturing-life-in-games-without-cost/"><u>In 2024, PureRecorder  Capturing Life in Games Without Cost</u></a></li>
<li><a href="https://tech-revival.techidaily.com/leverage-ai-with-chatgpt-for-effective-linkedin-job-hunting-top-tips-included/"><u>Leverage AI with ChatGPT for Effective LinkedIn Job Hunting - Top Tips Included</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/masterful-methods-for-sticker-elimination-in-tiktoks-for-2024/"><u>Masterful Methods for Sticker Elimination in TikToks for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/meeting-prep-101-test-your-windows-webcam-microphone/"><u>Meeting Prep 101: Test Your Windows Webcam, Microphone</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-onedrive-errors-on-windows-11-an-experts-fix-list/"><u>Navigating OneDrive Errors on Windows 11: An Expert's Fix List</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-the-maze-of-windows-error-code-0xc00000f/"><u>Navigating Through the Maze of Windows Error Code 0Xc00000f</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-win-os-extract-issues-saving-time-with-error-1152-solution/"><u>Overcoming Win OS Extract Issues: Saving Time with Error 1152 Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-shift-script-moving-windows-11-selected-files/"><u>Quick Shift Script: Moving Windows 11 Selected Files</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/saying-bonjour-the-elegant-way-to-express-happiness-and-goodwill/"><u>Saying 'Bonjour': The Elegant Way to Express Happiness & Goodwill</u></a></li>
<li><a href="https://windows11.techidaily.com/sound-revolution-for-your-pc-the-essential-guide-to-audio-drivers-updates/"><u>Sound Revolution for Your PC: The Essential Guide to Audio Drivers Updates</u></a></li>
<li><a href="https://os-tips.techidaily.com/step-by-step-guide-setting-up-a-new-gmail-account-on-your-android-smartphone/"><u>Step-by-Step Guide: Setting Up a New Gmail Account on Your Android Smartphone</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-to-become-a-win-11-insider/"><u>Step-by-Step to Become a Win 11 Insider</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-resolving-installation-issues-with-microsoft-store-apps/"><u>Steps for Resolving Installation Issues with Microsoft Store Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-pinpointing-device-serial-numbers-on-windows/"><u>The Ultimate Guide to Pinpointing Device Serial Numbers on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-the-finest-free-car-performance-fixes/"><u>The Ultimate Guide to the Finest Free Car Performance Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/top-6-windows-11-prime-fps-monitors-and-trackers/"><u>Top 6 Windows 11: Prime FPS Monitors & Trackers</u></a></li>
<li><a href="https://windows11.techidaily.com/top-solutions-for-windows-pin-access-issues-10plus11/"><u>Top Solutions for Windows PIN Access Issues (10+11)</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-11-entry-into-the-insider-trials/"><u>Unveiling Windows 11: Entry Into the Insider Trials</u></a></li>
</ul></div>
