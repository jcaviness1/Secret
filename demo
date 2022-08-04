player_1 = input("Name of Player 1: ")
player_2 = input("Name of Player 2: ")
secret_word = input("Enter word: ")
guess = ""
guess_count = 0
guess_limit = 3
out_of_guesses = False

guess = input("Enter guess: ")
while guess != secret_word and not (out_of_guesses):
    if guess_count < guess_limit:
        guess = input("Wrong, try again: ")
        guess_count += 1
    else:
        out_of_guesses = True

if out_of_guesses:
     print("Out of Guesses, YOU LOSE! " + player_2 + " :( " + player_1 + " wins! Better luck next time! ")
else:
     print(" You win " + player_2 + "! :) " + player_1 + " loses! ")

def game():
    player_1 = input("Name of Player 1: ")
    player_2 = input("Name of Player 2: ")
    secret_word = input("Enter word: ")
    guess = ""
    guess_count = 0
    guess_limit = 3
    out_of_guesses = False

    guess = input("Enter guess: ")
    while guess != secret_word and not (out_of_guesses):
        if guess_count < guess_limit:
            guess = input("Wrong, try again: ")
            guess_count += 1
        else:
            out_of_guesses = True

    if out_of_guesses:
         print("Out of Guesses, YOU LOSE! " + player_2 + " :( " + player_1 + " wins! Better luck next time! ")
    else:
        print(" You win " + player_2 + "! :) " + player_1 + " loses! ")

while True:
        # main program
     while True:
        answer = str(input('Play again? (yes/no): '))
        if answer in ('yes', 'no'):
         break
         print("invalid input.")
     if answer == 'yes':
         print("Okay, let's play!")
         game()
     else:
        print("Game over")
        break


