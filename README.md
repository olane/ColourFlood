First, [Wilson’s algorithm](/mbostock/11357811) generates a uniform [spanning tree](http://en.wikipedia.org/wiki/Spanning_tree) of the 960×500 canvas. (This is a computationally-expensive process and is run in a background worker.) Then, a breadth-first traversal of the spanning tree floods the canvas with color.

Compare this to [Prim’s algorithm](/mbostock/11337835).
