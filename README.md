# CSC649 Experiment 1: Word and Character Counter

## What the program does
Asks the user to enter a sentence, then displays the word count and the
character count (including spaces). If the input is empty or only spaces,
it shows a message instead.

## How to run
1. Open the project in PyCharm.
2. Open main.py and click Run (or run `python main.py` in the terminal).
3. Type a sentence when prompted and press Enter.

## Test results
| Test | Input | Output |
|---|---|---|
| Normal sentence | python is nice | Words: 3, Characters: 13 |
| Empty input | (nothing) | You did not enter a sentence. |
| Extra spaces | "Hello    world" | Words: 2, Characters: 14 |

## Limitation
The character count includes leading, trailing and extra spaces, so spacing
affects the result. Punctuation is also counted as characters.