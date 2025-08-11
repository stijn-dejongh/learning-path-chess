# Game Logs

Games ordered by date, with annotations and motif reviews when available.

## 📅 Game Log Structure

Each game log file is named by the month and year, e.g., `2025_Q3/black.md` and `2025_Q3/white.md` for Q3 2025. Each entry includes:

- Date of the game
- Opening played
- Reference to game PGN file/collection


### 📝 Game Review Template

| Date:                         | YYYY-MM-DD                                | 
|:------------------------------|-------------------------------------------|
| **Opening Played:**           | Italian / Caro–Kann / Slav                | 
| **Habit Focus:**              | (week’s focus habit)                      | 
| **Motif Focus:**              | (week’s focus motif)                      | 
| **Result:**                   | Win/Loss/Draw                             | 
| **Metric Hit?**               | Y/N                                       |
| **Example Success:**          | (move #, description)                     | 
| **Example Miss:**             | (move #, description)                     | 
| **Motif Applied?**            | Y/N                                       |
| **Key Moment:**               | (diagram or move #)                       |
| **Reason for miss:**          | (e.g., mis-evaluated threat, forgot plan) |
| **Adjustment for next game:** | (1 action)                                | 


## 📜  Analyzing Games

Perform (semi-)manual analysis of each game, focussing on key moments, missed motifs, and overall performance against the week's focus. In order to do this, it helps to annotate the game with comments on each move, especially where I applied or missed the motif's focus (cfr. * Key Moment*  and *Example Success/Miss* in the table).

To do the analysis, I can either use the [chess.com analysis tool](https://www.chess.com/analysis) or a local chess engine like Stockfish. This can be set-up locally with a Chess Database GUI such as [SCID](https://scid.sourceforge.net/).

### Installation Instructions for SCID

```bash
sudo apt update && sudo apt upgrade
sudo apt install scid scid-data scid-rating-data
sudo apt install stockfish
```

Test the installation by running:

```bash
stockfish version
```

Next, open SCID and configure it to use Stockfish as the analysis engine:

- Tools > Analysis Engine
- Click on *New* and add:
  - Name: StockFish 16
  - Command: `/usr/games/stockfish`
  - Directory: **Click the SCID button**

### Optional: add Opening Books and Repertoires

You can also add opening books and repertoires to SCID to help with your analysis. This can be done by downloading PGN files of openings and importing them into SCID.

You can download these from various sources, such as:

- [Lichess Opening Explorer](https://lichess.org/analysis#explorer)
- [Chess.com Opening Explorer](https://www.chess.com/openings)
- [PGN Mentor](https://pgnmentor.com/)
- [OpeningTree](https://openingtree.com/)
- [ChessBase Opening Repertoire](https://www.chessbase.com/)

After downloading the PGN files, you can import them into SCID by going to:

- File > Import > PGN File
- Select the downloaded PGN file and click Open.
- The openings will now be available in SCID for analysis.


