# ANKITA Scoop bucket

Official publisher bucket for [ANKITA](https://ankita-sable.vercel.app), an open-source desktop AI workspace. Windows x64. Package metadata is free and MIT licensed. Model providers may have their own account or usage requirements.

```powershell
scoop bucket add ankita https://github.com/akyourowngames/scoop-ankita
scoop install ankita/ankita
```

The manifest downloads the portable executable directly from the official GitHub release and verifies its SHA256. It adds a Start menu shortcut. Application settings remain in ANKITA's normal user profile; the bucket does not move or remove them.

```powershell
scoop update
scoop update ankita
scoop uninstall ankita
```

The bucket is published separately because Scoop Extras' popularity requirement is not currently met. End-to-end install/uninstall testing remains pending.
