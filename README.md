# Chess

A C++ chess game that brings local two-player matches to the terminal. Built collaboratively with object-oriented design, the project models chess pieces, board state, and player interactions through a modular class structure.

## Features

- **Two-player gameplay:** Play locally with coordinate-based move commands and alternating turns.
- **Custom board setups:** Place or remove pieces and choose the starting side before beginning a game.
- **Chess rules:** Piece-specific movement, move validation, check and checkmate handling, and pawn promotion.
- **Match flow:** Resign, start another game, and view cumulative scores across a session.
- **Text-based board:** Follow the position as the board updates after moves and setup changes.

## Engineering focus

- **Object-oriented modelling:** Separate classes represent the board, squares, players, and individual piece types.
- **Abstraction and polymorphism:** Shared piece interfaces organize the different movement behaviours.
- **Separation of concerns:** Game state, player input, score tracking, and board display are organized into distinct components.
- **Collaborative development:** Developed as a team project using Git for integration and version history.

## Technology

**C++ · Standard Library · Make · Git**

## Example interaction

During a match, moves use algebraic board coordinates:

```text
move e2 e4
move e7 e5
```

Setup mode supports placing pieces, removing pieces, and selecting which side moves first.

## About this repository

This repository is a documentation-only showcase. The implementation and original development history are maintained in a separate private repository. No source files, binaries, or source archives are included here.

Created collaboratively at the University of Waterloo. This page describes the team project; it does not claim sole authorship.
