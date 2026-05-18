# aPRG-adp
Averaged proximal reflected gradient method for monotone variational inequalities

Projected reflected gradient (PRG) method proposed by Malitsky is efficient for solving
monotone variational inequality (MVI), while the existing upper bound of step size is not tight
due to the inequality scaling in the theoretical analysis. In this paper, we construct an averaged
variant of PRG method for more general MVI and present a novel Lyapunov function to establish
convergent theory. This averaged PRG method provides an improvement of the golden ratio algo-
rithm [Y, Malitsky, Math. Program., 184, 383–410, 2020], and the involved step size is compatible
with that for the classical methods, such as Popov’s extragradient and forward-reflected-backward
methods. Moreover, a fully adaptive strategy without linesearch is presented to adjust step sizes,
which generates adaptive and potentially much larger step sizes. Numerical experiments on the
Nash−Cournot equilibrium, HpHard, and image reconstruction problems demonstrate that the
proposed algorithm significantly outperforms existing state-of-the-art methods.
