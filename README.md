# BringFido Python Style Guide

This is a fork of the excellent https://github.com/wemake-services/wemake-python-styleguide. We make use of 99% of it, and have forked it to tweak or disable the few rules that we disagree with enough, or that cause us enough unjustified overhead, to break with the main branch.

## Goals:

- Remove complexity considerations
- Remove or replace rules that we disagree with enough to change
- Remove rules that are designed to encourage "manual review", but eventually require a # noqa statement
- Add rules that we feel are missing
- Add compatibility with https://github.com/psf/black
- Simplify application across BringFido projects
- Add additional flake8 plugins

## Guidelines for keeping it simple:

- Only tweak items which are unnecessarily restrictive. Keep items with false positives; They are likely to be fixed upstream at some point.
- Keep commit count and file changes to a minimum.
- Fix bugs and make contributions on the parent repository when possible.
- Continually pull in the latest from the parent repository.
