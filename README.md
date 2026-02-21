# Mirror (CS50x Project)

## Project Overview
This project is an interactive Socratic Dialogue Engine developed in Scratch. Rather than a traditional game, it serves as a psychological mirror designed to help users identify logical and emotional inconsistencies in their personal desires and identities.

## Intention
The core objective is to guide users toward truth and freedom by stripping away societal and mental "bondages" and hypocrisies. By repeatedly asking "Why?" and diving deeper into the fragile foundation, the program forces a confrontation with one's root motivations to see if they are truly connected to self or externally "feeded".

## Technical Implementation
This project satisfies all CS50x requirements through the following technical features:

* **Custom Blocks with input**: Uses a `Challenge` block that accepts a `Statement` input into a new question, repeat the user's words back to them.
* **The "Why" Loop**: A `repeat 4` loop handles the sequential "digging" into user inputs, updating a `User_Input` variable with each iteration.
* **The Condition**: Uses an `if/else` conditional to manage user gender and greet accordingly.
* **Message Signals**: Utilizes `broadcast` signals to coordinate sprites that display the final "First vs. Last" answers comparison.

## How to Run
1. Download the `Mirror.sb3` file from this repository.
2. Go to [Scratch (MIT)](https://scratch.mit.edu/projects/editor/).
3. Click **File > Load from your computer** and select the file.
4. Click the Green Flag to begin the reflection.
