# Entelect Challenge 2015 Interactive GUI

This is a visualizer for the space invaders challenge. Its difficult to troubleshoot using the state and map files
directly. This tool loads a replay directory and allows you to interact with the state more easily.

Its purpose is to step through a replay directory to determine what the exact state of the game was
when your bot made its move.

## Features

- Move back and forth between state files (keyboard support)
- Click on entities to see information
- View player information

## Screenshot

![Alt text](/screenshot.jpg?raw=true "Screenshot")

## To run

```python main.py```

## Usage

### To open a state file

- Go to File -> Load State File
- Open a state file e.g. 'C:\Users\leonard\entelect\harness\Replays\0001\016\state.json'
- Other states will automatically be detected and loaded if it is in the standard replay structure

### Other functions

- Keyboard bindings are 
 - Left: to move back a round 
 - Right: to move forward a round and 
 - Control-r: to reload information windows
- Use the menus to get player info
- Click on entities in the map to get cell information
- Click on labels in information windows to collapse / expand details