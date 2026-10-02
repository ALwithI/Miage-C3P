 # Weekly Report 04

## Glauriel

**What I Learned:**

## Tien

**What I Learned**

* **Avoid returning `nil**`: It forces constant null checks everywhere in the client code.
* **Embrace recursion**: In a file system, a directory can simply delegate tasks to its children (using `self subclassResponsibility`).
* **Design Patterns**: Got hands-on practice implementing the **Composite** and **Visitor** patterns.

**Exercises & Projects**

**[Chess Game](https://github.com/nttt1400/Chess)**
* Rendered chess pieces with side-specific colors (and also chess squares) (`MyChessSquare`).
* Pawn mouvement and capture (`MyPawn`)
* Filtered out moves that leave your king in check so 2 players can play (`MyPiece`).
* Fixed a bug so the king can now capture unprotected enemy pieces (`MyKing`).
* Enforced strict turn to other player after each move (`MyChessGame`).
* Visual indicators now only show up for legal moves (`MyUnselectedState`).

**[FileSystem-Composite](https://github.com/nttt1400/FileSystem-Composite)**

* Built out the package using the Composite design pattern, along with a few extensions.