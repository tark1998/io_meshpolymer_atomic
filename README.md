# Atomic Blender PDB/XYZ Add-on

This add-on was part of [Blender 4.1 bundled add-ons](https://docs.blender.org/manual/en/4.1/addons/) and is now available as an extension on the [Extensions platform](https://extensions.blender.org/add-ons/atomic-blender-pdb-xyz).

The Atomic Blender (PDB/XYZ) add-on imports atomic structures
(molecules, crystals, clusters, particles, surfaces, etc.), which are
described in PDB (``.pdb``) and XYZ files (``.xyz``) (Section [Import
PDB/XYZ](#import-pdbxyz)). The add-on reads the coordinates of all
atoms in the PDB/XYZ file and represents the atoms as balls in the
Blender world. Also the sticks, which are described in PDB files only,
are shown if the sticks are *explicitly* listed in the PDB file.

To build a new version of the extension:
* `<path_to_blender> -c extension build --source-dir=./source`

For more information about building extensions refer to the [documentation](https://docs.blender.org/manual/en/dev/extensions/getting_started.html).

---

This add-on is offered as it is and maintaned by the community, no support expected.
