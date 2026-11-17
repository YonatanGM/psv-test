# psv-test

The NSYNK office (17th floor), 38 places from a Leica BLK360 scan, as a 360° tour with [Photo Sphere Viewer](https://photo-sphere-viewer.js.org) 5.15.1.

- `v2.html`: the test page. The **Options** panel (top right) switches PSV's own options, plugins, marker types and tour modes.
- `index.html`: the first, plain version.

Static files only, no build step (library files in `vendor/`, loaded with an import map). Generated from the NSYNK project's data (`tour.json`, `tour-v2.json`, `nodes/`).
