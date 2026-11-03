# FeCoMn ORR structures

Selected ORR background and intermediate structures for the FeCoMn–NC / FeCo–NC / Mn–NC manuscript.

## Contents

Twelve relaxed structures: the background and OOH, O and OH reaction states for each of three model families. Files are in VASP POSCAR format. Coordinates and selective-dynamics flags are preserved from the source files; each file can also be read as a VASP CONTCAR geometry.

- FeCoMn–NC: Fe27Co32 particle with eight adsorbed oxygen atoms and an axial Mn–OH background; added intermediates occupy the opposite Mn side.
- FeCo–NC: oxygen-covered Fe27Co32 particle background with eight oxygen atoms; added intermediates bind on the particle.
- Mn–NC: Mn–N4 model with an axial oxygen background; intermediates bind on the opposite side.

The state `OH` in FeCoMn–NC therefore contains the retained axial hydroxyl plus the reaction hydroxyl; it is the final adsorbed intermediate in that ORR path.

`structure_manifest.json` identifies composition, atom count, state and SHA-256 checksum. The independent FeCo(110) coverage library and additional recovery structures are not included in this deposit. No experimental datasets, manuscript files, licensed PAW potentials or charge/wavefunction files are included.
