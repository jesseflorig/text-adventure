# text-adventure.js
A text adventure javascript library.

## Game
A game is initialized with an `input`, `output`, and `adventure`:
```javascript
input     // Function that allows the game to receive input from the user
output    // Function that allows the game to return respond to the user
adventure // The contents of the adventure
```

## Player
The player state
```javascript
{
  name: String,
  inventory: [
    { 
      name: String,
      qty: Number,
    }
  ]
}
```

## NPC


## Room
