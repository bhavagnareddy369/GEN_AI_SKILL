# Assignment 1: Byte Pair Encoding (BPE)

## Overview
This assignment implements the Byte Pair Encoding (BPE) algorithm using Python.

BPE is a subword tokenization technique that identifies frequently occurring adjacent token pairs and merges them to create larger tokens.

## Objective
- Understand the working of BPE tokenization.
- Split words into individual characters.
- Calculate individual token frequencies.
- Calculate adjacent pair frequencies.
- Compute normalized pair scores.
- Identify and merge the highest-scoring pair.
- Repeat the merging process to generate subword tokens.

## Input Dataset

| Word | Frequency |
|---|---:|
| low | 5 |
| lower | 2 |
| newest | 3 |
| wildest | 6 |

## Scoring Formula

The normalized pair score is calculated using:

\[
Score(A,B) = \frac{Freq(A,B)}{Freq(A)\times Freq(B)}
\]

Where:
- `Freq(A,B)` = Frequency of the adjacent token pair.
- `Freq(A)` = Frequency of the first token.
- `Freq(B)` = Frequency of the second token.

## Algorithm
1. Take the input words and their frequencies.
2. Split each word into individual characters.
3. Calculate individual token frequencies.
4. Calculate adjacent pair frequencies.
5. Compute the normalized score for each pair.
6. Select the pair with the highest score.
7. Merge the selected pair.
8. Recalculate frequencies and scores.
9. Repeat until the specified number of merges is completed.
10. Display the final tokenization.

## Technologies Used
- Python
- Google Colab
- Collections module (`Counter`)

## Files
- `BPE_Implementation.ipynb` - Complete Python implementation of the BPE algorithm.

## Conclusion
The assignment demonstrates how BPE builds subword tokens through iterative pair merging and how normalized scoring can be used to select token pairs.
