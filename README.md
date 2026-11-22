# Rally Rush

An original top-down off-road racing game for the browser, in the spirit of mid-90s bird's-eye racers like Race Mania and Micro Machines: bump and smash your rivals, jump the ramps, earn prize money and work your way up through the leagues.

It renders in 3D with WebGL (a hand-written renderer, no libraries) and falls back to a 2D canvas on devices without WebGL (or add `?2d` to the URL). It's a single HTML file with no build step and no dependencies.

**Play:** https://mariuspaukste.github.io/race-mania/

## Features
- **Career mode:** five leagues (Rookie Cup → Legends Cup) of four races each. Points decide the league table; finish in the top 3 to unlock the next league and win a season bonus.
- **Money and garage:** prize money for every finish plus cash pickups on the track. Buy, sell and repair cars. Damage carries over between career races.
- **10 cars** in five body styles (buggy, hatch, jeep, pickup, coupe), each with its own speed, acceleration, grip and armour.
- **20 tracks:** 10 layouts raced in both directions, across six kinds of scenery: Meadow, Desert, Snow, Swamp, Canyon and Speedway.
- **Rival driving styles:** Peaceful, Normal, Aggressive or Brutal. Rougher rivals ram you and push you off the road.
- **Damage:** crashes into cars, barriers, trees and rocks slow your car down; badly damaged cars smoke, and a wrecked car limps along.
- **Off-road surfaces:** water, mud, soft sand, ice, gravel and oil patches; each scenery has its own grip.
- **Jump ramps**, plus **pickups** on the track: `$` cash, `N` nitro (up to three charges) and `+` repairs.
- **Track editor:** tap to place points, drag to shape the road, pick the scenery and road width, then save and race your own tracks. Ramps, patches and pickups are placed automatically.
- Quick race mode with any car, track, rival style, 2/3/5 laps and ten car colours. Lap records are saved per track.

## Controls
| Action | Keyboard | Phone |
|---|---|---|
| Accelerate | ↑ / W | ▲ |
| Brake / reverse | ↓ / S | ▼ |
| Steer | ← → / A D | ◀ ▶ |
| Nitro | Shift / Enter / Ctrl | ⚡ |
| Handbrake | Space | – |
| Pause | P / Esc | II |
