# homebrew-anonymizer

Homebrew tap for **[Anonymizer](https://github.com/arcane-tl/anonymizer)**.

| Install | Result |
|---------|--------|
| `brew install anonymizer` | CLI: **`anonymize`** |
| `brew install --cask anonymizer` | App: **`Anonymizer.app`** in `/Applications` |

## Full Mac setup

```bash
brew tap arcane-tl/anonymizer
brew trust arcane-tl/anonymizer    # Homebrew 6+ (once)
brew install anonymizer
brew install --cask anonymizer

anonymize doctor
```

### Trust (Homebrew 6+)

Third-party taps are blocked until trusted:

```bash
brew trust arcane-tl/anonymizer
```

Typo to avoid: `arcane-tl/anonymize` (missing **r**) is wrong and will not trust this tap.

### Common errors

| Error | Fix |
|-------|-----|
| No Cask with this name exists | `brew tap arcane-tl/anonymizer` first |
| Refusing to load … from untrusted tap | `brew trust arcane-tl/anonymizer` |

## Source

- Formula / cask: https://github.com/arcane-tl/anonymizer/tree/main/packaging/homebrew
