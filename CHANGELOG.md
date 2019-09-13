# Nova Video Player changelog

## Important notes:
- migrating from v3 or v4 to v2 will delete all your scraping information

## v4.x current git (unstable)
Unstable branch: this release is based on minSDK 21, targetSDK 28, AndroidX libraries, NDK-r20, ffmpeg 4.2.

## v3.x current git (testing)
Testing branch: this release is based on minSDK 21, targetSDK 27, NDK-r20, ffmpeg 4.2.

## v2.x current git (stable)
Stable branch: this release is based on minSDK 17, targetSDK 27, NDK-r16b, ffmpeg 3.3.x.

## v4.13 unstable branch release - 8/9/2019
"Not so much anymore unstable branch": this release is based on minSDK 21, targetSDK 28, AndroidX libraries, NDK-r20, ffmpeg 4.2.
- Switch to AudioTrack instead of openSLES to solve audio/video delay on some devices
- Disable for now UpNext row/channel preventing display of indexed folders
- Upgrade trakt-java library to solve two way sync

## v4.12 unstable branch release - 29/8/2019
"Not so much anymore unstable branch": this release is based on minSDK 21, targetSDK 28, AndroidX libraries, NDK-r20, ffmpeg 4.2.
- Fix HEVC decoding for some files on MTK based devices
- Do not revert on SW decoding in presence of high bitrate spike occurring on some 4k high bitrate videos

## v4.11 unstable branch release - 28/8/2019
"Not so much anymore unstable branch": this release is based on minSDK 21, targetSDK 28, AndroidX libraries, NDK-r20, ffmpeg 4.2.
- Fix coexistence with Archos Video Player

## v4.10 unstable branch release - 22/8/2019
"Not so much anymore unstable branch": this release is based on minSDK 21, targetSDK 28, AndroidX libraries, NDK-r20, ffmpeg 4.2.
- Fix video blacklisting on local storage

## v4.9 unstable branch release - 21/8/2019
"Not so much anymore unstable branch": this release is based on minSDK 21, targetSDK 28, AndroidX libraries, NDK-r20, ffmpeg 4.2.
- FFmpeg upstep to 4.2 and dav1d to 0.4.0
- Fix database crash preventing application to start on some custom ROMs

## v4.8 unstable branch release - 2/8/2019
Unstable branch: this release is based on minSDK 21, targetSDK 28, AndroidX libraries, NDK-r20, ffmpeg 4.2.
- Fix database crash preventing application to start on some devices

## v4.7 unstable branch release - 15/6/2019
Unstable branch: this release is based on minSDK 21, targetSDK 28, AndroidX libraries, NDK-r20, ffmpeg 4.2.
- Improve audio passthrough robustness
- Fix authentication issue with Trakt

## v3.11 Google Play beta release - 15/6/2019
Testing branch: this release is based on minSDK 21, targetSDK 27, NDK-r20, ffmpeg 4.2.
- Improve audio passthrough robustness

## v3.10 Google Play release - 9/6/2019
Testing branch: this release is based on minSDK 21, targetSDK 27, NDK-r19c, ffmpeg 4.2.
- Fix authentication issue with Trakt

## v4.6 unstable branch release - 3/6/2019
Unstable branch: this release is based on minSDK 21, targetSDK 28, AndroidX libraries, NDK-r19c, ffmpeg 4.2.
- Attempt to fix UPnP playback of files containing a "/"
- Do not crash when opening non-video files in browser
- Stability improvements

## v3.9 Google Play beta release - 1/6/2019
Testing branch: this release is based on minSDK 21, targetSDK 27, NDK-r19c, ffmpeg 4.2.
- Attempt to fix UPnP playback of files containing a "/"
- Do not crash when opening non-video files in browser
- Stability improvements

## v4.5 unstable branch release - 30/5/2019
Unstable branch: this release is based on minSDK 21, targetSDK 28, AndroidX libraries, NDK-r19c, ffmpeg 4.2.
- Fix files cannot play from external sdcard using an external player
- AndroidTV: fix EpisodesByDate week view crash in case of large TV show collection

## v3.8 Google Play release - 30/5/2019
Testing branch: this release is based on minSDK 21, targetSDK 27, NDK-r19c, ffmpeg 4.2.
- Fix files cannot play from external sdcard using an external player

## v4.3 unstable branch release - 19/5/2019
Unstable branch: this release is based on minSDK 21, targetSDK 28, AndroidX libraries, NDK-r19c, ffmpeg 4.2.
- Scanning and scraping proper Notifications
- Add an option to force disabling stereo downmix on phones/tablets with Android version > N
- AndroidTV: add pinning on long press for all movies/tvshows
- New TV show categories for quicker browsing through large collection
- Countless TV UI improvements (roles, trailers, badges, global del/deindex, subs picker)
- New player shortcuts (A/S switch audio/sub track, U/D = volume up/down) and menu support
- Improve audio passthrough stability
- Fix sftp playback interruptions
- Make private mode persistent
- Fix cloud support (still no streaming)- AndroidTV: add poster/backdrop zoom on long press
- AndroidTV: add tvshow episodes by date view
- Fix sftp playback interruptions
- Fix an android Q DP3 crash

## v2.2 stable branch release - 19/5/2019
Stable branch: this release is based on minSDK 17, targetSDK 27, NDK-r16b, ffmpeg 3.3.x.
- New TV show categories for quicker browsing through large collection
- Countless TV UI improvements (roles, trailers, badges, global del/deindex, subs picker)
- New player shortcuts (A/S switch audio/sub track, U/D = volume up/down) and menu support
- Improve audio passthrough stability
- Fix sftp playback interruptions
- Make private mode persistent
- Fix cloud support (still no streaming)
- Fix an android Q DP3 crash

## v3.7 Google Play release - 24/5/2019
Testing branch: this release is based on minSDK 21, targetSDK 27, NDK-r19c, ffmpeg 4.2.
- Fix software decoding fallback in case of error
- Re-enable downmix on phones to avoid voice channels loss on some phones
- Stability improvements
- Upgrade to latest ffmpeg and dav1d soft codecs
- Fix an android Q DP3 crash

## v4.2 API28+AndroidX beta release - 27/4/2019
Unstable branch: this release is based on minSDK 21, targetSDK 28, AndroidX libraries, NDK-r19c, ffmpeg 4.2.
- Option to have landscape fullscreen video on display with cutouts
- AndroidX migration
- Poster/backdrop zoom on AndroidTV via long press
- Improve stability of phone/tablet UI after API28 migration
- New A-Z orb option in All TV shows/Movies for alphabetical order browsing
- New all/not viewed orb option in All TV shows/Movies for limiting browsing to all/not viewed videos

## v3.6 Google Play beta release - 27/4/2019
Testing branch: this release is based on minSDK 21, targetSDK 27, NDK-r19, ffmpeg 4.2.
- Upgrade to latest ffmpeg and dav1d soft codecs

## v3.5 release candidate - 17/4/2019
Testing branch: this release is based on minSDK 21, targetSDK 27, NDK-r19, ffmpeg 4.2.
- Fix software decoding on pre-M Android versions

## v4.1 API28 beta release - 8/4/2019
Unstable branch: this release is based on minSDK 21, targetSDK 28, AndroidX libraries, NDK-r19, ffmpeg 4.2.
- New video overview
- Leanback style settings on AndroidTV
- Add recently added TV channels
- Improved subtitles picker wizard look
- API28 migration

## v3.3.1 Google Play beta release - 11/3/2019
Testing branch: this release is based on minSDK 21, targetSDK 27, NDK-r19, ffmpeg 4.2.
- New TV show categories on TV interface for quicker browsing through large collection
- Countless TV UI improvements (player look and feel, roles, movies trailers, audio badges, global deleletion/de-indexation, subtitles picker, more dynamic banners)
- New player shortcuts (A/S switch audio/sub track, U/D = volume up/down) and menu support
- Improve audio passthrough stability
- Fix crash in presence of damaged sdcard
- Fix cloud support (still no streaming)
- Do not downmix to stereo on phones/tablets if Android is recent enough (N): delegate to Android

## v3.4 special SMBv2/3 test release (experimental) - 18/3/2019
Testing branch: this release is based on minSDK 21, targetSDK 27, NDK-r19, ffmpeg 4.2.
- SMBv2/3 support via jcifs-ng
- Ability to deindex local folders

## v3.1 Google Play beta release 3/2/2019
Testing branch: this release is based on minSDK 21, targetSDK 27, NDK-r19, ffmpeg 4.2.
- New TV show categories on TV interface for quicker browsing through large collection

## v3.0 Google Play beta release - 30/1/2019
Testing branch: this release is based on minSDK 21, targetSDK 27, NDK-r19, ffmpeg 4.2.
- Migration from Android ndk-r17 to ndk-r19
- Add AV1 soft decoding capability through 4.2-dev ffmpeg version and dav1d codec
- Add support for x86_64 architecture
- Improve audio passthrough stability
- Make private mode persistent between application relaunches

## v2.1 Google Play public release - 20/9/2018
Stable branch: this release is based on minSDK 17, targetSDK 27, NDK-r16b, ffmpeg 3.3.x.
- Improved french translations and interfacing with crowdin service
- Stability improvements

## v2.0 Google Play public release - 7/9/2018
Stable branch: this release is based on minSDK 17, targetSDK 27, NDK-r16b, ffmpeg 3.3.x.
- Scraper improvements and bug fixes
- Issue a warning toast is hardware decoding is disabled

## v1.0 Initial Google Play public release - 26/8/2018
Compared to Archos Video Player open source release, following changes were made:
- Add support for Android P avoiding application crash at startup
- Add a "list episodes" button on tvshow episode view to quickly get to tvshow view on AndroidTV leanback version
- Add notification channels for Oreo
- Fix subtitle delay not applied on play resume when negative
- Fix floating player crash on Android version Oreo and above
- Fix loss of activity background and private mode background
- Prevent from playing a file when detecting a problem: issue a toast instead