# TerrainForge — 3D Procedural Terrain Generator

Generate stunning 3D terrain in your browser using procedural noise. Mountains, islands, forests — all rendered in real-time with Three.js.

**Live Demo:** [terrainforge-3d.surge.sh](https://terrainforge-3d.surge.sh/)

## Features

- **Procedural terrain** — Perlin noise with fractal Brownian motion (fBm)
- **Height-based coloring** — Deep water, shallow water, sand, grass, forest, rock, snow
- **Transparent water plane** — With subtle wave animation
- **Instanced trees** — Thousands of trees using InstancedMesh for performance
- **6 biome presets** — Mountains, Islands, Plains, Canyon, Tundra, Desert
- **Day/night cycle** — Sun angle control with dynamic sky color
- **Orbit camera** — Drag to rotate, scroll to zoom, right-drag to pan
- **Touch support** — Works on mobile
- **Seeded generation** — Same seed = same terrain
- **Screenshot export** — Download as PNG
- **Full parameter control** — Height, roughness, scale, water level, tree density

## Tech

- Three.js r128 (CDN) for WebGL rendering
- Custom Perlin noise + fBm implementation
- InstancedMesh for efficient tree rendering
- Shadow mapping
- Exponential fog
- Responsive design

## License

MIT
