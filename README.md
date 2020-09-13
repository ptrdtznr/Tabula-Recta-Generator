# Tabula-Recta-Generator
Old-school cipher technique to keep your wallet-friendly passwords secure. This idea is based on the Lifehacker.com article [How to Write Down and Encrypt Your Passwords with an Old-School Tabula Recta](https://lifehacker.com/how-to-write-down-and-encrypt-your-passwords-with-an-ol-5715794). 


# Usage:

```
python3 tabula_recta_generator.py
Set your private seed (or leave blank for random): 

    A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S | T | U | V | W | X | Y | Z
A | y | Z | w | $ | J | ; | J | l | y | n | | | % | > | ) | # | ; | ) | i | t | x | k | r | 7 | b | d | 0
B | 6 | 8 | S | c | e | L | a | ? | W | l | C | n | ( | J | e | J | @ | ( | ^ | B | s | ^ | J | $ | ! | $
C | X | k | _ | $ | U | 0 | D | ) | x | l | g | < | Y | # | ) | A | * | * | 9 | z | j | _ | # | C | Y | P
D | O | X | # | g | F | G | c | 2 | j | ; | & | i | g | V | ) | - | d | h | T | ( | L | h | h | K | 2 | 8
E | m | 4 | z | v | V | D | W | W | D | _ | F | R | u | 3 | | | O | c | v | x | ; | d | D | p | Q | V | I
F | 4 | w | h | R | a | k | 2 | 7 | 2 | ) | l | Q | O | | | { | ! | p | i | l | 8 | M | M | R | r | $ | |
G | j | n | Y | T | K | h | h | t | > | i | 5 | L | Y | p | ( | W | b | F | { | B | E | @ | 7 | K | { | o
H | K | W | Q | m | I | _ | p | S | e | 1 | a | q | l | Y | 3 | u | | | @ | > | ! | B | N | h | & | q | U
I | % | L | k | r | t | c | z | * | v | B | @ | g | r | O | { | } | t | d | Y | 6 | > | F | M | - | * | R
J | d | * | v | v | % | Z | Y | q | 3 | E | * | 0 | h | D | E | a | d | w | < | R | ; | s | m | H | 7 | y
K | T | i | & | 2 | U | ( | a | ! | K | > | W | 0 | T | 8 | > | ) | B | O | f | 2 | M | 9 | 3 | 8 | V | m
L | l | % | _ | Q | Y | p | x | - | ; | + | 6 | % | l | i | F | U | e | d | V | H | z | g | X | ! | P | 5
M | C | - | I | D | C | L | l | r | J | | | u | q | 8 | & | X | 9 | r | { | # | 6 | J | K | J | S | D | e
N | C | a | 4 | s | { | j | 1 | Y | V | x | m | z | { | d | Z | H | G | ^ | C | * | l | u | _ | b | L | !
O | < | 9 | | | R | i | x | K | 2 | 6 | 5 | X | C | k | 2 | R | K | * | * | m | 6 | z | 7 | z | z | s | F
P | 9 | m | Z | G | ) | _ | z | H | y | D | j | N | V | H | i | | | V | _ | ^ | e | ; | e | h | q | E | u
Q | 7 | @ | g | i | P | h | b | x | % | + | o | U | R | I | S | $ | P | } | H | v | ! | ? | 6 | O | ( | S
R | n | ) | & | X | G | 8 | } | 4 | T | 2 | w | D | E | z | z | s | L | l | v | N | > | T | 0 | | | R | b
S | s | # | % | Z | m | f | P | n | R | T | # | V | f | ? | f | a | c | h | $ | x | n | ! | I | T | F | #
T | g | w | q | b | + | v | L | D | D | a | H | 8 | g | t | V | K | J | F | Z | 1 | p | | | ? | { | 1 | H
U | 1 | 8 | l | ) | I | ^ | # | P | ) | ) | w | i | 0 | r | 6 | & | V | Q | w | W | X | r | y | _ | F | 5
V | g | h | % | > | X | T | o | d | V | K | D | W | p | 7 | ! | C | ; | H | % | 5 | J | t | < | | | n | 8
W | % | U | r | 2 | e | v | ? | l | H | v | T | 3 | $ | v | < | 0 | A | 9 | N | @ | * | ! | k | b | N | u
X | ; | + | 0 | R | - | V | 1 | Y | ; | p | x | j | A | % | a | P | Y | 0 | K | } | j | # | & | $ | Q | S
Y | K | X | | | d | W | * | p | 6 | ! | n | E | v | V | $ | x | 9 | o | z | 5 | c | | | J | y | - | L | z
Z | + | } | 6 | @ | 3 | f | G | K | + | | | 7 | W | 5 | W | < | 6 | 5 | I | + | 4 | ; | C | < | X | K | $
```
If you want to recreate your password table just use a seed ;-)

# Example

- Choose a password length, e.g. 12 characters
- Go to your website, e.g. www.gmail.com
- Find the intersection of column 'i' and row 'l', representing the end of gma*_il_*. 
- Starting at 'V', skip every second character and your password will be: "*;6lFeVzXPl_Y*." (its ugly)
- Use any schema (diagonally, vertical, skip-two-chars-go-to-nextline, ...)
