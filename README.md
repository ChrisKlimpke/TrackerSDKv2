# TrackerSDKv2

Version 2022-04-29AR supports ARKit with matrxi reportijng extensions

Version string used is 2022-05-31R is latest non ARKit version is tagged 1.1.8 and above


This version includes some minor bug fixes.

A description of this SDK can be found in VykingTrackerSDK-2021-10-06.pdf

The SDK relies on camera access and it is the apps responsibility to request camera access, the example code section provides an example of how to do this.

The SDK is currently available for MacOS (version 10.0 and above), iOS (version 11.2 and above) and for Android (API 26 and above), see notes below for more details regarding OS version support.

The SDK document assumes the developer is familiar with C, objective-c, swift and/or java. This document is accompanied by example program source file for a simple use cases for SceneKit (Apple) and Unity .

The latest 2020-10-29 SDK supports usage logging (see 3.1.3.4) and two new functions have been introduced. The first provides complete transparency of the information being send externally for the purposes of logging usage. The second function registers the shoe model sets with the SDK (see 3.1.3.5) and should be called when a show model set is utilised.

Now supports getSDKexpiry method

