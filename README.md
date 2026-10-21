# Sine Cura Cyber downloads

This repository hosts the installer for the free Sine Cura Cyber Windows helper. It contains no source code.

The helper reads the status of the protection already built into Windows (it never changes your settings) and sends a plain-English summary to the Sine Cura Cyber app on your iPhone.

Download page and install steps: https://sinecuracyber.com/download/

## Preview notice

The installer is an unsigned preview. Windows SmartScreen may warn you; click **More info**, then **Run anyway**. It needs Windows 10 or 11, 64-bit.

## Verify the download (SHA-256)

Each release lists the SHA-256 hash and includes a `.sha256` file. In PowerShell:

```powershell
Get-FileHash .\SineCuraHelperSetup-0.1.0.exe -Algorithm SHA256
```

The hash shown must match the one on the release page and on https://sinecuracyber.com/download/. If it does not, do not run the file.

Sine Cura Cyber is not affiliated with, endorsed by, or sponsored by Microsoft Corporation.
