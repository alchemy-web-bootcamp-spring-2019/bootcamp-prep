JS Refactor
===

### Rename 

1. Click anywhere in the current variable or function name that you'd like to improve.
1. Hit `fn` + `F2` keys.
1. Enter new name in box.


### Extract variable

1. Highlight the characters you want to extract into the variable (including quotes for strings).
1. Hit `SHIFT` + `CMD` + `J` keys, let go then `V`.

1. Select how far you plan to extract to (for now, choose the last item in the list).
1. Select `const` or `let` as appropriate (default to `const`)
1. Give it an obvious name without too much thought.
1. Double-check that the extraction worked correctly.

#### Extract method 

1. Highlight the lines you want to extract into the function (including quotes for strings).
1. `SHIFT` + `CMD` + `J` keys, let go then `M`.
1. Select how far you plan to extract to (for now, choose the last item in the list).
1. Give it an obvious name without too much thought.
1. Double-check that the extraction worked correctly.

#### Windows

Command|Meaning
---|---
`CTRL` + `A` | Select All
`SHIFT` + arrow key | extend/retract selection
`CTRL` + arrow key | move by one word
`SHIFT` any above | extend/retract selection

### Bonus VSCode!

No line selection required!

Command|Meaning
---|---
`CMD/CTRL` + `,` | open user settings
`OPTION/ALT` + up/down arrow | move line
`SHIFT` + `OPTION/ALT` + up/down arrow | copy lines
`CMD/CTRL` + `SHIFT` + K | delete line
`CMD/CTRL` + `D` | add next token
`CMD/CTRL` + `K` **then** `D` | skip to next token

