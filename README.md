# QuizBot

![QuizBot Logo](https://quizbot.ai/assets/logo.png)

QuizBot is an interactive web-based quiz application designed to streamline the process of creating, importing, and managing quizzes. Leveraging Moodle XML file formats, QuizBot allows educators and quiz creators to effortlessly import questions and deploy engaging quizzes for users.

Visit [QuizBot.ai](https://quizbot.ai/) for more information and online access.

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
  - [Importing Questions](#importing-questions)
  - [Taking the Quiz](#taking-the-quiz)
- [Supported File Formats](#supported-file-formats)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Moodle XML Import:** Easily import quizzes created in Moodle using XML files.
- **Multiple Question Types:** Supports multiple-choice questions with customizable options.
- **Progress Tracking:** Visual progress bar to monitor quiz completion.
- **Score Display:** Real-time score tracking and final results with percentage.
- **Responsive Design:** Optimized for various devices and screen sizes.
- **User-Friendly Interface:** Intuitive design for seamless user experience.
- **Error Handling:** Displays debug information for troubleshooting.

## Demo

Experience QuizBot in action by visiting our website:

🔗 [https://quizbot.ai/](https://quizbot.ai/)

## Installation

To run QuizBot locally, follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/quizbot.git
   ```

2. **Navigate to the Project Directory:**

   ```bash
   cd quizbot
   ```

3. **Open the Application:**

   Simply open the `quizbot.html` file in your preferred web browser.

   ```bash
   open quizbot.html
   ```

   or double-click the `quizbot.html` file to launch it.

## Usage

### Importing Questions

1. **Prepare Your File:**

   - **Moodle XML:** Ensure your quiz questions are formatted in Moodle XML.
   - **Text File:** Alternatively, use a plain text file with questions structured appropriately.

2. **Upload the File:**

   - Click on the **"Import Questions"** section.
   - Select your `.xml`, `.txt`, or `.html` file using the file input.

   ```html
   <input type="file" id="fileInput" accept=".xml,.txt,.html" />
   ```

3. **Start the Quiz:**

   Once the file is successfully uploaded and parsed, the quiz will initialize automatically.

### Taking the Quiz

1. **Navigate Through Questions:**

   - Use the **Previous** and **Next** buttons to move between questions.

2. **Select an Answer:**

   - Click on an option to select your answer. Selected options are highlighted for clarity.

3. **Check Your Answer:**

   - Click the **"Check Answer"** button to validate your choice. Correct answers are highlighted in green, while incorrect ones in red.

4. **View Progress:**

   - The progress bar at the top indicates your completion status.
   - Your current score is displayed above the quiz.

5. **Final Results:**

   - Upon completing all questions, your final score and percentage will be displayed.

## Supported File Formats

- **Moodle XML (`.xml`):**
  
  QuizBot fully supports importing quizzes formatted in Moodle's XML schema. This allows for seamless integration with Moodle-based quizzes.

- **Plain Text (`.txt`):**

  For simpler use cases, plain text files with structured questions can also be imported.

- **HTML (`.html`):**

  Import quizzes from HTML files containing structured question formats.
