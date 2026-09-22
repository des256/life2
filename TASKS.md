# Tasks

## Blocked

- Recombination DLC: waiting for Meta conversation

## Clean up

- table
- kitchen
- balcony
- lab
- bedroom
- bathroom/restroom
- laundry

## Thalamus

## Thalamus Model

## Youtube Videos

## Fractal One

### to be verified / done

- [DONE] implement MB3D key mappings:
  - W/S - forward/backward
  - A/D - left/right strafe
  - E/C - up/down strafe
  - U/O - axial roll
  - I/K - up/down tilt
  - J/L - left/right tilt
  - F3/F4 - zoom in/out
  - F1/F2 - move far plane
- [DONE] camera contains z_far control
- [DONE] tweak Park modes:
  - flat = 0 1
  - linear = 0..1
  - Ozora = cubic with dy=0 at the ends
  - Boom = 0 1 0 1
  - Organik = 0 1..1 0..0 1
  - Earth Frequency = 0..1 0..1
  - Universo Paralello = 0 1..0 1
- [DONE] design.lights: changed type to radiobutton
- [DONE] design.lights: move color/intensity/shadow to top, so type is editable at the bottom
- [DONE] design.lights: angle X and Y are now sliders
- [DONE] explore.formula: dropdown should respond now
- [DONE] explore: flex now 2:5:3 for bigger formula area
- [DONE] iteration: julia mode now radiobutton
- [DONE] iteration: improvement around specifying DE step size/stop/etc. (curious if it's actually an improvement)
- [DONE] fix path trace: include specular lobe for reflection
- [DONE] fix: double gamma
- [DONE] fix: run gamma after tone mapping instead of before
- [DONE] fix: remove global material, use full material list for tracing
- [DONE] fix path trace: shadow quirk
- [DONE] fix path trace: fix refraction
- [DONE] separate layers to PNG as well
- [DONE] implement EXR
- [DONE] fix palette loading

### general

- tooltips to describe the parameters
- forge and server hotswapping
- cancel command needs to really cancel forge
- camera reset button
- clear/new button
- M3L loader, maybe JSON equivalent

### file format

- what is "palette_z_offset" for? remove and adjust M3P loader accordingly
- add versioning

### preview area

- proper handling of redraw from preview state flags

### Formula

- add more formulas
- improve list management
- parameters by sliders

### Materials

- implement Ride
- Park: interpolation is rough, it takes only a few samples, should probably sample entire area

### Lights

- shadow toggle should only be available for non-path trace method

### Atmosphere

- review parameters, maybe only use background colors
- alpha background

### Fog

- depth or dynamic radiobutton
- review parameters
- god rays
- when switching fog, redraw properly

### Render

- review parameters

### Output

- verify all output formats for each camera type
- fix: format dropdown bug

### Animation

- ultra-rough preview to update current keyframe
- different preview rendering, possibly timeline with each keyframe
- selectable/draggable keyframes
- current keyframe is the one that's being edited on the other screens
- animation settings, interpolation mode
- animation rendering with forge

## Robot Power Board

## Oral Stories

- fatbike
- Janet Jackson

## Written Stories

-
