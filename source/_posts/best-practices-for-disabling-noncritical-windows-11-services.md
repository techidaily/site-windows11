---
title: Best Practices for Disabling Noncritical Windows 11 Services
date: 2024-07-03T11:18:19.143Z
updated: 2024-07-04T11:18:19.143Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Best Practices for Disabling Noncritical Windows 11 Services
excerpt: This Article Describes Best Practices for Disabling Noncritical Windows 11 Services
keywords: Win11 Service Control,Disable Noncritical Servs,Optimize Win Serv Levels,Streamline Win 11 Setup,Critical Windows Services,Reduce Win11 Clutter,Manage Win Service Limits
thumbnail: https://thmb.techidaily.com/7e475b588f2cf5836119cf29eeb77a68a0d6cc175af9626b84f7c3d068d74a0f.jpg
---

## Best Practices for Disabling Noncritical Windows 11 Services

 Windows 11 is notably superior to Windows 10\. From the modern start menu to widgets and icons, everything enhances your Windows experience. However, you may encounter performance issues at times.

 One of the main reasons might be the plethora of unnecessary Windows services running constantly. To fix this, you need to disable some unnecessary Windows services.

 In this article, we'll look over all those Windows 11 services that may contribute to slow performance and how you can disable them.

## How to Disable a Windows Service

 Certain Windows services often consume a severe amount of system resources. They operate continuously in the background, causing stutters and lags. But how can you find out which Windows 11 services to disable? And, before that, how to disable a Windows service?

 We advise creating a restore point before modifying any service settings. For the steps, refer to our guide on [how to use a restore point on Windows 11](https://www.makeuseof.com/windows-11-create-restore-point/).

 Below are the steps to disable a Windows 11 service:

1. [Open the Services app](https://www.makeuseof.com/windows-11-open-services-app/) and right-click on the service name you wish to disable.
2. From the context menu, select the **Properties** option.  
![Windows Services Context Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-services-context-menu.jpg)
3. Find the **Startup type** dropdown menu, and select **Disabled**.  
![Windows Services Startup Type Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-services-startup-type-option.jpg)

 Now that you understand how to disable a service, the main question is, which Windows 11 services are safe to disable?

 For that, we've listed all the services below in alphabetical order. Make sure to read about each service before disabling it! If you mistakenly disable a service, you can re-enable it from the same **Properties** window.

## 1\. AllJoyn Router Service

 The AllJoyn Router service enables you to connect your [IoT devices](https://www.makeuseof.com/tag/what-is-internet-of-things/) to your computer.

 If you don't prefer using or connecting smart devices like digital home security solutions, smart lights, or smart TVs with your Windows, there's no reason to keep this service enabled.

## 2\. AssignedAccessManager Service

 You might not be aware, but Windows has a feature called [Kiosk mode](https://www.makeuseof.com/windows-11-kiosk-mode/). This feature allows you to place restrictions on your computer. More specifically, it empowers you to force all users to access only a single app on your PC.

 The AssignedAccessManager service helps in setting up the kiosk mode. You may never need the kiosk mode if you don't use a public-facing computer. So, disable it using the steps outlined in the previous section.

## 3\. BitLocker Drive Encryption Service

 BitLocker is beneficial for encrypting your hard drive. However, you might not use it regularly due to its low popularity among Windows users. If so, you can safely disable the BitLocker Drive Encryption service.

 Remember, disabling this service will prevent you from using BitLocker and any other related functionality!

## 4\. Bluetooth services

 Bluetooth devices are on trend; ranging from earbuds and headphones to gaming controllers, wireless mice, and keyboards–all such devices make our work easier.

 However, if you prefer the old USB days, there's nothing wrong with that. If you have never used or don't plan to use any bluetooth device in the future, disable these services:

* **Bluetooth Audio Gateway Service**
* **Bluetooth Support Service**
* **Bluetooth User Support Service**

![All Windows Bluetooth Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-bluetooth-services.jpg)

## 5\. Connected User Experiences and Telemetry

 The Connected User Experiences and Telemetry service is responsible for sending your usage and diagnostic data to Microsoft servers. So, if this service is enabled on your computer, Microsoft may easily track the apps you use, the searches you make on the search bar, and more.

 Overall, no one enjoys being tracked, especially those who value privacy. Therefore, disable this service now to stop Microsoft from handling your user data.

## 6\. Delivery Optimization

 Windows updates, especially major ones, take a considerable time to download. The slow download speed may be due to your internet connection or other factors.

 The Delivery Optimization service does precisely what its name suggests: it improves the download speed of Windows updates and Microsoft apps by sharing bandwidth with your nearby devices.

 Don't be too excited, as it only works in the case of a local network or deployment setup! If you're not part of any local network, disable the Delivery Optimization service.

## 7\. Diagnostic Services

 Whenever something goes wrong on Windows, the first step the internet suggests is to [use Windows troubleshooters](https://www.makeuseof.com/windows-11-troubleshooters/). But, if you never bother to use any of them and fix the issues on your own, there are several diagnostic services that you can disable.

 Here are the services to disable if you don't prefer running any Windows troubleshooter:

* **Diagnostic Execution Service**
* **Diagnostic Policy Service**
* **Diagnostic Service Host**
* **Diagnostic System Host**

![All Windows Diagnostic Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-diagnostic-services.jpg)

## 8\. Geolocation Service

 As its name suggests, this service provides location-related data to Windows apps when needed. You can disable your location data if you don't want to share it due to privacy concerns.

 Once the Geolocation service is disabled, you won't be able to share your location using any Windows app or web browser.

## 9\. Netlogon

 The Netlogon service is only for domain networks. It means this service is only helpful in authenticating users within a domain environment. However, if your computer isn't part of such a network (as in the case of personal computers), disabling this service is a better option.

## 10\. Optimize Drives

 If you have ever defragmented your hard drive, you may be aware of its scheduled defragmentation feature. Simply put, this service handles routine defragmentation and optimization of your drives.

 So, if you like to [defrag your hard drive manually](https://www.makeuseof.com/defrag-hard-disk-drive-windows-11/) or if your system comes equipped with an SSD (which doesn't benefit from defragmentation), you might consider turning it off.

## 11\. Parental Controls

 This service is only helpful if you are a parent. With Parental Controls enabled, you can [restrict your children's computer use](https://www.makeuseof.com/windows-11-parental-controls-guide/). It mainly manages restrictive controls, including website and app restrictions.

 Now that you understand its usage, you can decide whether to disable the Parental Controls service.

## 12\. Phone Service

 The Phone Service handles connections between your computer and mobile devices. If you disable it, you may lose some mobile device syncing capabilities.

## 13\. Print Spooler

 The Print Spooler service is of great importance for printer users. It's the core service that allows you to print anything from your computer. If this service stops or gets disabled inadvertently, your printer-related tasks will not function.

 Therefore, proceed with caution if you plan to disable it! Remember, disabling this service will prevent you from using printers connected to your computer.

## 14\. Remote Desktop services

 Windows 11 includes a helpful feature called [Remote Desktop Connection](https://www.makeuseof.com/how-to-set-up-microsofts-remote-desktop-connection/). By using it, you can connect to any remote computer on the same network. And the Remote Desktop services handle the backend when you try to establish a connection.

 If you don't connect to remote desktop sessions, you can disable all its related services, which are:

* **Remote Desktop Configuration**
* **Remote Desktop Services**
* **Remote Desktop Services UserMode Port Redirector**

![All Windows Remote Desktop Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-remote-desktop-services.jpg)

## 15\. Sensor Service

 The Sensor service manages integration with sensors like GPS and ambient light sensors. If your device doesn't come equipped with such sensors or if you don't use applications that need sensor data, disabling this service is a good decision.

## 16\. Smart Card services

 Smart Cards are mainly for corporate users who sometimes need them for authentication on Windows devices. However, if you're a typical Windows user who prefers using a keyboard for login, you can disable the following smart card services:

* **Smart Card**
* **Smart Card Device Enumeration Service**
* **Smart Card Removal Policy**

![All Windows Smart Card Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-smart-card-services.jpg)

## 17\. Windows Biometric Service

 The Windows Biometric service is only helpful if you are using a laptop. It just enables the fingerprint to unlock functionality on laptops. Other than that, there is no use for this service. So, if you're using a PC or don't prefer using biometric unlock, you can disable it safely.

## 18\. Windows Error Reporting Service

 Just like other operating systems, Windows is not perfect. You may encounter an error or two after a Windows update.

 The Windows Error Reporting service automatically captures the event whenever you face an error on Windows. It then generates information about the error and sends it to Microsoft for further diagnosis.

 Disabling it is entirely safe, so feel free to turn it off from the Services app.

## 19\. Work Folders

 Work Folders are generally used in large organizations where people can store their local work-related files on a centralized server. They can then sync such files between work and personal computers. In short, Work Folders are an alternative to other file-syncing solutions.

 So, if your organization doesn't use this feature, the Work Folders service is safe to disable on Windows.

## 20\. Xbox Services

 Xbox services together offer the best possible experience when using an Xbox gaming console. These services handle Xbox Live features like saved game files, multiplayer access, and achievements, to name a few.

 If you don't use an Xbox or need any such feature in games, you can safely disable all the following services:

* **Xbox Accessory Management Service**
* **Xbox Live Auth Manager**
* **Xbox Live Game Save**
* **Xbox Live Networking Service**

![All Windows Xbox Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-xbox-services.jpg)

## Get Rid of Unwanted Windows 11 Services

 All the services we've mentioned above are safe to disable. However, always remember to create a restore point before making any changes, and be cautious when disabling services that might have specific use cases. For example, don't disable Bluetooth services if you prefer using a Bluetooth device. Similarly, if you use the fingerprint unlock on your laptop, don't modify the Windows Biometric service.

 One of the main reasons might be the plethora of unnecessary Windows services running constantly. To fix this, you need to disable some unnecessary Windows services.

 In this article, we'll look over all those Windows 11 services that may contribute to slow performance and how you can disable them.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/simple-steps-to-enable-windows-11s-search-feature-in-task-manager/"><u>Simple Steps to Enable Windows 11'S Search Feature in Task Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-11-unstartable-apps-and-error-0xc000003e/"><u>Fixing Windows 11: Unstartable Apps and Error 0xC000003E</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-interrupt-at-breakpoint-issue-in-windows-debugging/"><u>Dealing with Interrupt at Breakpoint Issue in Windows Debugging</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-xp-error-code-0x80300024/"><u>Navigating Windows XP Error Code: 0X80300024</u></a></li>
<li><a href="https://windows11.techidaily.com/file-finder-simplicity-windowed-explorer-reduction-technique/"><u>File Finder Simplicity: Windowed Explorer Reduction Technique</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-powershell-access-control-settings/"><u>Optimizing PowerShell Access Control Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/slashing-gpu-energy-on-desktop-window-manager/"><u>Slashing GPU Energy on Desktop Window Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-down-energy-waste-without-slowing-down-games/"><u>Cutting Down Energy Waste Without Slowing Down Games</u></a></li>
<li><a href="https://windows11.techidaily.com/circumventing-endless-credential-entry-alerts-in-windows/"><u>Circumventing Endless Credential Entry Alerts in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/1719252317464-understanding-and-fixing-the-common-problem-of-wwinplusp-not-working/"><u>Understanding and Fixing the Common Problem of WWin+P Not Working</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-turn-off-google-location-to-stop-tracking-you-on-samsung-galaxy-xcover-7-drfone-by-drfone-virtual-android/"><u>How to Turn Off Google Location to Stop Tracking You on Samsung Galaxy XCover 7 | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-calculating-costs-in-youtube-advertising-campaigns/"><u>2024 Approved  Calculating Costs in YouTube Advertising Campaigns</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/maximize-video-visibility-on-facebook-via-youtube/"><u>Maximize Video Visibility on Facebook via YouTube</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-this-article-talks-about-if-the-windows-movie-maker-available-and-if-yes-then-how-you-can-download-it-and-so-on-it-further-comprises-an-alternative-/"><u>Updated This Article Talks About if the Windows Movie Maker Available and if Yes, Then How You Can Download It and so On. It Further Comprises an Alternative to the Same to Create Videos</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-vivo-x-flip-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Location is Not Updating and How to Fix On Vivo X Flip | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-changeadd-location-filters-on-snapchat-for-your-realme-note-50-drfone-by-drfone-virtual-android/"><u>How to Change/Add Location Filters on Snapchat For your Realme Note 50 | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-closing-powerhouses-free-top-6-video-closers/"><u>In 2024, Closing Powerhouses  Free Top 6 Video Closers</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-mastering-ps4-game-capture-via-obs-studio/"><u>In 2024, Mastering PS4 Game Capture via OBS Studio</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/6-essential-audio-converters-for-music-lovers-and-more/"><u>6 Essential Audio Converters for Music Lovers and More</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/adding-music-to-your-instagram-snapshots-stickers-and-more-for-2024/"><u>Adding Music to Your Instagram Snapshots  Stickers and More for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>