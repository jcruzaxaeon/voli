

# VOLI 0.0.0
> [!NOTE] Since the current format is essentially a white-space delimited format any entries that include "white-space" must be surrounded by double-quotes (").  Use `camelCase` where possible.

```omni
Matches
   wednesday1 = {date: "March 6, 2024"}
      x  title                 n     unit      user   detail
      _  SKD                   1     hr        ax     
      _  Defrag[G]             1     hr        ax
      _  Project               1     hr        ax
      _  Tea                   15    min       ax     "Includes light reading"
      _  Sequencing            30    min       ax
      x  VOLI                  5     min       ax     "Push initial `VOLI` commit to GitHub"
      _  Read                  30    min       nn
   tuesday1 = {date: "March 5, 2024"}
      x  title                 n     unit      user   detail
      x  Sample                1     attempt   ax     "Try the sample"
      x  Sample                1     hr        nn     "Try the sample"

matchData
   date              [userAnte]
   "March 6, 2024"   ax: $5,
                     nn: $1,
   "March 5, 2024"   ax: $5,
                     nn: $1,

Results
   change   total    user
   0        100      ax
   0        100      nn

 Envelopes
   total    goal     user
   0        gold     ax
   0        choco    nn
```
- Based on the `.TBL`, and `.TBLS` format.
