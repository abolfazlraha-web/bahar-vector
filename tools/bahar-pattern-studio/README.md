# Bahar Leather Pattern Studio — prototype

This folder contains the first independent, dependency-free prototype for the Bahar Leather pattern workflow. It is deliberately separate from VectorCraft's core app until its geometry and export behavior have been validated.

## First milestone

- Enter bag body width/height, gusset depth, seam allowance, stitch-line offset and hole spacing in millimetres.
- Preview five basic pieces: front/back panels, two side gussets and one base.
- Export an SVG with physical millimetre dimensions for inspection and import into LightBurn.
- Keep cut outlines and stitch-hole marks visually distinct.

## Important limitations

This is a geometry prototype, not yet a production-ready bag pattern or a Windows installer. It does not yet calculate curved gussets, zipper paths, fold allowances, leather stretch, or a complete stitch-hole path through matching seams. Always test exported files on paper before cutting leather. The next milestone is automated geometry tests and then integration/package planning for Windows 10/11.
