# Pokémon: Legacy of the Shadows

**A toy-style, top-down 3D action-adventure inspired by Pokémon Rumble.**

## Overview
Inherit your grandfather's house and discover a mysterious Pokédex. A corrupted Lugia and its Shadow Pokémon plague the land. Explore eight lands, battle corrupted legendaries, purify them, recruit allies, and restore the world.

## Game Features
- **Real-time Combat:** Space to attack, E for special, Q to dodge (Rumble-style)
- **Team System:** Choose a starter (Charmander, Squirtle, Bulbasaur, or Pikachu) and recruit up to 2 allies
- **Purification Mini-game:** Defeat shadow bosses and tap to purify them
- **15% Shiny Chance:** Rare color variants of purified Pokémon
- **Pokédex:** Collect all 151 Pokémon
- **8 Lands:** Each with a unique corrupted legendary boss
- **House Progression:** Upgrade your base with new gear and features
- **Save/Load:** Persistent progress via localStorage

## How to Play
1. Open `index.html` in a modern browser
2. Choose your starter
3. Use **WASD** to move, **Space** to attack, **E** for special move, **Q** to dodge
4. Press **M** for map, **P** for Pokédex, **Esc** to pause
5. Defeat enemies, purify shadow Pokémon, and collect them

## Controls
- **WASD** — Move
- **Space** — Basic Attack
- **E** — Special Move
- **Q** — Dodge
- **Mouse Wheel** — Camera zoom
- **M** — Map
- **P** — Pokédex
- **Esc** — Pause

## File Structure
```
├── index.html          # Full prototype (paste and play)
├── README.md          # This file
├── LICENSE            # MIT License
└── assets/            # Models, audio, textures (future)
```

## Deployment
### GitHub Pages
1. Create a GitHub repository: `legacy-of-the-shadows`
2. Push `index.html` and `README.md` to `main` branch
3. Go to Repo → Settings → Pages
4. Set branch to `main`, folder to `/ (root)` → Save
5. Visit `https://your-username.github.io/legacy-of-the-shadows/`

### Local Testing
```bash
python -m http.server 8000
# Open http://localhost:8000
```

## Troubleshooting
- **Blank page?** Check browser console (F12) for errors. Ensure `index.html` is in repo root.
- **Models not loading?** Blender exports go in `/assets/models/` with relative paths.
- **Animations not working?** Ensure clip names in Blender match: `Idle`, `Walk`, `Attack`, `Special`, `Dodge`.

## Art Style
- **Toy-style 3D:** Chunky shapes, bright colors, soft shading, thick outlines
- **Top-down camera:** See the player's full body, not just the top of their head
- **Cutscenes:** 2D anime-style animations for story beats

## Next Steps
1. Export Blender models (.glb format) with named animations
2. Add sound effects and music
3. Expand to full 151 Pokédex entries
4. Add house customization UI
5. Implement difficulty settings and assist options

## License
MIT License — Free to use, modify, and distribute.

---
**Made with Three.js and ❤️ for Pokémon fans everywhere.**