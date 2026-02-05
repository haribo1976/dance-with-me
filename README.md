# Dance With Me

An interactive music and dance experience that invites you to move, breathe, and let go.

## The Experience

**Dance With Me** is a 3-minute journey through movement and music, designed to:
- Encourage spontaneous movement
- Create a safe, judgement-free space to dance
- Respond to your interactions with sound and visuals
- Guide you through a complete emotional arc

## How It Works

### Phases

The experience flows through five distinct phases:

1. **Warmup** (25s) - Gentle invitation to breathe and sway
2. **Build** (35s) - Energy slowly rises, movements expand
3. **Peak** (45s) - Full expression, freedom, celebration
4. **Flow** (35s) - Floating, drifting, riding the wave
5. **Cooldown** (20s) - Gradual settling, returning to stillness

### Interaction

| Input | Effect |
|-------|--------|
| **Mouse movement** | Creates flowing light trails |
| **Mouse click** | Spawns ripples and particle bursts |
| **Spacebar** | Pulse wave from center |
| **Arrow Up/Down** | Increase/decrease energy |
| **Arrow Left/Right** | Shift colour palette |

### Music

The experience generates its own music in real-time using the Web Audio API:
- **Bass pulses** anchor the rhythm
- **Melodic elements** follow pentatonic scales that shift with each phase
- **Ambient pads** create warmth and depth
- **Tempo** responds to energy level (80-140 BPM)

### Visuals

- **Particle systems** that respond to beat and movement
- **Flowing waves** that pulse with the music
- **Central visualiser** showing audio frequencies
- **Colour transitions** that reflect emotional tone

## Getting Started

Simply open `index.html` in a modern web browser (Chrome, Firefox, Safari, Edge).

```bash
# On macOS
open index.html

# On Windows
start index.html

# On Linux
xdg-open index.html
```

No installation required. No dependencies to install. Just dance.

## Options

- **Full Experience** - Dynamic prompts encouraging varied movement
- **Gentle Movement** - Softer prompts for those preferring subtler motion

## Design Philosophy

### Inclusive Movement

- Prompts are invitations, not instructions
- "Can't dance" doesn't exist here
- Any movement is the right movement
- Stillness is also welcome

### Emotional Safety

- No scoring or judgement
- Private experience (no data collection)
- Easy pause/restart controls
- Gentle transitions between phases

### Sensory Comfort

- Smooth colour transitions (no harsh flashing)
- Volume levels balanced for comfort
- Visual complexity scales with energy
- Escape/pause always available

## Technical Details

Built with:
- **p5.js** for visual rendering
- **Web Audio API** for generative music and beat detection
- **Vanilla JavaScript** for state management

No external dependencies beyond p5.js (loaded from CDN).

## The Creative Concept

Dance is a fundamental human expression that transcends skill or technique. This experience removes barriers:

- **No "right" moves** - Follow your body's intuition
- **No audience** - Just you and the music
- **No judgement** - Every movement is valid
- **No goal** - The dance itself is the destination

The visuals respond to you, creating a feedback loop where your movement shapes the world, and the world invites more movement.

## If It Worked...

You smiled. You moved. You forgot about time for a moment.

Maybe it felt a little silly. A little beautiful. A little magical.

That's exactly right.

---

*Created with joy, for joy.*
