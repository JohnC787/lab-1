# Algorithm steps for the "Im thinking of a number game"
GuessTheNumberGame
    ask the user for their name
    generate a random number between 1 and 100
    set guess_count to 0
    set max_guesses to 10
    initialize an empty list to store guesses

    while guess_count is less than max_guesses do
        prompt the user to enter a guess
        read the user's guess
        store the guess in the list
        increment guess_count

        if the guess is less than the number then
            display "The number is higher"
        else if the guess is greater than the number then
            display "The number is lower"
        else
            display "Congratulations, you guessed the number"
            end the game
    end while

    if the number was not guessed then
        display "You ran out of guesses"

    display all guessed numbers
