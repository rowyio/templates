# Connectors contribution guide

To get yourself familiar with how you can create a connectors, read this [documentation](https://docs.rowy.io/field-types/connector).

1) Pick from the list of issues for new connector requested or add your own issue if you are interested in creating one not on the list.
2) Please comment on an issue you would like to work on so that it can be assigned to you. 
3) Once, you have created the derivative function, submit a PR to the `connector` folder with a new folder containing following two files:
- main.ts: [Template](https://github.com/rowyio/templates/blob/main/connector/template/main.ts)
- config.json: [Template](https://github.com/rowyio/templates/blob/main/connector/template/config.ts)
- README.md: [Template](https://github.com/rowyio/templates/blob/main/connector/template/README.md)
4) Make sure your folder is name appropriately representing your derivative function as well as the README.md file details any requirements for using the derivative function.


Here is a [sample valid PR submission](https://github.com/rowyio/templates/pull/2/files) for a derivative function, make sure similar format is maintained.
