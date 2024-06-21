# Plane fonts

All fonts is in /dist

- ./dist/Plane -> all family font
- ./dist/PlaneNd -> All NerdFont

## Install

Install: `ttfautohint` aur
Install: `FontForge`

```bash
# 1. Clone Iosevka
$ git clone --depth 1 https://github.com/be5invis/Iosevka.git
# after clone for update.. `git fetch --depth=1`, `git pull --rebase`

# 2. Customizer Iosevka
$ cp conf-plane.toml Iosevka/private-build-plans.toml

# 3. Install dependecies
$ $ cd Iosevka && npm i

# 4. Make de font
$ npm run build -- contents::Plane

# Prepare font
$ cd .. && cp ./Iosevka/dist to ./dist/Plane


# ------ Nerd fonts ------

# 1. Clone NerdFont
$ git clone --depth 1 https://github.com/ryanoasis/nerd-fonts.git
# after clone for update.. `git fetch --depth=1`, `git pull --rebase`

# 2. Patches the font, edit this file for change what fonts to path
$ sh render

# ---> Get all fonts in ./dist

```
