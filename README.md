# Regular Expressions Metacharacters

| Metacharacter | Description | Examples |
| --- | --- | --- |
| \ | Escape reserved metacharacters | \\$ or \\. outside [] |
| . | Any character except new line | ton. = tone |
| \d | Digit (0-9) | \d\d\d = 327 |
| \D | NOT a Digit (0-9) | \D = a |
| \w | Word Char (Alphanumeric) | \w\w = hi |
| \W | NOT a Word Char (Symbols) | \W = % |
| \s | Whitespace (tab, space, newline) | \s = ' ' |
| \S | NOT Whitespace | \S = a |
| \b | Word Boundary | \bHo in **Ho** **Ho**Ho, \bHo\b in **Ho** HoHo |
| \B | NOT a Word Boundary | \BHo in  Ho Ho**Ho** |
| ^ | Begining of a String or Line | ^Ho in **Ho** HoHo |
| $ | End of a String or Line | Ho$ in Ho Ho**Ho** |
| [] | Matche Characters in bracket | [a-z] match a character a to z, [0-9] match a digit |
| [^ ] | NOT Match Characters in bracket | [^b]at will NOT match 'bat', [^a-z] match everything except lowercase a to z |
| \| | Alternation (Either Or) | pand(ora\|123) = pandora OR pand123 |
| () | Group | Swi(ft) will search Swift but will ignore Swiftly |
| * | Match 0 or more | [a-z]* |
| + | Match 1 or more | [a-z]+ |
| ? | Match 0 or 1 character | colo?r matches colour and color |
| {2} | Exact number of characters to be matched | [a-z]{2} so this matches only 2 characters between a to z |
| {2,10} | Range of numbers {minimum, maximum} | [a-z]{2,5} so matches characters a to z between 2 to 5 char length |
