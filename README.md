# GezuMC.github.io
GezuMath Blog

[‣]: # (@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@)
[‣]: # (@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@)
[‣]: # (@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@)
[‣]: # (@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@)
[‣]: #{{{‣ (Markdown Explicit Folding Syntax)
# Markdown Explicit Folding Syntax #

[dfireball-page]: https://daringfireball.net/projects/markdown/syntax#link
[md-comment-quest]: https://stackoverflow.com/questions/4823468/comments-in-markdown
[md-comment-ans1]: https://stackoverflow.com/a/32190021

* A Markdown comment is used as syntax for explicit folding begin and end.
  * Stack Overflow question _Comments in Markdown_: [question][md-comment-quest],  [answer][md-comment-ans].
* The Markdown used for Gezz explicit folding is based on a Markdown workaround comment; the workaround is based on Markdown reference link syntax.
  * [Link syntax: daringfireball.net][dfireball-page].
  * Syntax `[foo-string]:` is syntax for the link name.
  * Syntax `#foo-string` is syntax for an anchor link.
  * Syntax `(foo-string)` is syntax for the link title attribute.
* __Explicit folding syntax explanation__
  * Folding start is of the form `[chars]: #{{{syms (title or text)`.
  * Folding end is of the form `[chars]: #}}} (chars)`.
  * The line preceding `[chars]: #` cannot be normal text. (Several places in the StackOverflow answer, people say a blank line must precede the it.)
  * Using `<` and `>` in the workaround syntax can cause problems.
  * Inner parenthesis can't be used in the outer parentheses.

[<]: #}}} (<)
