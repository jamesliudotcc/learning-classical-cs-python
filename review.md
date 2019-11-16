Complaints:

Doesn't seem to use a lot of Python idioms.
E.g. descriptions of classes are comments above them instead of docstrings. In fact, no docstrings at all. Was pylint run on the code at all?
Lots of lines run waaaay over 80 lines.
It says uses Python 3.7 but no fstrings. Instead, janky old style format
Lots of repetitive type definitions. Things Mypy would infer
Variable names are often acronyms
I feel like more data classes could have been used to reduce boilerplate
for loops over ranges instead of comprehensions over collections
unnecessary else after if/raise. Pylint much?
