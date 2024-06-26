---
title: 10 Tips to Restore Bluetooth Functionality on Windows 11
date: 2024-06-25T11:59:03.012Z
updated: 2024-06-26T11:59:03.012Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 10 Tips to Restore Bluetooth Functionality on Windows 11
excerpt: This Article Describes 10 Tips to Restore Bluetooth Functionality on Windows 11
keywords: WiFi/Bluetooth Fix Win11,Reconnect Bluetooth Win11,Restore Bluetooth Win11,Fix Bluetooth Issue Windows 11,Troubleshoot Bluetooth Win11,Enable Bluetooth Win11,Revive Bluetooth on Win11
thumbnail: https://thmb.techidaily.com/e2b3e6d5f3444ca9eb9fe2e05133bcedc239a2116beb3419cf2a3656ee84dbb0.jpg
---

## 10 Tips to Restore Bluetooth Functionality on Windows 11

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
<li><a href="https://windows11.techidaily.com/solving-0x80072efd-in-win1110s-microsoft-store/"><u>Solving 0X80072EFD in Win11/10's Microsoft Store</u></a></li>
<li><a href="https://windows11.techidaily.com/how-removing-windows-11s-taskbar-chatter-affects-you-the-user/"><u>How Removing Windows 11'S Taskbar Chatter Affects You, The User?</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-blue-screen-in-win11-5-methods-to-prevent-hybrid-errors/"><u>Fixing Blue Screen in Win11: 5 Methods to Prevent Hybrid Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-guide-to-fix-windows-non-functional-start/"><u>A Step-by-Step Guide to Fix Window's Non-Functional Start</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-for-an-effortless-in-place-windows-11-revamp/"><u>Step-by-Step Guide for an Effortless, In-Place Windows 11 Revamp</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-absence-of-display-in-boot-process/"><u>Remedying Absence of Display in Boot Process</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-dream-team-top-windows-apps-for-a-winning-start/"><u>Digital Dream Team: Top Windows Apps for a Winning Start</u></a></li>
<li><a href="https://windows11.techidaily.com/disable-automatic-snipping-tool-activation-by-prtscn-keypress-in-windows-11/"><u>Disable Automatic Snipping Tool Activation by PrtScn Keypress in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-windows-11-performance-tweak-ntfs-file-compression/"><u>Enhance Windows 11 Performance: Tweak NTFS File Compression</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-starting-point-for-film-designers/"><u>[Updated] The Starting Point for Film Designers</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-discover-top-free-cameras-for-live-streaming-for-2024/"><u>[Updated] Discover Top Free Cameras for Live Streaming for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-retro-revelry-on-snapchat-camera-roll-insights/"><u>2024 Approved  Retro Revelry on Snapchat  Camera Roll Insights</u></a></li>
<li><a href="https://extra-information.techidaily.com/crafting-spectacular-time-lapses-with-gopro-hero5-black-for-2024/"><u>Crafting Spectacular Time-Lapses with GoPro Hero5 Black for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-frp-on-vivo-s17t-by-drfone-android/"><u>How to Bypass FRP on Vivo S17t?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/full-guide-on-mirroring-your-motorola-moto-g24-to-your-pcmac-drfone-by-drfone-android/"><u>Full Guide on Mirroring Your Motorola Moto G24 to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-essential-guide-to-mobile-horizon-photos/"><u>[Updated] The Essential Guide to Mobile Horizon Photos</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-kinemasters-ultimate-green-screen-implementation-techniques/"><u>In 2024, Kinemaster's Ultimate Green Screen Implementation Techniques</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-convert-your-avis-to-impactful-gifs-using-filmora-on-windowsmacos-for-2024/"><u>[Updated] Convert Your AVIs to Impactful GIFs Using Filmora on Windows/MacOS for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-three-ways-to-sim-unlock-motorola-by-drfone-android/"><u>In 2024, Three Ways to Sim Unlock Motorola</u></a></li>
</ul></div>
