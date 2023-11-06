# lottery.aleo

## Model representations
`Lottery.aleo` program is a simple system for the operation of an Aleo blockchain platform, which is implemented on the Aleo blockchain platform. 
This game is composed of a Ticket record and an action play transition. 

## Code overview
Structures:
`mapping num_winners`: u8 => u8: A mapping to keep track of the number of winners in the lottery.
`record Ticket`: Defines a record called `Ticket` with a single field owner of type address. 
`Transition play()`: The play transition is the main entry point for the lottery. It creates a new `Ticket`.
`Finalize play()`: It randomly selects whether the ticket is a winner using `ChaCha::rand_bool()`.

## Run Guide

To run this program, run:
```bash
leo run play

or 

./run.sh
```

## Execute Guide

To execute this program, run:
```bash
leo execute play
```

Discord: Attak Helicopter#9164
