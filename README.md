# vending-machine
using break function

# coding a vending machine
x = int(input('how many candies do you want '))

# 1)without break
for i in range(x):
    print('candies')

print()
# 2)if the vending machine doesn't have enough candies   ********BETTER**********
# using break function
av = 10
for i in range(x):
    if x > av:
        print('sorry the available candies are', av)
        print('out of stock')
        break
    print('candies')


