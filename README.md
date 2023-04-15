# Blockchain-Development

We will implement this game by writing a contract TicTacToeGame. This contract will store the
individual moves on the game board played between two players.

Two players will play this game. playerOne and playerTwo. One of the players who starts the
game, by deploying the contract, will be the playerOne. For playerTwo, the details (address) will
be passed to the contract while starting the game.

Either of the players can start with the first move.

The implementation of the game board in this contract is done using a one-dimensional array
of addresses. Each element of the array will store one of the three values. address(0), this will
be the default value of all the elements. address(playerOne) or address(playerTwo), this
depends on the move each player makes while playing the game.
