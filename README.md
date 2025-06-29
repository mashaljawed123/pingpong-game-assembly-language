# 🕹️ Ping Pong Game in Assembly (x86 MASM)

![Assembly Language](https://img.shields.io/badge/language-Assembly-blueviolet)
![Platform](https://img.shields.io/badge/platform-Windows-blue)
![Architecture](https://img.shields.io/badge/architecture-x86-lightgrey)
![Status](https://img.shields.io/badge/status-Completed-brightgreen)

## 👨‍💻 Developers

* **Rida** (22k-4409)
* **Mashal** (22k-4552)
* **Mehdi** (22k-4480)


## 🎮 Game Overview

A **console-based 2-player Ping Pong game** written entirely in **x86 Assembly** using **Irvine32** library for Windows. Players compete to bounce a moving ball using paddles, with increasing difficulty and speed controls.


## 🧠 Key Features

* Real-time paddle movement (Player 1: `W/S`, Player 2: `I/K`)
* Ball physics with direction, speed, and bounce logic
* Difficulty selection (Easy / Medium / Hard)
* Game pause/resume (`SPACE` / `ENTER`)
* Speed control (`F` to speed up, `L` to slow down)
* Replay and exit functionality (`R`, `ESC`)
* In-game scoring for both players
* Colored console interface using Irvine32 functions


## 🕹️ Controls

| Action              | Player 1          | Player 2 |
| ------------------- | ----------------- | -------- |
| Move Up             | `W`               | `I`      |
| Move Down           | `S`               | `K`      |
| Increase Ball Speed | `F`               | `F`      |
| Decrease Ball Speed | `L`               | `L`      |
| Pause / Resume      | `SPACE` / `ENTER` |          |
| Replay Game         | `R`               |          |
| Exit to Menu        | `ESC`             |          |


## 📂 Project Structure

```
📁 PingPongAssembly
├── pingpong.asm        # Main Assembly source file
├── Irvine32.inc        # Include file (provided by Kip Irvine)
├── README.md           # This documentation
```


## 🔧 Requirements

* Windows OS
* [Kip Irvine’s Irvine32 library](https://www.kipirvine.com/asm/examples/index.htm)
* MASM assembler (Microsoft Macro Assembler)
* Console that supports 80x25 layout


## 🔄 How to Run

1. Ensure MASM and Irvine32 are properly set up.
2. Compile the program using a compatible assembler (e.g., with Visual Studio or via command line).
3. Run the `.exe` in a Windows console.

> 🧩 *Game starts with a menu to read instructions and select difficulty before jumping into action!*


## 🎯 Game Modes

When starting the game, choose between:

* **1 = EASY**: Larger paddles for relaxed gameplay
* **2 = MEDIUM**: Smaller paddles and faster movement
* **3 = HARD**: Narrow paddles and high challenge


## 📘 Concepts Covered

* Real-time keyboard input handling
* Memory manipulation and register-level logic
* Structured Assembly programming (procedures, control flow)
* Graphics using ASCII and cursor manipulation (`gotoxy`)
* Delay and timing with game loops


## 📑 License

This project is created for educational purposes. Free to use, modify, and distribute with credit to the authors.

