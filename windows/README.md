# Windows HDC CLI

This folder contains the standalone Windows HarmonyOS HDC command-line tool.

## Connect over Wi-Fi

Open PowerShell or Command Prompt in this folder and run:

```text
hdc.exe tconn DEVICE_IP:PORT
hdc.exe list targets
```

For example:

```text
hdc.exe tconn 192.168.8.105:39159
```

## Install a HAP package

After the device is connected, install a package with:

```text
hdc.exe install path\to\app.hap
```

This is only the HDC CLI bundle. It does not include the HarmonyOS SDK, APIs,
project files, or build tools.
