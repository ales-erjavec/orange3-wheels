# Building wheels for biolab/orange3

[![Build](https://github.com/ales-erjavec/orange3-wheels/actions/workflows/build-wheel.yml/badge.svg)](https://github.com/ales-erjavec/orange3-wheels/actions/workflows/build-wheel.yml)

The Windows, macOS and manylinux wheels are build on Github Actions.

To make/build a new release, edit the .github/workflows/buils-wheel.yml file and
change the `BUILD_COMMIT` version to the appropriate tag/ref in the orange3
git repository. Commit the changes and push the this repo (or create a pull
request and have someone merge it).

The wheels are stored as build artefacts.
