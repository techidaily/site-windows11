---
title: "Mastering Microsoft Excel: A Comprehensive Guide to Using the SUBSTITUTE Function"
date: 2024-08-31T22:03:23.760Z
updated: 2024-09-01T22:03:23.760Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/b734a2c6690e4996dacb7188f3387d968781f292fbd537e9c3d8dd96d06bbb96.jpg
---

## Mastering Microsoft Excel: A Comprehensive Guide to Using the SUBSTITUTE Function

### Quick Links

* [What to Know When Using the SUBSTITUTE Function](https://article-helps.techidaily.com/updated-mastering-media-conversion-with-actionable-steps-from-xml-for-2024/)
* [Replace Occurrences of a String Using SUBSTITUTE in Excel](https://android-location.techidaily.com/how-to-fake-gps-on-android-without-mock-location-for-your-xiaomi-redmi-13c-5g-drfone-by-drfone-virtual/)

 To [replace a string](https://screen-mirror.techidaily.com/the-top-10-apple-iphone-6-plus-emualtors-for-windows-mac-and-android-drfone-by-drfone-ios/) of text, numbers, or symbols, Microsoft Excel offers a function called `SUBSTITUTE`. This function replaces the specified string with your choice of string. We'll show you how to use it in your spreadsheets.

Related: [How to Replace Any Character with Newlines in Notepad++](https://screen-mirror.techidaily.com/the-top-10-apple-iphone-6-plus-emualtors-for-windows-mac-and-android-drfone-by-drfone-ios/) 

##  What to Know When Using the SUBSTITUTE Function

 When you use the `SUBSTITUTE` function, know that it's case-sensitive and so you'll have to use it accordingly. Also, you can't specify wildcard entries in the function. You can use the function with your hard-coded values as well as [cell references](https://some-guidance.techidaily.com/the-ultimate-step-by-step-guide-to-kinemasters-green-screen-mastery-for-2024/).

 The function even lets you choose the instances of your specified string to change. This way, if you only want to change the first occurrence of a string, you can do so.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
##  Replace Occurrences of a String Using SUBSTITUTE in Excel

 To start using the function, open your spreadsheet with Microsoft Excel.

 In the spreadsheet, select the cell in which you want to display the result. In the below example, we'll replace 

        `HTG`
    
 with 

        `How-To Geek`
    
 .

![Click a cell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/1-select-cell-excel.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
 In your selected cell, type the following function and press Enter.

 In this function:

* **B2**: It's the cell with the content that you want to replace.
* **HTG**: This is the original string that you want to find and replace with the new string.
* **How-To Geek**: This is the new string that will replace the old string.

=SUBSTITUTE(B2,"HTG","How-To Geek")

![Replace a string with SUBSTITUTE.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/2-enter-substitute-function.png) 

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
 You'll see that the function has replaced the values as defined in the arguments.

![The result of the SUBSTITUTE function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/3-substitute-function-result.png) 

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Another scenario where you may want to use this function is when you want to change the country code for phone numbers. For example, if you have a list of phone numbers containing `+91` as the country code, you can use the `SUBSTITUTE` function to make all these phone numbers use `+1` as the country code.

 To do so, use the `SUBSTITUTE` function with the following arguments:

=SUBSTITUTE(B2,"91","1",1)

![Enter the SUBSTITUTE function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/4-change-country-code.png) 

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 As you can see, in the above function, we've specified `1` at the end. This tells the function to only change the first occurrence of `91` to `1`. If the remaining numbers in a phone number contain `91`, the function won't change that. This helps you avoid ending up with incorrect phone numbers.

![Country code changed with the SUBSTITUTE function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/5-country-code-changed.png) 

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 And that's how you use Excel's `SUBSTITUTE` function to change various strings in your spreadsheets.

---

 Another way to change your spreadsheet's contents is by [using Excel's find and replace feature](https://twitter-videos.techidaily.com/best-twitter-video-downloaders-how-to-save-twitter-videos-for-2024/). Check out our guide on that if you're interested.

Related: [How to Find and Replace Text and Numbers in Excel](https://twitter-videos.techidaily.com/best-twitter-video-downloaders-how-to-save-twitter-videos-for-2024/)

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
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-surging-up-the-search-results-with-effective-podcast-seo/"><u>[New] 2024 Approved  Surging Up the Search Results with Effective Podcast SEO</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-fixing-full-screen-failure-in-obs/"><u>[New] In 2024, Fixing Full Screen Failure in Obs</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-canvas-clearance-techniques-for-uncluttered-image-frames/"><u>[Updated] Canvas Clearance Techniques for Uncluttered Image Frames</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-craft-magical-time-lapse-video-using-a-gopro/"><u>[Updated] Craft Magical Time Lapse Video Using a GoPro</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-ultimate-guide-to-effective-youtube-banners-for-2024/"><u>[Updated] The Ultimate Guide to Effective YouTube Banners for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-why-is-instagram-turning-my-video-sideways-in-2024/"><u>[Updated] Why Is Instagram Turning My Video Sideways, In 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/audio-resurrection-for-airpods-overcoming-the-silent-connection-challenge-on-microsofts-latest-operating-systems/"><u>Audio Resurrection for AirPods: Overcoming the Silent Connection Challenge on Microsoft's Latest Operating Systems</u></a></li>
<li><a href="https://solve-news.techidaily.com/complete-guide-download-and-convert-movies-to-4k-uhd-quality-on-your-mac/"><u>Complete Guide: Download & Convert Movies to 4K UHD Quality on Your Mac</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-and-install-hp-officejet-pro-8610-drivers-on-windows-1110-complete-guide/"><u>Download & Install HP Officejet Pro 8610 Drivers on Windows 11/10: Complete Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/establishing-alternate-view-for-windows-pdfs/"><u>Establishing Alternate View for Windows PDFs</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-unable-to-launch-java-vm-on-windows-systems/"><u>Fixing Unable to Launch Java VM on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-to-fix-non-working-google-writes-on-pc/"><u>Guidelines to Fix Non-Working Google' Writes on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-through-chrome-edge-and-firefox-pasting-fixes/"><u>Guiding Through Chrome, Edge & Firefox Pasting Fixes</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-change-lock-screen-wallpaper-on-infinix-zero-30-5g-by-drfone-android/"><u>How to Change Lock Screen Wallpaper on Infinix Zero 30 5G</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-videos-from-motorola-razr-40-ultra-to-ipad-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Videos from Motorola Razr 40 Ultra to iPad | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-5-solutions-for-vivo-g2-unlock-without-password-by-drfone-android/"><u>In 2024, 5 Solutions For Vivo G2 Unlock Without Password</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-6-methods-to-protect-yourself-from-location-tracking-on-apple-iphone-se-drfone-by-drfone-virtual-ios/"><u>In 2024, 6 Methods to Protect Yourself from Location Tracking on Apple iPhone SE | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-budget-cameras-with-bold-action-features-and-quality/"><u>In 2024, Budget Cameras with Bold Action Features and Quality</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-embark-into-the-best-youtube-vr-content-ever/"><u>In 2024, Embark Into the Best YouTube VR Content Ever!</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-how-to-fake-gps-on-android-without-mock-location-for-your-asus-rog-phone-7-drfone-by-drfone-virtual/"><u>In 2024, How to Fake GPS on Android without Mock Location For your Asus ROG Phone 7 | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-pause-life360-location-sharing-for-vivo-s17e-drfone-by-drfone-virtual-android/"><u>In 2024, How To Pause Life360 Location Sharing For Vivo S17e | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-realme-gt-5-drfone-by-drfone-virtual-android/"><u>In 2024, Will Pokémon Go Ban the Account if You Use PGSharp On Realme GT 5 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/internal-naming-systems-a-detailed-approach-to-folders-in-explorer/"><u>Internal Naming Systems: A Detailed Approach to Folders in Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/key-to-command-line-shorthand-in-program-launches/"><u>Key to Command Line Shorthand in Program Launches</u></a></li>
<li><a href="https://windows11.techidaily.com/master-8-windows-cutting-apps-for-videos/"><u>Master 8 Windows Cutting Apps for Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-hard-drive-images-in-windows-os/"><u>Mastering Hard Drive Images in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-window-colors-and-style-in-terminal/"><u>Mastery over Window Colors & Style in Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/method-to-detach-onedrive-from-microsoft-id-in-windows/"><u>Method to Detach OneDrive From Microsoft ID in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-maze-fixing-windows-11-access-issues/"><u>Navigating the Maze: Fixing Windows 11 Access Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-0x80072af9-obstacle/"><u>Navigating Through Windows' 0X80072AF9 Obstacle</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-to-install-powertoys-on-win11-pro/"><u>Navigating to Install PowerToys on Win11 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11-install-quick-keyboard-shortcuts/"><u>Navigating Windows 11: Install Quick Keyboard Shortcuts</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-connection-4-ways-to-determine-router-speed-on-windows/"><u>Optimize Connection: 4 Ways to Determine Router Speed on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-common-hurdles-in-launching-obs-windows/"><u>Overcoming Common Hurdles in Launching OBS (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-glitches-in-windows-system-insights-tracker/"><u>Overcoming Glitches in Windows System Insights Tracker</u></a></li>
<li><a href="https://windows11.techidaily.com/overhauling-the-default-administrator-model-for-windows-users/"><u>Overhauling the Default Administrator Model for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/pathway-to-windows-11-utilizing-windows-7-key-as-a-gateway/"><u>Pathway to Windows 11: Utilizing Windows 7 Key as a Gateway</u></a></li>
<li><a href="https://windows11.techidaily.com/proving-win-hardware-with-top-6-graphics-testing-apps/"><u>Proving Win Hardware with Top 6 Graphics Testing Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/regain-access-to-sd-card-in-file-explorer-window/"><u>Regain Access to SD Card in File Explorer Window</u></a></li>
<li><a href="https://techidaily.com/remove-google-frp-lock-on-tecno-spark-20-by-drfone-android-unlock-remove-google-frp/"><u>Remove Google FRP Lock on Tecno Spark 20</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-icons-the-step-by-step-process/"><u>Resetting Icons: The Step-by-Step Process</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolved-updating-your-minecraft-graphics-driver-a-comprehensive-guide/"><u>Resolved: Updating Your Minecraft Graphics Driver - A Comprehensive Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-control-panel-error-with-missing-display-adjustments/"><u>Resolving Control Panel Error with Missing Display Adjustments</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-your-input-not-recognized-by-vlc/"><u>Resolving Windows: Your Input Not Recognized by VLC</u></a></li>
<li><a href="https://windows11.techidaily.com/secrets-of-storage-the-top-6-win11-techniques-for-capturing-file-and-directory-paths/"><u>Secrets of Storage: The Top 6 Win11 Techniques for Capturing File & Directory Paths</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-address-non-definable-values-in-winos/"><u>Strategies to Address Non-Definable Values in WinOS</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/mline-your-viewing-experience-youtube-ad-block-strategies/"><u>Streamline Your Viewing Experience - YouTube Ad-Block Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-user-experience-customizing-windows-pin-lengths/"><u>Tailoring User Experience: Customizing Windows PIN Lengths</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/three-ways-to-sim-unlock-oppo-a59-5g-by-drfone-android/"><u>Three Ways to Sim Unlock Oppo A59 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-avoid-vscode-crashing-on-new-os/"><u>Tips to Avoid VSCode Crashing on New OS</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-10-strategies-for-achieving-virality-on-insta/"><u>Top 10 Strategies for Achieving Virality on Insta</u></a></li>
<li><a href="https://some-skills.techidaily.com/top-vr-game-creators-to-watch-for-2024/"><u>Top VR Game Creators To Watch for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/traversing-the-digital-landscape-with-ease/"><u>Traversing the Digital Landscape with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-true-productivity-advanced-w11-taskbar-pins/"><u>Unlock True Productivity: Advanced W11 Taskbar Pins</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-windows-live-movie-maker-tutorial-easy-video-splitting-techniques/"><u>Updated 2024 Approved Windows Live Movie Maker Tutorial Easy Video Splitting Techniques</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-discover-the-8-most-compelling-soundscapes-for-youtube-debut-videos/"><u>Updated Discover the 8 Most Compelling Soundscapes for YouTube Debut Videos</u></a></li>
<li><a href="https://fake-location.techidaily.com/wondering-the-best-alternative-to-hola-on-lava-blaze-pro-5g-here-is-the-answer-drfone-by-drfone-virtual-android/"><u>Wondering the Best Alternative to Hola On Lava Blaze Pro 5G? Here Is the Answer | Dr.fone</u></a></li>
</ul></div>
