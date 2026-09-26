# Battle Island

A browser-based arcade flight game. Clear each coastal patrol by destroying every hostile plane. Pick up supply stars for points; every third star repairs one hull point.

## Controls

| Action | Keyboard | Touch |
| --- | --- | --- |
| Turn aircraft and camera | A / D or left / right arrows | Drag the joystick left / right |
| Speed up / reverse | W / S or up / down arrows | Drag the joystick up / down |
| Climb / dive | E / Q | Hold CLIMB / DIVE |
| Fire | Space | Hold FIRE |
| Pause | P or Escape | PAUSE |

You can open **HOW TO FLY** from the title, pause screen, or in-game HUD. The HUD shows altitude and compass heading. Left and right rotate the plane; the camera follows its nose. The game keeps the plane above the terrain when diving. The wing guns automatically track and fire at nearby aircraft in front of you. Holding FIRE also fires without a target. Turn around or reverse to re-engage an enemy you have flown past. Retrying starts the current mission again with the score it had at the beginning of that mission.

## Run locally

Requires Node.js 20. Run npm ci, then npm start and open http://localhost:3100. The scene uses Three.js from the jsDelivr CDN, so the browser needs internet access on its first load.

The terrain, waves, island scenery, aircraft and effects are created in JavaScript; the project does not require image assets.
