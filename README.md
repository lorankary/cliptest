# cliptest

This is a test for proof of concept to see if the Path2D object can be used
as in the game Mega Miner to mask off parts of the canvas that have
not yet been visited by the player.

Launch index.html and move the mouse around in the canvas to reveal
more and more of the underlying white space.

Conclusion: it's not perfect but may be good enough for our purposes.

The Path2D object is considered experimental but is supported
on Chrome, Firefox and Safari.

x_index.html started as my translate-and-rotate test but with added
clip paths from corner to corner.  No problem if only one diagonal
clip path is drawn but undesirable results when both diagonal
clip paths are added.
