# raid-backup v1.0

The second project in the raid-diognostics2 suite.

## Platforms
- Windows: `raid-backup.bat`
- macOS: `raid-backup.sh`
- Linux: `raid-backup.sh`

## Features
- Create timestamped backups
- Restore backups with explicit YES confirmation
- Browse backup folders and sizes
- SHA-256 manifest verification
- USB removable-drive backup
- Backup reports
- Safe settings/info
- No formatting or wiping

## Windows
Uses built-in PowerShell and Robocopy.

## macOS/Linux
Uses Python 3 and standard library file operations.

## Safety
This project never asks for, stores, or transmits administrator passwords/PINs.
It does not automatically format or wipe disks.
