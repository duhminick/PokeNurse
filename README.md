# PokeNurse
[![license](https://img.shields.io/github/license/mashape/apistatus.svg?maxAge=2592000)]()
[![build Status](https://travis-ci.org/vinnymac/PokeNurse.svg?branch=develop)](https://travis-ci.org/vinnymac/PokeNurse)
[![style](https://img.shields.io/badge/style-standard-brightgreen.svg)]()
[![discord](https://img.shields.io/badge/discord-PokéNurse-738bd7.svg)](https://discord.gg/sSXCruy)

<img src="app/app.png?raw=true" width="32px" align="left" hspace="10" vspace="10">

**PokéNurse** is a desktop application for Windows and Mac that allows you to manage your pokémon from Pokémon Go without the need for a mobile device. You can now favorite, transfer, and evolve from the comfort of your own home!

## Downloads for v1.1.2
You may view all the releases [here](https://github.com/vinnymac/PokeNurse/releases)
* [Mac OS X](https://github.com/vinnymac/PokeNurse/releases/download/v1.1.2/PokeNurse-darwin-x64.zip)
* [Windows 32 bit](https://github.com/vinnymac/PokeNurse/releases/download/v1.1.2/PokeNurse-win32-ia32.zip)
* [Windows 64 bit](https://github.com/vinnymac/PokeNurse/releases/download/v1.1.2/PokeNurse-win32-x64.zip)
* [Linux 32 bit](https://github.com/vinnymac/PokeNurse/releases/download/v1.1.2/PokeNurse-linux-ia32.zip)
* [Linux 64 bit](https://github.com/vinnymac/PokeNurse/releases/download/v1.1.2/PokeNurse-linux-x64.zip)

## Examples
![Login Window](http://i.imgur.com/QaeO99H.png)
![Main Window](http://i.imgur.com/ZGU0ee7.png)

This is my first project using [Electron](http://electron.atom.io/) and [Node.js](https://nodejs.org/en/).  Criticism is welcome and encouraged.

## Features
* List Pokemon
    * Pokedex Number
    * Name
    * CP
    * IV
* Transfer Pokemon
* Evolve Pokemon
* Favorite/Unfavorite Pokemon

## Contributing
  All future pull request should be made to the **develop** branch.

    git clone https://github.com/vinnymac/PokeNurse
    cd PokeNurse
    git checkout develop
    npm install
    npm run dev

## Releases

  Package for your platform

    npm run package

  Package for a specific platform ([docs packager](https://github.com/electron-userland/electron-packager/blob/master/docs/api.md))

    npm run package -- --platform=linux --arch=x64

  Package for all platforms

    npm run package-all

## FAQ
1. Will I be banned from pokemon go for using PokeNurse?

This app is meant to make pogo easier to manage. This is not a bot. We do not send location data. No one has ever been banned for using PokeNurse as far as we are aware. This doesn't mean you cannot be banned, if they somehow begin to detect API calls from pogobuf, then this may very well start happening, but that is the risk of using any of these third party tools right now that are not the original app.

## Todo
* Nickname Pokemon

## Known Issues
* Sometimes after login, the page will stay white instead of showing the list of Pokemon
* Google 2 Factor Authentication cannot be used. However you can use an [AppPassword](https://security.google.com/settings/security/apppasswords) instead.

## Credit
* [cyraxx](https://github.com/cyraxx) for [pogobuf](https://github.com/cyraxx/pogobuf) and [node-pogo-protos](https://github.com/cyraxx/node-pogo-protos)
* [AeonLucid](https://github.com/AeonLucid) for [POGOProtos](https://github.com/AeonLucid/POGOProtos)

## Legal
This Project is in no way affiliated with, authorized, maintained, sponsored or endorsed by Niantic, The Pokémon Company, Nintendo or any of its affiliates or subsidiaries. This is an independent and unofficial API for educational use ONLY. Using the Project might be against the TOS
