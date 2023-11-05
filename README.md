*Note: This tool doesn't work yet, don't try to use it!*

# Savegame Analyser

## Features

* Identify appropriate game (and version) from save file
* Extract key metadata & game data
* *Maybe* modify this data

## Components

* Uploader
  * Avoid actually persisting anything, just load it up and check what it is.
* Identifier script
  * Basically a giant `when`, using a definition of bytes in positions.
  * Once identified, passed on to a dedicated script for each game.
* Analyser scripts
  * One for each game
  * Extracts XP, items, etc

## Tech stack

???
