# The gallery based on the CSS grid layout.

The columns are set in grid tracks (the grid is explicit).
The rows are built with implicit grid so the layout isn't structured for fixed number of pictures.
```
.grid-layout {
  grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
  grid-auto-rows: 1fr;
  grid-auto-flow: dense;
}
```
* `auto-fill` directs browser to place as many tracks onto the grid as it can fit
* `dense` value makes items to fill gaps in the grid even if it changes the order of items


