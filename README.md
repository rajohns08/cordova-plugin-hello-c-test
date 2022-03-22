## Environment Setup
#### Steps to get environment set up from a fresh clone of repo:
1. clone this repo
2. `cd` into repo directory
3. install [nvm](https://github.com/nvm-sh/nvm) if you don't already have it
4. `nvm use 16.9.1` (`nvm install 16.9.1` if not already installed)
5. `npx cordova platform add android`

#### Steps to set up environment with link to local plugin for development
1. clone this repo
2. `cd` into repo directory
3. install [nvm](https://github.com/nvm-sh/nvm) if you don't already have it
4. `nvm use 16.9.1` (`nvm install 16.9.1` if not already installed)
5. Remove all references to `cordova-plugin-hello-c` from package.json and package-lock.json
6. `npx cordova platform add android`
7. `npx cordova plugin add ../cordova-plugin-hello-c --link`
