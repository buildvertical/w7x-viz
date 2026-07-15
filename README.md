# W7-X plasma boundary, colored by |B|

**Live viewer: https://buildvertical.github.io/w7x-viz/**

An interactive 3D view of the Wendelstein 7-X stellarator: the last closed
flux surface of a VMEC++ equilibrium, colored by magnetic field strength
(1.92 to 2.84 T), inside the machine's 70 superconducting coils (50
non-planar, 20 planar). Everything runs in the browser from one
self-contained page; you can also download `w7x_bmod.html` and open it
offline.

Things to try: press Play to sweep the 98 nested flux surfaces from the
magnetic axis to the boundary, enable "Single sector" and drag the angle to
cut the machine open (the cross-sections show the nested surfaces), hover
for |B| at the cursor, and press F1 for all controls.

Built from public data: the W7-X example equilibrium input and the
`coils.w7x` free-boundary coil centerlines shipped with
[VMEC++](https://github.com/proximafusion/vmecpp). Coil cross-sections are
rendered as square profiles sized to the published winding-pack design; the
planar/non-planar split is detected from the coil geometry itself.
