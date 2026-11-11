# Craft Cloud screenshots

Images for the README and docs of Craft Cloud. This branch holds only images and this file; it has no source code.

## web-admin

The browser admin (`/web`) of a local test server with made-up data: accounts ana, ben, chris, dana and an invite for eve, team spaces Studio and Marketing, and a fake update notice. File names are `<page>-<width>-<theme>.png`: the page (`overview`, `users`, `account`, `spaces`, `space`, `audit`), the width in pixels (1280 desktop, 390 phone) and `light` or `dark`.

Reference one as `https://raw.githubusercontent.com/Skyfuller1303/craft-cloud/screenshots/web-admin/<file>`.

Files:

- `web-admin/account-1280-dark.png`
- `web-admin/account-1280-light.png`
- `web-admin/account-390-dark.png`
- `web-admin/account-390-light.png`
- `web-admin/audit-1280-dark.png`
- `web-admin/audit-1280-light.png`
- `web-admin/audit-390-dark.png`
- `web-admin/audit-390-light.png`
- `web-admin/overview-1280-dark.png`
- `web-admin/overview-1280-light.png`
- `web-admin/overview-390-dark.png`
- `web-admin/overview-390-light.png`
- `web-admin/space-1280-dark.png`
- `web-admin/space-1280-light.png`
- `web-admin/space-390-dark.png`
- `web-admin/space-390-light.png`
- `web-admin/spaces-1280-dark.png`
- `web-admin/spaces-1280-light.png`
- `web-admin/spaces-390-dark.png`
- `web-admin/spaces-390-light.png`
- `web-admin/users-1280-dark.png`
- `web-admin/users-1280-light.png`
- `web-admin/users-390-dark.png`
- `web-admin/users-390-light.png`

## app

Screenshots of the desktop app, taken from the fixture-driven snapshot tests in `apps/craft-cloud-desktop/tests/snapshots/` (the fixture account is "FABIO", on the server "cloud.shadows.ch"; everything shown is made up). The files are the committed snapshots at 960 px wide, under their snapshot names. `overview-folders.png` is reduced to 64 colours to keep it small; the others are unchanged.

Reference one as `https://raw.githubusercontent.com/Skyfuller1303/craft-cloud/screenshots/app/<file>`.

Files:

- `app/adding-a-computer.png`: the Computers tab while a one-time code and QR code wait for the other computer.
- `app/admin-health.png`: the admin accounts page with the totals and the server health line (light theme).
- `app/admin-spaces-list-dark.png`: the admin list of team spaces (dark theme).
- `app/computers-light.png`: the Computers tab with the signed-in computers, their kind, platform and version.
- `app/files-loaded.png`: the Files tab with the recent files of every app and computer.
- `app/overview-folders.png`: the Overview tab with the storage numbers and the folder and kind breakdown.
- `app/security-on.png`: the Security tab with two-factor sign-in on, the password form and sign out of other computers.
- `app/shared-list.png`: the Shared tab with two invitations and the team spaces.
