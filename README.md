# Checkpoint-Algorithms
1. Prompt the user to enter a sentence ending with a period.
2. a.Read the sentence and store it in a variable.
   b.verify if the sentence ends with a point .
3. Initialize three counters: length (n), word_count (i), and vowel_count (v) to 0.
4. For each character in the sentence:
   a. If the character is a letter:
      i. Increment the length counter. n=n+1
      ii. If the character is a vowel, increment the vowel_count counter. v=v+1
   b. If the character is a space:
      i. Increment the word_count counter. i=i+1
5. Add 1 to the word_count counter to account for the last word. i=i+1
6. Print the length (n), word_count (i), and vowel_count (v) counters.
