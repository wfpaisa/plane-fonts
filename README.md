# plane-fonts


Install: `ttfautohint` aur

```bash
$ cp private-build-plans.toml Iosevka/private-build-plans.toml
$ git clone --depth 1 https://github.com/be5invis/Iosevka.git
$ cd Iosevka
$ npm run build -- contents::plane
$ cp -R Iosevka/dist font
```

