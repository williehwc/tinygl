# TinyGL

This fork of TinyGL is intended to be used with [CroMagRallyWatch](https://github.com/williehwc/CroMagRallyWatch) or the software-rendered [CroMagRally](https://github.com/williehwc/CroMagRally) standalone SDL game. It is forked from [C-Chads/tinygl](https://github.com/C-Chads/tinygl), which is based on the original TinyGL project by Fabrice Bellard.

## Changes

- Add glOrtho, glGetBooleanv, and glIsEnabled functions
- Add support for 1-5-5-5 ARGB, used by terrain textures in Cro-Mag Rally
- Add support for textures with alpha transparency, based on Zoltan Baldaszti's [proposed changes](https://github.com/C-Chads/tinygl/issues/18)
