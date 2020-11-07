# Counterfactual_Regret_Minimization

#### What is Counterfactual Regret Minimization(CFR)?

CFR is a self play algorithm, where it is used to solve large imperfect information games. It learns to play a game by playing against itself over and over again, until it reaches Nash Equilibrium, which is also known as the optimal strategy, at this point the worst case to play with anyone is a tie.

---

#### How does work?
CFR Starts off playing with a strategy that plays every decision with equal probability. After every game, it revisits its decisions, and finds ways to improve its strategy. It repeats this process over and over, improving its strategy each time. As it plays, it gets closer and closer towards an optimal strategy for the game: a strategy that can do no worse than tie against any opponent. 
