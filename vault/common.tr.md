---
id: common.tr
title: Tr
desc: ''
updated: 1642441815077
created: 1642441815077
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tr

> Translate characters: run replacements based on single characters and character sets.
> More information: <https://www.gnu.org/software/coreutils/tr>.

- Replace all occurrences of a character in a file, and print the result:

`tr {{find_character}} {{replace_character}} < {{filename}}`

- Replace all occurrences of a character from another command's output:

`echo {{text}} | tr {{find_character}} {{replace_character}}`

- Map each character of the first set to the corresponding character of the second set:

`tr '{{abcd}}' '{{jkmn}}' < {{filename}}`

- Delete all occurrences of the specified set of characters from the input:

`tr -d '{{input_characters}}' < {{filename}}`

- Compress a series of identical characters to a single character:

`tr -s '{{input_characters}}' < {{filename}}`

- Translate the contents of a file to upper-case:

`tr "[:lower:]" "[:upper:]" < {{filename}}`

- Strip out non-printable characters from a file:

`tr -cd "[:print:]" < {{filename}}`

