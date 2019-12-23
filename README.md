# santas_little_helper
Kringlecon 2019 - An automated websocket tool

This is a tool I wrote for interacting with the backend server during the Kringlecon 2019 CTF. It allows you to pull relevant data from the backend through the websocket. 

It generates map data and is able to start conversations with npc's anywhere on the map. But most importantly, it can teleport your character to any room in the Kringlecon CTF game. This includes rooms that are normally locked and not accessible. This allows you to reach the end credits of the game without doing a single challenge.

## Installation
Please install the following dependency first:

`python3 -m pip install websocket_client`

## Usage

To use this script, fill in your email address inside the script and then run it.

    -h | --help -> print this help
    -c | --create_data -> Generate the data file needed for teleporting and other functions
    -t | --teleport -> Teleport to a new location
    -g | --print_grid -> Print grid data for a zone
    -n | --npc-talk -> Talk to a certain NPC
