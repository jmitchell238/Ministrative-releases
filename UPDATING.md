# Updating Ministrative

**Short answer:** Download the new installer and run it. Your data is safe.

## How to update

1. **Close Ministrative** if it is open.
2. **Download the new installer** from the [Releases page](https://github.com/jmitchell238/Ministrative-releases/releases). The file is named like `MinistrativeSetup_v<version>.exe`.
3. **Run the installer.** Double-click it. Windows shows the same security warning as the first time: click **Run** (or **More info**, then **Run anyway**), then **Yes**. See [Windows will warn you first](README.md#windows-will-warn-you-first).
4. **Update Ministrative:** the first screen says **Update Ministrative**. Tick **I accept the License Agreement** and click **Install**. You do not need to uninstall the old version first; the installer updates it in place, in the same folder.
5. **Finish:** leave **Launch Ministrative** ticked and click **Finish**. A "What's New" window may appear to show what changed.
6. **Check the version** if you like: open **Settings** (the gear icon at the bottom of the sidebar), then **About**.

## Your data is safe

Your entries and settings are stored in a separate folder from the app (`%LOCALAPPDATA%\Ministrative`). The installer does not touch that folder when installing, upgrading, or uninstalling. That means:

- All your entries are kept after every update
- Attached files (Word documents, PDFs, and so on) are kept
- Your settings, such as your church name and theme, are kept
- Even if you uninstall the app, your data stays on your computer

If you like extra peace of mind, export a backup first: **Settings, Backup and Restore, Export**.

## If something looks different after updating

Ministrative may quietly adjust some of your data the first time it opens after an update, for example filling in new fields. This is normal, and you will not be asked to do anything. If something does not look right, email [support@ministrative.app](mailto:support@ministrative.app).

## Automatic updates

Ministrative checks once a day for a new version. When one is available it tells you and shows what's new.

From version 1.1.2 on:

1. Click **Update now**. Ministrative downloads the new version and checks that the file is exactly the one posted on the Releases page. A damaged download is deleted and nothing is installed.
2. Click **Install and restart**. Ministrative closes, Windows asks for permission once (click **Yes**), the update installs without any setup pages, and Ministrative opens again on the new version.
3. If the update did not finish, Ministrative tells you the next time it opens and still runs the version you had.

**Install when you close (optional, off unless you turn it on):** in Settings, Notifications & Reminders, turn on **Download updates in the background and install when I close Ministrative**. The update is then downloaded quietly and installed when you close Ministrative.

Ministrative never installs an older version, and never installs anything unless you click Install or have turned on that setting. You can still update the old way: download the installer from the Releases page and run it. You can turn the daily check off in Settings, Notifications & Reminders.
