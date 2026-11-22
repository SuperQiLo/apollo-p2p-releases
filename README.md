# apollo-p2p-releases

Public release artifacts for **Apollo P2P** (Android client, Windows host components, and Linux signaling/panel server binaries).

Download binaries from [GitHub Releases](https://github.com/SuperQiLo/apollo-p2p-releases/releases):

- `artemis-apollo-p2p-latest.apk` — Android client (`arm64-v8a`, Android 12+)
- `apollo-p2p-agent.exe` — Windows P2P signaling & WebRTC tunnel agent
- `apollo-p2p-sunshine.exe` — Modified Apollo host binary (`sunshine.exe`)
- `apollo-p2p-server-linux-arm64` — Linux signaling & web panel server (`arm64` / Oracle ARM)
- `apollo-p2p-server-linux-amd64` — Linux signaling & web panel server (`amd64` / x86_64)
- `SHA256SUMS.txt` — SHA-256 verification checksums

Verify checksums on Windows PowerShell:

```powershell
Get-FileHash .\artemis-apollo-p2p-latest.apk, .\apollo-p2p-agent.exe, .\apollo-p2p-sunshine.exe -Algorithm SHA256
```

Verify checksums on Linux:

```bash
sha256sum -c SHA256SUMS.txt --ignore-missing
```
