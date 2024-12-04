---
title: Tweaking Taskbar Width in Win11
date: 2024-11-28T17:31:14.934Z
updated: 2024-12-04T04:44:51.655Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tweaking Taskbar Width in Win11
excerpt: This Article Describes Tweaking Taskbar Width in Win11
keywords: Win11 Taskbar Adjustment,Taskbar Resizing Windows 11,Narrowing Windows Bar,Widen Taskbar Control,Set Taskbar Width (Win11),Customize Win11 Bar Size,Modify Window Bar Dimensions
thumbnail: https://thmb.techidaily.com/c88c76635d5e0629581e4fd4108916cee892ed1d438b3013953d19ca906db797.jpg
---

## Tweaking Taskbar Width in Win11

 Ever looked at the Windows 11 Taskbar and thought it looks too small for your liking? Or maybe you feel it could be a little smaller? If that’s the case, you can change its size to suit your needs by making it bigger or smaller.

 Unlike Windows 10, you can’t just unlock the Taskbar and adjust its size freely in Windows 11\. While Microsoft has removed this way of going about it in Windows 11, there is a workaround that you can use, although it’s not as elegant.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Do I Make the Windows 11 Taskbar Bigger or Smaller?

 The only way to change the size of the Taskbar is to use the Registry Editor. However, we advise caution when dealing with the Windows Registry because if something goes wrong, you might experience performance issues on your Windows 11 PC. If you’re unfamiliar with it, we recommend reading our guides on[what the Windows Registry is](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) and[how to not mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/) .

 Once you’re all caught up or are already familiar with the Windows Registry, and you know what you’re doing, you can make the Taskbar bigger or smaller. To do that:

1. Start by pressing**Win + R** to open Windows Run.
2. Type**regedit** in the text box and hit the**Enter** key.
3. Then, click**Yes** on the UAC prompt to launch the Registry Editor.
4. Copy and paste the below text in the address bar of the Registry Editor and hit the**Enter** key:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. In the**Advanced** key, look for a value called**TaskbarSi** . If it’s not there, right-click**Advanced** , select**New > DWORD (32-bit) Value** , and name that value**TaskbarSi.**  
![creating a new dword in the advanced key in the Registry Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/new-dword-advanced-regedit.jpg)
6. Double-click**TaskbarSi** to edit it, and then enter**2** in the**Value data** text box and click**OK** to make the Taskbar bigger.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/w7c5EHp-GDw?si=UTw7lZR0wTmRjp8W" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![changing the taskbarsi value to 2 in the Registry Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/taskbarsi-value-2.jpg)

 Once you restart your computer, you will see the result: an enlarged Taskbar.

![an enlarged Taskbar on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-enlarged-taskbar.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JMgRzDANfSQ?si=NDy01ntXGGOi1Uxs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To make the Taskbar smaller, enter**0** in the**Value data** text box, click**OK** , and then restart your computer. You will then see that the Taskbar has shrunk.

![a smaller taskbar in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-small-taskbar.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0OxkndZbIA4?si=TWJlkTbYKsVag8-q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you decide to go back to the Taskbar’s default size, you can easily set**Value data** to**1** or simply delete the**TaskbarSi** value.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xq2r4ZKM-Po?si=fA2DdEB1op-atCkz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Adjust the Taskbar’s Size to Suit Your Needs on Windows 11

 Even though you can’t make the Taskbar bigger or smaller on Windows 11 as easily as you can on Windows 10, a little know-how can help. And as long as you followed the instructions mentioned above correctly, you shouldn’t worry about messing up the Windows Registry. However, we still recommend that you use this method only if you know what you’re doing.

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
<li><a href="https://article-posts.techidaily.com/new-are-feedbacks-on-items-monetized-in-videos-in-2024/"><u>[New] Are Feedbacks on Items Monetized in Videos, In 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-instavision-blend-androidplusios-video-tiles/"><u>[New] InstaVision Blend Android+iOS Video Tiles</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-action-unleashed-the-latest-in-filmmaking-from-polaroids-xs/"><u>[Updated] Action Unleashed The Latest in Filmmaking From Polaroid's XS</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-effortless-capture-winmac-tools-to-record-desktop-screens/"><u>2024 Approved Effortless Capture Win/Mac Tools to Record Desktop Screens</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-upgrade-your-photo-edits-the-ultimate-guide-to-pixlr-power/"><u>2024 Approved Upgrade Your Photo Edits The Ultimate Guide to Pixlr Power</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-reversing-customized-search-in-windows-11/"><u>Guide to Reversing Customized Search in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-the-license-will-expire-warning-in-win11/"><u>How to Stop the License Will Expire Warning in Win11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-ideal-techniques-for-noiseless-recording/"><u>In 2024, Ideal Techniques for Noiseless Recording</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-retrieve-unseen-razer-devices-on-windows-11/"><u>Methods to Retrieve Unseen Razer Devices on Windows 11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/navigate-through-apples-latest-ipad-software-enhancements-the-ultimate-guide/"><u>Navigate Through Apple's Latest iPad Software Enhancements – The Ultimate Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/priority-accessibility-attach-google-mail-taskbar-ready/"><u>Priority Accessibility: Attach Google Mail Taskbar-Ready</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-steps-to-resolve-steams-internet-connectivity/"><u>Quick Steps to Resolve Steam's Internet Connectivity</u></a></li>
<li><a href="https://windows11.techidaily.com/securely-expanding-windows-volume-no-deletion-compatible/"><u>Securely Expanding Windows Volume, No Deletion Compatible</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-files-back-from-google-pixel-8-by-fonelab-android-recover-data/"><u>Simple ways to get lost files back from Google Pixel 8</u></a></li>
<li><a href="https://fox-that.techidaily.com/why-does-my-iphoneipad-overheat-understanding-causes-and-solutions/"><u>Why Does My iPhone/iPad Overheat? Understanding Causes & Solutions</u></a></li>
</ul></div>

