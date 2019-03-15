# Academic research flow

Tools and template for writing academic papers.

## Tools

1. Pandoc + Markdown for writing (free)
2. Grammarly for spelling, grammar and vocabulary corrections (free + paid options)
3. [Zotero](https://www.zotero.org) to collect, organize and cite (free)

### Pandoc

Pandoc is universal document converter.
More info and installation instructions: https://pandoc.org

Some useful filters:

- `pandoc-fignos`, filter for numbering figures and figure references. To install: `pip install pandoc-fignos`
- `pandoc-eqnos`, filter for numbering equations and equation references. To install: `pip install pandoc-eqnos`
- `pandoc-citeproc`

Reference BibTex file: `zotero.lib`

To generate PDF:

```bash
pandoc template.md -o template.pdf --filter=pandoc-fignos --filter=pandoc-eqnos --filter=pandoc-citeproc --number-sections
```
