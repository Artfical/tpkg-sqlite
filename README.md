# sqlite

SQLite 3.46.1: the library (with FTS5 and JSON) and the sqlite3 shell

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install sqlite
```

| | |
|---|---|
| Version | 3.46.1 |
| Licence | Public domain |
| Upstream | https://www.sqlite.org |
| Needs | [`gcc`](https://github.com/Artfical/tpkg-gcc), [`zlib`](https://github.com/Artfical/tpkg-zlib) |
| Needs tOS build | 615 or newer |
| Size | 3435295 bytes (7287215 unpacked) |
| SHA-256 of the `.tpkg` | `16221f7bd878584d2d988fe0e2abafd2cfdb4efff6cb906d3a84a2eb202cfe91` |

## Commands it adds

| Command | Runs |
|---|---|
| `sqlite3` | `bin/sqlite3` |

## Download

The package file (`sqlite-3.46.1.tpkg`) and the sources it was built from are the assets of the
[v3.46.1 release](https://github.com/Artfical/tpkg-sqlite/releases/tag/v3.46.1).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `sqlite-autoconf-3460100.tar.gz`

Check a download: `sha256sum sqlite-3.46.1.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: Public domain. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
