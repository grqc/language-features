# Necessary Features

The basic features the markup language should support:

## Latex

- `\section{}`
- `\subsection{}`
- `\theorem{}`, etc...
- images and descriptions
- formulas, `$ math $` and `$$ math $$`
- verbatim (code)
- references to structures
- bibliography

## HTML

- table of contents
- text blocks (XML style)
    - `<theorem> </theorem>`
- identifiers for blocks
    - `<definition name> </definition>`
- attributes for blocks
    - `<lemma name, hidden=true> <lemma>`

# Possibilities

## Markdown

Pros:
- Easy to learn
- Easy to read
- Used everywhere

Cons:
- Difficult to extend?

## RST

Pros:
- Easy enough to write
- More extensible

Cons:
- Lack of support?

## XML

Pros:
- Super powerful

Cons:
- Terrible to read or write

# Other possibilites

[Wikipedia](https://en.wikipedia.org/wiki/List_of_lightweight_markup_languages) says that there are a few markup languages that support `class` and `id` which should be sufficient for the functionalities we wish:

- *Markdown Extra* : seems supported by Pandoc Markdown
- *MediaWiki* : ugly
- *Org-mode* : Emacs stuff
- *reStructuredText* : auto ids?
- *Texy!* : ????
