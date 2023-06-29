# multi-start

[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/ioxiocom/multi-start/publish.yaml)](https://github.com/ioxiocom/multi-start/actions/workflows/publish.yaml)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![PyPI](https://img.shields.io/pypi/v/multi-start)](https://pypi.org/project/multi-start/)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/multi-start)](https://pypi.org/project/multi-start/)
[![License: BSD 3-Clause](https://img.shields.io/pypi/l/multi-start)](https://opensource.org/license/bsd-3-clause/)

This tool aims to help running multiple services inside a single docker container.

Sometimes you might want to have backend, frontend and nginx (or a combination of those)
inside a single container. This tool may help with:

- Prepare final Nginx configs using
  [parse-template](https://github.com/cocreators-ee/parse-template)
- Wait until backend and frontend start responding before running Nginx
- Stop every process if one of them exits so the whole container stops gracefully

## Installation

```shell
pip install multi-start
```

## Usage

```shell
multi-start --help
```
