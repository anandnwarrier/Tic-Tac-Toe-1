## Reinforcement learning based Tic-Tac-Toe playing agent

#### This is a simple C++ implementation of a tic-tac-toe playing agent bases on Q Learning. We maintain a table of Q values for every (state, action) pair in 'table.txt'. Actions are then sampled via an epsilon greedy policy. We update our Q table by updating Q values for the (state, action) along the sampled trajectory depending on whether the game was won or lost.
#### </br>

### Running the Code
#### To play a game against the agent, run:
#### ```./tictactoe.cpp```</br>

#### Note: The agent always starts and plays with 'X'. You play 'O'.
