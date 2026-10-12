# NA Mate – Privacy Policy

Last updated: 12 October 2026

NA Mate is a field tool of Nature Analytics for biodiversity monitoring. It prepares SD cards of camera traps,
starts AudioMoth recorders with an acoustic chime and shows a test screen for camera test photos.

**In short: NA Mate has no internet access. It does not send any data to Nature Analytics or to anyone else.**

## What the app uses and why

| Data | Why | Where it goes |
|---|---|---|
| Location (GPS) of the phone | Only when no position is passed by KoboCollect: the coordinates of the device being deployed | Written to the SD card (`GPS_info.txt`, `DEPLOYMENT.txt`), played to the AudioMoth in the chime, shown on the test screen |
| Camera | Only to scan the QR code on a device when you tap "Scan" | The image is not stored; only the text of the QR code is used |
| Values passed by KoboCollect on the same phone (device ID, project, location ID, cycle, deployment ID, form ID, name of the person, time) | To write the deployment record | Written to the SD card (`DEPLOYMENT.txt`) and returned to KoboCollect |
| Crash report and the last 50 app events (results and errors of SD card prep, chime and test screen) | To help fix errors | Stored in the app's own storage on the phone. Only when you tap "Send report", the app opens your own e-mail or chat app with this text addressed to Nature Analytics; you see it and decide whether to send it. The app itself sends nothing |

## What the app does not do

- No internet permission: the app cannot transmit data.
- No user accounts, no advertising, no analytics or tracking, no data sale or sharing.
- It only accesses the SD card that you choose yourself; on that card it deletes old files only after you confirm.

## Third-party components

QR code scanning uses ZXing Android Embedded (Apache License 2.0), which works offline and sends no data.

## Your data

The files on the SD card stay with the device and are read by the project team that collects the card. The app
does not keep copies. Uninstalling the app removes the crash report and the event list.

## Children

The app is a work tool for field teams and is not directed at children.

## Contact

NA Nature Analytics GmbH  
Wangener Str. 2, 82319 Starnberg, Germany  
E-mail: koboadmin@natureanalytics.earth

Changes to this policy are published on this page.
