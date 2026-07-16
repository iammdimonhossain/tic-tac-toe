instructions = '''
This will be our tic tac toe board:

  1 | 2 | 3 
 ___|___|___
  4 | 5 | 6 
 ___|___|___
  7 | 8 | 9 

Instructions:
1. Players take turns entering a number (1-9) to place their sign.
2. Player 1 goes first.
3. The first player to get three in a row (horizontally, vertically, or diagonally) wins.
4. If all 9 spots are filled and no one wins, it's a tie.
'''
def print_board():
    b=(f"""
 {board[0]} | {board[1]} | {board[2]} 
___|___|___
 {board[3]} | {board[4]} | {board[5]} 
___|___|___
 {board[6]} | {board[7]} | {board[8]} 
""")
    print(b)
board = []
for i in range(9):
    board.append(' ')

def take_input(player_name, player_sign):
    x = int(input(f"{player_name}: "))
    x-=1
    if x < 0 or x >= 9:
        print("Please enter a number between 1-9.")
    elif x in index_list:
        print("This spot is blocked.")
    else:
        index_list.append(x)
        return x
    return take_input(player_name, player_sign)
index_list = []

def calculate_result(player_one, player_two, sign_one, sign_two):
    if (board[0] == board[1] == board[2] == sign_one or
        board[3] == board[4] == board[5] == sign_one or
        board[6] == board[7] == board[8] == sign_one or
        board[0] == board[3] == board[6] == sign_one or
        board[1] == board[4] == board[7] == sign_one or
        board[2] == board[5] == board[8] == sign_one or
        board[0] == board[4] == board[8] == sign_one or
        board[2] == board[4] == board[6] == sign_one):
        print(f"Congratulations {player_one}! You WON!")
        quit("Thank you both for playing.")
    elif (board[0] == board[1] == board[2] == sign_two or
          board[3] == board[4] == board[5] == sign_two or
          board[6] == board[7] == board[8] == sign_two or
          board[0] == board[3] == board[6] == sign_two or
          board[1] == board[4] == board[7] == sign_two or
          board[2] == board[5] == board[8] == sign_two or
          board[0] == board[4] == board[8] == sign_two or
          board[2] == board[4] == board[6] == sign_two):
        print(f"Congratulations {player_two}! You WON!")
        quit("Thank you both for playing.")

def main():
    print("Welcome to the Tic Tac Toe game!")
    player_one = input("Enter Player 1 name: ")
    player_two = input("Enter Player 2 name: ")
    print(f"Thank you for joining, {player_one} and {player_two}!")
    print(instructions)
    sign_one = input(f"{player_one}, choose your sign (X or O): ")
    sign_one.upper()
    sign_two = 'O' if sign_one == 'X' else 'X'
    print(f"{player_one}'s sign is {sign_one}")
    print(f"{player_two}'s sign is {sign_two}")
    print_board()
    for i in range(9):
        if i % 2 == 0:
            player = player_one
            sign = sign_one
        else:
            player = player_two
            sign = sign_two

        index = take_input(player, sign)
        board[index] = sign
        print_board()
        calculate_result(player_one, player_two, sign_one, sign_two)
    print("It's a TIE! Nobody won. Play again.")

main()