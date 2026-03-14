# Avatar Clothes Try-On

A browser-based 3D avatar clothes try-on experience built with **Three.js** and **Ready Player Me**.

## What it does

- Displays an interactive **3D character** you can rotate and zoom
- Upload any **shirt image** to replace the avatar's top in real-time
- Upload any **pant image** to replace the avatar's bottom in real-time
- The uploaded clothing is projected onto the 3D model as a real texture with proper lighting — not just a color change
- Smart background removal strips the white/plain background from product photos automatically
- Reset either piece of clothing back to the original at any time

## How to use

1. Open `index.html` in a browser
2. Wait for the 3D avatar to load
3. Click **Upload Shirt** or **Upload Pant** and choose a clothing image
4. The outfit updates instantly on the character
5. Click **Reset** to revert to the original outfit

## Tech Stack

- [Three.js](https://threejs.org/) — 3D rendering
- [Ready Player Me](https://readyplayer.me/) — 3D avatar model
- Custom GLSL shaders for planar texture projection with diffuse lighting
- Canvas API for image processing (background removal, dominant colour extraction)

---

PRs are appreciated!
For further discussion contact: **salmanmemon569@yahoo.com**
