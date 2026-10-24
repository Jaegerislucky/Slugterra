SLUGTERRA BLASTER — ROBLOX IMPORT + CHAMBER DISPLAY

This uses the gun mesh supplied in slugterra-blaster-gun.zip.
The prepared model has a transparent cyan chamber, separate material surfaces,
a stable baked pose, under-12,000-triangle individual meshes, and fitting markers.
No external texture files are required by the supplied asset.

INSTALL (ONCE, IN ROBLOX STUDIO)
1. Stop Play and save a backup of your place.
2. Extract this ZIP on your Windows computer.
3. Studio: File > Import (Ctrl+M). Choose SlugterraBlaster.fbx.
   Import the entire model, including GripAnchor, MuzzleAnchor, ChamberAnchor
   and ChamberGlass. Keep all mesh items. Let Studio finish importing/registering
   the meshes under your account/experience.
   SlugterraBlaster.glb is supplied as an alternate format.
4. In Explorer, select the imported TOP Model (not one individual MeshPart).
5. Open Install-Blaster.txt, Ctrl+A, Ctrl+C. Paste its contents into Studio's
   Command Bar, then press Enter. Look for IMPORTED BLASTER INSTALLED.
6. Press Play. Choose a capsule slot and fire/draw the gun. The selected equipped
   slug is visible inside the glass, disappears for the shot, then reloads.

The gun keeps the name Slug Pistol, so the existing capsule hotbar, muzzle FX,
recoil and launch cinematics still find it. No new UI is added. Fusion features
and shinies are supported via CreatureForms when installed; otherwise it clones
from the existing slug model library. Chamber fitting does not alter stats.

The previous Tool and imported source Model are preserved in ServerStorage under
BlasterBackup_<time>. The original uploaded ZIP is not modified.

IMPORTANT
Roblox must import/register mesh assets in Studio; a Command Bar script cannot
turn this local FBX into published mesh IDs by itself. This package prepares that
step and installs the gameplay wiring afterward. It does not publish your game.

VERIFIED OFFLINE
- FBX reload, mesh names, transforms, forward direction and triangle budgets.
- Luau compilation of installer, server service, chamber fitting and client.
- Ownership/equipped-slot validation, duplicate shot rejection, hide/reload
  scheduling, cleanup, and unchanged inventory/coins/capsules in handler tests.
- Chamber fit calculations include fins and antennae and leave a safety margin.

STILL NEEDS STUDIO PLAYTEST
Actual 3D Importer output, held-gun grip, glass rendering, asset permissions,
chamber visibility, and replication. Blaster-preview.png is a Blender render,
not a Roblox Studio screenshot.
