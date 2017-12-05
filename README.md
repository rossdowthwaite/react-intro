# Intro to React

Tic Tac Toe game that:

* lets you play tic-tac-toe,
* indicates when one player has won the game,
* stores the history of moves during the game,
* allows players to jump back in time to see older versions of the game board.

tutorial source: https://reactjs.org/tutorial/tutorial.html

### Key takeaways

* When you want to aggregate data from multiple children or to have two child components communicate with each other, move the state upwards so that it lives in the parent component. The parent can then pass the state back down to the children via props, so that the child components are always in sync with each other and with the parent.

* Components without a state and a constructor can be coded as a **functional components**

* Immutability Is Important:
  * Easier Undo/Redo and Time Travel
  * Tracking Changes
  * Determining When to Re-render in React

* It’s strongly recommended that you assign proper keys whenever you build dynamic lists.
