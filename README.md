# NLP-HW1
#700772575
#Nithin Gundapu

Q2.2 — Mini‑BPE Code (README Explanation)
This script implements a tiny version of Byte Pair Encoding (BPE):

It converts each word into a list of characters (with _ at the end).

Counts how often each bigram (pair of symbols) appears.

Repeatedly merges the most frequent bigram.

Stores all merges in order.

Uses the learned merges to segment new words.

Output
The script prints:

the top merge at each step

the final list of merges

segmentations for:
new, newer, lowest, widest, newestest

This demonstrates how BPE learns reusable pieces like new, low, er, est, etc.

Q5 — Tokenization ( README Explanation)
This script compares three tokenization methods:

Naive tokenization: uses .split(), which simply splits on spaces and keeps punctuation attached.

Manual tokenization: uses a regex to remove punctuation and split contractions more cleanly.

spaCy tokenization: uses a real NLP tokenizer that separates punctuation, handles contractions, and follows linguistic rules.

The script prints:

the tokens from each method

and the differences between manual and spaCy tokenization

This shows how simple tokenizers can fail on punctuation and contractions, while spaCy produces more accurate linguistic tokens.

