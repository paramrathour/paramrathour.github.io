---
title: Game of Life
layout: page
---
The **Game of Life**, also known simply as **Life**, is a **cellular automaton** devised by the British mathematician **John Horton Conway** in 1970. It is a zero-player game, meaning that its evolution is determined by its initial state, requiring no further input. One interacts with the Game of Life by creating an initial configuration and observing how it evolves. It is **Turing complete** and can simulate a universal constructor or any other Turing machine.

<h2 align="center">Rules</h2>
The universe of the Game of Life is an infinite, two-dimensional orthogonal grid of square cells, each of which is in one of two possible states, live or dead, (or populated and unpopulated, respectively). Every cell interacts with its eight neighbours, which are the cells that are horizontally, vertically, or diagonally adjacent. At each step in time, the following transitions occur:
- Any live cell with two or three live neighbours survives.
- Any dead cell with three live neighbours becomes a live cell.
- All other live cells die in the next generation. Similarly, all other dead cells stay dead.

<h2 align="center">Examples of patterns</h2>
Many different types of patterns occur in the Game of Life, which are classified according to their behaviour. Common pattern types include: **still lifes**, which do not change from one generation to the next; **oscillators**, which return to their initial state after a finite number of generations; and **spaceships**, which translate themselves across the grid.
<h2 align="center">Still Lifes</h2>

<table class="table-wrapper" style="text-align:center;">
  <tr>
    <td>Block</td>
     <td>Beehive</td>
     <td>Loaf</td>
     <td>Boat</td>
     <td>Tub</td>
  </tr>
  <tr>
    <td><span class="image fit"><img src="https://paramrathour.github.io/Scientific-Computing/Cellular%20Automaton/Game%20of%20Life/GIFs/Block.gif"></span></td>
    <td><span class="image fit"><img src="https://paramrathour.github.io/Scientific-Computing/Cellular%20Automaton/Game%20of%20Life/GIFs/Beehive.gif"></span></td>
    <td><span class="image fit"><img src="https://paramrathour.github.io/Scientific-Computing/Cellular%20Automaton/Game%20of%20Life/GIFs/Loaf.gif"></span></td>
    <td><span class="image fit"><img src="https://paramrathour.github.io/Scientific-Computing/Cellular%20Automaton/Game%20of%20Life/GIFs/Boat.gif"></span></td>
    <td><span class="image fit"><img src="https://paramrathour.github.io/Scientific-Computing/Cellular%20Automaton/Game%20of%20Life/GIFs/Tub.gif"></span></td>
  </tr>
</table>

<h2 align="center">Oscillators</h2>

<table class="table-wrapper" style="text-align:center;">
  <tr>
    <td>Blinker</td>
     <td>Toad</td>
     <td>Beacon</td>
     <td>Pulsar</td>
  </tr>
  <tr>
    <td><span class="image fit"><img src="https://paramrathour.github.io/Scientific-Computing/Cellular%20Automaton/Game%20of%20Life/GIFs/Blinker.gif"></span></td>
    <td><span class="image fit"><img src="https://paramrathour.github.io/Scientific-Computing/Cellular%20Automaton/Game%20of%20Life/GIFs/Toad.gif"></span></td>
    <td><span class="image fit"><img src="https://paramrathour.github.io/Scientific-Computing/Cellular%20Automaton/Game%20of%20Life/GIFs/Beacon.gif"></span></td>
    <td><span class="image fit"><img src="https://paramrathour.github.io/Scientific-Computing/Cellular%20Automaton/Game%20of%20Life/GIFs/Pulsar.gif"></span></td>
  </tr>
</table>

<h2 align="center">Spaceships</h2>

<table class="table-wrapper" style="text-align:center;">
  <tr>
    <td>Glider</td>
     <td>Light Weight Spaceship</td>
     <td>Middle Weight Spaceship</td>
     <td>Heavy Weight Spaceship</td>
  </tr>
  <tr>
    <td><span class="image fit"><img src="https://paramrathour.github.io/Scientific-Computing/Cellular%20Automaton/Game%20of%20Life/GIFs/Glider.gif"></span></td>
    <td><span class="image fit"><img src="https://paramrathour.github.io/Scientific-Computing/Cellular%20Automaton/Game%20of%20Life/GIFs/Light Weight Spaceship.gif"></span></td>
    <td><span class="image fit"><img src="https://paramrathour.github.io/Scientific-Computing/Cellular%20Automaton/Game%20of%20Life/GIFs/Middle Weight Spaceship.gif"></span></td>
    <td><span class="image fit"><img src="https://paramrathour.github.io/Scientific-Computing/Cellular%20Automaton/Game%20of%20Life/GIFs/Heavy Weight Spaceship.gif"></span></td>
  </tr>
</table>

<h2 align="center">Glider Gun</h2>

<table class="table-wrapper" style="text-align:center;">
  <tr>
    <td>Gosper Glider Gun</td>
  </tr>
  <tr>
    <td><span class="image fit"><img src="https://paramrathour.github.io/Scientific-Computing/Cellular%20Automaton/Game%20of%20Life/GIFs/Gosper Glider Gun.gif"></span></td>
  </tr>
</table>

### References

- [Wikipedia](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life)
- [Scholarpedia](http://www.scholarpedia.org/article/Game_of_Life)
- Code of above patterns are available in this [repository](https://github.com/paramrathour/Scientific-Computing/tree/main/Cellular%20Automaton/Game%20of%20Life). You can try simulating by changing values but [this](https://bitstorm.org/gameoflife/) may be better.
- **Game of Life** simulated by **Game of Life**, Watch [here](https://youtu.be/D6aP9S9rEQk)