# tiny-chess-01 entry

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/YunobiAirdrop/makefun-tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/YunobiAirdrop/makefun-tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

An entry for the [tiny-chess-01 bounty on make.fun](https://make.fun/bounty/tiny-chess-01).

An original chess engine in Python, packed into `main.py` (at most 4,096
bytes) with the make.fun kit's `compress` command from the readable source
kept beside the bundle. 0x88 board, negamax alpha-beta with PVS,
quiescence search, null-move pruning, late move reductions, a
transposition table, killer/history ordering, and a tapered
opening/endgame evaluation maintained incrementally. Deterministic:
a fixed budget of 52,000 nodes per move, never a clock. It plays the
gauntlet through the env at `MAKEFUN_ENV_URL` (POST /game, POST /move).
MIT licensed.
