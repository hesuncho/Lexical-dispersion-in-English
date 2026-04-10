# Lexical-dispersion-in-English
The list of CIO words that were used for the study (total 325 words from CMU Dictionary)

cio.txt
The list of 325 CIO words collected from the CMU Pronouncing Dictionary, mentioned in the first paragraph of Section 4.1 (Data collection)
We collected English monosyllabic words with onset and coda (C1VC2), where C1 is not empty, V is /i:/
or /ɪ/, and C2 is an obstruent coda differing in voicing while sharing the same place of articulation (“CIO”).
The words were collected from the CMU Pronouncing Dictionary (American English, version 0.7b,
134,000 words) using R scripts. Homophones were treated as a single word; for example, leach/leech /li:tʃ/
- lich /lɪtʃ/ was counted as one minimal pair rather than two. There were 2,182 CVC words in the dictionary,
from which 325 CIO words were collected for our analysis.

cio_results.xlsx
The list of all possible CIO words, their scores, maxent values, P(word) obtained from the Phonotatic Learner (Hayes and Wilson 2008), mentioned in Section 5.1.1 (Step 1. Obtain P(word) for all the possible CIO words)
To generate hypothetical lexicons based on the phonotactic grammar of the actual lexicon, the
probabilities of all the possible CIO words (P(word)) were obtained. This includes non-existing but
phonotactically-possible English words, as well as existing ones. All possible CIO words are formed from
all possible combinations of consonants in the onset (22), vowels (/i,ɪ/) (2), and obstruents in the coda (16),
yielding a total of 704 (22 × 2 × 16 = 704).
