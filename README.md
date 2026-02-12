# ncSender Pro Releases

Official release binaries for **ncSender Pro** - a professional CNC streaming software for GRBL-based machines.

## Download

Download the latest release for your platform from the [Releases](https://github.com/siganberg/ncSenderProReleases/releases) page.

### Available Platforms

| Platform | Architecture | Format |
|----------|--------------|--------|
| Windows | x64 | `.exe`, `.msi` |
| macOS | Intel (x64) | `.dmg` |
| macOS | Apple Silicon (arm64) | `.dmg` |
| Linux | x64 | `.AppImage`, `.deb` |
| Linux | ARM64 (Raspberry Pi) | `.AppImage`, `.deb` |

## Installation

### Windows
Download and run the `.exe` installer or `.msi` package.

### macOS
1. Download the `.dmg` file for your Mac (Intel or Apple Silicon)
2. Open the DMG and drag ncSender Pro to Applications
3. Since the app is not code-signed by Apple, you'll need to clear the quarantine attribute before running:
   ```bash
   xattr -c /Applications/ncSender\ Pro.app
   ```
   Open Terminal (Applications → Utilities → Terminal), paste the command above, and press Enter. After that, you can open ncSender Pro normally.

### Linux
**AppImage:**
```bash
chmod +x ncSender_*.AppImage
./ncSender_*.AppImage
```

**Debian/Ubuntu (.deb):**
```bash
sudo dpkg -i ncSender_*.deb
```

### Raspberry Pi (ARM64)
Download the Linux ARM64 `.AppImage` or `.deb` package. Requires 64-bit Raspberry Pi OS.

## License

ncSender Pro requires a valid license to run. Purchase a license at [franciscreation.com](https://franciscreation.com).

After purchase, you'll receive an Installation ID via email. Enter this ID in the app to activate your license.

## Support

- Website: [franciscreation.com](https://franciscreation.com)
- Issues: For bug reports and feature requests, please contact support

## About

ncSender Pro is the commercial version of ncSender with additional features for professional CNC users.

---

Copyright (c) 2025 Francis Creation. All rights reserved.
