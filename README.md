# CSC649 Setup Activity

## Overview
This Python program accepts a sentence from the user, counts the total number of words, and calculates the total character count including spaces. If the input is empty, a warning message is displayed.

## How to Run
1. Open the project in PyCharm.
2. Run `main.py`.
3. Enter a sentence when prompted.

## Test Results
- **Normal Sentence:** Inputting `"Hello world"` outputs 2 words and 11 characters.
- **Empty Input:** Pressing Enter displays `"You did not enter a sentence."`.
- **Extra Spaces:** Inputting `"   Hello   World   "` correctly identifies 2 words.

## Limitation
Word counting relies on whitespace splitting, so punctuation attached to words (e.g., `"hello,"`) is counted as part of the word.