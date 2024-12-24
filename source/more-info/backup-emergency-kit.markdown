---
title: "Backup emergency kit"
description: "Information about backup emergency kit"
---

The backup emergency kit contains the encryption key needed to recover your backup.
Backups are encrypted (AES-128) and you need this information to decrypt the backup when you want to restore your system from that backup.

## Storing the backup emergency kit somewhere safe

1. To download the emergency kit, go to {% my backup title="**Settings** > **System** > **Backups**" %}
2. If it is your first time defining backup settings, select **Setup automatic backup** and download the encryption key.
   - You can also download the key again later under configuration. 

    ![Screenshot showing the encryption key in the download dialog for the backup emergency kit](/images/more-info/backup_emergency_kit_01.png)

3. Store the kit somewhere safe, outside of the Home Assistant system.
   - Without the encryption key, there is no way to restore the backup.

## Generating a new encryption key

The first time when you set up your backups, an encryption key is generated. But you can generate new ones. Old backups will still have the generated encryption key, but new backups will use the encryption key you defined yourself.

1. To generate a new encryption key, go to {% my backup title="**Settings** > **System** > **Backups**" %}.
2. Select **Configure automatic backups** and under **Encryption key**, select **Change**.
3. If you haven't downloaded the current encryption key yet, do it now.
4. Select **Change encryption key**.
5. Download the new encryption key and store it in a safe place.

## I lost my backup encryption key - how can I retrieve it?

You cannot. The backup encryption key is neither stored on Home Assistant nor on Home Assistant Cloud. If you have lost the encryption key, there is no way to restore the backup.
