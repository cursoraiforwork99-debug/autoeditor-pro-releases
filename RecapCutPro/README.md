# RecapCutPro release channel

Public auto-update manifest:

- `version.json` — polled by RecapCutPro on startup
- Raw URL: https://raw.githubusercontent.com/cursoraiforwork99-debug/autoeditor-pro-releases/main/RecapCutPro/version.json

To publish an update:
1. Upload patch or full Offline zip to Google Drive → Share → Anyone with the link.
2. Direct link form: `https://drive.google.com/uc?export=download&id=FILE_ID`
3. Edit `version.json` here: bump `version`, set `patch_url` or `zip_url`, update `notes`.
4. Customers who already have a build with this raw URL in `update_config.json` get the popup on next launch.

Leave `zip_url` / `patch_url` empty until a real public download exists (avoids a broken Download dialog).
