To other modders that needs specific EPOE-Forked compatibility patches.

If you are using PatchOperationFindMod for our mod, please use this configuration:

<mods>
	<li>Expanded Prosthetics and Organ Engineering - Forked</li>
	<li>Expanded Prosthetics, Implants and Augmentations</li>
	<li>EPOE-Forked: Legacy mode</li>
</mods>

The "Expanded Prosthetics, Implants and Augmentations" is our backup rename of our mod if we are forced to rename.
Having it done ahead of time means you don't need to worry about it later on.

With this setup, if it finds either of these mods in your mod list, the operation will proceed as normal.

Due to our Forked version having way more stuff, and different abstracts, the patches should be different from original.
Our layout of the xml files is mirroring how vanilla's core is arranged.
This means everything related to each prosthesis piece is located in the HediffsDefs file.

EPOE-Forked: Legacy mode runs almost the exact same copy of the mod, except for the material costs and some crafting recipes.
As long as what you patch does not affect the crafting costs, or a specific recipe unique to the legacy mode, it should yield the same results.