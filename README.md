# Rock-paper-scissor-sample-code
# Here,I provide you a sample code on game rock,paper,scissors
# enter basic details of players
player1 = input("Player1,Enter your name: ")
player2 = input("Player2,Enter your name: ")

# players choices

p1 = input("{} choose from rock,paper,scissor(r/p/s)".format(player1)).lower()
p2 = input("{} choose from rock,paper,scissor(r/p/s)".format(player2)).lower()

# comparing choices

if (p1 == 'r' and p2 == 's') or (p1 == 'p' and p2 == 'r') or (p1 == 's' and p2 == 'p'):
    print(player1 + "wins!")
elif (p1 == 'r' and p2 == 'p') or (p1 == 'p' and p2 == 's') or (p1 == 's' and p2 == 'r'):
    print(player2 + "wins!")
elif p1 == p2:
    print("Its a Draw!!!")
