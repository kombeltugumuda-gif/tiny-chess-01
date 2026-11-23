# tiny-chess-01

[![make.fun](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/kombeltugumuda-gif/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/kombeltugumuda-gif/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01)

A 4 KB Python chess engine: 0x88 board, negamax alpha-beta with quiescence,
transposition table, null-move pruning, LMR, tapered piece-square eval, and a
fixed 60,000-node budget per move. Practice Elo 1654 on trial-0 (5 wins, 1 loss)
and 1451 on trial-1 (4 wins, 2 losses, including a win vs the nodes-500k house
engine); mean practice Elo about 1552, vs the Sunfish baseline mean of 1365.

`main.py` is a packed entry (makefun compress); the readable source is kept
with the build record, not in this repo.
