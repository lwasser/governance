# <img src="images/logo/logo.png" width=40 /> pyOpenSci Governance

![GitHub release (latest by date)](https://img.shields.io/github/v/release/pyopensci/governance?color=purple&display_name=tag&style=plastic)

[![DOI](https://zenodo.org/badge/161679308.svg)](https://zenodo.org/badge/latestdoi/161679308)

[![CircleCI](https://circleci.com/gh/pyOpenSci/contributing-guide.svg?style=svg)](https://circleci.com/gh/pyOpenSci/contributing-guide)

## What is pyOpenSci?

The pyOpenSci project draws inspiration from [rOpenSci](https://ropensci.org/), a
community to help promote, teach, and grow best-practices in software development for the
Scientific R stack.

:construction: Construction note :construction:

## Contributing statement


## How to setup

This repository contains the source files for the [pyOpenSci governance](https://pyopensci.org/governance).

## Build the governance document locally

Our governance documentation is built with [Sphinx](https://sphinx-doc.org) which is a documentation tool.

The easiest way to build our documentationis to use [the `nox` automation tool](https://nox.thea.codes/), a tool for quickly building environments and running commands within them.
Using `nox` ensures that your environment has all the dependencies needed to build the documentation.

To build, follow these steps:

1. Install `nox`

   ```console
   $ pip install nox
   ```
2. Build the documentation:

   ```console
   $ nox -s docs
   ```

This should create a local environment in a `.nox` folder, build the documentation (as specified in the `noxfile.py` configuration), and the output will be in `_build/html`.

To build live documentation that updates when you update local files, run the following command:

```console
$ nox -s docs-live
```


## Contributing to this guide

We welcome and issues and pull-requests to improve the content of this guide.
If you'd like to see an improvement, please [open an issue](https://github.com/pyOpenSci/governance/issues/new/choose).
