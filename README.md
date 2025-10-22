# Chess

A two-player chess game implementation for local play in the browser.

## Features

- Full chess board with standard piece movement
- Two-player local gameplay (no AI)
- Move validation for all piece types
- Visual indicators for selected pieces and valid moves
- Turn-based gameplay with status display
- New game/reset functionality
- Fully responsive design

## Usage

Open chess.html in any modern web browser. No server or dependencies required.

### How to Play

1. Click on a piece to select it
2. Valid moves will be highlighted
3. Click on a highlighted square to move
4. Players alternate turns (White starts first)
5. Click "New Game" to reset the board

### Piece Movement

- Pawns: Move forward one square, two on first move, capture diagonally
- Rooks: Move horizontally or vertically any distance
- Knights: Move in L-shape (2+1 squares)
- Bishops: Move diagonally any distance
- Queen: Move in any direction any distance
- King: Move one square in any direction

## Technical Details

- Single HTML file with embedded CSS and JavaScript
- Pure JavaScript implementation with no external libraries
- Unicode chess piece symbols for clean rendering
- Path validation prevents jumping over pieces
- Zinc theme with minimal design aesthetic

## Limitations

- No castling, en passant, or pawn promotion
- No check/checkmate detection
- No move history or undo functionality
- Local play only (no online multiplayer)

## Browser Compatibility

Works in all modern browsers with JavaScript enabled.
