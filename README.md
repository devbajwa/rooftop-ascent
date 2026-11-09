# Rooftop Ascent

A first-person 3D parkour game for the browser, built with Three.js. Play it at **https://hardcore-parkour.netlify.app/**

Built by Waqas Bajwa with AI-assisted development. I designed the game, played and tested every build myself, and had the AI fix the issues I found, such as character movement, gameplay and performance.

You play Tabali, a free-runner crossing three districts: The Industrial District, Neon Skyline and Storm Peak. The rule is to keep moving.

## Controls

| Action | Keyboard and mouse | Touch |
|---|---|---|
| Run (speeds up into a sprint) | W A S D or arrow keys | Joystick on the left |
| Look around | Mouse (click the game first) | Drag on the right |
| Jump, vault, wall-jump | Space | JUMP |
| Slide, or roll on a big landing | Shift or C | SLIDE |
| Pause | Esc or P | |

## Moves

- **Vault**: jump near a low obstacle.
- **Wall-jump**: jump while on a wall.
- **Wall-run**: jump at a glass wall at an angle while running fast.
- **Roll**: hold slide just before landing a big drop to keep your speed.
- **Combo**: chain moves within 3 seconds to raise your score multiplier.

## Tech

- Three.js 0.160 loaded as ES modules from jsDelivr through an import map, with bloom post-processing.
- Pointer lock for mouse look, and a virtual joystick for touch screens.
- Sound made with the Web Audio API. Settings and progress are saved in the browser.
- Everything else is in `index.html`. There is nothing to build.
