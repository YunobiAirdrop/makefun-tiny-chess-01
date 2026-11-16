# makefun-tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/YunobiAirdrop/makefun-tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/YunobiAirdrop/makefun-tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A deterministic chess engine in a single `main.py` of at most 4,096 bytes: a
0x88 board, negamax alpha-beta search with quiescence, a transposition table,
killer-move ordering and piece-square-table evaluation, iteratively deepened
to a fixed node budget (never a clock), packed as an lzma payload with its
unpacker. It plays the whole gauntlet through the env at `MAKEFUN_ENV_URL`
and makes no model calls.

## Run it

```sh
MAKEFUN_ENV_URL=<env-url> python3 main.py
```

---
<sub>Entered on [make.fun](https://make.fun/?ref=zqdg0kc1&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
