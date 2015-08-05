# Turn Based Game

## Description
Create a Final Fantasy style game

## Objectives

### Learning Objectives

After completing this assignment, you should
- Understand how to delegate responsibility of objects using events
- Understand how and why to sketch a user flow
- Understand how and why to identify features
- Understand how and why to use prototypical inheritance and `_.extend`

### Performance Objectives

After completing this assignment, you be able to effectively use

* Backbone.Events
* `_.extend`

## Details

### Deliverables

* A set of sketches (either on paper or digital) of the screens of your app
  - Character Select
  - Battle Screen (with attack buttons)
  - Game End Screen
* A list of features within your Github issue broken down into small steps
* A full project with customized build tools to fit your project
* A build on Github Pages with link in your Issue

### Requirements

* No JSHint warnings or errors

## Normal Mode
You will be building a turn based battle game. If you're familiar with older
video games, think of Pokemon or Final Fantasy. The UI can be very very basic,
just some headings for names and info, a dropdown, and a couple of buttons. If
you have no idea what any of this means, read through
[this](http://en.wikipedia.org/wiki/Gameplay_of_Final_Fantasy#Parties_and_battles)
and/or [watch this](http://youtube.com/watch?v=MNmKNhm-1Js).
For a more simple approach ala Pokemon, look at this ![Pokemon Battle](http://stream1.gifsoup.com/view1/3624865/pokemon-battle-test-o.gif).

- There should be multiple enemy types.
- The enemy type should be randomly generated.
- There should be multiple player types.
- You should be able to select the player type from a dropdown.
- The gameplay should go back and forth between an enemy and the player, each
  inflicting damage on the other when they launch a successful attack.
- The player should manually select the "Fight" action to attack.
- The enemy should automatically attack when it is its turn.
- You should use constructors and prototypes for the players and enemies.
- The player's health should be visible.
- The enemies health may be visible, at your discretion.
- After either character is killed: show a game end screen

## Hard Mode
- The player should be able to click "Start Over" on the game end screen
- Show damage when dealt
- The player should be able to either "Fight" or "Use Magic", or some similar
  setup. Each player type should have different types of attack and/or magic. (check the `weapons` and `getAttackStrength` from our example in class)
- Give the player the ability to use items, such as items that regain health or
  increase attack.
- Make a party of players, rather than just one (a la Final Fantasy). The game
  play would cycle between Player 1 -> Enemy -> Player 2 -> Enemy, etc.
- Implement "ailments". E.g. being poisoned: makes you weaker, being put to sleep: makes you skip your turn.

## Notes

- Feel free to use separate JavaScript files and `broccoli-concat` to break your project into more manageable chunks rather than a single `app.js`.
- Handlbars is recommended to turn Javascript objects into HTML, but you may use raw jQuery or Javscript strings.

## Additional Resources

- Artwork is not required, but if you'd like to include artwork, [this might
  help](http://opengameart.org). Maybe [this too](http://open.commonly.cc). Get
  your game working before you introduce artwork. If you have a beautiful page
  that doesn't work, it will be considered an incomplete assignment.
