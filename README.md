# scoop-antchat

[Scoop](https://scoop.sh) bucket for [antchat](https://github.com/Jktfe/a-nice-terminal) — the lightweight ANT chat client. Single binary, no Bun/Node required on the host.

## Install

```powershell
scoop bucket add antchat https://github.com/Jktfe/scoop-antchat
scoop install antchat
```

Then verify:

```powershell
antchat --version
```

## Update

```powershell
scoop update antchat
```

`scoop update *` picks up new releases automatically via the manifest's `checkver: github` + `autoupdate.url` template — no need to wait for a manual bucket bump for most upgrades.

## Source

Manifests are generated from the reference template at [`Jktfe/a-nice-terminal/scoop/antchat.json`](https://github.com/Jktfe/a-nice-terminal/blob/main/scoop/antchat.json). Version + hash are synced into this repo by `scoop/update-bucket.sh` after each `antchat-v*` release.
