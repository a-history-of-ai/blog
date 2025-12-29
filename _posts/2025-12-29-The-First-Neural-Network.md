---
title:  "The Perceptron: The First Neural Network"
layout: post
---

<figure>
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6c/Mark_I_Perceptron.jpg/800px-Mark_I_Perceptron.jpg"
         alt="Mark I Perceptron" 
         height="300">
    <figcaption style="font-size: 10px;"> Mark I Perceptron at the Smithsonian. <a href="https://commons.wikimedia.org/wiki/File:Mark_I_Perceptron.jpg">Wikimedia Commons</a>, Public Domain</figcaption>
</figure>
*"The first machine which is capable of having an original idea."* — Frank Rosenblatt, 1958

The history of AI is a history of ideas and failure. This is true from the very beginning. Where Simon and Newell demonstrated intelligence by solving problems, others believed learning was the key. An intelligent machine should adapt from experience, improve with practice, and learn from mistakes.

If you want to study learning, an obvious place to start is the brain. Our brains are made up of billions of neurons, cells that transmit electrical signals. In 1943, Warren McCulloch and Walter Pitts showed mathematically how networks of artificial neurons could compute logical functions. In 1949, psychologist Donald Hebb proposed how learning might work: connections between neurons that fire together grow stronger. Others contributed ideas about adaptation and probability. But this was all theory.

Frank Rosenblatt was a psychologist who wanted to study this empirically. By the late 1950s, the technology existed to try. Rosenblatt built a machine and ran experiments to see what it revealed. This was no small undertaking. In the 1950s this meant physical engineering: soldering circuits, wiring connections, mounting photocells, machines the size of rooms.

In July 1958 at Cornell Aeronautical Laboratory, Rosenblatt stands before a machine he calls the Perceptron. The press and Navy, who funded his research, gathered to watch. Rosenblatt shows cards with shapes on them to the machine. The Perceptron gets them wrong at first. Then it adjusts its weights and after a few dozen examples, it learns to distinguish them correctly. This is remarkable and unlike anything seen before. The Perceptron learned from experience, not from programmed rules. You showed it examples, it found patterns and adjusted itself based on feedback.

As with many AI stories to follow, hype kicked in. The press and the Navy saw this working demo and projected extraordinary futures. Rosenblatt himself talked about firing perceptrons to the planets as mechanical space explorers. For a few years, the approach looked promising and funding flowed. But the gap between what the Perceptron could actually do and what people claimed it would do became enormous.

The Perceptron could distinguish simple patterns: letters from shapes, left from right, horizontal from vertical lines. It worked for problems where patterns were cleanly separable. But some patterns defeated it. XOR was the famous example: a simple logic rule that outputs true when the inputs differ and false when they are the same. In 1969, Marvin Minsky and Seymour Papert proved mathematically that this limitation was fundamental. No amount of training could fix it. If you couldn't learn to solve something as simple as XOR, you couldn't solve many real problems. So the hype collapsed and funding dried up.

Importantly the Perceptron revealed that machines could learn from examples. Rosenblatt proved that adjusting weights based on errors worked. The limitation was depth. Having only a single layer wasn't enough. The question became how to train deeper networks. That question would take several years to answer, and the solution would require both new mathematics and new hardware.

But first, someone had to keep working on neural networks while everyone else abandoned them. That story comes next.

---

## Further Reading

- McCulloch, W. S., & Pitts, W. (1943). ["A Logical Calculus of the Ideas Immanent in Nervous Activity." Bulletin of Mathematical Biophysics](https://www.cs.cmu.edu/~epxing/Class/10715/reading/McCulloch.and.Pitts.pdf)

- Rosenblatt, F. (1958). ["The Perceptron: A Probabilistic Model for Information Storage and Organization in the Brain." Psychological Review](https://www.ling.upenn.edu/courses/cogs501/Rosenblatt1958.pdf)

- Minsky, M., & Papert, S. (2017). [Perceptrons: An Introduction to Computational Geometry. Expanded edition](https://leon.bottou.org/publications/pdf/perceptrons-2017.pdf)

- Cornell Chronicle (2019). ["Professor's perceptron paved the way for AI – 60 years too soon."](https://news.cornell.edu/stories/2019/09/professors-perceptron-paved-way-ai-60-years-too-soon)
