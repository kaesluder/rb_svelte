# Radio Gaga

![screenshot showing grid of stations, search bar, and floating audio controls in lower-left corner](https://kaesluder.github.io/kae-garden-wiki/Radio_Browser_GaGa/Screenshot_20231118_150330.png)

A simple streaming radio player built with love using [Tauri](https://tauri.app), [SvelteKit](https://kit.svelte.dev) and [tailwindcss](https://tailwindcss.com). Looks up stations on [radio-browser](https://www.radio-browser.info).
## Install

Currently, this project needs to be built from code while I figure out how to package audio codecs. You will need a working [rust](https://www.rust-lang.org/tools/install) and [node](https://nodejs.org/en) tools. 

Last built using:
- node: v18.16.1
- rustc: 1.74.0 (79e9716c9 2023-11-13)


Ubuntu codec install:

```sh
sudo add-apt-repository multiverse
sudo apt install ubuntu-restricted-extras
sudo apt update

```


```sh
git clone https://github.com/kaesluder/radiogaga.git ./radiogaga
cd radiogaga
npm install
cargo tauri dev

```


## Current Status

- [x] Player is semi-functional able to play direct links to MP3 and AAC streams.
- [x] Search by name working.
- [x] Links to playlist (`.pls`) working.
- [ ] Implement tag search.
- [ ] Implement favorites system
- [ ] Implement preferences
- [ ] AppImage builds are broken
- [ ] Testing testing testing
- [ ] Build instructions
- [ ] Rust side testing
- [ ] Github CI
