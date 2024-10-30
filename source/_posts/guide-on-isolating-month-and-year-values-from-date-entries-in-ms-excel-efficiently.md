---
title: Guide on Isolating Month and Year Values From Date Entries in MS Excel Efficiently
date: 2024-10-26T16:50:54.259Z
updated: 2024-10-30T16:44:28.810Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/calendar-pins-office.jpg
---

## Guide on Isolating Month and Year Values From Date Entries in MS Excel Efficiently

### Quick Links

* [Get the Month or Year With Date Functions](https://youtube-help.techidaily.com/2024-approved-global-gross-earnings-of-youtube-luminaries/)
* [Get the Month or Year With the TEXT Function](https://extra-tips.techidaily.com/new-blending-binaries-digital-photographic-techniques/)

 Dates in Microsoft Excel are useful for tracking finances, orders, and sales. So, there may come a time when you want to pull a month or year out of a date entry. [Functions and formulas](https://games-able.techidaily.com/is-premium-play-on-demand-worth-it/) make this an easy task.

 There are a couple of ways to get a month from a [date in Excel](https://video-capture.techidaily.com/new-from-playback-to-printout-top-five-methods-of-documenting-minecraft-on-a-mac-for-2024/), depending on if you want to display the result as a number, word, or abbreviation. And luckily, you can use these same methods to get the year from your date entry.

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1557742/17382" target="_top" id="1557742">
  <img src="//a.impactradius-go.com/display-ad/17382-1557742" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1557742/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Get the Month or Year With Date Functions

 If you want to get the numeric value for a month such as 10 for October, 11 for November, and so on, the MONTH function gets the job done quickly. For years, you can simply use the [YEAR function](https://tech-revival.techidaily.com/integrate-bing-ai-into-your-android-phone-tips-and-tricks-for-seamless-communication/) and a reference.

 The syntax for each function is the same: 

        `MONTH(reference)`
    
 and 

        `YEAR(reference)`
    
 where you refer to the cell containing the date.

 You can use the following formulas to get the month and then the year from the date in cell A2:

=MONTH(A2)

=YEAR(A2)

 You'll then see the result in the cell containing the formula.

![YEAR function to obtain the year from a date](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/FullYear-ExcelMonthYearFromDate.png) 

 Remember, the month is formatted as its numeric value.

![MONTH function to obtain the month from a date](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/MonthNumber-ExcelMonthYearFromDate.png) 

 If you have a list of dates where you want to grab the month and/or year for each entry, use the fill handle to drag the formula(s) down to the remaining cells.

![Copy formula to cells using the fill handle](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/CopyFullFormulas-ExcelMonthYearFromDate.png) 

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148646/16836" target="_top" id="2148646">
  <img src="//a.impactradius-go.com/display-ad/16836-2148646" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148646/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111982/7443" target="_top" id="2111982">
  <img src="//a.impactradius-go.com/display-ad/7443-2111982" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111982/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Get the Month or Year With the TEXT Function

 Maybe you prefer to see the name of the month or an abbreviation rather than the number. You can do this for the month using the [TEXT function](https://youtube-tips.techidaily.com/n-2024-virtual-voyage-youtubes-premier-10-vr-video-experience/). You can also get the two-digit number for the year with this method.

Related: [How to Find the Day of the Week From a Date in Microsoft Excel](https://youtube-tips.techidaily.com/n-2024-virtual-voyage-youtubes-premier-10-vr-video-experience/) 

 The syntax for the function is `TEXT(value, format_code)` where you'll need both arguments to display the month. The `value` is the cell containing the date and the `format_code` is how you want to display the result.

 Here, we'll get the month for the date in cell A2 as a full word using the letter M for month as the `format_code`:

=TEXT(A2,"mmmm")

 Note, you need at least four M's within quotation marks to get the full month name. The number of letters in the month's name does not correspond to the number of M's in the argument; just enter at least four of them.

![Full month name using the TEXT function](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/FullMonth-ExcelMonthYearFromDate.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094418/7443" target="_top" id="2094418">
  <img src="//a.impactradius-go.com/display-ad/7443-2094418" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094418/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To get the three-letter abbreviation for a month instead of the full name, just use three M's:

=TEXT(A3,"mmm")

![Abbreviation for month name using the TEXT function](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/ShortMonth-ExcelMonthYearFromDate.png) 

 You can also use the TEXT function if you only want two digits for the year rather than all four. You'll use the letter Y for year as the `format_code`:

=TEXT(A2,"yy")

![Two digits for the year using the TEXT function](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/ShortYear-ExcelMonthYearFromDate.png) 

 Again, you can use the fill handle to [copy the formula(s)](https://extra-tips.techidaily.com/in-2024-converting-personal-memories-from-stillness-to-motion/) down to your remaining cells if you like.

![Copied formulas to cells using the fill handle](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/07/CopyShortFormulas-ExcelMonthYearFromDate.png) 

 Pulling a month or year out of a full date in Excel takes only a minute with these methods. For more, check out these additional [date and time functions in Excel](https://extra-lessons.techidaily.com/kickstart-your-telegram-promotion-journey-tips-for-newbies/) you might find useful.

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
<li><a href="https://screen-sharing-recording.techidaily.com/new-from-novice-to-proficient-the-path-with-zoom-webinars/"><u>[New] From Novice to Proficient The Path with Zoom Webinars</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-2024-approved-deep-dives-closer-scans-and-enhanced-gameplay-on-roblox/"><u>[Updated] 2024 Approved Deep Dives Closer Scans and Enhanced Gameplay on Roblox</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-depth-guide-to-uploading-lengthier-content-on-youtube/"><u>[Updated] In-Depth Guide to Uploading Lengthier Content on YouTube</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-maximizing-your-marketing-mettle-on-youtube/"><u>[Updated] Maximizing Your Marketing Mettle on Youtube</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-steps-to-create-makeup-videos/"><u>2024 Approved Steps to Create Makeup Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-ais-weak-spot-the-art-of-prompt-injection/"><u>Delving Into AI's Weak Spot: The Art of Prompt Injection</u></a></li>
<li><a href="https://win-data.techidaily.com/discover-how-to-locate-deleted-items-in-windows-10-top-8-strategies/"><u>Discover How to Locate Deleted Items in Windows 10 - Top 8 Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-chrome-saving-images-in-webp-format-on-windows/"><u>How to Stop Chrome Saving Images in WebP Format on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-fixes-for-the-add-your-folder-now-issue-on-windows-onedrive-drive/"><u>Immediate Fixes for the 'Add Your Folder Now' Issue on Windows OneDrive Drive</u></a></li>
<li><a href="https://windows11.techidaily.com/implementing-python-on-windows-for-optimized-file-transfer/"><u>Implementing PYTHON on Windows for Optimized File Transfer</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-change-your-sim-pin-code-on-your-tecno-camon-20-premier-5g-phone-by-drfone-android/"><u>In 2024, How To Change Your SIM PIN Code on Your Tecno Camon 20 Premier 5G Phone</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/nd-android-youtube-autoplay-tricks-for-2024/"><u>IOS & Android YouTube AutoPlay Tricks for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-high-speed-game-updates-in-battlenet/"><u>Mastering High-Speed Game Updates in Battle.net</u></a></li>
<li><a href="https://windows11.techidaily.com/mitigating-isdonedll-isarcextract-crashes-on-w10w11/"><u>Mitigating ISDone.dll (ISArcExtract) Crashes on W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-guide-to-disabling-restrictions-and-opening-hidden-outlook-directories/"><u>Stepwise Guide to Disabling Restrictions & Opening Hidden Outlook Directories</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-noobs-manual-to-saving-streaming-radio-lines/"><u>The Noob's Manual to Saving Streaming Radio Lines</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-vm-potential-in-windows-through-these-techniques/"><u>Unleash VM Potential in Windows Through These Techniques</u></a></li>
</ul></div>

