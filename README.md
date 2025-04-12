# 🐍 Snake Game in C

This is a classic **Snake Game** written in C, playable in the console. The snake moves around the board, eats the fruit, and grows longer. The goal is to survive as long as possible and beat the high score!

## 🕹 Features

- Console-based UI using ASCII characters
- Snake wraps around the screen edges
- Keeps track of the score and displays a "Game Over" screen
- Simple keyboard input for movement (`W`, `A`, `S`, `D`)
- Fruit spawns randomly on the board

## 📸 Screenshot

```
######################################
#                                    #
#              O F                   #
#                                    #
######################################
Score: 10
```

## 🧱 Built With

- Language: **C**
- Libraries: `stdio.h`, `stdlib.h`, `windows.h`, `conio.h`

## 🎮 Controls

| Key | Action       |
|-----|--------------|
| W   | Move Up      |
| S   | Move Down    |
| A   | Move Left    |
| D   | Move Right   |
| X   | Exit Game    |

## 🚀 Getting Started

### ✅ Requirements

- Windows OS (uses `windows.h` and `conio.h`)
- A C compiler (e.g. GCC)

### 🔧 How to Compile & Run

1. Clone the repository or copy the source code into a file named `snake.c`.

```bash
gcc snake.c -o snake
```

2. Run the executable:

```bash
./snake
```

> Note: Use `gcc` or any compatible C compiler on Windows. On Linux or Mac, you’ll need to replace `conio.h` and `Sleep()` functions.

## 📦 File Structure

```
snake-game/
├── snake.c         # Main game code
└── README.md       # This file
```

## 🧠 Future Improvements

- Persistent high score (save to file)
- Border collision (instead of wrapping)
- Game levels or speed increase
- Cross-platform support (Linux/Mac compatibility)


Enjoy the game! 🎉
