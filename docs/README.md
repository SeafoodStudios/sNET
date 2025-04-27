# Scratch Networking by Encoding of Translations
![Logo](https://raw.githubusercontent.com/SeafoodStudios/sNET/refs/heads/main/res/Logo.svg)
### The sNET protocol is a way of broadcasting cross-project without cloud variables! You can use this signed out, as a New Scratcher, or just a regular Scratcher. This is intended for the creation of public notifications, text radios and much more.
## sNET Send
sNET Send is the broadcasting part of sNET, and is available in the Scratch project or in this repository's src folder. To use this, upload the sprite to your Scratch project and use the custom block "SNET: Broadcast with Connection ID". You may invent a connection id, but please keep it original so that it does not interfere with other connections. The system blocks are all not to be used, but you can use the encode and decode blocks to convert into binary.
## sNET Get
sNET Get is the receiving part of sNET, and is available in the Scratch project or in this repository's src folder. To use this, upload the sprite to your Scratch project and use the custom block "SNET: Begin Receiving with ID". Enter the ID you used in sNET send, and it will be received.
## Tips & Tricks
- Using the Language variable, you can completely seclude your connection with a different language. The default language is English.
- Think of sNET as variables. Receiving something means 1 in binary, and not receiving anything is 0 in binary.
