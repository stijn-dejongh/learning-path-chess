# Common Mistakes

This file contains a list of common mistakes observed in my games, which will be used to guide training focus. It is loselely based on the 'Keep a Changelog' principle from Software Engineering, where we track changes and improvements over time.

## Current: Q3 2025

### Main Mistakes

- Early pawn rush before development
- Single-shot attacks with no follow-up
- Weak handling of early opponent queen activity
- Neglecting king safety
- Missing opponent tactics before attacking

### Mitigation Strategies

1. Before Every Move — The Blunder-Check Cycle
   - **Ask:** *What did my opponent’s last move change?*
   - **Check for:**
       - New **checks** they can give next move
       - New **captures** available
       - New **threats** (forks, pins, skewers, discovered attacks)
   - **Look for hanging pieces** (both mine and theirs)
   - Only then, commit to my move

2. Early Game Discipline
   - Develop **knights and bishops** before making multiple pawn moves (except e/d pawns in the center).
   - Castle by **move 8–10**, unless their king is more exposed than mine.
   - Avoid chasing the queen with pawns — develop with tempo instead.

3. Building Attacks
   - Aim for **two or more threats at once**, not a single “gotcha” move.
   - Bring *all* pieces into the attack before sacrificing.
   - Between attack waves, **improve the worst-placed piece**.

4. Handling Early Opponent Queen Moves
   - Don’t panic — develop pieces and block central lines.
   - Look for moves that **develop and attack the queen at the same time**.
   - Keep the king safe and ready to castle.

5. When Ahead
   - Trade **pieces, not pawns** — keep pawns for promotion chances.
   - Avoid risky complications when a simpler win is available.
   - Simplify into endings I know how to win.

6. When Behind
   - Complicate — open the position, create threats.
   - Avoid trading pieces unless removing their most dangerous attacker.
   - Look for perpetual check or stalemate chances.