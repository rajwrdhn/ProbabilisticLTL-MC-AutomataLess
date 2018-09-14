# ProbabilisticLTL-MC-AutomataLess

Markov chains are used to model randomized systems in probabilistic model check-
ing. Transitions in Markov chains are equipped with probability. Successor states
are chosen according to the probabilistic distribution, yielding a probability mea-
sure for ω-regular languages. The analysis of a Markov chain under linear temporal
logic specifications is usually done with a deterministic automaton in an overall
double exponential blow-up. Another method for the analysis of Markov chains is
the automata-less algorithm which is based on iterative refinement of the Markov
chains. The automata-less algorithm has a single exponential blow-up. This project 
adds the automata-less algorithm in the prism model checker.
