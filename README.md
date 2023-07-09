Courbet:
- Updated to latest Vantom Kernel
- EROFS, F2FS support
- Improve statusbar dimens
- Update system blobs from LA.QSSI.13.0.r1-10000.02-qssi.0
- other minor stuff

====================
    07-07-2023     
====================

* bionic
a385953  Revert "Revert "Switch to jemalloc memory allocator""  [youngherna]


* build/soong
d5a4f80  vndk: Add android.hardware.power-V3-ndk to VndkMustUseVendorVariantList  [klozz]


* frameworks/av
f024a64  camera: Expose aux cameras in third party apps  [Pierre-Hugues Husson]
bb5d0c3  camera2 vndk: Improve error handling  [Emilian Peev]
1d789df  camera: Don't segfault if we get a NULL parameter  [Steve Kondik]


* frameworks/base
8293e28  Camera: Avoid possible NPE after extension session configuration  [Emilian Peev]
12f6bbb  camera: Add backwards-compatible CaptureResultExtras constructor  [Adithya R]
072c87f  Camera: Prevent crash with prebuilt camera metadata  [Pranav Vashi]
4074910  Allow sending vendor- or device-specific commands to the camera HAL.  [Danny Baumann]


* vendor/derp
ecdc558  Merge pull request #42 from CrisBalGreece/13  [Alexander Brunswig]


====================
    07-06-2023     
====================

* build/make
dab591f  Merge tag 'android-13.0.0_r61' of https://android.googlesource.com/platform/build into HEAD  [NurKeinNeid]


* frameworks/av
e456144  Merge tag 'android-13.0.0_r61' of https://android.googlesource.com/platform/frameworks/av into HEAD  [NurKeinNeid]


* frameworks/base
a512475  PixelPropsUtils: Update for July 2023 security patch  [NurKeinNeid]
666a626  base: Do not reset keyguard going away state  [minarypenguin]
865b96f  Merge tag 'android-13.0.0_r61' of https://android.googlesource.com/platform/frameworks/base into HEAD  [NurKeinNeid]
9a18614  Merge pull request #15 from DF-Whyred/13  [Alexander Brunswig]


* manifest
2ad27ed  manifest: July 2023 Security update  [Michael Bestas]
3edf666  Merge tag 'android-13.0.0_r61' of https://android.googlesource.com/platform/manifest into HEAD  [NurKeinNeid]


* packages/apps/Settings
af951d2  Merge tag 'android-13.0.0_r61' of https://android.googlesource.com/platform/packages/apps/Settings into HEAD  [NurKeinNeid]


* packages/modules/Wifi
1607baa  Merge tag 'android-13.0.0_r61' of https://android.googlesource.com/platform/packages/modules/Wifi into HEAD  [NurKeinNeid]


====================
    07-05-2023     
====================

* frameworks/av
d057293  Merge pull request #4 from Klozz/13  [Alexander Brunswig]


* frameworks/base
6cea036  SystemUI: Enable and tune Split notification shade  [minaripenguin]


* manifest
63b96c6  Manifest for Android 13.0.0 Release 61  [The Android Open Source Project]


* packages/modules/Bluetooth
b9c5c6a  Merge pull request #1 from Klozz/13  [Alexander Brunswig]


* vendor/derp
da841c4  Merge pull request #41 from TheStrechh/13  [Alexander Brunswig]
b363870  devices: Add le_x2 (LeEco LeMax2)  [CrisBal]
fdaa5b0  devices: Add Poco X5 Pro 5G (redwood)  [Carlos Arriaga]


====================
    07-04-2023     
====================

* packages/apps/Aperture
ed10abf  Merge pull request #1 from amanrajOO7/13  [Alexander Brunswig]
