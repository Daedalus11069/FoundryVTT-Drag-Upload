![](https://img.shields.io/badge/Foundry-v13-informational)

This is a fork of [the original unmaintained module](https://github.com/cswendrowski/FoundryVTT-Drag-Upload)

# Drag Upload (maintained for)

## WARNING - Drag Upload will NOT work if you run Foundry in Admin mode on Windows due to a Windows security feature!

Adds the ability to drag files onto the Foundry canvas to automatically create Tokens, Tiles, Journal Pins, and Ambient Audio

![](./dragupload.gif)

If the file is an audio file (.mp3, .mp4, .wav, .flac), it will be created as an Ambient Audio with easing.

Otherwise, it will be treated as an Image and created based on the current active layer:

- Token: 1x1 Actor with Token
- Tile: Tile of the same size as the image
- Notes: Journal with a corresponding Journal Pin
- Other: Same as Token
