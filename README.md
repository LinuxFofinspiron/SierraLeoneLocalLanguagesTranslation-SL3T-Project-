# SierraLeoneLocalLanguagesTranslation-SL3T-Project-
This is an open source repo in which Sierra Leoneans and other people familiar with the local dialects of Sierra Leone interact so as to build a machine translation system for these languages.
The machine translation system intended here should be capable of translating sentences between any two languages. It should be capable of also recognizing the dialect automatically.
We start by building a dataset of texts in a source language together with a groundtruth translation in a target language. The file `dataset.csv` contains sample translations. The format 
of the file is such that each sentence translation is being done on its own line as given below:
<source-sentence>**<source-dialect>:<target-sentence>**<target-dialect>
where <source-dialect> and <target-dialect> are the shorthand representations of the languages; for instance: KR for Krio, MN for Mende, TM for Temne, LM for Limba and so on(to be agreed upon for others)...
As a baseline we should target a thousand translations between any pair of language; afterwards we proceed to model building where we create deep learning models to aid us with the stated tasks - Dialect Recognition and Machine Translation.
