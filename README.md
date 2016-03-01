# Chess---Server

Create a simple chess app that get the pieces' movement from the server.
(For the Android app client sample code: https://github.com/timothyhartanto/Chess---Client)
You need to send the format manually from the server, once the connection is established.

Piece position format: <piece code><horizontal position><vertical position>[space]<piece code><horizontal position><vertical position>[space]<piece code><horizontal position><vertical position> etc...

Note: You need to run the server first before executing the app.
Once the connection is established, you need to send in the input.

there are only 10 pieces on this application
Piece's code:
K: White King
Q: White Queen
B: White Bishop
N: White Knight
R: White Rook
k: Black King
q: Black Queen
b: Black Bishop
n: Black Knight
r: Black Rook

Example of data sent will be:
Ka1 Qg3 Be6 Ne4 Rd1 kg6 qa4 bf5 ng1 rf3


And the board format as follow:

 |a|b|c|d|e|f|g|h
---|---|---|---|---|---|---|---|---
8| | | | | | | | 
7| | | | | | | | 
6| | | | |B| |k| 
5| | | | | |b| | 
4|q| | | |N| | | 
3| | | | | |r|Q| 
2| | | | | | | | 
1|K| | |R| |n| | 

