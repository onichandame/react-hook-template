# react-hook-template

template for creating react hooks

# Author

[onichandame](https://onichandame.com)

# Usage

1. create a repo using this template
2. modify the _name_ field in `packages/react-hook/package.json`
3. modify the _scripts_ field in `packages/example/package.json`. Beware that the _react-hook_ in the `workspace react-hook` clause should be changed to the name set in the former step
4. modify the _react-hook_ in the dependencies of `packages/example/package.json` to match the name set in the step 2
5. run `yarn dev` to see the live demo or run `yarn build` to build the hook and the example
