---
title: "About the Backup emergency kit"
description: "Information about backup emergency kit"
---

The backup emergency kit contains information needed to recover your backup, such as the encryption key.
Backups are encrypted (AES-128) and you need this information to decrypt the backup when you want to restore  system from that backup.

<img class="no-shadow" src='/images/more-info/backup_emergency_kit_01.png' alt="Screenshot showing the encryption key in the download dialog for the backup emergency kit.">

## Changing the encryption key

The first time when you set up your backups an encryption key is be generated. But you can create your own key. Old backups will still have the generated encryption key, but new backups will use the encryption key you defined yourself.

## Storing the backup emergency kit somewhere safe

1. Download the emergency kit:
   - directly when setting up a backup
   - or any time from the settings page.
2. Store it somewhere safe, outside of the Home Assistant system.

## I lost my backup encryption key - how can I retrieve it?

You cannot. The backup encryption key is neither stored on Home Assistant nor on Home Assistant Cloud. If you have lost the encryption key, there is no way to restore the backup.
