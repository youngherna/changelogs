====================
    07-18-2023     
====================

* bionic
7c6a94d  Revert "Revert "Switch to jemalloc memory allocator""  [youngherna]


* build/soong
f3197e4  vndk: Add android.hardware.power-V3-ndk to VndkMustUseVendorVariantList  [klozz]


* frameworks/av
a8acab8  camera: Expose aux cameras in third party apps  [Pierre-Hugues Husson]
a9468e6  camera2 vndk: Improve error handling  [Emilian Peev]
3ab3506  camera: Don't segfault if we get a NULL parameter  [Steve Kondik]


* frameworks/base
71f5cbe  Camera: Avoid possible NPE after extension session configuration  [Emilian Peev]
1db16e1  camera: Add backwards-compatible CaptureResultExtras constructor  [Adithya R]
1674750  Camera: Prevent crash with prebuilt camera metadata  [Pranav Vashi]
bf6c471  Allow sending vendor- or device-specific commands to the camera HAL.  [Danny Baumann]
e32d1f0  core: Catch OOB when returning pooled string  [minaripenguin]
6394aac  core: Workaround for bad base64  [minaripenguin]
016f4d5  core: Workaround for ASI crash  [minaripenguin]
5eda8b9  PixelPropUtils: refactor  [aswin7469]
a6b0e63  PixelPropsUtils: Remove pixel whitelist  [jhenrique09]
a386be1  base: ApplicationPackageManager: Exclude PE 2021 Midyear from tensor pixel list  [someone5678]
b5043c9  base: ApplicationPackageManager: Block Tensor features for Recorder  [someone5678]
d1fb5d0  SystemUI: Fix battery color on QS for circle battery styles  [Pranav Vashi]
a6384db  Revert "hwui: renderthread/CanvasContext: Reduce the timeout for dequeueing buffers"  [exactxmpl]


* vendor/derp
6ab4c93  Merge pull request #48 from AbrarNoob/patch-1  [Alexander Brunswig]
56ad192  Merge pull request #49 from FPSensor/patch-1  [Alexander Brunswig]
abdc03f  devices: add Motorola Khaje devices  [FPSensor]


====================
    07-17-2023     
====================

* vendor/derp
3935df6  devices: add alioth (Poco F3/Mi 11x)  [Hasin Abrar Haque]


====================
    07-16-2023     
====================

* frameworks/base
6a1f057  fixup! BatteryService: Add SuperDart charging support  [NurKeinNeid]


* packages/apps/Aperture
21ece78  Merge pull request #2 from amanrajOO7/13  [Alexander Brunswig]


* vendor/derp
e350a04  Merge pull request #47 from hac4us06/13  [Alexander Brunswig]


====================
    07-15-2023     
====================

* packages/apps/Aperture
033c7c2  Merge branch 'lineage-20.0' of https://github.com/LineageOS/android_packages_apps_Aperture into HEAD  [Aman Singh]


====================
    07-14-2023     
====================

* frameworks/base
262a68a  Merge pull request #18 from Codecity001/13  [Alexander Brunswig]


* packages/apps/Aperture
c1472a0  Aperture: Simplify flash mode handling  [Sebastiano Barezzi]
9e0a3f7  Aperture: CameraActivity: Get rid of update{PrimaryBar,CameraMode}Buttons()  [Sebastiano Barezzi]
a1cad08  Aperture: Use the view model for views' rotation  [Sebastiano Barezzi]
1a512eb  Aperture: Introduce CameraViewModel  [Sebastiano Barezzi]


