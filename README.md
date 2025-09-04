# Battle City Tank Game

A classic tank battle game implementation using Python and Pygame, inspired by the legendary Battle City arcade game.

## Requirements

- Python 3.6+
- Pygame library

## Steps to Run this Codebase

1. Fork this repository: `https://github.com/theneurallab/tiktok-battle-tanks.git`
2. Clone your forked repository (replace `YOUR_USERNAME` with your actual GitHub username):

```bash
git clone https://github.com/YOUR_USERNAME/tiktok-battle-tanks.git
```

3. Navigate to the project directory:

```bash
cd tiktok-battle-tanks
```

4. Run the game:

```bash
python main.py
```

## Game Controls:

- **Mouse Click**: Start the game (click anywhere on the window)
- **W / Up Arrow**: Move tank up
- **S / Down Arrow**: Move tank down
- **A / Left Arrow**: Move tank left
- **D / Right Arrow**: Move tank right
- **Space**: Fire missiles
- **Close Window**: Quit game

## Game Rules:

- Control your tank and defend the symbol (eagle) at the base
- Destroy enemy tanks before they reach and destroy your base
- You have 3 lives - losing all lives results in game over
- Enemy tanks spawn continuously and move randomly around the battlefield
- Both you and enemies can destroy brick walls with missiles
- Cement walls are indestructible and block all movement and missiles
- Game over occurs when:
  - Your tank loses all 3 lives
  - The base symbol is destroyed (takes 4 hits)
- Enemy tanks have different movement patterns and will fire at you

## Project Structure

```
tiktok-battle-tanks/
├── main.py                        # Main game file with all game logic and classes
├── resources/                     # Game assets
│   ├── images/                    # Game graphics
│   │   ├── p1tankU.gif            # Player tank facing up
│   │   ├── p1tankD.gif            # Player tank facing down
│   │   ├── p1tankL.gif            # Player tank facing left
│   │   ├── p1tankR.gif            # Player tank facing right
│   │   ├── enemy1U.gif            # Enemy tank facing up
│   │   ├── enemy1D.gif            # Enemy tank facing down
│   │   ├── enemy1L.gif            # Enemy tank facing left
│   │   ├── enemy1R.gif            # Enemy tank facing right
│   │   ├── tankmissile.gif        # Player missile sprite
│   │   ├── enemymissile.gif       # Enemy missile sprite
│   │   ├── brick_wall.gif         # Destructible brick wall
│   │   ├── cement_wall.gif        # Indestructible cement wall
│   │   ├── symbol.gif             # Base eagle symbol
│   │   ├── symbol_destoryed.gif   # Destroyed base symbol
│   │   └── game_over.gif          # Game over screen
│   └── audios/                    # Sound effects
│       ├── fire.wav               # Tank firing sound
│       ├── hit.wav                # Tank hit/destruction sound
│       └── start.wav              # Game start sound
└── README.md                      # Project documentation
```

Made with ❤️ by [Neural Lab](https://theneurallab.com)
