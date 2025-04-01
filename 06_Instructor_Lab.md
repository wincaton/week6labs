# Instructor-led Lab

In this assignment you will practice utilizing arrays and/or lists in a program. 

## Magic Crystal Ball

You have decided your future does not lie in data science. Instead, you would like to ply your trade in fortune telling. As someone who has a solid understanding of technology, you decide to eschew a physical store and practice solely online. As such, you are keen on developing a program that will behave like a magic crystal ball.

Based on your vast research into "magic crystal ball" fortune telling, you decide on the following responses:

* It is certain
* It is decidedly so
* That question requires greater monetary compensation
* Reply is hazy; try again, with more money
* Concentrate and ask again
* My reply is no
* Outlook is not so good
* Very doubtful

In addition to these 8 responses, you will also provide 3 more of your own. Make sure your personality shows through *by not making them generic*. Save all of these responses in an array.

Your program should do the following:

1. Prompt the user to "Ask a question," "Review questions and responses," and "Complete services and pay."
   * If they already asked their first question, change the menu from "Ask a question" to "Ask another question." Keep track of this with a boolean.
2. Always provide the menu until the user decides to complete their use of the magic crystal ball.
3. Store the user's questions and received responses in an array/list. When the user selects the option "Review questions/responses" display all the questions asked and their respective answers to the screen.
4. **Randomly** select a response from your catalog of responses as a reply to the user's question (see below for guidance).
5. Keep track of how much the user owes you. You charge $30.00 per question asked. Thus, when the user quits, you will display the total owed and the count of the questions asked.

When you run your program, please input **at least 4 questions**. Save your notebook with the output of your program showing that you have run the program and inputted at least 4 questions.

Here is an example of program output with 2 questions:

```
Welcome to the all-seeing computer!
Ask what you seek to know...
1. Ask a question
2. Review questions and responses
3. Complete services and pay

1

Ask what you seek to know...
Will I become a Python expert?
It is decidely so.

1. Ask another question
2. Review questions and responses
3. Complete services and pay

1

Ask what you seek to know...
Should I have Wally & Buck for dinner?
Reply is hazy; try again, with more money.

1. Ask another question
2. Review questions and responses
3. Complete services and pay

2

Question: "Will I become a Python expert?"
Response: "It is decidely so."

Question: "Should I have Wally & Buck for dinner?"
Response: "Reply is hazy; try again, with more money."

1. Ask another question
2. Review questions and responses
3. Complete services and pay

3

Thank you for visiting the all-seeing computer.

You asked 2 questions. You owe $60.00 for today's service. 

```

### Randomness in Programming 

For this assignment, you will need to use a random number generator. Specifically, you will need to generate a random number within the range of your list's elements. A range is used in order to constrain the generated number to fit within the bounds of the number of elements within your list. To do so, you can rely on the library `random`. Here is an example with a list containing cities in Montana.

```Python
import random as rand

some_list = ['Missoula','Hamilton','Stevensville','Lolo']

rand_a = rand.randrange(0, len(some_list))

some_list[rand_a]
```

As an alternative, you can generate a random selection from a list using the function `choice()`. This is the preferred method for lists, arrays, and dictionaries.

```Python
rand_b = rand.choice(some_list)
```
