# Additional Token Frames  for FoundryVTT

![Latest Release Download Count](https://img.shields.io/github/downloads/p4535992/foundryvtt-additional-token-frames/latest/module.zip?color=2b82fc&label=DOWNLOADS&style=for-the-badge)

[![Forge Installs](https://img.shields.io/badge/dynamic/json?label=Forge%20Installs&query=package.installs&suffix=%25&url=https%3A%2F%2Fforge-vtt.com%2Fapi%2Fbazaar%2Fpackage%2Fadditional-token-frames&colorB=006400&style=for-the-badge)](https://forge-vtt.com/bazaar#package=additional-token-frames)

![Foundry Core Compatible Version](https://img.shields.io/badge/dynamic/json.svg?url=https%3A%2F%2Fraw.githubusercontent.com%2Fp4535992%2Ffoundryvtt-additional-token-frames%2Fmaster%2Fmodule.json&label=Foundry%20Version&query=$.compatibleCoreVersion&colorB=orange&style=for-the-badge)

![Latest Version](https://img.shields.io/badge/dynamic/json.svg?url=https%3A%2F%2Fraw.githubusercontent.com%2Fp4535992%2Ffoundryvtt-additional-token-frames%2Fmaster%2Fmodule.json&label=Latest%20Release&prefix=v&query=$.version&colorB=red&style=for-the-badge)

[![Foundry Hub Endorsements](https://img.shields.io/endpoint?logoColor=white&url=https%3A%2F%2Fwww.foundryvtt-hub.com%2Fwp-json%2Fhubapi%2Fv1%2Fpackage%2Fadditional-token-frames%2Fshield%2Fendorsements&style=for-the-badge)](https://www.foundryvtt-hub.com/package/additional-token-frames/)

![GitHub all releases](https://img.shields.io/github/downloads/p4535992/foundryvtt-additional-token-frames/total?style=for-the-badge)

[![Translation status](https://weblate.foundryvtt-hub.com/widgets/additional-token-frames/-/287x66-black.png)](https://weblate.foundryvtt-hub.com/engage/additional-token-frames/)

### If you want to buy me a coffee [![alt-text](https://img.shields.io/badge/-Patreon-%23ff424d?style=for-the-badge)](https://www.patreon.com/p4535992)

### This is just a personal fork of [https://github.com/yorkshirelandscape/token_frames](https://github.com/yorkshirelandscape/token_frames)

This is a updated/upgraded of the module [https://github.com/jcolson/token_frames](https://github.com/jcolson/token_frames)

Most of these token frames were harvested from other opensource projects.

A great tool to use in conjunction with this module is [Mr Primate's Tokenizer](https://github.com/MrPrimate/tokenizer).

![img](/wiki/support/github-social-preview.jpg)

![img](/wiki/support/TokenFrame.png)

## Installation

It's always easiest to install modules from the in game add-on browser.

To install this module manually:
1.  Inside the Foundry "Configuration and Setup" screen, click "Add-on Modules"
2.  Click "Install Module"
3.  In the "Manifest URL" field, paste the following url:
`https://raw.githubusercontent.com/p4535992/foundryvtt-additional-token-frames/master/module.json`
4.  Click 'Install' and wait for installation to complete
5.  Don't forget to enable the module in game using the "Manage Module" button

### Sourced from TokenTool

[TokenTool](https://github.com/RPTools/TokenTool), which uses the ["GNU AFFERO GENERAL PUBLIC LICENSE"](https://github.com/RPTools/TokenTool/blob/main/LICENSE.md).

### Sourced from MTVExtreme

[MTVExtreme](https://www.deviantart.com/mtvextreme) on DeviantArt made a few really cool token frames based on the seasons.

### Sourced from Jinker

[Jinker#8073](https://discord.com) on Discord made a really cool 'web' themed token.

### Sourced from /u/Benjosity

[Benjosity](https://reddit.com/u/Benjosity) on Reddit made some really nice backgrounds and tokens, included them with their permission!

### Sourced from Pngwing

[Pngwing](https://www.pngwing.com/en/) has many high quality images that can be used for tokens, and can be used for non-commercial use!

### Sourced from pdzoch

[pdzoch](https://imgur.com/user/pdzoch) created many CR level coordinated token frames for baddies that have now been included.

### Sourced from Drehatlas#9068

[Drehatlas#9068](https://discord.com) Created some token frames themself as they are working on an adventure module for TDE.  "In case someone else likes the frames, then the effort wasn't for nothing!"

### Sourced from EldritchImp#1049

[EldritchImp#1049](https://discord.com) contributed some beautifully crafted class-based token frames!

More of \[their\] content; check out the following social media links:

- [Twitter](https://twitter.com/Eldritch_Imp)
- [Facebook](https://www.facebook.com/ImpmanArt)
- [Instagram](https://www.instagram.com/eldritchimp/)
- [Portfolio](https://t.co/vHnsPxhq7A)

### Sourced from gus-uktena

Contact Info: [gus-uktena](https://github.com/gus-uktena)

[Requested that frames be added to foundry package](https://github.com/p4535992/foundryvtt-additional-token-frames/issues/8).

### Sourced from gus-uktena

Contact Info: [gus-uktena](https://github.com/gus-uktena)

[Requested that frames be added to foundry package](https://github.com/jcolson/token_frames/issues/8).

"Hello, I've just made some tokens for Band of Blades, which I would like to share with everyone. It includes a blank token so people can create their own variations. Thanks!"

### Sourced from Geekswordsman

Geekswordsman has graciously agreed to include some of his creations in the module. He can usually be found on the Foundry VTT discord server if you need to get in touch with him.

### Change of ownership and new token frames from volfied

Many thanks to Jay Colson for creating this module. In his absence, I have assumed direction of the project. I have also added some token frames of my own.

## Feel free to send pull requests for additional token frame content

If you have your own token frames that you would like to share with the Foundry community, please open a pull request here or open an [Issue](https://github.com/p4535992/foundryvtt-additional-token-frames/issues) and I'll do my best to incorporate your content in the next release.

## Other modules

[Additional Cards](https://github.com/p4535992/foundryvtt-additional-cards) is a module that adds three new Foundry V9 card decks for import from a compendium
[Additional Icons](https://github.com/p4535992/foundryvtt-additional-icons) is a module that add icons

# Build

## Install all packages

```bash
npm install
```

### dev

`dev` will let you develop you own code with hot reloading on the browser

```bash
npm run dev
```

## npm build scripts

### build

`build` will build and set up a symlink between `dist` and your `dataPath`.

```bash
npm run build
```

### build-watch

`build-watch` will build and watch for changes, rebuilding automatically.

```bash
npm run build-watch
```

### prettier-format

`prettier-format` launch the prettier plugin based on the configuration [here](./.prettierrc)

```bash
npm run-script prettier-format
```

### lint and lint:fix

`lint` launch the eslint process based on the configuration [here](./.eslintrc.json)

```bash
npm run-script lint
```

`lint:fix` launch the eslint process with the fix argument

```bash
npm run-script lint:fix
```

## [Changelog](./CHANGELOG.md)

## Issues

Any issues, bugs, or feature requests are always welcome to be reported directly to the [Issue Tracker](https://github.com/p4535992/foundryvtt-additional-cards/issues ), or using the [Bug Reporter Module](https://foundryvtt.com/packages/bug-reporter/).

## License

This package is under an [MIT license](LICENSE) and the [Foundry Virtual Tabletop Limited License Agreement for module development](https://foundryvtt.com/article/license/).

## Credit

Thanks to anyone who helps me with this code! I appreciate the user community's feedback on this project!
