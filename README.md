# Using TreeTagger trained with modern- language data on John Walker’s 18th century dictionary

Can we use a POS-tagging tool to measure a language evolution through centuries, especially recognize words that have become obsolete? How this tool manage to adapt to an older language state than the one it has been trained with? To answer these interrogations we runned TreeTagger, trained to identify and categorize words of modern english, on John Walker's *Critical Pronouncing Dictionary* dating back to 1791.

In this github repository you will find every **data** used and obtained and in the study.

*Ce travail est l’œuvre conjointe d’étudiants de la Licence Informatique et de la Licence d’Études Anglophones de Paris Diderot. Il a été financièrement supporté par le programme IdEx Université de Paris ANR-18-IDEX-0001*

### Data

- [Walker](Data/WalkerA-Z_v0.4.xml) : the source file containing Walker's dictionary's content (courtesy of N. Trapateau).
- [formatted_Walker](Data/formatted_Walker.txt) : the file obtained using [separateur.py](Code/separateur.py) plus a few manual adjustements.

### Code

- [separateur.py](Code/separateur.py) : to collect texts between a specific XML balise ( <balise> <\\balise> form ).

### Results

- [tree_tagger_res](Result/tree_tagger_res) :
- [unknown_lemmas](Result/unknown_lemmas) : the list of all the "unknown" tagged lemmas from the result.

### Documents

The docuements presenting the research and its results :
- The [abstract](Documents/Abstract.pdf)
- The [poster](Documents/Poster.pdf)

### Authors
- François HUANG
- Blanche MIRET
- Preethi SRINIVASAN
- Dao THAUVIN
