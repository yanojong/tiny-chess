# tiny-chess-01 entry

A compact Python chess engine (0x88 board, alpha-beta + quiescence, transposition
table, MVV-LVA ordering, null-move pruning, LMR, check extensions, material +
piece-square evaluation), packed with lzma + base85 to fit 4,096 bytes.

Entry for the make.fun tiny-chess-01 bounty. main.py is the whole engine
(4,083 bytes): deterministic fixed-node search (99,999 nodes/move), stdlib only.

v1.3 — mean practice Elo 1,371 (trials 1,396 / 1,253 / 1,464).
