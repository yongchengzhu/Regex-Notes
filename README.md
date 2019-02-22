# Regex Notes

A list of useful regular expressions for personal reference.



| Expression | Usage                                                |
| ---------- | ---------------------------------------------------- |
| .          | match anything except spaces.                        |
| \d         | match a single digit. (0-9)                          |
| \w         | match a single word character. (a-z, A-Z, 0-9, _)    |
| \s         | match a whitespace. (space, tab, newline)            |
| ^          | match the beginning of a string.                     |
| &          | match the end of a string.                           |
| []         | match any single characters inside the bracket.      |
| [^]        | match anything but characters after the caret.       |
| ?          | match 0 or 1.                                        |
| *          | match 0 or more.                                     |
| +          | match 1 or more.                                     |
| {3}        | match exact number. (in this case 3)                 |
| {3, 5}     | match exact range inclusively. (in this case 3 to 5) |
| (a\|b)     | match either *a* or *b*.                             |