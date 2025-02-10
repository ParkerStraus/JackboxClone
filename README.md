# Jackbox Clone

A rough mini-project to replicate the controller system used by Jackbox Games, which allows for the use of browser devices as controllers.

There are three components to this project.
- [The Server](https://github.com/ParkerStraus/JackboxServer): The system that connects both the browser controller and the unity client and handles all incoming input and output.
- [The Client](https://github.com/ParkerStraus/JackboxClient): The game itself, built on Unity Engine that connects to the server, and sends all the respective output to the phone, and recieved the viable input from phone via the server.
- [The Controller](https://github.com/ParkerStraus/JackboxController): The Browser interface used by the browser devices, built on React.
