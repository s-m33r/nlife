## nlife - Conway's Game Of Life in the terminal

```
nlife - Conway's Game Of Life with ncurses

arguments:
    --alive=<value>   | set the character used for living cells
    --dead=<value>    | set the character used for dead cells

    --delay=<seconds> | set the delay between generations
    --help            | print this help text

source:
    https://github.com/s-m33r/nlife
```

Learn more about [the game of life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life).  

Rules:  
- Any live cell with fewer than two live neighbours dies, as if by underpopulation.  
- Any live cell with two or three live neighbours lives on to the next generation.  
- Any live cell with more than three live neighbours dies, as if by overpopulation.  
- Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.  

Live cells are represented by `alive_chr` (default `0`) and dead cells by empty space.  

A radom map is initialized across the entire terminal and the simulation runs from there, endlessly!  

