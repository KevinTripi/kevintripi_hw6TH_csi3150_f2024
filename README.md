# Demo Quiz App (kevintripi_hw6TH_csi3150_f2024)
## 1. Problem Statement
The **Demo Quiz App** is a simple and easy way to test what you know. It asks you a series of multiple-choice questions, and you have *15 seconds* to pick an answer for each one. They are on html, sql, php, and css. The app tells you right away if you got it right or wrong. also keeps track of your score as you go. When you finish, it shows you how well you did and gives you the option to try again. It’s pretty *easy to use* and makes learning fun.

## 2. Functional Features
- **Start Quiz**: Begin the quiz with a single click for button.
- **Timed Questions**: Each question must be answered within *15 seconds*.
- **Instant Feedback**: See if your answer is right after you pick.
- **Score Tracking**: Your score is updated as you play.
- **Results Page**: Get a summary of your performance at the end.
- **Retry Option**: Replay the quiz anytime to improve your score.

## 3. Directory Structure
The app's files are organized as follows:
- **`index.html`**: Contains the main structure of the app and links to other files.
- **`style.css`**: Adds styling like colors, fonts, and layout to make the app look great.
- **`questions.js`**: Stores the quiz questions and their correct answers.
- **`quizApp.js`**: Manages all the app's functionality, like starting the quiz, tracking answers, and showing results.

## 4. Codebase Explanation
### **index.html**
- Sets up the app's structure, like the quiz box, buttons, and result display.
- Links to `style.css` for design and `quizApp.js` for functionality.

### **style.css**
- Adds global styling, such as a purple background and clean fonts fronts onlie.
- Styles interactive elements like buttons and options.
- Highlights correct answers in **green** and incorrect ones in **red**. (also x and checked icons)

### **questions.js**
- Stores the quiz data in a simple array of objects. Each object includes:
  - The question text.
  - A list of possible answers.
  - The correct answer.

### **quizApp.js**
- Handles app logic, like:
  - **Starting the quiz**: Shows the first question and starts the timer.
  - **Tracking answers**: Updates the score if the user selects the correct answer.
  - **Displaying results**: Shows the final score when the quiz is finished.
