# GAME-Coin-Toss-

import random

print('Heads = 0    &   Tails = 1')

n = random.randrange(0,1)
f='no'

a=int(input('Your Choice is: '))

    
if a != n:
    if a == 0:
        print('You Lose , It Is Tails')
        
    else:
        print('You Lose , It Is Heads')
        
else:
    print('You Win , Thank You')
            
            
