# CardMemory
 // Card Memory Game
This SwiftUI application is a simple memory card game where players match pairs of cards. The objective is to find all pairs with the least number of turns to maximize the score.
// Fundamental Items
To ensure the project meets the grading criteria, the following fundamental items are implemented:
- Correctly imported and used Standard Library module: The `SwiftUI` framework is imported and used throughout the program to create the user interface and handle user interaction.
// Features
- A standard 52-card deck where players match cards by rank and suit.
- Score tracking to count the number of matches made.
- Simple persistence to store the high score between game sessions using `UserDefaults`.
// Requirements
- iOS 14.0+
- Xcode 12.0+
// Installation
1. Clone the repository or download the project zip. 2. Open the file with Xcode.
3. Select an iOS simulator or connect an iOS device. 4. Build and run the application (`Command + R`).
// Usage
Upon launching the app, the user is presented with a grid of face-down cards. Tapping a card flips it over. The objective is to remember the positions of different cards and match pairs by flipping over two of the same cards consecutively.
