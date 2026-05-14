---
title:  "Reinforcement Learning: Intelligence is Winning"
layout: post
---

<figure>
    <img src="https://a-history-of-ai.github.io/blog/assets/images/backgammonboard.png"
         alt="Backgammon board" 
       >
</figure>

*"I felt like I was playing against a god of Go."* — Lee Sedol, world champion, 2016

---

In 1992, a researcher at IBM gave a computer program no strategy, no expertise and no knowledge of backgammon beyond the rules, then left it to play itself. One and a half million games later, it was beating the best players in the world and finding moves nobody had ever seen. Gerald Tesauro hadn't taught it anything. He had just given it a way to keep score.



The story of how machines learned to win at games is, in miniature, the story of AI itself. To win at chess you have to be intelligent. There is no shortcut. You have to plan, evaluate and outthink a competitor trying to beat you. Games have clear rules, a well-defined environment and a goal that needs no interpretation. Unlike the real world they are controlled environments to create and study intelligence, much like a laboratory.

The challenge is that even simple rules produce a staggering number of possible games. Chess has more possible games than atoms in the observable universe. Go, with even simpler rules, increases that complexity beyond comprehension. No computer, however fast, can search all of it. Brute force was never going to be enough.

Early AI researchers turned to games to work out how to search more intelligently. In 1950 Claude Shannon showed how the Minimax algorithm could be applied to chess to prune the search space considerably. It worked by assuming your opponent always plays their best move and searching all possible responses in turn. This helped considerably, but the search space was still vast enough that you had to stop somewhere, and a position that looks perfectly safe at depth 110 can be catastrophic at depth 111.

Games also provided the early testing ground for embedding expertise to direct the search. Arthur Samuel built a checkers program in 1959, encoding what made a position strong and allowing it to update its own weightings through play. By 1962 it was good enough to beat a former Connecticut state champion, and IBM were proud enough to put it on television. But it struggled when the encoded expertise failed to match unfamiliar positions. The knowledge that guided the search also limited it.

In 1992 Gerald Tesauro built TD-Gammon using reinforcement learning, giving it no knowledge of backgammon beyond the rules. He then set it to play 1.5 million games against itself, learning from the difference between what it expected and what it found, until it stopped being wrong. World-class players struggled to beat TD-Gammon, and it discovered better responses to openings than those refined over decades of expert play. A machine with no received wisdom had found something champions had missed.

In 2016, AI made the headlines when DeepMind's AlphaGo beat the world's best Go player. AlphaGo conquered Go by combining intelligent search, embedded expertise and reinforcement learning from self-play. The following year AlphaGo Zero abandoned embedding expertise entirely, learned from nothing but the rules, and surpassed AlphaGo in forty days. It independently rediscovered opening sequences human players had refined over centuries, then discarded some in favour of better ones.

Winning games provided a fertile proving ground for applying AI to real-world problems. The techniques that emerged from that laboratory now shape how LLMs are trained, manage energy grids, design drugs and run trading strategies. Beating the best players in the world was a problem that once seemed impossible. Defining what winning looks like in the real world turned out to be harder.

---

## Further Reading

- Shannon, C. E. (1950). ["Programming a Computer for Playing Chess."](https://vision.unipv.it/IA1/ProgrammingaComputerforPlayingChess.pdf)

- Samuel, A. L. (1959). ["Some Studies in Machine Learning Using the Game of Checkers."](https://www.cs.virginia.edu/~evans/greatworks/samuel.pdf)

- Tesauro, G. (1995). ["Temporal Difference Learning and TD-Gammon."](https://www.csd.uwo.ca/~xling/cs346a/extra/tdgammon.pdf)

- Silver, D., et al. (2016). ["Mastering the Game of Go with Deep Neural Networks and Tree Search."](https://arxiv.org/abs/1602.01783)
