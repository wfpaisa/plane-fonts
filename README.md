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
# after clone for update.. `git fetch --depth=1`, `git pull --rebase` (# puede que se necesite eliminar la carpeta si este creada)

# 2. Customizer Iosevka
$ cp conf-plane.toml Iosevka/private-build-plans.toml

# 3. Install dependecies
$ cd Iosevka && npm i

# 4. Make de font
$ npm run build -- contents::Plane

# Eliminar contenido de dist

# Prepare font
$ cd .. && cp -r ./Iosevka/dist/Plane ./dist/


# ------ Nerd fonts ------

# 1. Clone NerdFont, se intenta usar docker pero al renderizar la fuente queda espaciada, mejor se clona
# $ git clone --depth 1 https://github.com/ryanoasis/nerd-fonts.git
# after clone for update.. `git fetch --depth=1`, `git pull --rebase`

# 2. Patches the font, edit this file for change what fonts to path
$ sh render

# ---> Get all fonts in ./dist

```
