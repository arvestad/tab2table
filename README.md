The pupose of this tool is to make it easy to produce tables in Markdown Extra format.

Tabular input is read from stdin or a from one or more files on the
commandline. The header is taken from the first line of the file, by default, but can also be given as a commandlien argument.

Future plan: add HTML output.

An examle:

$ ./tab2table 3col.tab
A|B|C
-|-|-
10|20|30
100|200|300
1000|2000|3000
