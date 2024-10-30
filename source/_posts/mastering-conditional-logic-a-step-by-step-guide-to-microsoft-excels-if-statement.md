---
title: "Mastering Conditional Logic: A Step-by-Step Guide to Microsoft Excel's IF Statement"
date: 2024-10-25T16:26:49.471Z
updated: 2024-10-30T16:16:05.392Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/1c29d979a20696d19bd8c5c3e9d947157133fd882c32bc816c08287c2bc4feb3.jpg
---

## Mastering Conditional Logic: A Step-by-Step Guide to Microsoft Excel's IF Statement

### Quick Links

* [What Can You Do with Excel's IF Function?](https://extra-lessons.techidaily.com/high-definition-audio-essentials-the-top-6-mics-for-livestreaming/)
* [How to Write an IF Statement in Excel](https://ai-vdieo-software.techidaily.com/new-best-split-screen-video-apps-for-ios-and-android/)
* [Use the Nested IF Function in Excel](https://article-files.techidaily.com/25-top-rated-gratis-online-photography-tools-for-2024/)

### Key Takeaways

 The IF function returns different values depending on whether a condition is true or false. Use it in the form =IF(Condition,True,False). For example, =IF(C2>=60,"Pass","Fail") will return "Pass" if the value in C2 is equal to or over 60 and "Fail" if the value is under 60.

 Whether you're grading exams or simply trying to make sense of a spreadsheet full of data, Microsoft Excel's `IF` function can help. You can also use an `IF` function inside of another `IF` function to run deeper tests, too. We'll show you how.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948876/19272" target="_top" id="1948876">
  <img src="//a.impactradius-go.com/display-ad/19272-1948876" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948876/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  What Can You Do with Excel's IF Function?

 Put simply, you can use the `IF` function to retrieve a pre-specified result based on whether the function gets a TRUE or FALSE value.

 For example, if you have a score sheet, you can make it so your cells say

        `PASS`
    
 if someone has scored 60 or higher, or say

        `FAIL`
    
 if the score is 59 or lower. You can use a nested `IF` to even assign grades, like an

        `A`
    
 for someone with a score of 90 or higher.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1521325/16446" target="_top" id="1521325">
  <img src="//a.impactradius-go.com/display-ad/16446-1521325" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1521325/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  How to Write an IF Statement in Excel

 To write an `IF` statement in Excel, all you have to do is type the function and specify [what results to retrieve when the condition](https://instagram-clips.techidaily.com/how-to-share-igtv-videos-to-facebook-3-ways-for-2024/) is TRUE and FALSE.

Related: [How to Use Conditional Formatting to Find Duplicate Data in Excel](https://instagram-clips.techidaily.com/how-to-share-igtv-videos-to-facebook-3-ways-for-2024/) 

 Start by launching your spreadsheet with Microsoft Excel. Then, click the cell in which you want to use the function.

 In the following example, we'll use the `IF` function to say

        `Pass`
    
 if the obtained score is 60 or higher and

        `Fail`
    
 if the score is 59 or lower.

 We'll select the D2 cell where we want to display the result.

![Choose a cell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/1-choose-cell-if-function.png) 

 In the D2 cell, we'll enter the following function and press Enter.

=IF(C2>=60,"Pass","Fail")

 In the selected cell, you'll see the result depending on the value in the C2 cell.

![Result of Excel's IF function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/2-if-function-result-1.png) 

 To copy the function for all your records, from the bottom-right corner of the D2 cell, drag downwards to cover all your records.

![Result of Excel's IF function for all records.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/3-if-function-result-all-records.png) 

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137225/26400" target="_top" id="2137225">
  <img src="//a.impactradius-go.com/display-ad/26400-2137225" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137225/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 And that's it.

 Modify the `IF` function in whatever way you want and you'll get the desired result.

##  Use the Nested IF Function in Excel

 A nested `IF` is an `IF` function inside of another `IF` function. You use this when you want to run another logical test after the first one.

 We'll use the following dataset to demonstrate this function:

![Dataset for Excel's nested IF function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/4-dataset-for-excel-nested-if-function.png) 

 In this dataset, depending on the scores, the following results will be displayed:

* If the score is 90 or higher: **A**
* If the score is between 80 and 89: **B**
* If the score is between 70 and 79: **C**
* If the score is between 60 and 69: **D**
* If the score is between 0 and 59: **F**

 We'll select the D2 cell where we want to display the result, and then enter the following nested `IF` function and press Enter:

=IF(C2>=90,"A",IF(C2>=80,"B",IF(C2>=70,"C",IF(C2>=60,"D",IF(C2>=0,"F")))))

 You'll see the result in your selected cell.

![Result of Excel's nested IF function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/5-nested-if-function-result-1.png) 

 You can copy the function for all your records by dragging downwards from the D2 cell's bottom-right corner.

![Result of Excel's nested IF function for all records.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/6-nested-if-function-result-all-records.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049379/7443" target="_top" id="2049379">
  <img src="//a.impactradius-go.com/display-ad/7443-2049379" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049379/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 And you're set.

 Excel's `IF` function is an excellent way to run various logical tests. You can use it to specify multiple conditions and display the results accordingly.

 While you're at it, check out other [Excel logical functions](https://extra-skills.techidaily.com/in-2024-spark-engagement-the-ultimate-list-of-video-text-effects/) that can be useful in your work.

| |  Mastering Excel Functions |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |  |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |  |
| Functions                    | [AVERAGE](https://win-able.techidaily.com/fixing-overwatch-startup-issues-how-to-get-rid-of-the-persistent-black-screen/) **·** [CONCATENATE](https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-xiaomi-redmi-13c-5g-drfone-by-drfone-virtual-android/) **·** [COUNT](https://android-location-track.techidaily.com/how-to-track-a-lost-xiaomi-redmi-note-12t-pro-for-free-drfone-by-drfone-virtual-android/) **·** [COUNTIF](https://win-forum.techidaily.com/complete-tutorial-clearing-out-windows-10-memory-dump-data/) **·** [DATEDIF](https://youtube-data.techidaily.com/n-2024-explore-the-best-historian-content-top-10-youtube-recommendations/) **·** [FILTER](https://youtube-sure.techidaily.com/024-approved-the-ultimate-guide-to-youtube-live-streaming/) **·** [FREQUENCY](https://digital-screen-recording.techidaily.com/new-ideal-low-impact-recording-devices-for-eco-conscious-filmmakers/) **·** [FV](https://on-screen-recording.techidaily.com/updated-2024-approved-enhancing-gaming-experience-with-steam-switch-control/) **·** [HYPERLINK](https://some-guidance.techidaily.com/updated-the-minimalists-guide-to-aerial-imagery-with-dji-spark/) **·** [IF](https://android-unlock.techidaily.com/in-2024-how-to-use-google-assistant-on-your-lock-screen-of-huawei-phone-by-drfone-android/) **·** [IFS](https://screen-recording.techidaily.com/updated-ultimate-techniques-for-precise-iptv-screen-imaging/) **·** [IMAGE](https://screen-mirror.techidaily.com/top-10-airplay-apps-in-xiaomi-redmi-note-12-5g-for-streaming-drfone-by-drfone-android/) **·** [INDEX](https://youtube-help.techidaily.com/in-2024-the-full-course-on-becoming-a-yt-creator-expert/) **·** [IS](https://win-amazing.techidaily.com/new-release-gtx-1650-super-driver-updates-compatible-with-windows-11/) **·** [LEN](https://extra-hints.techidaily.com/scalable-and-stylish-type-in-ae-with-top-choices/) **·** [MATCH](https://extra-guidance.techidaily.com/mirthful-missions-delving-into-the-goofy-movie-vhs-for-2024/) **·** [MEDIAN](https://some-techniques.techidaily.com/in-2024-from-novice-to-expert-the-complete-powerdirector-journey/) **·** [RAND](https://instagram-video-recordings.techidaily.com/updated-master-igtv-edits-top-10-tools-ranked/) **·** [ROUND](https://youtube-zero.techidaily.com/ed-2024-approved-the-quick-pathway-to-establishing-a-video-channel-on-your-phone/) **·** [RRI](https://vp-tips.techidaily.com/2024-approved-quick-cash-on-reddit-here-are-13-ways-for-new-users/) **·** [SORT](https://some-techniques.techidaily.com/2024-approved-gopro-versus-polaroid-editing-faces-vs-cameras-that-shoot-them/) **·** [SQRT](https://screen-video-capture.techidaily.com/in-2024-master-guide-ultimate-tips-for-maximizing-mobizens-screen-capture/) **·** [SUBSTITUTE](https://screen-sharing-recording.techidaily.com/updated-maiden-shoot-revelations-and-critique-for-2024/) **·** [SUBTOTAL](https://phone-solutions.techidaily.com/in-2024-prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-oppo-a78-5g-drfone-by-drfone-virtual-android/) **·** [SUM](https://instagram-videos.techidaily.com/updated-steps-to-instagram-verification-and-fan-growth-in-under-150-characters/) **·** [SUMIF](https://on-screen-recording.techidaily.com/pinnacle-platforms-transforming-online-interaction/) **·** [TODAY](https://some-guidance.techidaily.com/2024-approved-unlock-spark-ars-full-potential-with-personalized-lut-implementations/) **·** [TRIM](https://graphic-issues.techidaily.com/regaining-access-to-nvidia-writable-displays/) **·** [TRUNC](https://windows11.techidaily.com/balancing-cpu-and-memory-use-after-news-downloads/) **·** [VLOOKUP](https://extra-tips.techidaily.com/integrate-sound-and-sight-web-studio/) **·** [WEEKDAY](https://youtube-tips.techidaily.com/n-2024-virtual-voyage-youtubes-premier-10-vr-video-experience/) **·** [XLOOKUP](https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-asus-rog-phone-7-ultimate-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/) **·** [YEAR](https://facebook-record-videos.techidaily.com/updated-in-2024-captivating-content-the-basics-of-removing-background-from-videos/) |  |
| Types                        | [Basic](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/) **·** [Budgeting](https://easy-unlock-android.techidaily.com/in-2024-how-to-reset-a-realme-narzo-60-pro-5g-phone-that-is-locked-by-drfone-android/) **·** [Data Entry](https://vimeo-videos.techidaily.com/in-2024-high-end-downloads-best-10-apps-for-extracting-vimeo-videos/) **·** [Logical](https://extra-skills.techidaily.com/in-2024-spark-engagement-the-ultimate-list-of-video-text-effects/) **·** [Text](https://video-screen-grab.techidaily.com/updated-the-art-of-smooth-video-transitioning-for-2024/) **·** [Time and Date](https://extra-lessons.techidaily.com/kickstart-your-telegram-promotion-journey-tips-for-newbies/)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |  |
| Explained                    | [Copying Formulas](https://extra-tips.techidaily.com/in-2024-converting-personal-memories-from-stillness-to-motion/) **·** [Evaluating Formulas](https://youtube-blog.techidaily.com/ed-the-role-of-youtube-images-in-video-promotion-and-discovery-for-2024/) **·** [Finding Functions](https://win11.techidaily.com/renaissance-pc-refresh-with-atlasos/) **·** [Fixing Formula Errors](https://extra-lessons.techidaily.com/step-into-premium-sound-quality-garageband-edition/) **·** [Functions vs Formulas](https://games-able.techidaily.com/is-premium-play-on-demand-worth-it/) **·** [Comparing Lookup Functions](https://tech-revival.techidaily.com/examining-codegpts-capabilities-in-tech-innovation/) **·** [Locking Formulas](https://some-guidance.techidaily.com/in-2024-unveiling-effective-sales-methods/) **·** [Structuring Formulas](https://youtube-docs.techidaily.com/n-2024-automate-playlist-retrieval-from-youtube-directly/) **·** [Translating Formulas](https://extra-tips.techidaily.com/techniques-to-reduce-nausea-while-in-vr/)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |  |

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
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-beat-bloggers-base-downloads-for-analysis/"><u>[Updated] 2024 Approved Beat Bloggers' Base Downloads for Analysis</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-master-screen-record-on-win-10/"><u>[Updated] In 2024, Master Screen Record on Win 10</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-explore-the-best-ai-naming-software-for-podcasters/"><u>2024 Approved Explore the Best AI Naming Software for Podcasters</u></a></li>
<li><a href="https://win-dash.techidaily.com/1726028502207-hdr/"><u>高画質HDR動画を適切に再生し、問題解決法</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/a-step-by-step-approach-to-macos-sierra-integration/"><u>A Step-by-Step Approach to macOS Sierra Integration</u></a></li>
<li><a href="https://buynow-info.techidaily.com/defining-tablet-leadership-the-apple-ipad-pro-11-2018-edition-in-focus/"><u>Defining Tablet Leadership: The Apple iPad Pro 11 (2018 Edition) in Focus</u></a></li>
<li><a href="https://sound-issues.techidaily.com/fixing-the-silent-issue-windows-media-player-volume-not-working/"><u>Fixing the Silent Issue: Windows Media Player Volume Not Working</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722978322419-get-your-m-audio-fast-track-driver-for-windows-11-7-8-and-81-today/"><u>Get Your M-Audio Fast Track Driver for Windows 11, 7, 8 and 8.1 Today</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-flash-dead-oppo-a1x-5g-safely-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Flash Dead Oppo A1x 5G Safely | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-return-to-original-windows-setup-settings/"><u>How to Return to Original Windows Setup Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/improving-system-performance-by-curbing-browser-activity/"><u>Improving System Performance by Curbing Browser Activity</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-your-contacts-after-honor-play-40c-has-been-deleted-by-fonelab-android-recover-contacts/"><u>Recover your contacts after Honor Play 40C has been deleted.</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-update-breakdown-overcoming-error-0x80246007-on-win11/"><u>Resolving Update Breakdown: Overcoming Error 0X80246007 on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/success-tips-reviving-your-intel-unison-app/"><u>Success Tips: Reviving Your Intel Unison App</u></a></li>
<li><a href="https://windows11.techidaily.com/turbo-type-tips-quick-key-input-enhancements-for-win-1011/"><u>Turbo-Type Tips: Quick Key Input Enhancements for Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-5ghz-wi-fi-connection-woes-how-to-solve-them/"><u>Win11 5GHz Wi-Fi Connection Woes: How to Solve Them</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-widgets-configuration-the-triad-approach/"><u>Windows 11 Widgets Configuration: The Triad Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-woos-resolve-opera-download-hitch/"><u>Windows Woos: Resolve Opera Download Hitch</u></a></li>
<li><a href="https://windows11.techidaily.com/winfix-guide-reviving-dormant-wsreset-service-process/"><u>Winfix Guide: Reviving Dormant WSReset Service Process</u></a></li>
</ul></div>

