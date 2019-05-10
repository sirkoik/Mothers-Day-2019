# Mothers Day 2019

## v0.1.1
* Implemented bobber function.

## v0.1
* Adjusted the lighting.
* Fixed the texture (now loads).

## v0.0.5a
* Better switching mechanics.
* Added switch sound.

## v0.0.4a
* Cycling and on / off works better.

## v0.0.3a
* Got PointLights on letters working, and with glow as well!

## v0.0.2a
* Basic animated lighting enabled
* Still need to adjust PointLights on letters.
* Need to fix textures.

# Suggestions
* 3D on/off switch? (Replaced with text as of v0.1)
* <a href="https://stackoverflow.com/questions/50948014/emit-light-from-an-object">Bloom?</a> 
* Vertical oscillation.

# Mobile troubleshooting
1. Added cube to check loading: cube loads.
2. Checked console with console remap. No errors.
2. Old non-textured letters do not show either.
2. Turned off blinker functions. <b>Letters show!</b>
2. Disabled pointLights, as suggested in <a href="https://github.com/mrdoob/three.js/issues/9131">three.js issue #9131</a>. Letters show. Use area lamps / spotlights instead?