# Ken Thompsons Quine in C

The original quine defined by Ken Thompson in his paper [Reflections on
Trusting Trust](rott.pdf). I've re-arranged `s` to be more human
readable, but will add an unchanged version.

## Example Usage

`./init simple`

`./init foobar`

`./init endless void`

## TODO

This is actually *not* the correct original implemetation as the paper
states `(213 lines deleted)`, which including the 11 visible characters,
means `s` is only 224 lines. The current implementation of `s` has 227
lines.

* [ ] Find 3 unnecessary lines in `s`
* [ ] Add more examples to `init` script
