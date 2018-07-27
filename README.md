# screepsmod-tickrate

## This allows a server admin to set tick rate on the screeps private server

[![NPM info](https://nodei.co/npm/screepsmod-tickrate.png?downloads=true)](https://npmjs.org/package/screepsmod-tickrate)

[![Circle CI](https://circleci.com/gh/ScreepsMods/screepsmod-tickrate.svg?style=shield)](https://circleci.com/gh/ScreepsMods/screepsmod-tickrate)

# Installation 

1. `npm install screepsmod-tickrate` in your mods folder.
2. Edit your mods.json file to point to index.js such as:

```
  "mods": [
    "node_modules\\screepsmod-tickrate\\index.js",
  ],
```

3. Note due to https://github.com/screeps/screeps/issues/66, you will likely need to install my other mod https://github.com/ScreepsMods/screepsmod-mongo to increase the performance of the private server DB.


# Usage
1. Open the screeps server CLI
2. run `setTickRate(50)` (Change 50 to whatever rate you want in ms)

