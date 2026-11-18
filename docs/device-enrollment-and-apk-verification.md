# Device Enrollment & MDM APK Verification

1. Download the signed `SUNTEK-MDM` release package for your terminal model from [GitHub Releases](https://github.com/SUNTEK-Official/suntek-mdm-docs/releases).
2. Verify package integrity:
   ```bash
   shasum -a 256 suntek-mdm-*.apk
   ```
3. Enroll the terminal by scanning your tenant provisioning QR code or installing via ADB in enterprise provisioning mode.
