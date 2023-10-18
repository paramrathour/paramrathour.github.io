---
title: Langton's Ant
layout: page
---
**Langton's ant** is a two-dimensional universal **Turing machine** with a very simple set of rules but complex emergent behavior. It was invented by Chris Langton in 1986 and runs on a square lattice of black and white cells.
<h2 align="center">Rules</h2>
Squares on a plane are colored variously either black or white. We arbitrarily identify one square as the "ant". The ant can travel in any of the four cardinal directions at each step it takes. The "ant" moves according to the rules below:

- At a white square, turn 90° clockwise, flip the color of the square, move forward one unit
- At a black square, turn 90° counter-clockwise, flip the color of the square, move forward one unit
- Langton's ant can also be described as a cellular automaton, where the grid is colored black or white and the "ant" square has one of eight different colors assigned to encode the combination of black/white state and the current direction of motion of the ant.

<table style="text-align:center;">
  <tr>
    <td>Animation of first 30000 steps of Langton's ant</td>
  </tr>
  <tr>
    <td><span class="image fit"><img src="{{ site.url }}/Scientific-Computing/Cellular%20Automaton/Langton's%20Ant/Langton's%20Ant.gif"></span></td>
    </tr>
</table>

### References

- [Wikipedia](https://en.wikipedia.org/wiki/Langton%27s_ant)
- Code of above patterns are available in this [repository](https://github.com/paramrathour/Scientific-Computing/tree/main/Cellular%20Automaton/Langton's%20Ant). You can try simulating by changing values