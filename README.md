# Chess Time Management

My chess time management has been horrific. Just about all the games I've been losing are due to running out of time. Winning a game on time is unheard of. I'm slower than everyone.

I built this tool to see where it's all going wrong and where I need to improve most. It's based on the advice from this video:  
https://www.youtube.com/watch?v=wdwxErflrY0

> **Set time goals.** Establish a loose schedule for how much time to spend in each phase of the game:  
> 15% for the opening, 45% for the middlegame, 40% for the endgame.

This script pulls your last 5 rapid games (10+0) from Chess.com and shows:
- A time-remaining graph for each move, overlaid across games
- A smooth S-curve target pace that aligns with the phase goals
- A bar chart showing your actual time spent per phase vs. target
- A diff plot highlighting which phase you're over or under spending time in

Just a simple tool to visualize bad habits and fix my worst issue: poor time management.
