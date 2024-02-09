# quiz
This is a quiz app from the JavaScript simplified course
https://javascriptsimplified.com/

live link : https://adrians90.github.io/quiz/
The app takes a quiz with three questions and the task is to make it functional and verify if the answers are correct. If all answers are correct, a "Congratulations!" modal pops onto the screen and the text color of each question turns green. If answers are incorrect, the text color is red.

The main tasks are :
@@ -13,4 +14,4 @@ The main tasks are :
- For each correct answer add the class `correct` to the parent with the class `question-item` and remove the class `incorrect`
- For each incorrect answer add the class `incorrect` to the parent with the class `question-item` and remove the class `correct`.
- Make sure unanswered questions show up as incorrect. The easiest way to do this is to add the incorrect class and removing the correct class from all question items before checking the correct answers
- If all answers are correct show the element with the id `alert` and hide it after one second (look into setTimeout) (use the class active to show the alert and remove the class to hide it)
- If all answers are correct show the element with the id `alert` and hide it after one second (look into setTimeout) (use the class active to show the alert and remove the class to hide it)
