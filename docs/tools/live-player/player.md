---
title: "Xamarin Live Player App"
description: "Edit and test apps in real time on your iOS or Android device"
ms.topic: article
ms.prod: xamarin
ms.assetid: A7EB73C1-38D7-46C5-9AF6-4C571C168BE7
ms.technology: xamarin-cross-platform
author: topgenorth
ms.author: toopge
ms.date: 05/10/2017
---

# Xamarin Live Player App

![Preview feature](~/media/shared/preview.png)

## Get the App

### Xamarin Live Player for Android
Xamarin Live Player is available for Android from Google Play:

[ ![Available on Google Play](images/google-play-badge.png)](https://play.google.com/store/apps/details?id=com.xamarin.live)

For Android devices without Google Play the Xamarin Live Player is available through [HockeyApp](https://aka.ms/xlp-hockeyapp) distribution. Additionally, early preview builds for Android can be installed directly from Google Play by opting in to the [open beta program](https://play.google.com/apps/testing/com.xamarin.live)

### Xamarin Live Player for iOS
We encourage users to join the [Xamarin Live Player app _iOS Preview_](https://aka.ms/liveplayeralpha) to enjoy quick access to the latest improvements through TestFlight.



## Using the App

Once you have installed the app on your phone, follow the
[setup instructions](~/tools/live-player/install.md) to connect to your
computer. Try one of the [sample apps](~/tools/live-player/samples.md) to get it working.

On startup, the Xamarin Live Player app looks like this (on iOS and Android respectively):

![Live Player iOS app screenshot](player-images/app-iphone-sml.png) ![Live Player Android app screenshot](player-images/app-android-sml.png)

When you press **Pair to Visual Studio**, use the camera to scan the
barcode showing on your computer:

![Screenshot of the iOS barcode scanner](player-images/scan-iphone-sml.png) ![Screenshot of the Android barcode scanner](player-images/scan-android-sml.png)

If the connection is successful, the code should run on
the device almost immediately (such as the Calculator sample):

![Sample calculator app running on device](player-images/basic-calculator-iphone-sml.png)

## Options

Press the information button **(i)** on the bottom of the app to reveal the **Options** menu:

![Screenshot of the options menu](player-images/options.png)

### Logs

View logs to diagnose problems.

### Settings

* Toggle display of compile and runtime errors.
* Version information.
* Send feedback.

![Screenshot of the settings](player-images/settings.png)

## Managing Devices

To connect a device for the first time, follow the instructions in [Requirements & Setup](~/tools/live-player/install.md). You can pair multiple devices (for example an iOS
and an Android), and manage them via the IDE.

# [Visual Studio](#tab/vswin)

In Visual Studio, choose **Tools > Xamarin Live Player > Manage Devices...**

![Manage devices window](player-images/manage-tools-menu-vs.png)

This window lets you do the following:

- Pair a new device by scanning the code
- Alternatively pair a device by typing the code displayed on its screen
- Remove existing devices from the list

You can also access this window from the device list.

# [Visual Studio for Mac](#tab/vsmac)

In Visual Studio for Mac, choose **Tools > (Xamarin Live Player) Manage Devices...**

![Manage devices window](player-images/manage-tools-menu.png)

This window lets you do the following:

- Pair a new device by scanning the code
- Alternatively pair a device by typing the code displayed on its screen
- Remove existing devices from the list

![Manage devices window](player-images/manage.png)

You can also access this window from the device list:

![Choose Xamarin Live Player Devices from the device list](player-images/manage-device-menu.png)

-----

If you experience any issues see [limitations and troubleshooting](~/tools/live-player/troubleshooting.md).


## Related Links

- [Limitations](~/tools/live-player/limitations.md)
- [Troubleshooting](~/tools/live-player/troubleshooting.md)
- [Xamarin Live Player Samples](~/tools/livehttps://developer.xamarin.com/samples.md)
