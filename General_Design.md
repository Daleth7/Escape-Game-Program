Description:
  * A large cube made up of smaller cubes or rooms each of which may contain a test, prize, clue or item. Each room has 6 doors ( up, down, north, south, east, west ). One exit lies on the exterior of the cube winning condition requires you to get to this exit. After a certain time (number of turns or a clock feature) segement of the cube move (think of rotating sections of a rubix cube) or on cetain events rotating the entire cube. The players job to orientate themselves and find where the exit lies and keep track of where they currently are in the cube and get to the exit.

* General:
  * This is going to be a single player, point-and-click escape game.
  * The goal of the player is to escape this mysterious location he/she has been placed in. There is only one exit.
  * The player advances through the game by moving through a map.
  * The game is won if the player successfully reaches the exit.
  * There is no scoring mechanism.
  * The game will have audio.
  * The game will be a 3-D, graphical program.
  * The game will belong to the point-and-click game category
  * The game will tell a story and/or have a background story.
  * There will be a save feature such that the player may resume his/her progress at a later date.
* Starting the game and winning/losing the game:
  * Upon each new game, the exit shall be randomly placed on one side of the cube, located outside. Depending on where the exit is, the wall adjoining the exit will become passable.
  * The exit will not move even as the cube rotates. The old, adjoining wall will become impenetrable while the new adjoining one becomes passable.
  * Upon each new game, the player will start in a random block on one side of the cube, just inside the walls.
  * As the player enters a new room, the game shall automatically save. This provides a checkpoint system that the player may resume from in the event of dying or reloading the game.
  * As the player progresses through the game, he/she will have a sanity bar that, if empty, indicates whether the player has lost or not. If the bar is empty, the player is considered to have lost and will resume the game at the latest, saved checkpoint.
  * Low sanity levels will affect the clarity of messages and hints the player shall receive.
  * Sanity level shall also affect the effectiveness of the player during battle challenges.
* Game components:
  * Map - a pre-generated entity that is composed of blocks and is three dimensional
  * The map will be of limited size, and its boundaries will be marked with walls.
  * Periodically, the blocks in a section of the map will be rearranged in a Rubik's cube fashion. The player will know that the map has changed through visual and audio cues. With each rotation, the blocks shall rotate as well, meaning the orientation will change.
  * Walls - blocks that may not be occupied nor passed through by the player.
  * Block - a cubical room the player may or may not occupy. Each one holds a challenge or puzzle for the player such that he/she must solve the puzzle before being able to advance.
  * For purposes of orientation, there shall be six, named directions corresponding to each face of a block: up refers to the ceiling; down refers to the floor; and north, south, east, and west refer to their respective cardinal directions.
  * Moving - the player advances one block farther on the map.
  * The player may choose any of the six directions to move when advancing.
  * Solving - when a puzzle is completed, the player is allowed to advance to the next block
  * Inventory - throughout various blocks, there are items the player may pick up and keep. The inventory shall be a place for the player to store said items for future use. This storage space will be unlimited and is global, i.e. the player can keep any items in the inventory throughout the game and into any block.
* Interaction with the environment:
  * Through the screen, the game will be in the first person point of view.
  * The player shall be positioned in the center of the room.
  * The player may interact using the keyboard and mouse
  * Interactions with objects occur when the player clicks on the object in question.
  * There will be multiple types of interactions possible when the player clicks on an object. These types will be choosable by the player (e.g. including a set of interaction icons that they player clicks)
  * To view another side of the room, the player will click on the edge of the screen. This will be highlighted when the cursor hovers over the clickable region.
  * At least some of the messages to the player (such as dialogue) will be presented as text. This text will be located on the bottom edge of the screen.
* Player obstacles/challenges:
  * Some challenges will be a combatant system where the player is faced with defeating a "guard". In these challenges, the player will be allowed to examine the current room and/or return to the previous room before engaging the "guard" in battle.
  * During combat where a player must battle an opposing character, the player will be engaged in a turn-by-turn system. During each turn, either the player or the opponent must select one of several actions to perform. For the player, he/she may select an action via a set of buttons on the screen. These actions shall include: attacking, defending, running, etc.
  * Some challenges will involve riddles.
* How the player will be helped
  * A model of the cube map will be provided to the player so that he/she may mark his/her position. This will be the player's first item.
  * A small model of the cube's map shall be shown on the bottom left corner of the screen. It will show in solid the surface the player in on (with respect to the z-axis) while the rest of the model is transparent.
  * This model can be expanded to full screen when the player clicks on the model icon. To shrink it back down, the player clicks an "X" button at the top right of the window.
  * The model shall include only two marks: one to denote the position of the player and the other to denote the exit. The player shall be responsible for making these marks.
  * Like the cube, the model can be manipulated, but the player will do this manually with a series of rotation buttons.
  * In addition to the model, the player shall be given a compass to aid in orienting the player. Like the model, the cardinal directions shall be shown on screen.
  * Because there shall be combat in some of the rooms, the player shall also be given a rusted, dull and bloody kitchen knife. The player will have to take this item off the body of a former prisoner's corpse.
* Story / backstory:
  * Most if not all the blocks shall contain notes left behind by previous captives. These notes shall give the player another piece to the overall story.
