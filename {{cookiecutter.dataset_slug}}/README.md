# {{ cookiecutter.dataset_slug }}

| Automated Test Suite | Status |
|----------------------|--------|
| Data Validation      | [![Build Status](https://travis-ci.org/{{ cookiecutter.dataset_github_repo }}.svg?branch=master)](https://travis-ci.org/{{ cookiecutter.dataset_github_repo }}) |

{{ cookiecutter.dataset_short_description }}

## Data

Some short description of the data.

## Scripts

Run `make` in project root to see available scripts to run.

```
$ make
Usage: make <command>

where <command> is one of the following:

validate             Validate data
dummy                Perform a dummy action with outputs
```

## License

See [LICENSE.md](LICENSE.md).
