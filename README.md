# BringFido Python Style Guide

This is a fork of the excellent https://github.com/wemake-services/wemake-python-styleguide. We make use of 99% of it, and have forked it to tweak the few rules that we disagree with enough, or that cause us enough unjustified overhead, to break with the main branch.

## Guidelines for keeping it simple

- Keep commit count and file changes to a minimum.
- Fix bugs and make contributions on the parent repository when possible.
- Continually pull in the latest from the parent repository.

Most configuration is done in the setup.cfg files of our primary repositories. Changes to this repository are limited to:

- Changes to rules which are partially valuable, but overly restrictive
- New rules