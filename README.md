# cfn_nag GitHub Action

This action executes cfn_nag linter against the repo for which the workflow is run.

## Inputs

### `input-path`

The directory of the repo to search for violations. Default `.`

## Example usage

```
uses: stelligent/cfn-nag-github-action@v1
with:
  input-path: templates
```
