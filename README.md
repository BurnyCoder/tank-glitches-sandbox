# Flying Tank Glitch Sandbox

A Three.js browser game featuring a tank with bunnyhopping mechanics and flying glitch zones.

<img width="2554" height="1180" alt="image" src="https://github.com/user-attachments/assets/bcfef900-866c-460d-af6c-880714512788" />

## Play

Open `index.html` in a browser.

## Controls

- **WASD** - Move tank
- **SPACE** - Jump (hold for auto-bhop)
- **R** - Reset position

## Features

- **Bunnyhopping** - Hold spacebar while moving to chain jumps and gain exponential speed
- **Air Control** - Turn and strafe while airborne
- **Glitch Zones** - Drive into red zones to trigger the flying glitch and get launched
- **Infinite World** - Procedurally generated terrain with trees, rocks, and glitch zones
- **No Speed Cap** - Chain enough bhops and go as fast as you want

## Mechanics

The bunnyhopping system uses exponential speed growth. Each successful bhop multiplies your speed by 1.15x plus a base boost. The longer your chain, the faster you accelerate.
