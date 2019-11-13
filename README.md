# Chess play robot, only for study purpose internal UiPath! 

1. This workflow will try to keep playing chess in chess.com

2. Tt depends on the stockfish engine, which can be found https://stockfishchess.org/

3. Current layout scan is using the picec number of the selector, which is not stable sometimes, in that case, it will refresh the whole page

4. keep play for a while would be banned by chess

TODO:
1. change the layout scan from variable + selector to extract table
2. remove the refresh
3. enlarge the python scope to reduce actions for reloading model
4. add an alternative engine for alpha-zero-chess in AI Fab
5. an introduction of the implementation
