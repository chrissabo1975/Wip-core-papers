Prime Move Theory Repository

A Minimal Theory of Generative Structure: From Distinction to Computation

https://img.shields.io/badge/License-MIT-yellow.svg
https://img.shields.io/badge/Python-3.8+-blue.svg
https://img.shields.io/badge/Theory-Under_Development-orange.svg

"The simplest code was the universe correcting itself."

This repository presents a complete research program exploring how structured complexity emerges from minimal beginnings. It contains everything: formal papers, computational simulations, philosophical manifestos, and narrative fiction—all centered on the Prime Move Operator, a minimal generative mechanism that produces hierarchical structure through cycles of distinction and persistence.

---

📚 Repository Structure

📄 Papers (Formal Theory)

· Paper 1.5 – Bootstrapping Structure from Minimal Axioms
  Conceptual foundation: Axioms 0-3, five-stage cycle derivation, minimality proof.
· Paper 2.1 – Mathematical Formalization
  Complete mathematical framework: Fibonacci proofs, φ-convergence, hierarchical indexing.

💻 Code (Computational Implementation)

· change_engine.py – 2D cellular automaton simulation
  Game of Life + decay + witness forcing. See theory in action.
· prime_move_operator.py – Pure Prime Move implementation
  Direct implementation of the mathematical model from Paper 2.1.
· examples.py – Ready-to-run demonstration scenarios

📖 Narrative & Manifestos

· Defrag (Chapters 0-1) – Science fiction short story
  Narrative instantiation of the theory in a cyberpunk setting.
· From Nothing 2.0 – Philosophical manifesto
  Accessible introduction to the core ideas.

---

🎯 Core Idea in One Paragraph

How does structure emerge from nothing?
The Prime Move Operator proposes a minimal five-stage cycle:
Split → Tension → Failed Merge → Scar → Decay
Once initiated from undifferentiated unity, this cycle:

1. Cannot stop (self-perpetuating)
2. Leaves permanent residues (scars accumulate)
3. Generates Fibonacci growth (golden ratio φ emerges)
4. Creates hierarchical complexity (scale-invariant structure)
5. Naturally accommodates computation (Turing-complete patterns arise)

No external rules. No tuning parameters. Just distinction, persistence, and time.

---

🚀 Quick Start

Run the Main Simulation

```bash
# Clone the repository
git clone https://github.com/chrissabo1975/prime-move-theory.git
cd prime-move-theory

# Install requirements
pip install numpy matplotlib

# Run the 2D simulation (shows theory in action)
python code/change_engine.py
```

Explore Different Modes

```bash
# Single distinction (minimal start)
python code/change_engine.py --mode single --steps 200

# Glider gun (persistent computation under decay)
python code/change_engine.py --mode glider_gun --decay 0.02

# High entropy regime
python code/change_engine.py --mode random --decay 0.1 --witness 0.01
```

Test the Mathematical Model

```bash
# Run the pure Prime Move Operator (from Paper 2.1)
python code/prime_move_operator.py

# See Fibonacci growth in action
python code/examples.py
```

---

🔍 Key Findings

1. Fibonacci Emergence

The Prime Move Operator naturally produces Fibonacci sequences:

```
Generational scars: 0, 1, 2, 4, 7, 12, 20, 33, 54, 88, 143, ...
Ratios converge to: φ ≈ 1.6180339887...
```

2. Golden Ratio Without Assumptions

φ emerges from only two structural constraints:

· Cycle length = 5 stages
· Maturation delay = 1 generation

No "golden ratio" parameter is introduced—it appears as a mathematical necessity.

3. Scale Invariance

Every level of the hierarchy is structurally identical. Subtrees are isomorphic copies of the whole tree (fractal-like self-similarity).

4. Self-Perpetuation

Once initiated, the process cannot terminate internally. Distinctions breed more distinctions through scar accumulation.

5. Computational Capacity

The system naturally produces Turing-complete substrates as emergent patterns (demonstrated via Game of Life integration).

---

🧩 Theory ↔ Code Mapping

Theory Concept Code Representation
Undifferentiated Unity Empty grid / U_0 state
Split (Prime Move) Initial seed / S_0 transition
Tension Game of Life neighborhood rules
Failed Merge Pattern collisions that don't stabilize
Scar Persistent live cells / Sc_k states
Decay Probabilistic cell death / D_k transition
Witness Forcing Random birth when system nears collapse
Hierarchical Level Tree depth k
Fibonacci Growth b_k = F_{k+2} - 1 in simulations

---

📈 What to Explore

Parameter Experiments

```python
# In change_engine.py, try:
DECAY_PROBABILITY = 0.0    # Pure computation (no entropy)
DECAY_PROBABILITY = 0.05   # Balanced regime
DECAY_PROBABILITY = 0.15   # High entropy (frequent collapse)
WITNESS_PROB = 0.0         # No forced rebirths
WITNESS_PROB = 0.01        # Frequent interventions
```

Research Questions

1. How does system stability depend on decay rate?
2. What's the critical decay probability for pattern persistence?
3. How do witness events affect long-term evolution?
4. Can the system maintain computational capacity under high entropy?

Visualization

The code includes matplotlib visualizations showing:

· Grid evolution over time
· Live cell counts (activity dynamics)
· Pattern persistence
· Phase transitions

---

🎓 Reading Paths

For Programmers / Computational Thinkers

1. Start with change_engine.py – see it in action
2. Read "From Nothing 2.0" manifesto
3. Explore Paper 2.1 for mathematical details
4. Implement your own extensions

For Mathematicians / Theorists

1. Read Paper 1.5 (axioms)
2. Study Paper 2.1 (formal proofs)
3. Verify with prime_move_operator.py
4. Explore extensions (stochastic, continuous limits)

For Philosophers / Interdisciplinary

1. Read "Defrag" fiction
2. Read "From Nothing 2.0"
3. Skim Paper 1.5 for conceptual framework
4. Watch simulations run

For Educators

1. Use change_engine.py to teach emergence
2. Paper 1.5 for philosophy of science discussions
3. Paper 2.1 for mathematical modeling examples
4. "Defrag" for creative writing inspiration

---

🔬 Scientific Context

Related Work

· Spencer-Brown's Laws of Form – Distinction as primitive
· Whitehead's Process Philosophy – Becoming over being
· Garfinkel's Ethnomethodology – Social order as accomplishment
· Conway's Game of Life – Emergent computation
· Fibonacci Systems – Population dynamics, phyllotaxis

Novel Contributions

1. Minimal bootstrapping – Structure from distinction alone
2. Parameter-free φ emergence – Golden ratio as necessity, not assumption
3. Unified hierarchy – Scale invariance across levels
4. Theory-to-code completeness – Full implementation alongside formalism

---

🤝 Contributing

This is an open research program. Contributions welcome:

1. Code improvements – Optimizations, new visualizations
2. Mathematical extensions – Stochastic variants, continuous limits
3. Empirical applications – Test against real-world data
4. Cross-disciplinary bridges – Connect to physics, biology, sociology
5. Documentation – Clarify, translate, teach

Ways to Engage

· Run the code and share your observations
· Submit issues with questions or suggestions
· Fork and experiment with parameters
· Write about applications in your field
· Create visualizations or demos

---

📜 License

MIT License – See LICENSE for details.

You are free to use, modify, and distribute this work with attribution.



---

🌐 Connect

· Repository: https://github.com/chrissabo1975/prime-move-theory
· Theory Discussion: Open an issue on GitHub
· Code Issues: Check the issues tab
· Extensions: Fork and experiment

---

From nothing → distinction → change → residue → structure → computation.
No grand claims required—just patterns worth noticing.
