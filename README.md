# React Quiz App
![Quiz](https://github.com/bharani-developer/quiz/blob/main/public/quiz1.png)
![Quiz](https://github.com/bharani-developer/quiz/blob/main/public/quiz2.png)
![Quiz](https://github.com/bharani-developer/quiz/blob/main/public/quiz3.png)
![Quiz](https://github.com/bharani-developer/quiz/blob/main/public/quiz4.png)

## Overview

React Quiz App is an interactive web application that presents users with 50 important React questions. The app features a timer for each question, tracks high scores, and allows users to reattempt questions to improve their scores.

## Features

1. **Question Bank**: 50 essential React questions.
2. **Timed Questions**: Each question comes with a timer to add a sense of urgency.
3. **High Score Tracking**: Keeps track of the highest score achieved by the user.
4. **Reattempt Option**: Users can reattempt questions to improve their scores.

## Usage

### 1. Start the Quiz
   - Click the "Start Quiz" button on the homepage to begin.

### 2. Answer Questions
   - Each question is displayed with multiple-choice answers.
   - Select the correct answer before the timer runs out.

### 3. View Score
   - At the end of the quiz, your score will be displayed along with the high score.

### 4. Reattempt Questions
   - You can reattempt the quiz to try and beat your previous high score.

## Code Structure

### **`src/App.js`**
Main component that manages the state and renders the main layout.

### **`src/components/Quiz.js`**
Component to handle the quiz logic and render questions.

### **`src/components/Question.js`**
Component to display a single question with answer choices and timer.

### **`src/components/Score.js`**
Component to display the user's current score and high score.

### **`src/components/HighScore.js`**
Component to display and manage the high score.

## Components

### App.js
The main component where the state is managed. It includes functions to handle the quiz start, track the score, and update the high score.

### Quiz.js
This component handles the quiz logic, fetching questions, managing the timer, and calculating the score.

### Question.js
This component represents a single question in the quiz. It includes answer choices and a timer.

### Score.js
This component displays the current score of the user and the high score.

### HighScore.js
This component manages and displays the high score.

## Technologies Used

- **Frontend**: React, React Router, CSS
- **State Management**: React Context API or Redux

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

**Your Name** - [bharani.developer@gmail.com](mailto:bharani.developer@gmail.com)

**Project Link**: [https://github.com/bharani-developer/quiz](https://github.com/bharani-developer/quiz)
