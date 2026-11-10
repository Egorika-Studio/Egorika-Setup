# Egorika release journal

Release notes retained before cleanup of superseded release assets and tags.

## v0.4.11

Published: 11/10/2026 07:18:31

Egorika Studio0.4.11: own Egorika avatars with offline caching, compact hover account menu, separate profile/devices/invitations, update indicator and static startup notice. Existing account/update engine, projects, masks, Undo, settings and panel layout preserved.

## v0.4.10

Published: 11/10/2026 06:15:41

Egorika Studio 0.4.10: complete Windows runtime package for the version-independent Egorika Setup. Preserve projects, account activation, settings and panel layout. The same Setup downloads the latest signed private editor after Egorika/GitHub sign-in. Visual C++ release runtimes are bundled app-local; optional YFT export uses Microsoft .NET Framework 4.8 or later.

## v0.4.9

Published: 11/10/2026 05:12:46

Egorika Studio 0.4.9

First invited Egorika/GitHub verification is now required. After success, a separately signed trial grant permits unlimited offline drawing on the same Windows user/computer. An existing invited account session can satisfy first verification. Updates, online session expiry or online revocation do not remove this unlimited test grant.

Program ZIPs contain no account or activation vault. New credential writes use Windows LOCAL_MACHINE persistence. Startup recovery and queued files are deferred until first activation succeeds. Projects, presets, masks, Undo and panel placement are preserved.

Owner console: https://egorika-accounts.egorika-accounts.workers.dev/console/
Sign in through Egorika/GitHub; ChatGPT is not needed. Only the verified GitHub owner ID is allowed. The previous ChatGPT Sites bridge has been disabled.

Only version/time/session check-in metadata is recorded. No network-location/IP-change/hardware history is added. Offline launches cannot be reported remotely. Older clients show unknown version.

QA: the owner completed real browser console sign-in and isolated native first activation. The isolated editor reopened after its own online session was revoked; the owner's original sessions were retained. This is not tamper-proof DRM or a malware-free certification.


## v0.4.8

Published: 11/09/2026 23:12:41

Egorika Studio 0.4.8

Safe update cleanup shared by Setup and the editor: ownership receipts and SHA-256 checks remove unchanged obsolete package files, retain user-modified/unknown files and one verified rollback copy. Rollback includes obsolete-file removal. Completed helper download stages can be reclaimed on a later download after the helper exits; legacy/unrecognised copies are preserved.

Projects, offline drawing, Windows account vault, masks, Undo, tools and panel placement are unchanged. No mandatory login, hardware fingerprint, launch telemetry or IP/country history was added.

The separate owner-private Egorika Control website shows account sessions and security events and can revoke one or all sessions. This does not close offline editors or remove invitations. User sessions were not revoked during QA.

No Windows Authenticode or malware-free certification is claimed. Payload signature verification retains the original Ed25519 release identity.


## v0.4.7

Published: 11/09/2026 22:24:49

Egorika Setup 0.4.7. Download the Windows ZIP with third-party notices. Sign in through GitHub with an invited Egorika account to install the latest signed private editor. No manual access token. Projects and settings stay on this computer. Windows Authenticode signing is separate and is not claimed.

## v0.4.6

Published: 11/09/2026 22:14:07

Egorika Setup0.4.6 installs the latest signed Egorika Studio release after GitHub sign-in with an invited Egorika account. No personal access token is needed.

Download **EgorikaSetup-0.4.6-Windows.zip**, extract and run EgorikaSetup.exe. The ZIP includes third-party notices. A direct EXE is also provided; license notices are included in the ZIP.

The editor packages remain private. Setup checks your invitation through the account service and verifies the original Egorika release signature and checksum. It installs per user and creates stable shortcuts. Projects and settings remain on your computer; the installed editor works offline.

Windows Authenticode publisher signing is not claimed. SHA256 checksums are included for download integrity. No publisher credentials or private signing keys are included.

