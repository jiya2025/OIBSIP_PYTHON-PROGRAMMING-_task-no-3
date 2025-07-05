# OIBSIP_PYTHON-PROGRAMMING-_task-no-3

 🎯 **Objective**:

To develop a **command-line password generator** in Python that:

* Accepts user input for password length and character types.
* Validates the input to prevent errors or weak passwords.
* Generates secure, randomized passwords using Python’s built-in libraries.
* Simulates AI-like behavior by guiding users, correcting mistakes, and adapting to user choices.

 🧰 **Tools and Technologies Used**:

| Tool / Module        | Purpose                                                            |
| -------------------- | ------------------------------------------------------------------ |
| **Python**           | Programming language used to write the script                      |
| **random** module    | For random selection of characters                                 |
| **string** module    | Provides sets of letters, digits, and symbols                      |
| **input()** function | To collect user preferences (password length, character types)     |
| **Control flow**     | `if`, `while`, and `try-except` for decision-making and validation |
| **print()** styling  | Used to enhance user interaction and display password tips         |


 🪜 **Steps Involved**:

 ✅ Step 1: Welcome and User Greeting

* Ask for the user’s name to personalize the interaction (adds an AI-like experience).
* Display a friendly introduction message.

 ✅ Step 2: Input for Password Length

* Prompt the user to enter a **numeric password length**.
* Use `try-except` to catch invalid input (e.g., letters or symbols).
* Use `while` loop to ensure length is at least 6 characters (security guideline).

 ✅ Step 3: Character Set Selection

* Ask the user (yes/no) whether to include:

  * Uppercase letters
  * Lowercase letters
  * Digits
  * Symbols
* If no types are selected, the program **intelligently defaults** to include all types (AI decision fallback).

✅ Step 4: Password Generation

* Using the `random.choice()` function, randomly pick characters from the user-defined pool.
* Combine them to form a password of the desired length.

 ✅ Step 5: Display Results

* Show the user the **random password** clearly.
* Provide a tip to store the password securely.

🎯 **Expected Outcome**:

| Feature                      | Result                                                    |
| ---------------------------- | --------------------------------------------------------- |
| ✅ Personalized Interaction   | User feels guided and supported like with an AI assistant |
| ✅ Input Validation           | Prevents errors due to invalid or missing input           |
| ✅ Secure Password Generation | Password includes random mix of characters for strength   |
| ✅ Flexible Configuration     | User chooses the type of characters to include            |
| ✅ Practical Usability        | Final password is ready to use and secure                 |
