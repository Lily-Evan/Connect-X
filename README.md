# Connect-X
🤖 ConnectX Agent – Kaggle Simulation Competition
This repository contains my agent for the ConnectX Simulation Competition on Kaggle – a game AI challenge where the objective is to get a certain number of checkers in a row (horizontally, vertically, or diagonally) before your opponent.

The agent follows simple but effective logic:

First, it checks for a winning move and plays it if available.

If not, it tries to block the opponent's winning move.

Otherwise, it selects a random valid column to play.

The code is written entirely in Python and submitted as a submission.py file, compatible with the Kaggle simulation framework.

🏆 My Result
Out of 180 participants, I achieved 45th place on the public leaderboard during the beta phase of the competition.

🚀 How to Run Locally
Install the Kaggle environments package:

bash
Αντιγραφή
Επεξεργασία
pip install kaggle-environments
Run the environment:


from kaggle_environments import make
env = make("connectx", debug=True)
env.run(["submission.py", "random"])
env.render(mode="ipython")
📌 Goals
Build a solid baseline agent with rule-based logic.

Explore strategies like Minimax or Reinforcement Learning in future iterations.

🧠 About the Competition
Kaggle’s Simulation Competitions are a new format where agents compete directly under rule-based scenarios, rather than being scored by a fixed evaluation metric. It’s a great way to explore decision-making AI and reinforcement learning.
