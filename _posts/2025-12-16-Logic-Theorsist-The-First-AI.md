---
title:  "Logic Theorist: The First AI"
layout: post
---

![Herbert Simon](https://upload.wikimedia.org/wikipedia/commons/b/bb/Herbert_simon_red_complete.jpg)
~*Image: Wikimedia Commons*~

*"Machines will be capable, within twenty years, of doing any work a man can do." — Herbert Simon, 1965*

---

January 1956. Herbert Simon's living room in Pittsburgh. His wife, three children, and several graduate students stand in a circle, each holding a 3x5 index card carrying instructions. Each person is a component of a program that doesn't yet exist on any machine. Simon gives a signal. They begin passing messages, following the rules on their cards, executing the program by hand. They are humans simulating a computer designed to simulate human thinking. Simon would later recall, "Here was nature imitating art imitating nature." If the program they are running works, it will prove that machines can think.

Computers could calculate. The question was whether they could reason. Alan Turing had posed this in 1950, arguing that machines could think if they could imitate intelligent behaviour. But skepticism remained widespread. Ada Lovelace had written a century earlier that the Analytical Engine "has no pretensions to originate anything." Many still believed computers could only follow orders, not solve problems that required judgment. Simon and Newell set out to prove otherwise.

Simon was a political scientist who studied how organisations make decisions. Newell was trained in mathematics and had worked on early radar systems. Neither of them were traditional computer scientists. To build Logic Theorist, they needed Cliff Shaw, a programmer at RAND who could translate their ideas into working code. Shaw would later say he was "the genuine computer scientist of the three." This collaboration became the pattern. AI requires an understanding of the problem to be solved, a theory and the ability to build a system to test it.

With Shaw's help, they got it working on a computer. What was simulated by hand in the living room now ran as code. The program proved theorems from Bertrand Russell's Principia Mathematica, one of the foundational texts of mathematical logic. Trying every possible logical deduction would take forever. The program used heuristics instead, rules of thumb that guided search toward promising directions. It could work backward from the goal. It could substitute variables in known theorems. It could draw logical conclusions from known facts. Simon and Newell had studied how humans prove theorems, including themselves. The heuristics were modelled on human problem solving. The machine was doing what humans did, just faster and more systematically. They called it Logic Theorist.

Logic Theorist proved 38 of the first 52 theorems in Chapter 2 of Principia Mathematica. For theorem 2.85, it found a proof more elegant than the one Russell and Whitehead had published. When Simon and Newell submitted their results, they wanted to list Logic Theorist as a co-author. The journal refused, stating that a machine couldn't be an author. But the refusal revealed something important. If a program could prove theorems, what did that say about the nature of thinking?

That summer, John McCarthy organized a conference at Dartmouth College on Artificial Intelligence, a term he coined for the occasion. Researchers gathered to discuss what might be possible. Simon and Newell showed up with Logic Theorist, the only working program anyone brought. They were, Simon admitted later, probably arrogant about it. They had something to show, not just talk about. The reception was lukewarm. Pamela McCorduck would later write that nobody except Simon and Newell themselves sensed the significance of what they had done. They had already built what everyone was talking about building, and nobody paid much attention.

Logic Theorist proved three things:

- **Heuristic search made problem solving tractable.** Rules of thumb guided search toward promising directions, making it tractable. This technique would become foundational. Chess programs used heuristic search through game trees. Route planning used search through possible paths. Medical diagnosis systems searched through possible diseases. Scheduling systems searched through possible orderings. The framework was soon everywhere.

- **Thinking could be described as symbol manipulation following rules.** Intelligence was a process you could specify and implement. This became the Physical Symbol System Hypothesis, the assumption that shaped AI for decades.

- **You could study thinking by building systems that think.** The program was both a tool and a theory being tested. If it worked, you had shown something about how problem solving works. If it failed, you learned what was missing.

Intelligence was problem solving, which was search guided by heuristics. Build systems that search intelligently, and you have built intelligence. Or so it seemed. For a while, it worked remarkably well.

What Simon and Newell established in that living room became Artificial Intelligence as a scientific discipline. They showed that you could build computer programs that solve problems. They showed that thinking could be studied by building systems. The program was both tool and theory, both application and understanding. Every AI system built since follows this pattern. Build something. See what it reveals. Learn what works and what doesn't. Refine your understanding. Build again. That cycle started in a living room with index cards and a family willing to pretend they were a computer. It worked, and we are still learning from it.

---

## Further Reading

- Lovelace, A. (1843). "Notes by the Translator" in Sketch of the Analytical Engine Invented by Charles Babbage.  
  https://psychclassics.yorku.ca/Lovelace/lovelace.htm

- Turing, A. M. (1950). "Computing Machinery and Intelligence." Mind, 59(236), 433-460.  
  https://www.cs.ox.ac.uk/activities/ieg/e-library/sources/t_article.pdf

- Newell, A., & Simon, H. A. (1956). "The Logic Theory Machine: A Complex Information Processing System." RAND Corporation.  
  https://www.rand.org/pubs/papers/P868.html

- McCarthy, J., Minsky, M. L., Rochester, N., & Shannon, C. E. (1955). "A Proposal for the Dartmouth Summer Research Project on Artificial Intelligence."  
  http://jmc.stanford.edu/articles/dartmouth/dartmouth.pdf

- History of Information, "Newell, Simon & Shaw Develop the First Artificial Intelligence Program."  
  https://www.historyofinformation.com/detail.php?id=742

