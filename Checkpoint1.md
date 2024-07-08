# **Checkpoint1**


To implement the first checkpoint, we need to select and implement two automatic evaluation metrics that capture the characteristics of improved argument generation in terms of appropriateness. 
Given that we do not have parallel data, we'll focus on metrics that can evaluate text quality and appropriateness indirectly.

## Proposed Metrics
**Perplexity:** This metric measures how well a language model predicts a given text. Lower perplexity indicates that the text is more fluent and natural according to the model.

**Semantic Similarity:** This metric evaluates how semantically similar the generated text is to the original text, ensuring the core meaning is preserved while making the argument more appropriate.

## Implementation Steps

## Perplexity:
We will use a pre-trained language model to calculate the perplexity of the generated texts. Lower perplexity scores indicate better fluency and coherence.

## Semantic Similarity:
- We will use a pre-trained transformer model (like BERT) to compute embeddings for the original and improved texts.
- Calculate the cosine similarity between these embeddings to assess how well the improved texts preserve the original meaning.

## Why These Metrics?
### Perplexity:
It provides a measure of the fluency and coherence of the text. A lower perplexity score generally indicates that the text is more natural and easier to read, which is crucial for making arguments more appropriate.


### Semantic Similarity:
It ensures that the core meaning of the original argument is preserved in the improved text. High semantic similarity indicates that the argument remains true to its original intent, which is essential for maintaining the validity of the argument while making it more appropriate.
Let's start by loading the data and implementing these metrics.
