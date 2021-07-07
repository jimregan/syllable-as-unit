`run-phonetisaurus-on-timit-kaggle.ipynb` sets up and runs Phonetisaurus on the TIMIT dictionary, based on Kaggle. The original notebook is available [on Kaggle](https://www.kaggle.com/jimregan/run-phonetisaurus-on-timit-kaggle), where the output of the notebook's execution can also be seen.

It uses Phonetisaurus; of the various grapheme-to-phoneme converters, Phonetisaurus uses graphones (grapheme-phoneme pairs), performs the alignment itself (that is, without the specific pairs of allowable graphones, which Google's Festus requires), and is OpenFST-based.


`syllabify-phonetisaurus-output.ipynb` syllabifies the output of Phonetisaurus, as above. Parts of it are a reimplementation of [this script](http://web.archive.org/web/20100614180508/http://semarch.linguistics.fas.nyu.edu/barker/Syllables/syllabify.pl)

It has no external dependencies.
