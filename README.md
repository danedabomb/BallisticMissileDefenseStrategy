# BallisticMissileDefenseStrategy
BMD Strategy: Towards Optimal Interceptor Allocation report for CS238 at Stanford. Worked with James Myerson and Galle Smagghe.

Methods Used:
- Baseline Heuristic: launch 2 interceptors at each incoming missile
- Markov Decision Process (MDP) using Monte Carlo Tree Search (MCTS)
- Partially Observable Markov Decision Process (POMDP) using MCTS

Results:
Our model outperformed the public baseline heuristic for BMD strategy. Success varied between MDP and POMDP methods based on the size of the incoming attack.
