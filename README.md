# A bunch of PKGBUILDS
I created this repo for the sole purpose of personal usage. This consists of different pkgbuilds, entirely created by me, or with some slight qol improvements to existing pkgbuilds available at AUR or official repos.

## Get started
In one line:

`git clone --depth 1 --recurse-submodules --shallow-submodules https://codeberg.org/shakakibara12/pkgbuilds`

Or in multiple:
```
git clone --depth 1 https://codeberg.org/shakakibara12/pkgbuilds
cd pkgbilds
git submodule init && git submodule update
```

### llama.cpp
For this pkgbuild due to constant upstreams releases, it is recommended to use pkgctl for updating it. It uses nvchecker to update the pkgbuild.

`pkgctl version upgrade`
