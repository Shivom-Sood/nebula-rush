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
| Start / resume | Enter or Space | Tap |

Boosting makes your ship twice as fast and the whole world more than twice as fast, and doubles your survival points.

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
- You earn survival points over time, double while boosting.
- Every 500 points the level goes up and asteroids fall faster and more often.
- You start with 3 lives, and your best score is saved in the browser.

## Screen sizes

The play area fills the window. On phones and narrow windows it stays portrait (2:3); on laptops and wide monitors it widens up to 16:9, with more asteroids spawning so the difficulty stays about the same. Scores from very different screen shapes may not compare exactly.

## How to run locally

It's a single file with no dependencies. Clone the repo and open `index.html` in a browser.
