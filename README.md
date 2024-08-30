# TABIND Scrabble Project

## Project Overview

The TABIND Scrabble Project is a Python-based application designed to generate all possible valid words from the letter combination "tabind". The project leverages permutations of the letters and filters these permutations against a comprehensive dictionary to identify valid words. This project can be adapted to work with any set of letters.

## Features

- **Permutation Generation:** Generates all possible permutations of the given letters.
- **Dictionary Filtering:** Filters generated permutations against a dictionary to ensure only valid words are retained.
- **Up-to-Date Word List:** Downloads the latest word list from a public repository to ensure accuracy.

## How It Works

1. **Loading the Dictionary:** 
   - The dictionary is loaded from a text file, and unnecessary single-letter combinations are filtered out, except for valid single letters like 'a' and 'i'.

2. **Generating Permutations:**
   - The program generates all possible permutations of the given letter set, from single letters to the full combination.

3. **Filtering Valid Words:**
   - The generated permutations are filtered against the dictionary, and only valid words are retained and sorted.

4. **Downloading the Word List:**
   - A word list is downloaded from a specified URL and used as the dictionary for filtering valid words.

## Installation

To use this project, clone the repository and make sure you have Python installed. The required libraries are `itertools` and `urllib`.

```bash
git clone https://github.com/yourusername/tabind-scrabble-project.git
cd tabind-scrabble-project


