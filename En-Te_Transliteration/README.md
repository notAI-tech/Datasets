# Why this project?

1. English Telugu transliteration has no or very few resources.
2. Telugu is written using English alphabet on most social media posts.
3. This project aims to help people working on NLP for Telugu language, by providing a good dataset and baseline models.

# Links and Description:

**V1:**
The first version contains data from two sources.

1. [en_te_wiki_titles](https://github.com/notAI-tech/Datasets/releases/download/En-Te_Transliteration/v1.en_te_wiki_titles.txt):

    contains 13,811 word en-te pairs, generated from Wikipedia by comparing titles of parallel articles.


2. [ni_bondha_comments](https://github.com/notAI-tech/Datasets/releases/download/En-Te_Transliteration/v1.ni_bondha_comment_words.txt):

    contains 24,757 word en-te pairs.
    
    The english versions of telugu words are obtained from the subreddit [r/Ni_Bondha](https://www.reddit.com/r/Ni_Bondha/).
    
    The corresponding telugu words are obtained by ranking transliterations of the subreddit comments from multiple models and APIs,
  using a [flair](https://github.com/zalandoresearch/flair) based character lm trained on Telugu text.
  
    Please note that english words are not lower-cased in this data. Since the english words are human written, we decided to retain the capitalization information in this release. Only punctuation was removed.


# Our model:
  https://github.com/notAI-tech/DeepTranslit/ now supports Hindi, Telugu, Malayalam, Marathi, Kannada, Tamil
