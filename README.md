# Using TreeTagger trained with modern- language data on John Walker’s 18th century dictionary

In this github project you will find every **data** obtained and used in this study.

## Data

- [Walker](Data/WalkerA-Z_v0.4.xml) : the source file containing Walker's dictionary's content (courtesy of N. Trapateau).
- [formatted_Walker](Data/formatted_Walker.txt) : the file obtained using [separateur.py](Code/separateur.py) plus a few manual adjustements.

## Code

- [separateur.py](Code/separateur.py) : to collect texts between a specific XML balise ( <balise> <\\balise> form ).

## Results

- [tree_tagger_res](Result/tree_tagger_res) :
- [unknown_lemmas](Result/unknown_lemmas) : the list of all the "unknown" tagged lemmas from the result.

### Documents

The docuements presenting the research and its results :
- The [abstract](Documents/Abstract.pdf)
- The [poster](Documents/Poster.pdf)
