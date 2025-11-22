# Battleship Game in Java

This is a terminal-based implementation of the classic **Battleship** game, created as a project for college. The game is written in **Java** and allows players to place ships and attack enemy positions with a limited number of attempts.

---

## Features

- Place ships of different sizes on a 10x10 grid:
  - Carrier (size 4)
  - Destroyer (size 3)
  - Submarine (size 2, 3 units)
  - Boat (size 1, 3 units)
- Validate ship placement to prevent overlapping or out-of-bounds positions.
- Attack opponent's ships using coordinate input (A0 to J9).
- Limited attempts (30 chances) to sink all ships.
- Clear game messages and error handling.
- Dynamic board display in the terminal.

---

## How to Play

1. Run the program.
2. Select a ship to position.
3. Enter the starting position for the ship (e.g., `B3`).
4. Choose a direction for the ship:
   - `H` → Horizontal
   - `V` → Vertical
   - `D` → Diagonal
5. Repeat until all ships are placed.
6. Attack by entering positions to fire upon (e.g., `C5`).
7. The game ends when:
   - All ships are destroyed → Attacking player wins
   - Remaining attempts run out → Defending player wins

---

## Game Flow

```text
===== BATTLE SEA =====

   a  b  c  d  e  f  g  h  i  j  
0  ~  ~  ~  ~  ~  ~  ~  ~  ~  ~  
1  ~  ~  ~  ~  ~  ~  ~  ~  ~  ~  
2  ~  ~  ~  ~  ~  ~  ~  ~  ~  ~  
3  ~  ~  ~  ~  ~  ~  ~  ~  ~  ~  
4  ~  ~  ~  ~  ~  ~  ~  ~  ~  ~  
5  ~  ~  ~  ~  ~  ~  ~  ~  ~  ~  
6  ~  ~  ~  ~  ~  ~  ~  ~  ~  ~  
7  ~  ~  ~  ~  ~  ~  ~  ~  ~  ~  
8  ~  ~  ~  ~  ~  ~  ~  ~  ~  ~  
9  ~  ~  ~  ~  ~  ~  ~  ~  ~  ~  
