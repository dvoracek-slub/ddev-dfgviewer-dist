# DDEV System for DFG Viewer

This DDEV system installs DFG Viewer based solely on its distribution package.

A more comprehensive DDEV system based on database dumps is available at https://github.com/slub/ddev-dfgviewer.

## Getting Started

```bash
git clone https://github.com/dvoracek-slub/ddev-dfgviewer-dist.git
cd ddev-dfgviewer-dist
git switch mediaplayer

ddev start
ddev check-install
ddev launch '/viewer?tx_dlf[id]=https://dfgviewer-dist.ddev.site/extra/Schattensucher.xml'
```

## Other Commands

```bash
# Start over
ddev reset
```

## URLs

- Backend Login: https://dfgviewer-dist.ddev.site/typo3/
  - User: `admin`
  - Password: `adminslub`
- phpMyAdmin: [https://dfgviewer-dist.ddev.site:8037](https://dfgviewer-dist.ddev.site:8037)
