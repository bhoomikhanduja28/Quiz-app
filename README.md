📚 Description
QuizApp is a simple console-based Python quiz application that allows teachers to add multiple-choice questions and students to take quizzes and view their scores. It also maintains and displays a summary of class results.

🚀 Features
Teachers can:

Add multiple questions to the quiz with options and correct answers.

Students can:

Choose a quiz uploaded by a teacher.

Answer multiple-choice questions.

View their score after completing the quiz.

View all students' scores through the "Class Result" feature.

🛠️ Technologies Used
Python 3

tabulate module (imported, but not actively used in this version)

📁 Project Structure
The app uses two main classes:

Teacher Class
Class-level lists:

quizapp — stores all teacher-created quizzes.

score — unused, can be removed.

Attributes:

teacher_name

question (list of questions)

options (list of options per question)

correct_answer (list of correct answers)

Methods:

question_answer(obj, i) — displays question and options.

correct_ans(ans, i, obj) — checks if the answer is correct.

Student Class
Class-level lists:

quizer — stores student names and scores.

table — unused, can be removed.

Attributes:

name

total_score

Methods:

tot_marks() — displays all students and their scores.

🎮 How to Use
Run the script in a Python environment.

Choose from the menu:

1. Add Questions — for teachers to input questions.

2. Take Quiz — for students to attempt a quiz.

3. Check Class Result — to view student scores.

Any other input will exit the app.

⚠️ Notes
The script does not persist data; all data will be lost when the program exits.

Inputs are taken directly from the console.

Only basic validation is implemented — ensure to enter valid options (a, b, c, d).

✅ To Do
Add persistent storage (e.g., file or database).

Improve input validation and error handling.

Use tabulate to show results in a cleaner format.

Add features like quiz categories, timestamps, or randomized question order.
