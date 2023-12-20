# TicTacToe-Project
 Group project in which we developed a graphical user interface and integrated Tic-Tac-Toe logic, enabling two clients to engage in multiplayer gameplay on a shared server.

# Description

Developed a Tic-Tac-Toe application requiring compilation of server and GUI classes. Users compile the server first, followed by the GUI for a seamless interface. Upon client-server connection, players engage in Tic-Tac-Toe matches, with win and draw announcements. The application offers options to start a new game, quit, and disconnect from the server for enhanced user control.

Implemented in Java, the project utilizes its robust frameworks, including GUI, to create a dynamic interface for clients. The inclusion of a server, coupled with expertise in threading, allows multiple clients to connect seamlessly, fostering interactive gameplay and enabling multiplayer engagement.

We encountered challenges in ensuring effective communication between the server and clients. Addressing this, we thoroughly understood our server and resolved issues within the client networking class. This comprehensive approach resulted in seamless and proper communication between the server and clients.

# How To Run Program
1. After opening file ensure you have at least three terminals open.
2. In the first terminal, compile the server by entering: javac GameServer.java
3. In the same terminal, compile the GUI by typing: javac GameGUI.java
4. In the first terminal, start the server by entering: java GameServer
5. In the other two terminals, run GUI instances by entering: java GameGUI
6. Once the server and GUIs are running, on each GUI:
   Enter "localhost" in the "IPAddress" textfield.
   Enter "1234" in the "Port" textfield.
   Click "Connect" button.
7. After connecting, you can start playing Tic-Tac-Toe.
8. To disconnect, use either the "Quit" or "Disconnect" button on the GUI.

# How to Use Project
1. Upon starting the game and conecting to the server, you will be assigned either "X" or "O."
2. The client is informed at the top whose turn it is.
3. When it's your turn, click any available spot on the grid to make your move.
4. After making your move, patiently wait until it announces your turn again.
5. Ensure not to click on the GUI when it is not your turn to avoid incorrect moves.

# Group Members
Alina Jalisi and Gabby Peña
