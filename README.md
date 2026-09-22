# STOW Scoop Bucket

Official Scoop bucket for [STOW](https://github.com/nocturney/STOW).

STOW is currently in preview. The normal Scoop channel intentionally remains empty until the first stable STOW release, because Scoop's GitHub version checker ignores prereleases by default.

## Stable install

Once a stable manifest is published:

```powershell
scoop bucket add stow https://github.com/nocturney/scoop-stow
scoop install stow
```

## Update

```powershell
scoop update
scoop update stow
```

## Uninstall

```powershell
scoop uninstall stow
```

STOW is installed by Scoop in portable/package-managed mode. Scoop remains responsible for upgrades; STOW's self-updater does not take over package-managed copies.

Legacy Trayify metadata is retained under `legacy/` for historical reference only and is not part of the active bucket.
