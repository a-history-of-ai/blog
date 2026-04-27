---
title:  "Genetic Algorithms: Bred, Not Built"
layout: post
---

<figure>
    <img src="https://a-history-of-ai.github.io/blog/assets/images/NASA-antennas.png"
         alt="NASA antennas evolved using genetic algorithms" 
         height="300">
    <figcaption style="font-size: 10px;">Development of NASA antennas through evolutionary algorithms. (Lohn et al., 2008)</figcaption>
</figure>

*"Living organisms are consummate problem solvers. They exhibit a versatility that puts the best computer programs to shame."* — John Holland

---

In the mid-1950s, John Holland was first introduced to the mathematics of natural selection. Holland was a graduate student in mathematics at the University of Michigan who already knew how to program a computer, a rare combination at the time. He saw what nobody had seen. Evolution was a search algorithm that could be programmed.

What Holland saw was intelligence that searched rather than reasoned. At the time, you wrote programs by telling the machine what to do, step by step. Holland proposed the opposite: specify a test for what a good answer looks like, then let the program evolve toward it.




Like biology, the mechanism is brutal. Encode thousands of candidate solutions as bit strings, like chromosomes, and score each one against a fitness function. Most fail. Pair the survivors, swap segments to create offspring, let mutations creep in and run for thousands of generations. The surviving population finds solutions you could not have specified in advance. Evolution doesn't know what it's looking for, and on the hardest problems, neither do we.

Holland published the framework in 1975 in a book called *Adaptation in Natural and Artificial Systems*. By the late 1980s genetic algorithms were one of the active areas of AI, and through the 1990s their popularity grew rapidly. Engineers applied them to problems as diverse as designing turbine blades, routing delivery vehicles, timing traffic lights, and pricing derivatives. Sometimes the result was startling. NASA needed a new spacecraft antenna and handed the problem to a genetic algorithm. The final shape looked unlike anything an engineer would have drawn, and it outperformed every human design.

Genetic algorithms struggled, however, when the thing to evolve was code itself. Random mutations to a program almost always break it. Genetic programming, the branch that tried to evolve programs directly, made progress in narrow domains but never scaled to real software.

Genetic programming is having a renaissance, thanks in part to LLMs and falling compute costs. LLMs understand how to change code and still make it work, allowing us to scale mutation intelligently for the first time. Faster and cheaper compute has made millions of evaluations tractable, allowing more solutions to be tried.

An example is AlphaEvolve, released by DeepMind in May 2025, where Gemini proposes the mutations. In its first year AlphaEvolve recovered 0.7% of Google's global compute through a better data centre scheduler and broke a record in matrix algebra that had stood for over half a century.

Holland's idea was simple. Good answers can be discovered. We are about to find out how many.

---

## Further Reading

- Holland, J. H. (1992). ["Genetic Algorithms." Scientific American, 267(1), 66-73.](https://www.isislab.it/wp-content/uploads/2021/01/Holland-Genetic-Algorithms.pdf)

- Lohn, J.D., Hornby, G.S., & Linden, D.S. (2008). ["Human-competitive evolved antennas." AI EDAM, 22(3), 235-247.](https://www.researchgate.net/publication/220306511_Human-competitive_evolved_antennas)

- Novikov, A., et al. (2025). ["AlphaEvolve: A coding agent for scientific and algorithmic discovery."](https://arxiv.org/abs/2506.13131)
