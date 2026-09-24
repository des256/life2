# Tasks

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

- implement MB3D key mappings:
  - W/S - forward/backward
  - A/D - left/right strafe
  - E/C - up/down strafe
  - U/O - axial roll
  - I/K - up/down tilt
  - J/L - left/right tilt
  - F3/F4 - zoom in/out
  - F1/F2 - move far plane
- camera contains z_far control
- tweak Park modes:
  - flat = 0 1
  - linear = 0..1
  - Ozora = cubic with dy=0 at the ends
  - Boom = 0 1 0 1
  - Organik = 0 1..1 0..0 1
  - Earth Frequency = 0..1 0..1
  - Universo Paralello = 0 1..0 1
- design.lights: changed type to radiobutton
- design.lights: move color/intensity/shadow to top, so type is editable at the bottom
- design.lights: angle X and Y are now sliders
- explore.formula: dropdown should respond now
- explore: flex now 2:5:3 for bigger formula area
- iteration: julia mode now radiobutton
- iteration: improvement around specifying DE step size/stop/etc. (curious if it's actually an improvement)
- fix path trace: include specular lobe for reflection
- fix: double gamma
- fix: run gamma after tone mapping instead of before
- fix: remove global material, use full material list for tracing
- fix path trace: shadow quirk
- fix path trace: fix refraction
- separate layers to PNG as well
- implement EXR
- fix palette loading
- tooltips to describe the parameters
- cancel command needs to really cancel forge
- updated M3P loader to represent material palette slightly better
- animation page with keyframe editor

### general

- camera reset button
- clear/new button
- M3I loader
- M3L loader, maybe JSON equivalent

### file format

- add versioning

### preview area

- proper handling of redraw from preview state flags

### Formula

- refactor formula system with DSL and SIMD JIT compiler
- add more formulas
- improve list management
- parameters by sliders

### Materials

- implement Ride
- Park: UI is wonky, main range and zoomed range are not behaving as they should, sampling tries to optimize CSS

### Lights

- shadow toggle should only be available for non-path trace method
- re-render shadows when moving lights

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

- animation settings, interpolation mode

## Robot Power Board

## Oral Stories

- fatbike
- Janet Jackson

## Written Stories

-
