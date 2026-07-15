# Ledger Desktop Downloads

This repository hosts public download metadata for Ledger Desktop.

Ledger Desktop is local-first accounting software for `.ledger` company files. You may install it and open ledger files in read-only mode without a license key. Creating, editing, or saving accounting data requires a valid trial or paid license activation.

## Current Release

Current stable version: `20260715.170325-7a59811`

Download the current installer ZIP:

[LedgerDesktopInstaller-20260715.170325-7a59811-win-x64.zip](https://github.com/rrmcmurry/Ledger.Downloads/releases/download/ledger-desktop-20260715.170325-7a59811/LedgerDesktopInstaller-20260715.170325-7a59811-win-x64.zip)

SHA-256:

```text
b4fd4e1017e97a36dc8669873a72dbd542e3fce32d3a67b70bb149284307e18f
```

Machine-readable update metadata is published at:

[stable/latest.json](stable/latest.json)

## Installation

1. Download the current installer ZIP above.
2. Extract the ZIP to a normal folder, such as Downloads or Desktop.
3. Open PowerShell in the extracted folder.
4. Run:

```powershell
powershell -ExecutionPolicy Bypass -File .\Install-LedgerDesktop.ps1 -Launch
```

The installer copies Ledger Desktop to:

```text
%LOCALAPPDATA%\Ledger\Desktop
```

It also creates shortcuts and registers `.ledger` files to open with Ledger Desktop.

## Licensing

Ledger Desktop may be installed and used to open `.ledger` files in read-only mode without a license key. This is intentional: users should not be locked out of viewing their own accounting records.

Editing and saving requires a valid license or trial activation. During early testing, trial keys are issued manually. Request a trial key by contacting [rrmcmurry](https://github.com/rrmcmurry) on GitHub.

Activation contacts the Ledger licensing service once and installs a signed, machine-bound certificate on your computer. After activation, Ledger can verify the certificate locally without ongoing internet access.

## Data Privacy Posture

Ledger Desktop works with local `.ledger` files. Public downloads and licensing services are not cloud backup, cloud sync, or hosted ledger services. Do not upload private client ledger files here.

You are responsible for choosing where your `.ledger` files live and for maintaining your own backups.

## License Terms

See [LICENSE.txt](LICENSE.txt).

Ledger Desktop is proprietary software by Robert McMurry. A formal McMurry Software publishing identity may replace this notice later.
