# sm64js

### Links
[Main Website: sm64js.com](https://sm64js.com)

[Discord Server](https://discord.gg/7UaDnJt)

## What is this?
This is an ongoing work-in-progress port of the decompilation of original Nintendo game, Super Mario 64, to native Javascript (no emulation or web assembly). The project involved creating a Javascript WebGL port of N64 Fast 3D Renderer, originally implemented with OpenGL in C.  This project also includes the development of online mass multiplayer versions of sm64js and other custom multiplayer game modes.

## Build instructions - Windows, Mac, or Linux



### Run these commands
```bash
# Node.js For Windows And Linux Virtual Machine For Mac
npm install

npm run start

node serveProduction.js
```
Npm install will give the dependecies needed.

Npm run start will start localhost:9300.

Node serveProduction.js will start MMO
You should now be able to access the website with the game from a web browser by typing "localhost" into the address bar.


### Related Projects
[Super Mario 64 Decomp](https://github.com/n64decomp/sm64)
 - Team that decompiled the original Super Mario 64 ROMs into C source code

[Super Mario 64 PC Port](https://github.com/sm64-port/sm64-port)
 - Team that ported the decompiled project to PC

[N64 Fast 3D Renderer](https://github.com/Emill/n64-fast3d-engine)
 - OpenGL Implementation of a 3D renderer for the Nintendo 64's graphics
(For this project, it was re-implemented in Javascript and WebGL)


