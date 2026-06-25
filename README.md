# SLOP for Zed

Zed language support for SLOP.

This extension uses the Tree-sitter grammar from the main SLOP repository:

```toml
[grammars.slop]
repository = "file:///Users/jcadam/code/slop"
commit = "6ec3931e4e54410ba722614de61c3b71c08a0f77"
path = "tree-sitter-slop"
```

## Local install

In Zed, run `zed: install dev extension` from the command palette and select this directory.

## Updating the grammar

After changing the grammar in the main SLOP repository, update the `commit` value in `extension.toml` to the new SLOP commit.
