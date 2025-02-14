+++
title = "Computations with Greater Quantum Depth Are Strictly More Powerful (Relative to an Oracle)"
authors = [
"Matthew Coudron",
"Sanketh Menda"
]
date = "2020-06-22"
[extra]
venue = "STOC 2020"
link = "https://arxiv.org/abs/1909.10503"
arxivlink = "https://arxiv.org/abs/1909.10503"
doi = "10.1145/3357713.3384269"
+++

A conjecture of Jozsa (arXiv:quant-ph/0508124) states that any polynomial-time quantum computation can be simulated by polylogarithmic-depth quantum computation interleaved with polynomial-depth classical computation. Separately, Aaronson conjectured that there exists an oracle O such that BQP<sup>O</sup> ≠ (BPP<sup>BQNC</sup>)<sup>O</sup>. These conjectures are intriguing allusions to the unresolved potential of combining classical and low-depth quantum computation. In this work we show that the Welded Tree Problem, which is an oracle problem that can be solved in quantum polynomial time as shown by Childs et al. (arXiv:quant-ph/0209131), cannot be solved in BPP<sup>BQNC</sup>, nor can it be solved in the class that Jozsa describes. This proves Aaronson’s oracle separation conjecture and provides a counterpoint to Jozsa’s conjecture relative to the Welded Tree oracle problem. More precisely, we define two complexity classes, HQC and JC whose languages are decided by two different families of interleaved quantum-classical circuits. HQC contains BPP<sup>BQNC</sup> and is therefore relevant to Aaronson’s conjecture, while JC captures the model of computation that Jozsa considers. We show that the Welded Tree Problem gives an oracle separation between either of {JC, HQC} and BQP. Therefore, even when interleaved with arbitrary polynomial-time classical computation, greater ”quantum depth” leads to strictly greater computational ability in this relativized setting.
