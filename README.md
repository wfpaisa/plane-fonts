# plane-fonts


Install: `ttfautohint` aur

```bash
$ cp conf-plane.toml Iosevka/private-build-plans.toml
$ git clone --depth 1 https://github.com/be5invis/Iosevka.git
$ cd Iosevka
$ npm run build -- contents::plane
# copy Iosevka/dist to ./dist/plane

# repet the process with
$ cp conf-plane-terminal.toml Iosevka/private-build-plans.toml

# ------

$ git clone --depth 1 https://github.com/ryanoasis/nerd-fonts.git
$ cd nerd-fonts

# add nerd-font to light and bold
# create the folders `./patched-fonts/plane/` and `./patched-fonts/plane-nerd`
$ ./font-patcher ./patched-fonts/plane/plane-terminal-light.ttf -out ./patched-fonts/plane-nerd --fontawesome --fontawesomeextension --fontlinux --octicons --powersymbols --powerline --powerlineextra --material

# copy `./patched-fonts/plane-nerd` to ./dist/plane-terminal_nerd
```


