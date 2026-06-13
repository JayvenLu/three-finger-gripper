# Three-Finger Gripper

Plain static GitHub Pages site for the three-finger vision-tactile gripper build.

Live page: https://jayvenlu.github.io/three-finger-gripper/

## Open-source CAD

The editable hardware design sources are available in [`assets/CAD`](assets/CAD):

| Model | STEP source | Browser preview |
| --- | --- | --- |
| Complete gripper | [`3finger_gripper.STEP`](assets/CAD/3finger_gripper.STEP) | [`3finger_gripper.glb`](assets/CAD/previews/3finger_gripper.glb) |
| Sensor mold | [`mold.STEP`](assets/CAD/mold.STEP) | [`mold.glb`](assets/CAD/previews/mold.glb) |

Use the STEP files for manufacturing and modification. The GLB files are derived, lightweight previews for the website.

The CAD sources and GLB derivatives under `assets/CAD/` are licensed under the [CERN Open Hardware Licence Version 2 - Strongly Reciprocal](assets/CAD/LICENSE.txt). Modified designs conveyed to others must remain available under the reciprocal terms of that license. The website code, photographs, videos, and other media outside `assets/CAD/` are not covered by this CAD license.

Suggested citation:

> Xiaofan Lu, Yuankai Lin, and Jiahui Chen, "Three-Finger Gripper CAD," GitHub repository, 2026. https://github.com/JayvenLu/three-finger-gripper

See [`assets/CAD/README.md`](assets/CAD/README.md) for credits, license scope, and the canonical source location.

## Local preview

```powershell
python -m http.server 4182 --bind 127.0.0.1
```
