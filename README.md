# quiz
This is a quiz app from the JavaScript simplified course
https://javascriptsimplified.com/

live link : https://adrians90.github.io/quiz/
The app takes a quiz with three questions and the task is to make it functional and verify if the answers are correct. If all answers are correct, a "Congratulations!" modal pops onto the screen and the text color of each question turns green. If answers are incorrect, the text color is red.

The main tasks are :

- Select all elements needed
- Prevent the default behaviour
- Get all selected answers (use the `checked` property on the input to determine if it is selected or not)
- Loop through the selected answer to see if they are correct or not
- For each correct answer add the class `correct` to the parent with the class `question-item` and remove the class `incorrect`
- For each incorrect answer add the class `incorrect` to the parent with the class `question-item` and remove the class `correct`.
- Make sure unanswered questions show up as incorrect. The easiest way to do this is to add the incorrect class and removing the correct class from all question items before checking the correct answers
- If all answers are correct show the element with the id `alert` and hide it after one second (look into setTimeout) (use the class active to show the alert and remove the class to hide it)
