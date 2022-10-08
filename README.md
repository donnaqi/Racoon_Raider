# Racoon_Raiders

A game that is somewhat similar to Rodent’s Revenge (https://en.wikipedia.org/wiki/Rodent%27s_Revenge)

## Demo

[![Watch the video](https://img.youtube.com/vi/6NmrODfm9es/hqdefault.jpg)](https://www.youtube.com/watch?v=6NmrODfm9es)

During the game, raccoons try to climb into one of the available garbage cans. The main player aims to prevent the raccoons from reaching the garbage cans by trapping them using recycling bins.

Each character takes up exactly one tile, except that a raccoon can crawl inside an open garbage can, in which case there will be two characters (a raccoon and a garbage can) on the same tile.

Some characters are movable (the main player, raccoons, and recycling bins) while others are static (garbage cans). Some of the movable characters can take turns (the main player and raccoons). Each turn-taking character can move exactly one tile on its turn, in one of the following directions: up, down, left or right. Raccoons are given turns less frequently than the main player, as can be seen in the example gameplay above.

When the game starts, the player is placed on the top-left corner. Raccoons, garbage cans and recycling bins are placed randomly on the board. Two types of raccoons exist in the game: regular raccoons and smart raccoons (with glasses), that move randomly or smartly respectively, aiming to crawl inside the garbage cans.

When a raccoon reaches an unoccupied, unlocked garbage can, it crawls inside and stays there. If the garbage can is locked, the raccoon will use up its turn to unlock it.

The player’s objective is to prevent the raccoons from getting into the garbage cans by trapping them with recycling bins, while trying to keep as many recycling bins clumped together as possible. We want to trap the raccoons, but we do not want to leave recycling bins all over the neighbourhood in doing so!

The player moves using the four arrow keys and pushes around the recycling bins in an attempt to trap the raccoons.

Recycling bins can’t move autonomously but can be pushed by the main player in the hope of trapping the raccoons. When pushed by the main player, a recycling bin moves in the same direction as the player. If the new tile happens to be occupied with another recycling bin, this recycling bin is also moved in the same direction as well. If there is a row or column of recycling bins being pushed, they all move. 

A raccoon is considered trapped if it is surrounded in all four directions (diagonals don’t matter) by recycling bins, other raccoons (including ones in garbage cans), the player, or the border of the game board.

The game ends once all raccoons are either trapped or inside garbage cans.

When the game ends, your score is displayed. The score is determined based on the number of trapped raccoons, as well as the maximum number of adjacent recycling bins.

Note that sometimes you may get into a game state where it will become impossible for the game to end (i.e. you can’t possibly trap the remaining raccoons). You will just need to close the game window. In this case, you never see a score.
