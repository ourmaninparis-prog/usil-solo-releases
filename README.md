# Usil Solo – Windows releases

This repository only holds the Windows installers for **Usil Solo**. Installed copies use it to update themselves.

- **Download:** the latest installer is under [Releases](../../releases/latest). Run `Usil-Solo-Setup-x.y.z.exe`; it installs for the current Windows user without administrator rights.
- **First use:** a parent, legal guardian or teacher asks for access from inside the app. The installer does nothing until that request has been approved.
- **Updates:** installed copies check here every few hours and install new versions at a quiet moment, never while the child is writing.
- **Integrity:** each update comes with an `.sig` file. The app installs an update only if this signature, made with the publisher's private key, matches the key built into the app.

The source code and the correction service are not published here.
