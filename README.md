# Jinie — Editorial (WebGL)

An interactive, real-time 3D editorial site for **DJ Jinie Bhatnagar** (Delhi → The World).

Built with vanilla **Three.js** (loaded via CDN + import map — no build step). Photos are
rendered as textured planes in genuine 3D space with a custom depth-of-field blur shader;
the camera physically dollies through the gallery shots as you scroll.

## Features
- Scroll-driven 3D camera with hero crossfade, depth-of-field, chromatic aberration
- Narrative section with scroll-activated colour-fill copy
- Animated genres ticker (House · Afro House · Progressive · Deep House · Melodic · Psy · Commercial · EDM)
- Mouse parallax, dust particles, film grain, editorial frame
- Device-aware quality (lower DPR / fewer effects on mobile) + reduced-motion fallback

## Running locally
ES modules + WebGL are blocked over `file://`, so serve it over HTTP:

```bash
python3 -m http.server 8000
# then open http://localhost:8000/
```

## Contact
Bookings & collabs — surbhibhatnagar96605@gmail.com · +91 98217 40778 · [@jinie_bhatnagar](https://instagram.com/jinie_bhatnagar)
