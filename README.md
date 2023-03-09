# BringFido Python Style Guide

This is a fork of the excellent https://github.com/wemake-services/wemake-python-styleguide. We make use of 99% of it, and have forked it to adjust the few core rules that are useful, but overly restrictive.

## Guidelines for keeping it simple

- Keep commit count and file changes to a minimum.
- Keep items with false positives; They are likely to be fixed upstream at some point.
- Fix bugs and make contributions on the parent repository when possible.
- Continually pull in the latest from the parent repository.

Most configuration is done in the setup.cfg files of our primary repositories. Changes to this repository are limited to:

- Changes to rules which are partially valuable, but overly restrictive
- Dependency updates
- New rules
