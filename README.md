# Adventure-Based-RPG-C++
The princess of the kingdom of CPeria has been captured by an evil wizard and placed in a castle guarded by monsters. Your job is to set her free and bring her back outside the castle

## How to Run
Just run __game.exe__. If it doesnt work, then add the .txt files and the .cpp file in a new project (console application) in Microsoft Visual Studio and then build the project and run it.

## Commands To Use
- The PICK command should accept the object to be picked as the second parameter. e.g. In the above example, if the user type the command PICK DAGGER, it should remove the dagger from the room, add the dagger to the user’s bag and display a message on the screen. Something that is not in the room should not be allowed to be picked.
- The DROP command should also accept the object to be dropped from the user’s bag into the current room.
- The EXIT command should exit the program.
- The ATTACK command should attack the monster in the room (if there is one). If the weapon that the monster can be killed with is in the bag, the monster should die. Other wise it should kill the user. In case of a death by the hands of monster, the game should end after displaying all the text in a file called EndDead.txt on the screen.
- A monster’s death should create a link between two rooms and its body should remain on the floor. Medusa is guarding the link between room 5 and room 8. Dracula is guarding the link between room 6 and room 9.
- The LOOK command should print out the description of the room including all the items and doors in the room.
- If the user exits the castle after rescuing the princess, the text in a file called EndWin.txt should be displayed and the game should end.
- If the user exits the castle without rescuing the princess, the text in a file called EndLose.txt should be displayed and the game should end.

### Interface
![c++](https://github.com/PlayZone30/Adventure-Based-RPG-C-/assets/133949037/d5460af1-3a87-48da-99f2-e00e1dcbdc0f)
