# Heat of Justice 🔥: Return of the Spring

**A pixel-art action-adventure game** where you play as Nisa, a law student fighting to restore justice and bring back spring to the world. Inspired by Turkish mythology and Nevruz traditions.

## 🎮 Play Now
[Play on GitHub Pages](https://heatofjustice.github.io)

## 🌟 Features
- **Three unique levels** based on the falling of "Cemre" (air, water, earth)
- **Pixel-art visuals** with smooth animations
- **Comic-style storytelling** between levels
- **Simple but challenging** arcade gameplay
- **Original soundtrack** and sound effects

## 📁 Project Structure
```
heatofjustice/
├── assets/
│   ├── characters/
│   │   ├── nisa/
│   │   │   ├── idle_1.png      # Durma (ön)
│   │   │   ├── idle_2.png      # Durma (arka)
│   │   │   ├── walk_1.png      # Yürüme 1. frame
│   │   │   ├── walk_2.png      # Yürüme 2. frame
│   │   │   └── fire.png        # Ateş etme tek frame
│   │   └── effects/
│   │       ├── death_1.png       # Ölüm animasyonu (2 frame)
│   │       ├── death_2.png
│   │       └── hurt.png        # Hasar efekti (1 frame)
│   │
│   ├── enemies/
│   │   ├── wind/
│   │   │   ├── frame_1.png    # Rüzgar düşmanı 1. frame
│   │   │   └── frame_2.png    # Rüzgar düşmanı 2. frame
│   │   ├── water/
│   │   │   ├── frame_1.png    # Su düşmanı 1. frame
│   │   │   └── frame_2.png    # Su düşmanı 2. frame
│   │   └── rock_boss/
│   │       ├── idle_1.png     # Boss durma 1. frame
│   │       ├── idle_2.png     # Boss durma 2. frame
│   │       ├── attack_1.png
│   │       ├── attack_2.png
│   │       └── attack_3.png     # Boss saldırı animasyonu (3 frame)
│   │
│   ├── backgrounds/
│   │   ├── level1_rooftop.png
│   │   ├── level2_library.png
│   │   └── level3_campus.png
│   │
│   ├── ui/
│   │   ├── healthbar.png      # 200x20 piksel
│   │   ├── buttons/
│   │   │   ├── arrow_left.png
│   │   │   ├── arrow_right.png
│   │   │   └── retry.png
│   │   └── icons/
│   │       └── pause.png
│   │
│   ├── particles/
│   │   ├── fireball.png       # 16x16 piksel
│   │   └── cemre_light.png    # 32x32 piksel
│   │
│   └── audio/
│       ├── sfx/
│       │   ├── nisa_fire.wav
│       │   ├── nisa_hurt.wav
│       │   ├── enemy_spawn.wav
│       │   └── cemre_fall.wav
│       ├── voices/            # Opsiyonel
│       │   ├── panel1.mp3
│       │   ├── panel2.mp3
│       │   ├── panel3.mp3
│       │   ├── panel4.mp3
│       │   ├── epsiode_1/
│       │   │   ├── panel5.mp3
│       │   │   ├── panel6.mp3
│       │   │   ├── panel7.mp3
│       │   │   └── panel8.mp3
│       │   ├── epsiode_2/
│       │   │   ├── panel9.mp3                              
│       │   │   ├── panel10.mp3
│       │   │   ├── panel11.mp3 
│       │   │   └── panel12.mp3
│       │   ├── epsiode_2/
│       │   │   ├── panel13.mp3
│       │   │   ├── panel14.mp3
│       │   │   └── panel15.mp3
│       │   └── panel16.mp3 # Son     # (max 5 sn)
│       └── bgm/
│           ├── level1.mp3
│           ├── level2.mp3
│           └── level3.mp3     # Loop'lu
│
├── js/
│   ├── phaser.min.js          # Phaser 3.60
│   └── game.js                # Ana kod
└── index.html
```

## 🛠 Development

### Requirements
- Modern web browser
- GitHub account (for deployment)

### Running Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/heatofjustice/heatofjustice.github.io.git
   ```
2. Open `index.html` in your browser

### Building
No build required - just edit the files directly:
- `game.js` for game logic
- Assets in respective folders

## 🎨 Asset Specifications
- **Sprites**: 64x64px (player), 32x32px (enemies)
- **Backgrounds**: 1280x720px
- **Audio**: 
  - Music: MP3 format, loopable
  - SFX: WAV format, <3 seconds

## 🤝 Contributing
Contributions are welcome! Please open an issue first to discuss what you'd like to change.

## 📜 License
[MIT](https://choosealicense.com/licenses/mit/)

---

**Developed with 💙 and Phaser 3**  
Brought to you by the Heat of Justice team
