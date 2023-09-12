# Courbet 
- September SCP
- Switch to Perf kernel (thanks to ElXreno)
- Improved lag spikes in some cases
- Switch to Mi Dolby
- Other minor improvments

* frameworks/av
1c48e9e  camera: Expose aux cameras in third party apps  [Pierre-Hugues Husson]
e477f5e  camera2 vndk: Improve error handling  [Emilian Peev]
41fbbfe  camera: Don't segfault if we get a NULL parameter  [Steve Kondik]


* frameworks/base
8583e6d  Camera: Avoid possible NPE after extension session configuration  [Emilian Peev]
3ba7685  camera: Add backwards-compatible CaptureResultExtras constructor  [Adithya R]
e1a4e46  Camera: Prevent crash with prebuilt camera metadata  [Pranav Vashi]
52425dc  Allow sending vendor- or device-specific commands to the camera HAL.  [Danny Baumann]


====================
    09-09-2023     
====================

* build/make
47e04cc  Bump Security String to 2023-09-05  [NurKeinNeid]


* frameworks/av
bece0d2  Merge tag 'android-security-13.0.0_r9' of https://android.googlesource.com/platform/frameworks/av into HEAD  [NurKeinNeid]


* frameworks/base
ba88622  GlobalActionsDialog: Enable blur behind via window flags  [Dhina17]
a47c4d9  DeviceInfoUtils: Read security patch from org.derpfest.build_security_patch  [jhenrique09]
53fb589  Merge tag 'android-security-13.0.0_r9' of https://android.googlesource.com/platform/frameworks/base into 13  [NurKeinNeid]


* frameworks/native
1035899  Merge tag 'android-security-13.0.0_r9' of https://android.googlesource.com/platform/frameworks/native into 13-diff  [NurKeinNeid]


* packages/apps/DerpLauncher
c69b78a  Merge tag 'android-security-13.0.0_r9' of https://android.googlesource.com/platform/packages/apps/Launcher3 into HEAD  [NurKeinNeid]


* packages/apps/Nfc
6b6c3b0  Merge tag 'android-security-13.0.0_r9' of https://android.googlesource.com/platform/packages/apps/Nfc into HEAD  [NurKeinNeid]


* packages/apps/Settings
4fc2773  Settings: storage: Do not skip primary user when listing non-logged in users  [Ramii Ahmed]
f4c4381  Merge tag 'android-security-13.0.0_r9' of https://android.googlesource.com/platform/packages/apps/Settings into HEAD  [NurKeinNeid]


* packages/modules/Bluetooth
f0cd899  Merge tag 'android-security-13.0.0_r9' of https://android.googlesource.com/platform/packages/modules/Bluetooth into HEAD  [NurKeinNeid]


* packages/providers/MediaProvider
6370bbb  Merge tag 'android-security-13.0.0_r9' of https://android.googlesource.com/platform/packages/providers/MediaProvider into HEAD  [NurKeinNeid]


* packages/services/Telephony
dab0f1a  Merge tag 'android-security-13.0.0_r9' of https://android.googlesource.com/platform/packages/services/Telephony into HEAD  [NurKeinNeid]


* vendor/derp
042735c  derp: Add CUSTOM_SECURITY_PATCH prop  [jhenrique09]


====================
    09-08-2023     
====================

* vendor/qcom/opensource/power
3e9a845  power: configs: bengal: Add 5.15 changes and add kernel contition to use  [chrisl7]
63d5069  power: configs: trinket: Add 5.15 changes and add kernel contition to use  [chrisl7]
1235b53  Revert "Power: Using only v3 powerhal version for this branch"  [chrisl7]
9440f33  Merge tag 'LA.VENDOR.13.2.0.r1-19400-KAILUA.0' of https://git.codelinaro.org/clo/la/platform/vendor/qcom-opensource/power into HEAD  [chrisl7]


