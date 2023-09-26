Concave pro-rata games are defined in [Concave pro-rata games](https://arxiv.org/abs/2302.02126) as a game with $n$ players with the following payoff for $i=1,...,n$:
$$U_i(x) = \frac{x_i}{1^Tx}f(1^Tx)$$
Here, $f:\mathbb R_+\rightarrow \mathbb R$ satisfying $f(0)= 0$ and concave. In the paper, the authors prove that if $f$ is $\mathcal C^1$ then, the price of anarchy is $\Theta(n)$. In the paper, the agents take the action simultaneously. What if we assume that the actions are taken sequentially, i.e. what can we say about the Stackelberg equilibrium of pro-rata games? We assume that there are $n$-players. The act by lexicographic order, player $k$ can see the actions of players $i=1,...,k-1$.

**Conjecture**: The welfare of the worst-case equilibrium of a strictly concave pro-rata game with sequential decisions is $\Theta(2^{-n})$. Intuition: Take the Cournot oligopoly game and compute the welfare. Then approximate any function over its non-trival zero with a Cournot game.
