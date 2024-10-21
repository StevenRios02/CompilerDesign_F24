I have created a lexical scanner that prints out the tokens from a text file, in this case 
test_input.txt. This text file is as follows:
int x = 42;
real y = 3.14;
if (x>y) then x = x + 1;


The output is as follows: 
steven@DESKTOP-SD3FFPF:/mnt/d/steve/compiler_design_homework$ ./toy_lang < test_input.txt
INT
ID
ASSIGN
INTNUM
SEMI
REAL
ID
ASSIGN
REALNUM
SEMI
IF
LPAREN
ID
GT
ID
RPAREN
THEN
ID
ASSIGN
ID
PLUS
INTNUM
SEMI
