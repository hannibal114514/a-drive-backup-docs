# Privacy policy

Effective date: 2026-10-23

A Drive Backup uses rclone on its owner's Mac to copy selected local files to the owner's Google Drive. Google Drive authorization is used to list backup files, upload files, create directories, retain previous file versions, and verify backups.

OAuth credentials and tokens are stored in the owner's local rclone configuration. Backup files, names, sizes, modification times, and file hashes are sent directly from the Mac to Google Drive through the owner's configured network proxy. Backup logs are stored locally. The documentation website does not receive backup files or OAuth tokens.

The setup does not sell data, use Google Drive data for advertising or AI model training, or intentionally share backups with other users. Google's services, the network proxy, and GitHub Pages operate under their respective policies.

Backup files and retained versions remain in Google Drive until the owner deletes them. The owner can stop local scheduled backups, revoke the app's Google account access, delete local credentials, and delete cloud backups independently. Stopping the schedule does not delete backups.

This app is for its owner's personal use only and provides no registration or public support service.
