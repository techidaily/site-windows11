---
title: Bridging the Gap Between Wi-Fi and Ethernet in Windows
date: 2024-07-11T21:12:46.866Z
updated: 2024-07-12T21:12:46.866Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bridging the Gap Between Wi-Fi and Ethernet in Windows
excerpt: This Article Describes Bridging the Gap Between Wi-Fi and Ethernet in Windows
keywords: Wi-Fi to Ethernet Conversion,Network Bridge for PCs,Windows Ethernet Integration,Combining Wi-Fi & Ethernet,Efficient Wireless to Wired Link,Enhancing Win Connectivity,Unifying Internet Streams in Windows
thumbnail: https://thmb.techidaily.com/1fcdc6cbb778104aee870cc96ea727883cbb745be14bb05420507854521a636d.jpg
---

## Bridging the Gap Between Wi-Fi and Ethernet in Windows

 You can have your Windows computer connected to Wi-Fi and Ethernet simultaneously, but the system won't use both connections at the same. Windows automatically configures the network adapter order priority to provide the best Internet connection via Ethernet or Wi-Fi.

 However, if you have multiple ISP connections or have a local media server, you can configure your Windows laptop to use Wi-Fi and Ethernet simultaneously. To do this, you must disable packet priority for both Wi-Fi and Ethernet network adapter.

## Why You May Need to Use Both the Wi-Fi and Ethernet Connections Simultaneously

 While you may not get an additional speed advantage when using the same ISP for your Wi-Fi and Ethernet, you can have both connections up and running as a backup for critical Internet-dependent services. Also, if you have access to multiple ISP connections, you can [merge multiple connections to increase your internet speed](https://www.makeuseof.com/how-to-merge-internet-connections/) .

 Additionally, it is also useful if you have a local server and want to be connected to both the Internet and the local server simultaneously. You can connect to the local media server via Ethernet and access the internet over Wi-Fi without dropping the connection.

 On the flip side, there are chances of packet loss due to duplicate packets being transmitted via both the Wi-Fi and Ethernet connection. Lower-end routers may also notice decreased speed due to increased load on your network device. This is part of the reasons [why you may want to replace your ISP's router](http://www.makeuseof.com/tag/reasons-replace-isp-router/) .

## How to Configure Windows to Use Wi-Fi and Ethernet Connections Simultaneously

 Since Windows automatically prioritizes the network adapter to use only one adapter at a time, you'll need to disable the packet priority option in the network adapter's network configuration. Doing so will allow Windows to use multiple connections simultaneously.

To disable packet priority and VLAN on Windows:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel** .
3. Next, go to**Network and Internet** and click on**Network and Sharing Center.**  
![control panel network change adapter settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/control-panel-network-change-adapter-settings.jpg)
4. In the left pane, click on**Change adapter settings.**
5. Right-click on your**Ethernet network adapter** and select**Properties** . Alternatively, double-click on the**Ethernet adapter** and then click on**Properties** .  
![ethernet properties configure networking control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/ethernet-properties-configure-networking-control-panel.jpg)

1. In the**Networking** tab, click the**Configure** button.
2. Next, open the**Advanced** tab.
3. Select**Priority and VLAN** under the**Property** section.
4. Click the drop-down under**Value** .  
![priority vlan disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/priority-vlan-disabled.jpg)
5. Select**Priority and VLAN Disabled.**
6. Click**OK** to save the changes.
7. Next, you need to repeat the steps for your Wi-Fi adapter. So, open Properties for your Wi-Fi adapter and set its**Priority and VLAN** value to**Priority & VLAN Disabled** .
8. Click**OK** to save the changes.

 With the network adapter priority option disabled, Windows will now use both network connections simultaneously.

## How to Set the Network Priority for Wi-Fi or Ethernet Using Interface Metric

 By default, Windows uses an automatic metric to detect and use the best network connectivity option available. However, if you need, you can manually set network priority to force Windows to use Ethernet or Wi-Fi as the preferred connectivity option.

To change network priority on Windows:

1. Press**Win + R** to open**Run** .
2. Type**ncpa.cpl** and click**OK** .  
![ncpa cpl open control panel network and sharing center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/ncpa-cpl.jpg)
3. Right-click on your Ethernet adapter and select**Properties** . If you want to prioritize your Wi-Fi adapter, choose that instead.
4. Next, select**Internet Protocol Version 4 (TCP/IPv4)** and click on**Properties** .  
![tcp ip v4 properties control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tcp-ip-v4-properties-control-panel.jpg)
5. Click the**Advanced** button in the**Properties** dialog.
6. Next, uncheck**Automatic metric** and type**5** in the**Interface metric** field.
7. Click**OK** on all the open windows to save the changes.
8. Note that if you use Internet Protocol Version 6 (IPv6) protocol, you’ll need to assign an interface metric for it as well.

 With the changes saved, Windows will prioritize your preference when multiple network adapters are connected to your computer. To undo the changes, open**Advanced TCP/IP Settings** and check the**Automatic** **metric** option. Then, click**OK** to save the changes.

## Make Your Computer Use Your Wi-Fi and Ethernet at the Same Time

 You can configure the network adapter on your computer to use both Wi-Fi and Ethernet connection simultaneously. While it has many advantages, it won't increase your Internet speed. Instead, you’ll need multiple Internet connections powering your Wi-Fi and Ethernet networks to see increased speed.

 Alternatively, if you have multiple Wi-Fi connections at home or office, you can configure your Windows computer to automatically switch to the strongest Wi-Fi network available when you move around.


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
<li><a href="https://windows11.techidaily.com/breaking-grayed-out-delete-feature-for-windows-11-pins/"><u>Breaking Grayed-Out Delete Feature for Windows 11 PINs</u></a></li>
<li><a href="https://windows11.techidaily.com/12-top-changes-to-expect-with-windows-11s-latest-release/"><u>12 Top Changes to Expect with Windows 11'S Latest Release</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcoming-kodi-freeze-in-new-win11-release/"><u>Overcoming Kodi Freeze in New Win11 Release</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-1110-malwarebytes-functional-flaws/"><u>Addressing Windows 11/10 Malwarebytes Functional Flaws</u></a></li>
<li><a href="https://windows11.techidaily.com/11-fixes-if-windows-11-cant-detect-a-wi-fi-network/"><u>11 Fixes if Windows 11 Can’t Detect a Wi-Fi Network</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-innovating-for-success-metaverse-sales-strategies/"><u>[Updated] Innovating for Success  Metaverse Sales Strategies</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-2024-approved-master-your-mobile-voice-explore-7-premier-android-tools-for-superior-call-quality/"><u>Updated 2024 Approved Master Your Mobile Voice Explore 7 Premier Android Tools for Superior Call Quality</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-expert-recommendations-prime-apps-for-mac-video-recording-for-2024/"><u>[Updated] Expert Recommendations  Prime Apps for Mac Video Recording for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/10-overlooked-windows-11-aesthetic-themes/"><u>10 Overlooked Windows 11 Aesthetic Themes</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-how-to-measure-the-performance-of-igtv-videos-for-2024/"><u>[Updated] How to Measure the Performance of IGTV Videos for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-software-generations-windows-7-key-for-11-boot/"><u>Bridging Software Generations: Windows 7 Key for 11 Boot</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-store-failure-code-0x800704cf/"><u>Addressing Windows Store Failure Code 0X800704CF</u></a></li>
<li><a href="https://windows11.techidaily.com/1719266225421-eradicate-black-screen-on-win11-top-easy-fixes/"><u>Eradicate Black Screen on Win11: Top Easy Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-faulty-display-settings-via-nonfunctional-fn-button-in-windows-11/"><u>Addressing Faulty Display Settings via Nonfunctional Fn Button in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/10-easy-steps-for-a-working-windows-mouse/"><u>10 Easy Steps for a Working Windows Mouse</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-the-workflow-of-windows-11s-recovery-features/"><u>Breaking Down the Workflow of Windows 11'S Recovery Features</u></a></li>
<li><a href="https://windows11.techidaily.com/10-ways-to-fix-onedrive-sync-issues-on-windows-11/"><u>10 Ways to Fix OneDrive Sync Issues on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-steam-vac-denial-for-gaming-sessions/"><u>Addressing Steam VAC Denial for Gaming Sessions</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-delete-gmail-account-withwithout-password-on-vivo-v29e-by-drfone-android/"><u>In 2024, Delete Gmail Account With/Without Password On Vivo V29e</u></a></li>
<li><a href="https://windows11.techidaily.com/1719208597283-unravel-complex-windows-issues-help-at-hand/"><u>Unravel Complex Windows Issues: Help at Hand</u></a></li>
<li><a href="https://windows11.techidaily.com/big-byte-in-mini-pcs-but-barely-booming/"><u>Big Byte in Mini PCs, But Barely Booming</u></a></li>
<li><a href="https://windows11.techidaily.com/1719297453407-mastery-overprint-how-to-reactivate-the-missing-windows-functionality/"><u>Mastery Overprint: How to Reactivate the Missing Windows Functionality</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-app-on-vivo-s17-pro-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to Recover Deleted Photos from Android Gallery App on Vivo S17 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/1719256266387-repairing-email-notification-shortcom-written-exercise/"><u>Repairing Email Notification Shortcom Written Exercise</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-expiring-software-license-caution-in-windows-1011/"><u>Avoiding Expiring Software License Caution in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/1719293537225-resurrect-your-chrome-on-win11-with-ease/"><u>Resurrect Your Chrome on Win11 with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/1719266282483-combatting-common-windows-11-mail-errors-get-your-email-back-now/"><u>Combatting Common Windows 11 Mail Errors - Get Your Email Back Now</u></a></li>
<li><a href="https://windows11.techidaily.com/add-emulators-to-playnite-a-windows-guide/"><u>Add Emulators to Playnite: A Windows Guide</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-instant-screen-capture-pro-chrome/"><u>[Updated] Instant Screen Capture Pro (Chrome)</u></a></li>
<li><a href="https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-honor-x9a-drfone-by-drfone-virtual-android/"><u>Thinking About Changing Your Netflix Region Without a VPN On Honor X9a? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/1719271997711-enable-high-contrast-mode-go-to-ease-of-access-settings-and-enable-high-contrast-mode-if-it-improves-visibility/"><u>Enable High Contrast Mode: Go to 'Ease of Access' Settings and Enable High Contrast Mode if It Improves Visibility.</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-enhancing-discord-communication-with-tts/"><u>[Updated] In 2024, Enhancing Discord Communication with TTS</u></a></li>
<li><a href="https://windows11.techidaily.com/1719356403176-cross-language-build-system-setup/"><u>Cross-Language Build System Setup:</u></a></li>
<li><a href="https://windows11.techidaily.com/1719207064707-ifas-hottest-laptops-unveiled/"><u>IFA's Hottest Laptops Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-through-file-download-blockades-on-windows-11/"><u>Breaking Through File Download Blockades on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/best-fit-the-ideal-vms-that-complement-your-windows-11-pc/"><u>Best Fit: The Ideal VMs That Complement Your Windows 11 PC</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-from-flv-to-youtube-stardom-top-10-video-conversion-tools-reviewed-for-2024/"><u>[Updated] From FLV to YouTube Stardom  Top 10 Video Conversion Tools Reviewed for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-capturing-quality-video-on-macbook-for-2024/"><u>[Updated] Capturing Quality Video on MacBook for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/bringing-silent-screens-to-life-tricks-for-win1011-users/"><u>Bringing Silent Screens to Life: Tricks for Win10/11 Users</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-direct-video-streaming-sending-fb-vids-straight-into-whatsapp/"><u>[Updated] In 2024, Direct Video Streaming  Sending FB Vids Straight Into WhatsApp</u></a></li>
<li><a href="https://windows11.techidaily.com/13-ways-to-open-the-windows-system-settings/"><u>13 Ways to Open the Windows System Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/1719267835321-reactivating-silenced-pc-speakers-easy-fixes-ahead/"><u>Reactivating Silenced PC Speakers – Easy Fixes Ahead!</u></a></li>
<li><a href="https://windows11.techidaily.com/arcade-mode-for-window-users-key-fixes-ahead/"><u>Arcade Mode for Window Users: Key Fixes Ahead!</u></a></li>
<li><a href="https://windows11.techidaily.com/best-video-splitters-and-editors-on-windows-systems/"><u>Best Video Splitters & Editors on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-clarity-with-these-budget-friendly-tools/"><u>Boost Clarity with These Budget-Friendly Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/10-must-have-microsoft-store-apps-for-a-new-windows-pc/"><u>10 Must-Have Microsoft Store Apps for a New Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/15-paths-to-recover-missing-windows-system-time-functionality/"><u>15 Paths to Recover Missing Windows System Time Functionality</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-improving-accessibility-with-on-screen-text-elements-on-youtube-videos/"><u>2024 Approved  Improving Accessibility with On-Screen Text Elements on YouTube Videos</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-architect-of-audiovisual-brilliance/"><u>In 2024, Architect of Audiovisual Brilliance</u></a></li>
<li><a href="https://windows11.techidaily.com/1719211883980-tackling-the-challenge-of-non-working-win-plus-printer-feature-in-windows/"><u>Tackling the Challenge of Non-Working Win + Printer Feature in Windows</u></a></li>
<li><a href="https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-realme-c55-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix the Error of Unfortunately the Process.com.android.phone Has Stopped on Realme C55 | Dr.fone</u></a></li>
</ul></div>
