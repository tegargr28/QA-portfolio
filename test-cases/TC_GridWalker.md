# Test cases: Grid Walker Game

App: https://eviltester.github.io/TestingApp/games/buggygames/
Browser: Chrome

The goal of the game is to walk through the grid from left to right, step on each square only once, and leave with a total score of zero.

| ID | Scenario | Steps | Expected | Actual | Status |
| -- | -------- | ----- | -------- | ------ | ------ |
| TC-GW-001 | Exit the grid after finishing a walk | Generate, click left column cell, walk to the right, click Exit The Grid | Game ends and shows a result | Nothing happens | Failed |
| TC-GW-002 | Start from the left column | Generate, click a cell in the left column | Score, moves and position update | | Not tested |
| TC-GW-003 | Click a middle cell before starting | Generate, click a cell in the middle | Game doesn't start | | Not tested |
| TC-GW-004 | Step on the same square twice | Start, move to a square, go back to it | Move is not allowed | | Not tested |
| TC-GW-005 | Move with arrow keys | Start, press the arrow keys | Position changes in that direction | | Not tested |
| TC-GW-006 | Press Generate in the middle of a game | Start, move a few squares, press Generate | New grid, score and moves reset | | Not tested |
