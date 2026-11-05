# JustPlayVideo (JPV)

A lightweight video player for **Windows 11, 64-bit**, focused on local playback and picture quality.

## Features

- Native playback using Windows Media Foundation and Direct3D 11.
- An optional, experimental mpv playback engine for broader format support.
- Drag-and-drop opening, seeking, volume controls and full screen.
- Options to remember window size and playback position.
- Audio-track and subtitle selection when using the mpv engine.

## Download and install

Open the **Releases** section of this repository and download **JustPlayVideo-<version>-Setup.exe** from the release assets.

Close an existing instance of JustPlayVideo, run the installer and follow its instructions. Installation is for the current Windows user and does not require administrator rights.

The automatic **Source code (zip)** and **Source code (tar.gz)** links are repository archives, not the Windows installer.

## Playback engines and formats

The native engine uses Windows codecs. Format support depends on the codecs and media components installed on the computer; HEVC/H.265, AV1 and VP9 may require additional Windows codec support. Windows 11 N requires the Media Feature Pack.

The optional **mpv** engine is not bundled with the installer. It can be downloaded during installation or later from **Options > Playback engine > Download the mpv engine...**. This optional download requires an internet connection. After selecting mpv as the playback engine, restart the player.

The mpv engine is the work of the [mpv developers and contributors](https://mpv.io). Downloaded Windows builds come from [zhongfly/mpv-winbuild](https://github.com/zhongfly/mpv-winbuild).

## Third-party notices

Third-party notices are included with the installed application in the **ThirdParty** folder. A downloaded mpv build has its own applicable licenses and provenance information.

