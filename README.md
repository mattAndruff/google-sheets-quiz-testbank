# google-sheets-quiz-testbank
How to make a quiz from a google sheet.
This is all based off me watching this guys video on how to do this: https://www.youtube.com/watch?v=oKliSlFZfV4&ab_channel=RogerBurrows  
If you appreciate this functionality, please go over to his channel and subscribe/give him a thumbs up.

Thank you Roger Burrows.

I modified the sheet to truly randomize the order of the questions, and to allow multiple correct answers, and more than 4 distractors.  Everything else is documented on his youtube video: https://www.youtube.com/watch?v=oKliSlFZfV4&ab_channel=RogerBurrows

I've included my code attached and example google sheet so you can get a feeling for how to create the columns.  Basically I use a '|' to seperate multiple answers per column so you can have a variable number of distractors/correct answers.  This really increases the number of unique questions.  I also added a limit to the number of questions.  As an example I have around ~130 questions, but with variants it's likely ~ 300 questions, but I limit the number of questions to 40.  This gives you a sizeable answer space to have multiple quizes with unique question/answers.


