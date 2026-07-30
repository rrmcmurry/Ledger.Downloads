# Ledger Desktop Downloads

This repository hosts signed public releases for The Ledger.

Ledger Desktop is local-first accounting software for Ledger company files. You may install it and open ledger files in read-only mode without a license key. Creating, editing, or saving accounting data requires a valid trial or paid license activation.

## Current Release

Download the latest Ledger Desktop installer from:

[Latest Ledger Desktop release](https://github.com/rrmcmurry/Ledger.Downloads/releases/latest)

## Installation

1. Open the latest release link above.
2. Download `McMurrySoftware.TheLedger-stable-Setup.exe`.
3. Run the signed installer.

The installer creates Windows shortcuts, registers Ledger company files, and
installs the built-in updater. Future releases are downloaded, verified, and
applied through The Ledger by going to Help > Check for Updates

The application is installed / updated under
`%LOCALAPPDATA%\McMurrySoftware.TheLedger`. 
Settings, and other machine/user state remain under
`%LOCALAPPDATA%\McMurrySoftware\TheLedger`.

## Licensing

Ledger Desktop may be installed and used to open ledger files in read-only mode without a license key. This is intentional: users should not be locked out of viewing their own accounting records.

Editing and saving requires a valid license or an active 30-day trial license.

License activation contacts the Ledger licensing service and installs a signed, machine-bound certificate on your computer. After activation, The Ledger can verify the certificate locally without ongoing internet access.

## Data Privacy Posture

Ledger Desktop works with local ledger files. Public downloads and licensing services are not cloud backup, cloud sync, or hosted ledger services. 

You are responsible for choosing where your ledger files live and for maintaining your own backups.

## License Terms

See the current legal drafts:

- [Ledger End User License Agreement](Legal/EULA.md)
- [Ledger Privacy Policy](Legal/PrivacyPolicy.md)
- [Ledger License Summary](Legal/LicenseSummary.md)

These documents remain subject to revision.

Ledger Desktop is proprietary software by Robert McMurry. A formal McMurry Software publishing identity may replace this notice later.
