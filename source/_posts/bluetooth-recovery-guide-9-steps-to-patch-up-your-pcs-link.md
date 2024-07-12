---
title: "Bluetooth Recovery Guide: 9 Steps to Patch Up Your PC's Link"
date: 2024-07-11T22:13:34.039Z
updated: 2024-07-12T22:13:34.039Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Bluetooth Recovery Guide: 9 Steps to Patch Up Your PC's Link"
excerpt: "This Article Describes Bluetooth Recovery Guide: 9 Steps to Patch Up Your PC's Link"
keywords: Bluetooth Repair Guide,Bluetooth Fix Tips,PC Link Restoration,Patching PC Bluetooth,PC Connectivity Troubleshooting,Reconnecting Bluetooth Devices,Bluetooth Error Resolution
thumbnail: https://thmb.techidaily.com/1fa3b9714516519d17cdc00ae160f98cb4b200553b264310d7d2980b9ce91d3e.jpg
---

## Bluetooth Recovery Guide: 9 Steps to Patch Up Your PC's Link

### Quick Links

* [Run the Appropriate Windows Troubleshooters](#run-the-appropriate-windows-troubleshooters)
* [Perform a Power Cycle](#perform-a-power-cycle)
* [Check the Quick Settings Panel](#check-the-quick-settings-panel)
* [Check Bluetooth Settings](#check-bluetooth-settings)
* [Configure the Bluetooth Support Service](#configure-the-bluetooth-support-service)
* [Update or Reinstall Your Bluetooth Drivers](#update-or-reinstall-your-bluetooth-drivers)
* [Disable and Re-Enable the Problematic USB Driver](#disable-and-re-enable-the-problematic-usb-driver)
* [Run SFC and DISM Scans](#run-sfc-and-dism-scans)
* [Boot into Safe Mode](#boot-into-safe-mode)

 Has the Bluetooth option disappeared on your Windows 11 computer? This can happen for several reasons, including temporary glitches, damaged Bluetooth drivers, and issues with the Windows OS. If you're unsure about what caused the problem, here are some tips that will help.

## 1\. Run the Appropriate Windows Troubleshooters

 Windows troubleshooters are built-in utilities that can help you diagnose and resolve various system-level issues. You can run the Bluetooth troubleshooter and allow Windows to fix any common Bluetooth-related issues. Here’s how:

1. Press **Win + I** to launch the Settings app.
2. In the **System** tab, click **Troubleshoot**.
3. Select **Other troubleshooters**.
4. Click the **Run** button next to **Bluetooth**.  
![Bluetooth Troubleshooter on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Bluetooth-Troubleshooter-on-Windows-11.jpg)

 Windows will scan your computer for any issues and try to fix them. Additionally, you can run the Hardware and Devices troubleshooter to scan your computer for any hardware issues. To do so:

1. Press **Win + R** to open the Run dialog.
2. Type **msdt.exe -id DeviceDiagnostic** in the Open field and press **Enter**.
3. In the Hardware and Devices window, click **Next** and follow the on-screen instructions to run the troubleshooter.  
![Hardware and Devices Troubleshooter on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Hardware-and-Devices-Troubleshooter-on-Windows.jpg)

## 2\. Perform a Power Cycle

 Sometimes, the most effective solution is surprisingly simple. Performing a power cycle can resolve various issues with your Windows PC caused by temporary glitches. To perform a power cycle:

1. Turn off your computer and unplug it from the power source.
2. Press and hold the **power button** for 30 to 60 seconds to drain all the power that’s left on your device.
3. Leave your computer idle for a few minutes.
4. Connect your computer to the power supply, and then turn it back on.

## 3\. Check the Quick Settings Panel

 The [Quick Settings panel in Windows 11](http://www.makeuseof.com/windows-11-customize-quick-settings-menu/) provides access to various commonly used settings, including Bluetooth. If you can’t find the Bluetooth toggle in the Quick Settings panel, you might have removed it by mistake. Here’s how you can retrieve it.

1. Press **Win + A** to open the Quick Settings panel.
2. Click the **pencil icon** to edit the Quick Settings panel.
3. Click on **Add** and select **Bluetooth** from the list to add it to the panel.  
![Add Bluetooth to Quick Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Add-Bluetooth-to-Quick-Settings.jpg)

## 4\. Check Bluetooth Settings

 The Bluetooth icon may not appear on the taskbar or system tray if you have previously removed the icon. Here's how you can [pin the Bluetooth icon to the Windows taskbar](https://www.makeuseof.com/how-pin-bluetooth-icon-windows-10-taskbar/) again.

1. Open the **Start menu** and go to **Settings > Bluetooth & devices**.
2. Go to **Devices** and click on **More Bluetooth Settings**.
3. Tick the box that reads **Show the Bluetooth icon in the notification area**.
4. Hit **Apply,** followed by **OK**.  
![Bluetooth Settings Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Bluetooth-Settings-Window.jpg)

## 5\. Configure the Bluetooth Support Service

 Bluetooth Support Service is a small program that runs in the background to allow Bluetooth to function on Windows. Your Bluetooth issues could be because the service isn't running. Here’s how to fix it.

1. Press **Win + R** to open the Run dialog.
2. Type **services.msc** in the text field and press **Enter**.
3. Double-click on **Bluetooth Support Service** to open its properties.
4. Use the drop-down menu next to **Startup type** to select **Automatic**.
5. Hit **Apply** to save changes.  
![Bluetooth Support Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Bluetooth-Support-Service.jpg)

 Restart your PC one more time and check if the Bluetooth option appears.

## 6\. Update or Reinstall Your Bluetooth Drivers

 Malfunctioning or corrupt Bluetooth drivers on your PC could also be the source of the problem. If that seems to be the case, updating the Bluetooth driver should help.

1. Right-click on the **Start** icon and select **Device Manager** from the list.
2. Expand the **Bluetooth** section, right-click on the **Bluetooth adapter**, and select **Update driver**.
3. Select **Search automatically for drivers** and allow Windows to install the best available drivers.  
![Update Bluetooth Driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Update-Bluetooth-Driver.jpg)

 If the Bluetooth entry is missing from the Device Manager, visit your Bluetooth adapter manufacturer's website to download the driver and install it manually.

 If updating the driver does not help, you’ll have to reinstall the Bluetooth drivers. To do so, open the Device Manager again, right-click on the **Bluetooth driver**, and then select **Uninstall device**.

 Once removed, restart your PC. Windows should install the missing Bluetooth driver during boot, and the Bluetooth option should appear on your PC.

## 7\. Disable and Re-Enable the Problematic USB Driver

 Several users on a [Microsoft Community post](https://answers.microsoft.com/en-us/windows/forum/all/windows-11-bluetooth-disappears-fixes-2023/34f5c8b1-b5a1-4323-a7f6-4513c733d731) reported restoring the missing Bluetooth functionality on their computers by disabling and re-enabling the USB drivers. You can also give it a go.

1. Open Device Manager using the search menu.
2. Expand **Universal Serial Bus controllers**.
3. Look for any entries with a yellow warning triangle. Right-click it and select **Disable device**.
4. Select **Yes** to confirm.
5. Right-click on the USB driver again and select **Enable device**.  
![Enable USB Driver Using Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/enable-usb-driver-using-device-manager.jpg)

## 8\. Run SFC and DISM Scans

 Bluetooth issues can also arise if critical system files are missing from your computer. Windows includes a couple of [tools that can help you replace any missing or damaged system files](http://www.makeuseof.com/windows-built-in-repair-tools/) with their cached version. Here’s how to run them.

1. Press **Win + X** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt shows up.
3. In the console, run the following command:

`sfc /scannow`

 Wait for the scan to complete, and then run the DISM (or Deployment Image Servicing and Management) scan.

`DISM.exe /Online /Cleanup-image /Restorehealth`

![DISM Scan on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/DISM-Scan-on-Windows.jpg)

 After the scan is complete, restart your PC and check if the issue is still there.

## 9\. Boot into Safe Mode

 When you boot Windows into Safe Mode, it runs without any non-essential drivers and programs. This can help you verify if the issue is caused by a third-party driver or program running in the background.

 Windows 11 gives [several options for booting into Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/). You can use any of your preferred methods to enter Safe Mode and see if the Bluetooth option appears. If it does, then a third-party program or service is to blame. In that case, you’ll have to remove any recently installed apps or programs to fix the issue.

 Has the Bluetooth option disappeared on your Windows 11 computer? This can happen for several reasons, including temporary glitches, damaged Bluetooth drivers, and issues with the Windows OS. If you're unsure about what caused the problem, here are some tips that will help.

## 1\. Run the Appropriate Windows Troubleshooters

 Windows troubleshooters are built-in utilities that can help you diagnose and resolve various system-level issues. You can run the Bluetooth troubleshooter and allow Windows to fix any common Bluetooth-related issues. Here’s how:

1. Press **Win + I** to launch the Settings app.
2. In the **System** tab, click **Troubleshoot**.
3. Select **Other troubleshooters**.
4. Click the **Run** button next to **Bluetooth**.  
![Bluetooth Troubleshooter on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Bluetooth-Troubleshooter-on-Windows-11.jpg)

 Windows will scan your computer for any issues and try to fix them. Additionally, you can run the Hardware and Devices troubleshooter to scan your computer for any hardware issues. To do so:

1. Press **Win + R** to open the Run dialog.
2. Type **msdt.exe -id DeviceDiagnostic** in the Open field and press **Enter**.
3. In the Hardware and Devices window, click **Next** and follow the on-screen instructions to run the troubleshooter.  
![Hardware and Devices Troubleshooter on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Hardware-and-Devices-Troubleshooter-on-Windows.jpg)

## 2\. Perform a Power Cycle

 Sometimes, the most effective solution is surprisingly simple. Performing a power cycle can resolve various issues with your Windows PC caused by temporary glitches. To perform a power cycle:

1. Turn off your computer and unplug it from the power source.
2. Press and hold the **power button** for 30 to 60 seconds to drain all the power that’s left on your device.
3. Leave your computer idle for a few minutes.
4. Connect your computer to the power supply, and then turn it back on.

## 3\. Check the Quick Settings Panel

 The [Quick Settings panel in Windows 11](http://www.makeuseof.com/windows-11-customize-quick-settings-menu/) provides access to various commonly used settings, including Bluetooth. If you can’t find the Bluetooth toggle in the Quick Settings panel, you might have removed it by mistake. Here’s how you can retrieve it.

1. Press **Win + A** to open the Quick Settings panel.
2. Click the **pencil icon** to edit the Quick Settings panel.
3. Click on **Add** and select **Bluetooth** from the list to add it to the panel.  
![Add Bluetooth to Quick Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Add-Bluetooth-to-Quick-Settings.jpg)

## 4\. Check Bluetooth Settings

 The Bluetooth icon may not appear on the taskbar or system tray if you have previously removed the icon. Here's how you can [pin the Bluetooth icon to the Windows taskbar](https://www.makeuseof.com/how-pin-bluetooth-icon-windows-10-taskbar/) again.

1. Open the **Start menu** and go to **Settings > Bluetooth & devices**.
2. Go to **Devices** and click on **More Bluetooth Settings**.
3. Tick the box that reads **Show the Bluetooth icon in the notification area**.
4. Hit **Apply,** followed by **OK**.  
![Bluetooth Settings Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Bluetooth-Settings-Window.jpg)

## 5\. Configure the Bluetooth Support Service

 Bluetooth Support Service is a small program that runs in the background to allow Bluetooth to function on Windows. Your Bluetooth issues could be because the service isn't running. Here’s how to fix it.

1. Press **Win + R** to open the Run dialog.
2. Type **services.msc** in the text field and press **Enter**.
3. Double-click on **Bluetooth Support Service** to open its properties.
4. Use the drop-down menu next to **Startup type** to select **Automatic**.
5. Hit **Apply** to save changes.  
![Bluetooth Support Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Bluetooth-Support-Service.jpg)

 Restart your PC one more time and check if the Bluetooth option appears.

## 6\. Update or Reinstall Your Bluetooth Drivers

 Malfunctioning or corrupt Bluetooth drivers on your PC could also be the source of the problem. If that seems to be the case, updating the Bluetooth driver should help.

1. Right-click on the **Start** icon and select **Device Manager** from the list.
2. Expand the **Bluetooth** section, right-click on the **Bluetooth adapter**, and select **Update driver**.
3. Select **Search automatically for drivers** and allow Windows to install the best available drivers.  
![Update Bluetooth Driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Update-Bluetooth-Driver.jpg)

 If the Bluetooth entry is missing from the Device Manager, visit your Bluetooth adapter manufacturer's website to download the driver and install it manually.

 If updating the driver does not help, you’ll have to reinstall the Bluetooth drivers. To do so, open the Device Manager again, right-click on the **Bluetooth driver**, and then select **Uninstall device**.

 Once removed, restart your PC. Windows should install the missing Bluetooth driver during boot, and the Bluetooth option should appear on your PC.

## 7\. Disable and Re-Enable the Problematic USB Driver

 Several users on a [Microsoft Community post](https://answers.microsoft.com/en-us/windows/forum/all/windows-11-bluetooth-disappears-fixes-2023/34f5c8b1-b5a1-4323-a7f6-4513c733d731) reported restoring the missing Bluetooth functionality on their computers by disabling and re-enabling the USB drivers. You can also give it a go.

1. Open Device Manager using the search menu.
2. Expand **Universal Serial Bus controllers**.
3. Look for any entries with a yellow warning triangle. Right-click it and select **Disable device**.
4. Select **Yes** to confirm.
5. Right-click on the USB driver again and select **Enable device**.  
![Enable USB Driver Using Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/enable-usb-driver-using-device-manager.jpg)

## 8\. Run SFC and DISM Scans

 Bluetooth issues can also arise if critical system files are missing from your computer. Windows includes a couple of [tools that can help you replace any missing or damaged system files](http://www.makeuseof.com/windows-built-in-repair-tools/) with their cached version. Here’s how to run them.

1. Press **Win + X** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt shows up.
3. In the console, run the following command:

`sfc /scannow`

 Wait for the scan to complete, and then run the DISM (or Deployment Image Servicing and Management) scan.

`DISM.exe /Online /Cleanup-image /Restorehealth`

![DISM Scan on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/DISM-Scan-on-Windows.jpg)

 After the scan is complete, restart your PC and check if the issue is still there.

## 9\. Boot into Safe Mode

 When you boot Windows into Safe Mode, it runs without any non-essential drivers and programs. This can help you verify if the issue is caused by a third-party driver or program running in the background.

 Windows 11 gives [several options for booting into Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/). You can use any of your preferred methods to enter Safe Mode and see if the Bluetooth option appears. If it does, then a third-party program or service is to blame. In that case, you’ll have to remove any recently installed apps or programs to fix the issue.

 Has the Bluetooth option disappeared on your Windows 11 computer? This can happen for several reasons, including temporary glitches, damaged Bluetooth drivers, and issues with the Windows OS. If you're unsure about what caused the problem, here are some tips that will help.

## 1\. Run the Appropriate Windows Troubleshooters

 Windows troubleshooters are built-in utilities that can help you diagnose and resolve various system-level issues. You can run the Bluetooth troubleshooter and allow Windows to fix any common Bluetooth-related issues. Here’s how:

1. Press **Win + I** to launch the Settings app.
2. In the **System** tab, click **Troubleshoot**.
3. Select **Other troubleshooters**.
4. Click the **Run** button next to **Bluetooth**.  
![Bluetooth Troubleshooter on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Bluetooth-Troubleshooter-on-Windows-11.jpg)

 Windows will scan your computer for any issues and try to fix them. Additionally, you can run the Hardware and Devices troubleshooter to scan your computer for any hardware issues. To do so:

1. Press **Win + R** to open the Run dialog.
2. Type **msdt.exe -id DeviceDiagnostic** in the Open field and press **Enter**.
3. In the Hardware and Devices window, click **Next** and follow the on-screen instructions to run the troubleshooter.  
![Hardware and Devices Troubleshooter on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Hardware-and-Devices-Troubleshooter-on-Windows.jpg)

## 2\. Perform a Power Cycle

 Sometimes, the most effective solution is surprisingly simple. Performing a power cycle can resolve various issues with your Windows PC caused by temporary glitches. To perform a power cycle:

1. Turn off your computer and unplug it from the power source.
2. Press and hold the **power button** for 30 to 60 seconds to drain all the power that’s left on your device.
3. Leave your computer idle for a few minutes.
4. Connect your computer to the power supply, and then turn it back on.

## 3\. Check the Quick Settings Panel

 The [Quick Settings panel in Windows 11](http://www.makeuseof.com/windows-11-customize-quick-settings-menu/) provides access to various commonly used settings, including Bluetooth. If you can’t find the Bluetooth toggle in the Quick Settings panel, you might have removed it by mistake. Here’s how you can retrieve it.

1. Press **Win + A** to open the Quick Settings panel.
2. Click the **pencil icon** to edit the Quick Settings panel.
3. Click on **Add** and select **Bluetooth** from the list to add it to the panel.  
![Add Bluetooth to Quick Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Add-Bluetooth-to-Quick-Settings.jpg)

## 4\. Check Bluetooth Settings

 The Bluetooth icon may not appear on the taskbar or system tray if you have previously removed the icon. Here's how you can [pin the Bluetooth icon to the Windows taskbar](https://www.makeuseof.com/how-pin-bluetooth-icon-windows-10-taskbar/) again.

1. Open the **Start menu** and go to **Settings > Bluetooth & devices**.
2. Go to **Devices** and click on **More Bluetooth Settings**.
3. Tick the box that reads **Show the Bluetooth icon in the notification area**.
4. Hit **Apply,** followed by **OK**.  
![Bluetooth Settings Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Bluetooth-Settings-Window.jpg)

## 5\. Configure the Bluetooth Support Service

 Bluetooth Support Service is a small program that runs in the background to allow Bluetooth to function on Windows. Your Bluetooth issues could be because the service isn't running. Here’s how to fix it.

1. Press **Win + R** to open the Run dialog.
2. Type **services.msc** in the text field and press **Enter**.
3. Double-click on **Bluetooth Support Service** to open its properties.
4. Use the drop-down menu next to **Startup type** to select **Automatic**.
5. Hit **Apply** to save changes.  
![Bluetooth Support Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Bluetooth-Support-Service.jpg)

 Restart your PC one more time and check if the Bluetooth option appears.

## 6\. Update or Reinstall Your Bluetooth Drivers

 Malfunctioning or corrupt Bluetooth drivers on your PC could also be the source of the problem. If that seems to be the case, updating the Bluetooth driver should help.

1. Right-click on the **Start** icon and select **Device Manager** from the list.
2. Expand the **Bluetooth** section, right-click on the **Bluetooth adapter**, and select **Update driver**.
3. Select **Search automatically for drivers** and allow Windows to install the best available drivers.  
![Update Bluetooth Driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Update-Bluetooth-Driver.jpg)

 If the Bluetooth entry is missing from the Device Manager, visit your Bluetooth adapter manufacturer's website to download the driver and install it manually.

 If updating the driver does not help, you’ll have to reinstall the Bluetooth drivers. To do so, open the Device Manager again, right-click on the **Bluetooth driver**, and then select **Uninstall device**.

 Once removed, restart your PC. Windows should install the missing Bluetooth driver during boot, and the Bluetooth option should appear on your PC.

## 7\. Disable and Re-Enable the Problematic USB Driver

 Several users on a [Microsoft Community post](https://answers.microsoft.com/en-us/windows/forum/all/windows-11-bluetooth-disappears-fixes-2023/34f5c8b1-b5a1-4323-a7f6-4513c733d731) reported restoring the missing Bluetooth functionality on their computers by disabling and re-enabling the USB drivers. You can also give it a go.

1. Open Device Manager using the search menu.
2. Expand **Universal Serial Bus controllers**.
3. Look for any entries with a yellow warning triangle. Right-click it and select **Disable device**.
4. Select **Yes** to confirm.
5. Right-click on the USB driver again and select **Enable device**.  
![Enable USB Driver Using Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/enable-usb-driver-using-device-manager.jpg)

## 8\. Run SFC and DISM Scans

 Bluetooth issues can also arise if critical system files are missing from your computer. Windows includes a couple of [tools that can help you replace any missing or damaged system files](http://www.makeuseof.com/windows-built-in-repair-tools/) with their cached version. Here’s how to run them.

1. Press **Win + X** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt shows up.
3. In the console, run the following command:

`sfc /scannow`

 Wait for the scan to complete, and then run the DISM (or Deployment Image Servicing and Management) scan.

`DISM.exe /Online /Cleanup-image /Restorehealth`

![DISM Scan on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/DISM-Scan-on-Windows.jpg)

 After the scan is complete, restart your PC and check if the issue is still there.

## 9\. Boot into Safe Mode

 When you boot Windows into Safe Mode, it runs without any non-essential drivers and programs. This can help you verify if the issue is caused by a third-party driver or program running in the background.

 Windows 11 gives [several options for booting into Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/). You can use any of your preferred methods to enter Safe Mode and see if the Bluetooth option appears. If it does, then a third-party program or service is to blame. In that case, you’ll have to remove any recently installed apps or programs to fix the issue.

 Has the Bluetooth option disappeared on your Windows 11 computer? This can happen for several reasons, including temporary glitches, damaged Bluetooth drivers, and issues with the Windows OS. If you're unsure about what caused the problem, here are some tips that will help.

## 1\. Run the Appropriate Windows Troubleshooters

 Windows troubleshooters are built-in utilities that can help you diagnose and resolve various system-level issues. You can run the Bluetooth troubleshooter and allow Windows to fix any common Bluetooth-related issues. Here’s how:

1. Press **Win + I** to launch the Settings app.
2. In the **System** tab, click **Troubleshoot**.
3. Select **Other troubleshooters**.
4. Click the **Run** button next to **Bluetooth**.  
![Bluetooth Troubleshooter on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Bluetooth-Troubleshooter-on-Windows-11.jpg)

 Windows will scan your computer for any issues and try to fix them. Additionally, you can run the Hardware and Devices troubleshooter to scan your computer for any hardware issues. To do so:

1. Press **Win + R** to open the Run dialog.
2. Type **msdt.exe -id DeviceDiagnostic** in the Open field and press **Enter**.
3. In the Hardware and Devices window, click **Next** and follow the on-screen instructions to run the troubleshooter.  
![Hardware and Devices Troubleshooter on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Hardware-and-Devices-Troubleshooter-on-Windows.jpg)

## 2\. Perform a Power Cycle

 Sometimes, the most effective solution is surprisingly simple. Performing a power cycle can resolve various issues with your Windows PC caused by temporary glitches. To perform a power cycle:

1. Turn off your computer and unplug it from the power source.
2. Press and hold the **power button** for 30 to 60 seconds to drain all the power that’s left on your device.
3. Leave your computer idle for a few minutes.
4. Connect your computer to the power supply, and then turn it back on.

## 3\. Check the Quick Settings Panel

 The [Quick Settings panel in Windows 11](http://www.makeuseof.com/windows-11-customize-quick-settings-menu/) provides access to various commonly used settings, including Bluetooth. If you can’t find the Bluetooth toggle in the Quick Settings panel, you might have removed it by mistake. Here’s how you can retrieve it.

1. Press **Win + A** to open the Quick Settings panel.
2. Click the **pencil icon** to edit the Quick Settings panel.
3. Click on **Add** and select **Bluetooth** from the list to add it to the panel.  
![Add Bluetooth to Quick Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Add-Bluetooth-to-Quick-Settings.jpg)

## 4\. Check Bluetooth Settings

 The Bluetooth icon may not appear on the taskbar or system tray if you have previously removed the icon. Here's how you can [pin the Bluetooth icon to the Windows taskbar](https://www.makeuseof.com/how-pin-bluetooth-icon-windows-10-taskbar/) again.

1. Open the **Start menu** and go to **Settings > Bluetooth & devices**.
2. Go to **Devices** and click on **More Bluetooth Settings**.
3. Tick the box that reads **Show the Bluetooth icon in the notification area**.
4. Hit **Apply,** followed by **OK**.  
![Bluetooth Settings Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Bluetooth-Settings-Window.jpg)

## 5\. Configure the Bluetooth Support Service

 Bluetooth Support Service is a small program that runs in the background to allow Bluetooth to function on Windows. Your Bluetooth issues could be because the service isn't running. Here’s how to fix it.

1. Press **Win + R** to open the Run dialog.
2. Type **services.msc** in the text field and press **Enter**.
3. Double-click on **Bluetooth Support Service** to open its properties.
4. Use the drop-down menu next to **Startup type** to select **Automatic**.
5. Hit **Apply** to save changes.  
![Bluetooth Support Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Bluetooth-Support-Service.jpg)

 Restart your PC one more time and check if the Bluetooth option appears.

## 6\. Update or Reinstall Your Bluetooth Drivers

 Malfunctioning or corrupt Bluetooth drivers on your PC could also be the source of the problem. If that seems to be the case, updating the Bluetooth driver should help.

1. Right-click on the **Start** icon and select **Device Manager** from the list.
2. Expand the **Bluetooth** section, right-click on the **Bluetooth adapter**, and select **Update driver**.
3. Select **Search automatically for drivers** and allow Windows to install the best available drivers.  
![Update Bluetooth Driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Update-Bluetooth-Driver.jpg)

 If the Bluetooth entry is missing from the Device Manager, visit your Bluetooth adapter manufacturer's website to download the driver and install it manually.

 If updating the driver does not help, you’ll have to reinstall the Bluetooth drivers. To do so, open the Device Manager again, right-click on the **Bluetooth driver**, and then select **Uninstall device**.

 Once removed, restart your PC. Windows should install the missing Bluetooth driver during boot, and the Bluetooth option should appear on your PC.

## 7\. Disable and Re-Enable the Problematic USB Driver

 Several users on a [Microsoft Community post](https://answers.microsoft.com/en-us/windows/forum/all/windows-11-bluetooth-disappears-fixes-2023/34f5c8b1-b5a1-4323-a7f6-4513c733d731) reported restoring the missing Bluetooth functionality on their computers by disabling and re-enabling the USB drivers. You can also give it a go.

1. Open Device Manager using the search menu.
2. Expand **Universal Serial Bus controllers**.
3. Look for any entries with a yellow warning triangle. Right-click it and select **Disable device**.
4. Select **Yes** to confirm.
5. Right-click on the USB driver again and select **Enable device**.  
![Enable USB Driver Using Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/enable-usb-driver-using-device-manager.jpg)

## 8\. Run SFC and DISM Scans

 Bluetooth issues can also arise if critical system files are missing from your computer. Windows includes a couple of [tools that can help you replace any missing or damaged system files](http://www.makeuseof.com/windows-built-in-repair-tools/) with their cached version. Here’s how to run them.

1. Press **Win + X** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt shows up.
3. In the console, run the following command:

`sfc /scannow`

 Wait for the scan to complete, and then run the DISM (or Deployment Image Servicing and Management) scan.

`DISM.exe /Online /Cleanup-image /Restorehealth`

![DISM Scan on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/DISM-Scan-on-Windows.jpg)

 After the scan is complete, restart your PC and check if the issue is still there.

## 9\. Boot into Safe Mode

 When you boot Windows into Safe Mode, it runs without any non-essential drivers and programs. This can help you verify if the issue is caused by a third-party driver or program running in the background.

 Windows 11 gives [several options for booting into Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/). You can use any of your preferred methods to enter Safe Mode and see if the Bluetooth option appears. If it does, then a third-party program or service is to blame. In that case, you’ll have to remove any recently installed apps or programs to fix the issue.


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
<li><a href="https://windows11.techidaily.com/regaining-control-over-your-speakers-settings-in-windows/"><u>Regaining Control over Your Speakers' Settings in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-call-issue-fixed-runtime-errors-in-malwarebytes-for-win10win11/"><u>Overcoming the Call Issue: Fixed Runtime Errors in Malwarebytes for Win10/Win11</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-photos-from-c65-by-fonelab-android-recover-photos/"><u>Undelete lost photos from C65.</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-unavailable-nvidia-cp-on-windows-11/"><u>Overcoming Unavailable Nvidia CP on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-gl-driver-error-3-on-windows-11-a-step-by-step-guide/"><u>Resolving GL Driver Error 3 on Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-chuckle-cache-the-best-humor-tweets-on-twitch/"><u>[New] Chuckle Cache  The Best Humor Tweets on Twitch</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-screen-glitches-in-windows-11-a-step-by-step-guide/"><u>Solving Screen Glitches in Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-11-usage-chronicles/"><u>Navigating Through Windows 11 Usage Chronicles</u></a></li>
<li><a href="https://android-unlock.techidaily.com/complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-samsung-galaxy-f14-5g-by-drfone-android/"><u>Complete Review & Guide to Techeligible FRP Bypass and More For Samsung Galaxy F14 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/redoing-power-schemes-with-lost-settings-win-11/"><u>Redoing Power Schemes with Lost Settings (Win 11)</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-clearing-up-confusion-understanding-digital-rights-management-drm/"><u>[Updated] In 2024, Clearing Up Confusion  Understanding Digital Rights Management (DRM)</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-voice-over-fundamentals-from-syncing-dialogue-to-final-cut/"><u>[New] Voice Over Fundamentals  From Syncing Dialogue to Final Cut</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-optimizing-recording-quality-tips-and-tricks-for-ps3-gamers/"><u>In 2024, Optimizing Recording Quality  Tips and Tricks for PS3 Gamers</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-route-engaging-windows-11s-capture-utility/"><u>Quick Route: Engaging Windows 11'S Capture Utility</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-sync-your-views-iphones-looping-feature/"><u>In 2024, Sync Your Views  IPhone's Looping Feature</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-master-the-art-of-rapid-tiktok-videos/"><u>[Updated] Master the Art of Rapid TikTok Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-your-system-without-relying-on-bitlocker/"><u>Securing Your System without Relying on Bitlocker</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-efficiency-how-copilot-key-shapes-your-windows-11-experience/"><u>Mastering Efficiency: How Copilot Key Shapes Your Windows 11 Experience</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-perfect-pause-removing-unwanted-noise-and-music-from-your-imovie-videos/"><u>New Perfect Pause Removing Unwanted Noise and Music From Your iMovie Videos</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-upload-tiktok-videos-on-chrome-android-and-iphone-a-step-by-step-guide/"><u>[Updated] 2024 Approved  Upload TikTok Videos on Chrome, Android & iPhone - A Step-by-Step Guide</u></a></li>
<li><a href="https://vp-tips.techidaily.com/fixing-iphone-x-overcoming-face-id-malfunction-for-2024/"><u>Fixing iPhone X  Overcoming Face ID Malfunction for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-top-10-free-video-tools-cross-platform-os-support/"><u>[Updated] Top 10 Free Video Tools  Cross-Platform OS Support</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-your-gear-use-efficiently-using-windows-interfaces/"><u>Navigate Your Gear Use Efficiently Using Windows Interfaces</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-quick-vimeo-transformation-tips-easy-to-create-gifs/"><u>[New] In 2024, Quick Vimeo Transformation Tips  Easy-to-Create GIFs</u></a></li>
<li><a href="https://windows11.techidaily.com/seeking-entry-into-the-windows-11-insider-circle/"><u>Seeking Entry Into the Windows 11 Insider Circle</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-hyper-v-for-efficient-linux-vm-creation-in-windows/"><u>Leveraging Hyper-V for Efficient Linux VM Creation in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-make-your-retro-games-look-like-they-used-to-with-retroarchs-shaders/"><u>How to Make Your Retro Games Look Like They Used to With RetroArch’s Shaders</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-apple-iphone-se-2020-drfone-by-drfone-virtual-ios/"><u>Why Your WhatsApp Live Location is Not Updating and How to Fix on your Apple iPhone SE (2020) | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-unstoppable-methods-to-turn-off-ms-defender/"><u>Mastering Unstoppable Methods to Turn Off MS Defender</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-forgot-your-apple-id-password-and-email-on-apple-iphone-6-heres-the-best-fixes-by-drfone-ios/"><u>In 2024, Forgot Your Apple ID Password and Email On Apple iPhone 6? Heres the Best Fixes</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-magixs-legacy-in-vectors-finding-future-software/"><u>2024 Approved  Magix's Legacy in Vectors  Finding Future Software</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-windows-users-through-system-slumber/"><u>Guiding Windows Users Through System Slumber</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-workspace-malfunctions-essential-tips-for-office-on-winos/"><u>Resolving Workspace Malfunctions: Essential Tips for Office on WINOS</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-searching-on-windows-techniques-beyond-ls-command/"><u>Seamless Searching on Windows: Techniques Beyond LS Command</u></a></li>
<li><a href="https://howto.techidaily.com/want-to-uninstall-google-play-service-from-xiaomi-redmi-note-13-proplus-5g-here-is-how-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Want to Uninstall Google Play Service from Xiaomi Redmi Note 13 Pro+ 5G? Here is How | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/sound-struggles-winning-back-noise-from-windows-spacebar/"><u>Sound Struggles: Winning Back Noise From Windows' Spacebar</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-the-ultimate-guide-to-decreasing-sounds-prominence-in-lumafusion/"><u>[Updated] 2024 Approved  The Ultimate Guide to Decreasing Sounds' Prominence in Lumafusion</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-how-to-detach-audio-from-video-in-premiere-pro-in-2024/"><u>New How to Detach Audio From Video in Premiere Pro, In 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/prevent-windows-stop-recurrent-file-explorer-launches/"><u>Prevent Windows: Stop Recurrent File Explorer Launches</u></a></li>
<li><a href="https://extra-skills.techidaily.com/maximizing-4k-quality-selecting-between-projection-and-television-screens-for-2024/"><u>Maximizing 4K Quality  Selecting Between Projection and Television Screens for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/harmonize-workflow-setting-active-hours-on-windows-11-for-peace-of-mind/"><u>Harmonize Workflow: Setting Active Hours on Windows 11 for Peace of Mind</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-the-roadmap-to-recognition-earning-your-verified-status-on-discord/"><u>In 2024, The Roadmap to Recognition  Earning Your Verified Status on Discord</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/iphone-lens-wizardry-secrets-to-selecting-perfect-positions-for-2024/"><u>IPhone Lens Wizardry  Secrets to Selecting Perfect Positions for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/expert-picks-premium-costless-screencasting-apps-reviewed/"><u>Expert Picks  Premium, Costless Screencasting Apps Reviewed</u></a></li>
<li><a href="https://windows11.techidaily.com/faster-task-management-display-in-windows-11-os/"><u>Faster Task Management Display in Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-basics-top-settings-to-optimize-on-new-windows-11/"><u>Mastering the Basics: Top Settings to Optimize on New Windows 11</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/in-2024-finding-the-best-gif-websites-was-never-easier/"><u>In 2024, Finding the Best GIF Websites Was Never Easier</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-elevate-your-storytelling-how-to-create-professional-looking-films-on-a-budget/"><u>Updated In 2024, Elevate Your Storytelling How to Create Professional-Looking Films on a Budget</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-should-past-facebook-actions-follow-you-today-investigate/"><u>In 2024, Should Past Facebook Actions Follow You Today? Investigate</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-absent-windows-extras-a-comprehensive-guide/"><u>Reviving Absent Windows Extras: A Comprehensive Guide</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-discover-your-rhythm-assembling-tailored-youtube-playlists-for-the-digital-age-webmobile/"><u>[New] In 2024, Discover Your Rhythm  Assembling Tailored YouTube Playlists for the Digital Age (Web/Mobile)</u></a></li>
<li><a href="https://windows11.techidaily.com/rectify-windows-error-reestablishing-java-vm/"><u>Rectify Windows Error: Reestablishing Java VM</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-surface-laptop-go-3-review-new-processor-same-old-drawbacks/"><u>Microsoft Surface Laptop Go 3 Review: New Processor, Same Old Drawbacks</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-read-only-status-in-1011s-file-directories/"><u>Remedying Read-Only Status in 10/11'S File Directories</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-exploring-the-marvel-of-apples-m1-max-attachments/"><u>In 2024, Exploring the Marvel of Apple’s M1 Max Attachments</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11-align-your-sticky-notes-accurately/"><u>Navigating Windows 11: Align Your Sticky Notes Accurately</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-performance-with-5-wsl-2-enhancements/"><u>Maximizing Performance with 5 WSL 2 Enhancements</u></a></li>
</ul></div>
