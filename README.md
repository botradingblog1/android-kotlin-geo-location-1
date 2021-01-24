# Android Kotlin sample app for tracking the device's geo location

## Overview
This is an Android sample app written in Kotlin which shows how to track the devices geo-location.

## Highlights:
* Request coarse and fine location permission
* Handle different permission allow and deny responses
* Set up fusedLocationProvider client and locationRequest
* Start and stop location tracking
* Display latitude and longitude results in the UI

## Supporting material
For a step-by-step tutorial, please see my [blog post on getting geo location in Android with Kotlin](https://mobiledeveloperblog.com/taking-and-saving-camera-images-with-android-and-kotlin/).

## Getting Started
1. Cone the project from GitHub

```
	https://github.com/justmobiledev/android-kotlin-geo-location-1.git
```
2. Build the project in Android Studio
3. Configure emulator to set a mock location or route
3. Deploy on emulator or device.

## Versions used
* Android Studio 4.1.1
* Android API 29

## Sample App Usage
1. Press the 'Start Tracking' button to start the request permission flow.
2. Once the permission is granted, a latitude and longitude should be displayed
3. Use the 'Stop Tracking' button to stop tracking a geo location.
