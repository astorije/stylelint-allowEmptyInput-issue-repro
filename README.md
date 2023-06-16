This is a reproduction repo for the following GitHub issue reported to the Stylelint repository: https://github.com/stylelint/stylelint/issues/6926

Steps to reproduce:

- First, make sure Node.js and Yarn are installed.
  - At the time of creation, Node.js v20.0.0 and v1.22.19 were used.
- Clone this repository
- Install dependencies with `yarn install`
- Run:
  - `yarn pass` works as expected
  - `yarn fail` should also work but instead the `allowEmptyInput` configuration is ignored.
