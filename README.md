# Minecraft-CRAP
Minecraft Modpack "Creativity, Resources and Awesome Places"

This pack is a subset of favorite mods taken from the great modpacks [All The Mods 6](https://www.curseforge.com/minecraft/modpacks/all-the-mods-6) and [Create 101 Season 2](https://www.curseforge.com/minecraft/modpacks/create-101-season-2/) as well as some other mods. This modpack is meant to bring a great minecraft extended experience while being lightweigt with under 60 mods. Main focus is on building and automation for a medieval like server setup, and world exploration. \
See [Modlist](Modpack/modlist.html) for a complete list of mods.

## Features
- Lightweight
- Keeps the server performance as high as possible
- Big set of new blocks and decorative items for great buildings
- Tech from Create mod only, to maintain a medieval flair
- Great biomes from Biomes O' Plenty
- Better world generation with a bigger variety of buildings and overhauled vanilla structures
- Animals that add up to the variety of the generated worlds, to make exploration even more fun

## Disclaimer
This modpack is primarily created for personal use. Feel free to use, copy and change it as much as you wish.

## Build
This package uses an automated build process. When a new release happens, the modpack version in 
[`Modpack/manifest.json`](Modpack/manifest.json) as well as the `modpackUrl` in 
[`Serverpack/server-setup-config.yaml`](Serverpack/server-setup-config.yaml) are updated automatically. The files must
be uploaded to curseforge manually.

For commit messages, use [Angular commit message conventions](https://github.com/angular/angular/blob/master/CONTRIBUTING.md#-commit-message-format):
```
<type>(<scope>): <short summary>
```
Allowed Types are

- **build**: Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)
- **ci**: Changes to our CI configuration files and scripts (example scopes: Circle, BrowserStack, SauceLabs)
- **docs**: Documentation only changes
- **feat**: A new feature
- **fix**: A bug fix
- **perf**: A code change that improves performance
- **refactor**: A code change that neither fixes a bug nor adds a feature
- **test**: Adding missing tests or correcting existing tests

Notice: Only types `perf`, `feat` and `fix` will trigger the build of a new release.