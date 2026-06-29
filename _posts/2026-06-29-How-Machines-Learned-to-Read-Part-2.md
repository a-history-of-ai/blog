---
title:  "How Machines Learned to Read, Part 2: Every Time I Fire a Linguist"
layout: post
---

<figure>
    <img src="https://a-history-of-ai.github.io/blog/assets/images/embeddings.png"
         alt="Visualisation of word embeddings from TensorBoard Embedding Projector"
       >
    <figcaption style="font-size: 10px;">Visualisation of word embeddings from TensorBoard Embedding Projector</figcaption>
</figure>

*"Every time I fire a linguist, the performance of our speech recognition system goes up."* — Fred Jelinek

---

In 1972, IBM gave Fred Jelinek's speech recognition group two linguists to help build a language model. One of them, Stan Petrick, considered the problem and offered a reassurance: "Don't worry, I will just make a little grammar." He never did. Within a year both had left, replaced by engineers and physicists whose instinct was probability rather than grammar. The speech recogniser started to improve.



Jelinek reframed the problem entirely. Inspired by information theory, he asked a precise question about spoken language: given a sequence of sounds, which words were most likely to have produced them? The same logic, his colleagues realised, applied to text. The tool was the n-gram: a probability table built from counting which words appeared together. Given enough data, the patterns were reliable, and each word left a statistical trace pointing toward what came next. It was the most undignified possible way to process language, and it outperformed everything built with grammar.

Like many ideas in the history of AI, the statistical approach didn't fully take off until the conditions were right. It was data hungry. "There is no data like more data," as Robert Mercer, one of Jelinek's colleagues at IBM, put it, and in 2001 researchers at Microsoft confirmed exactly that: a simple model trained on a billion words outperformed a clever one trained on a million. The internet solved the data problem, producing hundreds of billions of examples where researchers had worked with millions. Fortunately, the computers needed to process all of it kept getting faster and cheaper.

Translation was the obvious next step. Google trained a system on millions of document pairs, finding statistical patterns that mapped one language to another with no linguistic rules at all. Google Translate launched in 2006. It was so successful that Google has since expanded to 249 languages, adding them as fast as data could be found.

Counting words was remarkably useful and statistical NLP worked at scale, but still said nothing about what language meant. In 2013, a team at Google discovered something that would help. Their technique, Word2Vec, represented words as points in a mathematical space. The output was remarkable. Words with similar meanings clustered together. Words with analogous relationships tended to occupy equivalent positions. For example, the vector from Tokyo to Japan pointed in the same direction as the vector from Paris to France. The model had learned something that looked like meaning.

The limitation was that the vectors were static. Every word had a single fixed point in space regardless of context. "Bank" occupied the same position whether the surrounding words were about rivers or balance sheets. Meaning shifts with context, and a fixed vector could not shift with it. Getting that right would require a model that could weigh every word's relationship to every other word in a sentence, and know which ones deserved attention.


---

## Further Reading

- Banko, M., & Brill, E. (2001). ["Scaling to Very Very Large Corpora for Natural Language Disambiguation."](https://aclanthology.org/P01-1005/)

- Mikolov, T. et al. (2013). ["Efficient Estimation of Word Representations in Vector Space."](https://arxiv.org/abs/1301.3781)

- Liberman, M. (2010). ["Obituary: Frederick Jelinek."](https://aclanthology.org/J10-4001.pdf)
