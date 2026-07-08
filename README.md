# scoop-zyrax

Scoop bucket for [Zyrax Guard](https://github.com/tiagosilva07/zyrax-guard) — audit AI agent
configs (prompt injection, rogue MCP servers) and vet packages before install.

```powershell
scoop bucket add zyrax https://github.com/tiagosilva07/scoop-zyrax
scoop install zyrax-guard
```

Update with `scoop update zyrax-guard` — or just run `zyrax-guard upgrade`, which detects the
scoop install and delegates.

The manifest is regenerated automatically on every [release](https://github.com/tiagosilva07/zyrax-guard/releases)
by `scoop-bump.yml` in the main repo; hashes come from the release's signed `checksums.txt`.
