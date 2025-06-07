# breath1

Create a JavaScript single HTML file. It reads iPhone's accelerometer data and displays it on the page. The final goal is to monitor breathing patterns by placing the phone on the stomach or the chest.

### Usage

Open `index.html` on your mobile device. On iOS (including Edge for iPhone), tap the page once to grant motion sensor access. Use the on‑screen controls to adjust the sample interval, the number of samples shown before fading and the averaging interval. After tapping, the accelerometer values will appear on screen along with a 2D fading trail reflecting your chosen settings.
Use the axis selector to choose whether the trail plots X–Y, X–Z or Y–Z with the remaining axis mapped to color.
Every few seconds, based on the averaging interval, the app shows a red cross at the averaged location for that period.
Enable "Center on average" to keep that red cross in the middle of the display and shift the trail accordingly.
