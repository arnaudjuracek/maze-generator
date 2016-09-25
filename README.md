<h1 align="center">:runner::question: maze-generator</h1>
<h3 align="center">Agnostic maze generator &amp; solver in `JS`, using [depth first search hunt &amp; kill](http://weblog.jamisbuck.org/2011/1/24/maze-generation-hunt-and-kill-algorithm) and [breadth first search](https://en.wikipedia.org/wiki/Breadth-first_search) algorithms.</h3>

<div align="center">
  <sup>Also, check this a*maze*ing [paper](http://www.astrolog.org/labyrnth/algrithm.htm) on mazes in general.</sup>
  <!-- License -->
  <a href="https://raw.githubusercontent.com/arnaudjuracek/xy/master/LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square" alt="License" />
  </a>
</div>
===

### Installation
```sh
npm install --save arnaudjuracek/maze-generator
```

### Usage

```js
const mg = require('maze-generator');

let maze   = mg.Maze(columns, rows, [start.x, start.y]).generate();
let solver = mg.Solver(maze).solve();
```

See `example/` for a more advanced usage.

### License
MIT.
