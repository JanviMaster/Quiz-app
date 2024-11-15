<h1>Quiz App</h1>

  <p>This is a simple <strong>Quiz Application</strong> built using React. The app allows users to answer a series of multiple-choice questions and displays the final score at the end.</p>

  <h2>Features</h2>
  <ul>
    <li>Interactive quiz with multiple questions.</li>
    <li>Dynamic scoring based on correct answers.</li>
    <li>Displays the user's final score upon completion.</li>
    <li>Option to restart the quiz after finishing.</li>
  </ul>

  <h2>Technologies Used</h2>
  <ul>
    <li><strong>React</strong>: For building the user interface and managing the state.</li>
    <li><strong>JavaScript</strong>: Core language for adding functionality.</li>
    <li><strong>HTML/CSS</strong>: For structuring and styling the app.</li>
  </ul>

  <h2>Components</h2>
  <h3>1. Quiz Component</h3>
  <ul>
    <li>Handles the main quiz logic.</li>
    <li>Tracks the current question, selected option, and score.</li>
    <li>Renders each question and options dynamically from the <code>QuizData</code>.</li>
    <li>Manages the flow of the quiz and shows results when completed.</li>
  </ul>

  <h3>2. QuizResult Component</h3>
  <ul>
    <li>Displays the final score after the quiz is completed.</li>
    <li>Provides an option to restart the quiz.</li>
  </ul>
  <li><strong>Key Features:</strong>
            <ul>
                <li>Displays the user's score out of the total number of questions.</li>
                <li>Includes a "Restart Quiz" button that resets the quiz state and allows the user to retake it.</li>
            </ul>
        </li>
        <li><strong>Props Passed:</strong>
            <ul>
                <li><code>score</code>: The final score achieved by the user.</li>
                <li><code>totalQuestions</code>: The total number of questions in the quiz.</li>
                <li><code>restartQuiz</code>: A function to reset the quiz.</li>
            </ul>
        </li>
    </ul>
    <h2>Installation and Setup</h2>
    <ol>
        <li>Clone the repository to your local machine:
            <pre><code>git clone https://github.com/your-username/quiz-app.git
cd quiz-app</code></pre>
        </li>
        <li>Install the required dependencies:
            <pre><code>npm install</code></pre>
        </li>
        <li>Start the development server:
            <pre><code>npm start</code></pre>
        </li>
        <li>Open your browser and navigate to <code>http://localhost:3000</code> to view the app.</li>
    </ol>
    <h2>Usage</h2>
    <ol>
        <li>Open the app in your browser.</li>
        <li>Answer the multiple-choice questions by selecting one option.</li>
        <li>Navigate through the questions using the "Next" button.</li>
        <li>At the end of the quiz, view your final score on the result page.</li>
        <li>Use the "Restart Quiz" button to retake the quiz.</li>
    </ol>
    <h2>Future Enhancements</h2>
    <ul>
        <li>Add a timer for each question to make the quiz more challenging.</li>
        <li>Include a leaderboard to track high scores.</li>
        <li>Allow users to select difficulty levels (easy, medium, hard).</li>
        <li>Add animations and transitions for a better user experience.</li>
        <li>Support for fetching quiz data dynamically from an API.</li>
    </ul>
