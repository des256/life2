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

- tooltips to describe the parameters
- forge and server hotswapping (i.e. when forge disappears, automatically reconnect when one shows up again; same for server)
- tweak material and lighting settings when loading M3Ps to represent more authentically
- implement MB3D key mappings:
  - W/S - forward/backward
  - A/D - left/right strafe
  - E/C - up/down strafe
  - U/O - axial roll
  - I/K - up/down tilt
  - J/L - left/right tilt
  - F3/F4 - zoom in/out
  - F1/F2 - move far plane
  - F - create keyframe
- fix BRDF path tracing approach properly (proper specular PDF, so reflection and shadow are not needed in this path)
- shadow and reflection do not exist with path tracing (are automatic)
- design features and versioning
- cancel command needs to propagate to forge, really canceling immediately

### preview area

- proper handling of redraw from preview state flags

### Camera

- maybe move some other controls to the camera part

### Formula

- add more formulas
- improve list management
- parameters by sliders

### Iteration

- improvement around specifying DE step size/stop/etc.

### Materials

- tweak Park modes:
  - flat = 0 1
  - linear = 0..1
  - Ozora = cubic with dy=0 at the ends
  - Boom = 0 1 0 1
  - Organik = 0 1..1 0..0 1
  - Earth Frequency = 0..1 0..1
  - Universo Paralello = 0 1..0 1
- implement Ride

### Lights

- parameters by sliders

### Atmosphere

- review ambient
- review depth ambient
- review diffuse shadow
- review background; maybe just 2 colors for ambient+depth ambient+background...

### Fog

- fog: depth or dynamic
- review depth fog
- review dynamic fog
- god rays

### Render

- tweak AO methods
- review ray count
- review tone mapping
- review exposure
- review gamma
- review bloom and sharpen
- when switching between BRDF and Path Trace, the corresponding widgets should change too

### Output

- forge: each layer to separate PNG
- implement EXR
- verify all output formats for each camera type
- maybe combine camera and output settings or move stereo setup to camera part
- PNG should not revert to EXR

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
