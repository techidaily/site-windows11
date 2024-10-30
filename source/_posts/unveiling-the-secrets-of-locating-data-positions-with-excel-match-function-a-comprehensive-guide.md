---
title: "Unveiling the Secrets of Locating Data Positions with Excel MATCH Function: A Comprehensive Guide"
date: 2024-10-29T16:07:28.525Z
updated: 2024-10-30T16:24:39.478Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/f0ebef61d0b2c8908bbc43dc1da12abaf166bb4f6229b3a45bf569455ab91d1f.jpg
---

## Unveiling the Secrets of Locating Data Positions with Excel MATCH Function: A Comprehensive Guide

### Quick Links

* [What Is the MATCH Function in Excel?](https://android-location-track.techidaily.com/in-2024-how-to-track-a-lost-realme-narzo-60x-5g-for-free-drfone-by-drfone-virtual-android/)
* [Use MATCH in Excel](https://easy-unlock-android.techidaily.com/the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-nokia-c210-device-by-drfone-android/)

 When you need to find a value's exact position in your spreadsheet, you can use the MATCH function in Excel. This saves you from manually searching for the location that you may need [for reference](https://extra-information.techidaily.com/in-2024-chic-coverage-for-your-portable-screen/) or another formula.

 The MATCH function is often used with [the INDEX function](https://youtube-help.techidaily.com/in-2024-the-full-course-on-becoming-a-yt-creator-expert/) as an advanced lookup. But here, we'll walk through how to use MATCH on its own to find a value's spot.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100534/7443" target="_top" id="2100534">
  <img src="//a.impactradius-go.com/display-ad/7443-2100534" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100534/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  What Is the MATCH Function in Excel?

 The MATCH function in Excel [searches](https://win11.techidaily.com/renaissance-pc-refresh-with-atlasos/) for a value in the array, or range of cells, that you specify.

 For instance, you might look up the value 10 in the cell range B2 through B5\. Using MATCH in a formula, the result would be 3 because the value 10 is in the third position of that array.

![Position of a value in a cell range](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/Position-ExcelMATCHFunction.png) 

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2141676/17091" target="_top" id="2141676">
  <img src="//a.impactradius-go.com/display-ad/17091-2141676" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettieu.pxf.io/i/5597632/2141676/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The syntax for the function is 

        `MATCH(value, array, match_type)`
    
 where the first two arguments are required and 

        `match_type`
    
 is optional.

 The match type can be one of the following three options. If the argument is omitted from the formula, 1 is used by default.

* **1**: Finds the largest value less than or equal to the searched  
        `value`  
      
 . The range must be in ascending order.
* **0**: Finds the value exactly equal to the searched  
        `value`  
      
 and the range can be in any order.
* **\-1**: Finds the smallest value greater than or equal to the searched  
        `value`  
      
 . The range must be in descending order.

 You may also see these match types as a tooltip when you build your formula in Excel.

![Match type tool tip in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/MatchTypes-ExcelMATCHFunction.png) 

 The MATCH function is not case sensitive, allows the wildcards asterisk (\*) and question mark (?), and returns #N/A as the [error](https://instagram-videos.techidaily.com/updated-cut-and-paste-success-enhancing-videos-for-instagram-shares/) if no match is found.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043593/7443" target="_top" id="2043593">
  <img src="//a.impactradius-go.com/display-ad/7443-2043593" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043593/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Use MATCH in Excel

 When you're ready to put the MATCH function to work, take a look at these examples to help you walk through [building the formula](https://extra-resources.techidaily.com/2024-approved-crafting-visuals-in-ae-selecting-excellent-plugin-choices/).

 Using our example above, you would use this formula to find the value 10 in the range B2 through B5\. Again, our result is 3 representing the third position in the cell range.

=MATCH(10,B2:B5)

![MATCH used to look up a value's position](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/Match10-ExcelMATCHFunction.png) 

 For another example, we'll include the match type 1 at the end of our formula. Remember, match type 1 requires the array be in ascending order.

=MATCH(10,B2:B5,1)

 The result is 4 which is the position of the number 9 in our range. That's the highest value less than or equal to 10.

![MATCH with match type 1](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/MatchType1-ExcelMATCHFunction.png) 

 Here's an example using match type 0 for an exact match. As you can see, we receive the #N/A error because there is no exact match to our value.

=MATCH(10,B2:B5,0)

![MATCH with match type 0](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/MatchType0-ExcelMATCHFunction.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925489/19272" target="_top" id="1925489">
  <img src="//a.impactradius-go.com/display-ad/19272-1925489" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925489/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Let's use the final match type -1 in this formula.

=MATCH(10,B2:B5,-1)

 The result is 2 which is the position of the number 11 in our range. That's the lowest value greater than or equal to 10\. Again, match type -1 requires the array be in descending order.

![MATCH with match type -1](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/MatchType-1-ExcelMATCHFunction.png) 

 For an example using text, here we can find Caps in the cell range A2 through A5\. The result is 1 which is the first position in our array.

=MATCH("Caps",A2:A5)

![MATCH for finding text in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/MatchText-ExcelMATCHFunction.png) 

 Now that you know the basics of using the MATCH function in Excel, you might also be interested in learning about using [XLOOKUP in Excel](https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-asus-rog-phone-7-ultimate-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/) or using [VLOOKUP for a range of values](https://win-able.techidaily.com/1723001670706-troubleshooting-genshin-impact-fix-stability-issues-and-stop-pc-crashes/).

| |  Mastering Excel Functions |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |  |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |  |
| Functions                    | [AVERAGE](https://win-able.techidaily.com/fixing-overwatch-startup-issues-how-to-get-rid-of-the-persistent-black-screen/) **·** [CONCATENATE](https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-xiaomi-redmi-13c-5g-drfone-by-drfone-virtual-android/) **·** [COUNT](https://android-location-track.techidaily.com/how-to-track-a-lost-xiaomi-redmi-note-12t-pro-for-free-drfone-by-drfone-virtual-android/) **·** [COUNTIF](https://win-forum.techidaily.com/complete-tutorial-clearing-out-windows-10-memory-dump-data/) **·** [DATEDIF](https://youtube-data.techidaily.com/n-2024-explore-the-best-historian-content-top-10-youtube-recommendations/) **·** [FILTER](https://youtube-sure.techidaily.com/024-approved-the-ultimate-guide-to-youtube-live-streaming/) **·** [FREQUENCY](https://digital-screen-recording.techidaily.com/new-ideal-low-impact-recording-devices-for-eco-conscious-filmmakers/) **·** [FV](https://on-screen-recording.techidaily.com/updated-2024-approved-enhancing-gaming-experience-with-steam-switch-control/) **·** [HYPERLINK](https://some-guidance.techidaily.com/updated-the-minimalists-guide-to-aerial-imagery-with-dji-spark/) **·** [IF](https://android-unlock.techidaily.com/in-2024-how-to-use-google-assistant-on-your-lock-screen-of-huawei-phone-by-drfone-android/) **·** [IFS](https://screen-recording.techidaily.com/updated-ultimate-techniques-for-precise-iptv-screen-imaging/) **·** [IMAGE](https://screen-mirror.techidaily.com/top-10-airplay-apps-in-xiaomi-redmi-note-12-5g-for-streaming-drfone-by-drfone-android/) **·** [INDEX](https://youtube-help.techidaily.com/in-2024-the-full-course-on-becoming-a-yt-creator-expert/) **·** [IS](https://win-amazing.techidaily.com/new-release-gtx-1650-super-driver-updates-compatible-with-windows-11/) **·** [LEN](https://extra-hints.techidaily.com/scalable-and-stylish-type-in-ae-with-top-choices/) **·** [MATCH](https://extra-guidance.techidaily.com/mirthful-missions-delving-into-the-goofy-movie-vhs-for-2024/) **·**[MEDIAN](https://some-techniques.techidaily.com/in-2024-from-novice-to-expert-the-complete-powerdirector-journey/) **·** [RAND](https://instagram-video-recordings.techidaily.com/updated-master-igtv-edits-top-10-tools-ranked/) **·** [ROUND](https://youtube-zero.techidaily.com/ed-2024-approved-the-quick-pathway-to-establishing-a-video-channel-on-your-phone/) **·** [RRI](https://vp-tips.techidaily.com/2024-approved-quick-cash-on-reddit-here-are-13-ways-for-new-users/) **·** [SORT](https://some-techniques.techidaily.com/2024-approved-gopro-versus-polaroid-editing-faces-vs-cameras-that-shoot-them/) **·** [SQRT](https://screen-video-capture.techidaily.com/in-2024-master-guide-ultimate-tips-for-maximizing-mobizens-screen-capture/) **·** [SUBSTITUTE](https://screen-sharing-recording.techidaily.com/updated-maiden-shoot-revelations-and-critique-for-2024/) **·** [SUBTOTAL](https://phone-solutions.techidaily.com/in-2024-prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-oppo-a78-5g-drfone-by-drfone-virtual-android/) **·** [SUM](https://instagram-videos.techidaily.com/updated-steps-to-instagram-verification-and-fan-growth-in-under-150-characters/) **·** [SUMIF](https://on-screen-recording.techidaily.com/pinnacle-platforms-transforming-online-interaction/) **·** [TODAY](https://some-guidance.techidaily.com/2024-approved-unlock-spark-ars-full-potential-with-personalized-lut-implementations/) **·** [TRIM](https://graphic-issues.techidaily.com/regaining-access-to-nvidia-writable-displays/) **·** [TRUNC](https://windows11.techidaily.com/balancing-cpu-and-memory-use-after-news-downloads/) **·** [VLOOKUP](https://extra-tips.techidaily.com/integrate-sound-and-sight-web-studio/) **·** [WEEKDAY](https://youtube-tips.techidaily.com/n-2024-virtual-voyage-youtubes-premier-10-vr-video-experience/) **·** [XLOOKUP](https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-asus-rog-phone-7-ultimate-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/) **·** [YEAR](https://facebook-record-videos.techidaily.com/updated-in-2024-captivating-content-the-basics-of-removing-background-from-videos/) |  |
| Types                        | [Basic](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/) **·** [Budgeting](https://easy-unlock-android.techidaily.com/in-2024-how-to-reset-a-realme-narzo-60-pro-5g-phone-that-is-locked-by-drfone-android/) **·** [Data Entry](https://vimeo-videos.techidaily.com/in-2024-high-end-downloads-best-10-apps-for-extracting-vimeo-videos/) **·** [Logical](https://extra-skills.techidaily.com/in-2024-spark-engagement-the-ultimate-list-of-video-text-effects/) **·** [Text](https://video-screen-grab.techidaily.com/updated-the-art-of-smooth-video-transitioning-for-2024/) **·** [Time and Date](https://extra-lessons.techidaily.com/kickstart-your-telegram-promotion-journey-tips-for-newbies/)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |  |
| Explained                    | [Copying Formulas](https://extra-tips.techidaily.com/in-2024-converting-personal-memories-from-stillness-to-motion/) **·** [Evaluating Formulas](https://youtube-blog.techidaily.com/ed-the-role-of-youtube-images-in-video-promotion-and-discovery-for-2024/) **·** [Finding Functions](https://win11.techidaily.com/renaissance-pc-refresh-with-atlasos/) **·** [Fixing Formula Errors](https://extra-lessons.techidaily.com/step-into-premium-sound-quality-garageband-edition/) **·** [Functions vs Formulas](https://games-able.techidaily.com/is-premium-play-on-demand-worth-it/) **·** [Comparing Lookup Functions](https://tech-revival.techidaily.com/examining-codegpts-capabilities-in-tech-innovation/) **·** [Locking Formulas](https://some-guidance.techidaily.com/in-2024-unveiling-effective-sales-methods/) **·** [Structuring Formulas](https://youtube-docs.techidaily.com/n-2024-automate-playlist-retrieval-from-youtube-directly/) **·** [Translating Formulas](https://extra-tips.techidaily.com/techniques-to-reduce-nausea-while-in-vr/)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |  |

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
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-delving-into-the-chronology-of-windows-movie-maker-editions/"><u>[New] 2024 Approved Delving Into the Chronology of Windows Movie Maker Editions</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-creating-compelling-solo-videos-on-a-budget/"><u>[Updated] 2024 Approved Creating Compelling Solo Videos on a Budget</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-in-2024-premiere-visionary-film-glimpses/"><u>[Updated] In 2024, Premiere Visionary Film Glimpses</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-modern-techniques-record-idevice-screen-effortlessly-for-2024/"><u>[Updated] Modern Techniques Record iDevice Screen Effortlessly for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-boosting-video-management-creating-an-effective-youtube-watch-later-list/"><u>2024 Approved Boosting Video Management Creating an Effective YouTube Watch Later List</u></a></li>
<li><a href="https://blog-min.techidaily.com/dvdbd-makemkv/"><u>地デジ DVD/BD コピー変換手順：MAKEMKVで簡単に</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-quickly-accessdeactivate-bing-chat-in-windows-search-bar/"><u>How To Quickly Access/Deactivate Bing Chat in Windows Search Bar</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-hidefake-snapchat-location-on-your-honor-x8b-drfone-by-drfone-virtual-android/"><u>In 2024, How to Hide/Fake Snapchat Location on Your Honor X8b | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/integrate-and-upgrade-the-best-6-android-apps-on-windows-11/"><u>Integrate and Upgrade: The Best 6 Android Apps on Windows 11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/inverting-media-flow-apple-device-technique-for-2024/"><u>Inverting Media Flow Apple Device Technique for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-win-11s-capabilities-for-seamless-application-switch/"><u>Leveraging Win 11'S Capabilities for Seamless Application Switch</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-desktop-organization-notes-on-w11w10/"><u>Mastering Desktop Organization: Notes on W11/W10</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/precision-speed-control-for-elite-pc-users-for-2024/"><u>Precision Speed Control for Elite PC Users for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/rebooting-trust-how-to-rectify-windows-safety-setbacks/"><u>Rebooting Trust: How to Rectify Windows Safety Setbacks</u></a></li>
<li><a href="https://windows11.techidaily.com/rog-ally-and-the-new-competitor-from-asus/"><u>ROG Ally and the New Competitor From ASUS</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-image-access-via-file-explorer-in-windows-11/"><u>Streamline Image Access via File Explorer in Windows 11</u></a></li>
<li><a href="https://win-dash.techidaily.com/streamline-your-media-library-mastering-the-art-of-youtube-to-mp44k-downloads-with-leading-online-and-desktop-converters/"><u>Streamline Your Media Library: Mastering the Art of YouTube to MP4/4K Downloads with Leading Online and Desktop Converters</u></a></li>
<li><a href="https://windows11.techidaily.com/trimming-startup-latency-adjust-boot-menu-delay-in-win11/"><u>Trimming Startup Latency: Adjust Boot Menu Delay in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-the-screen-shot-game-snipping-tool-or-printscreen/"><u>Winning the Screen Shot Game: Snipping Tool or Printscreen?</u></a></li>
</ul></div>

