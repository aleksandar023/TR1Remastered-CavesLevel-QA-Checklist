
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
| Lara faces the correct direction at the level start                                                  |                |                |       |
| Esc key opens the main menu                                                                      |                |                |       |
| Inventory and weapons menus display the correct items                                                |                |                |       |
|🟨 Medium priority                                                                                  |                |                |       |
| Audio syncs with video in FMV                                                                    |                |                |       |
| FMV plays without issues (no frame drops or stuttering)                                          |                |                |       |
| **Load / Save / Exit**                                                                               |                |                |       |
|🟥 High priority                                                                                    |                |                |       |
| The game can be saved                                                                                |                |                |       |
| \- *via Options > Game menu*                                                                     |                |                |       |
| \- *via shortcut (F5)*                                                                           |                |                |       |
| The game can be saved in an empty slot                                                               |                |                |       |
| The game can overwrite previous save                                                               |                |                |       |
| The save file name corresponds to the level name                                                     |                |                |       |
| The game can be loaded                                                                               |                |                |       |
| \- *via Options > Game menu*                                                                       |                |                |       |
| \- *via shortcut (F9)*                                                                           |                |                |       |
| Loading a save resumes the game at the exact saved state                                                                  |                |                |       |
| \- *Lara’s position*                                                                               |                |                |       |
| \- *Health*                                                                                        |                |                |       |
| \- *Inventory items*                                                                               |                |                |       |
| \- *Enemy state*                                                                                   |                |                |       |
| "Exit to title" works from the Options > Game menu                                               |                |                |       |
| **Level Completion**                                                                                 |                |                |       |
|🟥 High priority                                                                                    |                |                |       |
| The level is completable by reaching the exit trigger	                                                |                |                |       |
| The stats screen is displayed correctly                                                                |                |                |       |
| \- *Level name*                                                                                    |                |                |       |
| \- *Time taken*                                                                                    |                |                |       |
| \- *Secrets found*                                                                                 |                |                |       |
| \- *Pickups*                                                                                       |                |                |       |
| \- *Kills*                                                                                         |                |                |       |
| \- *Ammo used / hits*                                                                              |                |                |       |
| \- *Medipacks used*                                                                                |                |                |       |
| \- *Distance traversed*                                                                            |                |                |       |
| Pressing the Enter key loads the next level                                                              |                |                |       |
| **Static Level Geometry**                                                                            |                |                |       |
| ***General Geometry***                                                                                 |                |                |       |
|🟥 High priority                                                                                    |                |                |       |
| The level layout matches the intended design                                                         |                |                |       |
| No missing/misplaced geometry                                                                    |                |                |       |
| Geometry align properly (no gaps/overlaps)                                                       |                |                |       |
| ***Collision & Interaction***                                                                          |                |                |       |
|🟥 High priority                                                                                    |                |                |       |
| Geometry has correct collision (no walk-through/invisible walls)                                 |                |                |       |
| Intended ledges are reachable                                                                    |                |                |       |
| ***Textures***                                                                                         |                |                |       |
|🟥 High priority                                                                                    |                |                |       |
| Textures are applied to surfaces as intended                                           |                |                |       |
| Textures are mapped properly across the surface (no stretching or misalignment)                  |                |                |       |
| Textures are at the correct resolution (no blurry or pixelated textures)                         |                |                |       |
|🟨 Medium priority                                                                                  |                |                |       |
| Seams are not visible between adjacent textures                                                  |                |                |       |
| No visual artifacts are present (z-fighting, etc)                                                |                |                |       |
| **Props (Non-Interactable objects)**                                                                 |                |                |       |
|🟥 High priority                                                                                    |                |                |       |
| Props are placed as intended                                                                     |                |                |       |
| Props are placed correctly on the surface (no floating/clipping/sinking)                         |                |                |       |
|🟨 Medium priority                                                                                  |                |                |       |
| Prop models are displayed correctly                                                              |                |                |       |
| Prop model has correct collision (if applicable)                                                 |                |                |       |
| Props models are textured properly                                                               |                |                |       |
| **Lighting**                                                                                         |                |                |       |
|🟥 High priority                                                                                    |                |                |       |
| Light sources are placed as designed                                                             |                |                |       |
| Correct light intensity (not too dark/bright)                                                    |                |                |       |
| Shadows appear properly relative to the light source                                               |                |                |       |
| Shadow intensity is as intended                                                                  |                |                |       |
|🟨 Medium priority                                                                                  |                |                |       |
| No visible light glitches (e.g., flickering or popping)                                          |                |                |       |
| Pickups/interactable objects in dark areas are visible                                           |                |                |       |
| Lara's model is consistently lit across light zones                                              |                |                |       |
| **Skybox**                                                                                           |                |                |       |
|🟥 High priority                                                                                    |                |                |       |
| Skybox is displayed correctly                                                                    |                |                |       |
|🟨 Medium priority                                                                                  |                |                |       |
| Skybox is mapped properly (no stretching or distortion)                                          |                |                |       |
| Skybox resolution is appropriate (not pixelated or blurry)                                       |                |                |       |
| Skybox has no visual artifacts (seams, flickering, etc.)                                         |                |                |       |
| **Visual Effects (VFX)**                                                                             |                |                |       |
|🟥 High priority                                                                                    |                |                |       |
| Ray lights are placed as intended                                                                |                |                |       |
| Ray light direction and beam shape match the intended design                                     |                |                |       |
| Snow particles spawn at the correct location and height                                          |                |                |       |
|🟨 Medium priority                                                                                  |                |                |       |
| Ray light intensity is appropriate (not too bright or faint)                                     |                |                |       |
| Ray light does not clip through geometry or create visual glitches                               |                |                |       |
| Snow particle textures are displayed correctly                                                   |                |                |       |
| Snow particles move at the predefined speed                                                      |                |                |       |
| **Camera**                                                                                           |                |                |       |
|🟥 High priority                                                                                    |                |                |       |
| The camera remains consistently positioned behind Lara during free movement                          |                |                |       |
| The camera pans to key points when triggered                                                         |                |                |       |
| Camera panning is one-time only (trigger deactivates after use)                                  |                |                |       |
| **Ambient music**                                                                                    |                |                |       |
|🟥 High priority                                                                                    |                |                |       |
| Ambient music plays properly throughout the entire level                                         |                |                |       |
| Ambient music doesn’t overlap with other triggered SFX (secret chimes or encounter music)        |                |                |       |
| Ambient music resumes correctly after other triggered SFX finishes playing                         |                |                |       |
| **Pickup Items**                                                                                     | Small Medipack | Large Medipack |       |
|🟥 High priority                                                                                    |                |                |       |
| Item(s) have a correct placement in the level (X amount)                                         |                |                |       |
| Item can be picked up by pressing Ctrl key                                                       |                |                |       |
| Item is displayed in the lower-right corner of the screen when collected                         |                |                |       |
| Item is added to inventory correctly                                                             |                |                |       |
|🟨 Medium priority                                                                                  |                |                |       |
| Item model is displayed properly                                                                 |                |                |       |
| Item model uses an appropriate texture                                                           |                |                |       |
| Item model texture is displayed without visual artifacts (visible seams, UV mapping issues, etc) |                |                |       |
| The hand icon appears when an item is in range for pickup                                            |                |                |       |
| **Secret areas**                                                                                     |                |                |       |
|🟥 High priority                                                                                    |                |                |       |
| All secret areas are reachable                                                                   |                |                |       |
| Secrets include proper pickups                                                                   |                |                |       |
|🟨 Medium priority                                                                                  |                |                |       |
| Secret count updates on HUD/stat screen                                                          |                |                |       |
| Secret chime SFX plays when entering the secret area                                                 |                |                |       |
| Secret chime SFX only plays once per secret                                                      |                |                |       |
| Secret chime SFX doesn’t overlap with other sounds in the level                                  |                |                |       |
| **Enemies**                                                                                          | Bats           | Wolves         | Bears |
| ***Setup validation (Pre-trigger)***                                                                   |                |                |       |
|🟥 High priority                                                                                    |                |                |       |
| Enemy placements are correct in the level                                                        |                |                |       |
| The enemy is initially inactive before being triggered                                               |                |                |       |
|🟨 Medium priority                                                                                  |                |                |       |
| The enemy model is displayed properly                                                                |                |                |       |
| The enemy has a proper hitbox                                                                        |                |                |       |
| The enemy model has the correct texture                                                                |                |                |       |
| The enemy model texture has no visual artifacts (visible seams, UV mapping issues, etc)              |                |                |       |
| ***Enemy trigger logic***                                                                              |                |                |       |
|🟥 High priority                                                                                    |                |                |       |
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
| Enemy navigates terrain properly (no clipping with the environment)                             |                |                |       |
| Enemy follows Lara through doors                                                                  |                |                |       |
| ***Combat***                                                                                           |                |                |       |
|🟥 High priority                                                                                    |                |                |       |
| Enemies attack Lara                                                                              |                |                |       |
| The correct amount of damage is dealt to Lara's health upon attack/collision                         |                |                |       |
| Lara automatically targets the closest enemy                                                     |                |                |       |
| Lara's health bar updates in real-time (damage/healing)                                          |                |                |       |
| Lara dies when health depletes fully                                                             |                |                |       |
| Medium priority                                                                                  |                |                |       |
| Enemy Attack animation is synced with damage output                                              |                |                |       |
| Attack SFX plays properly                                                                        |                |                |       |
| ***Enemy health and death***                                                                           |                |                |       |
|🟥 High priority                                                                                    |                |                |       |
| The enemy has the correct amount of health                                                            |                |                |       |
| Lara deals an appropriate amount of damage to an enemy                                              |                |                |       |
| Lara dies when her health is depleted                                                               |                |                |       |
|🟨 Medium priority                                                                                  |                |                |       |
| Death animation plays properly                                                                   |                |                |       |
| Death SFX plays properly                                                                         |                |                |       |
| Enemy model stays collapsed after death                                                          |                |                |       |
| Enemy loses collision box after death                                                            |                |                |       |
| **Switches and corresponding doors**                                                                 |                |                |       |
|🟥 High priority                                                                                    |                |                |       |
| Lara can interact with the switch by pressing Ctrl key                                         |                |                |       |
| Switch opens the correct door                                                                    |                |                |       |
| Camera frames door (if applicable)                                                               |                |                |       |
| The door stays open for the correct duration (if timed)                                                |                |                |       |
| The switch can be reset (if applicable)                                                              |                |                |       |
| \- *Resetting closes the door*                                                                         |                |                |       |
|🟨 Medium priority                                                                                  |                |                |       |
| Switch model is displayed properly                                                               |                |                |       |
| Switch model has a proper collision box                                                          |                |                |       |
| Switch model has a correct texture                                                               |                |                |       |
| Switch texture has no visual artifacts (visible seams, UV mapping issues, etc)                   |                |                |       |
| Switch animation plays properly                                                                  |                |                |       |
| Interacting with the switch triggers a proper SFX                                                |                |                |       |
| Switch animations and SFX sync correctly                                                         |                |                |       |
| The hand icon appears when Lara is within interaction range of the switch                            |                |                |       |
| The door model is displayed correctly                                                                |                |                |       |
| The door model has a proper collision box                                                            |                |                |       |
| The door model has the correct texture                                                                 |                |                |       |
| The door texture has no visual artifacts (visible seams, UV mapping issues, etc)                     |                |                |       |
| The door opens up with a proper SFX                                                                  |                |                |       |
| Door animation and SFX sync correctly                                                            |                |                |       |
| **Pressure Plates and corresponding doors**                                                          |                |                |       |
|🟥 High priority                                                                                    |                |                |       |
| The door opens when Lara steps on a plate                                                                |                |                |       |
| The door remains open while Lara is on a plate                                                                 |                |                |       |
| Door closes after X seconds when stepping outside of the plate                                   |                |                |       |
| Plate reactivates correctly                                                                      |                |                |       |
|🟨 Medium priority                                                                                  |                |                |       |
| The pressure plate model is displayed properly                                                       |                |                |       |
| The pressure plate model has a proper collision box                                                  |                |                |       |
| The pressure plate has the correct texture                                                             |                |                |       |
| The pressure plate texture has no visual artifacts (visible seams, UV mapping issues, etc)           |                |                |       |
| The pressure plate has a proper animation                                                            |                |                |       |
| The pressure plate has a proper SFX                                                                  |                |                |       |
| The pressure plate animations and SFX sync correctly                                                 |                |                |       |
| The door model is displayed correctly                                                                |                |                |       |
| The door model has a proper collision box                                                            |                |                |       |
| The door has the correct texture                                                                       |                |                |       |
| The door texture has no visual artifacts (visible seams, UV mapping issues, etc)                     |                |                |       |
| The door opens up with a proper SFX                                                                  |                |                |       |
| Door animation and SFX sync correctly                                                            |                |                |       |
| **Dart trap**                                                                                        |                |                |       |
|🟥 High priority                                                                                    |                |                |       |
| Darts activate on a trigger                                                                        |                |                |       |
| Dart deals an appropriate amount of damage on contact                                                |                |                |       |
| Dart deactivates when Lara moves out of range                                                     |                |                |       |
| Darts traverse at the correct speed                                                                |                |                |       |
|🟨 Medium priority                                                                                  |                |                |       |
| The dart model is displayed properly                                                                 |                |                |       |
| The dart model has a correct texture                                                                 |                |                |       |
| The dart model has a correct collision box                                                           |                |                |       |
| Blood VFX on hit is displayed upon taking damage from darts                                      |                |                |       |
| Smoke VFX appears at dart origin                                                                 |                |                |       |
| Proper SFX appears when firing darts                                                             |                |                |       |
| Spark VFX appears on wall impact                                                                 |                |                |       |
| **Achievements**                                                                                    |                |                |       |
|🟥 High priority                                                                                    |                |                |       |
| Correct achievement(s) trigger at appropriate moments                                            |                |                |       |
| Achievements trigger only once per event                                                         |                |                |       |
|🟨 Medium priority                                                                                  |                |                |       |
| The achievement icon displays correctly without graphical issues                                     |                |                |       |
| Achievement text appears as intended without typos                                               |                |                |       |
| **Performance**                                                                                      |                |                |       |
|🟥 High priority                                                                                    |                |                |       |
| Level loads within acceptable time                                                               |                |                |       |
| FPS is stable throughout the level                                                                   |                |                |       |
| No visible pop-in of textures or models                                                          |                |                |       |
| Memory usage remains stable during gameplay                                                      |                |                |       |
