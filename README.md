# Difficulty viewing large code files?

If you're having trouble viewing large code files on GitHub, you may find it helpful to download a ZIP file containing the entire repository. To do so, follow these steps:

1. Click on the green "Code" button on the repository page.
2. Select "Download ZIP" from the dropdown menu.
3. Save the ZIP file to your computer.

This can be particularly useful if you're experiencing issues with GitHub's web interface or if you need to access the repository without an internet connection. If you have any questions or concerns, please don't hesitate to contact us. 
<img width="624" alt="image" src="https://user-images.githubusercontent.com/117291117/231703905-7469ae09-6d82-4f77-ad05-fa29142ac9a8.png">
# Sentence Auto Completion using Probability

The provided code is a language model that:

- Downloads several books from the Gutenberg Project website
- Creates different n-gram models (unigram, bigram, trigram, and quadgram) based on the words in those books
- Defines a function called `suggest_next_word` that takes a sentence as input and suggests possible words that come after the sentence, based on the probability of occurrence of the next word given the last two or three words in the input sentence

To calculate this probability, the function looks up the counts of the relevant n-grams in the corresponding models, and divides the count of the relevant n-gram that ends with the suggested word by the count of the n-gram that ends with the last two or three words of the input sentence. If there is no such n-gram in the model, the function looks for the probability based on a shorter n-gram model (for example, if there is no trigram that ends with the suggested word, it looks for a bigram that ends with the last word of the input sentence).

Overall, this code can be used as a basic language model for generating sentences or predicting the next word given a partial sentence. However, it has some limitations, such as not taking into account the context of the sentence beyond the last few words, and not accounting for the grammatical structure of the sentence.

# Input
<img width="250" alt="image" src="https://user-images.githubusercontent.com/117291117/228686202-3ee5ce5b-4b9d-4e0d-86d8-0062f7af9778.png">
<img width="200" alt="image" src="https://user-images.githubusercontent.com/117291117/228686313-5ab822c3-e7e7-489e-845b-0247a359ec7c.png">

# Output
<img width="275" alt="image" src="https://user-images.githubusercontent.com/117291117/228685592-95b54b10-e476-43c1-9065-f6358fdc24f4.png">
<img width="275" alt="image" src="https://user-images.githubusercontent.com/117291117/228685648-25d12931-7bd5-44cd-9b08-0e45dab85ea5.png">
