flexydoc
========

Flexible Documentation generator. Possibly using grunt and a customizable language grammar.

# Draft
What we want to achieve with this project is an _agnostic-language_ parser, and _agnostic-linker_.  
All of that glued with a [gruntjs][gruntjs] Task.

### What does agnostic-linker means?
It could be interesting to group your code following your implementation logic,
not as it's usually grouped by your framework/toolkit.

### Dependencies

  * [dmajda/pegjs][pegjs] - [PEG][peg]-based parser for nodejs.
  * a static site generator between:
    * [DocPad](https://github.com/bevry/docpad) 419 :star:
    * [Wintersmith](https://github.com/jnordberg/wintersmith) 112 :star:
    * [Blacksmith](https://github.com/flatiron/blacksmith) 98 :star:

[pegjs]: https://github.com/dmajda/pegjs
[peg]: http://en.wikipedia.org/wiki/Parsing_expression_grammar
[highlight.js]: https://github.com/isagalaev/highlight.js
[grunt]: https://github.com/gruntjs/grunt
