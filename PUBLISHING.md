# Publishing

Public repository:

- `https://github.com/teogsxr/007-first-light-italian-dub-v0.1`

Public release:

- `https://github.com/teogsxr/007-first-light-italian-dub-v0.1/releases/tag/v0.1`

The repo contains generated mod assets, manifests, documentation and installer scripts.
It must not contain original game chunks, original WEMs, original source audio, or local
QA pages that embed original source audio.

To update the public package:

```powershell
git status -sb
git add -A
git commit -m "Update release package"
git push
gh release upload v0.1 ..\007-first-light-italian-dub-v0.1.zip --clobber
```

Before every push, scan for local-only or original-audio paths:

```powershell
Get-ChildItem -Recurse -File |
  Select-String -Pattern '127\.0\.0\.1|local comparison|original source audio'
```
