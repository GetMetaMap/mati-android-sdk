---
title: "Android Changelog"
excerpt: "MetaMap's Android SDK Changelog"
slug: "android-changelog"
category: 61ae8e8dba577a0010791480
hidden: true
---

# Feedback

If you have an issue or ideas to improve MetaMap's Android SDK, please look at our [issues](https://github.com/GetMetaMap/metamap-android-sdk/issues) page to see if your issue has been reported or to add your own.


# Version 3.22.3
###### 29 June 2022

#### Bug Fixes
* UserAgent information update which will fix the bug related to the device information in the dashboard
* Captured media files are being removed right after they will no longer be re-used
* Fixed bug when the app language could remain the same after the language was changed several times
* Fixed: `JSONException: No value for inputId`
* Fixed: `IllegalStateException: KoinApplication has not been started`
* Fixed: `NullPointerException: Attempt to invoke virtual method 'int android.view.Display.getRotation()' on a null object reference`

#### Updated Features
Removed library `androidx.cardview:cardview`
Removed library `org.jetbrains.kotlin:kotlin-stdlib-jdk7`
Removed library `androidx.fragment:fragment-ktx`
Removed library `androidx.core:core-ktx`
Removed library `androidx.lifecycle:lifecycle-runtime-ktx`
Removed library `androidx.navigation:navigation-dynamic-features-fragment`


# Version 3.22.2
###### 15 June 2022

#### Bug Fixes
* Fixed: IllegalStateException: KoinApplication has not been started
* `metamap_` prefix added to all keys for string resources to avoid any conflicts with the client applications
* Resolved Github issue: https://github.com/GetMetaMap/metamap-android-sdk/issues/37



# Version 3.22.1
###### 03 June 2022

#### Bug Fixes
* Fixed `IllegalStateException` A recording is already in progress. Previous recordings must be stopped before a new recording can be started.
* Document icon fix in the hint screen
* Fixed ProgressBar overlap on email code submission screen
* Translations fixed on the first screen for Bank, Work, Payroll Data and CustomInput products



# Version 3.22.0
###### 27 May 2022

#### New Features
* Location Intelligence step support added

#### Updated Features
* Metadata builder updated. Method `with` was marked as deprecated

#### Bug Fixes
* Icons for Bank, Payroll, Work Account Data and Custom Input products became visible on the first page
* Fixed: the button on the first page didn’t work after language change
* Custom Document hint text and icon overlap bug fixed



# Version 3.21.6
###### 21 May 2022
  
#### Bug Fixes
* Face detector bugfix during selfie verification



# Version 3.21.5
###### 18 May 2022

#### Updated Features
* National Id documents are loaded dynamically

#### Bug Fixes
* Minor improvements



# Version 3.21.4
###### 14 May 2022
  
#### New Features
* Custom Input support added

#### Updated Features
* Terms and Conditions and our Privacy policy link updated
* CameraX version upgraded to 1.1.0-rc01

#### Bug Fixes
* Fixed resend countdown in email verification screen
* Other fixes and improvements



# Version 3.21.3
###### 11 May 2022

#### Updated Features
* CameraX version upgraded to 1.1.0-beta03

#### Bug Fixes
* Bugfix: InvalidConfigException: Surface was requested when the Recorder had encountered error. Encoder cannot created: null



# Version 3.21.2
###### 20 April 2022

#### Updated Features
* Resources names changed

#### Bug Fixes
* Exit screen button UI bug fix


# Version 3.21.1
###### 14 April 2022

#### Bug Fixes
* Hotfix: Document upload errors are handled correctly now



# Version 3.21.0
###### 14 April 2022

#### Updated Features
* Reduced SDK size
* Added required documents screen
* Skip back side for Documents
* Changed subtypes for Panama and Nigeria

#### Removed Features
`com.github.mhiew:android-pdf-viewer` dependency removed



# Version 3.20.0
###### 01 April 2022
  
#### Updated Features
* Document subtypes support added for each document issuing country
* Face detection feature added to selfie
* No internet connection and internal server errors support added

#### Bug Fixes
* Fix: Now two applications using MetaMap can be installed on one device



# Version 3.19.1
###### 22 March 2022
  
#### Updated Features
* CameraX version upgraded to 1.1.0-beta02

#### Bug Fixes
* Camera crash fixed. Github [issue: #33](https://github.com/GetMetaMap/metamap-android-sdk/issues/33)
* Proguard obfuscation issue in debug mode fixed when using proguard-android-optimized.txt file



# Version 3.19.0
###### 16 March 2022
  
#### Bug Fixes
* Proguard obfuscation issue in debug mode fixed
* Koin conflict with the client app eliminated
* Issue with app restoration after being killed fixed



# Version 3.18.0
###### 14 March 2022
  
#### Bug Fixes
* HotFix: Metamaps containing e-signature will be seen in the verifications dashboard



# Version 3.17.0
###### 03 March 2022
  
#### Bug Fixes
* Hotfix: Esign step sent to the end of the flow



# Version 3.16.0
###### 25 February 2022
  
#### New Features
* Added support for OnActivityResult

#### Updated Features
* Translations updated



# Version 3.15.0
###### 24 February 2022
  
#### New Features
* Credit check consent added
* Activity Result API is used to get the SDK result instead of the deprecated onActivityResult method

#### Updated Features
* Rebranding conducted
* UI refactoring, added support for different screen sizes
* Resources renamed to avoid conflicts
* Added mechanism to remove temporary files to reduce SDK size
* `androidx.cardview:cardview` dependency added `1.0.0`
* `androidx.window: window` dependency added `1.0.0`
* `CameraX` version upgraded to `1.1.0-beta01`
* `androidx.constraintlayout:constraintlayout` version upgraded to `2.1.2`
* `org.jetbrains.kotlin:kotlin-stdlib-jdk7` version upgraded to `1.5.21`
* `androidx.core:core-ktx` version upgraded to `1.7.0`
* `org.jetbrains.kotlinx:kotlinx-serialization-json` version upgraded to `1.3.2`
* `com.github.mhiew:android-pdf-viewer` version upgraded to `3.2.0-beta.1`

#### Removed Features
* Material library removed

#### Bug Fixes
* Phone number validation issue fixed
* SecurityException fixed
* Metadata fixedLanguage issue eliminated
* Translation corrected: "cargar" became "cargando"



# Version 3.14.0
###### 09 February 2022

#### Updated Features
* Support for Brazilian NID CPF number manual entry



# Version 3.13.0
###### 28 January 2022
  
#### New Features
* Financial dynamic web containers added

#### Updated Features
* Face masks detection error support added
* Added support for localized SMS confirmation messages for phone verification step
* Added support for localized email confirmation messages for email verification step




<!-- Note to developers: copy/paste the template below for each version. Delete categories that don't apply the the release

# Version
###### Date
  
#### New Features
* <new feature>

#### Updated Features
* <changes in existing functionality>

#### Deprecated Features
* <soon-to-be removed features>

#### Removed Features
* <removed features>

#### Bug Fixes
* <bug fixes>

#### Security Vulnerabilities
* <known vulnerabilities>
-->