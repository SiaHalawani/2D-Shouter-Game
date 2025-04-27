# ShooterGamea

## Overview
**ShooterGamea** is a 2D side-scrolling shooting game developed purely with HTML5, Canvas API, and JavaScript. The player controls a dynamic character, fights waves of enemies, navigates through obstacles, collects upgrades, and battles increasingly challenging bosses.

This game features:
- Responsive character movement and shooting.
- Charge and health mechanics.
- Power-ups (gifts, kits) to recharge and upgrade abilities.
- Varied enemy types (Simple Enemies, Bosses, Mega Boss).
- Rich animations and seamless background scrolling.
- Full audio integration: music, sound effects, and boss battle themes.
- Game win and game over scenarios with custom credit scenes.

---

## Game Controls
| Action | Key |
|:-------|:---|
| Move Up | Arrow Up |
| Move Left | Arrow Left |
| Move Down | Arrow Down |
| Move Right | Arrow Right |
| Shoot Forward | Q |
| Shoot Upward | A |
| Shoot Downward | Z |
| Teleport Left | W |
| Teleport Right | X |
| Pause | Escape |
| Start/Play | Enter |

---

## Installation Instructions

1. Download the full project repository.
2. Ensure all media files are included:
   - **Images**: `background.jpg`, `bossbg.jpg`, `backgroundwon.png`, `44.png`, `45.png`, `47.png`, `boss.png`, `bossblast.png`, `BIGBOSS.png`, `BIGBOSSMAD.png`, `4.png`, etc.
   - **Audio**: `music.mp3`, `bossmusic.mp3`, `winmusic.mp3`, `ded.mp3`, `blast.mp3`, `blasttwo.mp3`, `demonic.mp3`
3. Open `index.html` in any modern web browser.

---

## Project Structure
```
CGBOSSGAME/
├── index.html
├── assets/
│   ├── images/
│   └── sounds/
└── README.md
```
*Note: For better project organization, it is recommended to group assets inside an `assets/` folder.*

---

## Main Components

- **Sprite**: Abstract base class for all moving/drawing elements.
- **Character**: The player's avatar, capable of moving, shooting, upgrading, and managing health and charge.
- **Bullet Variants (Bullet, BulletU, BulletD)**: Projectiles for multi-directional shooting.
- **Enemies**:
  - SimpleEnemy: Standard foes.
  - BossEnemy: Mini-bosses with special attacks.
  - BigBoss: Major boss featuring complex movement and special abilities.
- **Power-ups**:
  - GIFT: Restores charge.
  - KIT: Upgrades shooting capability.
- **Obstacles**:
  - Obstacle (vertical)
  - VObstacle (horizontal)
- **Blasts**: Special boss attacks.
- **Music System**: Handles background music and event-triggered tracks.
- **Game Loop**: Controls updating, rendering, collision detection, and state management.

---

## Audio System

Music and effects are context-sensitive:
- Level Background Music: `music.mp3`
- Boss Fight Music: `bossmusic.mp3`
- Winning Sequence Music: `winmusic.mp3`
- Game Over Sound: `ded.mp3`
- Bullet Fire Sound: `blast.mp3`, `blasttwo.mp3`
- Special Boss Sound: `demonic.mp3`

---

## Credits

This project was entirely designed, programmed, and assembled by a **single developer**.

- **Concept**: Sondos Halawani
- **Programming**: Sondos Halawani
- **Game Design**: Sondos Halawani
- **Artwork**: Sondos Halawani
- **Music Composition**: Sondos Halawani

---

## Future Enhancements

- Mobile and touchscreen support.
- Additional weapon systems and player skins.
- More sophisticated AI for enemies.
- Enhanced visual effects (explosions, particle systems).
- Save/load feature for scores and achievements.
- Difficulty modes.

---

## License

This project is intended for educational, personal, and demonstration purposes only. Commercial use is prohibited without explicit permission.

---

# Enjoy the Game!

Play hard. Defeat all enemies. Conquer the Big Boss. 🚀

