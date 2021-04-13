# a4-howgoodisyourchessopening

See here: https://6859-sp21.github.io/a4-howgoodisyourchessopening/

For our A4 assignment, we explored a sample of the open source dataset from [lichess.com](https://database.lichess.org/), which provides game data from all of their games. Currently we are exploring the win/draw rate by Elo (a standard for rating) based on the opening moves. We wanted to explore if the frequency of opening moves differs across skill levels and if there are trends in win rates when scoping across amateur to master level players

In order to be able to interact and visualize the moves, we use Javascript libaries [chessboard.js](http://chessboardjs.com) and [chess.js](https://github.com/jhlywa/chess.js) to create a chessboard that the user can operate. They are prompted to make a move, or several, which creates a PGN, which is the standard game notation for chess moves. We use this PGN to filter through the dataset and then us d3 to create a binned stackd histogram that shows the win/rate draw across Elo for the input PGN. We also implemented tooltips to look closer and see the amount of games as well as meta data below to show the total number of games with that PGN and the proportion of total games.

We hope to add more data and expand on possible insights we can get from the data, as well as add possible features such as most common next moves and meta-data on certain setups.



## License

[MIT License](LICENSE.md)

[jQuery]:https://jquery.com/
[chessboardjs.com]:http://chessboardjs.com
[chess.js]:https://github.com/jhlywa/chess.js
