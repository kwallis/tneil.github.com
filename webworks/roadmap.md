---
title: BlackBerry WebWorks Roadmap
layout: default
---

# BlackBerry WebWorks Roadmap

Below you will find the **_tentative_** roadmap for BlackBerry&reg; WebWorks.  Scope and timelines are subject to change.

You can also join the roadmap conversations on the [BlackBerry WebWorks Contributions forum](http://supportforums.blackberry.com/t5/BlackBerry-WebWorks/bd-p/ww_con)


### BlackBerry Services APIs

We are working with the RIM internal groups responsible for BBM, Advertising, BlackBerry ID, Payment, Analytics and Push services SDKs
to bring their APIs to the WebWorks Platform.  As this functionality becomes available it will be added to the scope of an in-flight release following a release train model.  

If these APIs become available and are ready before the next version of the SDK ships, we will make them available for download through the API documentation.  Once the API has found its way into an official release, we will update the API documentation to show that the functionality is now part of the core SDK.

### Echo Release - Smartphone [Early August]

This is an update to the Smartphone SDK focusing on some incremental updates, bug fixes, and shipping a packaged BlackBerry 7 simulator. This release also includes items that provide HTML5 functionality on OS 5.0 out of the box instead of having to download a separate JavaScript toolkit.

Scope:

* Automatic insertion of the [HTML5 JavaScript toolkit](http://supportforums.blackberry.com/t5/Web-Development/Supporting-Gears-using-HTML5-in-BlackBerry-WebWorks-applications/ta-p/557280) for 5.0 devices
* Microphone API
* Inclusion of BB7 Smartphone Simulator
* Fix for memory drain issue
* Inclusion of the BB7 net_rim_api.jar library so that custom API extensions for BB6 and BB7 can also be used with WebWorks

Stretch Goal:

* Payment API

### Foxtrot Release - Tablet [September]

This update focuses on updating the Tablet SDK with the latest underlying components as well as some incremental improvements.

Scope:

* Fix for "Flicker" effect on app start-up when using loading screens
* Fix for increased app size on build seen in v2.1
* New packaged simulator
* New packaged Tablet OS SDK
* Save & Read support for File API
* blobToString() and stringToBlob() support

### Golf Release - Smartphone [September]

This update focuses on architectural enhancements as well as additional desktop platform support in preparation to be used with [[Ripple|https://github.com/blackberry/Ripple-UI]].

Scope:

* Service Oriented Architecture for API extensions to match that of the Tablet OS.  More JavaScript and less Java Scriptable objects.  Based on a RESTful API architecture.
* Mac OS X support


## Previous Releases

### Epsilon Release - Smartphone OS SDK v2.1 [Delivered]

This is an update to the Smartphone SDK focusing on some incremental updates, and bug fixes and the introduction of some new APIs. 

Scope:

* NTLM/BASIC Authentication support
* Improved page rendering speed when not using loading screens
* Top Banner Indicator API (Add icon and number to the banner at the top of the home screen)
* Updates to the Push API with added functionality
* Camera API (take a picture or a video)


### Delta Release - Tablet OS SDK v2.1 [Delivered]

This is an update to the Tablet OS SDK focusing on some incremental updates, bug fixes, permissions configuration and the introduction of some new APIs.  This release also starts to converge some of the functionality currently available on the Smartphone SDK.

Scope:

* In App Payment API
* Camera API (take a picture or a video)
* File API (IO/Properties)
* Microphone API
* PIN API
* Configure permissions for items such as GPS
* Set your home screen category



### Gamma Release [Delivered]

This is a documentation only release.  The core goal for this release is to converge the API documentation for the PlayBook and the 
Smartphone platforms and to provide a better way of navigating the API documentation. 

Scope:

* Updated look and feel
* Combine PlayBook and Smartphone API documentation
* Provide filters for APIs for 5.0, 6.0 & PlayBook
* Provide examples on a per function basis if necessary
* Allow better cross linking of objects
* Provide a Table of Contents view and an Object Listing view for all the APIs
* Add documentation for the HTML5 supported APIs and other application related browser APIs
* Convert our API documentation from library.xml to jsdocs format
* Remove frames from documentation to allow for deep linking
* Upload the new jsdocs, templates, docs build instructions to a new repository in github for community collaboration


### Smartphone SDK 2.0.0 [Delivered]

Scope

* Navigation Mode working with iframes
* Navigation Mode improvements for devices with touch & trackpad
* On-device JavaScript APIs extracted 
* JavaScript APIs now distributed with the SDK
* Allow compiled JARs in JavaScript Extensions
* Allow reference JARs in JavaScript Extensions for linking
* Third party JavaScript extensions no longer need to be packages per application

Remarks

* Further optimizations for Trackpad navigation on BlackBerry 6 with a combination of Touch and Trackpad
* Existing JavaScript APIs that were previously shipped with the OS will be moved into the open source project where the project will no longer have a dependency on OS upgrades for fixes or functionality additions

### Tablet OS SDK 2.0.0.x RTM [Delivered]

* Bug Fixes
* Top Bezel Swipe Gesture
* Revamped Installers
* Splash/Loading Screen support
* Configure orientation to Portrait/Landscape/Both
* Support for "_-." in file names
* Web Inspector Support when using -d command line parameter
* Support for Embedded .swf Flash files


### Smartphone SDK 1.5.1 [Delivered]

Scope

* Re-branding of BlackBerry Widgets to BlackBerry WebWorks
* Distributed installer will now contain code with OSS Apache 2.0 license

Remarks

* Simply an incremental release mainly focused on branding changes
* Source Code uploaded to github

### Smartphone SDK 1.5.0 [Delivered]

Scope

* Caching
* Multiple entry points
* Support for BlackBerry 6 
* SMS JavaScript API
* Audio JavaScript API
* Phone Integration JavaScript API

Remarks

* Source Code uploaded to github 

### Tablet OS SDK 1.0.0.23 Beta 3 [Delivered]

* Bug Fixes

* Additional Loading Screen support for transitions between pages
* Switched to use "-" for command line parameters instead of "/" for better Mac OS X support
* Many Documentation updates

Remarks

* Mainly a bug fix release to fix some critical issues around accessing WebWorks JavaScript APIs

### Tablet OS SDK 1.0.0.2 Beta 2 [Delivered]

* Included application signing tools
* Added loading screen support
* Bug fixes

Remarks

* Main goal of release was to ensure that signing tools were included and to sync with the latest simulator Beta

### Tablet OS SDK 1.0.0.1 Beta 1 [Delivered]

* Initial set of APIs
* Support for building and packaging for Tablet OS

Remarks

* Source code pending to be uploaded to github
