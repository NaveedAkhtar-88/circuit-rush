# Circuit Rush

A real-time multiplayer racing game that runs in the browser. Up to 8 drivers race on three tracks, grab nitro, shock rivals with EMP blasts and fight for points in a three race championship. No accounts, no installs, and no friends needed: add bots and race solo.

**Play now:** https://naveedakhtar-88.github.io/circuit-rush/

## How to play

1. Open the link and type your name.
2. Press Create a room, or enter a friend's 4 letter code and press Join. Share the invite link to skip typing the code.
3. The host can add up to 7 bots, then presses Start championship.
4. Race 3 laps on each of 3 tracks. Points per race: 10, 8, 6, 5, 4, 3, 2, 1. The most points after the last race wins.

## Controls

- Keyboard: arrows or WASD to drive, Space or Shift for nitro, E for the EMP item.
- Phone or tablet: gas is automatic. Use the LEFT and RIGHT pads to steer, BRK to brake, NITRO to boost and EMP to fire your item.

## Game features

- Drift physics with grip, off-track slowdown and crash barriers.
- Blue N orbs refill nitro. Purple ? boxes give one EMP that slows every car within range.
- Procedurally generated tracks with a minimap, live position, lap counter and race timer.
- Bots with their own racing lines, so the grid is never empty.
- Live standings and a points championship across three races.

## How it works

- One HTML file, no build step and no server of my own.
- Players connect directly to each other with WebRTC through PeerJS. The room code is the host's peer id.
- Each player simulates their own car and sends its state about 20 times a second. The host relays everyone's cars, runs the bots, keeps the race clock and awards points.
- Cars are drawn with the HTML canvas. Other players are smoothed so movement looks fluid even with network jitter.

## Tech

HTML, CSS, JavaScript, Canvas, WebRTC (PeerJS), GitHub Pages.

## Author

Naveed Akhtar. Portfolio: https://naveedakhtar-88.github.io/
