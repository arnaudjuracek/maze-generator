maze-generator
===

Agnostic maze generator &amp; solver in `JS`, using [depth first search hunt &amp; kill](http://weblog.jamisbuck.org/2011/1/24/maze-generation-hunt-and-kill-algorithm) and [breadth first search](https://en.wikipedia.org/wiki/Breadth-first_search) algorithms.

<sup>Also, check this a*maze*ing [paper](http://www.astrolog.org/labyrnth/algrithm.htm) on mazes in general.</sup>

### Usage

```js
const mazeGenerator = require('./../index.js');

let maze   = mazeGenerator.Maze(columns, rows, [start.x, start.y]).generate();
let solver = mazeGenerator.Solver(maze).solve();
```

See `example/` for a more advanced usage.

### License
MIT.
