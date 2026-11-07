# The Rubik's Cube and Its Higher Cousins as Graphs

An interactive toy that turns the Rubik's cube into a graph, then follows the same idea into higher dimensions.

## The idea
- Every **sticker** is a dot.
- Every **slice** of the cube is a closed **loop of 12 dots**.
- Turning a slice simply slides the dots around their loops.

The same picture works for the 4D cube (3⁴) and beyond, all the way to 3⁷.

| Puzzle | Stickers | Loops | Edges | Loops per sticker |
|---|---|---|---|---|
| 3³ (the ordinary cube) | 54 | 9 | 108 | 2 |
| 3⁴ (4D) | 216 | 54 | 648 | 3 |
| 3⁵ | 810 | 270 | 3,240 | 4 |
| 3⁶ | 2,916 | 1,215 | 14,580 | 5 |
| 3⁷ | 10,206 | 5,103 | 61,236 | 6 |

In n dimensions: stickers = 2n·3ⁿ⁻¹, loops = C(n,2)·3ⁿ⁻², and each sticker lies on n−1 loops.

## How to play
1. Pick a puzzle: 3³ to 3⁷.
2. Click any dot to select a sticker. Its loops are highlighted.
3. Choose a plane and a layer, then press **Turn**.
4. Press **Scramble**, then try to get every cell back to one colour.
5. Switch to **3D model** (3³ and 3⁴) to see the puzzle itself. On the 3³, drag a sticker to turn it, or use the keys R L U D F B M E S (hold Shift to turn the other way).

Your progress is saved in your browser.

## License
MIT
