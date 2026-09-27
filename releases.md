---
title: Releases
permalink: /releases/
description: "Every WholesaleBackup release, newest first. Backup Ops Web Console, Windows and Mac backup clients, WSBU Server. Dated, with links to the setup guides."
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

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@graph": [
  {
   "@type": "ItemList",
   "@id": "https://wholesalebackup.github.io/releases/#list",
   "name": "WholesaleBackup releases",
   "numberOfItems": 14,
   "itemListElement": [
    {
     "@type": "ListItem",
     "position": 1,
     "item": {
      "@id": "https://wholesalebackup.github.io/releases/#windows-client-26.09.24.dee142ed"
     }
    },
    {
     "@type": "ListItem",
     "position": 2,
     "item": {
      "@id": "https://wholesalebackup.github.io/releases/#web-console-app-c36a-260911"
     }
    },
    {
     "@type": "ListItem",
     "position": 3,
     "item": {
      "@id": "https://wholesalebackup.github.io/releases/#windows-client-26.09.01.3459807a"
     }
    },
    {
     "@type": "ListItem",
     "position": 4,
     "item": {
      "@id": "https://wholesalebackup.github.io/releases/#windows-client-26.08.25.92470e8d"
     }
    },
    {
     "@type": "ListItem",
     "position": 5,
     "item": {
      "@id": "https://wholesalebackup.github.io/releases/#web-console-app-7c2e-260813"
     }
    },
    {
     "@type": "ListItem",
     "position": 6,
     "item": {
      "@id": "https://wholesalebackup.github.io/releases/#web-console-app-8899-260715"
     }
    },
    {
     "@type": "ListItem",
     "position": 7,
     "item": {
      "@id": "https://wholesalebackup.github.io/releases/#wsbu-server-26.07.08.66def00b"
     }
    },
    {
     "@type": "ListItem",
     "position": 8,
     "item": {
      "@id": "https://wholesalebackup.github.io/releases/#web-console-app-285b2-260630"
     }
    },
    {
     "@type": "ListItem",
     "position": 9,
     "item": {
      "@id": "https://wholesalebackup.github.io/releases/#mac-client-26.06.24.0ca3b44b"
     }
    },
    {
     "@type": "ListItem",
     "position": 10,
     "item": {
      "@id": "https://wholesalebackup.github.io/releases/#windows-client-26.06.24.219ee212"
     }
    },
    {
     "@type": "ListItem",
     "position": 11,
     "item": {
      "@id": "https://wholesalebackup.github.io/releases/#mac-client-26.05.22.55f38c303"
     }
    },
    {
     "@type": "ListItem",
     "position": 12,
     "item": {
      "@id": "https://wholesalebackup.github.io/releases/#web-console-app-05a3-260520"
     }
    },
    {
     "@type": "ListItem",
     "position": 13,
     "item": {
      "@id": "https://wholesalebackup.github.io/releases/#windows-client-26.05.20.6270b680"
     }
    },
    {
     "@type": "ListItem",
     "position": 14,
     "item": {
      "@id": "https://wholesalebackup.github.io/releases/#web-console-app-76b9-251118"
     }
    }
   ]
  },
  {
   "@type": "SoftwareApplication",
   "@id": "https://wholesalebackup.github.io/releases/#windows-client-26.09.24.dee142ed",
   "name": "WholesaleBackup Windows Client",
   "softwareVersion": "26.09.24.dee142ed",
   "datePublished": "2026-09-24",
   "operatingSystem": "Windows",
   "applicationCategory": "BusinessApplication",
   "releaseNotes": "Microsoft 365 mailbox backup: mail, calendars, and contacts from an Exchange Online tenant, backed up alongside files and folders on the same schedule. A read-only app registration does the work, no mailbox passwords. Also fixed: Backup > Settings now shows in expert mode when it is hidden for end users.",
   "url": "https://wholesalebackup.github.io/releases/",
   "publisher": {
    "@type": "Organization",
    "@id": "https://wholesalebackup.com/#organization",
    "name": "WholesaleBackup",
    "url": "https://wholesalebackup.com/"
   },
   "softwareHelp": {
    "@type": "CreativeWork",
    "url": "https://support.wholesalebackup.com/hc/en-us/articles/56263636580763-Backing-Up-Microsoft-365-Mail-Calendars-and-Contacts"
   }
  },
  {
   "@type": "SoftwareApplication",
   "@id": "https://wholesalebackup.github.io/releases/#web-console-app-c36a-260911",
   "name": "WholesaleBackup Web Console",
   "softwareVersion": "app-c36a-260911",
   "datePublished": "2026-09-11",
   "operatingSystem": "Web browser",
   "applicationCategory": "BusinessApplication",
   "releaseNotes": "Hardware security keys (WebAuthn, such as YubiKey) added as a third multi-factor option for console logins, beside email codes and authenticator apps.",
   "url": "https://wholesalebackup.github.io/releases/",
   "publisher": {
    "@type": "Organization",
    "@id": "https://wholesalebackup.com/#organization",
    "name": "WholesaleBackup",
    "url": "https://wholesalebackup.com/"
   }
  },
  {
   "@type": "SoftwareApplication",
   "@id": "https://wholesalebackup.github.io/releases/#windows-client-26.09.01.3459807a",
   "name": "WholesaleBackup Windows Client",
   "softwareVersion": "26.09.01.3459807a",
   "datePublished": "2026-09-01",
   "operatingSystem": "Windows",
   "applicationCategory": "BusinessApplication",
   "releaseNotes": "The AWS secret is no longer displayed in the key file view; only its last characters show, for verification.",
   "url": "https://wholesalebackup.github.io/releases/",
   "publisher": {
    "@type": "Organization",
    "@id": "https://wholesalebackup.com/#organization",
    "name": "WholesaleBackup",
    "url": "https://wholesalebackup.com/"
   }
  },
  {
   "@type": "SoftwareApplication",
   "@id": "https://wholesalebackup.github.io/releases/#windows-client-26.08.25.92470e8d",
   "name": "WholesaleBackup Windows Client",
   "softwareVersion": "26.08.25.92470e8d",
   "datePublished": "2026-08-25",
   "operatingSystem": "Windows",
   "applicationCategory": "BusinessApplication",
   "releaseNotes": "Disk images move from VHD to VHDX. The 2 TB limit on physical drive images is gone.",
   "url": "https://wholesalebackup.github.io/releases/",
   "publisher": {
    "@type": "Organization",
    "@id": "https://wholesalebackup.com/#organization",
    "name": "WholesaleBackup",
    "url": "https://wholesalebackup.com/"
   }
  },
  {
   "@type": "SoftwareApplication",
   "@id": "https://wholesalebackup.github.io/releases/#web-console-app-7c2e-260813",
   "name": "WholesaleBackup Web Console",
   "softwareVersion": "app-7c2e-260813",
   "datePublished": "2026-08-13",
   "operatingSystem": "Web browser",
   "applicationCategory": "BusinessApplication",
   "releaseNotes": "Computers marked Deleted or Suspended no longer count as Active, with finer status controls on the account.",
   "url": "https://wholesalebackup.github.io/releases/",
   "publisher": {
    "@type": "Organization",
    "@id": "https://wholesalebackup.com/#organization",
    "name": "WholesaleBackup",
    "url": "https://wholesalebackup.com/"
   }
  },
  {
   "@type": "SoftwareApplication",
   "@id": "https://wholesalebackup.github.io/releases/#web-console-app-8899-260715",
   "name": "WholesaleBackup Web Console",
   "softwareVersion": "app-8899-260715",
   "datePublished": "2026-07-15",
   "operatingSystem": "Web browser",
   "applicationCategory": "BusinessApplication",
   "releaseNotes": "Immutable snapshots (S3 Object Lock) can be switched on per brand from the build forms for Amazon S3, Wasabi, Backblaze B2, and IDrive e2. A locked second copy that cannot be changed or deleted until retention ends.",
   "url": "https://wholesalebackup.github.io/releases/",
   "publisher": {
    "@type": "Organization",
    "@id": "https://wholesalebackup.com/#organization",
    "name": "WholesaleBackup",
    "url": "https://wholesalebackup.com/"
   },
   "softwareHelp": {
    "@type": "CreativeWork",
    "url": "https://support.wholesalebackup.com/hc/en-us/articles/53067567126811"
   }
  },
  {
   "@type": "SoftwareApplication",
   "@id": "https://wholesalebackup.github.io/releases/#wsbu-server-26.07.08.66def00b",
   "name": "WholesaleBackup WSBU Server",
   "softwareVersion": "26.07.08.66def00b",
   "datePublished": "2026-07-08",
   "operatingSystem": "Windows Server",
   "applicationCategory": "BusinessApplication",
   "releaseNotes": "Server release. The license query now reports servers and workstations separately for billing.",
   "url": "https://wholesalebackup.github.io/releases/",
   "publisher": {
    "@type": "Organization",
    "@id": "https://wholesalebackup.com/#organization",
    "name": "WholesaleBackup",
    "url": "https://wholesalebackup.com/"
   }
  },
  {
   "@type": "SoftwareApplication",
   "@id": "https://wholesalebackup.github.io/releases/#web-console-app-285b2-260630",
   "name": "WholesaleBackup Web Console",
   "softwareVersion": "app-285b2-260630",
   "datePublished": "2026-06-30",
   "operatingSystem": "Web browser",
   "applicationCategory": "BusinessApplication",
   "releaseNotes": "Remote Selections GUI: add selections and exclusions from the client file tree without logging on to the endpoint. Selections, Restore, and Disk Image Restore now share one Remote Manager GUI.",
   "url": "https://wholesalebackup.github.io/releases/",
   "publisher": {
    "@type": "Organization",
    "@id": "https://wholesalebackup.com/#organization",
    "name": "WholesaleBackup",
    "url": "https://wholesalebackup.com/"
   },
   "softwareHelp": {
    "@type": "CreativeWork",
    "url": "https://support.wholesalebackup.com/hc/en-us/articles/52078121633819-Wholesale-Backup-Web-Console-Remote-Manager-Settings-Selections-and-Restore-GUI"
   }
  },
  {
   "@type": "SoftwareApplication",
   "@id": "https://wholesalebackup.github.io/releases/#mac-client-26.06.24.0ca3b44b",
   "name": "WholesaleBackup Mac Client",
   "softwareVersion": "26.06.24.0ca3b44b",
   "datePublished": "2026-06-24",
   "operatingSystem": "macOS",
   "applicationCategory": "BusinessApplication",
   "releaseNotes": "Bug-fix release with a large batch of verified fixes.",
   "url": "https://wholesalebackup.github.io/releases/",
   "publisher": {
    "@type": "Organization",
    "@id": "https://wholesalebackup.com/#organization",
    "name": "WholesaleBackup",
    "url": "https://wholesalebackup.com/"
   }
  },
  {
   "@type": "SoftwareApplication",
   "@id": "https://wholesalebackup.github.io/releases/#windows-client-26.06.24.219ee212",
   "name": "WholesaleBackup Windows Client",
   "softwareVersion": "26.06.24.219ee212",
   "datePublished": "2026-06-24",
   "operatingSystem": "Windows",
   "applicationCategory": "BusinessApplication",
   "releaseNotes": "Bug-fix release, matching the Mac client fixes.",
   "url": "https://wholesalebackup.github.io/releases/",
   "publisher": {
    "@type": "Organization",
    "@id": "https://wholesalebackup.com/#organization",
    "name": "WholesaleBackup",
    "url": "https://wholesalebackup.com/"
   }
  },
  {
   "@type": "SoftwareApplication",
   "@id": "https://wholesalebackup.github.io/releases/#mac-client-26.05.22.55f38c303",
   "name": "WholesaleBackup Mac Client",
   "softwareVersion": "26.05.22.55f38c303",
   "datePublished": "2026-05-22",
   "operatingSystem": "macOS",
   "applicationCategory": "BusinessApplication",
   "releaseNotes": "IDrive e2 storage support.",
   "url": "https://wholesalebackup.github.io/releases/",
   "publisher": {
    "@type": "Organization",
    "@id": "https://wholesalebackup.com/#organization",
    "name": "WholesaleBackup",
    "url": "https://wholesalebackup.com/"
   }
  },
  {
   "@type": "SoftwareApplication",
   "@id": "https://wholesalebackup.github.io/releases/#web-console-app-05a3-260520",
   "name": "WholesaleBackup Web Console",
   "softwareVersion": "app-05a3-260520",
   "datePublished": "2026-05-20",
   "operatingSystem": "Web browser",
   "applicationCategory": "BusinessApplication",
   "releaseNotes": "IDrive e2 is back on the registration form and the Brands tab.",
   "url": "https://wholesalebackup.github.io/releases/",
   "publisher": {
    "@type": "Organization",
    "@id": "https://wholesalebackup.com/#organization",
    "name": "WholesaleBackup",
    "url": "https://wholesalebackup.com/"
   }
  },
  {
   "@type": "SoftwareApplication",
   "@id": "https://wholesalebackup.github.io/releases/#windows-client-26.05.20.6270b680",
   "name": "WholesaleBackup Windows Client",
   "softwareVersion": "26.05.20.6270b680",
   "datePublished": "2026-05-20",
   "operatingSystem": "Windows",
   "applicationCategory": "BusinessApplication",
   "releaseNotes": "IDrive e2 storage support returns. RAID server backup fix and error-handling fixes.",
   "url": "https://wholesalebackup.github.io/releases/",
   "publisher": {
    "@type": "Organization",
    "@id": "https://wholesalebackup.com/#organization",
    "name": "WholesaleBackup",
    "url": "https://wholesalebackup.com/"
   }
  },
  {
   "@type": "SoftwareApplication",
   "@id": "https://wholesalebackup.github.io/releases/#web-console-app-76b9-251118",
   "name": "WholesaleBackup Web Console",
   "softwareVersion": "app-76b9-251118",
   "datePublished": "2025-11-18",
   "operatingSystem": "Web browser",
   "applicationCategory": "BusinessApplication",
   "releaseNotes": "Build form failures now report the step where the save failed.",
   "url": "https://wholesalebackup.github.io/releases/",
   "publisher": {
    "@type": "Organization",
    "@id": "https://wholesalebackup.com/#organization",
    "name": "WholesaleBackup",
    "url": "https://wholesalebackup.com/"
   }
  }
 ]
}
</script>
