## Tic-Tac-Toe

Multiplayer Tic-Tac-Toe game over Local Area Network

## Folder Structure
    .vscode
        settings.json
    bin
        com\jeevesh2002\tictactoe
            TicTacToe.class
            TicTacToe$Painter.class
    res
        blueCircle.png
        blueX.png
        board.png
        redCircle.png
        redX.png
    src
        com\jeevesh2002\tictactoe
            TicTacToe.java
    README.md

## Understanding

This project uses sockets to communicate between two devices connected to the same network.
This first device which connects to the socket will act as server and the second acts as client.
The device acting as server will always be the first to play and plays as X.

## Usage
The whole program is bundled into a single jar file and can be downloaded using the link below
[Download Jar file](https://github.com/jeevesh2002/Tic-Tac-Toe-over-LAN--java)

# Run the program using
```bash
java -jar <path to jar file>

Input IP: Enter the IPv4 Address you want to connect to
Enter Port: Enter a Port which is free
Do the same on the other device.
```
