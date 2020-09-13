# Tabula-Recta-Generator
Old-school cipher technique to keep your wallet-friendly passwords secure. This idea is based on the Lifehacker.com article [How to Write Down and Encrypt Your Passwords with an Old-School Tabula Recta](https://lifehacker.com/how-to-write-down-and-encrypt-your-passwords-with-an-ol-5715794). 


# Usage:

```python3
python3 tabula_recta_generator.py
Set your private seed (or leave blank for random): 

a | b | c | d | e | f | g | h | i | j | k | l | m | n | o | p | q | r | s | t | u | v | w | x | y | z | 
a | ^ | S | $ | 6 | 1 | R | { | ? | V | K | l | V | q | n | S | f | F | M | q | z | O | U | A | 2 | @ | 
b | U | T | > | T | N | 8 | % | h | 6 | s | O | e | B | * | d | X | t | v | L | Q | u | U | X | Q | W | 
c | + | > | g | u | X | Q | I | S | O | R | t | A | @ | W | { | j | + | l | c | I | % | < | g | % | M | 
d | - | + | c | m | @ | I | % | C | w | * | E | m | ? | F | g | 9 | P | 9 | S | l | V | 3 | W | + | l | 
e | 6 | q | A | 2 | G | i | B | 5 | O | 1 | % | | | w | U | w | $ | M | V | U | T | x | n | i | } | D | 
f | Y | O | # | < | 4 | J | Z | _ | 4 | $ | + | 0 | C | ^ | O | - | O | ; | & | > | H | ) | x | ! | Q | 
g | L | Z | I | } | Q | ! | u | d | W | L | u | * | n | { | z | z | R | K | } | ^ | I | H | t | 9 | y | 
h | C | { | H | 7 | A | K | V | f | ( | _ | z | J | 2 | _ | C | v | | | < | 8 | Y | v | p | 0 | z | Z | 
i | t | R | i | < | _ | 1 | v | j | H | i | 5 | @ | B | ; | 5 | | | ^ | * | j | D | X | 4 | c | X | # | 
j | P | v | e | 2 | M | K | G | _ | $ | B | g | Q | 1 | G | ( | n | 6 | 0 | X | ; | x | T | m | ) | p | 
k | % | T | ^ | d | 6 | I | * | d | ? | F | Z | b | w | H | P | C | < | k | 9 | S | H | $ | Q | ^ | E | 
l | N | b | D | y | x | 7 | 8 | V | _ | t | B | # | c | B | N | X | G | 0 | g | Q | _ | M | N | _ | k | 
m | 2 | + | y | Z | w | N | h | V | t | u | ) | > | d | n | @ | z | Q | J | h | X | R | + | l | ) | O | 
n | e | P | s | u | i | b | 1 | e | y | Z | J | X | e | @ | P | 0 | ^ | y | o | 8 | W | b | g | i | v | 
o | I | P | K | * | y | m | > | w | K | P | r | 4 | G | N | Z | < | $ | v | # | 7 | a | W | ; | R | I | 
p | w | & | W | ? | 3 | T | a | N | Y | E | ( | 5 | u | w | C | } | k | | | M | F | - | f | a | { | h | 
q | N | R | z | 5 | b | ; | X | 5 | Q | B | D | Y | > | a | & | F | { | m | ) | & | B | W | f | r | h | 
r | & | A | - | 3 | 6 | N | n | c | - | Z | 3 | E | T | 8 | E | - | p | ? | _ | h | k | D | c | p | w | 
s | 8 | # | Z | W | Q | & | a | $ | L | V | > | c | e | H | ( | H | u | l | a | | | 0 | ) | E | L | ? | 
t | S | ? | ? | @ | 7 | f | # | r | 6 | $ | ; | E | Z | * | W | % | N | L | k | f | x | | | - | g | * | 
u | a | ? | a | u | t | f | 7 | 3 | s | 1 | U | U | G | J | t | n | R | ) | _ | 0 | R | 9 | ; | L | C | 
v | 3 | y | E | Y | % | i | 1 | Q | 6 | & | k | z | G | k | L | - | ) | b | I | j | G | R | P | e | % | 
w | } | E | V | n | I | y | b | T | T | % | ? | i | 7 | i | n | Z | T | O | d | g | a | V | ? | T | A | 
x | U | F | 0 | ; | l | 5 | P | Y | - | w | @ | L | + | & | 5 | ? | 2 | Z | D | ! | y | d | | | y | O | 
y | } | 6 | F | 3 | D | W | ^ | | | I | 7 | * | 5 | W | f | ( | f | k | N | 6 | | | h | 3 | G | * | W | 
z | b | @ | x | 1 | D | 4 | T | A | } | k | $ | { | f | e | ^ | * | @ | v | 0 | b | & | b | d | 0 | A |
```
If you want to recreate your password table just use a seed ;-)


# Example

- Choose a password length, e.g. 12 characters
- Go to your website, e.g. www.gmail.com
- Find the intersection of column 'i' and row 'l', representing the end of gma*_il_*. 
- Starting at 'V', skip every second character and your password will be: *Vt#BX0QM_NDx*.
- Use any schema (diagonally, vertical, skip-two-chars-go-to-nextline, ...)
