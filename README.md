# Chess_Pieces
Repository of SVG Chess Piece Sets

## Dependencies
brew install rsvg-convert
## Instructions to make ScidvsPC Compatible Piece Sets from SVG Images
Use the script entitled "MkScidPieces_fromSVG" in the repository. </br>

./MkScidPieces_fromSVG [DirectoryName] </br>
If your pieces are in a Directory named Alpha (i.e. the name of the piece type): </br>
./MkScidPieces_fromSVG Alpha </br>

Save the output into a text file, and save this into usr/{name of User}/.scidvspc/pieces (note that you need to create the pieces directory). 

## Links to Chess Piece Images in SVG Format
1. [Pychess](https://github.com/pychess/pychess/tree/master/pieces)
2. [Raptor](https://github.com/Raptor-Fics-Interface/Raptor/tree/master/raptor/resources/set) (Majority in png format, but a few have svg format as well)
3. [Lichess API](https://github.com/ornicar/lila/tree/master/public/piece)
4. [Aquarium Steel & Wood Set](http://rybkaforum.net/cgi-bin/rybkaforum/topic_show.pl?tid=15257) by Greg Mallen
5. [Python-chess](https://github.com/niklasf/python-chess/blob/master/chess/svg.py#L34)
