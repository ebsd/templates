# My custom pandoc templates

For markdown writing.

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

## yaml

Please read template file.
