# tiny-chess-01 entry

An original chess engine in Python, packed into `main.py` (at most 4,096
bytes) with the make.fun kit's `compress` command from the readable source
kept beside the bundle. 0x88 board, negamax alpha-beta with PVS,
quiescence search, null-move pruning, late move reductions, a
transposition table, killer/history ordering, and a tapered
opening/endgame evaluation maintained incrementally. Deterministic:
a fixed budget of 52,000 nodes per move, never a clock. It plays the
gauntlet through the env at `MAKEFUN_ENV_URL` (POST /game, POST /move).
MIT licensed.
