## A simple calc
This is a simple calc in lex(flex) and Yacc(bison).

## Clone

```
git clone git@github.com:StepfenShawn/Simple-Calc.git
```

## Installing dependencies

* gcc/clang
* flex
* bison

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
$ flex lex.l
$ bison calc.y
$ gcc calc.tab.c
$ ./a.out
```

## Examples
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

If you find some errors,plaese open an issue!

## License
[MIT license(2020 Stepfen Shawn)](https://github.com/StepfenShawn/Simple-Calc/blob/master/LICENSE)
