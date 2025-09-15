This tool for maintains AES-256 encrypted file with accessCodes to oidc.plus4u.net.

[Changelog](doc/CHANGELOG.md)

# "DIRTY" INSTALLATION OF FIX
- Install `npm install -g oidc-plus4u-vault`
- List your install path by running cmd `npm root -g`
- Find `oidc-plus4u-vault` 
- Replace `oidc-plus4u-vault/app/tasks/ls.js` with `ls.js` from this repo

# How to install ?

`npm install -g oidc-plus4u-vault`

# How to use ?

![Help](doc/help.png)

# How to develop ?

Publish new version
1. `npm pack`
2. `npm publish --registry https://registry.npmjs.org/`
