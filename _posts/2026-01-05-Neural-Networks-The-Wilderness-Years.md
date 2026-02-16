---
title:  "Neural Networks: The Wilderness Years"
layout: post
---

<figure>
    <img src="https://a-history-of-ai.github.io/blog/assets/images/hinton.png"
         alt="Geoffrey Hinton" 
        >
    <figcaption style="font-size: 10px;">Image: Canadian Institute for Advanced Research / Associated Press</figcaption>
</figure>
*"Give me another six months and I'll prove to you that it works."* — Geoffrey Hinton

As we saw in the Perceptron post, by the end of 1960s, funding for neural network research dried up and most researchers moved on to other promising approaches. Most, but not all. A small group of researchers believed.



Geoffrey Hinton was one of them. His PhD supervisor at the University of Edinburgh urged him weekly to abandon neural networks. Hinton refused, insisting he just needed more time.

In the early 1980s, John Hopfield at Caltech published work on networks that could store and recall patterns. Show the network part of a pattern and it could reconstruct the whole. Hopfield's work reignited interest in what neural networks might achieve.

In 1986, David Rumelhart, Geoffrey Hinton, and Ronald Williams published a paper in Nature describing a new algorithm. The Backpropagation algorithm solved the problem that had defeated Rosenblatt and showed that you could train networks with multiple layers.

As the name suggests, Backpropagation works backward. During training, the network measures output error. Then, working backward layer by layer, the algorithm calculates how much each connection contributed to that error. It adjusts each weight by a small amount to reduce the error. Repeat this across thousands of examples and, if the weights settle down, the network learns. Backpropagation lets networks learn representations at multiple levels of abstraction. Simple features in early layers combine into complex patterns in later layers.

Some notable applications emerged. In 1987, Terry Sejnowski and Charles Rosenberg built NETtalk, a neural network that learned to pronounce English text. They trained it on examples and it started like a babbling baby, gradually improving until it could read text aloud. The system learned pronunciation rules without anyone programming them explicitly. This was a demonstration of what backpropagation could do.

In 1989, Yann LeCun at AT&T Bell Labs trained a neural network to recognise handwritten digits. The US Postal Service provided 9,298 scanned postcodes from mail sorting offices. LeCun used 7,291 to train the network and 2,007 to test it. The system achieved a 1% error rate on the digits it classified, with a 9% rejection rate on ambiguous cases. This solved expensive operational problems. Postal services deployed it for sorting mail. Banks used similar systems to read cheques, processing millions per day.

But problems emerged:

- **Training was slow.** Using the computers available at the time, networks needed days or weeks to learn from thousands of examples.

- **Networks with many layers were hard to train.** The error signal weakened as it passed backward through the layers, so the early layers barely learned.

- **Training was unstable.** Small changes to initial settings could cause training to fail completely. Networks required careful tuning to work at all.

- **Networks were data hungry.** They needed thousands of examples to learn effectively. In the late 1980s and early 1990s, large labeled datasets were rare. So researchers could only work within narrow domains.

By the early 1990s, a new approach emerged. It was easier to use, worked better on small datasets, and solved problems that neural networks struggled with. More on the success of SVMs in a later post.

The connectionist community that had survived now faced another exodus. Funding and researchers moved on. Working on neural networks in the 1990s became career suicide all over again.

But the faithful kept going. They had seen backpropagation work and built systems that learned things no one had programmed. They just needed the right conditions.

Those conditions were coming. They just didn't know it yet.

---

## Further Reading

- Hopfield, J. J. (1982). ["Neural networks and physical systems with emergent collective computational abilities." Proceedings of the National Academy of Sciences](https://www.pnas.org/doi/10.1073/pnas.79.8.2554)

- Nielsen, M. A. (2015). ["How the backpropagation algorithm works." Neural Networks and Deep Learning, Chapter 2](http://neuralnetworksanddeeplearning.com/chap2.html)

- Sejnowski, T. J., & Rosenberg, C. R. (1987). ["Parallel networks that learn to pronounce English text." Complex Systems](https://content.wolfram.com/sites/13/2018/02/01-1-10.pdf)

- LeCun, Y., et al. (1989). ["Backpropagation Applied to Handwritten Zip Code Recognition." Neural Computation](http://yann.lecun.com/exdb/publis/pdf/lecun-89e.pdf)

- Stanford HAI (2024). ["From Brain to Machine: The Unexpected Journey of Neural Networks."](https://hai.stanford.edu/news/from-brain-to-machine-the-unexpected-journey-of-neural-networks)
