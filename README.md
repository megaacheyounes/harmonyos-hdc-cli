# HarmonyOS HDC CLI

Standalone platform bundles for the HarmonyOS HDC command-line tool.

HDC is used to connect to a HarmonyOS device and install HAP packages without
including a HarmonyOS project, SDK, APIs, or build tools.

## Platforms

- `windows/` — Windows HDC CLI bundle.
- `macos/` — Reserved for the future macOS HDC CLI bundle.

## Windows usage

Open PowerShell or Command Prompt in the `windows` directory.

### Connect over Wi-Fi

```text
hdc.exe tconn DEVICE_IP:PORT
hdc.exe list targets
```

Example:

```text
hdc.exe tconn 192.168.1.105:39159
```

### Install a HAP package

After connecting to the device:

```text
hdc.exe install path\to\app.hap
```
 
