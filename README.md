# homebrew-anonymizer

Homebrew tap for **[Anonymizer](https://github.com/arcane-tl/anonymizer)**.

| Install | Result |
|---------|--------|
| `brew install anonymizer` | CLI: **`anonymize`** |
| `brew install --cask anonymizer` | App: **`Anonymizer.app`** in `/Applications` |

## Full Mac setup

```bash
# Required: third-party tap (not in official homebrew/cask)
brew tap arcane-tl/anonymizer
brew install anonymizer
brew install --cask anonymizer

anonymize doctor
```

**Auto-tap one-liner** (if you forget `brew tap`):

```bash
brew install --cask arcane-tl/anonymizer/anonymizer
```

If you see `No Cask with this name exists`, you skipped the tap — use one of the blocks above.

Same product name throughout — not “anonymizer-app”.

## Source

- Formula / cask sources: https://github.com/arcane-tl/anonymizer/tree/main/packaging/homebrew
