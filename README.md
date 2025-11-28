# Space Flight Simulator 🚀

A 3D browser-based space flight simulator where you can pilot different spacecraft through a realistic model of our solar system. Built with React, Three.js, and Tailwind CSS.

## What is This?

Space Flight Simulator is an interactive, educational space exploration game that lets you:

- **Fly through the Solar System** - Navigate from the Sun to Neptune and everything in between
- **Explore Planets and Moons** - Get close to celestial bodies to learn scientific facts about them
- **Choose Your Spacecraft** - Select from 4 different ship types, each with unique characteristics
- **Experience Environmental Hazards** - Encounter solar flares and radiation belts
- **Use Autopilot Navigation** - Set course for any planet with one key press

## How to Play

### Getting Started

1. Open `index.html` in a modern web browser (Chrome, Firefox, Edge, or Safari recommended)
2. The simulation starts automatically with your spacecraft positioned near Earth
3. Use the controls below to navigate through space

### Gameplay Tips

- **Approach planets slowly** to see detailed information about them
- **Monitor your ship stats** in the top-right HUD (fuel, hull integrity, radiation, temperature)
- **Watch for environmental warnings** - solar flares and radiation belts can damage your ship
- **Use autopilot** for long-distance travel to conserve fuel and navigate accurately
- **Switch camera views** to experience both external and cockpit perspectives

## Controls

### Flight Controls

| Key | Action |
|-----|--------|
| `W` / `↑` | Pitch down |
| `S` / `↓` | Pitch up |
| `A` / `←` | Roll left |
| `D` / `→` | Roll right |
| `Space` | Thrust forward |

### View & Interface

| Key | Action |
|-----|--------|
| `V` | Toggle camera view (External / Cockpit) |
| `I` | Toggle planet information panel |

### Autopilot Navigation

| Key | Destination |
|-----|-------------|
| `1` | Mercury |
| `2` | Venus |
| `3` | Earth |
| `4` | Mars |
| `5` | Jupiter |
| `6` | Saturn |
| `7` | Uranus |
| `8` | Neptune |
| `X` | Cancel autopilot |

You can also click the navigation buttons in the bottom-left panel to engage autopilot.

## Spacecraft Types

Choose your ship from the selection panel in the top-left corner:

| Ship | Speed | Fuel | Hull | Best For |
|------|-------|------|------|----------|
| **Deep Space Explorer** | 2.0 | 150 | 120 | Balanced exploration |
| **Hussam Zaid Fighter** | 3.5 | 80 | 80 | Fast maneuvering |
| **Heavy Cargo Hauler** | 1.2 | 300 | 200 | Long-range durability |
| **Scientific Research Vessel** | 1.8 | 120 | 100 | High radiation shielding |

## Planets & Destinations

The simulator includes all 8 planets of our solar system plus the Sun, each with:

- Accurate relative distances and sizes
- Scientific facts and information
- Moons (where applicable)
- Environmental data (temperature, radiation levels)

### Celestial Bodies

- **The Sun** - Our yellow dwarf star at the center
- **Mercury** - Smallest planet, closest to the Sun
- **Venus** - Hottest planet with thick atmosphere
- **Earth** - Our home planet with the Moon
- **Mars** - The Red Planet with Phobos and Deimos
- **Jupiter** - Largest planet with Io, Europa, Ganymede, and Callisto
- **Saturn** - Famous for its rings, with Titan and Enceladus
- **Uranus** - Ice giant that rotates on its side
- **Neptune** - Windiest planet with Triton

## HUD Elements

- **Top-Left**: Ship selection panel
- **Top-Right**: Ship status (velocity, fuel, hull, radiation, temperature)
- **Bottom-Left**: Navigation/Autopilot controls
- **Bottom-Right**: Control reference
- **Center**: Environmental hazard warnings (when applicable)
- **Bottom-Center**: Planet information (when near a celestial body)

## Technical Requirements

- Modern web browser with WebGL support
- JavaScript enabled
- No installation required - runs entirely in the browser

## Credits

- Spacecraft model: Hussam Zaid
- Built with [Three.js](https://threejs.org/), [React](https://react.dev/), and [Tailwind CSS](https://tailwindcss.com/)
