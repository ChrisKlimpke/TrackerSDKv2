# TrackerSDKv2

Version string used is 2022-07-25AR is latest ARKit version is tagged 2.0.3 and above for use wih ARKit

Version string used is 2022-07-25R is latest non ARKit version is tagged 1.1.10 and above

2024-11-04 Latest verison of 2024-11-04R  is now git tagged 1.1.16

2024-04-04 Latest verison of 2024-04-04AR is now git tagged 2.0.6

These versions of the iOS SDK supports the laest AR models for foot tracking

This version includes some minor bug fixes.

A description of this SDK can be found in VykingTrackerSDK-2021-10-06.pdf

The SDK relies on camera access and it is the apps responsibility to request camera access, the example code section provides an example of how to do this.

The SDK is currently available for MacOS (version 10.0 and above), iOS (version 11.2 and above) and for Android (API 26 and above), see notes below for more details regarding OS version support.

The SDK document assumes the developer is familiar with C, objective-c, swift and/or java. This document is accompanied by example program source file for a simple use cases for SceneKit (Apple) and Unity .

The latest 2020-10-29 SDK supports usage logging (see 3.1.3.4) and two new functions have been introduced. The first provides complete transparency of the information being send externally for the purposes of logging usage. The second function registers the shoe model sets with the SDK (see 3.1.3.5) and should be called when a show model set is utilised.

Now supports getSDKexpiry method

