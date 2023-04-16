# Battery saving
Some scripts for Battery saving on Linux. These dont include TLP, as it breaks some peripherals

## Disable cores

This does not always help battery, some people say. Surprisingly it also works on OSTree filesystems.

- You can set the resulting scripts as start scripts for KDE profiles for example.
- Or you can use custom udev rules detecting battery or AC state, that set a systemd target, with a systemd service executing the scripts.

Install:

```
wget https://github.com/trytomakeyouprivate/battery-saving/raw/main/setup-core-disabling | bash
```
