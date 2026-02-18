# WebROTT: Rise of the Triad for the web

Ported by [Neil Rackett](https://x.com/neilrackett)

## Introduction

<img width="638" height="397" alt="image" src="https://github.com/user-attachments/assets/1558c670-be05-427a-b1ce-1ee767a4870e" /> <img width="638" height="397" alt="image" src="https://github.com/user-attachments/assets/17067577-e151-4d6d-a9c6-69a1ef9d9837" />

After porting [Rise of the Triad (ROTT) to Atari ST](https://github.com/neilrackett/atarist-rott/releases), I thought it was only fair that I should create a version for those of you that, for whatever inexplicable reason, don't own any of Atari's late-80s or early-90s hardware.

_Welcome to WebROTT: all of the original features, no installation required._

[Click here to try it now!](https://labs.neilrackett.com/rott)

Supports keyboard, mouse or joystick/gamepad controls.

## Build

You can build the WebAssembly version of ROTT using [Emscripten](https://emscripten.org/):

- Install the shareware version of ROTT for DOS using DOSbox (or [download the files from Archive.org](https://archive.org/details/rott_shareware))
- Create a `tmp` folder in the root of this project
- Copy the `ROTT` folder you installed the DOS version into to the `tmp` folder (the actual folder, not just the contents)
- Run `make`

All of the files you need to deploy WebROTT will be in the `build` folder, and you can play them locally by running `make serve` and opening http://localhost:8000 in your browser.

The build process uses Emscripten's internal version of SDL, so there's no need to install any dependencies.

## License

This software is distributed in source code format and is licensed under the
terms of the GNU General Public License. A copy of this license is included
with the software in the file COPYING.

This is a completely unofficial port and is not supported by 3D Realms, Apogee, or the porters.
