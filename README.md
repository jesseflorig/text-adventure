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
  name: String
  inventory: [Slot]
}
```

## NPC
Collection of NPCs
```javascript
{
  name: String
  descriptions: [Description]
  dialogues: [Dialogue]
  reaction: [Reactions]
}
```

## Room
Collection of rooms
```javascript
{
  name: String
  desc: String
  doors: [Door]
}
```

## Item
Collection of items
```javascript
{
  name: String
  descriptions: [Description]
  actions: [Action]
}
```
