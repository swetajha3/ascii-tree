Christmas Tree in Characters

An animated Christmas tree drawn entirely from text characters, with hand-gesture control, pixel-art letters, an advent calendar and a shared letter wall. It is a single file (index.html) with no build step.

Live site: https://swetajha3.github.io/ascii-tree/

What it does
The film: a 12-second animated tree. A light drops, a golden stage spreads out, the tree grows under a rainbow ring, a star opens, two comets spiral down and switch on the lights, gifts pop up and a reindeer runs. Everything on screen is a text character, with synthesized sound.
Hand control: press Hand control and use your webcam to build the tree yourself (see below).
Customise: change the tree colour, lights, frost and gift colours, and add pixel-art cards for friends.
Letter wall: public letters that everyone can read. The latest also show as clickable envelopes above the tree.
Advent calendar, card maker, wish list, Secret Santa, bells and a small game.
Countdown to 25 December, music, and a reduce-motion setting.
Hand gestures

Press Hand control, allow the camera, and wait for "Hand tracking is ready".

Gesture	What happens
Open palm (hold)	Starts the show
Spin your index finger in circles	Grows the tree
Sprinkle (pinch fingertips, then open)	Snow falls and frost settles
Sprinkle again	Lights and decorations switch on
Open both hands	Gifts appear
Heart with both hands	The reindeer appears

Only your hands are tracked. If tracking can't load, use the Next step button or drag on the screen.

Run it

Open index.html in a modern browser (Chrome or Edge work best). To publish, use GitHub Pages: Settings, Pages, Deploy from a branch, main, / (root).

The camera needs a secure page (HTTPS or localhost). GitHub Pages provides HTTPS.

Set up the shared letter wall

Without this step, letters are saved on one device only.



Anyone can add a letter but not edit or delete one. Delete unwanted letters from the Firebase console's Data tab. Letters are public, so don't post private details.

Notes
Fonts load from Google Fonts. Hand tracking loads Google's MediaPipe model from a CDN. Both need an internet connection; the tree itself works offline.
Customisations, cards and the wish list are saved in your own browser. Use Copy my tree link or Copy share code to pass your setup to friends.
Keys: H hides the on-screen buttons while recording, Space pauses, R replays.

Built with: HTML, CSS, JavaScript, Canvas/Web APIs, MediaPipe, Firebase Realtime Database.

License

All rights reserved.
 

