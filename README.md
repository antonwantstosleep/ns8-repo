# Personal NS8 repository

Software Center index for modules published from this account:

- [n8n](https://github.com/antonwantstosleep/ns8-n8n) (`ghcr.io/antonwantstosleep/n8n`)

One Pages site serves every package in this index:

```text
https://antonwantstosleep.github.io/ns8-repo/
```

Add that URL once in Software Center → Settings → Software repositories. Existing installers use the repository name `z-n8n`. That name sorts after `nethforge`, so the n8n package from this index replaces the official one. Other NethForge applications stay available.

`createrepo.py` reads semantic versions from each image under `ghcr.io/antonwantstosleep/<package id>`. The GHCR package must be public and must carry a semver tag such as `0.1.0`. A GitHub Actions run refreshes `repodata.json` on every push to `main`, every hour, and on demand.

Current n8n image: `ghcr.io/antonwantstosleep/n8n:0.1.2` (n8n 2.42.3, runners 2.42.3, Postgres 16.15).
