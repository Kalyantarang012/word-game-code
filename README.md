# word-game-code
word game code



import random 
print("guess the word") 
print("you have ten guesses") 
print("the word is in lowercase letters")
print("if you need a hint check the lists in the code for help")

loop = 0

word = " "

topic = random.randint(1,4)
ra = random.randint(1,10)

if topic == 1: 
    print("the topic is fruits!") 
    topic = "fruit"

if topic == 2: 
    print("the topic is super heroes!") 
    topic = "super heroes"

if topic == 3: 
    print("the topic is colors!") 
    topic = "color"
if topic == 4: 
    print("the topic is movies!") 
    topic = "movie"
if topic == "fruit":
  if ra == 1: word = "apple"
  if ra == 2: word = "banana"
  if ra == 3: word = "orange"
  if ra == 4: word = "mango"
  if ra == 5: word = "grapes"
  if ra == 6: word = "pineapple"
  if ra == 7: word = "watermelon"
  if ra == 8: word = "strawberry"
  if ra == 9: word = "kiwi"
  if ra == 10: word = "cherry" 
  guess = input("what do you think the word is? ") 
  if guess == word: 
    print("you win!") 
  else: 
    print("thats wrong try again")
    guess = input("what do you think the word is? ") 
  if guess == word: 
    print("you win!") 
  else: 
    print("thats wrong try again") 
    guess = input("what do you think the word is? ") 
  if guess == word: 
    print("you win!") 
  else: 
    print("thats wrong try again") 
    guess = input("what do you think the word is? ") 
  if guess == word: 
    print("you win!") 
  else: 
    print("thats wrong try again") 
    guess = input("what do you think the word is? ") 
  if guess == word: 
    print("you win!") 
  else: 
    print("thats wrong try again") 
    guess = input("what do you think the word is? ")
  if guess == word: 
    print("you win!") 
  else: 
    print("thats wrong try again") 
    guess = input("what do you think the word is? ")
  if guess == word:
    print("you win!") 
  else: 
      print("thats wrong try again") 
      guess = input("what do you think the word is? ")
  if guess == word: 
      print("you win!") 
  else: 
    print("thats wrong try again") 
    guess = input("what do you think the word is? ") 
    if guess == word:
      print("you win!") 
    else: 
      print("thats wrong try again") 
      guess = input("what do you think the word is? ")

    if guess != word: print("you lose!") 
    print("the word was", word)

super_heroes = ["batman","superman","spiderman","hulk","captain america","iron man","thor","black widow","hawk eye","flash"]

if topic == "super heroes":
  word = super_heroes[ra-1]
  guess = input("what do you think the word is? ")
  while loop < 10: 
    if guess == word: 
      print("you win!") 
      break 
    else: 
      print("thats wrong try again") 
      guess = input("what do you think the word is? ") 
      loop += 1


colors = ["blue","red","black","green","white","yellow","silver","tan","purple","brown"]

if topic == "color": 
  if ra == 1: 
    word = colors[0] 
  if ra == 2: 
    word = colors[1] 
  if ra == 3: 
    word = colors[2] 
  if ra == 4: 
    word = colors[3] 
  if ra == 5: 
    word = colors[4] 
  if ra == 6: 
    word = colors[5] 
  if ra == 7: 
    word = colors[6] 
  if ra == 8: 
    word = colors[7] 
  if ra == 9: 
    word = colors[8] 
  if ra == 10: 
    word = colors[9] 
  guess = input("what do you think the word is? ")
  while loop < 10: 
    if guess == word: 
      print("you win!") 
      break 
    else: 
      print("thats wrong try again") 
      guess = input("what do you think the word is? ") 
      loop += 1





movies = ["batman vs superman","spiderman homecoming","jurassic park","sonic","harry potter","thor","fantastic 4","minecraft","flash"]

if topic == "movie":
  word = super_heroes[ra-1]
  guess = input("what do you think the word is? ")
  while loop < 10: 
    if guess == word: 
      print("you win!") 
      break 
    else: 
      print("thats wrong try again") 
      guess = input("what do you think the word is? ") 
      loop += 1
