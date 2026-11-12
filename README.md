# CPU Jr. Backup — Info Site

Public information pages for **CPU Jr. Backup**, a personal application that
uses [Rclone](https://rclone.org/) and [Restic](https://restic.net/) to store
encrypted Raspberry Pi system backups in Google Drive.

These pages provide the application home page and privacy policy URLs used by
the Google OAuth consent screen.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | Application home page |
| `privacy.html` | Privacy policy |
| `style.css` | Shared styles (responsive, light/dark mode) |

## Publishing

The site is static HTML with no build step. Serve it with GitHub Pages
(Settings → Pages → deploy from the default branch, root folder). The pages
will then be available at:

- `https://ickiwas-ui.github.io/cpu-jr-backup-info/`
- `https://ickiwas-ui.github.io/cpu-jr-backup-info/privacy.html`

## Updating the privacy policy

When the policy changes, update the **Effective date** at the top of
`privacy.html`.
