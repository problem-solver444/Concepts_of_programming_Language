# Explanation and Overview of Python Programs

This section provides an in-depth explanation of the three Python programs in this repository: **Daily Steps Tracker**, **Library Book Borrowing Analysis**, and **Word Scramble Game**. Each program is designed to handle specific tasks with user interaction and outputs meaningful results. Below, you will find an overview of each problem and a step-by-step explanation of how the program functions.

---
## Video Tutorial
- [Watch the First Video Tutorial](https://drive.google.com/file/d/1AM8uRQWylaYPRl4_2d0dgJlpdnwgFkou/view?usp=drive_link)
- [Watch the Second Video Tutorial](https://drive.google.com/file/d/1ntDsoDDRb73D9KDlbAD4gK2H18_Dq5fG/view?usp=drive_link)

---

## Problem 1: Daily Steps Tracker

### Overview
The **Daily Steps Tracker** program is designed to help users track the number of steps they take each day over the course of a month. By taking the user's input of daily steps, the program calculates important statistics such as the highest and lowest step counts, the average steps per day, and sorts the values in descending order for further analysis.

### How It Works
1. **Input Collection**: 
   - The program prompts the user to input daily step counts, which are entered as space-separated values. 
   - Example: `8000 7500 9000 10000 12000 11000 9500 8700 8900 9100`

2. **Data Processing**:
   - The program stores the input in a list and converts each entry to an integer.
   - It then calculates the highest and lowest values using Python's built-in `max()` and `min()` functions.
   - The average number of steps is calculated by summing all values and dividing by the length of the list.

3. **Sorting**:
   - The program sorts the list of daily steps in descending order using Python’s `sorted()` function.

4. **Output**:
   - The program displays the highest and lowest step counts, the average steps, and the sorted step counts.

### Key Features
- Handles dynamic user input.
- Provides both statistical and comparative analysis (highest, lowest, and average).
- Displays data in an ordered list (descending).

---

## Problem 2: Library Book Borrowing Analysis

### Overview
The **Library Book Borrowing Analysis** program helps track books borrowed from a library over a month. Users can input the title of each borrowed book along with the number of days it was borrowed. The program calculates statistics such as the most borrowed book, the least borrowed book, the average number of days borrowed, and provides a list of unique titles.

### How It Works
1. **Input Collection**:
   - The program prompts the user to input the title of the borrowed book along with the number of days it was borrowed in the format `"Book Title - Days Borrowed"`.
   - Example: `The Great Gatsby - 5`, `1984 - 7`.

2. **Data Processing**:
   - Each record is parsed into the book title and the corresponding number of days borrowed.
   - The program aggregates the days for each book using a dictionary where the keys are book titles and the values are the total days borrowed.

3. **Statistics Calculation**:
   - The most and least borrowed books are determined using the `max()` and `min()` functions, respectively, based on the total number of days borrowed.
   - The average number of borrowing days is computed by summing all borrowed days and dividing by the number of unique books.

4. **Sorting**:
   - The books are sorted by the number of days borrowed, from most to least borrowed.

5. **Output**:
   - The program displays the most and least borrowed books, the average number of borrowing days, the unique titles, and the sorted list of books by the borrowing duration.

### Key Features
- Aggregates multiple borrowings for the same book.
- Provides insights into borrowing patterns (most and least borrowed books).
- Outputs sorted data for easy analysis.

---

## Problem 3: Word Scramble Game

### Overview
The **Word Scramble Game** program challenges the user to guess a word that has been scrambled. The program randomly selects a word from a predefined list, scrambles the letters, and presents the scrambled word to the user. The player has a limited number of attempts (5) to guess the correct word. If the player fails to guess correctly within the allowed attempts, the program reveals the correct word.

### How It Works
1. **Word Selection**:
   - The program randomly selects a word from a predefined list of words, such as "python", "algorithm", "developer".

2. **Scrambling the Word**:
   - The selected word is scrambled by shuffling the letters randomly using Python’s `random.shuffle()` function.

3. **User Input**:
   - The player is prompted to guess the word based on the scrambled version.
   - The program allows the user 5 attempts to guess the correct word.

4. **Game Flow**:
   - After each guess, the program checks if the guess matches the original word.
   - If the guess is correct, the player is congratulated. If the guess is incorrect, the number of remaining attempts is reduced by 1.
   - If the player runs out of attempts, the program reveals the correct word.

5. **Output**:
   - The program displays feedback based on the user's guesses, including the number of attempts left or the correct word if all attempts are used.

### Key Features
- Random word selection and scrambling.
- Player feedback after each guess.
- Handles user inputs gracefully with a limited number of attempts.
- Reveals the correct word if the player is unsuccessful.

---

## Conclusion

Each of these Python programs was designed to offer interactive experiences and perform useful analyses. From tracking daily steps to analyzing book borrowings and testing word guessing skills, these programs utilize core Python functions and user input processing to deliver valuable results.

---
