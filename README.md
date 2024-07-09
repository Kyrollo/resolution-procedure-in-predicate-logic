# Logical Formula Manipulation Toolkit

This repository contains Python functions for manipulating logical formulas, facilitating operations such as eliminating implications, moving negations inward, converting to CNF (conjunctive normal form), and more.

## Description

The project provides a set of Python functions designed to manipulate logical formulas through various transformations. Each function performs specific operations aimed at simplifying or standardizing logical expressions, making them easier to analyze or process further.

## Functions Included

- **eliminate_implication(formula)**: Eliminates implications from the formula.
- **move_negation_inward(formula)**: Moves negations inward according to logical rules.
- **remove_double_not(formula)**: Removes double negations.
- **standardize_variable(expression)**: Standardizes variables to ensure uniqueness.
- **prenex_form(formula)**: Converts the formula into prenex (quantifier) form.
- **skolemization(formula)**: Skolemizes existential quantifiers.
- **drop_universal(formula)**: Drops universal quantifiers.
- **convert_to_cnf(formula)**: Converts the formula into conjunctive normal form (CNF).
- **turn_conjunction(cnf_formula)**: Renames variables in CNF formulas to ensure uniqueness.

Each function is designed to operate on a string representing a logical formula and returns the transformed string.

## Usage

To use these functions, clone this repository to your local machine:

```sh
git clone https://github.com/<your-username>/<repository-name>.git
