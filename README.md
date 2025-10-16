# 🍫 ChocoPass

![image](https://github.com/user-attachments/assets/8dd6822d-565b-48fc-8a05-8fe094b2cbc0)

## Summary

"ChocoPass" is a command-line, text-based game where you navigate a multi-level grid, collect chocolates, survive pop quizzes, and try to win over your COMP1510 instructor, Chris. Move your character in four cardinal directions across increasingly challenging levels.

## Motivation

This game was developed to strengthen my procedural Python skills. Along the way, I experimented with the itertools module, implemented comprehensive unit testing, and built a robust suite of 95+ tests to ensure high code quality.

## Requirements

- Python 3.6+

## Quick Start

Clone the repository:

```bash
git clone https://github.com/yourusername/chocopass.git
cd chocopass
```

Run the game:

```
python game.py
```

Run tests:

```
python -m pytest unit_tests/
```

## Gameplay

### Objective

Collect 10 Reese's chocolates and pass Chris's final exam to graduate!

### Controls

```
[1] North    [2] South    [3] East    [4] West
```

### Map Symbols

| Symbol | Meaning           |
| ------ | ----------------- |
| `*`    | Your character    |
| `#`    | Walls/obstacles   |
| `!`    | Reese's chocolate |
| `C`    | Instructor Chris  |

### Game Mechanics

- **Levels**
  - **Level 1 (Tech Hub)**: Start collecting chocolates
  - **Level 2 (Student Lounge)**: After 5 chocolates, quiz damage doubles
  - **Level 3 (Room 645)**: After 10 chocolates, face Chris in the final exam
- **Pop Quizzes**: 20% chance of triggering per move, philosophical questions with no right answers (success is random)
- **Intelligence and HP**: Gain intelligence points for correct answers, lose HP for wrong answers
- **Final Exam**: Higher intelligence increases chances of passing

## Features

### Comprehensive Testing Suite

- **95+ Unit Tests** ensuring robust code quality that tests every game function
- **Mock Testing** for random elements and user input
- **Edge Case Coverage** including boundary conditions and error handling

### Clean Architecture

- **Modular Design**: 20+ well-documented functions with clear responsibilities
- **Type Hints**: Comprehensive docstrings with parameter descriptions
- **Error Handling**: Graceful input validation and boundary checking

### Python Libraries & Modules

- **Random Module**: Sophisticated probability systems and random sampling
- **Itertools**: Creative use for string repetition and combinations
- **Dictionaries & Lists**: Efficient game state management and coordinate handling.

🥚 Easter egg -
Inspired by my COMP1510 class, where pop quizzes strike without warning and every answer _kind of_ feels right… and if you haven’t guessed already, my instructor has a soft spot for Reese’s chocolates!
