# push_swap

School algorithmic project **push_swap** : The goal is to sort data using only two stacks and a limited set of instructions.

# COMMANDS 
pa : push a - take the first element at the top of b and push it to the top of a. Do nothing if b is empty.
pb : push b - take the first element at the top of a and push it to the top of b. Do nothing if a is empty.
sa : swap a - swap the first 2 elements at the top of stack a. Do nothing if there is only one element or none).
sb : swap b - swap the first 2 elements at the top of stack b. Do nothing if there is only one element or none).
ss : sa and sb at the same time.
ra : rotate a - shifts up all elements of stack a by 1. The first element becomes the last.
rb : rotate b - move up all elements of stack b by 1. The first element becomes the last.
rr : ra and rb at the same time.
rra : reverse rotate a - shifts down all elements of stack a by 1. The last element becomes the first.
rrb : reverse rotate b - shift down all elements of stack b by 1. The last element becomes the first.
rrr : rra and rrb at the same time.

# COMPILATION
----------
for push swap
```
make
```
for checker
```
make bonus
```
