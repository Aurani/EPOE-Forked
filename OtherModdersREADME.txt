To other modders that needs specific EPOE compatibility patches.

If you are using PatchOperationFindMod to include the forked version, you can have it in this configuration:

<mods>
	<li>Expanded Prosthetics and Organ Engineering</li>
	<li>Expanded Prosthetics and Organ Engineering - Forked</li>
	<li>Expanded Prosthetics, Implants and Augmentations</li>
</mods>

With this setup, if it finds any of these mods in your mod list, the operation will then proceed to the next stage.
Do check if patching for forked version defs, as original will not have it and can break the sequence if original is used and detected.
In the event of that, make a seperate PatchOperationFindMod and omit the <li>Expanded Prosthetics and Organ Engineering</li>.

The "Expanded Prosthetics, Implants and Augmentations" is our backup rename of our mod if we are forced to rename.
Having it done ahead of time means you don't need to worry about it later on.


Our Forked version have way more stuff, and the layout of the xml files is mirroring how vanilla's core is arranged.
This means everything related to each prosthesis piece is located in the HediffsDefs file.