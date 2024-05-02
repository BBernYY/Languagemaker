# Language making program
Title speaks for itself
## Defining a word
> A word has a certain amount of syllables: these syllables are built using vowels and consonants flowing from high-to-low-to-high contstrictions (vowels having the least).
* `krink`: ✅ word
* `rkink`: ❌ not a word

### Determining the amount of syllables per word
The amount of syllables in a word should preferably be related to either

1. The frequency of the word in the language the word is translated from, or
2. The amount of syllables of the word in the language it is translated from
This connection is generally non-linear, since the amount of possible letters makes for exponentially more possible syllables, leading to shorter optimized words.

The best way to do this, is probably to calculate how much information can be stored in each syllable, and then calculate the word based on frequency.

### Pre- and suffixes
It should also be possible to add pre- and suffixes to words, to account for conjugation.