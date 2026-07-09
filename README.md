# 👽 Zelda-Game

A text-based console game made to learn and implement fundamental Object-Oriented Programming (OOP) concepts in C++. 

## How to Run
Just run `Zelda.exe`. If it doesn't work, add the `.txt` files and the `.cpp` file into a new console application project in Microsoft Visual Studio, build the project, and run it.

## Game Description
The princess of the kingdom of CPeria has been captured by an evil wizard and placed in a castle guarded by monsters. Your job is to set her free and lead her safely back outside. 

* **The Castle:** Contains 9 rooms. You start in Room 1, which has the castle exit on its west wall.
* **The Mission:** The princess is locked in Room 9. You must navigate the maze, pick up essential items, defeat two monsters, rescue the princess, and escape.
* **The Monsters:** 
  * **Medusa (Room 5):** Turns players to stone. Defeat her by using the **Magic Shield** (found in Room 3). Defeating her opens a path to Rooms 7 and 8.
  * **Dracula (Room 6):** Guards the door to Room 9. Defeat him using the **Silver Dagger** (found in Room 7).
* **Inventory & Treasure:** Your bag can hold up to 10 items. Treasures include a Golden Egg (Room 2), Golden Chalice (Room 4), and a P=NP proof paper (Room 8).

> ⚠️ **Warning:** Attacking a monster without the proper weapon in your inventory results in immediate death. Leaving the castle without the princess results in losing the game.

## Project Requirements & Implementation
This project was implemented using OOP design principles, managing state through room transitions, inventory tracking, and file I/O operations:

* **File Configuration:** The game dynamically reads the storyline from `Start.txt` and room data from `Rooms.txt`. Win/loss conditions read from `EndWin.txt`, `EndLose.txt`, and `EndDead.txt`.
* **Commands:** The user inputs text-based commands: `MOVE [NORTH/SOUTH/EAST/WEST]`, `PICK [ITEM]`, `DROP [ITEM]`, `LOOK`, `ATTACK`, and `EXIT`.
* **Room Limits:** Rooms dynamically display descriptions, available exits, monsters, and a maximum of 5 items.

## Author
**Abhijeet Ranjan Prasad**
* 🎓 3rd Year ECE Student at IIT BHU
* 🐙 [GitHub Profile](https://github.com/NA0MI7)
* 💼 [LinkedIn Profile](https://www.linkedin.com/in/mr-abhijeet-ranjan-prasad-87b975348/)

## License
This project is open-source and available under the MIT License.
