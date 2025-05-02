# Analyze Sentence Algorithm

This algorithm, `AnalyzeSentence`, is designed to process a user-inputted sentence that ends with a period (`.`). It reads the sentence character by character and calculates three important properties:

- **Sentence Length:** The total count of all characters in the sentence, including spaces and the final period.
- **Word Count:** The number of words present in the sentence. It assumes that words are separated by a single space. The counter is initialized to 1 to account for the first word.
- **Vowel Count:** The total number of vowel characters (both lowercase: a, e, i, o, u; and uppercase: A, E, I, O, U) found within the sentence.

The algorithm iterates through the input sentence, character by character, until the period is encountered, incrementing the respective counters based on whether the current character is a space or a vowel. Finally, it outputs the calculated sentence length, word count, and vowel count.