---
title: "Exploring the Versatility of Hyperlink in Excel: 6 Essential Applications"
date: 2024-08-28 13:32:37
updated: 2024-08-29 11:37:17
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/109f8e41f016b710f8a0ad598776af950e5e0ec716fb01a083b32b51c83dd241.jpg
---

## Exploring the Versatility of Hyperlink in Excel: 6 Essential Applications

### Quick Links

* [What Is the HYPERLINK Function?](https://data-wizards.techidaily.com/how-to-repair-corrupt-mov-mp4-avi-mkv-and-other-video-files-on-windows-and-mac-os/)
* [Link to a Cell in the Spreadsheet](https://some-guidance.techidaily.com/2024-approved-undo-motion-recapturing-video-from-mobile-devices/)
* [Link to a Cell Within the Workbook](https://video-ai-editor.techidaily.com/new-best-watermark-free-video-joiners-for-seamless-edits/)
* [Link to a Defined Name](https://article-helps.techidaily.com/a-guide-to-excellent-live-cricket-online-watch-for-2024/)
* [Link to a Workbook on Another Drive](https://fox-hovers.techidaily.com/updated-2024-approved-easy-entry-into-cinematography-choosing-film-cameras-35mm-to-pands/)
* [Link to a Workbook on the Web](https://article-tips.techidaily.com/2024-approved-the-prime-picks-best-storytelling-channels-fans/)
* [Link to a Word Document](https://video-screen-grab.techidaily.com/updated-pocket-safari-androids-selection-of-best-simulators/)

### Key Takeaways

With the HYPERLINK function, you can enter a file path or URL with the sheet, cell, or defined name you want to link to. For example: "=HYPERLINK("\[HTG\_Desktop.xlsx\]Sheet1!A6")" Insert display text to make your link friendlier.

 Excel offers its own [built-in linking feature in the toolbar](https://tech-revival.techidaily.com/enhance-your-at-home-workflow-with-these-6-ingenious-uses-of-chatgpt/). But the HYPERLINK function lets you do more, like a link to a workbook on your company intranet, shared server, another drive, or even a bookmark in a Word document. Let's look at everything you can do with this versatile function.

##  What Is the HYPERLINK Function?

 HYPERLINK in Excel is a function for [creating clickable links](https://android-location.techidaily.com/in-2024-3-effective-methods-to-fake-gps-location-on-android-for-your-samsung-galaxy-s23-drfone-by-drfone-virtual/) to all sorts of places and objects. You could, of course, do some of the same things that HYPERLINK does using the Link tool in Excel. However, a [formula](https://games-able.techidaily.com/is-premium-play-on-demand-worth-it/) gives you finer control of the link, and HYPERLINK is a simple function to learn that can get you comfortable with creating formulas in general. Additionally, HYPERLINK lets you link directly to a specific cell or defined name.

 The syntax for the function's formula is 

        `HYPERLINK(location, text)`
    
 where only the first argument is required and contains the path to the Excel file.

 You can use the second argument to display specific text as the link. Place text in quotation marks or use a cell reference. For example, instead of displaying the file path or [URL](https://extra-information.techidaily.com/boost-your-competitive-edge-with-custom-vocal-alteration-techniques-in-free-fire-gaming-no-charge/), you can display "Click Here" or a value from another cell in the current sheet.

Related: [How to Remove Hyperlinks in Microsoft Excel](https://extra-guidance.techidaily.com/new-secure-and-unshakable-direct-url-addition-on-your-tiktok-profile/) 

##  1\. Link to a Cell in the Spreadsheet

 To link to a certain cell in the current spreadsheet, you'll include the file name, sheet name, and cell reference. Notice that you place the file name in brackets and the entire argument in quotes.

 For example, with this formula, we link to cell A6 in our current spreadsheet named Sheet1\. The file name is HTG\_Desktop.xlsx. Remember to include the [file extension](https://twitter-videos.techidaily.com/updated-the-dos-and-donts-of-youtube-videos-on-twitter-for-2024/), which is either .xls or .xlsx depending on your version of Excel.

=HYPERLINK("[HTG_Desktop.xlsx]Sheet1!A6")

![HYPERLINK function to link within the current sheet](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/LinkCurrentSheet-ExcelHYPERLINKFunction.png) 

 To link to the same file, sheet, and cell, but use a friendly name for the link like "Go to A6", you can use this formula:

=HYPERLINK("[HTG_Desktop.xlsx]Sheet1!A6","Go to A6")

![HYPERLINK function to link within the current sheet and use display text](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/LinkCurrentSheetText-ExcelHYPERLINKFunction.png) 

##  2\. Link to a Cell Within the Workbook

 To link to a cell in the current workbook, but on [a different sheet](https://facebook-video-footage.techidaily.com/updated-2024-approved-dynamic-and-simple-building-a-subscriber-button-for-youtube-using-filmora/), simply replace the current sheet name with the other sheet's name.

 Here, we'll link to cell B2 on Sheet2:

=HYPERLINK("[HTG_Desktop.xlsx]Sheet2!B2")

![HYPERLINK function to link to a cell in another sheet](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/LinkOtherSheet-ExcelHYPERLINKFunction.png) 

 You can also insert the [CELL function](https://support.microsoft.com/en-us/office/cell-function-51bd39a5-f338-4dbe-a33f-955d67c2b2cf) as the `location` argument rather than typing the file name. Here's the formula for linking to the same cell as above:

=HYPERLINK(CELL("address",Sheet2!B2))

![HYPERLINK and CELL functions](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/LinkOtherSheetCELL-ExcelHYPERLINKFunction.png) 

 For this combined function formula, you can also enter display text for the `text` argument. Instead of adding text in quotes, we'll use the value in cell D1 which is the word "Title":

=HYPERLINK(CELL("address",Sheet2!B2),D1)

![HYPERLINK and CELL functions with a cell as display text](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/LinkOtherSheetCELLText-ExcelHYPERLINKFunction.png) 

##  3\. Link to a Defined Name

 Maybe you'd like to link to a [named range of cells](https://fox-blue.techidaily.com/2024-approved-mastering-chroma-key-techniques-in-live-broadcasts/) in the current or another Excel workbook. In this case, you'll add brackets around the path directly before the defined name.

 To link to the defined name Scores in the current workbook titled HTG\_Desktop.xlsx, you'd use the following formula:

=HYPERLINK("[HTG_Desktop.xlsx]Scores")

![HYPERLINK function to link a defined name](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/LinkCurrentDefinedName-ExcelHYPERLINKFunction.png) 

 To link to the defined name Totals in a different workbook, you'll enter the complete path in brackets followed by the cell range name like this:

=HYPERLINK("[C:\\Users\Sandy\Desktop\MyDataEntryForm.xlsx]Totals")

![HYPERLINK function to link a defined name in another sheet](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/LinkOtherDefinedName-ExcelHYPERLINKFunction.png) 

 To use something different for the display text, in either example, simply add it to the second argument:

=HYPERLINK("[HTG_Desktop.xlsx]Scores","Go There")

![HYPERLINK function to link a defined name with display text](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/LinkOtherDefinedNameText-ExcelHYPERLINKFunction.png) 

##  4\. Link to a Workbook on Another Drive

[Linking to an Excel file](https://extra-approaches.techidaily.com/new-reviewing-the-unseen-facebooks-privacy-and-security-guide/) on a different drive on your computer is another option. You can also link directly to a cell or named range if needed.

 To link to the file without a designated cell or defined name, include the complete path in quotes. Here, we'll link to the file MyDataEntryForm.xlsx on the E drive.

=HYPERLINK("E:\MyDataEntryForm.xlsx")

![HYPERLINK function to link a sheet on another drive](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/LinkOtherDrive-ExcelHYPERLINKFunction.png) 

 For a particular cell, we'll link to C9 on Sheet1 in the same file and location. Add brackets around the path with the sheet name and cell reference afterwards.

=HYPERLINK("[E:\MyDataEntryForm.xlsx]Sheet1!C9")

![HYPERLINK function to link a sheet cell on another drive](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/LinkOtherDriveCell-ExcelHYPERLINKFunction.png) 

 For another example, we'll link to the named range Totals in the same file and location. Because you're [using a defined name](https://some-skills.techidaily.com/new-the-impact-of-testimonial-videos-today/), be sure to insert the brackets around the path. Here, we'll include the display text Totals:

=HYPERLINK("[E:\MyDataEntryForm.xlsx]Totals","Totals")

![HYPERLINK function to link a defined name on another drive](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/LinkOtherDriveDefinedNameText-ExcelHYPERLINKFunction.png) 

##  5\. Link to a Workbook on the Web

 Maybe the workbook you want to link to is on your company intranet or a website. You can link to a remote XLSX file by including the full path in quotes as follows:

=HYPERLINK("http://www.mysite.com/report.xlsx")

![HYPERLINK function to link a workbook on the web](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/LinkWeb-ExcelHYPERLINKFunction.png) 

 To link to a specific sheet and cell, include the file path in brackets with the sheet name and cell reference directly following.

=HYPERLINK("[http://www.mysite.com/report.xlsx],Sheet1!A7")

![HYPERLINK function to link a workbook cell on the web](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/LinkWebCell-ExcelHYPERLINKFunction.png) 

##  6\. Link to a Word Document

 If you want to integrate your documents with your spreadsheets, you can use the HYPERLINK function to link to a Word document. Plus, you can link straight to a [bookmark you've created in Word](https://win-solutions.techidaily.com/stop-interruptions-ultimate-solution-to-world-of-tanks-blitz-stability-problems/).

 To link to the Word document, include the full path in quotes and don't forget the file extension. For Word, it's either .doc or .docx depending on your version:

=HYPERLINK("C:\\Users\Sandy\Desktop\MiscWorkDoc.docx")

![HYPERLINK function to link a Word document](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/LinkWord-ExcelHYPERLINKFunction.png) 

 To link to a bookmark in Word instead, you'll add those brackets followed by the bookmark name. Here, we link to the same file as above but directly to the bookmark named Details and include the display text Report:

=HYPERLINK("[C:\\Users\Sandy\Desktop\MiscWorkDoc.docx]Details","Report")

![HYPERLINK function to link a Word document bookmark with text](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/LinkWordBookmarkText-ExcelHYPERLINKFunction.png) 

 If you're looking for an alternative way to create links in Excel, especially for a particular cell in another workbook or one on the web, keep the HYPERLINK function in mind.

 For more, look at how to [link to cells or spreadsheets in Google Sheets](https://fox-links.techidaily.com/updated-in-2024-decoding-the-functions-of-a-virtual-reality-helmet/) too!

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
