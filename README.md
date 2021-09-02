# iOS Application SelfPass

<p align="center">
![Logo][<img height="160" src="Logo/logo.png" />]
</p>

<p align="center">
<img src="https://img.shields.io/badge/platforms-iOS-lightgrey"/>
<img src="https://img.shields.io/badge/Xcode-11.0%2B-yellowgreen"/>
<img src="https://img.shields.io/badge/Language-SWIFT%205-orange"/>
<img src="https://img.shields.io/badge/License-MIT-blue"/>

</p>

This directory contains the full implementation of SelfPass application for iOS platform. This app is created and layout it programmatically, and get everything done with Storyboard and XIB. Additionally, It also provides a way to cooperate with UIScrollView.


# Requirements

iOS 12.4+

Xcode 11.0+

Swift  5

# Installation

Clone this repository and import into the Xcode.

# API Setup:
Update ```Selfpass/Selfpass/Constants/Constants.swift``` with the following info:

```swift
SERVER_BASE_URL = "Contact support team to get APP-BASE-URL"
NEWS_FEED_URL = "Contact support team to get NEWS_FEED_URL"
APP_ID = "Contact support team to get APP_ID"
CBU_UDID_BLUETOOTH = "Contact Support team to get CBU_UDID_BLUETOOTH"
CONTACTUS_URL = "contact Support team to get CONTACTUS_URL"
PRIVACY_URL = "Contact support team to get PRIVACY_URL"
ABOUTUS_URL = "Contact support team to get ABOUTUS_URL"
```


# Update ```SelfPass/SelfPass/GoogleService-Info.plist```

Generate the GoogleService-Info.plist from Firebase Console to enable O-Auth, Crashlytics, Google Sigin and Push Notifications.

After Generating the GoogleService-Info.plist

# Update ```SelfPass/SelfPass/info.plist``` 

update the URL types with the Following info:

URL Types - "Reverse Client Id in GoogleService-info.plist" with the  GoogleService-Info.plist Reverse Client-id.

# Usage

You could directly clone and open in the xcode. 
Select the scheme as "SelfPass" and Choose the device and run on the xcode.

# Generating the ipa

 Step 1: In .entitlements file, Enter the APS Environment as "development" for development ipa or Enter the APS Environment as "production" for Production ipa.
 
 Step 2: Choose "Any iOS devices" in scheme.

 Step 3: Choose Product->Archive to generate the ipa in organizer.

 Step 4: Choose Distribute App.

 Step 5: Upload the app to AppStore.


