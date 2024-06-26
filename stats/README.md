This directory contains output from Python built using `--enable-pystats` and run over the pyperformance test suite.

Results are automatically added every Sunday at midnight UTC.

To manually generate a set of results you have write permissions to this repository, you can do one of the following:

- Visit [the pystats workflow](https://github.com/faster-cpython/ideas/actions/workflows/pystats.yml) and press the "Run workflow" button. You can manually select a different fork and branch of CPython to test.
- In a checkout of this repo, use the `gh` tool:

```bash
gh workflow run pystats.yml
```

To manually select a different fork and branch:

```bash
gh workflow run pystats.yml -f fork=mdboom -f branch=my-changes
```
