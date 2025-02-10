# Jackbox Clone

A rough mini-project to replicate the controller system used by Jackbox Games, which allows for the use of browser devices as controllers.

There are three components to this project.
- [The Server](https://github.com/ParkerStraus/JackboxServer): The system that connects both the browser controller and the unity client and handles all incoming input and output. This is the part that starts first when initializing the project.
- [The Controller](https://github.com/ParkerStraus/JackboxController): The Browser interface used by the browser devices, built on React. Connects to the server, sends user input, and receives browser interface info.
- [The Client](https://github.com/ParkerStraus/JackboxClient): The game itself, what the general public sees. Built on Unity Engine, it connects to the server last, sends all the respective output to the phone, and receives the viable input from the browser device via the server.
