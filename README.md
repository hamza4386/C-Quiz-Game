🎮 C++ Console-Based Quiz Game

An interactive console-based quiz system developed in C++, designed to reinforce programming fundamentals while offering a fun, gamified experience. The game features multiple categories, difficulty levels, lifelines, scoring streaks, multiplayer mode, and persistent data tracking.

📖 Project Overview

This project simulates a real-world quiz environment using modular programming, arrays/structs, file handling, and algorithmic logic. Users can challenge themselves with randomized questions or compete with a friend in 2-player hotseat mode. Administrators can securely manage question banks, and players can track performance through leaderboards and review logs.

✨ Key Features
⚙️ Core System

Main Menu: Intuitive interface with Start Quiz, View Leaderboard, and Exit options.

Input Validation: Prevents crashes by handling invalid inputs.

File Handling: Questions, high scores, and logs are persistent.

🕹️ Game Modes

Single Player: Challenge yourself with 10-question quizzes.

2-Player Mode: Compete against a friend turn-by-turn.

Admin Panel: Securely add or edit questions in the database.

📊 Performance & Tracking

Leaderboard: Displays top 5 scores by player name, date, and difficulty.

Streak Bonuses: Rewards consecutive correct answers.

Review Mode: Highlights incorrect answers with the correct solution.

Activity Logs: Records sessions, scores, and attempts automatically.

📝 Gameplay Rules & Scoring

Questions per Session: 10

Time Limit: 10 seconds per question

Difficulty Levels & Penalties:

Level	Correct	Wrong
Easy	+1	-2
Medium	+1	-3
Hard	+1	-5

Lifelines: 50/50, Skip, Swap, Time Extension (usable once per session).

🛠️ Technical Highlights

Data Structures: Arrays and text files for questions, scores, and logs.

Algorithms: Randomization for questions, sorting for leaderboard, timers for question limits.

Modular Design: Separate functions for loading questions, calculating scores, and updating leaderboard.

🔗Written By:

Muhammad Hamza

