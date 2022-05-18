# DDEV System for DFG Viewer

This DDEV system installs DFG Viewer based solely on its distribution package.

A more comprehensive DDEV system based on database dumps is available at https://github.com/slub/ddev-dfgviewer.

## Getting Started

```bash
ddev start
ddev check-install
ddev launch
```

You may need to set the storage PID in backend.

## URLs

- Backend Login: https://dfgviewer-dist.ddev.site/typo3/
  - User: `admin`
  - Password: `adminslub`
- phpMyAdmin: [https://dfgviewer-dist.ddev.site:8037](https://dfgviewer-dist.ddev.site:8037)
