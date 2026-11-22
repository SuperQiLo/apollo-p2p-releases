# apollo-p2p-releases

Public release artifacts for **Apollo P2P** streaming clients and host binaries.

Download installers and binaries from [GitHub Releases](https://github.com/SuperQiLo/apollo-p2p-releases/releases):

- `artemis-apollo-p2p-latest.apk` — Android client (`arm64-v8a`, Android 12+)
- `apollo-p2p-agent.exe` — Windows P2P signaling & WebRTC tunnel agent
- `apollo-p2p-sunshine.exe` — Modified Apollo host binary (`sunshine.exe`)
- `SHA256SUMS.txt` — SHA-256 verification checksums

Verify checksums on Windows PowerShell:

```powershell
Get-FileHash .\artemis-apollo-p2p-latest.apk, .\apollo-p2p-agent.exe, .\apollo-p2p-sunshine.exe -Algorithm SHA256
```
