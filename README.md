# QuSpin Software Releases

Official installers for QuSpin software. This repository holds release
downloads only; it contains no source code.

## Downloads

| Software | Version | Platform |
|---|---|---|
| [Neuro-1 Control Center](https://github.com/quspin-inc/software-releases/releases/tag/neuro1-control-center-v1.70) | 1.70 | Windows x64 |
| [QTFM Simple Gradiometer](https://github.com/quspin-inc/software-releases/releases/tag/qtfm-simple-gradiometer-v1.4.1) | 1.4.1 | Windows x64 |

All versions are listed on the [Releases page](https://github.com/quspin-inc/software-releases/releases).

## Verifying a download

Each release lists the SHA-256 checksum of every file. To check a file on
Windows, run this in PowerShell and compare the result:

```powershell
Get-FileHash .\<downloaded-file> -Algorithm SHA256
```

## Documentation and support

Product documentation is at [quspin.com](https://quspin.com). For support,
[contact QuSpin](https://quspin.com/contact/).
