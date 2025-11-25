# Reset, Restore & Checkout

## Reset (Dangerous)
Moves HEAD & can erase commits.

### Undo last commit — keep changes staged:
```bash
git reset --soft HEAD^
```

### Undo last commit — remove from staging:
```bash
git reset HEAD^
```

### Undo everything (dangerous):
```bash
git reset --hard HEAD^
```

## Restore (Safe)
```bash
git restore filename
git restore --staged filename
```

## Checkout (Safe for viewing)
```bash
git checkout commit_id
git checkout master
```

Detached HEAD allows safe experiments.
