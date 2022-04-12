# bseq
An implementation of a dynamic array of Bytes in Nim

The code still needs few performance optimizations before you can use it.

If you get the exception: "Error: ambiguous call" when passing a variable of type `int8`, `uin8`, `byte` or `char` to a function, you can fix it by replacing `procName(x)` by `procName(x.byte)`
