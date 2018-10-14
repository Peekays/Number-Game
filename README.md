# Number-Game
Build a game in Javascript with following rules -

  User has 1000 INR when he starts the game.
  Every try(click on start) is charged 100 INR.
  Game is over if user has less than 100 INR.
  Every try generates three random numbers, each random number is in 0-9 range.
  If all the numbers are odd/even (eg. 2 4 6), user gets 300 INR.
  If the numbers are in sequence with difference of 1 in any order (eg. 2 3 4 or 3 2 4 or 4 6 5), user gets 800 INR.
  If all the numbers are same (eg. 4 4 4), user gets 1000 INR.
  Else user gets no money.
  
  Important: Kindly follow the instructions
Please download this html template and don’t change the html structure in the file. You can use any javascript plugin you are familiar with.

1. Use (id="moneyLeft") for updating the INR
2. Use (id="randomNumbers") for updating the random numbers.
3. After the game is over
    a. Start button should be disabled.
    b. Change the Text to "Game Over" in div with id="message"
