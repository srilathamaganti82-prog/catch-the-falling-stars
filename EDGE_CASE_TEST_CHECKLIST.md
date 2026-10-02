# Edge-Case Test Checklist

| Test | Expected result |
|---|---|
| Start from START | Enters PLAYING |
| Pause during PLAYING | Enters PAUSED and stops movement |
| Resume from PAUSED | Returns to PLAYING |
| Press P | Toggles pause/resume |
| Catch a star | Score increases by 1 |
| Reach 5 points | Level increases |
| Reach 10 points | WIN appears |
| Miss 3 stars | LOSE appears |
| Restart after WIN | New run starts at score 0 |
| Restart after LOSE | New run starts at score 0 |
| Refresh/reopen page | High score remains |
| Move left at edge | Player stays inside screen |
| Move right at edge | Player stays inside screen |
