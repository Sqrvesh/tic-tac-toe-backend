# Tic Tac Toe API
Uses Minimax algorithm to find the best move possible.

### To run:
```
flask run
```
### End points:
```
GET: / (for testing)
response: Crazy Tic Tac Toe AI
```
```
POST: /ai/nextmove

body: {
    board: ["X", " ", "O", "X", " ", " ", " ", " ", " "],
    player: "O"
}

board: (array representation of current board)
player: (current player to move "O" / "X")

response: {
    move: "6"
}

move: (String with position for best move (0 - 9))
```
