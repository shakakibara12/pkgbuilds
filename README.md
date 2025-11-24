# A bunch of PKGBUILDS
I created this repo for the sole purpose of personal usage. This consists of different pkgbuilds, entirely created by me, or with some slight qol improvements to existing pkgbuilds available at AUR or official repos.

## Get started
`git clone --depth 1 https://github.com/shakakibara12/pkgbuilds`
`cd pkgbuilds`
`git submodule --depth 1 update`

### llama.cpp
For this pkgbuild due to constant upstreams releases, it is recommended to use pkgctl for updating it. It uses nvchecker to update the pkgbuild.
`pkgctl version upgrade`
