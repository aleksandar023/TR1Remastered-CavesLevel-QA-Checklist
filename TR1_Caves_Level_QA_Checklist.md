
# TR1 Remastered - Caves Level QA Checklist

> **Note**: This is a fan-made checklist created for portfolio purposes and is not affiliated with the official developers.

---

|Basic Level Functionality                                                                      | Status         |                |       |
| ------------------------------------------------------------------------------------------------ | -------------- | -------------- | ----- |
| **FMV and level start**                                                                              |                |                |       |
|🟥 High priority                                                                                    |                |                |       |
| FMV loads properly before the level                                                              |                |                |       |
| FMV is skippable (if applicable)                                                                 |                |                |       |
| Level loads correctly                                                                            |                |                |       |
| Lara faces the correct direction at level start                                                  |                |                |       |
| Esc key opens the main menu                                                                      |                |                |       |
| Inventory and weapons menus display correct items                                                |                |                |       |
| 🟨Medium priority                                                                                  |                |                |       |
| Audio syncs with video in FMV                                                                    |                |                |       |
| FMV plays without issues (no frame drops or stuttering)                                          |                |                |       |
| **Load / Save / Exit**                                                                               |                |                |       |
| High priority                                                                                    |                |                |       |
| Game can be saved                                                                                |                |                |       |
| \- *via Options > Game menu*                                                                     |                |                |       |
| \- *via shortcut (F5)*                                                                           |                |                |       |
| Game can be saved in an empty slot                                                               |                |                |       |
| Game can overwrite previous save                                                                 |                |                |       |
| Save file name corresponds to the level name                                                     |                |                |       |
| Game can be loaded                                                                               |                |                |       |
| \- *via Options > Game menu*                                                                       |                |                |       |
| \- *via shortcut (F9)*                                                                           |                |                |       |
| Loaded game resumes exact state                                                                  |                |                |       |
| \- *Lara’s position*                                                                               |                |                |       |
| \- *Health*                                                                                        |                |                |       |
| \- *Inventory items*                                                                               |                |                |       |
| \- *Enemy state*                                                                                   |                |                |       |
| "Exit to title" works from the Options > Game menu                                               |                |                |       |
| **Level Completion**                                                                                 |                |                |       |
| High priority                                                                                    |                |                |       |
| Level is completable by reaching the exit trigger                                                |                |                |       |
| Stats screen displays correctly:                                                                 |                |                |       |
| \- *Level name*                                                                                    |                |                |       |
| \- *Time taken*                                                                                    |                |                |       |
| \- *Secrets found*                                                                                 |                |                |       |
| \- *Pickups*                                                                                       |                |                |       |
| \- *Kills*                                                                                         |                |                |       |
| \- *Ammo used / hits*                                                                              |                |                |       |
| \- *Medipacks used*                                                                                |                |                |       |
| \- *Distance travelled*                                                                            |                |                |       |
| Pressing Enter key loads next level                                                              |                |                |       |
| Static Level Geometry                                                                            |                |                |       |
| General Geometry                                                                                 |                |                |       |
| High priority                                                                                    |                |                |       |
| Level layout matches the intended design                                                         |                |                |       |
| No missing/misplaced geometry                                                                    |                |                |       |
| Geometry align properly (no gaps/overlaps)                                                       |                |                |       |
| Collision & Interaction                                                                          |                |                |       |
| High priority                                                                                    |                |                |       |
| Geometry has correct collision (no walk-through/invisible walls)                                 |                |                |       |
| Intended ledges are reachable                                                                    |                |                |       |
| Textures                                                                                         |                |                |       |
| High priority                                                                                    |                |                |       |
| Textures are applied to surfaces as intended by design                                           |                |                |       |
| Textures are mapped properly across the surface (no stretching or misalignment)                  |                |                |       |
| Textures are at the correct resolution (no blurry or pixelated textures)                         |                |                |       |
| Medium priority                                                                                  |                |                |       |
| Seams are not visible between adjacent textures                                                  |                |                |       |
| No visual artifacts are present (z fighting, etc)                                                |                |                |       |
| Props (Non-Interactable objects)                                                                 |                |                |       |
| High priority                                                                                    |                |                |       |
| Props are placed as intended                                                                     |                |                |       |
| Props are placed correctly on the surface (no floating/clipping/sinking)                         |                |                |       |
| Medium priority                                                                                  |                |                |       |
| Prop models are displayed correctly                                                              |                |                |       |
| Prop model has correct collision (if applicable)                                                 |                |                |       |
| Props models are textured properly                                                               |                |                |       |
| Lighting                                                                                         |                |                |       |
| High priority                                                                                    |                |                |       |
| Light sources are placed as designed                                                             |                |                |       |
| Correct light intensity (not too dark/bright)                                                    |                |                |       |
| Shadows appear properly relative to light source                                                 |                |                |       |
| Shadow intensity is as intended                                                                  |                |                |       |
| Medium priority                                                                                  |                |                |       |
| No visible light glitches (e.g., flickering or popping)                                          |                |                |       |
| Pickups/interactable objects in dark areas are visible                                           |                |                |       |
| Lara's model is consistently lit across light zones                                              |                |                |       |
| Skybox                                                                                           |                |                |       |
| High priority                                                                                    |                |                |       |
| Skybox is displayed correctly                                                                    |                |                |       |
| Medium priority                                                                                  |                |                |       |
| Skybox is mapped properly (no stretching or distortion)                                          |                |                |       |
| Skybox resolution is appropriate (not pixelated or blurry)                                       |                |                |       |
| Skybox has no visual artifacts (seams, flickering, etc.)                                         |                |                |       |
| Visual Effects (VFX)                                                                             |                |                |       |
| High priority                                                                                    |                |                |       |
| Ray lights are placed as intended                                                                |                |                |       |
| Ray light direction and beam shape match the intended design                                     |                |                |       |
| Snow particles spawn at the correct location and height                                          |                |                |       |
| Medium priority                                                                                  |                |                |       |
| Ray light intensity is appropriate (not too bright or faint)                                     |                |                |       |
| Ray light does not clip through geometry or create visual glitches                               |                |                |       |
| Snow particle textures are displayed correctly                                                   |                |                |       |
| Snow particles move at the predefined speed                                                      |                |                |       |
| Camera                                                                                           |                |                |       |
| High priority                                                                                    |                |                |       |
| Camera remains consistently positioned behind Lara during free movement                          |                |                |       |
| Camera pans to key points when triggered                                                         |                |                |       |
| Camera panning is one-time only (trigger deactivates after use)                                  |                |                |       |
| Ambient music                                                                                    |                |                |       |
| High priority                                                                                    |                |                |       |
| Ambient music plays properly throughout the entire level                                         |                |                |       |
| Ambient music doesn’t overlap with other triggered SFX (secret chimes or encounter music)        |                |                |       |
| Ambient music resumes correctly after other triggered SFX finish playing                         |                |                |       |
| Pickup Items                                                                                     | Small Medipack | Large Medipack |       |
| High priority                                                                                    |                |                |       |
| Item(s) have a correct placement in the level (X amount)                                         |                |                |       |
| Item can be picked up by pressing Ctrl key                                                       |                |                |       |
| Item is displayed in the lower-right corner of the screen when collected                         |                |                |       |
| Item is added to inventory correctly                                                             |                |                |       |
| Medium priority                                                                                  |                |                |       |
| Item model is displayed properly                                                                 |                |                |       |
| Item model uses an appropriate texture                                                           |                |                |       |
| Item model texture is displayed without visual artifacts (visible seams, UV mapping issues, etc) |                |                |       |
| Hand icon appears when an item is in range for pickup                                            |                |                |       |
| Secret areas                                                                                     |                |                |       |
| High priority                                                                                    |                |                |       |
| All secret areas are reachable                                                                   |                |                |       |
| Secrets include proper pickups                                                                   |                |                |       |
| Medium priority                                                                                  |                |                |       |
| Secret count updates on HUD/stat screen                                                          |                |                |       |
| Secret chime SFX plays when entering secret area                                                 |                |                |       |
| Secret chime SFX only plays once per secret                                                      |                |                |       |
| Secret chime SFX doesn’t overlap with other sounds in the level                                  |                |                |       |
| Enemies                                                                                          | Bats           | Wolves         | Bears |
| Setup validation (Pre-trigger)                                                                   |                |                |       |
| High priority                                                                                    |                |                |       |
| Enemy placements are correct in the level                                                        |                |                |       |
| Enemy is initially inactive before being triggered                                               |                |                |       |
| Medium priority                                                                                  |                |                |       |
| Enemy model is displayed properly                                                                |                |                |       |
| Enemy has a proper hitbox                                                                        |                |                |       |
| Enemy model has a correct texture                                                                |                |                |       |
| Enemy model texture has no visual artifacts (visible seams, UV mapping issues, etc)              |                |                |       |
| Enemy trigger logic                                                                              |                |                |       |
| High priority                                                                                    |                |                |       |
| Trigger placed at the correct location                                                           |                |                |       |
| Enemy activates by a correct trigger (one or more enemies)                                       |                |                |       |
| Trigger activates only once                                                                      |                |                |       |
| Medium priority                                                                                  |                |                |       |
| Activation trigger does not overlap unrelated actions                                            |                |                |       |
| Enemy trigger SFX plays correctly (if any)                                                       |                |                |       |
| Enemy paths towards Lara                                                                         |                |                |       |
| Movement animation plays properly                                                                |                |                |       |
| Movement SFX plays properly                                                                      |                |                |       |
| No model stretching/distortion during animation                                                  |                |                |       |
| Enemy navigates terrain properly (no clipping with the environement)                             |                |                |       |
| Enemy follow Lara through doors                                                                  |                |                |       |
| Combat                                                                                           |                |                |       |
| High priority                                                                                    |                |                |       |
| Enemies attack Lara                                                                              |                |                |       |
| Correct amount of damage is dealt to Lara's health upon attack/collision                         |                |                |       |
| Lara automatically targets the closest enemy                                                     |                |                |       |
| Lara's health bar updates in real-time (damage/healing)                                          |                |                |       |
| Lara dies when health depletes fully                                                             |                |                |       |
| Medium priority                                                                                  |                |                |       |
| Enemy Attack animation is synced with damage output                                              |                |                |       |
| Attack SFX plays properly                                                                        |                |                |       |
| Enemy health and death                                                                           |                |                |       |
| High priority                                                                                    |                |                |       |
| Enemy have a correct amount of health                                                            |                |                |       |
| Lara deals an appropriate amount of damage to enemy                                              |                |                |       |
| Enemy dies when health is depleted                                                               |                |                |       |
| Medium priority                                                                                  |                |                |       |
| Death animation plays properly                                                                   |                |                |       |
| Death SFX plays properly                                                                         |                |                |       |
| Enemy model stays collapsed after death                                                          |                |                |       |
| Enemy loses collision box after death                                                            |                |                |       |
| Switches and corresponding doors                                                                 |                |                |       |
| High priority                                                                                    |                |                |       |
| Player can interact with the switch by pressing Ctrl key                                         |                |                |       |
| Switch opens the correct door                                                                    |                |                |       |
| Camera frames door (if applicable)                                                               |                |                |       |
| Door stays opened for correct duration (if timed)                                                |                |                |       |
| Switch can be reset (if applicable)                                                              |                |                |       |
| \- Resetting closes door                                                                         |                |                |       |
| Medium priority                                                                                  |                |                |       |
| Switch model is displayed properly                                                               |                |                |       |
| Switch model has a proper collision box                                                          |                |                |       |
| Switch model has a correct texture                                                               |                |                |       |
| Switch texture has no visual artifacts (visible seams, UV mapping issues, etc)                   |                |                |       |
| Switch animation plays properly                                                                  |                |                |       |
| Interacting with the switch triggers a proper SFX                                                |                |                |       |
| Switch animations and SFX sync correctly                                                         |                |                |       |
| Hand icon appears when Lara is within interaction range of the switch                            |                |                |       |
| Door model is displayed correctly                                                                |                |                |       |
| Door model has a proper collision box                                                            |                |                |       |
| Door model has a correct texture                                                                 |                |                |       |
| Door texture has no visual artifacts (visible seams, UV mapping issues, etc)                     |                |                |       |
| Door opens up with a proper SFX                                                                  |                |                |       |
| Door animation and SFX sync correctly                                                            |                |                |       |
| Pressure Plates and corresponding doors                                                          |                |                |       |
| High priority                                                                                    |                |                |       |
| Door opens when stepping on plate                                                                |                |                |       |
| Door remains open while on plate                                                                 |                |                |       |
| Door closes after X seconds when stepping outside of the plate                                   |                |                |       |
| Plate reactivates correctly                                                                      |                |                |       |
| Medium priority                                                                                  |                |                |       |
| Pressure plate model is displayed properly                                                       |                |                |       |
| Pressure plate model has a proper collision box                                                  |                |                |       |
| Pressure plate has a correct texture                                                             |                |                |       |
| Pressure plate texture has no visual artifacts (visible seams, UV mapping issues, etc)           |                |                |       |
| Pressure plate has a proper animation                                                            |                |                |       |
| Pressure plate has a proper SFX                                                                  |                |                |       |
| Pressure plate animations and SFX sync correctly                                                 |                |                |       |
| Door model is displayed correctly                                                                |                |                |       |
| Door model has a proper collision box                                                            |                |                |       |
| Door has a correct texture                                                                       |                |                |       |
| Door texture has no visual artifacts (visible seams, UV mapping issues, etc)                     |                |                |       |
| Door opens up with a proper SFX                                                                  |                |                |       |
| Door animation and SFX sync correctly                                                            |                |                |       |
| Dart trap                                                                                        |                |                |       |
| High priority                                                                                    |                |                |       |
| Darts activate on trigger                                                                        |                |                |       |
| Dart deal appropriate amount of damage on contact                                                |                |                |       |
| Dart deactivate when Lara moves out of range                                                     |                |                |       |
| Darts traverse at a correct speed                                                                |                |                |       |
| Medium priority                                                                                  |                |                |       |
| Dart model is displayed properly                                                                 |                |                |       |
| Dart model has a correct texture                                                                 |                |                |       |
| Dart model has a correct collision box                                                           |                |                |       |
| Blood VFX on hit is displayed upon taking damage from darts                                      |                |                |       |
| Smoke VFX appears at dart origin                                                                 |                |                |       |
| Proper SFX appears when firing darts                                                             |                |                |       |
| Spark VFX appears on wall impact                                                                 |                |                |       |
| Achievemenets                                                                                    |                |                |       |
| High priority                                                                                    |                |                |       |
| Correct achievement(s) trigger at appropriate moments                                            |                |                |       |
| Achievements trigger only once per event                                                         |                |                |       |
| Medium priority                                                                                  |                |                |       |
| Achievement icon displays correctly without graphical issues                                     |                |                |       |
| Achievement text appears as intended without typos                                               |                |                |       |
| Performance                                                                                      |                |                |       |
| High priority                                                                                    |                |                |       |
| Level loads within acceptable time                                                               |                |                |       |
| FPS is stable throughout level                                                                   |                |                |       |
| No visible pop-in of textures or models                                                          |                |                |       |
| Memory usage remains stable during gameplay                                                      |                |                |       |
