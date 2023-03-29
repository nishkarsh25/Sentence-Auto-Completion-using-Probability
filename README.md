# Sentence Auto Completion using Probability

The provided code is a language model that:

- Downloads several books from the Gutenberg Project website
- Creates different n-gram models (unigram, bigram, trigram, and quadgram) based on the words in those books
- Defines a function called `suggest_next_word` that takes a sentence as input and suggests possible words that come after the sentence, based on the probability of occurrence of the next word given the last two or three words in the input sentence

To calculate this probability, the function looks up the counts of the relevant n-grams in the corresponding models, and divides the count of the relevant n-gram that ends with the suggested word by the count of the n-gram that ends with the last two or three words of the input sentence. If there is no such n-gram in the model, the function looks for the probability based on a shorter n-gram model (for example, if there is no trigram that ends with the suggested word, it looks for a bigram that ends with the last word of the input sentence).

Overall, this code can be used as a basic language model for generating sentences or predicting the next word given a partial sentence. However, it has some limitations, such as not taking into account the context of the sentence beyond the last few words, and not accounting for the grammatical structure of the sentence.
