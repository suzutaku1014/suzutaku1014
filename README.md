# Takumi Suzuki

I build real-time visual systems from physical and perceptual models.

`Computer Vision` `PyTorch` `OpenGL / GLSL` `WebGL` `TypeScript`

My current focus is the boundary between computation and visual experience:
turning depth, motion, light, and atmosphere into interactive systems that can
be observed, measured, and refined.

## Featured work

### [ombrelle-live](https://github.com/suzutaku1014/ombrelle-live)

Real-time painterly rendering driven by monocular depth and optical flow.

[![ombrelle-live demo](https://raw.githubusercontent.com/suzutaku1014/ombrelle-live/main/docs/images/demo.gif)](https://github.com/suzutaku1014/ombrelle-live)

- OpenCV capture and motion estimation → PyTorch/MPS depth inference → OpenGL/GLSL rendering
- A distilled depth model reduced parameters by 25.6x and improved application rendering from 52.9 to 134.6 fps on the measured setup
- Includes paired input/output recording, temporal-stability measurement, synthetic fixtures, and documented failed hypotheses

### [sky-ocean-renderer](https://github.com/suzutaku1014/sky-ocean-renderer)

A real-time WebGL ray tracer for atmospheric scattering, volumetric clouds,
and Fresnel ocean reflection. The sky is computed by numerically integrating
light along each view ray.

**[Open the live demo →](https://suzutaku1014.github.io/sky-ocean-renderer/)**

## Software engineering

- **[reslot](https://github.com/suzutaku1014/reslot)** — a production-minded appointment rescheduling reference app with transactional workflows, outbox delivery, tests, and public operations controls
- **[Auditloom](https://github.com/suzutaku1014/auditloom)** — an evidence-based repository quality auditing CLI, designed around untrusted input, reproducible findings, and explicit verification boundaries

## What I care about

- Real-time computer vision and graphics
- Interactive systems grounded in measurable behavior
- Translating physical or perceptual ideas into working prototypes
- Architecture, testing, and documentation that make experiments reproducible
