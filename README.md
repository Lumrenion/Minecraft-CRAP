# Minecraft-CRAP
Minecraft Modpack "Creativity, Resources and Awesome Places"

This fabric modpack does not add new content to the game. Its main goals are
- improve server and client performance
- improve gameplay 

See [Modlist](Modpack/modlist.html) for a complete list of mods.

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

`fix` will create a new patch version. `feat` will create a new minor version. To release a new major version,
add `BREAKING CHANGE` to the commit message. E.g.:
```
feat(modlist): Update all mods
BREAKING CHANGE: All mods have been upgraded to the newest version. Server and client must be in sync
```