# BHSA2RRG

This project is an extension of [Dirk Roorda's tree-writing grammar](https://nbviewer.jupyter.org/github/annotation/tutorials/blob/master/bhsa/trees.ipynb) of Biblical Hebrew sentences in the [BHSA corpus](https://etcbc.github.io/bhsa/).

The present project is designed to format the BHSA syntax trees into Role and Reference Grammar (RRG)-like trees for the purpose of creating a database of RRG-trees as part of the Düsseldorf University-based [TreeGraSP research project](https://rrg-bh.phil.hhu.de/editor/index).

The BHSA2RRG formats the BHSA syntax trees in two significant ways:
* Represents the Hebrew text in phonological script (based on the Text-Fabric phono-package)
* Segmentates words with several referring morphemes into seperate constituents (leaves)
