Introduction
============

Mypy is a static type checker for Python. If you sprinkle your code
with type annotations using the Python 3 function annotation syntax
(using the PEP 484 notation), mypy can type check you code and find
common bugs. Mypy is a static analyzer, or a lint-like tool: type
annotations are just hints and are not enforced when running your
program. You run your program with a standard Python interpreter, and
the annotations are treated basically as comments.
Mypy 是一个 python 语言的静态类型检查器。如果你在你的代码中使用了 python3
的函数标注语法(使用 PEP484 的记号)，那么 mypy 可以对你的代码进行类型检查，
发现一些一般的错误。

Mypy has a powerful but easy-to-use type system with modern features
such as type inference, generics, function types, tuple types and
union types. You can also always escape to dynamic typing -- mypy's
take on static typing doesn't really restrict what you can do in your
programs, but it will make your programs easier to debug, maintain and
understand.

This document is a short introduction to mypy. It will get you started
writing statically typed code. Knowledge of Python 3.x and some kind
of a statically typed object-oriented language such as Java are
assumed.

.. note::
   Mypy is still experimental. There will be changes
   that break backward compatibility.
