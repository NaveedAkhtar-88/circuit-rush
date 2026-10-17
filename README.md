# Circuit Rush

Real-time multiplayer highway racing for up to 8 players, built by Naveed Akhtar.

Play: https://naveedakhtar-88.github.io/circuit-rush/

## How it works
- One player creates a room and shares the 4 letter code. Friends join from any browser. No accounts, no installs.
- Add bots to fill the grid. A championship is 3 races on 3 highways. Points: 10, 8, 6, 5, 4, 3, 2, 1.
- Race forward up a straight road, dodge traffic and trucks, grab blue N orbs for nitro and purple ? boxes for an EMP that slows nearby cars. Oil patches make you slide.

## Controls
- Keyboard: Left and Right (or A and D) steer, Up (W) gas, Down (S) brake, Space or Shift nitro, E EMP.
- Phone: LEFT and RIGHT pads on the bottom left, GAS, BRAKE, NITRO and EMP buttons on the right.

## Tech
Single HTML file, canvas rendering, PeerJS (WebRTC) peer to peer networking. The host runs the championship and bots, each player simulates their own car.
