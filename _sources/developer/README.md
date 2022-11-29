# Developer instructions

## Rebuild jupyter book

```
rm -rf _build
jupyter-book build .
```

## Copy to gh-pages

```
ghp-import -n -p -f _build/html
```