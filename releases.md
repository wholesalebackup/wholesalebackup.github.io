---
title: Releases
permalink: /releases/
---

# WholesaleBackup Releases

Every release of the Backup Ops Web Console, the Windows and Mac backup clients, and the self-hosted WSBU Server, newest first. Generated from the team's release notes on 2026-09-27. Product pages: [Web Console](https://wholesalebackup.com/backup-software/web-console/), [pricing](https://wholesalebackup.com/pricing/). Knowledge base: [support.wholesalebackup.com](https://support.wholesalebackup.com/hc/en-us).


## September 2026

- **2026-09-24** · Windows Client `26.09.24.dee142ed` · Microsoft 365 mailbox backup: mail, calendars, and contacts from an Exchange Online tenant, backed up alongside files and folders on the same schedule. A read-only app registration does the work, no mailbox passwords. Also fixed: Backup > Settings now shows in expert mode when it is hidden for end users. [Guide](https://support.wholesalebackup.com/hc/en-us/articles/56263636580763-Backing-Up-Microsoft-365-Mail-Calendars-and-Contacts)
- **2026-09-11** · Web Console `app-c36a-260911` · Hardware security keys (WebAuthn, such as YubiKey) added as a third multi-factor option for console logins, beside email codes and authenticator apps.
- **2026-09-01** · Windows Client `26.09.01.3459807a` · The AWS secret is no longer displayed in the key file view; only its last characters show, for verification.

## August 2026

- **2026-08-25** · Windows Client `26.08.25.92470e8d` · Disk images move from VHD to VHDX. The 2 TB limit on physical drive images is gone.
- **2026-08-13** · Web Console `app-7c2e-260813` · Computers marked Deleted or Suspended no longer count as Active, with finer status controls on the account.

## July 2026

- **2026-07-15** · Web Console `app-8899-260715` · Immutable snapshots (S3 Object Lock) can be switched on per brand from the build forms for Amazon S3, Wasabi, Backblaze B2, and IDrive e2. A locked second copy that cannot be changed or deleted until retention ends. [Guide](https://support.wholesalebackup.com/hc/en-us/articles/53067567126811)
- **2026-07-08** · WSBU Server `26.07.08.66def00b` · Server release. The license query now reports servers and workstations separately for billing.

## June 2026

- **2026-06-30** · Web Console `app-285b2-260630` · Remote Selections GUI: add selections and exclusions from the client file tree without logging on to the endpoint. Selections, Restore, and Disk Image Restore now share one Remote Manager GUI. [Guide](https://support.wholesalebackup.com/hc/en-us/articles/52078121633819-Wholesale-Backup-Web-Console-Remote-Manager-Settings-Selections-and-Restore-GUI)
- **2026-06-24** · Mac Client `26.06.24.0ca3b44b` · Bug-fix release with a large batch of verified fixes.
- **2026-06-24** · Windows Client `26.06.24.219ee212` · Bug-fix release, matching the Mac client fixes.

## May 2026

- **2026-05-22** · Mac Client `26.05.22.55f38c303` · IDrive e2 storage support.
- **2026-05-20** · Web Console `app-05a3-260520` · IDrive e2 is back on the registration form and the Brands tab.
- **2026-05-20** · Windows Client `26.05.20.6270b680` · IDrive e2 storage support returns. RAID server backup fix and error-handling fixes.

## November 2025

- **2025-11-18** · Web Console `app-76b9-251118` · Build form failures now report the step where the save failed.

---

Subscribe: [releases feed](https://github.com/wholesalebackup/wholesalebackup.github.io/releases.atom)
