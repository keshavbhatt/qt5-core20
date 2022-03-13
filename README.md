
# Qt5-core20
Qt 5 runtime as content snap

This snap is to be consumed by various Qt apps that require Qt5 runtime. This snap will auto-connect and provide for an application published by [keshavnrj](https://snapcraft.io/search?q=keshavnrj). Other Developers who want to use this as their base can explicitly ask to auto-connect their app snap from store admin by writing a forum post in [snapcraft forums](https://forum.snapcraft.io/).

## Technical information about qt5-core20 content snap:

- Qt libraries and runtime is provided by Official Ubuntu Focal Fossa repositories.
- There are few more packages which are used by consumer of this content snap like:
 - mpv, ffmpeg, socat, wget, xclip, coreutils
- The consumer snaps need to launch their apps using the provided [desktop-launch](https://github.com/keshavbhatt/qt5-core20/blob/main/snap_launcher/bin/desktop-launch) script or atleast use this in their command chain. One example consumer of this content snap is [olivia](https://github.com/keshavbhatt/olivia), read the snap/snapcraft.yaml file in olivia's repo to see how to consume this snap as runtime.
- Current consumers of qt5-core20 content snap are listed and updated [here](https://gist.github.com/keshavbhatt/b7921fdae94d1f43d677833d4556f182)
- While committing this line to the readme, the daily active users count for this [Qt551](https://snapcraft.io/qt551) content snap is ~58,814 devices as reported by the Snapcraft metrics dashboard. This snap will replace the Qt551 snap gradually. 
