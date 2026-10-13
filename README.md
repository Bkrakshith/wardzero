# WardZero

**The Simulated Hospital Where Robots Train Before They Meet Patients**

Project page: https://bkrakshith.github.io/wardzero/

WardZero is an open platform to build and test robot solutions for hospitals. It gives a complete simulated
hospital with a surgical wing, two simulators (Isaac Sim and MuJoCo), a safety layer and navigation. The
reference robot is a Unitree G1 humanoid with BrainCo Revo2 hands.

This repository contains only the static project page. The code is in
[hospital-sim](https://github.com/Bkrakshith/hospital-sim) and its component repositories.

## Status

WardZero is in development. All tests used simulation only. No tests on a real robot and no tests of the
transfer from simulation to a real robot (sim-to-real) are complete. Refer to the disclaimer on the page.

## Contents

| Path | Contents |
|---|---|
| `index.html` | The project page |
| `static/css/` | Page style |
| `static/images/` | Architecture diagram, training curve, plan of the surgical wing |
| `static/videos/` | Feature clips (H.264) and their poster images |

## Preview on a local computer

```bash
python3 -m http.server 8000      # then open http://localhost:8000
```

## Licence

The page text and code have the Apache License 2.0. The videos and images show third-party assets with their
own licences. Refer to `NOTICE`.

Built by: Rakshith Bangalore Kumaraswamy

## Versions

- Version 2.0 (this page): the hospital is closer to UK hospital guidance. It adds fire doors, bed lifts, a ward with en-suite rooms and a small A&E.
- Version 1.0: the original page, kept at `v1/` and in the tag `v1.0`.
