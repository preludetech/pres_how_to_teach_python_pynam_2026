# Katas for teaching specific problem solving techniques 

## 2d Array

- assesses for loops and lists
- assesses basic problem solving 
- demonstrates brute forcing


Given the array:

```
arr = [["a","b","c"],["d","e","f"],["g","h","i"]]
```

- Write some code that prints each row on its own line

```
['a', 'b', 'c']
['d', 'e', 'f']
['g', 'h', 'i']
```

- print an individual cell

Eg ask them to print `f` or `g`


- Now make it print this:

abc
def
ghi

- Now each column

adg
beh
cfi 

- Just the middle column

d
e
f


- now upside down

ghi
def
abc
 
- right to left 

gda
heb
ifc 

- diagonal: top left to bottom right 

a
e
f

- bottom right to top left 


- top right to bottom left

- bottom left to top right 


## array borders 

Teaches: 
- problem decomposition 
- problem generalization 


```
arr = [["a","b","c"],["d","e","f"],["g","h","i"]]
```

- write out all the characters in the border. Clockwise, starting from 'a':

abcfihgd 

- anti-clockwise 

adghifcba 

- snake

abcfedghi 


- make them work for different size arrays: 4x4 5x5
- make them work for rectangular arrays: 4x6

- spiral
can be done with recursion or with loops

abcfihgde


## Migratory birds 
https://www.hackerrank.com/challenges/migratory-birds/problem
- problem decomposition
- imagine pen and paper  
- 


# Leaderboard 

We are playing an online game. We have a bunch of people who scored different numbers of points. 


1 97 
2 80
2 80
4 72
5 50
6 40
6 40
6 40
9 35
10 20


Eg: 

existing_scores = {"jane":5, "greg":18, ...}

def get_new_score_position(existing_scores, new_score)

## Biggest pluses 

https://www.hackerrank.com/challenges/two-pluses/problem