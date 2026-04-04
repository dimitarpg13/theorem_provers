# Theorem Prover Models and Proof Assistants

**Key Architectural Paradigms**

The field has consolidated around a few approaches: whole-proof generation (emit an entire proof, validate with Lean), stepwise tactic generation with tree search (BFS, MCTS), and agentic/modular approaches that decompose proofs into sub-lemmas and iteratively refine with compiler feedback. The current generation is critically dependent on large-scale synthetically generated training data covering difficult intermediate proof states. 

For details see: https://www.emergentmind.com/topics/llm-based-theorem-provers

The trend is clear: the gap between formal and informal reasoning is narrowing fast, and the most effective systems now combine RL training, Lean compiler feedback loops, and test-time scaling. If you're looking to integrate any of these into a workflow, Goedel-Prover-V2 (8B or 32B) and Lean Copilot are probably the most accessible starting points given their open-source availability and strong results.

