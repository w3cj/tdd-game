# The Ultimate Tester and the Lazy Implementor

One of the hardest parts about testing is coming up with the right tests. This is a simple pairing game based on test-driven development to help you practice writing _better_ tests.

## The idea is simple.

The **Ultimate Tester's** goal is to trick the **Lazy Implementor** into writing _good code_ by writing _good tests_.

The **Lazy Implementor's** goal is to make the tests pass by writing a function with as little code as possible that does not actually solve the whole problem...

### Here are some ground rules:

* The tester can only write one test at a time
* Each test written must fail before the implementor's turn begins
* The implementor's turn continues until all tests pass
* If the implementor's function exceeds 17 lines, the code must be refactored (Feel free to create functions above the `module.exports`)

Check out the example test and implementation files in the example folder to see how something like this might proceed.

### How to Play

1. Pair Up.
2. Assign Roles (Implementor and Tester).
3. Set a timer for 25 minutes.
4. Begin Game.
5. After timer is up, or after the implementor can no longer trick the tester:
  * Swap Roles.
  * Choose to continue the same problem, or choose a [new one](https://github.com/gSchool/DailyProgrammer).
6. Repeat.

### Getting Started

Install eslint to catch linter errors _before_ running the exercise:

[https://atom.io/packages/linter-eslint](https://atom.io/packages/linter-eslint)

#### Set up the game:
```bash
$ npm install
```

### Run the example:
```bash
$ npm run example
```

### Run the game:
```bash
$ npm run game
```

This game was created by [g15 student skuttleman](https://github.com/skuttleman/tdd-game)
