# Wordle Helper

A recursive C++ utility to assist in solving Wordle puzzles by filtering possible answers based on known letter positions and exclusions.

## Overview

This tool helps narrow down potential solutions for Wordle puzzles by:

- Accepting input strings indicating correct (green) and incorrect (yellow) letter placements.
- Filtering a dictionary of five-letter words to find all possible matches that fit the given constraints.

## Features

- **Green Letter Matching**: Specify which letters are correctly placed.
- **Yellow Letter Exclusion**: Indicate which letters are in the word but not in the specified positions.
- **Dictionary Filtering**: Uses a word list to suggest valid guesses.
