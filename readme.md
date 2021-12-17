
** Kate's Combo Words **

An all-in-one file (actually 4 files of various sizes, wait no, 3, github won't let me add the biggest) for using a range of different text-processing techniques, like vector embedding, word frequencies, and pronunciations.  I've removed the bottom % of least-frequent words (measured by a combination of Subtlex and Google Trillion data) to remove all the extremely rare or junk words from the corpora.

XXSmall is small enough to be uploaded to Glitch and the P5 editor, but doesn't contain many normal-but-less-common words.


Columns: 

0: word
1: total wordcount in Subtlex, subtitle frequencies (https://www.kaggle.com/lukevanhaezebrouck/)
2: total wordcount in the Google 3 Trillion web scrape (https://www.kaggle.com/rtatman/english-word-frequency 
3: pronunciation from the CMU Pronouncing Dictionary (https://github.com/Alexir/CMUdict)
4: Part-of-speech confidence (from Subtlex)
5: Part-of-speech (from Subtlex)
6: Allison Parrish's pronunciation vectors (trained on the CMU pronunciations) https://github.com/aparrish/phonetic-similarity-vectors 
7: Word meaning vectors (100d model) (https://www.kaggle.com/anindya2906/glove6b)
