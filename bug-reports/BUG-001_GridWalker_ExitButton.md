# BUG-001: "Exit The Grid" button does nothing

- App: Grid Walker Game (https://eviltester.github.io/TestingApp/games/buggygames/)
- Related test case: TC-GW-001
- Severity: High
- Status: Open
- Browser: Chrome, desktop
- Found on: 2026-11-03

## What happens

After walking through the grid, I clicked "Exit The Grid" and nothing changed. No message, no result. Because of this the game can't be finished, so you can't win or lose.

## Steps to reproduce

1. Open the Grid Walker Game
2. Click Generate
3. Click a cell in the left column to start
4. Move through the grid to the right side
5. Click "Exit The Grid"

## Expected

The game ends and shows if I won or lost.

## Actual

Nothing happens after the click.

## Screenshot

![bug screenshot](../img/bug-001-exit-button.png)

## Still to check

- Does it happen on every generated grid?
- Any error in the browser console (F12)?
- Same result in another browser?
