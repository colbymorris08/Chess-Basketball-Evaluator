♟️🏀 Chess-Basketball-Evaluator

A chess-style decision engine for evaluating basketball plays across NBA and WNBA contexts

⸻

Overview

Chess-Basketball-Evaluator is an interactive Streamlit app that evaluates basketball offensive plays using a chess engine–style decision framework.

Just as chess openings are evaluated differently depending on position, tempo, and opponent, basketball plays should be evaluated differently depending on league-specific efficiency profiles.

This project compares NBA vs WNBA expected value (EPP) for common half-court actions, revealing why some plays that grade well in the NBA underperform in the WNBA — and vice versa.

⸻

Core Idea: The Chess Analogy

“The best play isn’t the one that works in the NBA — it’s the one that works for your league’s evaluation function.”

	•	Chess engines score openings differently based on structural advantages
	•	Basketball analytics often assume NBA-centric efficiency
	•	The WNBA has different scoring distributions, especially:
	•	Higher relative midrange efficiency
	•	Lower rim finishing rates
	•	Different spacing and physical constraints

This app reframes play selection as a decision tree, not a single outcome — much like chess.

⸻

What the App Does

🎮 Interactive Play Selection
	•	Choose from common actions:
	•	FAV Zoom
	•	FAV Elbow
	•	SOB Basic Zoom
	•	SOB Triangle
	•	BOB Triangle Down
	•	FAV Nail
	•	Each play expands into multiple branches (reads)

⸻

📊 NBA vs WNBA Evaluation

For each play, the app computes:
	•	Shot zone outcomes per branch (rim, midrange, corner 3, etc.)
	•	League-specific shot efficiency
	•	Expected Points Per Possession (EPP)

Displayed side-by-side:
	•	NBA evaluation
	•	WNBA evaluation
	•	Net WNBA advantage / disadvantage

⸻

🌳 Decision Tree Comparison
	•	Visualizes each play as a branching decision tree
	•	Highlights where value diverges between leagues
	•	Makes clear why a play succeeds or fails

⸻

📈 All-Plays Comparison
	•	League-level bar charts comparing:
	•	Overall EPP
	•	Play-by-play WNBA advantage
	•	Color-coded table showing:
	•	Best plays for WNBA
	•	Worst NBA-biased actions

⸻

🎯 Key Insights Panel

Automatically identifies:
	•	✅ Best WNBA play
	•	⚠️ Worst WNBA play
	•	Clear explanations grounded in shot profile differences

Example:
	•	BOB Triangle Down performs better in WNBA due to midrange emphasis
	•	FAV Elbow underperforms due to reliance on rim finishing and above-break 3s

⸻

Key Findings
	•	Some “elite” NBA plays are structurally inefficient in the WNBA
	•	WNBA-optimized offense:
	•	Embraces midrange
	•	Reduces forced rim attempts
	•	Values decision stability over pure spacing
	•	NBA analytics should not be blindly transferred to the WNBA

⸻

Why This Matters

This tool demonstrates how:
	•	Analytics must be context-aware
	•	League-specific efficiency changes optimal strategy
	•	Coaches and analysts can rethink playbooks using decision trees, not averages

The same play can be:
	•	A “best move” in one league
	•	A positional blunder in another

Just like chess.

⸻

Tech Stack
	•	Python
	•	Streamlit
	•	Pandas / NumPy
	•	Matplotlib
	•	Custom decision-tree evaluation logic

⸻

Future Extensions
	•	Defensive coverage modeling
	•	Player-specific efficiency inputs
	•	NCAA / international league profiles
	•	Automated play design recommendations

⸻

Author

Built by Colby Morris
colby.morris08@gmail.com
