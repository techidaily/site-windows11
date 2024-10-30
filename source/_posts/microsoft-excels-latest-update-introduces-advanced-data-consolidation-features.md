---
title: Microsoft Excel's Latest Update Introduces Advanced Data Consolidation Features
date: 2024-10-26T16:24:33.942Z
updated: 2024-10-30T16:47:30.491Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/08/microsoft-excel-logo-1.jpg
---

## Microsoft Excel's Latest Update Introduces Advanced Data Consolidation Features

Microsoft Excel now offers GROUPBY and PIVOTBY aggregation functions, which make it easier to collect and organize data into compact summaries or tables. Plus, a new PERCENTOF function allows you to quickly return percentages from raw data. These functions are still in beta and are currently limited to Microsoft 365 Insider builds.

 The [GROUPBY](https://support.microsoft.com/en-us/office/groupby-function-5e08ae8c-6800-4b72-b623-c41773611505) function is extremely simple and requires just three arguments—what to group by, the values that you want to aggregate, and the function that you'd like to use for aggregation. In an example provided by Microsoft, the function **\=GROUPBY(tbl\[Category\],tbl\[Sales\],SUM)** reduces some complicated sales information into a two-column table. The left side of the table lists product categories, while the right side contains sales numbers aggregated by the SUM function.

 Microsoft's demonstration of the GROUPBY function is shown below.

![Using the GROUPBY function in Microsoft Excel to split item sales into product categories with corresponding sales figures.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/1-5.png) 

Microsoft

 Excel's new [PIVOTBY](https://support.microsoft.com/en-us/office/pivotby-function-de86516a-90ad-4ced-8522-3a25fac389cf) function is extremely similar to GROUPBY, but it takes four arguments instead of three. Using the same dataset from the previous example, Microsoft uses the function **\=PIVOTBY(tbl\[Category\],tbl\[Year\],tbl\[Sales,MAX)** to show the largest sales by product category and year. Total sales for each product category are also included.

 Notice the use of the MAX function in this example. GROUPBY and PIVOTBY allow you to select from a list of Excel's lambda functions, which can remove some of the guesswork when aggregating data. Microsoft plans to expand etc lambda support to all functions that support lambda, meaning that some large functions will become more streamlined and legible.

![Using the PIVOTBY function in Microsoft Excel to split item sales into categories, with each year of sales separated into columns.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/2-2.png) 

Microsoft

 The GROUPBY and PIVOTBY functions aren't groundbreaking, but they're simple, tidy, and automatically updated by changes to your data. Also, you can pull some pretty interesting tricks by fooling around with the new functions' full arguments. Microsoft seems especially proud of text aggregation, which can be performed by using the GROUPBY function with the addition of a sorting argument and ARRAYTOTEXT.

 There's also the new PERCENTOF function. Microsoft says that [PERCENTOF](https://support.microsoft.com/en-us/office/percentof-function-7c66da0a-ac30-45d0-bfc7-834a8bd7c962) is "particularly useful" when paired with GROUPBY or PIVOTBY, as it can spit out complex percentage values with relatively few steps. (Technically speaking, PERCENTOF is logically equivalent to **\=SUM(data\_subset)/SUM(data\_all)**.)

 Microsoft Excel's new functions are currently limited to Microsoft 365 Insider builds. Do not use these functions in important spreadsheets, as they are still in beta and may be modified in a stable release.

 Source: [Microsoft](https://insider.microsoft365.com/en-us/blog/new-aggregation-functions-in-excel-groupby-and-pivotby)

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
<li><a href="https://youtube-tips.techidaily.com/ed-master-your-online-presence-the-ultimate-guide-to-effective-freefire-tags-for-2024/"><u>[Updated] Master Your Online Presence The Ultimate Guide to Effective FreeFire Tags for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/4-most-known-ways-to-find-someone-on-tinder-for-vivo-v27-by-name-drfone-by-drfone-virtual-android/"><u>4 Most-Known Ways to Find Someone on Tinder For Vivo V27 by Name | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-overcoming-windows-update-error-8007000e-with-simple-steps/"><u>Expert Advice: Overcoming Window's Update Error '8007000E' With Simple Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-your-teammers-disconnected-screens/"><u>Fix Your Teammers’ Disconnected Screens</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-speed-up-your-windows-11-boot-time/"><u>How to Speed Up Your Windows 11 Boot Time</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-delete-icloud-account-from-apple-iphone-14-plus-without-password-by-drfone-ios/"><u>In 2024, How to Delete iCloud Account From Apple iPhone 14 Plus without Password?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-a-lost-samsung-galaxy-f34-5g-for-free-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track a Lost Samsung Galaxy F34 5G for Free? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-mouse-drivers-for-efficient-windows-use/"><u>Mastering Mouse Drivers for Efficient Windows Use</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-onedrive-files-on-pc-without-internet/"><u>Mastering OneDrive Files on PC without Internet</u></a></li>
<li><a href="https://extra-skills.techidaily.com/prime-10-sticker-adding-tools-for-iphone-and-android-photos-for-2024/"><u>Prime 10 Sticker-Adding Tools for iPhone and Android Photos for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-your-system-mastering-the-art-of-expanded-pins-in-win1011/"><u>Secure Your System: Mastering the Art of Expanded Pins in Win10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-windows-discord-cutting-down-latency-issues/"><u>Speedy Windows Discord: Cutting Down Latency Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-installation-error-with-oculus-on-w11w10/"><u>Tackling Installation Error with Oculus on W11/W10</u></a></li>
<li><a href="https://driver-error.techidaily.com/tackling-windows-11s-irql-crash/"><u>Tackling Windows 11'S IRQL Crash</u></a></li>
<li><a href="https://windows11.techidaily.com/tweaking-taskbar-width-in-win11/"><u>Tweaking Taskbar Width in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-global-communication-navigating-languages-with-shortcuts-on-windows/"><u>Unlock Global Communication: Navigating Languages with Shortcuts on Windows</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ling-the-secrets-how-to-clear-yt-background/"><u>Unveiling the Secrets How to Clear YT Background</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014850/22899" target="_top" id="2014850">
  <img src="//a.impactradius-go.com/display-ad/22899-2014850" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014850/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

