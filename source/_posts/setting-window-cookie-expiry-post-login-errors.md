---
title: Setting Window' Cookie Expiry Post-Login Errors
date: 2024-08-08T06:09:25.141Z
updated: 2024-08-09T06:09:25.141Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Setting Window' Cookie Expiry Post-Login Errors
excerpt: This Article Describes Setting Window' Cookie Expiry Post-Login Errors
keywords: Cookie Setup Duration,Login Error Management,Post-Login Cookie TTL,Preventing Login Failures,Session Time To Live,Manage Cookies After Log In,Avoid Login Issues
thumbnail: https://thmb.techidaily.com/23bcbbd5e45bcabcdfd0dcf9f0d56055fdfa4178e94d0dd13999edb6b6a4b8b2.jpg
---

## Setting Window' Cookie Expiry Post-Login Errors

 Windows has a policy setting that can lock someone out from signing in if they enter the wrong local account password too many times. The user is not allowed to sign in for a set number of minutes after being locked out, but you can change this lockout duration.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Change the Duration a User Is Locked Out of Their Account via Local Security Policy

 This method will work as long as the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press **Windows key + R** to open the **Run** dialogue.
2. Type “secpol.msc” into the text field and hit **Enter**.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, click on the **Account Lockout Policy** folder under **Account Policies**.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on **Account lockout duration**.  
![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
![Choose how long a local account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-set-local-account-lockout-duration.jpg)

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
3. This will pull up information, among other things, about how long this account lockout duration is currently set.
4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->
## Find the Balance Between Security and Convenience

 Setting account lockout duration too high will cause inconvenience, but if you set it to zero, an administrator will have to be contacted each time a user locks themselves out. Find a balance between security and convenience when it comes to changing how long a user is locked out after a set number of failed login attempts.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-how-to-do-screen-recording-on-iphone-easily/"><u>[New] 2024 Approved  How to Do Screen Recording on Iphone Easily?</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-entry-level-exploration-into-visual-frameworks-for-2024/"><u>[New] Entry-Level Exploration Into Visual Frameworks for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-light-up-the-screen-tips-and-steps-for-adding-gifs-to-snapchats/"><u>[New] Light Up the Screen  Tips and Steps for Adding GIFs to Snapchats</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-pixelated-prowess-celebrating-the-best-shooter-classics/"><u>[Updated] 2024 Approved  Pixelated Prowess  Celebrating the Best Shooter Classics</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-explore-unlimited-free-fun-with-top-meme-templates/"><u>[Updated] Explore Unlimited Free Fun with Top Meme Templates</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-mastering-the-knowledge-of-asmr-media/"><u>[Updated] Mastering the Knowledge of ASMR Media</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-spark-innovation-with-these-androids-top-graphic-designers/"><u>[Updated] Spark Innovation with These Android's Top Graphic Designers</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-the-9gag-pathway-to-piling-up-popular-memes-for-2024/"><u>[Updated] The 9GAG Pathway to Piling Up Popular Memes for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-guide-to-hyper-v-installation-in-win-11-home/"><u>A Comprehensive Guide to Hyper-V Installation in Win 11 Home</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-lenovo-thinkphone-drfone-by-drfone-virtual-android/"><u>A Detailed Guide on Faking Your Location in Mozilla Firefox On Lenovo ThinkPhone | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-operational-optimization-top-windows-pct-strategies/"><u>Achieve Operational Optimization: Top Windows PCT Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/adapting-the-oculus-quest-2-for-windows-os-virtual-reality/"><u>Adapting the Oculus Quest 2 for Windows OS Virtual Reality</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-oneplus-nord-ce-3-lite-5g-drfone-by-drfone-virtual-android/"><u>Can I use iTools gpx file to catch the rare Pokemon On OnePlus Nord CE 3 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/change-location-on-yik-yak-for-your-apple-iphone-xs-to-enjoy-more-fun-drfone-by-drfone-virtual-ios/"><u>Change Location on Yik Yak For your Apple iPhone XS to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-xc0000142-issue-in-windows-11-10/"><u>Correcting XC0000142 Issue in Windows 11, 10</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-windows-gadgets-2024s-must-haves-list/"><u>Cutting-Edge Windows Gadgets - 2024'S Must-Haves List</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-your-global-ip-on-win-os-via-cli/"><u>Demystifying Your Global IP on WIN OS via CLI</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/efficiently-shifting-huge-video-files-from-iphone-to-mac/"><u>Efficiently Shifting Huge Video Files From iPhone to Mac</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-your-gameplay-overcoming-lags-in-warfare/"><u>Elevating Your Gameplay: Overcoming Lags in Warfare</u></a></li>
<li><a href="https://fox-http.techidaily.com/elevating-your-unbox-sessions-secrets-for-more-views-and-likes-on-tiktok/"><u>Elevating Your Unbox Sessions  Secrets for More Views and Likes on TikTok</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-pc-sounds-with-windows-11s-mixer-feature/"><u>Enhance PC Sounds with Windows 11'S Mixer Feature</u></a></li>
<li><a href="https://android-location.techidaily.com/for-people-wanting-to-mock-gps-on-infinix-hot-30-5g-devices-drfone-by-drfone-virtual/"><u>For People Wanting to Mock GPS on Infinix Hot 30 5G Devices | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-controlling-windows-11s-content-filter/"><u>Guide: Controlling Windows 11’S Content Filter</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-how-to-deactivate-amdnvidia-vr-boosting/"><u>Guide: How to Deactivate AMD/Nvidia VR Boosting</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-forgot-locked-iphone-6-plus-password-learn-the-best-methods-to-unlock-by-drfone-ios/"><u>In 2024, Forgot Locked iPhone 6 Plus Password? Learn the Best Methods To Unlock</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-change-your-sim-pin-code-on-your-infinix-hot-40-phone-by-drfone-android/"><u>In 2024, How To Change Your SIM PIN Code on Your Infinix Hot 40 Phone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-fix-locked-apple-id-from-apple-iphone-6s-plus-by-drfone-ios/"><u>In 2024, How to Fix Locked Apple ID from Apple iPhone 6s Plus</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-nokia-105-classic-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your Nokia 105 Classic Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-send-and-fake-live-location-on-facebook-messenger-of-your-poco-c55-drfone-by-drfone-virtual-android/"><u>In 2024, How to Send and Fake Live Location on Facebook Messenger Of your Poco C55 | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-mastering-the-microscope-effect-for-enhanced-video-conferencing/"><u>In 2024, Mastering the Microscope Effect for Enhanced Video Conferencing</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-recommended-best-applications-for-mirroring-your-realme-narzo-60-pro-5g-screen-drfone-by-drfone-android/"><u>In 2024, Recommended Best Applications for Mirroring Your Realme Narzo 60 Pro 5G Screen | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-the-comprehensive-blueprint-for-capturing-whatsapp-calls/"><u>In 2024, The Comprehensive Blueprint for Capturing WhatsApp Calls</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-file-restoration-top-8-techniques-for-windows/"><u>Mastering File Restoration: Top 8 Techniques for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-internet-connection-league-of-legends-on-windows/"><u>Mastering Internet Connection: League of Legends on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-fixing-windows-11s-5ghz-connectivity/"><u>Mastering the Art of Fixing Windows 11'S 5GHz Connectivity</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-device-id-extraction-techniques-for-windows-users/"><u>Mastery of Device ID Extraction Techniques for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-freeze-flaws-in-adobes-pc-artist-suite/"><u>Mending Freeze Flaws in Adobe's PC Artist Suite</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-nitpicking-colors-8-tips-for-a-neutral-desktop/"><u>Navigating Nitpicking Colors: 8 Tips for a Neutral Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11s-s-mode-is-it-worth-considering/"><u>Navigating Windows 11'S 'S Mode': Is It Worth Considering?</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-setup-google-play-on-windows-11/"><u>Quick Setup: Google Play on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/recover-hidden-5ghz-link-in-windows-11-using-these-fixes/"><u>Recover Hidden 5GHz Link in Windows 11 Using These Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-could-not-create-vm-problems-in-microsoft-os/"><u>Remedying 'Could Not Create VM' Problems in Microsoft OS</u></a></li>
<li><a href="https://windows11.techidaily.com/resuscitate-stalled-excel-performance-in-windows-environment/"><u>Resuscitate Stalled Excel Performance in Windows Environment</u></a></li>
<li><a href="https://extra-tips.techidaily.com/salty-sessions-captured-best-cams-for-surfers/"><u>Salty Sessions Captured - Best Cams for Surfers</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-language-input-change-keyboard-layouts-in-win-11/"><u>Simplifying Language Input: Change Keyboard Layouts in Win 11</u></a></li>
<li><a href="https://fix-guide.techidaily.com/solved-warning-camera-failed-on-vivo-y27s-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Solved Warning Camera Failed on Vivo Y27s | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-to-extending-windows-1011-contextual-commands/"><u>Step-by-Step Guide to Extending Windows 10/11 Contextual Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-solve-missing-dll-rockalldlldll-error/"><u>Steps to Solve Missing DLL: Rockalldll.dll Error</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-windows-update-fixes-for-error-0x800736cc/"><u>Streamlining Windows Update Fixes for Error 0X800736CC</u></a></li>
<li><a href="https://windows11.techidaily.com/taskers-edge-enigma-hidden-processes/"><u>Tasker's Edge Enigma: Hidden Processes?</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11s-printer-interface-max-48-chars/"><u>Unlocking Windows 11'S Printer Interface (Max 48 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/unplugged-no-more-six-methods-to-restore-functioning-network-hardware-on-your-pc/"><u>Unplugged No More: Six Methods to Restore Functioning Network Hardware on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/utilizing-windows-widgets-for-real-time-resource-tracking/"><u>Utilizing Windows Widgets for Real-Time Resource Tracking</u></a></li>
<li><a href="https://extra-information.techidaily.com/vivid-visions-essential-online-sources-for-laps-screen-decor/"><u>Vivid Visions  Essential Online Sources for Laps Screen Decor</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/what-pokemon-evolve-with-a-dawn-stone-for-honor-90-pro-drfone-by-drfone-virtual-android/"><u>What Pokémon Evolve with A Dawn Stone For Honor 90 Pro? | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/why-virtual-reality-lack-of-content-2023-update/"><u>Why Virtual Reality Lack of Content? -2023 Update</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-and-discord-fixing-the-deadly-js-error-quickly/"><u>Win 11 and Discord: Fixing The Deadly JS Error Quickly</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/xchange-your-mind-with-non-sharex-insights/"><u>XChange Your Mind with Non-ShareX Insights</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>