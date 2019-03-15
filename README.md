# Academic research flow

Tools and template for writing academic papers.

## Tools

### Writing with Pandoc and Makrdown

Installing filters:

- `pip install pandoc-fignos`
- `pip install pandoc-eqnos`

```bash
pandoc template.md -o template.pdf --filter=pandoc-fignos --filter=pandoc-eqnos --filter=pandoc-citeproc --number-sections
```
