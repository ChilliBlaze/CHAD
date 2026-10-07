SPHERICAL BATTLEFIELD — MULTIPLAYER

Run locally:
  node server.js
Then open http://localhost:8080

Controls:
  WASD       move
  Mouse      look (pointer lock)
  Left click attack / shoot
  Right click aim
  E          weapon wheel
  F          first/third person
  G          emote wheel
  Space      jump
  Q          crouch
  Shift      sprint
  Esc        release pointer lock

Multiplayer additions:
- Health, names and kill-streak leaderboard sync through the server.
- Rifle, minigun, sniper, knife, bat and lightsaber damage other players.
- Grenade and air strike splash damage can also hurt the caller.
- Emotes sync so other players can see them.

Performance changes:
- High-performance WebGL preference.
- Render pixel ratio capped at 1.35.
- Shadows disabled and expensive world geometry/lights reduced.

Render hosting:
Keep server.js and game.html in the same repository. Render start command: node server.js

MOVEMENT CATEGORY
-----------------
Open the weapon wheel with E and choose Movement. Movement equipment is secondary and does not replace your normal weapon.
- Grapple Hook: press R to attach/release. It can latch onto the spherical ground, tree trunks, fence posts and torches.
- Dash: press R for a fast burst; the equipped item is a glowing green baton.
- Jump Boots: Space becomes a super jump; a glowing upward-arrow device is visible in first person.
- Teleport Beacon: press R to throw the white beacon. After it lands, your next left-click attack teleports you to it instead of attacking.
