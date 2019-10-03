# Contribution guidelines
*Anders Poirel*

Here are a few guidelines reguarding software engineering best practices to ensure that your contributions to projects can be merged in smoothly.

## Coding Style

In general, you should aim to follow the [PEP-8 guidelines](https://www.python.org/dev/peps/pep-0008/) in your Python code. That is,

- set tabs to be equal to 4 spaces in your editor (that is, 4 spaces per indentation level
- line length should stay under 79 columns
- function and variable names should be lowercase with `_` seperating words
- use line breaks after binary operators

## Project Structure

Try to respect the [Cookie Cutter Data Science](https://drivendata.github.io/cookiecutter-data-science/) project structure. These are meant as guidelines - it can be adapted  but in general:
- data, notebooks and scripts should be in seperate folders
- raw data should be considered immutable (that is, never overwrite the original data)
- notebook names should be informative: they should contains author name, version and purpose

## Git usage
