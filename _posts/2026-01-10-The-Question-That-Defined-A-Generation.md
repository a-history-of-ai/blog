---
title:  "The Question That Defined a Generation"
layout: post
---

<figure>
    <img src="https://a-history-of-ai.github.io/blog/assets/images/McCarthy.png"
         alt="John McCarthy" 
         height="300">
    <figcaption style="font-size: 10px;">John McCarthy</figcaption>
</figure>

*"The central problem of artificial intelligence involves how to express the knowledge about the world that is necessary for intelligent behavior."* — John McCarthy

---

Arguably no one has had such a long lasting impact on AI as John McCarthy. He shaped the field in ways few others did and his contributions cast a long shadow for decades. He gave the field its name, posed central questions and introduced the programming language that made exploring them possible. His key insight was to consider how knowledge should be represented.

McCarthy was there from the very start. He was one of the organizers of the Dartmouth conference in the summer of 1956 that gave the field its name. Naming mattered. It declared that machine intelligence was a legitimate research program, not science fiction.

In 1958, McCarthy described the Advice Taker. You would tell this machine facts using formal logic, and it would reason about them. Ask how to get from your house to the airport, and it would figure out cars, roads, and what makes something drivable. The Advice Taker was never built, because the technology wasn't ready. Computers in 1958 had tiny memories and no interactive interfaces.

But in describing what such a program would need, McCarthy posed questions he couldn't solve. Three of these problems would go on to define the field:

- **The frame problem.** What stays the same when you paint a room? The color changes but the temperature doesn't. A machine needs to know which facts remain true after an action. Specifying everything that does not change is infinite. Assuming nothing changes creates paradoxes.

- **The symbol grounding problem.** The symbol "car" means something to humans because we have seen cars, sat in them, driven them. To a computer, it is just a string of letters. How do you connect symbols to what they represent?

- **The knowledge representation problem.** How do you capture what experts know in a form machines can use? Medical diagnosis requires knowing thousands of facts about diseases, symptoms, and treatments. How do you organize this so a program can reason with it?

McCarthy had not only named the field and posed questions. He built tools to explore them. In 1960, he created LISP, a language where code and data were the same thing. Lists could represent facts, rules, or even other programs. You could even write programs that reasoned about programs. This was radical - code that modified itself, that examined its own logic. LISP became the language of AI, with most major systems for the next thirty years written in it.

McCarthy's questions proved more durable than any answers found in his lifetime. The frame problem, symbol grounding, and knowledge representation resisted solution for decades, spawning entire subfields and countless PhD theses.

The focus of AI is very different now. Large language models seemed to sidestep these questions by learning patterns from billions of words. But have they? Can a system that cannot update a single fact without retraining truly represent knowledge? Can symbols be grounded without sensory experience? Can statistical patterns spot what doesn't happen from observing only what does? 

McCarthy gave AI its name in 1956. Seventy years later, the field is still wrestling with the problems he posed in 1958.

---

## Further Reading

- McCarthy, J., Minsky, M. L., Rochester, N., & Shannon, C. E. (1955). ["A Proposal for the Dartmouth Summer Research Project on Artificial Intelligence."](http://jmc.stanford.edu/articles/dartmouth/dartmouth.pdf)

- McCarthy, J. (1959). ["Programs with Common Sense." Proceedings of the Teddington Conference on the Mechanization of Thought Processes.](http://www-formal.stanford.edu/jmc/mcc59.html)

- McCarthy, J. (1960). ["Recursive Functions of Symbolic Expressions and Their Computation by Machine, Part I." Communications of the ACM, 3(4), 184-195.](http://www-formal.stanford.edu/jmc/recursive.pdf)

- Mitchell, M. & Krakauer, D. C. (2023). ["The Debate Over Understanding in AI's Large Language Models." Proceedings of the National Academy of Sciences.](https://www.pnas.org/doi/10.1073/pnas.2215907120)

- Stanford Computer Science. ["Professor John McCarthy."](https://legacy.cs.stanford.edu/memoriam/professor-john-mccarthy)
