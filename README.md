# _Greene's Groatsworth of Wit_ data
This repository contains data associated with Brett Greatley-Hirsch, Andrew Hadfield, and Rachel White, “Upstart Crows and Red Herrings: Thomas Nashe and _Greene's Groatsworth of Wit_”, _Shakespeare Quarterly_. For more information, please consult the published article.

The data is released under a [CC BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).

[corpus.csv](corpus.csv) lists the corpus of 22 representative sole-authored, well-attributed prose works by Henry Chettle, Robert Greene, and Thomas Nashe, as well as _Greene's Groatsworth of Wit_ itself (split into the epistle and remainder), along with their dates of first publication, the source texts used, and total word tokens.

[Delta_1098bsl-50mffwnpp.csv](Delta_1098bsl-50mffwnpp.csv) tables word-frequency counts (as a proportion of total tokens) for the top 50 most frequent function words, excluding personal pronouns, in 1098-word non-overlapping segments (with any remaining segments excluded). 

[SVM_1098bsl-mids.csv](SVM_1098bsl-mids.csv) tables word-frequency counts (as a proportion of total tokens) for 206 “middling” words present in no fewer than 25% and no more than 75% of 1098-word non-overlapping segments (with any remaining segments excluded).

[Zeta-100pos3grams-markers.xlsx](Zeta-100pos3grams-markers.xlsx) tables 100 Nashe and Chettle–Greene part-of-speech 3gram markers with their Zeta scores, using 1098-word non-overlapping segments.

[Zeta-100pos3grams.csv](Zeta-100pos3grams.csv) tables the proportion of Nashe and Chettle–Greene part-of-speech 3gram markers (counted as a proportion of all part-of-speech 3grams) for each 1098-word non-overlapping segment.
