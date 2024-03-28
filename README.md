# Install
[![ci](https://github.com/ttiimmothy/install/actions/workflows/ci.yml/badge.svg)](https://github.com/ttiimmothy/Install/actions/workflows/ci.yml)

Software that needed to be installed

## Editor

- Editor

1. [Visual Studio Code](https://code.visualstudio.com/)
1. [Intellij](https://www.jetbrains.com/idea/download/?section=mac)
1. [Pycharm](https://www.jetbrains.com/pycharm/download/?section=mac)
1. [RustRover](https://www.jetbrains.com/rust/nextversion/)
1. [Neovim](https://github.com/neovim/neovim) - `brew install neovim`

- Visual Studio Code settings and extensions: [ttiimmothy/vscode-settings](https://github.com/ttiimmothy/vscode-settings)
- Neovim settings: [ttiimmothy/nvim-dotfiles](https://github.com/ttiimmothy/dotfiles/tree/main/.config/nvim)

## Terminal

- [iTerm](https://iterm2.com/) - Terminal replacement

## Microsoft Edge Extensions

- [AdGuard AdBlocker](https://microsoftedge.microsoft.com/addons/detail/adguard-adblocker/pdffkfellgipmhklpdmokmckkkfcopbh)
- [React Developer Tools](https://microsoftedge.microsoft.com/addons/detail/react-developer-tools/gpphkfbcpidddadnkolkpfckpihlkkil)
- [Redux Devtools](https://microsoftedge.microsoft.com/addons/detail/redux-devtools/nnkgneoiohoecpdiaponcejilbhhikei)
- [Vue Telescope](https://microsoftedge.microsoft.com/addons/detail/vue-telescope/icgcillpgelpleniodgkmohgdmeogodl) - Check what the versions of vue and frameworks that the websites use
  - [github repo](https://github.com/nuxtlabs/vue-telescope-analyzer)
- [Vue.js devtools](https://microsoftedge.microsoft.com/addons/detail/vuejs-devtools/olofadcdnkkjdfgjcmjaadnlehnnihnl)
- (**Optional**) [Wappalyzer](https://microsoftedge.microsoft.com/addons/detail/wappalyzer-technology-p/mnbndgmknlpdjdnjfmfcdjoegcckoikn) - **Don't** recommend installing because of the frequent updates

## MacOS Productivity

- [Raycast](https://raycast.com/) - Spotlight replacement
- (**Optional**) [Final Cut Pro](https://www.apple.com/ca/final-cut-pro/) - Video editor
- [Microsoft Edge](https://www.microsoft.com/en-us/edge?ep=198&form=MA13L7&es=40) - Preferred browser
- [Logi Options+](https://www.logitech.com/en-us/software/options.html) - Mouse configuration
- [OBS](https://obsproject.com/) - Streaming and recording
- [Docker](https://docs.docker.com/desktop/install/mac-install/) - Docker dashboard
- [SourceTree](https://www.sourcetreeapp.com/) - Visual panel for `git control`
- [Microsoft Word](https://www.microsoft.com/en-us/microsoft-365/download-office)

## Social Media

- [Discord](https://discord.com/)
- [Signal](https://signal.org/download/)

## Useful Website

- [Figma](https://www.figma.com/) - Illustrations, logos
- [DrawSQL](https://drawsql.app/diagrams) - Illustration of SQL tables
- [ChatGPT](https://chat.openai.com/)

## CLI

- [`zsh`](https://zsh.org/)
- [`fish`](https://fishshell.com/)
  - Config: [ttiimmothy/dotfiles](https://github.com/ttiimmothy/dotfiles)
- [`bun`](https://bun.sh/) - Preferred package managers
- [`npm-check-updates`](https://github.com/raineorshine/npm-check-updates) - Upgrade dependencies
  - [ ] `npm upgrade` cannot upgrade all the dependencies listed in `package.json`, only can do the major updates in **Greater Than or Equal To (>=)** `"react": ">=17.0.2"`
- **The *below version ranges* cannot be upgraded by `npm upgrade` but can be upgraded by `npm-check-updates`, because `npm upgrade` cannot directly change the version in `package.json`**
  - Exact Version
  `"react": "17.0.2"`
  - Caret (^)
  `"react": "^17.0.2"`, this can only be compatible to `17.1.0`, but not `18.0.0`
  - Tilde (~)
  `"react": "~17.0.2"`, this allows any patch update to version `17.0.2`, such as `17.0.3`, but not minor updates like `17.1.0` or major updates like `18.0.0`
- [`tree-cli`](https://github.com/MrRaindrop/tree-cli) - Tools for displaying project tree
- [`unbuild`](https://github.com/unjs/unbuild) - Build tools for libraries

## License

Install is licensed under [GNU General Public License v3.0](LICENSE).