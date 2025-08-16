## What is an Encoder?
  * Function: Converts the original data (like text, image, or audio) into a compressed internal representation (latent representation).

  * Works like a feature extractor.

  * Output: A numerical vector that summarizes the meaning or important features of the data.

✅ Example (Text):
    Input: "I love cats"
    Encoder output: [0.21, -0.57, 0.89, ...] (a vector that represents the meaning).

  ![encoder](../images/encoder.png)

## What is an Decoder?
A Decoder is a core component in AI models. Its role is to transform the latent representation coming from the Encoder into human-readable outputs.

## How Decoder works?

  * It receives the vector produced by the Encoder.

  * It starts generating the output gradually (step by step).

  * In text: it generates one word at a time (often one word per second), then uses that word together with the latent vector to generate the next word, and so on until the full sentence is produced.

  * In images: it generates pixels progressively until the complete image is formed.

  ![decoder](../images/decoder.png)

