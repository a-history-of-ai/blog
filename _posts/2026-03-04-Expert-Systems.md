---
title:  "Expert Systems: When Knowledge Became the Product"
layout: post
---

<figure>
    <img src="https://upload.wikimedia.org/wikipedia/commons/5/53/Symbolics3640_Modified.JPG"
         alt="Expert systems console">
    <figcaption style="font-size: 10px;">Expert systems console, Wikimedia Commons</figcaption>
</figure>

*"Knowledge is the only instrument of production that is not subject to diminishing returns."* — J.M. Clark, 1923

Your best salesperson just resigned. Twenty years of knowing which people matter, who to speak to when, and how decisions actually get made. None of that knowledge is in the CRM, so when they leave, it goes with them.

Every organisation carries knowledge it can't locate. It lives in the people who've been there longest, embedded in the culture and inherited processes. It isn't written down because no one can tell you exactly what it is.

In 1965, Edward Feigenbaum, a computer scientist at Stanford, thought intelligence required knowledge. Within a decade, leading researchers were publishing findings using a system he designed, without thinking twice about the AI behind it.



Early AI could follow rules and search, but it had little knowledge of the world it was operating in. It failed at everyday problems for exactly that reason. To test the idea, Feigenbaum sat down with Nobel Laureate Joshua Lederberg and started asking questions. How do you identify an unknown molecule from a mass spectrometry output? What do you look for? How do you rule things out? The sessions went on for months, with Feigenbaum diligently capturing how an expert thinks.

The program they built, DENDRAL, did something no AI had done before. DENDRAL knew one thing: chemistry. It analysed mass spectrometry data and determined molecular structures by capturing specific rules about bond energies, fragmentation patterns, and molecular stability, drawn from Lederberg's decades at the bench. Once captured, the knowledge outlasted the conversation that produced it and was now available for others to use.

Knowledge was the engine, Feigenbaum concluded, and reasoning was just the vehicle. Over the next decade, systems were built that made the case, including:

- **MYCIN** diagnosed bacterial blood infections and recommended antibiotics. It held the knowledge of infectious disease specialists, encoded as several hundred if-then rules weighted by confidence. When tested head-to-head against specialists at Stanford Medical School in a blinded evaluation, it matched the performance of the most experienced physicians.

- **PROSPECTOR** encoded the expertise of economic geologists to evaluate mineral deposits. In 1980 it predicted that a site in Washington state contained a molybdenum deposit worth over a hundred million dollars. The geologists had surveyed the area and missed it.

- **R1, later renamed XCON**, was built for Digital Equipment Corporation to configure customer computer orders. Every order was different, and getting the configuration right was a job only a handful of engineers could do. R1 encoded their expertise as production rules. By 1986 it was processing 80,000 orders a year with 95 to 98 percent accuracy, saving DEC an estimated $25 million annually.

The idea spread fast. If you could bottle a chemist's expertise, you could bottle anyone's. Entire hardware companies — Symbolics, Lisp Machines Incorporated, Texas Instruments — built specialised machines just to run expert systems faster. Universities created knowledge engineering programmes. Consulting firms built practices around eliciting expert knowledge. Companies invested billions in systems that were already working. Hundreds of expert systems were deployed across financial planning, oil drilling and military logistics.

Expert systems collapsed in the late 1980s and the field moved on. Feigenbaum's intuition about knowledge went with it. Most organisations still carry more expertise than they have ever captured. That problem is still there.

Your best salesperson resigned. The problem is that you never captured what they knew.

---

## Further Reading

- Feigenbaum, E. A. (1977). ["The Art of Artificial Intelligence: Themes and Case Studies of Knowledge Engineering."](https://stacks.stanford.edu/file/druid:bg342cm2034/bg342cm2034.pdf)

- Feigenbaum, E. A. (1980). ["Expert Systems in the 1980s."](https://stacks.stanford.edu/file/druid:vf069sz9374/vf069sz9374.pdf)

- Yu, V. L., et al. (1984). ["An Evaluation of MYCIN's Advice."](https://people.dbmi.columbia.edu/~ehs7001/Buchanan-Shortliffe-1984/Chapter-31.pdf)

- ACM. (1994). ["Edward A. Feigenbaum — A.M. Turing Award Laureate."](https://amturing.acm.org/award_winners/feigenbaum_4167235.cfm)
