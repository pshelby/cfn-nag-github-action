# cfn_nag GitHub Action

This action executes cfn_nag_scan linter against the repo for which the workflow is run.

## Inputs

### `input_path`

The directory of the repo to search for violations. Default: `$GITHUB_WORKSPACE`

### `extra_args`

Additional arguments to pass to `cfn_nag_scan`. Default: `--print-suppression`

## Example usage

```
uses: stelligent/cfn-nag-github-action@v1
with:
  input_path: templates
  extra_args: --fail-on-warnings
```
