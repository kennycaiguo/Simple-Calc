## A simple calc
This is a simple calc in Flex and Yacc

## How to run
Windows:
```
win_flex lex.l
win_bison calc.y
gcc calc.tab.c
./a.exe
```
Mac/Linux:
```
flex lex.l
bison calc.y
gcc calc.tab.c
./a.out
```

## example
```
1+1
2
3-1
2
2+3+4+0
9
5+
lexical error.
```

If you find some error,Plaese open a issue!