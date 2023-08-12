import random

rock = '''
    _______
---'   ____)
      (_____)
      (_____)
      (____)
---.__(___)
'''

paper = '''
    _______
---'   ____)____
          ______)
          _______)
         _______)
---.__________)
'''

scissors = '''
    _______
---'   ____)____
          ______)
       __________)
      (____)
---.__(___)
'''

player = input("What do you choose? Type 0 for Rock, 1 for paper, or 2 for scissors?\n")
hands = ["0", "1", "2"]
computer1 = random.choice(hands)

if player == computer1:
    print("It's a draw!")
elif (player == "0" and computer1 == "2") or (player == "1" and computer1 == "0") or (player == "2" and computer1 == "1"):
    print("You win!")
else:
    print("You lose!")

print("Your choice:")
if player == "0":
    print(rock)
elif player == "1":
    print(paper)
elif player == "2":
    print(scissors)

print("Computer's choice:")
if computer1 == "0":
    print(rock)
elif computer1 == "1":
    print(paper)
elif computer1 == "2":
    print(scissors)
