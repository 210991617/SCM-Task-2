# 23-MARCH-2023
import random
player_1=input('Player
name: ')
player_2=input('Player 2 name: ')
for i in range (4):
heap=[]
for i in range (1,5):
| heap.append(random.randint (1,6))
print (heap)
while True:
print(player_1,"'s turn")
player1_coins = int(input("Enter number of coins"))
player1_stack = int(input('Which stack?'))
player1_stack = player1_stack - 1
if player1_stack <= len(heap) and player1_coins > ℗ and player1_coins <=heap[player1_stack]:
heap [player1_stack]=heap[player1_stack]-player1_coins
print (heap)
print("invalid input")
continue
if heap[0] == heap[1] == heap[2] == heap [3] == 0:
print(player_1, "WON")
else:
break
print(player_2,"'s turn")
player2_coins = int(input("Enter number of coins"))
player2_stack = int(input('which stack?'))
player2_stack = player2_stack - 1
if player2_stack<=4 and player2_coins > 0 and player2_coins <= heap[player2_stack]:
heap [player2_stack]=heap[player2_stack] - player2_coins
print (heap)
else:
print("invalid input")
print(heap)
continue
if heap[0] == heap[1] == heap[2] == heap[3] == 0:
print(player_2,"won")
break
