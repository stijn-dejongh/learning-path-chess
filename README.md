# 🏹 Chess Learning Experiment

> Documenting a learning journey using established techniques, and LLM assistance to generate quick reference documentation.

## 🎯 Goals
This project is both a chess improvement plan and a personal experiment in **learning approaches**.  
I want to:
1. Improve my practical chess strength in 10-minute online rapid games (current rating ~550 ELO).
2. Apply and study **top-down vs. bottom-up learning**, **deliberate practice**, and **limiting search space** in a real skill domain.
3. Track progress and adjust training based on measurable improvement in both chess and learning efficiency.

## 🧠 Learning Approach

### 1. **Top-Down / Mixed Learning**
- I learn best when I understand **how things fit together** before drilling details.
- My repertoire and study plans emphasize **opening structure**, **core ideas**, and **motifs** over memorizing deep move trees at this stage.

### 2. **Deliberate Practice**
- Each week focuses on **one specific motif or principle** (e.g., bishop activity before pawn locks, central break timing).
- Training loop: review model games → play targeted games → review only that motif → log hit rate.

### 3. **Limiting Search Space**
- **Macro level:** Restrict my openings to a small, coherent repertoire.
- **Micro level:** Limit study to main lines and 1–2 common deviations, handling offbeat lines with core principles.

## ♟ Decisions & Rationale

### 1. Current Opening Repertoire
Chosen to match my **aggressive but safe** style and reduce memorization load:
- **White:** Italian Game — fast development, early kingside pressure, central pawn breaks.
- **Black vs 1.e4:** Caro–Kann Advance — solid structure, bishop activity before e6, thematic counterattacks with c5/f6.
- **Black vs 1.d4:** Slav Defence — Caro–Kann-like structure, bishop activity before e6, c5 break after development.

**Rationale:**  
These share recurring **motifs** (central breaks, bishop placement, layered threats) so practice in one helps the others, accelerating pattern recognition.

### 2. Weakness Analysis & Training Priorities

From recent game review, key weaknesses identified:
- Early pawn rushes before development
- Single-shot attacks with no backup plan
- Poor handling of early opponent queen moves
- Neglect of king safety
- Missing opponent tactical threats before attacking

**Rationale:**  
Targeting these in training will prevent the most common and costly errors, leading to faster rating gains than focusing solely on new theory.

### 3. Principle & Decision Guides
Created:
- **Core Principles** tailored to my weaknesses (blunder-check cycle, early game discipline, attack construction, etc.).
- **In-Game Decision Guide** — a 6-step quick mental checklist to avoid oversight and keep moves principled.

**Rationale:**  
Having a repeatable thought process reduces blunders, ensures king safety, and makes my attacks more sustainable.

### 4. Repository Structure
The repo will contain:
- `[dashboard.md](dashboard.md)` — current focus, motif of the week, practice loops, and review templates.
- `[/openings/](./openings/)` — visual/markdown “battle cards” and PGN repertoires for each opening.
- `[/game_logs/](./game_logs/)` — annotated games and motif reviews.
- `[/learnings/](./learnings/)` — modular learning materials (principles, decision guides, etc.).

**Rationale:**  
Keeping materials modular lets me update one part without cluttering the rest, and makes it easy to compare learning progress over time.

## 📈 Next Steps

- Play a set of **practice games** applying the decision guide and sticking to the chosen openings.
- Log each game using the review template.
- Rotate motif focus weekly and track hit rates.
- Adjust openings or study focus based on game reviews, not speculation.

---

## 🛠 How to Use This Repo

1. **Pick the Week’s Motif Focus**
    - Example: “Bishop out before locking pawns” or “Central pawn break timing.”
    - Write it at the top of `dashboard.md`.

2. **Study Model Games**
    - Open the relevant `.pgn` file in `/openings/`.
    - Play through 2–3 annotated games that show the motif in your openings.

3. **Play Focused Games**
    - Play 5–10 rapid games (10–15 min time control).
    - In each game, consciously look for your motif.
    - If facing an unusual position, default to the principles in `decision_guide.md`.

4. **Log Games**
    - Use the template in `dashboard.md` or `/game_logs/` for each game.
    - Record whether you applied the motif, and one reason if you missed it.

5. **Review at Week’s End**
    - Tally your “hit rate” for the motif (games where you applied it correctly).
    - Write 1–2 key takeaways for the next week.

6. **Rotate to the Next Motif**
    - Select a new focus from the weaknesses list or from a new tactical/positional theme.
