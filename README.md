# Nebula Rush

A browser space shooter: dodge and blast falling asteroids, grab power-ups, and chase a high score.

### ▶ [Play it](https://shivom-sood.github.io/nebula-rush/)

## Controls

| Action | Keyboard | Touch |
| --- | --- | --- |
| Move | Arrow keys / WASD | Drag to fly |
| Shoot | Space | Auto-fires while touching |
| Boost | Hold Shift | — |
| Pause | P | — |
| Mute / unmute | M | — |
| Start / resume | Enter or Space | Tap |

Boosting makes your ship twice as fast and the whole world more than twice as fast, and doubles your survival points.

## Enemies

- **Drones** show up from level 2. They swoop in, weave side to side firing aimed shots at you, then dive away after about 10 seconds. Ramming one costs a life.
- **A boss** arrives every 5 levels, with a health bar at the top of the screen. It cycles through a spread of shots, an aimed burst and a spinning ring, and each boss is tougher than the last. Fewer asteroids fall during the fight, and beating it is worth 1,000 points per boss plus two power-ups.

Enemy shots are blocked by the shield, and a bomb clears them along with every drone on screen and takes a chunk off the boss.

## Power-ups

Power-ups float down every 10–15 seconds and sometimes drop from destroyed asteroids. Fly close and they get pulled toward your ship.

- **Triple Shot:** two extra guns fire angled shots alongside your main gun (~10s)
- **Rapid Fire:** much faster fire rate (~10s)
- **Laser:** hold fire for a continuous beam that burns through every asteroid in its path (~10s)
- **Shield:** absorbs one hit
- **Bomb:** destroys every asteroid on screen
- **Extra Life:** one more life (max 5)

## Scoring

- Destroying an asteroid earns points; smaller ones are worth more. Big ones take up to three hits.
- Drones are worth 120 points and drop power-ups more often than asteroids.
- You earn survival points over time, double while boosting.
- Every 500 points the level goes up and asteroids fall faster and more often.
- You start with 3 lives, and your best score is saved in the browser.

## Screen sizes

The play area fills the window. On phones and narrow windows it stays portrait (2:3); on laptops and wide monitors it widens up to 16:9, with more asteroids spawning so the difficulty stays about the same. Scores from very different screen shapes may not compare exactly.

## How to run locally

It's a single file with no dependencies. Clone the repo and open `index.html` in a browser.
