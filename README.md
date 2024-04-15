My final project for CPSC 101 was a tic-tac-toe game built with PyGame using a coin flip, buttons, and bots.

    Libraries Used

1.) Random (built into Jupyter)

Generates random numbers that would be used for bots and the coin.

2.) Time (built into Jupyter)

Delays code, so visuals stay longer.

3.) PyGame (pip install pygame or pip3 install pygame)

PyGame is a popular library for game creation, and a suggestion from my instructor. I used its UI systems and button features for a more engaging experience. Learn more at [https://www.pygame.org/wiki/about](url)

    Basic Description
After running all cells, a PyGame window will open with four buttons for game mode selection (two-player, easy, medium, and hard). Each takes the player to a coin flip, except for the former, where the player will pick heads or tails to decide who plays first. All modes now display a game grid. In the two-player mode, each player will alternate turns, which changes the symbol to keep the player's moves separate. 
Other modes alternate between the player and a bot with varying degrees of difficulty: easy is a mindless bot playing randomly, medium has the ability to block the player from winning, and hard can play a winning move and block its opposition. Once a condition to end the game is met, the window transitions to the end screen with two buttons allowing another game or closing the program.

    The Board
Though the user sees a grid, information is stored in a list. A program loops through columns and rows to determine whether someone has won, and bots to decide relevant positions. I implemented safeguards that catch players or bots trying to play in spots already occupied.

    Future Work
I previously created a rock, paper, scissors (lizard, spock) algorithm that could be incorporated as an alternative to the coin toss. This would provide more dynamic gameplay, and retain a player's attention for longer.

During my presentation, a classmate suggested I add a scoreboard. I loved this idea, and may decide to make this addition as a 'scoreboard' button found in the endscreen. It would ideally keep track of all wins, losses, and ties with each unique bot and display a win-loss ratio (excluding ties).

Below my code, you can find markdown cells providing more code centered changes I would like to have made.

    Buttons
Having minimal Python and PyGame experience made creating buttons very difficult. Thankfully, I found a video that greatly assisted my understanding of this feature [https://www.youtube.com/watch?v=G8MYGDf_9ho&t=137s](url)
