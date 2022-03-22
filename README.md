About
-----

The self-proclaimed “noisy band” [65daysofstatic](https://65daysofstatic.com/) have a procedurally-generated YouTube channel called [Wreckage Systems](https://www.youtube.com/65propaganda/live). The current version is version 2.

Subscribers to their [Patreon](http://www.wreckage.systems/) can download [the software that powered version 1](https://65labs.itch.io/wreckage-systems-v1-archive) for Windows, Mac, and Linux. At least on Linux, it's provided as a zip archive that you can just extract and run.

But perhaps, like me, you like your software to have modern niceties like “a launcher”, and to be installed with [Flatpak](https://flatpak.org/). If so, the manifest in this repo allows you to do this.

Usage
-----

1. Subscribe to [Wreckage Systems](http://www.wreckage.systems/) on Patreon
1. Clone this repo
1. Download the Linux archive from https://65labs.itch.io/wreckage-systems-v1-archive into this directory
1. Run the following command:


```bash
flatpak-builder --install --force-clean --user _app com._65daysofstatic.WreckageSystemsV1.yaml
```
