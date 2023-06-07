# Debloat Instructions

This document provides a list of safe-to-uninstall apps and the corresponding adb shell commands to remove them from your Lenovo Tab M10 tablet. These commands will help you debloat your device and reclaim storage space. Please note that removing system apps can potentially affect the functionality of your device. Make sure you understand the risks involved and backup any important data before proceeding.

## Prerequisites

Before you begin, ensure that you have the following:

- A Lenovo Tab M10 tablet
- A computer with ADB (Android Debug Bridge) installed
- USB debugging enabled on your tablet

## Debloat Commands

Below is a list of safe-to-uninstall apps along with the corresponding adb shell commands. Open a terminal or command prompt on your computer and execute these commands one by one:

- `adb shell pm uninstall -k --user 0 com.android.chrome`
- `adb shell pm uninstall -k --user 0 com.google.android.apps.docs`
- `adb shell pm uninstall -k --user 0 com.google.android.apps.maps`
- `adb shell pm uninstall -k --user 0 com.google.android.apps.photos`
- `adb shell pm uninstall -k --user 0 com.google.android.apps.tachyon`
- `adb shell pm uninstall -k --user 0 com.google.android.gm`
- `adb shell pm uninstall -k --user 0 com.google.android.googlequicksearchbox`
- `adb shell pm uninstall -k --user 0 com.google.android.music`
- `adb shell pm uninstall -k --user 0 com.google.android.talk`
- `adb shell pm uninstall -k --user 0 com.google.android.videos`
- `adb shell pm uninstall -k --user 0 com.google.android.youtube`
- `adb shell pm uninstall -k --user 0 com.android.bips`
- `adb shell pm uninstall -k --user 0 com.android.bluetoothmidiservice`
- `adb shell pm uninstall -k --user 0 com.android.bookmarkprovider`
- `adb shell pm uninstall -k --user 0 com.android.carrierconfig`
- `adb shell pm uninstall -k --user 0 com.android.carrierdefaultapp`
- `adb shell pm uninstall -k --user 0 com.android.dreams.basic`
- `adb shell pm uninstall -k --user 0 com.android.dreams.phototable`
- `adb shell pm uninstall -k --user 0 com.android.egg`
- `adb shell pm uninstall -k --user 0 com.android.htmlviewer`
- `adb shell pm uninstall -k --user 0 com.android.inputdevices`
- `adb shell pm uninstall -k --user 0 com.android.managedprovisioning`
- `adb shell pm uninstall -k --user 0 com.android.printspooler`
- `adb shell pm uninstall -k --user 0 com.android.providers.partnerbookmarks`
- `adb shell pm uninstall -k --user 0 com.android.simappdialog`
- `adb shell pm uninstall -k --user 0 com.android.stk`
- `adb shell pm uninstall -k --user 0 com.android.wallpaper.livepicker`
- `adb shell pm uninstall -k --user 0 com.android.wallpapercropper`
- `adb shell pm uninstall -k --user 0 com.caf.fmradio`
- `adb shell pm uninstall -k --user 0 com.netflix.mediaclient`
- `adb shell pm uninstall -k --user 0 com.netflix.partner.activation`
- `adb shell pm uninstall -k --user 0 com.qti.qualcomm.datastatusnotification`
- `adb shell pm uninstall -k --user 0 com.qti.service.colorservice`
- `adb shell pm uninstall -k --user 0 com.qualcomm.atfwd`
- `adb shell pm uninstall -k --user 0 com.qualcomm.embms`
- `adb shell pm uninstall -k --user 0 com.qualcomm.location`
- `adb shell pm uninstall -k --user 0 com.qualcomm.qcrilmsgtunnel`
- `adb shell pm uninstall -k --user 0 com.qualcomm.qti.auth.fidocryptoservice`
- `adb shell pm uninstall -k --user 0 com.qualcomm.qti.dynamicddsservice`
- `adb shell pm uninstall -k --user 0 com.qualcomm.qti.lpa`
- `adb shell pm uninstall -k --user 0 com.qualcomm.qti.perfdump`
- `adb shell pm uninstall -k --user 0 com.qualcomm.qti.qms.service.connectionsecurity`
- `adb shell pm uninstall -k --user 0 com.qualcomm.qti.qms.service.telemetry`
- `adb shell pm uninstall -k --user 0 com.qualcomm.qti.remoteSimlockAuth`
- `adb shell pm uninstall -k --user 0 com.qualcomm.qti.simsettings`
- `adb shell pm uninstall -k --user 0 com.qualcomm.qti.telephonyservice`
- `adb shell pm uninstall -k --user 0 com.qualcomm.qti.uim`
- `adb shell pm uninstall -k --user 0 com.qualcomm.timeservice`
- `adb shell pm uninstall -k --user 0 com.quicinc.cne.CNEService`
- `adb shell pm uninstall -k --user 0 org.codeaurora.ims`
- `adb shell pm uninstall -k --user 0 com.motorola.demo`
- `adb shell pm uninstall -k --user 0 com.android.wantjoin.settings`
- `adb shell pm uninstall -k --user 0 com.lenovo.launcher.provider`
- `adb shell pm uninstall -k --user 0 com.android.protips`
- `adb shell pm uninstall -k --user 0 com.lenovo.smarttabm10`
- `adb shell pm uninstall -k --user 0 com.lenovo.dsa`
- `adb shell pm uninstall -k --user 0 com.lenovo.lsf`
- `adb shell pm uninstall -k --user 0 com.lenovo.ota`
- `adb shell pm uninstall -k --user 0 com.tblenovo.launcher`
- `adb shell pm uninstall -k --user 0 amazon.speech.sim`
- `adb shell pm uninstall -k --user 0 com.lenovo.ue.device`
- `adb shell pm uninstall -k --user 0 com.android.wantjoin.childmode.ctrl`
- `adb shell pm uninstall -k --user 0 com.tblenovo.lenovotips`
- `adb shell pm uninstall -k --user 0 com.lenovo.lsf.device`
- `adb shell pm uninstall -k --user 0 com.lenovo.screencapture`
- `adb shell pm uninstall -k --user 0 com.lenovo.loggerpannel`
- `adb shell pm uninstall -k --user 0 com.tblenovo.whatsnewclient`
- `adb shell pm uninstall -k --user 0 com.lenovo.tabm10`
- `adb shell pm uninstall -k --user 0 com.lenovo.screenassistant`
- `adb shell pm uninstall -k --user 0 com.tblenovo.lewea`
- `adb shell pm uninstall -k --user 0 com.tblenovo.setup`
- `adb shell pm uninstall -k --user 0 com.lenovo.defaultlaunch`
- `adb shell pm uninstall -k --user 0 jp.co.fsi.fskaren.lenovo`
- `adb shell pm uninstall -k --user 0 com.tblenovo.whatsnewhost`
- `adb shell pm uninstall -k --user 0 com.tblenovo.wallpaper`
- `adb shell pm uninstall -k --user 0 com.tblenovo.soundrecorder`

Please note that this is not an exhaustive list, and there may be other apps specific to your device that you may want to uninstall. Use these commands as a starting point and exercise caution while removing any system apps.

## Disclaimer

The instructions and commands provided in this repository are intended for advanced users who understand the risks involved in removing system apps. Removing system apps can potentially affect the functionality of your device. The author and contributors of this repository are not responsible for any damage or issues that may occur as a result of following these instructions. Proceed at your own risk.
