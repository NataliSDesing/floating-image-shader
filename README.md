# Floating Image Shader with Scroll & Mouse Interaction

This project creates a smooth, animated 3D floating image using WebGL (Three.js), inspired by advanced parallax and cloth-like distortion effects, similar to those used on the Alef Estate website.

## ✨ Features

- 🌬️ **Organic wave deformation** via custom vertex shader
- 🎢 **Mouse interaction** — smooth rotation in response to cursor position
- 🧭 **Scroll-based animation** — the image levels out and moves down as you scroll
- 🪶 **Light 3D twist** — initial offset along X, Y, Z axes for immersive look
- 🖼️ **Transparent background** — easily overlay on any site

## 🔧 Technologies

- [Three.js](https://threejs.org/) — WebGL 3D rendering
- Custom vertex and fragment shaders
- Pure HTML/JS — no build tools or frameworks

## 🚀 How to use

1. Clone or download this repository.
2. Open `index.html` in your browser.
3. Or deploy it using GitHub Pages to embed it in platforms like Tilda.

### Embed in Tilda

To embed this floating image in a Tilda project:

1. Deploy this project via GitHub Pages.
2. Insert an **HTML block** in Zero Block or your page.
3. Use this iframe code:

```html
<iframe src="https://your-github-username.github.io/your-repo-name/" 
        width="100%" height="100vh" style="border:0;"></iframe>
