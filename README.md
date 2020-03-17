# cfn_nag GitHub Action

This action executes cfn_nag linter against the repo for which the workflow is run.

## Inputs

### `directory-to-scan`

The directory of the repo to search for violations. Default `.`

## Outputs

### `violations`

Number of violations found.

## Example usage

uses: stelligent/cfn-nag-github-action@v1
with:
  directory-to-scan: './templates'
