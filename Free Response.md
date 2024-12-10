# 2024 AP Computer Science Principles Free-Response Questions: Set 1

## AP® Computer Science Principles Written Response Prompts

### Instructions:

- **Time:** 1 hour
- **Questions:** 2
- Read each question carefully and completely.
- Write your response in the space provided for each question in the Written Response booklet.
- You may plan your answers in this orange booklet, but no credit will be given for anything written in this booklet. You will only earn credit for what you write in the separate Written Response booklet.

---

### Pre-FRQ Practice

## Identify the Algorithm present in the JavaScript Files.

### Aspects of Algorithm

Sequencing
Selection
Iteration

### Question 1

Programs accept input to achieve their intended functionality. **Describe at least one valid input to your program and what your program does with that input.**

- Write your responses to this question only on the designated pages in the separate Written Response booklet.
- If there are multiple parts to this question, write the part letter with your response.

evan: takes a user input of a to do/reminder and creates a card that displays the reminder with a remove button. you can remove the card by clicking the button.

gabe: takes questions from api, puts it on the screen, answers true or false, checks if its correct, and calculate score.

### Question 2

Refer to your Personalized Project Reference when answering this question.

#### Part (a):

Consider the first iteration statement included in the Procedure section of your Personalized Project Reference. **Describe what is being accomplished by the code in the body of the iteration statement.**
evan:

```Javascript
for (let i = 0; i < ToDoItems.length; i++) {
      if (ToDoItems[i] === specificCardText) {
        ToDoItems.splice(i, 1);
        break;}}
```

it loops through the length of the to-do (thats how many times it runs)and when it reaches the a statement of the to-do thing it cut it out of the array and it stops. it removes the card.

gabe:

```Javascript
for (let i = 0; i < array.length; i++){
         if (array[i].includes("Correct")) {a++}
         if (array[i].includes("Incorrect")) {b++}}
         clear()
         const correct = a * 100/DOMSelectors.input.value
         const incorrect = b * 100/DOMSelectors.input.value
         DOMSelectors.question.insertAdjacentHTML("beforeend", `<h1>You got ${correct}% of them right and ${incorrect}% of them wrong!</h1>`)
```

it loops through all the array of the questions in i, and calculates the amount marked right and wrong from a function to calculate a percentage for them and then inserts a line to tell you these percentages.

#### Part (b):

Consider the procedure identified in part (i) of the Procedure section of your Personalized Project Reference.

- Write two calls to your procedure that each cause a different code segment in the procedure to execute.
- Describe the expected behavior of each call. If it is not possible for two calls to your procedure to cause different code segments to execute, explain why this is the case for your procedure.

evan: no matter what i put in its going to find the if theres a match and either add it or remove it.

#### Part (c):

Suppose another programmer provides you with a procedure called `checkValidity(value)` that:

- Returns `true` if a value passed as an argument is considered valid by the other programmer.
- Returns `false` otherwise.

Using the list identified in the List section of your Personalized Project Reference, **explain in detailed steps an algorithm that uses `checkValidity` to check whether all elements in your list are considered valid by the other programmer.** Your explanation must be detailed enough for someone else to write the program code for the algorithm that uses `checkValidity`.

- Write your responses to this question only on the designated pages in the separate Written Response booklet.
- If there are multiple parts to this question, write the part letter with your response.

---

### End of Exam

```

```
