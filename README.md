# Atomic Blender PDB/XYZ Add-on

This add-on was part of
[Blender 4.1 bundled add-ons](https://docs.blender.org/manual/en/4.1/addons/)
and is now available as an extension on the
[Extensions platform](https://extensions.blender.org/add-ons/atomic-blender-pdb-xyz).

The Atomic Blender (PDB/XYZ) add-on imports atomic structures
(molecules, crystals, clusters, particles, surfaces, etc.), which are
described in PDB (``.pdb``) and XYZ files (``.xyz``) (Section [Import
PDB/XYZ](#import-pdbxyz)). The add-on reads the coordinates of all
atoms in the PDB/XYZ file and represents the atoms as balls in the
Blender world. Also the sticks, which are described in PDB files only,
are shown if the sticks are *explicitly* listed in the PDB file. For more
information see the [Wiki page](https://projects.blender.org/extensions/io_mesh_atomic/wiki).

> **Note**
>
> **Speed advantage**
>
> Thanks to the Blender specific method called 
> [instancing vertices structure](https://docs.blender.org/manual/en/latest/scene_layout/object/properties/instancing/verts.html),
> which is used to build an atomic structure, the speed of the loading
> and the general handling of an atomic structure inside the Blender 3D View
> is quite fast. Atomic structures with 1000 atoms and much more
> can be easily handled.

---

This add-on is offered as it is and maintaned by the community.
