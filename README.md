# VLC Pause Click plugin builds for nightly VLC
Builds of [`vlc-pause-click-plugin`](https://github.com/nurupo/vlc-pause-click-plugin) targeting the nightly, in-development version of VLC.

## Important note!
Note that the nightly VLC is a moving target, VLC developers constantly change its code and break ABI compatibility, so the plugin might stop working or even building due to a change in VLC's code.
Meaning that a plugin targeting a nightly VLC built today might not work with the nightly VLC built tomorrow.
To work around this issue, it's recommended that you use the plugin only with the specific version of VLC that it was built for.
A download link for the specific nightly VLC version that the plugin was built for is provided in the release information and in each of the zip files.

## Disclaimer
Due to the nature of the nightly VLC, the support for it is very limited and low-priority.
The plugin is not guaranteed to work correctly or even work at all.
If the plugin breaks to build against newer nightly VLC versions, it might not get fixed for quite some time.
It's also quite possible that nightly VLC could have its own bugs that prevent the plugin from working that are out of my control to fix.

Well, enough with disclaimers.
I do hope that the plugin works for you and you find it useful.

## Download
See the [latest build](https://github.com/nurupo/vlc-pause-click-plugin-nlightly-builds/releases/tag/ci-nightly-latest).

Visit the [releases](https://github.com/nurupo/vlc-pause-click-plugin-nlightly-builds/releases) page to see all the builds.
Note that only a certain number of builds is kept, older builds get removed.

## Why a separate repository?
Mainly for security reasons -- seting up automated builds like this requires making some security compromises and I didn't want to risk [`vlc-pause-click-plugin`](https://github.com/nurupo/vlc-pause-click-plugin) becoming compromised.

## License
LGPLv2.1+
