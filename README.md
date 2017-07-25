# Prolog syntax highlighting for Notepad++

<p align="center"><img src="http://i.imgur.com/ZMzPga8.png" width="600"/></p>


### Known problems

*(Those problems are due to limitations of Notepad++ syntax highlighting configurability)*

- Dots used outside of rule termination (e.g. `15.0`, `I in 1..5`, `test(a,b) =.. L`, etc.) will be badly highlighted.

- If a dot is used in a rule before the rule terminating dot, it will consider, for folding purposes, that the first dot is the end of the rule.

- Operators used to construct variable pairs (e.g. `A-B`, `'test':Y`) mess up the highlighting for that construct.
