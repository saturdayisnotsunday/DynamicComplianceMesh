# Dynamic Compliance Mesh (DCM)

A concept for impact-resistant vehicle structures: a hollow triangulated space frame, using the zero-mobility (rigid) property of triangles, with selected sides made compliant (springs and/or fluid-filled cells) so they can absorb energy while the structure stays stiff up to a set load. Circles with radial triangles are used where loads need to be spread, such as the roof.

**Status:** early-stage theory. No simulation or physical testing has been done yet. Not for safety-critical use.

## Concept Visualisation

An interactive breakdown of the DCM structure: a cutaway body view, four styling variants on the same mesh, and the cell behaviour at rest vs. under impact.

GitHub strips scripts from Markdown and raw HTML previews, so the file won't render inline on this page. Scroll to the bottom and click **Open visualization**.

## 3D Model

`DCM7_design1_truss_v2.obj` is a hollow strut-frame model of DCM7, Design 1, built from the hand sketches (proportions estimated; units in metres). Open it in Blender or any 3D viewer.

## Original Sketches

Handwritten pages documenting the development of the Dynamic Compliance Mesh.

**Page 1**



![Page 1](pg1.png)



**Page 2**



![Page 2](pg2.png)



**Page 3**



![Page 3](pg3.png)


## Known Issues and Open Questions

- **Cost:** the concept looks inefficient for cheap cars, which works against the goal of accessibility. It may suit bunker-type structures (e.g. domes) better. This needs testing before any conclusion.
- **Shear-thickening fluid (STF):** if the impact does not act on the fluid directly, and the base structure is not strong enough, the fluid may only add weight while the soft section behind still takes the impact. Testing is needed.
- **Gas fill:** SF6 cannot be used because of its global-warming impact. An alternative gas is needed, or the gas should be dropped.
- **Early renders:** the first concept images were generated with ChatGPT and are illustrative only.

## Planned Work

- A probability model of survival under sudden-jerk crashes (DCM space frame vs. standard chassis).
- Finite-element simulation of a single spring-triangle cell.
- Physical prototypes and impact tests.

## License

All rights reserved. See [LICENSE](LICENSE).
