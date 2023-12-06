<<<<<<< HEAD
## Summary

In this course, I employ TensorFlow framework to build several Neural Networks and explore more advanced techniques like Natural Language Processing and Reinforcement Learning. I also dive into Neural Networks, and learn the principles behind how deep, recurrent, and convolutional Neural Networks operate.

### Projects:

  - **[Rock Paper Scissors]**


### How to test these:

  1. For each project, download the `py files` (x3) in their respective py files folders and also the csv files.
  2. Save them all in the same directory/folder.
  3. Open a terminal in VS Code - or any other IDE - and run the `main.py` file ("python main.py")
  
=======
## Rock Paper Scissors

For this challenge, you will create a program to play Rock, Paper, Scissors. A program that picks at random will usually win 50% of the time. To pass this challenge your program must play matches against four different bots, winning at least 60% of the games in each match.

In the file RPS.py you are provided with a function called player. The function takes an argument that is a string describing the last move of the opponent ("R", "P", or "S"). The function should return a string representing the next move for it to play ("R", "P", or "S").

A player function will receive an empty string as an argument for the first game in a match since there is no previous play.

The file RPS.py shows an example function that you will need to update. The example function is defined with two arguments (player(prev_play, opponent_history = [])). The function is never called with a second argument so that one is completely optional. The reason why the example function contains a second argument (opponent_history = []) is because that is the only way to save state between consecutive calls of the player function. You only need the opponent_history argument if you want to keep track of the opponent_history.

_Hint: To defeat all four opponents, your program may need to have `multiple strategies` that change depending on `the plays of the opponent`._

### Development

Do not modify RPS_game.py. Write all your code in RPS.py. For development, you can use main.py to test your code.

The file main.py imports the game function and bots from RPS_game.py.

To test your code, play a game with the play function. The play function takes four arguments:

- two players to play against each other (the players are actually functions)
- the number of games to play in the match
- an optional argument to see a log of each game. Set it to True to see these messages.

```python
play(player1, player2, num_games[, verbose])
```

For example, here is how you would call the function if you want player and quincy to play 1000 games against each other and you want to see the results of each game:

```python
play(player, quincy, 1000, verbose=True)
```

### Testing

The unit tests for this project are in test_module.py. We imported the tests from test_module.py to main.py for your convenience.The tests will therefore run automatically whenever you run the file `test_module.py`

### Submitting

Copy your project's URL and submit it to freeCodeCamp.

Sourced from : https://www.freecodecamp.org/learn/machine-learning-with-python/machine-learning-with-python-projects/rock-paper-scissors
>>>>>>> 19a846f70f623edb4d6839cb0cd1545189a6b368
