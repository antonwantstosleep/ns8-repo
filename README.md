# Personal NS8 repository

Index for the n8n module published from [antonwantstosleep/ns8-n8n](https://github.com/antonwantstosleep/ns8-n8n).

Software Center URL:

```text
https://antonwantstosleep.github.io/ns8-repo/
```

Add it in Software Center → Settings → Software repositories with the name `z-n8n`. That name sorts after `nethforge`, so this n8n replaces the official one. Other NethForge applications stay available.

`createrepo.py` reads semantic versions from `ghcr.io/antonwantstosleep/n8n`. The image package must be public. A GitHub Actions run refreshes `repodata.json` on every push to `main`, every hour, and on demand.
