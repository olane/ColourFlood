First, Wilson’s algorithm generates a uniform [spanning tree](http://en.wikipedia.org/wiki/Spanning_tree) of the 960×500 canvas. (This is a computationally-expensive process and is run in a background worker.) All pixels outside a bounding circle are culled from the tree. Then, a breadth-first traversal of the spanning tree floods the canvas with color.

[Demo](http://oli-lane.co.uk/colourflood/)