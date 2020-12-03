# My custom pandoc template

For markdown writing : `pandoc_custom_note.latex`.

## Use

Clone this repo into `~/.pandoc/templates`.

```
cd ~/.pandoc
git clone https://github.com/ebsd/templates.git
```

Convert .md to .pdf :

```
pandoc test.md -o test.pdf --from markdown --template pandoc_custom_note --highlight-style breezedark
```

## yaml header

Please read template file `pandoc_custom_note.latex`.

# Eisvogel template

Is coming from https://github.com/Wandmalfarbe/pandoc-latex-template.
