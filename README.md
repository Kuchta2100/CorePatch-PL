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

**Skip shared profile verification**:
<br>Allows installing apps that share the same system account, even if they have different signatures.
<br>![](https://img.shields.io/badge/INFO-Disable%20signature%20comparison-blue)
<br>![](https://img.shields.io/badge/must%20also%20be%20enabled-blue)

**Disable package verification agent**:
<br>e.g., Google Play Protect

### Download

**Latest release**: You can download the latest stable version from the [GitHub Releases](https://github.com/LSPosed/CorePatch/releases) page.  
**Development builds**: Get the latest development builds directly from [GitHub Actions](https://github.com/LSPosed/CorePatch/actions).  
**Historical versions**: Older versions are available for download [here](https://soft.shouji.com.cn/down/32512.html).

### Credits

Special thanks to the following for their contributions.
- [weishu](https://github.com/tiann): For code references.
- [LSPosed](https://github.com/LSPosed/LSPosed): For the ART Hook Framework.
- [yujincheng08](https://github.com/yujincheng08): For technical support.

### Community & support

Join the community on [Telegram](https://t.me/core_patch_chat) to discuss the module and get support.  
If you find this project useful, consider supporting the developer via [PayPal](https://www.paypal.com/paypalme/code620).

### License

CorePatch is released under the GPL V2 license. See the `LICENSE` file for more details.

