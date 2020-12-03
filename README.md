# Usage

Clone this repo into `~/.pandoc/templates`.

```
cd ~/.pandoc
git clone https://github.com/ebsd/templates.git
```

# Custom pandoc template

Convert .md to .pdf :

```
pandoc note-template-pandoc-markdown.md -o note-template-pandoc-markdown.pdf --from markdown --template pandoc_custom_note --highlight-style breezedark
```

## yaml header for markdown file

Please read template file `pandoc_custom_note.latex`.

Or check `note-template-pandoc-markdown.md`.

# Eisvogel template

Is coming from https://github.com/Wandmalfarbe/pandoc-latex-template.

Convert .md to .pdf :

```
pandoc doc-template-pandoc-markdown.md -o doc-template-pandoc-markdown.pdf --from markdown --template eisvogel --toc --number-sections --highlight-style breezedark
```

## yaml header for markdown file

Check `doc-template-pandoc-markdown.md`.

