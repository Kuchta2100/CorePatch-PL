# CorePatch
An Xposed module for Vector (formerly LSPosed) that disables signature verification in the Android OS.

![GitHub release (latest by date)](https://img.shields.io/github/v/release/coderstory/CorePatch)
![CRAN/METACRAN](https://img.shields.io/cran/l/devtools)

### Supported Android Versions

This version is designed exclusively for **Android 9–16.**
<br>![](https://img.shields.io/badge/INFO-Use%20the%20latest%20version%20of%20the%20Vector%20app-blue)

## Features

CorePatch offers several key features to bypass standard Android installation checks.

**Allow downgrade**:
<br>Allows installing an older version of an app, eliminating the error: 
<br>![](https://img.shields.io/badge/INFO-INSTALL__FAILED__VERSION__DOWNGRADE-green)

**Disable checksum verification**:
<br>Allows installing apps after modifying the APK file.
<br>![](https://img.shields.io/badge/INFO-ignores%20invalid%20checksum%20error-green)

**Disable signature comparison**:
<br>Allows reinstalling apps with different signatures.

**Disable accurate signature matching**:
<br>Disables strict signature matching between APK packages, allowing installations where each APK split has a different signature.
<br>![](https://img.shields.io/badge/WARNING!-Enable%20only%20if%20necessary!-red)

**Use installed signatures**:
<br>Always uses the signatures of already installed apps during installation.
<br>![](https://img.shields.io/badge/WARNING!-This%20is%20extremely%20dangerous-red)
<br>![](https://img.shields.io/badge/Enable%20only%20when%20absolutely%20necessary%21-red)

**Bypass lock**:
<br>Bypasses the installation blocklist on certain devices, e.g., Nothing Phone.

**Skip shared user verification**:
<br>Allows installing apps with a signature different from their shared user.
<br>![](https://img.shields.io/badge/INFO-Disable%20signature%20comparison-blue)
<br>![](https://img.shields.io/badge/must%20also%20be%20enabled-blue)

**Disable package verification agent**:
<br>e.g., Google Play Protect
