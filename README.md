# Super IP — AmneziaWG Android fork

This repository is a maintained fork of [amnezia-vpn/amneziawg-android](https://github.com/amnezia-vpn/amneziawg-android).
It keeps the upstream AmneziaWG protocol and Android application identity while adding practical client features.

## Fork features

- Persistent connection notification while a userspace VPN tunnel is active.
- One-tap **Stop** action in the notification to disconnect without reopening the app.
- Notification opens the AmneziaWG app when tapped.
- Quick Settings tile for one-tap tunnel toggle from Samsung, Xiaomi, Pixel and other Android control panels.

The upstream Play Store build is available at [org.amnezia.awg](https://play.google.com/store/apps/details?id=org.amnezia.awg).

## Building

```
$ git clone --recurse-submodules https://github.com/amnezia-vpn/amneziawg-android
$ cd amneziawg-android
$ ./gradlew assembleRelease
```

macOS users may need [flock(1)](https://github.com/discoteq/flock).
