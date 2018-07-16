# **craft ai** decision tree interpreter test suite #

This is the official test suite for the different **craft ai** decision tree interpreters.

## decide _a.k.a. decision trees inductions_ ##

- `./decide/trees` contains decision trees both invalid and valid, as computed by [craft ai](http://craft.ai).
- `./decide/expectations` contains a files describing expectations on each decision tree. (`./decide/expectations/blind.json` contains expectations on `./decide/trees/blind.json`).

## decision rules reducer ##

`./reduce_decision_rules` contains decision rules (as they appear in decision trees) and their expected reduction.

## decision rules formatter ##

`./format_decision_rules` contains decision rules (as they appear in decision trees) and their expected format.
