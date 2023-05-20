# DrawTheHouseGame
 we introduce a GameController class that handles the game logic. It creates instances of Die and House and provides a playGame() method to control the game flow.

The playGame() method repeatedly rolls the die, checks the outcome, and triggers the corresponding methods in the House class to build the components. 
It also provides feedback on the progress and displays the house using the toString() method.

The DrawTheHouseGame class serves as the entry point of the program, where we create an instance of GameController and call its playGame() method to start the game.

Both implementations achieve the same goal, but this alternative approach separates the game logic into a dedicated controller class, providing a clearer separation of concerns.
