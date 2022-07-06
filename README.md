# Post a comment javascript action

This action adds a comment to an open PR

## Inputs

## `repo-token`

**Required** The repo's GITHUB_TOKEN.

## `warning`

**Required** The warning message to comment. The provided message will be prepended with `** WARNING **: `.

## Example usage
```
uses: actions/pr-warning@v1.0
with:
  repo-token: ${{ secrets.GITHUB_TOKEN }}
  warning: "a warning"
```