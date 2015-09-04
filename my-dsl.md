# Language
[http://www.gnu.org/software/sed/manual/sed.html](sed)


# Domain
Line-by-line text manipulation


# Computational model
A sed program is given an input stream of text. It reads it line by line, and
for each line, it sees if any of the rules specified in the program match it
and performs the specified action for that rule.


# DSL-ness
Sed is very close to being "purely" domain-specific. It can only process streams
of text in order, so it cannot do any loops. Even if it were Turing-complete,
its syntax is so well-tuned for text processing that nobody uses it for anything
else.


# Internal or external?
Sed is usually an internal DSL, as it is usually invoked from shell scripts in a
pipeline. Occasionally, however, it is used as an external DSL to make some
quick modifications to a file.


# Host language
Usually the sed language is in a shell script but sometimes it is standalone.
The language is almost always executed by the sed program.


# Benefits
It makes it very easy to make simple edits to a text document. One useful
example is for changing the copyright date on every page on a website when
the new year happens.


# Drawbacks
All it can do is mapipulate text, so other languages are requred to do anything
else.
