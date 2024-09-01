---
title: "Guide: Mastering the Art of Text Trimming in MS Excel"
date: 2024-08-26 12:35:37
updated: 2024-08-29 12:26:28
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/05fdd1e1f79925f7174d27adc0ae3abbe1009fc921370376e92e90f7d158bcf8.jpg
---

## Guide: Mastering the Art of Text Trimming in MS Excel

### Quick Links

* [Truncate Text in Excel with RIGHT or RIGHTB](https://change-location.techidaily.com/in-2024-ways-to-trade-pokemon-go-from-far-away-on-xiaomi-civi-3-drfone-by-drfone-virtual-android/)
* [Truncate Text in Excel with LEFT or LEFTB](https://win-dash.techidaily.com/download-and-install-lenovo-ideapad-100-drivers-for-windows-10-step-by-step-guide/)
* [Truncate Text in Excel with MID or MIDB](https://youtube-web.techidaily.com/ehensive-guide-to-crafting-engaging-youtube-outros/)

 If text is a big part of the data in your spreadsheet, you may need to adjust it to fit properly. The [TRUNC function](https://windows11.techidaily.com/balancing-cpu-and-memory-use-after-news-downloads/) in Microsoft Excel works only with numbers. So if you want to truncate text, here's how.

 There are many useful [functions for working with text](https://video-screen-grab.techidaily.com/updated-the-art-of-smooth-video-transitioning-for-2024/) in Excel. Three of those functions help you truncate text in a cell. These are RIGHT, LEFT, and MID, and each has a variation for using bytes instead of characters.

##  Truncate Text in Excel with RIGHT or RIGHTB

 The RIGHT function uses the [number of characters](https://fox-http.techidaily.com/new-dynamic-shade-adjuster-app-for-2024/) for a single-byte character set (SBCS) while RIGHTB uses a number of bytes for a [double-byte character set (DBCS)](https://en.wikipedia.org/wiki/DBCS). Both functions work the same way with only that difference. So, you can use whichever works best for you.

Related: [How to Count Characters in Microsoft Excel](https://fox-http.techidaily.com/new-dynamic-shade-adjuster-app-for-2024/) 

 The syntaxes are 

        `RIGHT(text, number_characters)`
    
 and 

        `RIGHTB(text, number_bytes)`
    
 with the first argument for each formula required. You can enter the cell reference and keep what's on the right.

 To keep 12 characters on the right from the text string in cell A2, you would use this formula:

=RIGHT(A2,12)

![Keep 12 characters on the right](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/RIGHT12-ExcelTruncateText.png) 

 As another example, we want to keep only the last word and punctuation. This formula retains the last eight characters on the right.

=RIGHT(A2,8)

![Keep eight characters on the right](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/RIGHT8-ExcelTruncateText.png) 

##  Truncate Text in Excel with LEFT or LEFTB

 The LEFT and LEFTB functions work like the RIGHT and RIGHTB functions where you use either the number of characters or bytes respectively. But with these [functions](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/), you're shortening your text string from the opposite side.

Related: [12 Basic Excel Functions Everybody Should Know](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/) 

 The syntaxes are `LEFT(text, number_characters)` and `LEFTB(text, number_bytes)` with the first argument for each formula required. Again, insert the cell reference for the text and keep what's on the left side.

 To keep 32 characters on the left from the text string in cell A2, you would use this formula:

=LEFT(A2,32)

![Keep 32 characters on the left](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/LEFT32-ExcelTruncateText.png) 

 For another example, we want to keep only the first word in the string. This formula retains only the first four characters on the left.

=LEFT(A2,4)

![Keep four characters on the left](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/LEFT4-ExcelTruncateText.png) 

##  Truncate Text in Excel with MID or MIDB

 If the [text that you want to keep](https://youtube-web.techidaily.com/024-approved-ultimate-routine-personalize-your-youtube-shorts-image-credits/) is in the middle of a text string, you'll use the MID or MIDB functions. These functions are like the other two in that you enter a number or characters for MID and number of bytes for MIDB.

Related: [How to Shrink or Expand Cells to Fit Text in Microsoft Excel](https://youtube-web.techidaily.com/024-approved-ultimate-routine-personalize-your-youtube-shorts-image-credits/) 

 The syntaxes are `MID(text, start, number_characters)` and `MIDB(text, start, number_bytes)` with all arguments for each formula required. You can use a cell reference for the first argument, the number of the starting character or byte for the second, and the number to keep for the third.

 Here, we'll remove everything from the string except for a middle portion. With this formula, the text is in cell A2, we want to start with the 35th character, and keep only 24 characters.

=MID(A2,35,24)

![Keep 24 characters in the middle](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/MID35-ExcelTruncateText.png) 

 As another example, using the following formula you can shorten the text in cell A2 and keep only the second word. We use 6 for the `start` argument and 3 for the `number_characters` argument.

=MID(A2,6,3)

![Keep three characters in the middle](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/MID6-ExcelTruncateText.png) 

 Shortening text in your sheet may be necessary or simply something you prefer. These [functions and formulas](https://games-able.techidaily.com/is-premium-play-on-demand-worth-it/) help you truncate text in Excel from the right, left, or middle, as you need it.

Related: [How to Add Text to a Cell With a Formula in Excel](https://buynow-reviews.techidaily.com/a-comprehensive-review-top-long-reach-routers-dominating-the-market-in-ebytes/)

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
