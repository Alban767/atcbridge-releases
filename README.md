# atcbridge releases

Binary releases of **atcbridge** — the ATC Bridge for the Flight Simulator Training Center
(TeamSpeak / X-Plane / Air Manager). Installed copies check this repository for updates.

Each release carries two assets:

- `atcbridge.exe` — the Windows program
- `atcbridge.exe.sig` — the developer's Ed25519 signature of that exe

The app only installs an update whose signature matches its embedded public key.
