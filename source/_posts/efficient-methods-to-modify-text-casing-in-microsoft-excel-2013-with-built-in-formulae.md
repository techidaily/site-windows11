---
title: Efficient Methods to Modify Text Casing in Microsoft Excel 2013 with Built-In Formulae
date: 2024-08-31T22:03:09.381Z
updated: 2024-09-01T22:03:09.381Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/00_lead_image_change_case.png
---

## Efficient Methods to Modify Text Casing in Microsoft Excel 2013 with Built-In Formulae

You may find you need to change multiple cells from one case to another in Excel. Maybe you imported data that came in all upper case, or maybe you convert headings on columns to upper case. Changing case is easy using some special functions.

 There are three functions that allow you to change the case of text in multiple columns easily:

* \= Upper(B1) – converts text to all upper case
* \= Lower(B1) – converts text to all lower case
* \= Proper(B1) – converts text to proper case, or title case (the first letter of each word is capitalized)

 For our example, we will change two columns of first and last names in a sample address list. First, we want to insert a new column after the Last name column. To do this, highlight the column after which you want to insert the blank column by clicking on the lettered header, right-click on the header, and select Insert from the popup menu.

![01_inserting_column](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/01_inserting_column.png) 

 The new column is formatted the same way as the original column. In our example, we entered the title of the column in the gray highlighted cell at the top of the column. We will be deleting the original column once we’ve converted the case.

![02_entering_title](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/02_entering_title.png) 

 In the first cell of the new column, enter the desired case function, with the cell reference in the parentheses, for the text you want to convert. In our example, we want to convert each name to title case, so we entered the Proper() function in the first cell in the column (below the heading row) with A2 as the cell reference.

 NOTE: Remember to preface your function with the equals sign.

![03_entering_formula](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/03_entering_formula.png) 

 Now, we need to propagate the function to the rest of the cells in the column. To do this, select the cell containing the case function and click Copy in the Clipboard section of the Home tab or press Ctrl + C.

![04_clicking_copy](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/04_clicking_copy.png) 

 Highlight the remaining cells in the column and click Paste or press Ctrl + V.

![05_clicking_paste](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/05_clicking_paste.png) 

 TIP: You can also quickly copy the contents of a cell into the remaining cells in the column by double-clicking the box on the lower, right corner of the cell.

![05a_double_click_box_to_paste](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/05a_double_click_box_to_paste.png) 

 Each of the cells in the new column look like they contain the names in a different case. However, each cell still contains the Proper() function referring to another cell. Because we are planning to delete the original column, we need to replace the function with the actual name to which it evaluates. To do this, highlight all the cells in the column containing the function and copy them.

![06_formula_still_in_cells](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/06_formula_still_in_cells.png) 

 To paste the values back into the same cells, click the down arrow on the Paste button in the Clipboard section of the Home tab. Then, click Values in the Paste Values section.

 NOTE: This is the same procedure we discussed in a previous article about [converting a numerical formula to a static value](https://article-posts.techidaily.com/decoding-the-art-of-enhanced-perception-for-2024/).

![07_pasting_values](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/07_pasting_values.png) 

 Now, all the cells in the column should contain text, not functions.

![08_names_in_cells](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/08_names_in_cells.png) 

 To delete the original column, select the entire column by clicking the lettered header, right-click on the header, and select Delete from the popup menu.

![09_deleting_original_column](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/09_deleting_original_column.png) 

 To convert the first names to title case, we followed the same procedure.

![10_both_columns_fixed](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/10_both_columns_fixed.png) 

 It’s that easy to tidy up your text. These case functions will also work if the case of the text is jumbled (e.g., bUFfEt).

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
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-exploring-browsing-anomalies-where-are-my-fb-video-suggestions/"><u>[New] 2024 Approved  Exploring Browsing Anomalies  Where Are My FB Video Suggestions?</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-elite-video-influencers-for-2024/"><u>[New] Elite Video Influencers for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-hdri-vs-sdr-a-comparative-analysis-for-filmmakers/"><u>[New] HDRI Vs. SDR  A Comparative Analysis for Filmmakers</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-titans-clash-discovering-the-ultimate-7-grand-wars/"><u>[New] Titans Clash  Discovering the Ultimate 7 Grand Wars</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-the-twitch-enthusiasts-recording-guidebook-for-2024/"><u>[Updated] The Twitch Enthusiast's Recording Guidebook for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-exploring-why-filmmakers-cherish-filmora-features/"><u>2024 Approved  Exploring Why Filmmakers Cherish Filmora Features</u></a></li>
<li><a href="https://screen-recording.techidaily.com/crafting-your-weekly-schedule-with-google-meet/"><u>Crafting Your Weekly Schedule with Google Meet</u></a></li>
<li><a href="https://win11.techidaily.com/dissecting-the-role-of-windows-cab-files-in-system-setup/"><u>Dissecting the Role of Windows CAB Files in System Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-using-microsoft-copilot-in-development/"><u>Essential Guide to Using Microsoft Copilot in Development</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-guidance-on-hardware-and-software-at-toms-review-site/"><u>Expert Guidance on Hardware & Software at Tom's Review Site</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-your-slow-internet-matching-mobile-and-desktop-speeds/"><u>Fix Your Slow Internet: Matching Mobile and Desktop Speeds</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-incompatible-fingerprint-error-on-windows-os/"><u>Fixing Incompatible Fingerprint Error on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-your-windows-license-will-expire-soon-error-on-windows-10-and-11/"><u>How to Fix the “Your Windows License Will Expire Soon” Error on Windows 10 and 11</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1722891200961-how-to-pair-airpods-with-your-nintendo-switch-console/"><u>How To Pair AirPods With Your Nintendo Switch Console</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-15-to-other-iphone-15-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 15 to other iPhone 15 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/ifas-best-laptops-of-2023-now/"><u>IFA's Best Laptops of 2023, Now!</u></a></li>
<li><a href="https://windows11.techidaily.com/keyboard-shortcut-wisdom-shrinking-down-software-in-win11/"><u>Keyboard Shortcut Wisdom: Shrinking Down Software in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-meaning-of-windows-mbr-error-messages/"><u>Mastering the Meaning of Windows MBR Error Messages</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-here-are-top-10-webm-to-mp3-converters-you-can-either-install-on-your-pc-or-mac-computer-or-use-online-to-convert-webm-video-to-mp3-audio-file.m/"><u>New In 2024, Here Are Top 10 WebM to MP3 Converters You Can Either Install on Your PC or Mac Computer or Use Online to Convert Webm Video to Mp3 Audio File</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-zero-error-in-windows-11-with-procedures/"><u>Overcoming Zero-Error in Windows 11 with Procedures</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/prime-ringtone-retailers-for-game-of-thrones-fans-for-2024/"><u>Prime Ringtone Retailers for Game of Thrones Fans for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-forgotten-power-schemes-on-ws-11/"><u>Resetting Forgotten Power Schemes on WS 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-lockout-due-to-failed-sign-in-attempts/"><u>Resolving Windows Lockout Due to Failed Sign-In Attempts</u></a></li>
<li><a href="https://windows11.techidaily.com/revamping-robustness-of-win11s-cleanup-companion-ccleaner/"><u>Revamping Robustness of Win11's Cleanup Companion, CCleaner</u></a></li>
<li><a href="https://windows11.techidaily.com/speed-ahead-overcoming-low-valorant-download-speeds-in-windows/"><u>Speed Ahead: Overcoming Low Valorant Download Speeds in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-hypervisorbsod-in-windows-a-top-ten-approach/"><u>Stop HYPERVISOR_BSOD in Windows: A Top-Ten Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-translations-hotkey-tips-for-windows-11-language-switching/"><u>Streamline Translations: Hotkey Tips for Windows 11 Language Switching</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-tasks-top-9-reasons-to-adopt-modernized-outlook/"><u>Streamline Your Tasks: Top 9 Reasons to Adopt Modernized Outlook</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-nvidia-connection-failures-in-10-and-11-editions/"><u>Streamlining Nvidia Connection Failures in 10 & 11 Editions</u></a></li>
<li><a href="https://windows11.techidaily.com/the-7-best-photo-organizer-apps-for-windows/"><u>The 7 Best Photo Organizer Apps For Windows</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-definitive-guide-to-interpreting-windows-system-failures-and-crashes/"><u>The Definitive Guide to Interpreting Windows System Failures and Crashes</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-fix-guide-stabilizing-ps4-input-link-on-pc/"><u>The Ultimate Fix Guide: Stabilizing PS4 Input Link on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-how-to-fix-older-user-credential-message/"><u>Unlocking: How to Fix Older User Credential Message</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-directdraw-complexities-in-the-latest-microsoft-oses/"><u>Unraveling DirectDraw Complexities in the Latest Microsoft OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-cs-go-launch-guide/"><u>Windows 11 CS GO Launch Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-woes-get-your-arrows-back-to-normal/"><u>Windows Woes? Get Your Arrows Back to Normal</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->