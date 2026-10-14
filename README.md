# Minime Event Workspace — Windows releases

Installer releases of the **Minime Event Workspace** desktop application (Windows, x64), published
as GitHub Releases of this repository. Binaries only: this repository holds no source code.

Each release `vX.Y.Z` carries three assets:

| Asset | Purpose |
| --- | --- |
| `Minime-Event-Workspace-X.Y.Z-setup.exe` | one-click per-user installer (first install by hand; also the update download) |
| `Minime-Event-Workspace-X.Y.Z-setup.exe.blockmap` | differential-update data |
| `latest.yml` | the update feed the installed application reads |

Installed copies check this repository for a newer published release at start and every six hours and
update themselves. Draft releases are invisible to them. The installer is not code-signed: Windows
SmartScreen may ask once per computer on a manual install ("Run anyway").

No issues, discussions or contributions are expected here.
