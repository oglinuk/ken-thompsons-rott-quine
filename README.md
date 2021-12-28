# Ken Thompsons Quine in C

The original quine defined by Ken Thompson in his paper [Reflections on
Trusting Trust](rott.pdf). I've re-arranged `s` to be more human
readable, but will add an unchanged version.

## Example Usage

`gcc main.c -o main && ./main > foo.c | gcc foo.c -o foo && ./foo > bar.c | gcc bar.c -o bar`
