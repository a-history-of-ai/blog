---
title:  "AI: Still Searching"
layout: post
---

<figure>
    <img src="https://a-history-of-ai.github.io/blog/assets/images/hanoig.jpg"
         alt="The Towers of Hanoi illustrated in La Nature" 
       >
    <figcaption style="font-size: 10px;">The Towers of Hanoi illustrated in La Nature</figcaption>
</figure>

*"Physical symbol systems are capable of intelligent action, and search is the essence of heuristic problem solving."* — Allen Newell & Herbert Simon, 1976

---

Problem solving involves considering different options, breaking things down, searching for a solution. Playing chess you explore options, consider possible moves, what your opponent may do in reaction, weighing up options along the way. It quickly becomes apparent that you can't look at all options, so you focus attention and search intelligently. You rely on patterns and tactics picked up along the way.

Alongside knowledge representation, replicating intelligent search became the focus of early AI efforts. When we left Simon and Newell after Logic Theorist, they had recognized the core problem: you cannot search everything, so you must search intelligently. Inspired by George Polya's work on problem solving, they built the General Problem Solver, demonstrating two important innovations.




The first was means-ends analysis, a framework for breaking problems down:

- **Identify the difference** between where you are and where you want to be.
- **Select a move** that reduces that difference.
- **If the move has preconditions** you cannot yet meet, those become subgoals.
- **Repeat recursively** until you reach something you can solve directly.

Breaking big problems into smaller ones seems obvious now, but Simon and Newell were the first to demonstrate it could work as an algorithm.

The second was the use of heuristics to guide the search. A heuristic is a rule of thumb, a shortcut that helps focus attention on promising directions without guaranteeing success. GPS measured how far the current state was from the goal and tried moves that reduced the biggest ones first.

GPS tackled well-defined problems like the Tower of Hanoi with ease. But not all problems are as easy to define, or gaps as easy to measure. The General Problem Solver couldn't handle general problems.

Search became one of AI's defining problems, alongside knowledge representation. McCarthy had asked how you represent what you know. GPS showed that even with perfect knowledge representation, you still need to search efficiently through possibilities. The two problems were intertwined. You cannot reason your way to answers without understanding what you are reasoning about. You cannot search infinite possibility spaces without guidance. Together, these challenges shaped AI research for decades.

The challenge of intelligent search remains. Out of the box, modern reasoning models still struggle with multi-step planning tasks over long horizons. Anyone successfully building with AI today is breaking problems into subtasks and routing them to specialised agents. Sound familiar?

---

## Further Reading

- Newell, A. (1981). ["The Heuristic of George Polya and Its Relation to Artificial Intelligence."](https://stacks.stanford.edu/file/druid:gj292yv5713/gj292yv5713.pdf)

- Newell, A., & Simon, H. A. (1961). ["GPS: A Program that Simulates Human Thought." In Lernende Automaten, pp. 109-124.](https://iiif.library.cmu.edu/file/Simon_box00064_fld04907_bdl0001_doc0001/Simon_box00064_fld04907_bdl0001_doc0001.pdf)

- Zhang, A. L., Kraska, T., & Khattab, O. (2025). ["Recursive Language Models."](https://arxiv.org/pdf/2512.24601)
