# CIT281 Project 5

## Overview

Project goals and outcomes:

1. Gain experience working with classes, including class constructors and methods.
2. Gain experience interpreting existing code to design a new class, including constructor and methods.
3. Gain more experience working with code modules.
4. Gain experience executing and debugging Node.js code using VSCode, including module breakpoints.
5. Gain more experience working with Array `map()` and `forEach()` methods.
6. Gain experience working with the concept of a gaming loop.
7. Gain more experience working with objects and arrays.

## Deliverables

- `lab-06.zip`
- `p5.js`
- `p5-monster-game.js`
- `p5-monster.js`

These files should be placed in your `cit281/p5` folder and zipped into `p5.zip`.

## Summary

In Project 5, the focus was on creating a Monster Game program using classes. The game creates monsters with initial life values and minimum life values for them to be considered alive. The game loop involves draining life from each monster randomly until all monsters have died. Key concepts include class construction, method implementation, module usage, and debugging with VSCode. Extra credit opportunities involve adding additional features and understanding the provided code deeply.

### Project Structure
1. **`p5.js`**:
   - Entry point for the game project.
   - Declares the list of monsters and game configuration properties.
   - Creates an instance of the Monster Game.
   - Lists the game monsters and their initial values.
   - Plays the game until all monsters have died.

2. **`p5-monster-game.js`**:
   - Contains the `MonsterGame` class.
   - Includes methods for listing monsters, creating monsters, and playing the game.
   - Uses the `Monster` class from `p5-monster.js`.

3. **`p5-monster.js`**:
   - Contains the `Monster` class.
   - Includes methods for constructing monster instances, updating life, and randomly draining life.
   - Implements the class constructor and methods as per the project requirements.

### Additional Details
- **Testing and Debugging**: Breakpoints in VSCode help understand the flow and behavior of the game.
- **Array Methods**: Utilizes `map()` and `forEach()` for handling monster arrays.
- **Game Loop**: Implements a delay and life drain mechanics to simulate the game until all monsters are dead.
