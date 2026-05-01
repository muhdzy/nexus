# NEXUS

A futuristic single-page landing page with neon visuals, motion-heavy sections, and Three.js-powered 3D scenes. The page is built as a standalone HTML file with custom CSS and JavaScript, and it includes a hero, about, services, portfolio, CTA, and footer layout. fileciteturn0file0

## Features

- Animated custom cursor
- Fixed glassmorphism-style navigation
- Full-screen hero section with live 3D wireframe geometry
- About section with a second 3D scene
- Services grid with interactive feature cards
- Portfolio grid with multiple animated project canvases
- Call-to-action section with a floating grid effect
- Responsive layout for smaller screens
- Scroll reveal animations
- Custom scrollbar styling and scanline overlay fileciteturn0file0

## Tech Stack

- HTML5
- CSS3
- JavaScript
- [Three.js](https://threejs.org/) via CDN
- Google Fonts (`Orbitron` and `Syne`) via CDN fileciteturn0file0

## File Structure

```text
nexus3D.html
```

This project is currently implemented as one self-contained HTML file. fileciteturn0file0

## How to Run

### Option 1: Open directly
Open `nexus3D.html` in a modern browser.

### Option 2: Use a local server
For the smoothest experience, run the file through a local server so the browser loads external assets reliably.

Example:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000/nexus3D.html
```

## What the Page Includes

### Hero
The hero section uses a `canvas` element and a Three.js scene to render a rotating wireframe icosahedron, torus rings, and particles behind the headline. fileciteturn0file0

### About
The about section includes a second Three.js canvas with wireframe geometry and a stat block layout. fileciteturn0file0

### Services
The services section presents six feature cards covering 3D environments, interface architecture, motion systems, performance engineering, AI integration, and brand systems. fileciteturn0file0

### Portfolio
The portfolio area displays four project cards, each backed by its own animated canvas. fileciteturn0file0

### CTA
The CTA section contains an email input, a submit button, and a floating grid animation. fileciteturn0file0

## Customization Ideas

- Replace placeholder project names with real client or personal work
- Swap the copy to match your brand voice
- Adjust the neon palette in `:root`
- Add real links for navigation and footer items
- Connect the CTA form to a backend or email service
- Split the single file into separate HTML, CSS, and JS files if the project grows

## Notes

- The design depends on Three.js from a CDN, so an internet connection is needed unless you bundle the library locally. fileciteturn0file0
- The page is highly visual and uses several canvas animations, so performance will vary by device. fileciteturn0file0

## License

Add your preferred license here.
