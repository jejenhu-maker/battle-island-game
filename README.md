# Battle Island

A browser-based arcade flight game. Clear each coastal patrol by destroying every hostile plane. Pick up supply stars for points; every third star repairs one hull point.

## Controls

| Action | Keyboard | Touch |
| --- | --- | --- |
| Steer | A / D or left / right arrows | Drag the joystick left / right |
| Speed up / reverse | W / S or up / down arrows | Drag the joystick up / down |
| Change altitude | E / Q | The aircraft maintains a safe height automatically |
| Fire | Space | Hold FIRE |
| Pause | P or Escape | PAUSE |

The wing guns automatically track and fire at nearby aircraft ahead. Holding FIRE also fires without a target. Move back to re-engage an enemy you have flown past. Retrying starts the current mission again with the score it had at the beginning of that mission.

## Run locally

Requires Node.js 20. Run npm ci, then npm start and open http://localhost:3100. The scene uses Three.js from the jsDelivr CDN, so the browser needs internet access on its first load.

The terrain, waves, island scenery, aircraft and effects are created in JavaScript; the project does not require image assets.
