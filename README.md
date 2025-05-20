*Evil Hangman* 🪓

A twist on the classic Hangman game—this Java-based program secretly manipulates the hidden word to make the player's task as difficult as possible. Instead of committing to a single word from the beginning, the program dynamically updates its word choice to remain as ambiguous as possible, maximizing the challenge.

🔍 *Project Overview*

This project builds upon a basic Hangman implementation and transforms it into "Evil Hangman", where the program adapts after each guess to keep the player guessing for as long as possible. It uses word families and strategic partitioning to maintain the illusion of fairness while minimizing the user's chances of winning.

🧠 *Key Concepts*
- File I/O for loading dictionary words
- User Input via Scanner
- Dynamic word selection using HashMaps and ArrayLists
- Word families to group candidate words by pattern
- Good design principles like encapsulation, cohesion, and low coupling
- Basic unit testing to validate core functionalities

✨ *Features*
- Pattern-based word family generation
- Dynamically selects the largest word family after each guess
- Tracks incorrect and repeated guesses
- User-friendly prompts and error handling
- Clean code design with modular class responsibilities
