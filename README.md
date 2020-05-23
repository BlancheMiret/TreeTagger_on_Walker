# Using TreeTagger trained with modern- language data on John Walker’s 18th century dictionary

In this github project you will find every **data** obtained and used in this study.

## Data

- [Walker](Data/WalkerA-Z_v0.4.xml) : the source file containing Walker's dictionary's content (courtesy of N. Trapateau).
- [formatted_Walker](Data/formatted_Walker.txt) : the file obtained using [separateur.py](Code/separateur.py) plus a few manual adjustements, that is : corrections of (--See), (&amp)...

## Code

- [separateur.py](Code/separateur.py) : to collect texts between a specific XML balise ( <balise> <\\balise> form ).

## Results

- [tree_tagger_res](Result/tree_tagger_res) :
- [unknown_list_from_result](Result/unknown_list_from_result) : the list of all the "unknown" tagged lemmas from the result.
- Analyse des résultats ?

### Poster LATEX

The final poster had been made with Latex. You can find the Latex Code in the folder **PosterLatex**. The file to compile is **poster2.tex**.
