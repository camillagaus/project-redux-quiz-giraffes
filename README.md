# Redux quiz group project
This is a group project where me and my team have built a quiz game using Redux. It's a multiple choice quiz.

We started the project by planning how we would structure our quiz. We decided to work in smaller group (four in each group) and do mob-programming. We came up with some questions about giraffes and decided that we wanted to show the progress with the format "1/5 questions answered". We also decided what components we needed to build the webpage and how the styling should look like. 

## The questions array
We put our questions in our store `src/reducers/quiz.js`. 

What we included in each object: 
* `id` - a unique identifier for the question. 
* `question` - this is the text which is displayed to the user for this question. 
* `options` - an array of possible answers to the question which the user will choose from. 
* `correctAnswerIndex` - the index of the item in the `options` array which is the correct answer.

## Stretch Goals 🏃‍♂
Strech goals we chose to do:
* After selecting an answer, highlight the correct answer if they chose incorrectly.
* Use images to make your questions and answers look richer

## View it live 📱
https://affectionate-mirzakhani-7ee123.netlify.app/ 


