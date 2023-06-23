# flatpak-repo
My personal flatpak repository

Currently contains:
* `me.timschneeberger.jdsp4linux.pulse` - Legacy PulseAudio flavor of JamesDSP

## Installation

Add the repository:
```bash
sudo flatpak remote-add --if-not-exists thepbones-repo https://raw.githubusercontent.com/ThePBone/flatpak-repo/main/thepbone.flatpakrepo
```
Install a package: 
```bash
sudo flatpak install <APP-ID>
```

> **Note**: Use the `--user` parameter, if you want to add & install packages for your own user account only. No root permissions are required in that case.
