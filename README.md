# Snakes & Ladders — Editable Questions

## How to Use

1. Download the `index.html` file.
2. **Save the file as type: All Files, encoding: UTF-8**.
3. Open the file in any modern web browser (Chrome, Edge, Firefox).
4. Choose the number of players before starting the game.
5. Click **Start Game** to begin.
6. Click **Roll Dice** to move your pawn.
7. When you land on a question square, a pop-up will appear. Answer correctly to move forward, or skip/wrong to move backward.
8. Pawns automatically climb ladders and slide down snakes.
9. The first player to reach square 100 wins!

## Editing Questions

- Open the `index.html` file in a code editor.
- Locate this section:

```javascript
const questionSquares = {
  5: { q: "Area of triangle? (1/2*base*height)", a: "1/2*base*height" },
  13: { q: "Area of rectangle? (length*width)", a: "length*width" },
  27: { q: "Area of circle? (pi*r^2)", a: "pi*r^2" },
  44: { q: "Perimeter of square? (4*side)", a: "4*side" },
  65: { q: "Volume of cube? (side^3)", a: "side^3" },
  72: { q: "Square root of 49?", a: "7" },
  88: { q: "11+9?", a: "20" }
};
