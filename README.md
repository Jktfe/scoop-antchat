# scoop-antchat

[Scoop](https://scoop.sh) bucket for [antchat](https://github.com/Jktfe/a-nice-terminal) — the lightweight ANT chat client. Single binary, no Bun/Node required on the host.

## Install

Install the native Windows app and the fresh ANT CLI together:

```powershell
scoop bucket add antchat https://github.com/Jktfe/scoop-antchat
scoop install antchat-app
```

Then verify the CLI is available for local agents and MCP workflows:

```powershell
ant --help
```

Install just the CLI:

```powershell
scoop bucket add antchat https://github.com/Jktfe/scoop-antchat
scoop install ant
```

Legacy CLI package:

```powershell
scoop install antchat
```

## Update

```powershell
scoop update antchat
scoop update antchat-app
scoop update ant
```

`scoop update *` picks up new releases automatically via each manifest's `checkver` + `autoupdate.url` template — no need to wait for a manual bucket bump for most upgrades.

## Source

The fresh CLI manifest mirrors [`Jktfe/a-nice-terminal/scoop/ant.json`](https://github.com/Jktfe/a-nice-terminal/blob/main/scoop/ant.json). Version + hash are synced into this repo after each `ant-v*` release.
