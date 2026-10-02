# State Diagram — Catch the Falling Stars

START
  | Start Game
  v
PLAYING <----> PAUSED
  |              |
  |              | Resume
  |              v
  |----------- PLAYING
  |
  +--> WIN (score reaches 10)
  |
  +--> LOSE (3 stars missed)
          |
          | Restart / Enter
          v
        PLAYING

Progression:
- Catch a star = +1 score.
- Every 5 points increases the level.
- Higher levels make stars fall faster.
- 3 misses = LOSE.
- 10 points = WIN.
- Restart resets the current run.
- Highest score is saved in browser localStorage.
