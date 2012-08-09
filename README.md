LEMON
=====

What is it?
-----------

From original documentation (http://www.hwaci.com/sw/lemon/lemon.html):

Lemon is an LALR(1) parser generator for C or C++. It does the same job as bison and yacc.
But Lemon is not another bison or yacc clone. It uses a different grammar syntax which is designed to reduce the number of coding errors.
Lemon also uses a more sophisticated parsing engine that is faster than yacc and bison and which is both reentrant and thread-safe.
Furthermore, Lemon implements features that can be used to eliminate resource leaks,
making is suitable for use in long-running programs such as graphical user interfaces or embedded controllers.

What is different compared to original (SQLite) version?
--------------------------------------------------------

* Added option `-H` to specify a header file extension.
* Added option `-P` to specify a file-name prefix.
* Generated parser has same extension as template file.
