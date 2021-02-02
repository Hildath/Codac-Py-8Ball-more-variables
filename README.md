# Codac-Py-8Ball-more-variables
Added variables to the exercise so as to have every option in one go (or almost !)

https://gist.github.com/690d04ad099948cdd0d5ceb6e4eee3ed

import random

name = ""
question = "Will I win the lottery?"
question2 = ""
answer =  ""
random_number = random.randint(1, 12)
random_number2 = random.randint(13, 14)
# random_number correctly imported from random.randint
print(random_number)

if random_number == 1:
  answer = "Yes - definitely."
elif random_number == 2:
  answer = "It is decidedly so."
elif random_number == 3:
  answer = "Without a doubt."
elif random_number == 4:
  answer = "Reply hazy, try again."
elif random_number == 5:
  answer = "Ask again later."
elif random_number == 6:
  answer = "Better not tell you now."
elif random_number == 7:
  answer = "My sources say no."
elif random_number == 8:
  answer = "Outlook not so good."
elif random_number == 9:
  answer = "Very doubtful."
elif random_number == 10:
  answer = "Why not?"
elif random_number == 11:
  answer = "The Force is with you."
elif random_number == 12:
  answer = "The stars are looking after you."
else:
  answer = "Error"
if random_number2 == 13:
  name = "Unicorn"
  print(name + " asks: " + question + " Magic 8 Ball's answer: " + answer) 
if random_number2 == 14:
  name == ""
  print("Question: " + question2)
  print("The Magic 8-Ball cannot provide a fortune unless you ask it something.")
