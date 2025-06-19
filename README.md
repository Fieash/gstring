# gstring
`grep` a string.
To install, add this to your `.zshrc`
```bash
gstring() { strings $1 | grep $2 }
```

to reload:
```bash
source ~/.zshrc
```
