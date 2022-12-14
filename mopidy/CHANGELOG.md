## 2.1.1 - 2022-04-11

* π Fix alpine package repositories
* β Removed fixed tornado version


## 2.1.0 - 2022-04-05

* πΌ Update alpine to `3.14`
* πΌ Update Mopidy-Iris to `3.62.0`
* πΌ Update Mopidy-MPD to `3.2.0`
* πΌ Update python3 to `3.9.5-r2`
* πΌ Update ca-certificates to `20211220-r0`
* πΌ Update sudo to `1.9.7_p1-r1`
* π Updated config.json and Readme


## 2.0.1 - 2020-06-03

* πΌ Update python3 to `3.9.5-r1`
* π Specifiy own S6 entrypoint, don't rely on the base image.


## 2.0.0 - 2020-05-02

* β¨ Resurrect Mopidy
* πΌ Update Mopidy to `3.1.1-r3`
* π¨ Use Alpine as base image
* π¨ Migrate to new `devices` option format. Thanks @LiJu09

### β οΈ Breaking Change β οΈ

When coming from a previous version validate your settings, since the addon got completly redone!


## 1.2.3 - 2020-05-22

* π¨ Updated Changelog to new format
* πΈοΈ Marked as deprecated


## 1.2.2 - 2020-02-09

### Changed

* π¨ Start mopidy as `system` startup


## 1.2.1 - 2020-02-07

* π½ Downgrade Mopidy to `2.2.2-1`
* πΌ Use mopidy-youtube `2.1.0`
* πΌ Update youtube-dl to `2020.1.24`


## 1.2.0 - 2019-12-06

* β Use Youtube-Mopidy integration from [@natumbri](https://github.com/natumbri/mopidy-youtube)
* πΌ Updated Mopidy to `2.3.1-1`
* πΌ Updated youtube-dl to `2019.11.28`
* πΌ Update certifi to same version as youtube-dl
* π¨ More startup logging


## 1.1.0 - 2019-10-19

* πΌ Updated OS to debian buster (thanks @Nickerchen)
* β Removed aarch64 support


## 1.0.0 - 2019-10-16

* π¨ Set mopidy version to `2.1.0-1`
* β Own versioning starting with 1.0.0
* β Added example config setting for media dir
* π Fixed ALSA not forwarding sound correctly


## 2.2.3 - 2019-10-06 (old versioning)

* β Put mopidy 2.2.3-1 inside the addon.
* π¨ Added device mapping for `/dev/snd`
* π¨ Adjust mopidy version for aarch64 systems. It will be the version `2.1.0-1` on those systems.
