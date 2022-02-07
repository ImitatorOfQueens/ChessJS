# Chess written in Javascript

Chess implementation with Typescript. Uses TDD to drive development
    * Red-Green-Refactor

The simplest design possible will be used to get a test working.
    * Inital thoughts is a Game object, that has a Board object, which in turn has a Piece Object
    * There's maybe a Tile object in there somewhere, but uncertain at this point
    * A top-down approah will be used. So Game object first and then moving on to Board and Piece.

No UI of any note will be used for the inital game. The Game will have all the rules of Chess for V0.1

UI and multiplayer; either with client-server or P2P will be implemented after the inital game is developed.

A database and possibly an AI will accompany the game afterwards.

