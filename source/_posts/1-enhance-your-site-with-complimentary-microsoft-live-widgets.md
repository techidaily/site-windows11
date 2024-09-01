---
title: 1. Enhance Your Site with Complimentary Microsoft Live Widgets
date: 2024-08-31T22:04:05.660Z
updated: 2024-09-01T22:04:05.660Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/sshot20100604114715.png
---

## 1. Enhance Your Site with Complimentary Microsoft Live Widgets

Would you like to use Hotmail, Office Web Apps, Messenger, and more on your website domain? Here's how you can add Windows Live to your website for free. Microsoft offers a popular suite of online communications products including Hotmail and Messenger. Although Hotmail hasn't been as popular in recent years as Gmail, it is getting a refresh this summer that might make it an even better email solution. Additionally, the new Office Web Apps offer great compatibility with Office documents. While Skydrive offers 25Gb of free online file storage for all users, so Windows Live can make a great communications solution for your domain. Note**:** To signup for Windows Live for your domain, you will need to be able to add info to your WordPress.com blog or change Domain settings manually. **Getting Started** Open the Windows Live Custom Domains page (Link below) to get started adding Windows Live to your domain. Your free Windows Live account will let you create up to 500 accounts, so it's great for teams and groups that want to have customized email addresses in addition to those who just want an email account for their website. Enter your domain or subdomain you want to add to Windows Live in the box, and then select whether you want to setup Hotmail with this or now. We want to add email to our domain, so select Set up Windows Live Hotmail for my domain and click Continue. You'll need to sign in with a Windows Live ID to create the account, or choose to create a new Windows Live account associated with your domain. 

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/image44.png) 

 Sign in with your Windows Live ID...this can be a Hotmail, Live Messenger, XBOX Live, Zune ID, or Microsoft.com account. 

![sshot-2010-06-04-[11-49-18]](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/sshot20100604114918.png) 

 Or, enter your information to create a new Windows Live ID if you selected the second option. 

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/image45.png) 

 Now, review your settings and make sure everything looks correct. Click the I Accept button to setup your account. 

![sshot-2010-06-04-[11-49-53]](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/sshot20100604114953.png) 

 Your account is now fully setup, but you'll need to add or edit DNS information on your site. The steps are slightly different depending if your site is hosted on WordPress.com, on your own server, or hosting service. We'll show you how to do it on either one. 

![sshot-2010-06-04-[12-24-02]](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/sshot20100604122402.png) 

 First, though, note the information below this box. You'll see settings for your Mail setup... 

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/image46.png) 

 Security settings... 

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/image47.png) 

 And Messenger integration. Make note of the settings, especially the circled ones, as we'll need them in the next step. 

![sshot-2010-06-04-[12-24-35]](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/sshot20100604122435.png) 

**Integrate Windows Live with Your WordPress Blog** If the domain you added to Windows Live is for your [WordPress blog](https://tech-hub.techidaily.com/how-do-character-restrictions-affect-chatgpts-generated-text-outputs/), login to your WordPress dashboard in a separate browser window or tab. Click the arrow beside Upgrades, and select Domains from the menu. 

![sshot201006032200002](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/sshot201006032200002.png) 

 Click the Edit DNS link beside the domain name you're adding to Windows Live. 

![sshot201006032200593](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/sshot201006032200593.png) 

 In the text box on this page, enter the following, replacing **Your\_info** with your code from the Mail Setup box in your Windows Live Dashboard. Note that this is the blurred section in our screenshots. It should be a numerical code like 1234567890.pamx1.hotmail.com. 

> MX 10 **Your\_info**.pamx1.hotmail.com.

> TXT v=spf1 include:hotmail.com \~all CNAME **Your\_info** domains.live.com.

 Click Save DNS records, and your settings are saved to WordPress. Note that this will only integrate email with your WordPress account; you cannot integrate Messenger with a domain hosted on WordPress.com. 

![sshot-2010-06-04-[12-11-53]](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/sshot20100604121153.png) 

 Finally, return to your Windows Live Settings page and click Refresh. If your settings are correct, you'll now be ready to use Windows Live on your WordPress.com domain. 

![sshot-2010-06-04-[12-24-02]](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/sshot20100604122402.png) 

**Integrate Windows Live with Your Own Server** If your website is hosted on your own server or hosting account, you'll need to take a few more steps to add Windows Live to your domain. This is fairly easy, but the steps may be different depending on your hosting company or registrar. With some hosts, you may have to contact support to have them add the MX records for you. Our site's host uses the popular cPanel for website administration, so here's how we added the MX Entries through cPanel. Login to your website's cPanel, and select MX Entry under the Mail section. 

![sshot-2010-06-04-[12-14-48]](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/sshot20100604121448.png) 

 In the text box on this page, enter the following, replacing **Your\_info** with your code from the Mail Setup box in your Windows Live Dashboard. Note that this is the blurred section in our screenshots. It should be a numerical code like 1234567890.pamx1.hotmail.com. 

> MX 10 **Your\_info**.pamx1.hotmail.com.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/image48.png) 

 Now, go back to your cPanel home, and select Advanced DNS Zone Editor under Domains. 

![sshot-2010-06-04-[12-17-11]](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/sshot20100604121711.png) 

 Here, add a TXT record with the following info: 

| Name:     | **yoursite.com.**                |
| --------- | -------------------------------- |
| TTL:      | 3600                             |
| TXT Data: | v=spf1 include:hotmail.com \~all |

 Click Add Record and your Mail integration data is all configured. 

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/image49.png) 

 To integrate Messenger with your own domain, you'll have to add an SRV entry to your DNS settings. cPanel doesn't have an option for this, so we had to contact our site's hosting company and they added the entry for us. Copy all of the information in the Messenger box and send it to your domain support, and they should be able to add this for you. Alternately, if you don't want or need Messenger, then you can simply skip this step. 

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/image50.png) 

 Once all of your settings are in place, return to your Windows Live Settings page and click Refresh. If your settings are correct, you'll now be ready to use Windows Live on your WordPress.com domain. 

![sshot-2010-06-04-[12-24-02]](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/sshot20100604122402.png) 

**Create a New Email Account On Your Domain** Welcome to your new Windows Live admin page! Now you can add email accounts so you and anyone else you want can access Hotmail and the other Windows Live apps with your domain. Click Add to add an account. 

![sshot-2010-06-04-[12-25-05]](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/sshot20100604122505.png) 

 Enter an account name, which will be the email address of the account, e.g. **accountname@yourdomain.com**. Then enter the user's name and a password for the account. By default this will be a temporary password, and the user will have to change it on first log-in, but if you're setting up this account for yourself, you can uncheck the box and keep this as your standard password. 

![sshot-2010-06-04-[12-59-27]](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/sshot20100604125927.png) 

 Now, go to [www.mail.live.com](http://www.mail.live.com), and sign in with your new email address and password. Remember, your email address is your username previously entered followed by @**yourdomain.com**. 

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/image51.png) 

 To finish setting up the email account, enter your password, secret question and answer, alternate email, and location information. Click I accept to finish setting up your new email account. 

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/image52.png) 

 Enter the characters in the Captcha to confirm you're a human, and click Continue. 

![sshot-2010-06-04-[13-03-35]](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/sshot20100604130335.png) 

 Your new Hotmail inbox will now load, and you'll have a welcome email in your inbox. This works the same as normal Hotmail, except this time, your email address is with your own domain. 

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/image53.png) 

 You can now access any of the Windows Live services from the top-level menu. 

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/image54.png) 

 Here's an Excel Spreadsheet open in the new Office Web Apps via SkyDrive on our new Windows Live account. 

![sshot-2010-06-04-[13-32-14]](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/sshot20100604133214.png) 

 If you setup Messenger access previously, you can now sign in to Windows Live Messenger using your new @**yourdomain.com** account as well. 

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/image55.png) 

**Important Links** Accessing your Windows Live accounts is easy. Simply go to any Windows Live site, such as [www.hotmail.com](http://www.hotmail.com) or [www.skydrive.com](http://www.skydrive.com), and sign in with your new Windows Live ID from your domain as normal. You don't need a special address to access your account; it works just like the standard public Hotmail accounts. To administer your Windows Live for your domain, go to <https://domains.live.com/> and sign in with the Windows Live ID you used to create the account. Here you can add more users, change settings, and view usage details for the Windows Live accounts on your domain. 

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/06/image56.png) 

**Conclusion** Windows Live is easy to add to your domain, and lets you create up to 500 email address for it. With the upcoming updates to Hotmail and Office Web Apps coming this summer, this can be a nice way to make your domain even more useful. And with 500 email accounts, you can easily let your team take advantage of your unique address as well. If you'd rather use Google's online applications with your domain, check out our article on how to [add free Google apps to your website or blog](https://tech-haven.techidaily.com/reliable-guide-successfully-transforming-your-kindle-books-into-epub-format-proven-methods-of-2024/). **Link** [Signup for Windows Live for Your Domain](https://domains.live.com/Signup/SignupDomain.aspx)

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
<li><a href="https://youtube-webster.techidaily.com/024-approved-10-best-asmr-recorders-for-exceptional-audio-quality/"><u>[New] 2024 Approved  10 Best ASMR Recorders for Exceptional Audio Quality</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-ideal-choices-for-comprehensive-movement-recording/"><u>[New] 2024 Approved  Ideal Choices for Comprehensive Movement Recording</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-t5-thievery-released-a-deep-dive-review-for-2024/"><u>[New] T5 Thievery Released - A Deep Dive Review for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2023-endless-ears-on-facebook-downloads-for-2024/"><u>[Updated] 2023  Endless Ears on Facebook Downloads for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-the-game-plan-to-trendsetting-video-content/"><u>[Updated] 2024 Approved  The Game Plan to Trendsetting Video Content</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-oppo-a78-system-crash-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Oppo A78 System Crash Issue | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/ais-interactive-voice-turning-prompts-into-meaningful-exchanges/"><u>AI's Interactive Voice: Turning Prompts Into Meaningful Exchanges</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/discover-an-enhanced-reading-experience-with-wikipedias-latest-dark-mode-update/"><u>Discover an Enhanced Reading Experience with Wikipedia's Latest Dark Mode Update</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-using-microsoft-copilot-in-development/"><u>Essential Guide to Using Microsoft Copilot in Development</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-troubleshooting-missing-steam-controllers/"><u>Essential Tips: Troubleshooting Missing Steam Controllers</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-your-slow-internet-matching-mobile-and-desktop-speeds/"><u>Fix Your Slow Internet: Matching Mobile and Desktop Speeds</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-your-unresponsive-xbox-controllers-on-pc/"><u>Fixing Your Unresponsive Xbox Controllers on PC</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-gmail-password-on-xiaomi-redmi-note-12t-pro-devices-by-drfone-android/"><u>How to Reset Gmail Password on Xiaomi Redmi Note 12T Pro Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-unfreeze-google-chrome-in-windows-11-fastly-find-out-now/"><u>How to Unfreeze Google Chrome in Windows 11 Fastly? Find Out Now!</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-unlock-pin-related-bluetooth-disconnects-in-win11win10/"><u>How To Unlock PIN-Related Bluetooth Disconnects in Win11/Win10</u></a></li>
<li><a href="https://windows11.techidaily.com/identifying-your-device-top-6-windows-pc-model-names/"><u>Identifying Your Device: Top 6 Windows PC Model Names</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-blueprint-for-successful-valorant-thumbnails-on-social-media-platforms/"><u>In 2024, The Blueprint for Successful Valorant Thumbnails on Social Media Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-meaning-of-windows-mbr-error-messages/"><u>Mastering the Meaning of Windows MBR Error Messages</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-easily-getting-outlook-preview-on-winoss/"><u>Navigate Easily: Getting Outlook Preview on WinOSs</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-non-operational-windows-programs-with-7-strategies/"><u>Navigating Non-Operational Windows Programs with 7 Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-text-pasting-in-powertoys-quickly/"><u>Navigating Text Pasting in PowerToys Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-code-0x0000004e-anomalies/"><u>Navigating Through Code 0X0000004E Anomalies</u></a></li>
<li><a href="https://buynow-help.techidaily.com/nokia-71-analysis-exceptional-visuals-photography-and-cost-effective-smartphone-selection/"><u>Nokia 7.1 Analysis: Exceptional Visuals, Photography, and Cost-Effective Smartphone Selection</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/photobooth-hiccups-resolving-frozen-playback-issues/"><u>Photobooth Hiccups  Resolving Frozen Playback Issues</u></a></li>
<li><a href="https://hardware-help.techidaily.com/raphael-demystifies-ddr5-insights-from-amd-and-samsungs-joint-webinar-on-memory-technology-evolution/"><u>Raphael Demystifies DDR5: Insights From AMD & Samsung's Joint Webinar on Memory Technology Evolution</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaim-lost-boot-prompts-uefi-fixes/"><u>Reclaim Lost Boot Prompts: UEFI Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-forgotten-power-schemes-on-ws-11/"><u>Resetting Forgotten Power Schemes on WS 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-lockout-due-to-failed-sign-in-attempts/"><u>Resolving Windows Lockout Due to Failed Sign-In Attempts</u></a></li>
<li><a href="https://windows11.techidaily.com/revamping-robustness-of-win11s-cleanup-companion-ccleaner/"><u>Revamping Robustness of Win11's Cleanup Companion, CCleaner</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/solved-rejuvenate-fallout-4-on-windows/"><u>Solved: Rejuvenate Fallout 4 on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-tasks-top-9-reasons-to-adopt-modernized-outlook/"><u>Streamline Your Tasks: Top 9 Reasons to Adopt Modernized Outlook</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-nvidia-connection-failures-in-10-and-11-editions/"><u>Streamlining Nvidia Connection Failures in 10 & 11 Editions</u></a></li>
<li><a href="https://windows11.techidaily.com/the-7-best-photo-organizer-apps-for-windows/"><u>The 7 Best Photo Organizer Apps For Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-fix-guide-stabilizing-ps4-input-link-on-pc/"><u>The Ultimate Fix Guide: Stabilizing PS4 Input Link on PC</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/top-10-google-cardboards-most-stunning-vr-games-for-2024/"><u>Top 10  Google Cardboard's Most Stunning VR Games for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/transformative-ways-to-customize-windows-11-ui/"><u>Transformative Ways to Customize Windows 11 UI</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-the-access-denied-message-for-windows-device-files/"><u>Troubleshooting the 'Access Denied' Message for Windows Device Files</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-potential-understanding-function-fn-key-operations/"><u>Unleash Potential: Understanding Function (Fn) Key Operations</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-how-to-fix-older-user-credential-message/"><u>Unlocking: How to Fix Older User Credential Message</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-directdraw-complexities-in-the-latest-microsoft-oses/"><u>Unraveling DirectDraw Complexities in the Latest Microsoft OSes</u></a></li>
<li><a href="https://some-techniques.techidaily.com/utilizing-cookiebot-technology-custom-marketing-with-advanced-tracking/"><u>Utilizing Cookiebot Technology | Custom Marketing with Advanced Tracking</u></a></li>
<li><a href="https://windows11.techidaily.com/win-specific-error-recovery-reinstating-non-functional-software/"><u>Win-Specific Error Recovery: Reinstating Non-Functional Software</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->