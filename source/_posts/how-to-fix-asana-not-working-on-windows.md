---
title: How to Fix Asana Not Working on Windows
date: 2024-06-25T12:22:12.799Z
updated: 2024-06-26T12:22:12.799Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix Asana Not Working on Windows
excerpt: This Article Describes How to Fix Asana Not Working on Windows
keywords: Fix Asana Windows Error,Windows Asana Glitch Solve,Asana Fix On PC,Resolve Asana Crash Windows,Asana Sync Issue Windows,Windows Asana Malfunction,Stop Asana Freeze Windows
thumbnail: https://thmb.techidaily.com/8224c2eaffde473b7b29c4172387e354997fe7d2a767ebc186d1a15d8b28408a.jpg
---

## How to Fix Asana Not Working on Windows

 Asana is one of the leading project and task management programs. You can keep track of all the projects and actively collaborate with your team easily with it.

 But what happens when Asana doesn't load on your Windows PC? It can be irritating, especially when you have to review your assigned tasks and complete the pending work.

 Here, we'll explore various solutions to fix the Asana not working or loading issues on Windows.

## 1\. Start by Applying Quick Fixes

 Below are some quick troubleshooting methods to try if Asana is not loading correctly for you:

* **Check Asana's web client:** If you're experiencing issues with the Asana Windows app, try accessing it through your web browser. If it works there, you'll know that the problem is with the Windows app and not Asana's server.
* **Troubleshoot your network connection:** Asana requires a stable network connection to work properly. Restart your router or [troubleshoot your Windows network settings](https://www.makeuseof.com/windows-11-windows-cant-connect-to-this-network-error-fix/) once if your internet connection is too weak.
* **Hard restart the Asana app:** If Asana is stuck on the loading screen, try a hard restart. To do this, open Asana first, right-click anywhere on the loading screen and select the **Reload** option.  
![Asana Reload Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/asana-reload-option.jpg)

 These basic steps can often resolve common Asana issues. However, if you're still facing loading issues, keep reading to try some advanced methods.

## 2\. Clear the Asana Cache Files

 Like other Windows apps, Asana creates cache files to store temporary data. Sometimes, the cache files become corrupted due to malware or unexpected system shutdowns. This ultimately causes Asana to slow down or crash on startup. But how can you fix the Asana not working issues, then? In this case, clearing the stored cache files can often solve this.

 Before proceeding, close Asana if it's already running on your device. You can use the system tray or [open the Windows Task Manager](https://www.makeuseof.com/how-to-access-task-manager-on-windows-11/) to close the Asana app.

 Here's how you can clear Asana's cache files on Windows:

1. Press the **Win + R** keys to launch the Run app.
2. Type **%appdata%/asana/cache** in the textbox and click **Ok**.
3. On the File Explorer window, select the **Cache\_Data** folder.  
![Asana Cache Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/asana-cache-folder.jpg)
4. Press the **Del** key or click the **Delete** icon to remove the cache files.
5. After clearing the cache, re-open Asana to check the loading issue.

 Clearing the cache will force the app to reconnect to Asana's server. If this is not working for you, proceed to the next step.

## 3\. Update Asana to the Latest Version

 Asana's development team often releases updates to fix known bugs. If you're using an outdated version of Asana, you're missing some essential features and, most importantly, bug fixes. So, try updating the app to the latest version to solve the loading issues.

 Follow the steps below to update your Asana app:

1. Launch Asana from the start menu and minimize it.
2. [Open the Run app](https://www.makeuseof.com/windows-open-run-command-dialog-box/) and type **%localappdata%/asana** in the text field.  
![Run App On Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-app-on-windows.jpg)
3. Click the **Ok** button to open Windows File Explorer.
4. Double-click the **Update.exe** file. Wait for a few seconds, and the app will automatically close.  
![Asana Local AppData Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/asana-local-appdata-folder.jpg)
5. Now, go back to the Asana app. It should prompt you with a text message saying, "**A new version of the Asana app is available.**".
6. Click the **Restart** button on the pop-up to update Asana.

## 4\. Run the Asana Connectivity Test

 Sometimes, due to unknown reasons, your network may be unable to connect to Asana's servers. To handle such cases, you can visit the [Asana Help Test](https://connectivity-test.asana.com/) website.

 Wait for a while and check the **WebSocket connection** status. If it says **Success**, then there's no need to worry. If you're getting a **Failed** or **Prohibited** status, contact [Asana's Support team](https://asana.com/support) with a screenshot of the diagnostics.

![Asana Diagnostics Overview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/asana-diagnostics-overview.jpg)

## 5\. Change Your Default DNS Server

 DNS (Domain Name System) helps your browser open any website that you type on the search bar. Surprisingly, the DNS server you're using can be the root source of your problem.

 When a DNS server fails, it generally starts giving you network errors. So, changing the default DNS server to another might be a good idea in such cases. If you've never done it before, check [how to change the DNS server on Windows](https://www.makeuseof.com/change-dns-settings-windows-11/) for a step-by-step guide.

 When it comes to public DNS servers, Cloudflare and Google grab the top spot. If you want to choose one, view our [Cloudflare and Google's DNS comparison](https://www.makeuseof.com/google-dns-vs-cloudflare-dns/) article to know which will suit you.

 On the other hand, if you're using a private DNS provider, set a custom rule for Asana. You can do so by adding the below domains in whitelist or bypass mode:

* **app.asana.com**
* **sync.app.asana.com**

![ControlD Custom Rules](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/controld-custom-rules.jpg)

## 6\. Allow Asana Through the Firewall

 A firewall comes into use when you want to prevent unauthorized network users from misusing resources. The default Windows firewall keeps your system safe but can block some necessary services (in rare cases).

 If you're sure that your firewall is causing trouble, try whitelisting the Asana app in its settings.

 Here's how to fix the firewall issue on your computer:

1. Open Windows search and type **Allow an app through Windows Firewall**.
2. Double-click on the best match and click the **Change settings** button.
3. In the list of apps, search for **Asana**. If you can't find it, you may need to add it manually by selecting **Add an app**.
4. Once you add Asana, ensure it has permission to pass through the firewall. Tick the **Private** and **Public** checkboxes depending on your network type.  
![Asana Firewall Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/asana-firewall-settings.jpg)

## 7\. Reinstall the Asana App

 If you're still struggling to get Asana running, the final solution is to reinstall Asana.

 Reinstalling means you will uninstall the app first and then install it again. Don't worry about losing your data, as Asana continuously syncs your data across all its supported platforms.

 Here are the steps to follow to reinstall the Asana app:

1. Open the Windows Settings app and navigate to **Apps > Installed apps**.
2. Find **Asana** in the list and click the three-dot menu.
3. Click the **Uninstall** option from the context menu to uninstall Asana.  
![Installed App Settings On Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/installed-app-settings-on-windows.jpg)
4. After uninstalling, visit [Asana’s official website](https://asana.com/download) to download the latest version of the app.
5. Once the download is complete, run the installer or setup file to install Asana.

 A fresh install will remove all the old files from your computer and replace them with new ones. Moreover, by reinstalling Asana, you can troubleshoot almost all issues related to the Asana app. So, don't fear to give it a try once!

## Get Back Your Full Asana Experience on Windows

 By following the steps outlined in this guide, you should be able to resolve the loading issues and enjoy a smooth experience. However, if you're still out of luck, the main problem may be your Asana account. In this matter, we recommend reaching out to their tech support team.

 But what happens when Asana doesn't load on your Windows PC? It can be irritating, especially when you have to review your assigned tasks and complete the pending work.

 Here, we'll explore various solutions to fix the Asana not working or loading issues on Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>