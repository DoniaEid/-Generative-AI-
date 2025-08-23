## What is coher in LLMs?
 Coher is usually an abbreviation or term that refers to a model's ability to generate coherent and connected text across multiple sentences or paragraphs.

 This means the model maintains context and links ideas logically without going off-topic or providing contradictory information.

 The term is often used in LLM research to measure the quality of generated text in terms of internal coherence.

 In other words, the more “coher” a model is, the more natural, logical, and smooth the generated text appears.

##  What is an Embedding Model in AI?

An embedding model is a type of AI model that converts any data (text, image, audio, etc.) into a numerical representation called “vectors.”

The idea: each text or item is transformed into a set of numbers that represent its meaning or features in a way the computer can understand.

## Why do we use it?

  * Text search: Find documents similar to a specific word or query.

  * Text classification: Quickly determine the type or topic of a text.

  * Content recommendation: Like “similar products” or “songs you might like.”

  * Data comparison: Measure similarity between texts or items by calculating the distance between their vectors.

![embadding](../images/embadding.png)


Sure! Here's the English version of your text:

---

## Top-k Sampling

  * When the model chooses the next word, it picks from the **top k most probable words only.

  * Example: If there are 10 possible words and k=3 → it will choose from the top 3 words only.

  * Benefit: Reduces the chance of picking strange or inappropriate words, making the text more natural.

![top_k](../images/top_k.png)
## Top-p Sampling (Nucleus Sampling)

  * Instead of a fixed number, the model chooses words whose **cumulative probability reaches p

  * Example: If p=0.9 → it selects words that together account for 90% of the total probability.

  * Benefit: More flexible than Top-k, because the choice depends on the actual probabilities of the words.

![top_p](../images/top_p.png)

## What is an Embedding?

 Embedding in Artificial Intelligence (AI) is a method of transforming data (such as words, images, or even users) into numerical vectors, so that a computer can understand and process them.

Example:

   -If we have a word like "cat" or "dog", the computer doesn’t actually understand words.

   -Embedding converts the word into a sequence of numbers (a vector) in a mathematical space (vector space).

   -These numbers represent the meaning of the word, so that words with similar meanings are located close to each other in that space.

  For instance:

  * vector("cat") is very close to vector("dog").

  * But it is far from vector("car").


![emadding2](../images/empadding2.png)


## Fact:
   Embedding first 🎯

     Any input (word, token, or item) is converted into a numerical vector.
     This step transforms the raw data (text, ID, etc.) into a form that the computer can work with.

   Encoder next 🧠

     The encoder takes these vectors (the embeddings) and passes them through layers of neural networks (like attention, RNN, CNN…).
     The goal is to extract a deeper representation that captures more meaning and context.








