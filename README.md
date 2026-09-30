# NFL Ranking Engine

**Input:** Every completed game this season: who played, who won, where it was played, and the final score (points scored, points allowed, margin of victory).

**What the math does:** Turns each game into an equation, so the whole season becomes a system of equations with one unknown rating per team. Solving it gives ratings that account for who each team actually played and how much they won or lost by.

**Output:** A rating and a 1–32 rank for every team.

**How I'll test it:** Compare my rankings to the NFL standings and expert power rankings, then predict each week's games before kickoff and track how often I'm right. The toughest benchmark is the Vegas spread, so I'll compare against that too.
