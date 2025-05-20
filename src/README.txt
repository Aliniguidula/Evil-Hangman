1. Collaborators
I completed this project by myself.

2. Cohesion and Coupling Analysis
Cohesion

The program has a high cohesion, with well-defined classes and methods tailored to their respective responsibilities.
EvilHangman handles game logic and user interaction.
Solution is responsible for tracking the state of the guessed word.
Testing classes focus on checking the functionality of their respective components.
Each method has a specific purpose, enhancing readability and maintainability.

Coupling

The program has low coupling, with minimal dependencies between classes.
EvilHangman interacts with Solution primarily through method calls.
Solution maintains internal logic for managing the target word, without needing direct interaction with the word families or user input.
This low dependency makes unit testing and potential future modifications easier without risking bigger code changes.

3. How to Run the Program
Run the game using the runner class: EvilHangmanRunner
Follow the on-screen prompts to guess letters until you either solve the word or exhaust your guesses.