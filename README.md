# Super Smash Bros. Randomizer
This tool helps you randomize characters for Super Smash Bros. Melee. It avoids stale characters.

## Quickstart
Python is required to run this. Install Python and run via
`python main.py`

## Usage
You can use the following commands to manage active and waiting players:  
`join`  
`leave`  
`swap`  
`status`  
`clear`/`reset`  
`exit`/`quit`  

To randomize characters for all players, use:  
`run`  

Ports are denoted by `P1`, `P2`, `P3` and `P4`. Waiting players are in a "lobby" and can be referenced to by using `L1`, `L2` and so forth.

### Samples
`join P1 Ryuu`  
Ryuu joins at port 1.

`join P2 Muzz`  
Muzz joins at port 2.

`leave P4`  
Port 4 leaves the game. (The player is moved to the lobby.)

`leave L1`  
Lobby 1 leaves. (Player is fully removed.)

`swap P1 P3`  
Port 1 and Port 3 swap positions.

`swap P4 L2`  
Port 4 swaps out for Lobby 2.

`status`  
List all the players (active and waiting).

`clear`  
Clear all the players.