# Slavic_valency_Slovo
This repository contains data used for my paper "Valency patterns across Slavic: insights from a token-based cross-linguistic perspective" submitted to Slovo

If you use this dataset, please cite:
Say, Sergey. 2026. Dataset for "Valency patterns across Slavic: insights from a token-based cross-linguistic perspective". GitHub repository.

Two data sources are used in this study, stored in two separate folders: UD_data and BivalTyp_data, as described below.

# UD_data

For the analysis of valency patterns in Slavic languages at the corpus-token level, I used ten preprocessed datasets from Universal Dependencies (UD). Due to file size limitations, the datasets are stored in three archives, representing East, West, and South Slavic languages, respectively. Each dataset is organized identically, with rows representing individual corpus tokens (verb dependents) and columns representing their various attributes, either extracted directly from UD or created during data preprocessing, as described in the article. The two most important attributes are stored in the "encoding device" and "argumenthood" columns. The "encoding device" schematically represents the argument-coding device used with a specific dependent, typically a morphological case (e.g., DAT) or a case–preposition combination (e.g., "naACC"). Argumenthood is a binary annotation, where 1s and 0s correspond to verb dependents identified as arguments and adjuncts, respectively, by the frequency-based algorithm described in the paper.

# BivalTyp_data

This folder contains several files representing the latest development version of the BivalTyp database, as available in October 2025, covering 149 languages, including the ten Slavic languages analyzed from a token-based perspective. The four files in this folder contain the following data:

- "predicates.xlsx" contains the list of 130 sentences included in the BivalTyp questionnaire, along with some of their basic attributes.

- "languages_preprocessed.xlsx" contains metadata on the 149 languages in the BivalTyp sample, as stored in the database. This metadata includes genealogical and geographical information, names of contributors, and other relevant details.

- "data_for_download_preprocessed.xlsx" contains full database entries for all languages for which such entries are available, including translated sentences, their glosses, and other information, covering the ten Slavic languages as well.

- "languages_everything.xlsx" contains attributes of 145 languages, mainly calculated based on the actual content of the database, including transitivity prominence values, entropy of the observed distribution of verbs among valency classes, etc. (Four languages were excluded from the analysis due to the scarcity of data.)
